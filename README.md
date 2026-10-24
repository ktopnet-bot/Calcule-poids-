# Calcul poids tuyauterie

Application web d'un seul fichier (`index.html`) pour calculer les poids de tuyauterie, accessoires, brides et vannes, par isométrique et par spool.

## Utilisation

Ouvrir `index.html` dans un navigateur (ordinateur ou téléphone). Aucune installation, aucun serveur.

- **Fiche** : classe, NPS, schedule et type de bride, avec la fiche de données correspondante.
- **Liste** : une fiche par pièce (tube, accessoire, bride, vanne, isolation), avec poids unitaire et total automatiques. Dupliquer et supprimer demandent une confirmation.
- **Rapport par spool** : poids total par isométrique et par spool, avec filtre par isométrique.

La liste est enregistrée dans le navigateur (localStorage) ; elle n'est pas envoyée ailleurs.

## Source des données

Tous les poids sont intégrés dans le fichier, extraits du classeur *Calcul poids pour chantier GCT Gabès* (feuille *Weight Tables*). Les dimensions de la fiche proviennent du *Piping Slide Chart V1* (M.W. Kellogg). Les poids de vannes et clapets de cette source sont différents de ceux des catalogues du web : le classeur fait référence.

## Limites connues

- Les dimensions de la fiche (longueurs, diamètres de bride, boulonnage) ne viennent que du Piping Slide Chart et ne couvrent que certaines classes.
- Les valeurs absentes du classeur s'affichent « n/d » et comptent 0 kg.
- Les poids doivent être vérifiés avant tout usage de chantier.
