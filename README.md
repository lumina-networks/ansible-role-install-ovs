# Ansible Role: OVS

An Ansible Role that installs OpenVSwitch with minor modification to allow more Flows on RHEL/CentOS, and Debian/Ubuntu.

## Requirements

Ansible 2.x

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    ovs_version: 2.8.1
    MAX_MPLS: 10


## Dependencies

None.

## Example Playbook

    - hosts: mininet
      roles:
        - ansible-role-install-ovs


## License

MIT

## Author Information

This role was created in 2018 by Darin Sikanic
