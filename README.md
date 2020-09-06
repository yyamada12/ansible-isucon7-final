# ansible-isucon7-final

## Overview

Ansible playbook for [ISUCON7-final](http://isucon.net/archives/50949022.html)
benchmarker および開発環境を構築するための ansible-playbook です

## Requirement

- Ubuntu 16.04

## Usage

image:

```
apt-get update
apt-get install -y ansible git
git clone https://github.com/yyamada12/ansible-isucon7-final.git
cd ansible-isucon7-final
ansible-playbook image.yml -i local
```

bench:

```
apt-get update
apt-get install -y ansible git
git clone https://github.com/yyamada12/ansible-isucon7-final.git
cd ansible-isucon7-final
ansible-playbook bench.yml -i local
```
