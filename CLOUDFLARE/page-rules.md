# DASH -> DOMAIN -> PAGE RULES

ie: https://dash.cloudflare.com/.../YOUR-DOMAIN.TLD/page-rules

## Let's Let's Encrypt pass

1. Create a Page Rule: `*.YOURDOMAIN.TLD/.well-known/acme-challenge/*`
2. Then the settings are: `SSL: OFF`
3. Order: `First`