# NexusAI

Static HTML site. Deploy the `public/` directory to Cloudflare Pages. No build command is needed.

All page assets are in `public/assets/`.

Live site: https://nexusai-3ld.pages.dev/

To publish later changes after pushing to GitHub, run:

```sh
npx wrangler pages deploy public --project-name nexusai --branch main
```
