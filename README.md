# Ansible Runbook: ping_internet

[![Build](https://github.com/dcjulian29/ansible-runbook-ping_internet/actions/workflows/build.yml/badge.svg)](https://github.com/dcjulian29/ansible-runbook-ping_internet/actions/workflows/build.yml) [![Release](https://github.com/dcjulian29/ansible-runbook-ping_internet/actions/workflows/release.yml/badge.svg)](https://github.com/dcjulian29/ansible-runbook-ping_internet/actions/workflows/release.yml) [![GitHub Release](https://img.shields.io/github/v/release/dcjulian29/ansible-runbook-ping_internet)](https://github.com/dcjulian29/ansible-runbook-ping_internet/releases) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-runbook-ping_internet.svg)](https://github.com/dcjulian29/ansible-runbook-ping_internet/issues)

This is an Ansible runbook that will validate a host can ping another host on the Internet.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
collections:
- name: dcjulian29.ping_internet
  type: git
  source: https://github.com/dcjulian29/ansible-runbook-ping_internet.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy collection install -r requirements.yml
```

To excute the runbook:

```shell
ansible-playbook dcjulian29.ping_internet.runbook.yml
```
