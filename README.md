# AuPropre — site de l'agence

Site statique (HTML, CSS, JS), hébergé sur Cloudflare.

- `public/` : les fichiers du site (accueil, pages légales, 404).
- `wrangler.jsonc` : configuration Cloudflare (sert le dossier `public/`).

Chaque push sur `main` redéploie le site automatiquement.
