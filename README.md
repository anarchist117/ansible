# Install Ansible
```
apt update
apt install software-properties-common
add-apt-repository --yes --update ppa:ansible/ansible
apt install ansible
```

# Check connection
```
ansible all -m ping
```

# Run ansible playbook
```
ansible-playbook -i inventory update.yml
```

# Run custom command
```
ansible all -m command -a 'uptime -p'
```

# Documentation
https://docs.ansible.com/ansible/latest/installation_guide/installation_distros.html#installing-ansible-on-ubuntu