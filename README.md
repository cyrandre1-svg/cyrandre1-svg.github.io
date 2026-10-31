# Bibliothèque technique navale — site d’information

Site statique de présentation de BTN, application personnelle de recherche documentaire, et politique de confidentialité liée à son accès Google Drive.

## Fichiers

- `index.html` : présentation de l’application.
- `confidentialite.html` : données traitées, autorisations Google, stockage, retrait des accès et hébergement du site.
- `style.css` : mise en page adaptative, sans dépendance externe.
- `.nojekyll` : publication directe des fichiers statiques par GitHub Pages.

## Publication et entretien

Dans les paramètres du dépôt, ouvrir **Pages**, sélectionner **Deploy from a branch**, la branche **main** et le dossier **/ (root)**, puis enregistrer. Aucun outil de compilation n’est nécessaire.

Les changements validés sur `main` sont ensuite publiés par GitHub Pages. Conserver la même politique de confidentialité dans les liens du site et dans la configuration OAuth Google.

Pour une vérification Google Search Console, ajouter uniquement la balise HTML ou le fichier de vérification public fourni par Google. Ne pas publier de secret d’authentification.

Ce dépôt contient uniquement le site d’information. Ne pas y ajouter de document source, index, sauvegarde de l’application, client OAuth, jeton ou clé de tunnel. Le programme BTN et les données documentaires sont sauvegardés séparément.

La politique doit être mise à jour avant toute modification des usages décrits, notamment l’ajout d’un assistant distant, d’un formulaire ou d’un outil de mesure d’audience.
