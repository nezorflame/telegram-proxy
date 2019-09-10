# telegram-proxy

Configs for a MTProto Telegram proxy behind SSLH.

Inspired by <https://habr.com/ru/post/412779/>

File structure:

- `/opt/mtproxy/docker-compose.yml`
- `/etc/mtproxy.env`
- `/etc/systemd/system/mtproxy.service`
- `/etc/default/sslh`
- `/etc/sslh/sslh.cfg`
- `/etc/systemd/system/multi-user.target.wants/sslh.service`
