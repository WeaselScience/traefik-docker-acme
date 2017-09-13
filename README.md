Run traefik as you usually would. Place the containers in the same user-defined bridge network and add at least the following labels to your targets:

`traefik.enable` = `true`

`traefik.frontend.rule` = `Host:my.website.com`

`traefik.port` = `80`
