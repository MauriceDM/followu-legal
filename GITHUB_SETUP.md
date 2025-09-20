# GitHub Setup – SchulKlausur (Legal Pages)

## 1) Account
- Username: `MauriceDM` (öffentlich sichtbar) → URL: `https://github.com/MauriceDM`

## 2) Repository
- Name: `followu-legal` (Public)

## 3) Upload
- Dateien aus diesem Paket ins Repo-Root hochladen (Drag&Drop)

## 4) GitHub Pages
- Settings → Pages → Source: **Deploy from a branch → main/root**

## 5) Custom Domain
- Eintragen: `legal.follow-u.de` → Save → **Enforce HTTPS**, sobald verfügbar

## 6) DNS beim Provider/Cloudflare
- **CNAME**: Name/Host `legal` → Target `MauriceDM.github.io`
- Cloudflare: Proxy **DNS only**

## 7) Test
- https://legal.follow-u.de/
- https://legal.follow-u.de/impressum/
- https://legal.follow-u.de/privacy/
