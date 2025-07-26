📊 Market Maker VBA


🎯 Objectif pédagogique


Ce projet a pour but de simuler un mini market maker en utilisant Excel/VBA, pour comprendre les mécanismes de formation des prix bid/ask, la tenue de carnet d’ordres, et le suivi d’un PnL dynamique. Il permet d’explorer de manière interactive les bases du market making, sans infrastructure de marché en temps réel.

⚙️ Fonctionnalités principales
Génération dynamique de prix bid/ask autour d’un mid-price configurable

Interface utilisateur avec boutons de trading (achat / vente)

Suivi automatique du PnL non réalisé et réalisé

Carnet de position mis à jour après chaque transaction

Détection de dépassement de risque (position ou perte max)

Paramétrage des spreads et tailles de lots via l’interface Excel

🖼️ Aperçu


(Ajoute ici un ou deux screenshots si tu veux : par exemple une capture de l’interface Excel et du PnL en fonctionnement)

Exemple :

![Interface Excel du Market Maker](./screenshots/market_maker_excel_interface.png)
🧰 Outils & technologies
Excel : Interface utilisateur + calculs

VBA : Logique métier (pricing, exécution, mise à jour des positions/PnL)

🗂️ Structure du projet
market-maker-vba/
│
├── MarketMaker.xlsm         # Fichier Excel avec macros activées
├── README.md                # Présentation du projet
└── screenshots/             # (optionnel) Captures d'écran de l'interface
