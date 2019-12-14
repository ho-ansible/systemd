# Ansible role: systemd
General config of systemd.

+ handler: daemon-reload

## Requirements
Only tested on Debian stable, for now.

## Role Variables

## Handlers
+ `daemon-reload`: notify this handler after modifying any
  systemd unit files, including drop-in config

## Dependencies
None.

## License
MIT

## Author Information
Sean Ho, https://github.com/ho-ansible/
