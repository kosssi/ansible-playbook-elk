# ansible-playbook-elk

[![License](https://img.shields.io/badge/License-MIT%20License-blue.svg)](https://raw.githubusercontent.com/kosssi/ansible-playbook-elk/master/LICENSE)
[![Build Status](https://travis-ci.org/kosssi/ansible-playbook-elk.svg?branch=master)](https://travis-ci.org/kosssi/ansible-playbook-elk)

Installation of the Elasticsearch ELK Stack - that is, Elasticsearch, Logstash, and Kibana.


## Requirements

Software:

 - Ansible 1.9.1

Roles:

    ansible-galaxy install -r requirements.txt


## roles

 - [x] java
 - [ ] Elasticsearch
 - [ ] Logstash
 - [ ] Kibana
 - [ ] nginx


## Tests

| Family | Distribution | Version | Test Status |
|:-:|:-:|:-:|:-:|
| Debian | Debian  | Jessie  | [![x86_64](http://img.shields.io/badge/x86_64-passed-006400.svg)](#) |
| Debian | Debian  | Wheezy  | [![x86_64](http://img.shields.io/badge/x86_64-n/a-cccccc.svg)](#) |
| Debian | Ubuntu  | Precise | [![x86_64](http://img.shields.io/badge/x86_64-n/a-cccccc.svg)](#) |
| Debian | Ubuntu  | Trusty  | [![x86_64](http://img.shields.io/badge/x86_64-n/a-cccccc.svg)](#) |
| Debian | Ubuntu  | Vivid   | [![x86_64](http://img.shields.io/badge/x86_64-n/a-cccccc.svg)](#) |
| RedHat | CentOS  | 6.4     | [![x86_64](http://img.shields.io/badge/x86_64-n/a-cccccc.svg)](#) |
| RedHat | CentOS  | 6.6     | [![x86_64](http://img.shields.io/badge/x86_64-n/a-cccccc.svg)](#) |
| RedHat | Centos  | 7       | [![x86_64](http://img.shields.io/badge/x86_64-n/a-cccccc.svg)](#) |
| RedHat | Fedora  | 20      | [![x86_64](http://img.shields.io/badge/x86_64-n/a-cccccc.svg)](#) |
| RedHat | Fedora  | 21      | [![x86_64](http://img.shields.io/badge/x86_64-n/a-cccccc.svg)](#) |

## Links

 - Thanks Pedro Salgado for [ansible test tool](https://github.com/ansiblebit/primogen).
 - Thanks Mitchell Anicas for [tutorial](https://www.digitalocean.com/community/tutorials/how-to-install-elasticsearch-logstash-and-kibana-4-on-ubuntu-14-04).
