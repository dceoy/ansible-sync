ansible-sync
============

Ansible playbook for data sync and Slack notification

Setup
-----

```sh
$ git clone https://github.com/dceoy/ansible-sync.git
$ cd ansible-sync
$ cp example_hosts hosts
$ cp example_sync.yml sync.yml
$ vim hosts       # => edit
$ vim sync.yml    # => edit
```

Usage
-----

Sync targets in vars.

```sh
$ ansible-playbook -i hosts sync.yml
```
