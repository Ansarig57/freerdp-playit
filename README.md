# Free RDP with Playit.io

This GitHub repo provides:
- Auto-generated RDP every 10 minutes
- Random password saved in `rdp.txt`
- Uses Playit.io for tunnel (add your PLAYIT_YAML in GitHub Secrets)

## Setup

1. Fork this repo or create your own
2. Add `PLAYIT_YAML` as a secret in GitHub > Settings > Secrets
3. Enable GitHub Pages for `/docs` to host frontend
4. Or upload `docs` folder to Netlify

## Website

Edit `docs/index.html` and replace:
```
YOUR_USERNAME / YOUR_REPO
```
With your GitHub info.
