# Media Download

Minimal animated PWA for downloading publicly accessible TikTok videos and Facebook videos/Reels.

## Run
`npm install && npm start`

## Notes
- TikTok uses TikWM first and falls back to Cobalt.
- Facebook public videos/Reels use a Cobalt-compatible API instance.
- Set `COBALT_API_URL` to your own Cobalt instance for reliable production use. The upstream Cobalt project notes that hosted API instances may require their own access/instance setup.
- Use only content you are authorized to download.
