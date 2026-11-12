# CoachPace

Website for CoachPace, an AI running coach that lives in Telegram. It reads the
activities you already log on Strava, writes a seven-day plan, and rewrites the
week when a session is missed.

## Run locally

No build step. Open `index.html`, or serve the folder:

```sh
python3 -m http.server 8000
```

## Structure

- `index.html` - the whole site (markup, styles, and the FAQ/nav script)
- `logo_coachpace.svg` - vector logo mark, transparent background
- `logo_coachpace_hd.png` - 1024 x 1024 PNG on the paper background, used for
  the Telegram bot avatar and social previews
- `favicon.png` - 256 px favicon
- `img/track-aerial.jpg`, `img/runner-steps.jpg` - section imagery

## Images

Both photographs are from Unsplash and stored locally, used under the
[Unsplash License](https://unsplash.com/license):

- `img/track-aerial.jpg` - https://unsplash.com/photos/1502904550040-7534597429ae
- `img/runner-steps.jpg` - https://unsplash.com/photos/1476480862126-209bfaa8edc8

They are illustrative only. No athlete, quote, or case study is implied.

## Notes

- The Telegram button still points at `t.me/pacelab_bot`. Update it once the
  new bot handle is live.
- `og:image` uses the absolute `raw.githubusercontent.com/.../main/...` URL so
  social previews work after this branch is pushed.
