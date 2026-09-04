# YouSupply landing page

Public coming-soon landing page for [YouSupply](https://yousupply.co.nz).

## GitHub Pages

The site deploys automatically from `main` through GitHub Actions. In GitHub, open **Settings → Pages** and select **GitHub Actions** as the source.

The custom domain is stored in `CNAME`. Configure the apex-domain DNS records shown by GitHub Pages in Cloudflare, then enable HTTPS once GitHub has verified the domain.

The live ordering portal remains separate:

- `yousupply.co.nz` → this landing page
- `cwf.yousupply.co.nz` → YouSupply ordering application through Cloudflare Tunnel

This page contains no secrets, customer data or application credentials.