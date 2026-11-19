# Site d'ÉCHO : Petite Voix

Trois pages statiques, sans serveur ni base de données :

- `index.html` : présentation du jeu, avec la grotte interactive, et la section **Assistance** (`#assistance`) ;
- `confidentialite.html` : la politique de confidentialité (le même fichier est aussi dans l'appli, `www/confidentialite.html`) ;
- `app-ads.txt` : la déclaration publicitaire exigée par AdMob.

## En ligne

Le site est publié sur GitHub Pages : https://yk197-afk.github.io/ (dépôt `YK197-afk.github.io`).
Pour le modifier, change les fichiers dans ce dépôt : la mise en ligne suit en une minute environ.

Éditeur : NEO TECH. Contact : support@neotechmali.com.

## Ce qu'il reste à faire

1. **`app-ads.txt`** : quand tu as ton identifiant d'éditeur AdMob, enlève le « # » de la dernière ligne
   et remplace `pub-XXXXXXXXXXXXXXXX` par cet identifiant.
2. **Badges** : quand le jeu est publié, remplace les deux pastilles « bientôt » d'`index.html`
   par les badges officiels d'Apple et de Google, avec les liens vers tes fiches.
3. **Confidentialité** : si tu modifies `confidentialite.html`, recopie-le aussi dans `www/` pour que l'appli affiche la même version.

## Utiliser ton propre domaine (facultatif)

Tu peux servir ce site depuis neotechmali.com (ou un sous-domaine) : GitHub, Settings > Pages > Custom domain,
puis un enregistrement DNS chez ton hébergeur de domaine. Si tu déclares neotechmali.com comme site du développeur
dans les stores, `app-ads.txt` doit alors être à la racine de neotechmali.com.

## Les adresses à donner aux stores

| Champ | Adresse |
|---|---|
| Site du développeur (Google Play) et URL marketing (App Store) | `https://yk197-afk.github.io/` |
| URL d'assistance (App Store) | `https://yk197-afk.github.io/#assistance` |
| Politique de confidentialité (les deux stores) | `https://yk197-afk.github.io/confidentialite.html` |

AdMob lit `app-ads.txt` sur le domaine du « site du développeur » déclaré dans les stores.
Le fichier doit donc être à la racine de ce domaine, pas dans un sous-dossier.

Polices : Lexend Zetta et Atkinson Hyperlegible Next, sous licence SIL Open Font License (voir `fonts/`).
