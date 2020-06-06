# tobias_richter.rrdcached

[![Build Status](https://travis-ci.org/tobias-richter/ansible-rrdcached.svg?branch=master)](https://travis-ci.org/tobias-richter/ansible-rrdcached)

This roles compiles/setups rrdtool and rrdcached on Debian/Ubuntu systems for the usage with librenms.

## Requirements

This role requires Ansible 2.7 or higher.

## Role Variables

See [defaults/main.yml](defaults/main.yml) for the documented role variables.

## Example Playbook

This playbook compiles/setups rrdcached in version 1.7.2.

    - hosts: rrdcached
	  roles:
	    - role: tobias_richter.rrdcached
	      rrdcached_version: 1.7.2