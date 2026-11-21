# Tubix legal website (GitHub Pages)

Same structure and look as https://muralismart360.github.io/keetjet-legal/ .

```
index.html                  home page (links to the three pages)
.nojekyll                   makes Pages serve the .md files as plain text
docs/style.css              shared dark style
docs/privacy_policy.html    privacy policy (Play Console URL)
docs/terms.html             terms of use
docs/about.html             about
docs/app/*.md               texts shown INSIDE the app (en, te, hi) - the app loads these
```

## Upload
1. On GitHub (account `muralismart360`) create a **public** repository `tubix-legal`.
2. Upload everything in this folder (keep the `docs` folders; include the hidden `.nojekyll`) to
   the root of branch `main`.
3. Settings > Pages > Deploy from a branch > main / (root).

## Links after publishing
- Home: https://muralismart360.github.io/tubix-legal/index.html
- Privacy policy (Play Console): https://muralismart360.github.io/tubix-legal/docs/privacy_policy.html
- Terms: https://muralismart360.github.io/tubix-legal/docs/terms.html
- About: https://muralismart360.github.io/tubix-legal/docs/about.html
- App texts: https://muralismart360.github.io/tubix-legal/docs/app/about_en.md (and howto/privacy/terms, _te, _hi)
