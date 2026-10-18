# Vet Care legal site (Play Store URLs)

Static pages for Google Play Console:

| Page | File | Use in Play Console |
|------|------|---------------------|
| Privacy Policy | `privacy-policy.html` | App content → Privacy policy |
| Account deletion | `delete-account.html` | App content → Data safety → Account deletion URL |

## Why this exists

`https://metconhitech.com/vetcare/` currently returns **404**, so Play Console rejects the account deletion link.

## Host on GitHub Pages (free, recommended)

1. Create a **public** GitHub repository named `vetcare-legal` (must be public).
2. Upload everything inside this `legal-site` folder to the repo root (or push this folder’s contents).
3. In the repo: **Settings → Pages**
4. Source: **Deploy from a branch**
5. Branch: `main` / folder: `/ (root)` → Save
6. Wait 1–2 minutes, then open:

```
https://TAHA-5440.github.io/vetcare-legal/
https://TAHA-5440.github.io/vetcare-legal/privacy-policy.html
https://TAHA-5440.github.io/vetcare-legal/delete-account.html
```

(Replace `TAHA-5440` if your GitHub username differs.)

## Paste into Play Console

- **Privacy policy URL:** `https://TAHA-5440.github.io/vetcare-legal/privacy-policy.html`
- **Account deletion URL:** `https://TAHA-5440.github.io/vetcare-legal/delete-account.html`

Open both links in an Incognito window first — they must load with **no 404**.
