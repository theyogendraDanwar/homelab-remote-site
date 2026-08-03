# Homelab Remote — public site (Support + Privacy)

Static pages for App Store Connect.

| Field | URL |
| --- | --- |
| Support URL | https://theyogendraDanwar.github.io/homelab-remote-site/support.html |
| Privacy Policy URL | https://theyogendraDanwar.github.io/homelab-remote-site/privacy.html |
| Home | https://theyogendraDanwar.github.io/homelab-remote-site/ |

## Enable GitHub Pages (required once)

1. Open https://github.com/theyogendraDanwar/homelab-remote-site/settings/pages  
2. **Source:** Deploy from a branch  
3. Branch: **main** → folder **/ (root)** → **Save**  
4. Wait ~1 minute, then open the Support URL above.

## Push pages from your Mac (if not already on GitHub)

In Terminal:

```bash
cd /tmp/homelab-remote-site
git push -u origin main
```

If HTTPS asks for login, use a [Personal Access Token](https://github.com/settings/tokens) as the password, or:

```bash
git remote set-url origin git@github.com:theyogendraDanwar/homelab-remote-site.git
git push -u origin main
```

## App Store Connect

- **English (U.S.) → Support URL:** `https://theyogendraDanwar.github.io/homelab-remote-site/support.html`  
- **Privacy Policy URL:** `https://theyogendraDanwar.github.io/homelab-remote-site/privacy.html`  

Support email: yogendra.danwar@gmail.com
