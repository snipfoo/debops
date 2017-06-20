## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) mariadb_server

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-mariadb_server.svg?style=flat)](https://travis-ci.org/debops/ansible-mariadb_server)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--mariadb__server-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-mariadb_server/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops.mariadb_server-660198.svg?style=flat)](https://galaxy.ansible.com/debops/mariadb_server)


[MariaDB](http://mariadb.org/) is a popular relational SQL database that
was forked from MySQL server. Ansible roles `debops.mariadb` and
`debops.mariadb_server` allow you to manage a MariaDB server and / or
access it remotely from other hosts.

`debops.mariadb_server` role is the "server" part - it installs
`mariadb-server` Debian package, and configures access to the database from
local `root` account. After that, you can use `debops.mariadb` role to
manage databases and user accounts on the server.

### Installation

This role requires at least Ansible `v1.8.0`. To install it, run:

```Shell
ansible-galaxy install debops.mariadb_server
```

### Documentation

More information about `debops.mariadb_server` can be found in the
[official debops.mariadb_server documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-mariadb_server/docs/).


### Role dependencies

- `debops.secret`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- Maciej Delmanowski (maintainer) | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPL-3.0](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps](https://debops.org/). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
