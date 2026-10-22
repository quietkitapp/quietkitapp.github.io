# Bookscout Privacy Policy

_Last updated: 2026-10-22_

Bookscout is a browser extension that helps self-publishers research book niches on
Amazon. It is designed so that your research stays on your device.

## What Bookscout reads

- **Amazon pages you open** (search results and product pages on the supported Amazon
  marketplaces) to show research data on top of them.
- **Amazon product pages of the results you are viewing**, fetched in the background at
  a slow rate (one request every 1.5–2 seconds) to read the Best Sellers Rank, page count
  and publication date. These requests go directly from your browser to Amazon, like
  opening the page yourself. Bookscout never crawls pages you did not open, except the
  next results page when you click "Analyze next page".
- **Amazon's search-suggestion service** when you use the keyword explorer, with the
  keywords you type.

## What Bookscout stores

Everything below is stored only in your browser (`chrome.storage.local`) and is never
sent to us or to any third party:

- settings (theme, marketplace, royalty settings, filters)
- a 24-hour cache of product data and a history of Best Sellers Ranks you have seen
- saved niches and their snapshots
- the last search analysis (for the side panel and CSV export)
- your license key, license instance id and license status

You can clear the cache in **Options → Data & privacy**, or remove all data by
uninstalling the extension.

## What leaves your device

Only for the paid plan: your **license key** and the license **instance id** are sent to
**Lemon Squeezy** (`api.lemonsqueezy.com`), our payment provider and merchant of record,
to activate, validate (on browser start and once a day) and deactivate the license.
No browsing data, research data or personal information is included.

Purchases happen on Lemon Squeezy's checkout page; their privacy policy applies there:
https://www.lemonsqueezy.com/privacy

## What Bookscout does not do

- No analytics, tracking, advertising or fingerprinting.
- No remote code.
- No selling or sharing of data.
- No access to websites other than the supported Amazon marketplaces and Lemon Squeezy.

## Permissions

- `storage` – keep settings, cache and saved niches locally
- `alarms` – re-validate the license once a day
- `sidePanel` – the research workspace
- `offscreen` – parse fetched product pages (service workers cannot parse HTML)
- Host access to `amazon.com`, `amazon.co.uk`, `amazon.de`, `amazon.fr`, `amazon.es`,
  `amazon.it`, `amazon.ca`, `amazon.com.au`, `amazon.co.jp` (pages and search
  suggestions) and `api.lemonsqueezy.com` (license only)

## Contact

Questions or support: risioja@gmail.com

Bookscout is not affiliated with Amazon. Sales figures are estimates.
