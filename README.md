# ansibleDockerInstall
## Prerequisites:
1. Ansible available
2. Ubuntu VMs

## Input/Parameters:
1. Make sure the Ansible hosts file is ready
2. Make sure vars/params.yml is ready

## Use the ansible playbook to:
1. Install mandatory packages for Docker
2. Add Docker key to Apt
3. Add Docker repo to Apt
4. Add Docker Users to docker group

## Run the playbook:
ansible-playbook -i hosts pbInstallDocker.yml

## Tests:
Playbook(s) has/have been tested against:
- Ubuntu Bionic
- ansible 2.9.5

## Improvement:
