# ansible-apps_vim

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_vim-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_vim)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_vim.svg)](https://github.com/lotusnoir/ansible-apps_vim/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_vim?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/56111)](https://galaxy.ansible.com/lotusnoir/apps_vim)
![Ansible Quality Score](https://img.shields.io/ansible/quality/56111)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)


Configure vimrc using ansible.

## Requirements

none

## Role variables

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|

## Examples

        ---
        - hosts: apps_vim
          become: yes
          become_method: sudo
          gather_facts: yes
          roles:
            - role: ansible-apps_vim
          environment:
            http_proxy: "{{ http_proxy }}"
            https_proxy: "{{ https_proxy }}"
            no_proxy: "{{ no_proxy }}

## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

