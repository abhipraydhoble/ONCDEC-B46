## launch two instances (ubuntu) 
## create ssh keypair
````
ssh-keygen
````

## copy public key And paste to worker node .ssh/authorized_keys file

**Install ansible on master node**
  
````
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible -y
````
````
ansible --version
````
### set up inventory file

````
sudo nano /etc/ansible/hosts
private-ip of worker nodes
````

### edit ansible.cfg

````
[defaults]
inventory = hosts
host_key_checking = False
````


### ping all nodes to test connection
````
ansible all -m ping
````

````
- hosts: all
  become: yes
  tasks:

    - name: update
      apt: update_cache=yes

    - name: Install Nginx
      apt: name=nginx state=latest

      notify:
        - restart nginx

  handlers:
    - name: restart nginx
      service: name=nginx state=reloaded
````
### run playbook
````
ansible-playbook nginx.yaml
````


