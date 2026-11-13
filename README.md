# Mayur — Telegram landing page

Ready-to-upload website. Upload `index.html`, `assets/`, `_redirects`, and `robots.txt` together to your hosting provider.

- Telegram invite: https://t.me/+hSkKyQ30D8EzYjFl
- Meta Pixel: 1109602441875385
- Automatic redirect: 2 seconds
- Preview without redirect: append `?preview=1` to the hosted URL.

Editable React source remains in the repository root under `src/` with the pixel snippet in the root `index.html`.

To refresh this folder after source changes, run from the repository root:

```sh
npm run build -- --base=./ --outDir mayur/telegram-landing-page
```

The build recreates this directory; preserve this README separately if needed.
