Ansible playbooks for setting up my Fedora dev machine.

Inspired by and heavily borrowed from:
    https://sudo-science.com/using-ansible-to-set-up-vim/
    https://fedoramagazine.org/using-ansible-setup-workstation/
    https://github.com/docent-net/fedora-desktop-ansible

Make a hosts file (example provided at `example.host.file`) and call the main playbook like this:
```
ansible-playbook -i hosts dev_config.yml
```
