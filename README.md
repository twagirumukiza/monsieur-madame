# MM90 — Catalogue Monsieur Madame Happy Meal 2017

Site statique bilingue FR/EN pour inventorier la collection des 90 figurines Monsieur Madame distribuées dans les Happy Meal McDonald's France à partir du 22 novembre 2017.

## Contenu
- `index.html`, `styles.css`, `app.js` : site complet, responsive, sans framework.
- `data/collection.json` : 90 fiches initiales, identifiants MM17-001 à MM17-090.
- Recherche, filtres, tri, fiches modifiables, quantité possédée, doubles, liste de recherche, état, rareté /100, prix indicatif, source/date de prix, notes et photos personnelles.
- Sauvegarde locale via `localStorage`, export/import JSON.
- Interface française/anglaise.

## Déploiement GitHub Pages
1. Crée un dépôt GitHub public, par exemple `MonsieurMadameCollection`.
2. Décompresse ce dossier et pousse **le contenu** du dossier à la racine du dépôt.
3. Dans **Settings → Pages**, choisis **Deploy from a branch**, branche `main`, dossier `/ (root)`.
4. Enregistre et attends la publication. Le site sera servi à l'URL GitHub Pages affichée par GitHub.

Aucun build, aucune clé API, aucun serveur nécessaire. Pour tester en local, lance un serveur HTTP dans ce dossier (par exemple `python -m http.server 8000`) puis ouvre `http://localhost:8000`. Ne pas ouvrir `index.html` directement en `file://`, car le navigateur peut bloquer le chargement de `data/collection.json`.

## Sauvegarde et limites
- Les données de collection et les photos sont stockées dans le navigateur de l'appareil courant. Elles ne se synchronisent pas entre appareils et peuvent être perdues si les données du navigateur sont effacées. Utilise régulièrement **Exporter** et conserve le JSON.
- Les photos sont limitées à 1,5 Mo chacune afin de ne pas surcharger le stockage local.
- Pour importer, utilise un export JSON de MM90. L'import fusionne les données par identifiant.
- Le score de rareté et les prix démarrent volontairement vides : aucune cote n'est inventée. Ajoute la source et la date du relevé pour les rendre traçables.
- Les noms anglais sont des équivalents descriptifs pour l'interface et peuvent différer des noms officiels de l'édition britannique. Vérifie avant publication ou revente.
- Les cartes affichent des formes décoratives génériques, pas des reproductions officielles. Ajoute tes propres photos des figurines pour améliorer l'identification.

## Sources initiales
- Coleka, « Happy Meal - Monsieur Madame 2017 » : https://www.coleka.com/fr/jouets-happy-meal-mcdonald-s/de-2015-a-2019/happy-meal-monsieur-madame-2017_r3218
- Bibelotmania, « Monsieur Madame - 90 Figurines - Happy Meal - 2017 » : https://www.bibelotmania.com/?idf=3&idm=7640&pag=cid508_alb
- Article de collectionneur, 11 janvier 2018 : https://cest-trop-bien.blogspot.com/2018/01/les-90-figurines-monsieur-madame-des.html

## Données historiques de départ
Sources de collectionneurs indiquent une distribution en France du 22 novembre 2017 au mois de janvier 2018; Bibelotmania précise la période promotionnelle jusqu'au 16 janvier 2018. Le catalogue de 90 noms est transcrit depuis la liste Coleka. Les identifiants MM17-### sont des identifiants internes de ce projet, pas des numéros imprimés officiels.

## Identification depuis ta photo
La photo initiale sert de point de départ à l'inventaire, mais aucune pièce n'est pré-identifiée automatiquement. Ouvre une fiche, ajoute une photo personnelle et note les caractéristiques visibles. Une identification ne doit être confirmée qu'après comparaison avec une image ou un emballage de référence fiable.

## Licence / indépendance
Projet indépendant de collectionneur, non affilié à McDonald's, à Sanrio ou aux ayants droit de la série Monsieur Madame. Les marques et noms restent la propriété de leurs titulaires. Le site n'intègre pas d'images officielles afin de limiter les problèmes de droits.
