# Site de Stock Granulés

Pages publiques de l'appli, pour les fiches App Store et Google Play.

| Page | Fichier | À utiliser pour |
|---|---|---|
| Accueil | `index.html` | URL marketing (Apple, facultatif), site web (Google) |
| Assistance | `assistance.html` | URL d'assistance (Apple, obligatoire) |
| Confidentialité | `confidentialite.html` | URL de politique de confidentialité (Apple et Google) |

## Avant de publier

Remplacer `VOTRE-EMAIL@exemple.fr` par l'adresse de contact, dans `assistance.html` et `confidentialite.html`.

## Publier sur GitHub Pages

1. Créer un dépôt **public** sur GitHub, par exemple `stock-granules-site`.
2. Envoyer les fichiers :
   ```
   git add .
   git commit -m "Site de l'appli"
   git branch -M main
   git remote add origin https://github.com/TON-COMPTE/stock-granules-site.git
   git push -u origin main
   ```
3. Sur GitHub : Settings > Pages > Source « Deploy from a branch », branche `main`, dossier `/ (root)`, Save.
4. Après une ou deux minutes, le site est en ligne :
   - https://TON-COMPTE.github.io/stock-granules-site/
   - https://TON-COMPTE.github.io/stock-granules-site/assistance.html
   - https://TON-COMPTE.github.io/stock-granules-site/confidentialite.html
