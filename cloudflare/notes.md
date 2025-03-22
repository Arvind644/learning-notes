# Cloudflare notes

Use this command before running `npx wrangler login` or '`npx wrangeler deploy` to avoid permission isseues. I have tested it on my wsl2 environment.

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```