# Evakuator Pyatykhatky

Static one-page site for SEO and GEO. No build step. All files are in `public/`.

Before publishing, replace `your-domain.com` with the real domain (macOS):

    grep -rl your-domain.com public | xargs sed -i '' 's#your-domain.com#REAL-DOMAIN#g'

Cloudflare settings: Build command empty, Deploy command `npx wrangler deploy`.
Pages (legacy) settings: Build command empty, Output directory `public`.
