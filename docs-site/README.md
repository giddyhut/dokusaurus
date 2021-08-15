# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

## Installation

```console
~~yarn install~~
npx @docusaurus/init@latest init docs-site classic
```

## Local Development

```console
~~yarn start~~
npm run start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```console
~~yarn build~~
npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

```console
GIT_USER=<Your GitHub username> USE_SSH=true yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

## Netlify deployment
- Base directory: docs-site
- Build command: npm run build
- Publish directory: docs-site/build

Online site: https://nostalgic-swartz-d1134f.netlify.app/