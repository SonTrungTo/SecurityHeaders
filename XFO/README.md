- XFO header protects your site from clickjacking, meaning
iframe can be copied to somebody else's site and be put `src`
as your site.
- `X-Frame-Options: DENY/SAMEORIGIN/ALLOW-FROM https://...`
