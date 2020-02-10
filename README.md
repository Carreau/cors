# cors

Simple proxy to add CORS request for pypi.anaconda.org package index.

Adapted from ryanking13/cors


## Making your own CORS proxy

1. [Learn about Cloudflare Workers](https://workers.cloudflare.com/)
2. Fork this repository
3. Change `accound_id` in [wrangler.toml](./wrangler.toml) to your Account ID
5. `npx wrangler dev`
