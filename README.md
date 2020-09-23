# ansible-role-baseline

![GitHub](https://img.shields.io/github/license/jam82/ansible-role-baseline) [![Build Status](https://travis-ci.org/jam82/ansible-role-baseline.svg?branch=master)](https://travis-ci.org/jam82/ansible-role-baseline)

**Ansible role for bootstrapping a machine for configuration by ansible.**

## Supported Platforms

- Alpine 3.11, 3.12
- Archlinux
- CentOS 7, 8
- Debian 9, 10
- Fedora 31, 32
- Ubuntu 18.04, 20.04

## Requirements

Ansible 2.8 or higher is recommended.

## Variables

None.

## Dependencies

None.

## Example Playbook

```yaml
---
# role: ansible-role-baseline
# file: site.yml

- hosts: all
  become: true
  gather_facts: false
  roles:
    - role: ansible-role-baseline
```

## License and Author

- Author:: [jam82](https://github.com/jam82/)
- Copyright:: 2020, [jam82](https://github.com/jam82/)

Licensed under [MIT License](https://opensource.org/licenses/MIT).
See [LICENSE](https://github.com/jam82/ansible-role-baseline/blob/master/LICENSE) file in repository.

## References

- [Ansible Docs](https://docs.ansible.com/)
