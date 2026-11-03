# Page de la clé publique Tesla Fleet

- Sert uniquement à publier la clé **publique** demandée par Tesla, à l'adresse
  https://fleet.briandt07.com/.well-known/appspecific/com.tesla.3p.public-key.pem
- La clé **privée** reste dans Home Assistant (`config/tesla_fleet.key`) et ne doit jamais venir ici.
- Dépôt GitHub public `briandt07/fleet-key`, GitHub Pages, domaine déclaré chez Hostinger (enregistrement CNAME `fleet` → `briandt07.github.io`).
- `.nojekyll` est indispensable : sans lui, GitHub Pages ignore le dossier `.well-known`.
