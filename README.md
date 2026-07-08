# Instakrapo

Générateur de posts Instagram (format 3:4) pour la tournée de la fanfare.
Application web statique, installable en PWA. Aucune dépendance serveur.

## Fichiers
- `index.html` — l'app (police Adam Script embarquée)
- `manifest.webmanifest` — métadonnées PWA
- `sw.js` — service worker (offline + installation)
- `icon-*.png`, `apple-touch-icon.png`, `favicon-32.png` — icônes

## Publier sur GitHub Pages
1. Créer un dépôt public, y déposer tout le contenu de ce dossier **à la racine**.
2. Settings → Pages → Source : `Deploy from a branch`, branche `main`, dossier `/ (root)`.
3. L'URL est `https://<utilisateur>.github.io/<depot>/`.
4. Sur iPhone : ouvrir l'URL dans Safari → Partager → « Sur l'écran d'accueil ».

## Mettre à jour
Après modification, changer `instakrapo-v1` en `instakrapo-v2` dans `sw.js`
pour forcer le rechargement du cache.
