# ansible-role-baseline

![GitHub](https://img.shields.io/github/license/jam82/ansible-role-baseline) ![GitHub last commit](https://img.shields.io/github/last-commit/jam82/ansible-role-baseline) ![GitHub issues](https://img.shields.io/github/issues-raw/jam82/ansible-role-baseline) [![Molecule](https://github.com/jam82/ansible-role-baseline/actions/workflows/molecule.yml/badge.svg)](https://github.com/jam82/ansible-role-baseline/actions/workflows/molecule.yml)

**Ansible role for bootstrapping a machine for configuration by ansible.**

## Supported Platforms

- Almalinux
- Alpine
- Archlinux
- CentOS
- Debian
- Fedora
- OpenSuse Leap
- Oracle
- Ubuntu

## Requirements

Ansible 2.9 or higher is recommended.

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
