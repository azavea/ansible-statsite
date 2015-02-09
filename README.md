# ansible-statsite

An Ansible role to install [Statsite](https://github.com/armon/statsite).

## Role Variables

- `statsite_version` - Statsite version
- `statsite_data_dir` - Home directory for the Statsite system user (default: `/var/lib/statsite`)
- `statsite_log` - Statsite log path (default: `/var/log/statsite.log`)
- `statsite_log_rotate_count` - Statsite log rotation count (default: `5`)
- `statsite_log_rotate_interval` - Statsite log rotation interval (default: `daily`)

## Example Playbook

See the [examples](./examples/) directory.
