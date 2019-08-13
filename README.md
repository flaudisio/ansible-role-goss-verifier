# Ansible Role: Goss

Ansible role for Goss installation.

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
---
- hosts: all
  roles:
    - role: goss
      vars:
        goss_version: v0.3.6
```

## License

[MIT](LICENSE).
