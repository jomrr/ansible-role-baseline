# ansible-role-baseline

![GitHub](https://img.shields.io/github/license/jomrr/ansible-role-baseline) ![GitHub last commit](https://img.shields.io/github/last-commit/jomrr/ansible-role-baseline) ![GitHub issues](https://img.shields.io/github/issues-raw/jomrr/ansible-role-baseline) [![Molecule](https://github.com/jomrr/ansible-role-baseline/actions/workflows/molecule.yml/badge.svg)](https://github.com/jomrr/ansible-role-baseline/actions/workflows/molecule.yml)

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

- Author:: [jomrr](https://github.com/jomrr/)
- Copyright:: 2020, [jomrr](https://github.com/jomrr/)

Licensed under [MIT License](https://opensource.org/licenses/MIT).
See [LICENSE](https://github.com/jomrr/ansible-role-baseline/blob/master/LICENSE) file in repository.

## References

- [Ansible Docs](https://docs.ansible.com/)
