# Setup

## Ansible control node
- Ensure ansible 2.9.x is installed
- Clone this repository in any directory you choose
- Configure the target host, username and desired http_port in the hosts/target file

## Target host
- Ensure you can elevate privileges from the user you are connected 

## Using the playbook
- Navigate to the location of deploy.yml
- Execute: ansible-playbook deploy.yml -i hosts
