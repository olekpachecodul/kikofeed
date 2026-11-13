# Kiko Feed

The newest secondhand Kiko Kostadinov listings from resale shops, in one page.

**Live at https://kiko.hengecorp.com** (feed: https://kiko.hengecorp.com/feed.xml)

This is one of a family of feeds (Rick Owens, Kiko Kostadinov, Helmut Lang, 205W39NYC, Soshiotsuki) that share one engine.
The code, the look (`themes/kiko.css`) and **this feed's shop list (`brands/kiko.json`) live in
[olekpachecodul/rickfeed](https://github.com/olekpachecodul/rickfeed)**. Change them there; this repo picks the change up on its next run.

What's here:
- `.github/workflows/feed.yml`: checks the shops up to every 15 minutes and republishes the page.
- `data/state.json`: what's already been seen (created and updated automatically).

Run it now: Actions tab → Kiko Feed → Run workflow.
