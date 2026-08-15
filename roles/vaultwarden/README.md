---
# clone1.services vaultwarden Role

Role to install and configure vaultwarden user and user service.

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
  vars:
      vaultwarden_admin_token: "your argon admin token"
      vaultwarden_domain: vw.example.com
      vaultwarden_public_key: "ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAdIPglhRboPP5m4f0yz/olK27ZArPy1GGHrilJLtmy6aR root@vmm.example.com"
  roles:
    - vaultwarden
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
