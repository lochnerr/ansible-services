---
# clone1.services selinux_tpm2setup Role

Role to fix SELinux permissions error resulting in the systemd-tpm2-setup service failing on startup.

## Requirements

This role has no rquirements and can stand alone.

## Role Variables

All variables with default values are defined in defaults/main.yml.  All required, and most other optional, variables are documented in meta/argument_specs.yml.  No variables are defined in vars/main.yml.

## Dependencies

No dependencies.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- name: Execute tasks on servers
  hosts: servers
  roles:
    - role: clone1.services.selinux_tpm2setup
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
