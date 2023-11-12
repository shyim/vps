# Private server

Manages with docker compose only my VPS. Host OS is Alpine Linux with just Docker installed and auto package updates. [Docker live-restore](https://docs.docker.com/config/containers/live-restore/) allows updating Docker Engine without downtime.

Services:

- [Traefik](https://traefik.io/) for Proxy the Containers
- [Watchtower](https://containrrr.dev/watchtower) auto updates of containers
- [Restic](https://restic.readthedocs.io/en/stable/index.html) for backups
- [Ofelia](https://github.com/mcuadros/ofelia/) for cronjobs, to trigger Restic every day
- [Screego](https://screego.net/) for Screen Sharing at [screen.fos.gg](https://screen.fos.gg)
- [Thelounge](https://thelounge.chat/) IRC Client at [irc.shyim.de](https://irc.shyim.de)
- [Wakapi](https://github.com/muety/wakapi/) Wakatime compatible self-hosted service at [time.fos.gg](https://time.fos.gg)

