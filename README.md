# Pages publiques des applis GAIA

Site statique servi par GitHub Pages, pour les adresses que demande le Play Store (politique de confidentialité,
demande de suppression du compte). Dépôt **public** à part : Pages sur un dépôt privé demande un abonnement payant,
et les dépôts des applis restent privés. N'y mettre que ce qui peut être lu par tout le monde.

## Adresses

- Hestia, confidentialité : `https://fibreariane.github.io/hestia/confidentialite/`
- Hestia, suppression du compte : `https://fibreariane.github.io/hestia/suppression-compte/`

## Mise en ligne (une fois)

1. Sur GitHub, créer le dépôt public `fibreariane.github.io` (ce nom exact : le site est alors servi à la racine
   `https://fibreariane.github.io/`), sans README.
2. `git remote add origin https://github.com/fibreariane/fibreariane.github.io.git` puis `git push -u origin main`.
3. Settings › Pages : Source « Deploy from a branch », branche `main`, dossier `/ (root)`. En ligne en une minute environ.

## Règles

- Adresse de contact affichée : l'adresse Gmail de l'utilisatrice (son choix, 22 novembre 2026). La changer
  partout d'un coup si elle crée une adresse à part.
- Une page par dossier (`appli/page/index.html`) pour des adresses sans `.html`.
- Quand une appli change ce qu'elle stocke ou envoie (nouveau service, nouvelle autorisation Android), mettre sa
  page de confidentialité à jour et changer la date en haut.
- Un fichier `.nojekyll` à la racine : GitHub sert les fichiers tels quels.
