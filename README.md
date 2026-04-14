# AI Open Client — Website

This repository hosts the public landing page, support page, and privacy
policy for **AI Open Client**, a free, non-commercial, open-source iOS app
for chatting with AI.

Apple Intelligence runs privately on-device as the default experience, and
additional open-source AI models are available as alternative backends —
with more to be added over time.

## What's here

| File            | Purpose                                            |
| --------------- | -------------------------------------------------- |
| `index.html`    | Marketing landing page (Marketing URL)             |
| `support.html`  | Help, FAQ, and issue-reporting page (Support URL)  |
| `privacy.html`  | Privacy Policy page (Privacy Policy URL)           |
| `assets/styles.css` | Shared Liquid-Glass-inspired stylesheet        |

No JavaScript, no build step, no framework. Three hand-written HTML files
plus a single CSS file. Designed mobile-first so it renders well on the
iPhone that App Store reviewers will use to inspect it.

## Live URLs

After GitHub Pages is enabled for this repository (see below), the three
URLs used in the App Store Connect listing are:

- **Marketing URL** — `https://dmitriybagrov92.github.io/open-ai-client-ios/`
- **Support URL** — `https://dmitriybagrov92.github.io/open-ai-client-ios/support.html`
- **Privacy Policy URL** — `https://dmitriybagrov92.github.io/open-ai-client-ios/privacy.html`

## Enabling GitHub Pages

1. Go to **Settings → Pages** in this repository.
2. **Source**: "Deploy from a branch".
3. **Branch**: `main` (or `master`), folder `/ (root)`.
4. Click **Save**. The site is usually live within 30–60 seconds.

## Local preview

Just open `index.html` in a browser, or run a tiny local server:

```bash
python3 -m http.server 4000
```

Then open <http://localhost:4000>.

## License

Content is released under the Apache License 2.0 (see `LICENSE`).
