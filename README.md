# LPV•pro — Prototype interactif B2B

Prototype interactif pour la réponse à appel d'offres de la refonte de l'espace pro B2B de **Le Petit Vapoteur**.

## 🔗 Démo en ligne

**https://sbessoudo.github.io/lpv-pro-prototype/**

## Parcours couvert

- **Accueil connecté** — hero personnalisé, commandes récentes, sections produits
- **Mega menu** — navigation par catégorie (E-cigarettes, E-liquides, Résistances, Accessoires)
- **Recherche** — autocomplete, filtres marque/famille/stock, tri
- **Fiche produit** — prix remisé, stock, thumbnails, specs, avis, quantité clavier
- **Panier** — persistance, alertes disponibilité/encours, récapitulatif
- **Checkout 3 étapes** — adresses, paiement (CB / Virement SEPA / Encours), confirmation
- **Centre de notifications** — panneau in-app, préférences par canal

## Utilisation

Fichier HTML auto-contenu — aucune installation requise.

```
Ouvrir index.html dans n'importe quel navigateur
```

Toutes les dépendances (React 18, fonts) sont embarquées. Fonctionne hors ligne.

## Stack

- React 18 (Babel standalone, pas de build step)
- Fonts : Oswald + Inter
- Données : seed statique (5 typologies, 14 produits, utilisateur Vaposhop SAS P3 −18%)
