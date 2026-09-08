# MaBoutique

Monorepo de la plateforme SaaS MaBoutique : gestion d'activité (produits, services, stock, ventes, caisse, clients, employés, rendez-vous, commandes, rapports, abonnements) pour tout type de commerce (alimentation générale, boucherie, restaurant, coiffeur, pharmacie, etc.).

## Structure du dépôt

```
MBoutique/
├── backend/     # API REST Laravel (Sanctum, multi-tenant, modular monolith)
└── frontend/    # Application React (mobile/web) — à venir
```

- Documentation d'architecture backend complète : [`backend/docs/README.md`](backend/docs/README.md).
- Chaque projet (`backend/`, `frontend/`) est autonome : ses propres dépendances (`composer.json` / `package.json`), son propre `.gitignore` interne si besoin, ses propres commandes de démarrage documentées dans son propre dossier.
