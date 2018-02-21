# Ansible Role: prometheus-postgresql-exporter

An Ansible role that installs Prometheus PostgreSQL Exporter on Ubuntu|Debian|Redhat-based machines with systemd|Upstart|sysvinit.

## Requirements

All needed packages will be installed with this role.

## Role Variables

Available variables are listed below, along with default values:
```yaml
```
## Dependencies

- UnderGreen.prometheus-exporters-common

## Example Playbook
```yaml
- hosts: postgresql
  roles:
    - prometheus-postgresql-exporter
```
## License

GPLv2
