# StackSpan

Cloudflare Pages static site for stackspan.co -- foot health, bunions, and minimalist footwear guides.

## Local preview

    npm install
    npm run dev
 
## Deploy

Build output directory: public. Run npm run deploy after Wrangler auth, or connect GitHub in the Cloudflare Pages dashboard.

Update /go/* links in public/_redirects when offers change.

Tailwind CSS loads via CDN on content pages. No secrets in this repo.
