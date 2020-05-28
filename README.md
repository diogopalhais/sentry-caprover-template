# sentry-caprover-template

### Configurations after deploy

Enter main container
`docker exec -it --user root <containerID> bash`

Get the seeting from config
`sentry config get system.url-prefix`

Update the setting to new value
`sentry config set system.url-prefix https://app.domain.com`
