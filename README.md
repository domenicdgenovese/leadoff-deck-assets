# leadoff-deck-assets

Public image host for the Leadoff daily carousel.

This repository exists for one reason: **Buffer attaches carousel media by
public URL and cannot authenticate.** Raw URLs from a private repo return 404
to anyone without a token, so the slides have to live somewhere anonymously
readable. Everything here is published to Instagram and TikTok the next
morning anyway — there is nothing in this repo that is not already public.

```
deck/YYYY-MM-DD/slideNN.png    1080x1350, in swipe order
```

Written by `scripts/publish-deck-daily.sh` in the `leadoff-launch-video`
repository. Slides are generated from Leadoff's own endpoints — probable
starters and the graded model record — so nothing here is hand-authored.

Old dates are kept. They cost almost nothing and they are the only record of
what a given day's card actually claimed.
