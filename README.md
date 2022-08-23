# Ansible Role : regenerate_ssh_host_keys

[![CI](https://github.com/glillico/ansible-role-regenerate_ssh_host_keys/workflows/CI/badge.svg)](https://github.com/glillico/ansible-role-regenerate_ssh_host_keys/actions?query=workflow%3ACI)

This role creates a service that regenerates the sshd host keys when the server is booted.  Once run the service is disabled.

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: servers
      vars_files:
        - vars/main.yml
      roles:
        - glillico.regenerate_ssh_host_keys

## License

MIT

## Author Information

This role was created in 2021 by Graham Lillico.
