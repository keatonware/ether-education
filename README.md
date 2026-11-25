# Ether Education

Clickable prototype of an NCE board-prep platform for student nurse anesthetists. Working name, sample data.

It is one static page (`index.html`) served by GitHub Pages. No build step.

## Adding a custom domain later

1. Buy the domain.
2. In this repository: Settings, Pages, Custom domain. Enter the domain and save. GitHub adds a `CNAME` file here.
3. At the domain registrar, add the DNS records GitHub shows (for an apex domain, four `A` records to GitHub's Pages IPs; for `www`, a `CNAME` record to `keatonware.github.io`).
4. Once the check passes, tick "Enforce HTTPS".
