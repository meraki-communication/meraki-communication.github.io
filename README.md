# Site Meraki Communication

Site statique optimisé, prêt pour GitHub Pages (≈ 20 Ko de HTML, aucun framework).

## Mise en ligne
1. Créer un dépôt GitHub (ex. `meraki-site`).
2. Déposer à la racine : `index.html`, `.nojekyll` **et le dossier `img/`**.
3. Settings → Pages → Source : `Deploy from a branch`, branche `main`, dossier `/ (root)`.
4. Le site est en ligne sur `https://<utilisateur>.github.io/<depot>/`.

## Navigation
Les 4 pages sont dans le même fichier, via l'URL :
- `#accueil`, `#portfolio`, `#agilitek`, `#ucknef`

## Optimisations
- HTML/CSS statique, JS minimal (navigation + lumière du hero).
- Images WebP, chargées seulement quand la page/section est affichée (lazy).
- Photo du hero préchargée en priorité.
- Police Outfit en un seul fichier variable, non bloquante ; Noto Sans réduite aux seuls caractères « /μεράκι/ ».
- Animations désactivées si l'utilisateur a demandé « réduire les animations ».
