# svelte-kit on cloudflare workers

[install wrangler](https://developers.cloudflare.com/workers/cli-wrangler/install-update) and configure `wrangler.toml.init` with your `account_id` and rename to `wrangler.toml`.

```
npm i
npm run dev
```
to develop locally then
```
npm run build
wrangler publish
```
when you're ready to deploy.
