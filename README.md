# Presentations

Static site, one folder per deck, deployed to Cloudflare (Workers static assets, see `wrangler.jsonc`) on every `git push`.

- `/` — landing page listing the decks
- `/buttons/` — The Buttons

In a deck: ← → / space / click the edges. Add `class="skip"` to a slide to hide it without deleting it.
Preview locally: `python3 -m http.server 4321`
