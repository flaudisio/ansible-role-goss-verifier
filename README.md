# Ansible Role: Goss Verifier

Ansible role to install and run Goss as a [Molecule verifier][molecule-verifier].

[molecule-verifier]: https://molecule.readthedocs.io/en/stable/configuration.html#goss

## Requirements

None.

## Role Variables

This is a non-exhaustive list of the role variables. Please see the file [`defaults/main.yml`](defaults/main.yml)
for more details.

```yaml
goss_version: v0.3.6
```

## Dependencies

None.

## Example Playbook

```yaml
# <role_dir>/molecule/default/verify.yml
---
- name: Verify
  hosts: all
  become: true

  roles:
    - role: goss
      vars:
        goss_version: v0.3.6 # Optional!
```

## License

[MIT](LICENSE).
