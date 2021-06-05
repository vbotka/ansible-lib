# ansible_lib

[![quality](https://img.shields.io/ansible/quality/39556)](https://galaxy.ansible.com/vbotka/ansible_lib)[![Build Status](https://travis-ci.org/vbotka/ansible-lib.svg?branch=master)](https://travis-ci.org/vbotka/ansible-lib)

[Ansible role.](https://galaxy.ansible.com/vbotka/ansible_lib/) Library of Ansible tasks.

Feel free to [share your feedback and report issues](https://github.com/vbotka/ansible-lib/issues).

[Contributions are welcome](https://github.com/firstcontributions/first-contributions).


## Description

This role is a collection of independent tasks. The purpose is providing a library of reusable tasks
which can be included in playbooks and other roles, e.g.

```
       - name: Create groups of reachable and unreachable hosts.
         include_role:
           name: vbotka.ansible_lib
           tasks_from: al_hosts_reachable
```

See the comments in the tasks.


## Requirements and dependencies

### Collections

* community.general


## License

[![license](https://img.shields.io/badge/license-BSD-red.svg)](https://www.freebsd.org/doc/en/articles/bsdl-gpl/article.html)


## Author Information

[Vladimir Botka](https://botka.link)
