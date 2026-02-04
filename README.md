# Resume

https://sanfrancrisko.github.io/resume/

## Deploy key setup

This repo publishes to `sanfrancrisko/sanfrancrisko.github.io` via GitHub Actions.

1) Generate a deploy key (public/private).
2) Add the public key to `sanfrancrisko/sanfrancrisko.github.io` Deploy keys with write access.
3) Add the private key to this repo as the `ACTIONS_DEPLOY_KEY` secret.

## Node version

Local and CI use `.nvmrc` (Node 17).
