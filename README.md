# ansible-apps_vim

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_vim-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_vim)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_vim.svg)](https://github.com/lotusnoir/ansible-apps_vim/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_vim?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_vim)
[![downloads](https://img.shields.io/ansible/role/d/56925)](https://galaxy.ansible.com/lotusnoir/apps_vim)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56925)](https://galaxy.ansible.com/lotusnoir/apps_vim)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Install and configure vimrc

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_vim
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_vim


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

