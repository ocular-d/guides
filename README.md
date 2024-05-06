# Guides

Monorepo for all documentation guides using `pnpm`.

## Development setup

### Nix

- If you have `Nix` and `direnv` installed, you know the drill.
- If you have `Nix` installed without  `direnv` use `nix develop`.

### Without Nix

Make sure to have `Node` and `pnpm` installed, see the [official documentation](https://pnpm.io/installation).

## Getting started

Clone your fork and run `pnpm` in the root for the repository.

## Notes

Change into the directory of the guide you want under `apps` and do:

`pnpm start`  
Starts the development server.

`pnpm build`  
Bundles your website into static files for production.

`pnpm serve`  
Serves the built website locally.

`pnpm deploy`  
Publishes the website to GitHub pages.

We recommend that you begin by typing (for example):

`cd apps/editorial`  
`pnpm start`
