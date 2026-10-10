# MonsieurMadamePops

Boutique des 90 figurines Monsieur Madame du Happy Meal McDonald's France (2017). Même principe que HarryPotterPops, BlockyPops et Mariopops : page unique HTML, panier en localStorage, 4 angles photo par article, FR/EN, clair/sombre, menu burger par année, pied de page légal (CGV, licence, mentions légales, RGPD).

## Photos
Déposer dans `images/` quatre fichiers par figurine, nommés d'après le slug de la fiche :
`<slug>-front.jpg`, `<slug>-right.jpg`, `<slug>-left.jpg`, `<slug>-back.jpg`
(ex. `madame-acrobate-front.jpg`). Tant qu'une photo manque, un visage générique s'affiche.
Le plus simple : utiliser l'éditeur (dépôt `monsieur-madame-editeur`), qui produit les noms et le zip.

## Déploiement GitHub Pages
Pousser le contenu de ce dossier à la racine du dépôt `monsieur-madame` (branche `main`, dossier `/ (root)`).
L'ancien carnet de collection reste dans l'historique git du dépôt.

## À compléter
Les champs vides de `SITE_INFO` (statut, SIRET, adresse, e-mail, médiateur…) s'affichent en jaune « à compléter » dans les pages légales.
Projet indépendant de collectionneur, non affilié à McDonald's ni aux ayants droit de Monsieur Madame.
