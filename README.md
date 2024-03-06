# The Workstation Initializer
An ansible-based tool to maintain my workstation(s) configured with **Infrastructure as Code** practices.

## Disclaimer
This is a WIP and it has been crafted with my workflows and preferences in mind. You may use it as an inspiration for your projects but take in account that this could break your machine.

## Requirements
* ansible
* git
* curl
* Ubuntu (22.04 or higher?)

## How to run

```shell
ansible-galaxy install -r requirements.yaml
ansible-playbook playbooks/basic.yaml -K
```
