# vibely-legal

Public legal documents for the **Vibely** mobile app, served by GitHub Pages.

| Page | URL |
|---|---|
| Privacy Policy | `/privacy-policy/` |
| Terms of Service | `/terms-of-service/` |
| Delete Your Account | `/account-deletion/` |

## ⚠️ Do not edit the Markdown here

These pages are **generated**. The source of truth lives in the private app repository at
`legal/*.md`, where the documents are reviewed alongside the code they describe — the data
types in the privacy policy have to match what the app actually collects and what
`ios/Runner/PrivacyInfo.xcprivacy` declares.

To change a document, edit it there and run:

```bash
./legal/publish.sh /path/to/vibely-legal
```

That copies the Markdown across, adds the Jekyll front matter, rewrites the in-repo
`*.md` links to site URLs, and refuses to publish if it finds an unfilled `[PLACEHOLDER]`
or a link it did not rewrite. Then commit and push here.

Editing a page directly in this repo will be silently overwritten by the next sync.

## Why this repo is separate

The app repository is private, and GitHub Pages from a private repository requires a paid
plan. Keeping the published documents in their own public repo is free, avoids exposing the
app source, and the content is meant to be public anyway.

## Layout

`_layouts/default.html` is self-contained — no theme gem, no external CSS, fonts, or scripts.
Nothing to resolve at build time, so the site cannot break because an upstream theme changed.
It renders in light and dark, and wide tables scroll inside their own container rather than
forcing the page sideways on a phone.

## These URLs must stay live

Both app stores require a reachable privacy policy URL, and Google Play separately requires
the account-deletion URL. A dead link gets the app pulled during periodic review. Do not
rename the repo, change the permalinks, or make it private.
