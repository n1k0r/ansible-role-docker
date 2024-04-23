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
    userland-proxy: false
```
