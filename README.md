# snipe-it-kickstart

[Snipe-IT](https://snipeitapp.com/) is an open source asset management tool. Snipe-IT Kickstart is
an opinionated implementation of running Snipe-IT in specifc ways.

## Caution

These configuration files are *not production ready*. They are designed to be a *guide* to follow. The
configurations are inherently insecure and you should replace example passwords displayed in favor
of your own unique passwords and `APP_KEY`

## Kickstart things

Want to get up and going *fast*?

Clone this repository
`cd docker`
`docker-compose up`

Add `127.0.0.1    snipeit.test` to your `/etc/hosts`/`C:\Windows\system32\drivers\etc\hosts` file.

Open `http://snipeit.test:8000` in a browser.
