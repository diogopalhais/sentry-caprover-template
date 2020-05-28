# sentry-caprover-template

### Configurations after deploy

Enter main container
```bash
docker exec -it --user root <containerID> bash
```

Get the setting from config
```bash
sentry config get system.url-prefix
```

Update the setting to new value
```bash
sentry config set system.url-prefix https://app.domain.com
```

Settings to update:
- mail.from
- mail.host
- mail.password
- mail.port:
- mail.use-tls
- mail.username
- system.admin-email
- system.url-prefix
