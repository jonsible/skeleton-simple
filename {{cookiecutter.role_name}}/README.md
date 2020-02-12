# {{ cookiecutter._organization }}.{{ cookiecutter.role_name }}

[![Build Status](https://travis-ci.com/jonsible/ansible-role-{{ cookiecutter.role_name }}.svg?branch=master)](https://travis-ci.com/jonsible/ansible-role-{{ cookiecutter.role_name }})
[![Galaxy](https://img.shields.io/badge/galaxy-{{ cookiecutter._organization }}.{{ cookiecutter.role_name }}-blue.svg)](https://galaxy.ansible.com/{{ cookiecutter._organization }}/{{ cookiecutter.role_name }}/)

{{ cookiecutter.description }}

## Requirements

None.

## Role Variables

### Default usage

As default {{ cookiecutter.role_name }} is installed and running.
If you want to adapt this to your needs look at the [Advanced usage](#advanced-usage) section.

### Advanced usage

For more advanced usage the following variables are available:
```yaml
# see defaults/main.yml
```

## Dependencies

None

## Example Playbook

Install {{ cookiecutter.role_name }} with the default settings
```yaml
- hosts: all
  roles:
     - role: {{ cookiecutter._organization }}.{{ cookiecutter.role_name }}
```

## License

GPL-3.0-or-later

## Author Information

This role was created in {{ cookiecutter._year }} by [{{ cookiecutter._author }}].
