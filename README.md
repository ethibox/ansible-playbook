# Ansible playbook

> Ansible playbook for debian/ubuntu

## 📦 Usage

```bash
git clone https://github.com/ethibox/ansible-playbook
ansible-galaxy collection install devsec.hardening
ansible-playbook playbook.yml -u <user> -i <host>,
```

To open additional ports (host and Docker containers):

```bash
ansible-playbook playbook.yml -u <user> -i <host>, -e allowed_ports=80,443,8080
```

## 📜 License

This project is licensed under the GNU GPL v3.0 - see the [LICENSE.txt](https://raw.githubusercontent.com/ethibox/ansible-playbook/master/LICENSE.txt) file for details.

**Free Software, Hell Yeah!**
