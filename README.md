# [Catena](https://github.com/alysoid/catena) Ansible Role: hostname

Manage hostname and `/etc/hosts` file accordingly via Ansible.

## Role default variables

| Variable           | Default              | Info                      |
| ------------------ | -------------------- | ------------------------- |
| `hostname`         | `{{ ansible_fqdn }}` | System/Server hostname    |
| `hostname_aliases` | `[]`                 | Array of hostname aliases |
