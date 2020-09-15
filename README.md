# Ansible role: vim
Configure text editor for convenience.

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `vim_pkgs`: list of (`name`: `url`) pairs of git repos to clone 
  under `/etc/vim/pack/`

## Dependencies
None.

## Example Playbook

```
- hosts: all
  roles:
    - { role: ho-ansible.vim }
```

## License
MIT

## Author Information
Sean Ho, https://github.com/ho-ansible/
