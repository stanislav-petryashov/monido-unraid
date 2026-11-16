# Monido for Unraid

The [Community Applications](https://ca.unraid.net) template for [Monido](https://github.com/stanislav-petryashov/monido): track your net worth and cash flow, on your own or as a family. Self-hosted, entered by hand, no bank connections; an optional AI advisor through Claude.

- **Install:** Apps → search "Monido" → Install. Open the WebUI within 15 minutes of the first start and set the family password.
- **Data:** `/mnt/user/appdata/monido` (the SQLite database). Back it up with the rest of your appdata.
- **Permissions:** the container runs as `PUID`/`PGID` (default 99/100, Unraid's `nobody:users`), so the files in appdata belong to the share's usual owner.
- **Updates:** the template follows `ghcr.io/stanislav-petryashov/monido:latest`; update the container from the Docker tab.
- **Docs and support:** [monido.dev](https://monido.dev), the [deployment guide](https://github.com/stanislav-petryashov/monido/blob/master/docs/deploy-docker.md) and the [issues](https://github.com/stanislav-petryashov/monido/issues).

Licensed under MIT, like Monido.
