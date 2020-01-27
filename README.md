<p><img src="https://pbs.twimg.com/media/CcZdW37UcAA9DZz.png" alt="traefik logo" title="traefik" align="right" height="60" /></p>

Ansible Role Traefik
=========
[![Galaxy Role](https://img.shields.io/ansible/role/46109.svg)](https://galaxy.ansible.com/0x0I/traefik)
[![Downloads](https://img.shields.io/ansible/role/d/46109.svg)](https://galaxy.ansible.com/0x0I/traefik)
[![Build Status](https://travis-ci.org/0x0I/ansible-role-traefik.svg?branch=master)](https://travis-ci.org/0x0I/ansible-role-traefik)

**Table of Contents**
  - [Supported Platforms](#supported-platforms)
  - [Requirements](#requirements)
  - [Role Variables](#role-variables)
      - [Install](#install)
      - [Config](#config)
      - [Launch](#launch)
      - [Uninstall](#uninstall)
  - [Dependencies](#dependencies)
  - [Example Playbook](#example-playbook)
  - [License](#license)
  - [Author Information](#author-information)

Ansible role that installs and configures Traefik: a dynamic service load-balancer and edge router

##### Supported Platforms:
```
* Debian
* Redhat(CentOS/Fedora)
* Ubuntu
```

Requirements
------------

Requires the unzip/gtar utility to be installed on the target host. See ansible unarchive module notes for details.

Role Variables
--------------
Variables are available and organized according to the following software & machine provisioning stages:
* _install_
* _config_
* _launch_
* _uninstall_

#### Install

...*description of installation related vars*...

#### Config

...*description of configuration related vars*...

#### Launch

...*description of service launch related vars*...

#### Uninstall

...*description of uninstallation related vars*...

Dependencies
------------

...*list dependencies*...

Example Playbook
----------------
default example:
```
- hosts: all
  roles:
  - role: 0xOI.<role>
```

License
-------

Apache, BSD, MIT

Author Information
------------------

This role was created in 2019 by O1.IO.
