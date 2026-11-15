# Gilderow site (GitHub Pages)

Static pages for the platform app registrations:

- `index.html` (about)
- `privacy.html` (privacy policy, `#data-deletion` section)
- `terms.html` (terms of service, needed by TikTok)
- `oauth/callback.html` (https relay that forwards an OAuth sign-in to ReachForge on the owner's computer)
- `style.css`

TikTok's URL-prefix signature file (`*.txt`) is added by the Connect wizard to the upload folder
`data/site_publish/` and uploaded to the repository's top level next to `index.html`.

Not published from this repository. Publish it as described in `CONNECT.md` step 1, after replacing
`CONTACT_EMAIL_PLACEHOLDER` with the contact address.
