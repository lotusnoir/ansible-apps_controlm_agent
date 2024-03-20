# ansible-apps_controlm_agent

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_controlm_agent-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_controlm_agent)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_controlm_agent.svg)](https://github.com/lotusnoir/ansible-apps_controlm_agent/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_controlm_agent?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_controlm_agent)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_controlm_agent)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/apps_controlm_agent)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Description](#description)
- [Requirements](#requirements)
- [Role variables](#role-variables)
- [Examples](#examples)
- [License](#license)
- [Author Information](#author-information)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Description

Install anc configure BMC control-M agent in order to launch cron tasks
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_controlm_agent
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_controlm_agent


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
