FlowLink — Pack complet (SEO + légal + sécurité)

À FAIRE AVANT PROD
1) Remplacer BASE_URL (sitemap.xml, robots.txt, canoniques dans les pages) par votre domaine final.
2) Compléter Mentions légales : raison sociale, forme juridique, SIREN/SIRET, TVA, adresse, directeur de publication.
3) Vérifier le slug Cal.com (actuellement flow-link/rdv-1h) et le remplacer dans index.html si besoin.
4) Activer HTTPS & HSTS sur Cloudflare (Always Use HTTPS).

Recommandé (optionnel)
- Ajouter analytics RGPD (Plausible/Matomo) et déclencher uniquement si consentement = "accepted".
- Remplacer og-image.png par une version brandée personnalisée.
- Forcer www → non‑www (ou inverse) via des règles Cloudflare.

Déploiement Cloudflare Pages
- Uploader TOUT le contenu du zip à la racine.
- Vérifier /sitemap.xml et /robots.txt.
- _headers et _redirects sont pris en charge par Cloudflare Pages.
