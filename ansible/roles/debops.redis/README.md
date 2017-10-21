## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) redis

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-redis.svg?style=flat)](https://travis-ci.org/debops/ansible-redis)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--redis-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-redis/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops.redis-660198.svg?style=flat)](https://galaxy.ansible.com/debops/redis)


The `debops.redis` role allows you to easily setup infrastructure capable of
running and managing 1 or more Redis servers. It is completely self healing
with Redis Sentinel and supports replication seamlessly.

### Installation

This role requires at least Ansible `v2.0.0`. To install it, run:

```Shell
ansible-galaxy install debops.redis
```

### Documentation

More information about `debops.redis` can be found in the
[official debops.redis documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-redis/docs/).


### Role dependencies

- `debops.secret`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- Nick Janetakis | [e-mail](mailto:nick.janetakis@gmail.com) | [Twitter](https://twitter.com/nickjanetakis) | [GitHub](https://github.com/nickjj)
- Maciej Delmanowski (maintainer) | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPL-3.0](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps](https://debops.org/). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).