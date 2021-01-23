# ansible-role-prometheus
Ansible role. Install and configure Prometheus.

Prometheus is a montoring & alerting tool: https://prometheus.io/

Prometheus IHM is accessible with: http://prometheus.ansible-test.local

## Installation

For now, only docker-compose install is able.


## Run tests

`ansible-playbook -i tests/hosts tests/test.yml --limit localhost`

## Configuration

Check `defaults/main.yml`

## Examples

Check `tests/test.yml`.