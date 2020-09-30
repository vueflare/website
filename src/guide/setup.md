## Preparation

This template uses [@cloudflare/wrangler](https://github.com/cloudflare/wrangler) to deploy your app as a Webworker so you need to make sure you have it installed and [configured](https://github.com/cloudflare/wrangler#-config) globally;
```
npm install -g @cloudflare/wrangler
```
Add your `account_id` to `wrangler.toml`. You can find your account_id on the
right sidebar of the Workers or Overview Dashboard. Note: You may need to scroll
down! For more details on finding your account_id click [here](https://developers.cloudflare.com/workers/quickstart/#account-id-and-zone-id).


## Installation

To install we use [create-vueflare-app](https://github.com/vueflare/create-vueflare-app) package to download the template.

If using npm: 

```bash
$ npm init vueflare-app <project-name>
$ cd <project-name>
$ npm install
```

If using Yarn:

```bash
$ yarn create vueflare-app <project-name>
$ cd <project-name>
$ yarn
```
## Preview the project

```
npm run preview
```
or
```
yarn preview
```

## Publish to workers.dev

```
npm run publish
```
or
```
yarn publish
```