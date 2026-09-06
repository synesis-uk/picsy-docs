# PICSy documentation

This repository contains the user documentation published at [docs.picsy.uk](https://docs.picsy.uk). It is a separate repository from the PICSy application, so documentation work can be developed and reviewed without changing the app.

## Local development

To use `http://docs.picsy.local` with the existing local Traefik proxy, add
`127.0.0.1 docs.picsy.local` to your Windows hosts file, then run:

```bash
docker compose up -d
```

The first start installs dependencies and prepares the Mintlify preview. Follow
startup with `docker compose logs -f docs`. Edits reload automatically. Stop the
preview with `docker compose down`. The external Docker network `proxy` and
Traefik must already be running.

Alternatively, run the preview directly:

You need Node.js and npm.

```bash
npm install
npm run dev
```

The local preview is normally available at `http://localhost:3000`.

## Checks

```bash
npm run check:links
```

Before opening a pull request, also read [CONTRIBUTING.md](CONTRIBUTING.md).

## Publishing

Mintlify publishes changes from the default branch. Pull requests can be reviewed using Mintlify's preview deployment before they are merged.
