# WordPress
Automate WordPress Setup 

```
git clone https://github.com/MiteshShah/WordPress.git
cd WordPress
cp -av config.example ~/.ssh/config

# Update IP Address and Dont forget to copy ssh keys on that remote servers
vim ~/.ssh/config

# Lets Play Ansible Playbook
ansible-playbook playbook.yml -i hosts
```
