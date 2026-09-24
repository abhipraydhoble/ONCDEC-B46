````
resource "aws_vpc" "vnet" {
  cidr_block = "192.168.0.0/16"
  tags = {
    Name = "terraform-vpc"
  }
}

resource "aws_subnet" "pub" {
  vpc_id = aws_vpc.vnet.id
  tags = {
    Name = "public-subnet-tf"
  }
  cidr_block = "192.168.0.0/22"
  availability_zone       = "ap-southeast-1a"
  map_public_ip_on_launch = true
}

resource "aws_internet_gateway" "igw" {
  vpc_id = aws_vpc.vnet.id
  tags = {
    Name = "int-gw"
  }
}

resource "aws_route_table" "rt-1" {
  vpc_id = aws_vpc.vnet.id
  tags = {
    Name = "rt-public"
  } 
  route {
  gateway_id = aws_internet_gateway.igw.id
  cidr_block = "0.0.0.0/0"
  }

}

resource "aws_route_table_association" "connect" {
  route_table_id = aws_route_table.rt-1.id
  subnet_id      = aws_subnet.pub.id
}
````
