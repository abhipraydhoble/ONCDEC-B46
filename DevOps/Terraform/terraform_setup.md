<img width="1902" height="857" alt="image" src="https://github.com/user-attachments/assets/c7cd6b57-14d0-48bb-9811-7894829a9217" />
<img width="1140" height="817" alt="image" src="https://github.com/user-attachments/assets/3b804b20-f50f-4a1b-a474-2990168d15dc" />

<img width="1907" height="952" alt="image" src="https://github.com/user-attachments/assets/fd3cf192-0673-4b6c-ba2a-745949d6dc67" />
<img width="407" height="641" alt="image" src="https://github.com/user-attachments/assets/b790e017-7987-476e-838e-5d78a3e71a01" />
<img width="1900" height="742" alt="image" src="https://github.com/user-attachments/assets/66ae5bda-fec9-47ef-a108-c6b1838b1ef9" />
<img width="1281" height="677" alt="image" src="https://github.com/user-attachments/assets/7d067376-97fa-4fa9-ae8b-d0f1efe3fd63" />
<img width="1907" height="841" alt="image" src="https://github.com/user-attachments/assets/8efba381-80a3-45be-9a80-ecdaf0bb81ab" />


# Terraform Installation

````
sudo apt update
````

````
wget -O - https://apt.releases.hashicorp.com/gpg | sudo gpg --dearmor -o /usr/share/keyrings/hashicorp-archive-keyring.gpg
echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(grep -oP '(?<=UBUNTU_CODENAME=).*' /etc/os-release || lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list
sudo apt update && sudo apt install terraform -y
````

````
terraform --version
````
# AWS ClI Installation
````
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install
````

````
aws --version
````
