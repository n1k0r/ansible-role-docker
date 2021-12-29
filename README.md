# Docker role for Ansible

## Variables

```yaml
docker:
  registry:
    url: registry.gitlab.com
    username: user
    password: account_token_here

  daemon: # default value
    log-driver: local
    userlang-proxy: false
```

Account dictionary is also expected: https://gitlab.com/n1k0r-ansible/roles/master
