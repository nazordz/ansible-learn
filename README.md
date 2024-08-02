
# Vagrant
Boot 2 nodes with vagrant
```bash
$ vagrant up
```

# Ansible examples
ping 2 nodes in file `hosts` and in `k8s` group.
```bash
$ ansible -i hosts k8s -m ping
```

playbook example
```bash
$ ansible-playbook playbooks/update-playbook.yaml
```

[Learn more](https://github.dev/tresnax/tutorial-ansible?tab=readme-ov-file)