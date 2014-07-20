# ansible-role-phpstorm

[![Build Status](https://travis-ci.org/kosssi/ansible-role-phpstorm.svg?branch=master)](https://travis-ci.org/kosssi/ansible-role-phpstorm)

Ansible role for install [phpStorm](http://www.jetbrains.com/phpstorm/).

## Role Defaults Variables

    phpstorm_version: 7.1.3
    phpstorm_install_dir: /opt
    phpstorm_bin: /usr/local/bin/phpstorm

## Example Playbook

    roles:
      - { role: kosssi.composer }

## License

MIT
