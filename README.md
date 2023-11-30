# Postfix Sendgrid

[![CI](https://github.com/jobscore/ansible-role-postfix-sendgrid/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/jobscore/ansible-role-postfix-sendgrid/actions/workflows/ci.yml)

Ansible Role for configuring Postfix as a Sendgrid relay on Ubuntu

## Role Variables

```
postfix_mailname: The hostname to be used by Postfix
sendgrid_user: Your username from Sendgrid. You can use `apikey` as the username if using API keys (recommended)
sendgrid_password: Your password (or API key) from Sendgrid
```

## Example Playbooks

``` yaml
- hosts: servers
  roles:
    - role: jobscore.postfix_sendgrid
```

## License

[MIT](/LICENSE)

Author Information
------------------

This role was created by [Eric Magalhães](https://emagalha.es) while working for [JobScore Inc](https://jobscore.com).
