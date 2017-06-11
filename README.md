[![Build Status](https://travis-ci.org/lifeofguenter/ansible-role-sonarr.svg?branch=master)](https://travis-ci.org/lifeofguenter/ansible-role-sonarr)

# Ansible Role: Sonarr

An Ansible role that installs Sonarr on Debian like systems.

## Requirements

none

## Role Variables

- `sonarr_user: sonarr`

## Dependencies

none

## Example Playbook

    - hosts: media-center
      roles:
        - { role: lifeofguenter.sonarr }

## License

MIT
