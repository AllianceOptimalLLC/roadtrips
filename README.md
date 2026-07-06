# Roadtrips

A growing collection of hand-built, fact-checked road trip field guides:
the route, where you can legally car camp for free, the lake-and-mountain
views worth stopping for, and the honest gotchas.

Static site, no build step. Deployed on Vercel (auto-deploys on push to `main`).

## Structure

```
index.html                     # hub landing page (lists all trips)
trips/<slug>/index.html        # one self-contained guide per trip
trips/<slug>/img/*.jpg         # that trip's photos
vercel.json                    # cleanUrls + trailingSlash
```

## Add a new trip

1. Create `trips/<new-slug>/index.html` (self-contained HTML) and an `img/` folder.
2. Add a card for it in the root `index.html` trip grid.
3. Commit and push to `main`. Vercel redeploys automatically.

## Trips

- **01 &mdash; Las Vegas to Banff** (`/trips/vegas-to-banff/`): free car-camping
  corridor NV to Alberta, near mountains and lakes. Live.

Trip-planning information only, not legal advice.
