# ansible-localhost

Provision localhost using Ansible.

## Install & Run

Fork this exapmle repository on GitHub and make whatever changes you wish to the *my-machine* role.

Then run on the machine you would like to provision:

```sh
sudo apt -y install ansible git
git clone https://github.com/<user>/ansible-localhost
cd ansible-localhost
ansible-playbook -K playbook.yml
```

