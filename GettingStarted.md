## Getting Started

### 1. Create inventory file (inventory/hosts):
[local]
localhost ansible_connection=local

[servers]
server1 ansible_host=192.168.1.10
server2 ansible_host=192.168.1.11

### 2. Test connectivity:
ansible all -m ping -i inventory

### 3. Run playbook:
ansible-playbook -i inventory playbook.yml

## Best Practices

1. Always use version control
2. Keep sensitive data encrypted using ansible-vault
3. Use roles for reusable configurations
4. Test playbooks on staging before production
5. Use tags for selective execution
6. Maintain clear documentation

## Additional Tools

### macOS:
brew install ansible-lint

### Arch Linux:
sudo pacman -S ansible-lint

## Resources

- [Ansible Documentation](https://docs.ansible.com/)
- [Ansible Galaxy](https://galaxy.ansible.com/)
- [Ansible GitHub](https://github.com/ansible/ansible)
