# Site vitrine restaurant — gratuit (statique)

## Déploiement gratuit (iPhone OK)
### Option A — GitHub Pages
1) Crée un compte GitHub → nouveau repo `resto`.
2) Uploade `index.html`, `styles.css`, `script.js`, `menu.pdf` (optionnel).
3) Settings → Pages → `main` / `/root`. → Le site est live.

### Option B — Netlify (simple)
1) https://app.netlify.com → *Add new site* → *Deploy manually* → glisse le dossier.
2) Tu obtiens `https://xxxx.netlify.app` gratuit.

### Option C — Hugging Face Spaces (Static)
1) Create Space → **Static** → upload les fichiers.

## Personnalisation rapide
- Remplace l’adresse, horaires, téléphone dans la section **Infos** (HTML).
- Mets ton email réel dans la section **Réservations**.
- Remplace les images (URLs Unsplash) par tes photos.
- Exporte un PDF de ton menu et remplace `menu.pdf`.

## Formulaire (propre)
- Crée un compte **Formspree** (gratuit → quelques soumissions/mois).
- Change le `onsubmit` pour pointer vers Formspree ou ajoute un petit backend.

## Vrai e‑commerce ?
- Ajoute des boutons “Commander” → Stripe Checkout (voir l’autre ZIP que je t’ai donné),
  sinon passe direct à Shopify si tu veux livraison + taxes + inventaire.

