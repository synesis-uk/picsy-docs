# PICSy documentation

This repository contains the user documentation published at [docs.picsy.uk](https://docs.picsy.uk). It is a separate repository from the PICSy application, so documentation work can be developed and reviewed without changing the app.

## Local development

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
