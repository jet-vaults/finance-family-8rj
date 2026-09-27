# finance-family-8rj

## Status

| | |
|---|---|
| **Domain** | `https://preview.finance-family.co.il` |
| **Pages URL** | `https://finance-family-8rj.pages.dev` |
| **Storage mode** | `Standard` (`standard`) |
| **Storage account** | `jetvaults` |
| **Public storage** | `https://jetvaults.blob.core.windows.net/finance-family-8rj/` |
| **Private storage** | `https://jetvaults.blob.core.windows.net/finance-family-8rj-private/` |
| **Public container** | `finance-family-8rj` |
| **Private container** | `finance-family-8rj-private` |
| **Activated** | Yes |

## CNAME

Create this DNS record with your DNS provider:

| Type | Name | Value |
|------|------|-------|
| CNAME | `preview.finance-family.co.il` | `finance-family-8rj.pages.dev` |

After DNS propagates, Cloudflare Pages will validate the custom domain and issue SSL. You do not need to run the Activate Site workflow for CNAME sites.

## Development

Edit files in `wwwroot/` and push to `main` - Cloudflare Pages auto-deploys.

Only the `wwwroot/` directory is served. Everything else stays in the repo.
