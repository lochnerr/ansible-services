---
# clone1.services gitolite Role

Role to install and configure gitolite.

## Requirements

This role has no rquirements and can stand alone.

## Role Variables

All variables with default values are defined in defaults/main.yml.  All required, and most other optional, variables are documented in meta/argument_specs.yml.  No variables are defined in vars/main.yml.

## Dependencies

No dependencies.

## Example Playbook

```yaml
- name: Execute tasks on servers
  hosts: servers
  roles:
    - gitolite
```

## Role Idempotency

Role Idempotency is True (Idempotent)

## Role Atomicity

Role Atomicity is False (not supported).

## Roll-back capabilities

Roll-back capabilities are not supported.

## License

MIT

## Author Information

The clone1 DevOps Team
