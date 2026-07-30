---
# clone1.services ddclient Role

Role to install and configure ddclient.

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
    - role: clone1.services.ddclient
```

Another way to consume this role would be:

```yaml
- name: Initialize the run role from clone1.services
  hosts: servers
  gather_facts: false
  tasks:
    - name: Trigger invocation of run role
      ansible.builtin.include_role:
        name: clone1.services.ddclient
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
