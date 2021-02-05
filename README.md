# Kali Deploy

* Ansible playbook to deploy common Kali utilities


## Running

```
dnf install ansible -y
ansible-playbook -i "localhost," -c local site.yml
```

If getting an error about python2-dnf, try the following:

```
ansible-playbook -i "localhost," -c local site.yml -e 'ansible_python_interpreter=/usr/bin/python3'
```

## Breakdown

See individual roles under `roles/`
