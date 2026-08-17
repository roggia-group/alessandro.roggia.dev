# alessandro.roggia.dev

Static site served at <https://alessandro.roggia.dev> by the Cloudflare Pages project `roggia-dev-alessandro`.

## Editing

The page is `public/index.html`. It is a single self-contained file — no build
step, no dependencies, no framework.

Push to `main` and Cloudflare deploys it automatically. There is no manual
upload step.

Only `public/` is published. Everything else in this repository, this file
included, stays off the web.

## Infrastructure

The Pages project, its custom domain and its DNS record are managed with
Terraform, not from this repository.
