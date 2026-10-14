# PognonPILOT

Application de gestion de finances personnelles (PWA) : comptes, opérations, virements, catégories, rapports, import/export CSV, Excel et PDF.

- Fonctionne hors ligne une fois ouverte une première fois.
- Aucune donnée n'est stockée sur GitHub : les données restent dans le navigateur et dans ton fichier `pognonpilot-donnees.json` (OneDrive).

## Mettre à jour l'appli
1. Remplace les fichiers modifiés dans ce dépôt (Add file → Upload files).
2. Dans `sw.js`, augmente le numéro de `VERSION` (ex. `pognonpilot-v2`).
3. Rouvre l'appli deux fois : la nouvelle version s'installe.
