# ansible-statsite

An Ansible role to install [Statsite](https://github.com/armon/statsite).

## Role Variables

- `statsite_version` - Statsite version
- `statsite_conf_dir` - Statsite configuration directory (default: `/etc/statsite`)
- `statsite_sink_dir` - Statsite sink collection directory (default: `/usr/libexec/statsite`)
- `statsite_data_dir` - Home directory for the Statsite system user (default: `/var/lib/statsite`)
- `statsite_flush_interval` - How often metrics should be flushed to sink in seconds (default: `10`)
- `statsite_stream_cmd` - Stream command to Statsite sink
- `statsite_log` - Statsite log path (default: `/var/log/statsite.log`)
- `statsite_log_rotate_count` - Statsite log rotation count (default: `5`)
- `statsite_log_rotate_interval` - Statsite log rotation interval (default: `daily`)

## Example Playbook

See the [examples](./examples/) directory.
