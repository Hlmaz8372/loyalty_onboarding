# Loyalty — System Map

Interactive, centre-outward map of how a Shopify loyalty system works.

**Live:** https://hlmaz8372.github.io/loyalty_onboarding/

## Presenting
- **Next / Back** or **→ / ←** or **Space** — reveal the next branch
- **Drag** empty space to move around, **scroll / pinch** to zoom, **Fit** or **0** to re-centre
- **Click any block** for details, **Esc** to close

## Editing
Everything on the map lives in three lists at the top of the `<script>` in `index.html`:

- `NODES` — the blocks (name, position, step it appears on, panel text)
- `EDGES` — the lines between blocks
- `CAPTIONS` — the caption for each step

Change those lists. Don't touch the code below them.

## Updating the live site
1. Add file → Upload files → drop in the new `index.html`
2. Write a short note → Commit changes
3. Wait ~1 minute. Same link, new version.

## Undoing a change
Open `index.html` → **History** → pick an older version → copy its contents back in and commit.
Nothing is ever lost.
