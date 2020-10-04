# Ansible role: vim
Configure text editor for convenience.

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `vim_pkgs`: list of (`name`: `url`) pairs of git repos to clone 
  under `/etc/vim/pack/`

## Playbooks
+ `main.yml`: apply role
+ `uninstall.yml`: remove. Run before removing config from inventory.

## Dependencies
None.

## License
+ Ansible role licensed [MIT](LICENSE)

## Author Information
+ Ansible role by [Sean Ho](https://github.com/ho-ansible/)
