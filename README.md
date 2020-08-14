# Ansible

Contains ansible playbooks to configure laptop.

It assumes that hosts in inventory runs Fedora or similar. Its is tested using Fedora 32.

# Running

```bash
dnf install git
git clone https://github.com/thiagohdeplima/ansible-for-my-desktop
pip install ansible
ansible-playbook -K play_install.yml
```