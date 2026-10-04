# Matmata Moto Store — Gestion de vente et de stock

Application web (HTML/CSS/JS, sans serveur) : tableau de bord, produits, ventes (panier), rapports, alertes, commandes, comparaison de prix, fournisseurs, clients.

## Mise en ligne sur GitHub Pages
1. Créez un dépôt GitHub (ex. `matmata-moto-store`) et déposez `index.html`, `data.json`, `README.md`.
2. Dépôt → **Settings → Pages** → Source : *Deploy from a branch* → branche `main`, dossier `/ (root)` → Save.
3. L'application sera disponible sur `https://<votre-compte>.github.io/matmata-moto-store/`.

## Données
- `data.json` contient les données du fichier Excel V14 (822 produits, 2070 ventes, fournisseurs, clients), chargées au premier lancement.
- Ensuite tout est enregistré dans le navigateur (localStorage). Utilisez la page **Données** pour exporter/importer une sauvegarde JSON.
- Les données étant locales à chaque navigateur, exportez-les pour passer d'un appareil à un autre.
