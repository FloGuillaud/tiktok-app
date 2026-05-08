# tiktok-app

GitHub Pages source for **satirical-shorts** — TikTok Developer Portal verification.

## Live

- Home: https://floguillaud.github.io/tiktok-app/
- Terms of Service: https://floguillaud.github.io/tiktok-app/tos.html
- Privacy Policy: https://floguillaud.github.io/tiktok-app/privacy.html

## TikTok URL prefix verification

Place the challenge file (`tiktok<random>.txt`) provided by the TikTok
Developer Portal at the **root** of this repo (e.g. `tiktokWiMQi…txt`).

Once pushed and Pages rebuilt (~30s), TikTok can fetch it at:
`https://floguillaud.github.io/tiktok-app/tiktokWiMQi…txt`

Then click "Verify" in the TikTok dashboard.

## Setup GitHub Pages (one-time)

1. Repo Settings → Pages
2. Source: `Deploy from a branch`
3. Branch: `main` / folder: `/ (root)`
4. Save. Wait ~30s for first deploy.
