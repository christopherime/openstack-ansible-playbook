# openstack-ansible-playbook

## Description

Ansible playbook to deploy OpenStack on a Ubuntu 22.04 machine
This project is "for science" and for training see how it goes.
It is not intended for production use.

## Resources

Based on the following resources:

- <https://docs.openstack.org/devstack/latest/guides/single-machine.html>

## Requirements

- Target machine on Ubuntu, ideally 22.04 I will not test on other versions / distros atm.
- Update the inventory.yml accordingly to your setup

## Usage

- Clone this repo
- run `ansible-playbook -i inventory.yml playbook.yml`
  