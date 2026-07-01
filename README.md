# PEX — Outil de Transmission d'Entreprise

Outil pédagogique d'aide à la décision pour la transmission d'entreprise, développé pour **PEX — Cabinet d'expertise & conseil**.

## Utilisation

L'outil est une application web autonome contenue dans un seul fichier : **`Outil.html`**.
Il suffit de l'ouvrir dans un navigateur web (Chrome, Edge, Firefox, Safari) — aucune installation n'est requise.
Un mot de passe est demandé au démarrage.

> Une connexion internet est nécessaire au premier chargement (polices Google Fonts et
> bibliothèques Chart.js, jsPDF, SheetJS/ExcelJS et PDF.js chargées via CDN).

## Fonctionnalités

- Profil d'entreprise et saisie des associés cédants / repreneurs
- Générateur de CSV à partir d'une liasse fiscale (PDF)
- Import de documents financiers (Excel / CSV)
- Calculs automatiques (ratios, valorisation, DSCR)
- Comparaison de scénarios (Dutreil, crédit vendeur, hybride, LBO, donation-cession)
- Stratégie personnalisée par cédant et repreneur
- Export PDF (synthèse multi-pages), Excel et sauvegarde de session (JSON)

## Charte graphique

Interface en tons froids (deux bleus + une nuance teal), sans doré dans l'UI.

| Couleur | Code | Usage |
|---|---|---|
| Bleu Marine Profond | `#002D62` | Couleur principale (barre latérale, titres, texte) |
| Bleu Turquoise | `#6CB4CF` | 2ᵉ bleu — accents, tuiles, graphiques |
| Teal (nuance) | `#178FA0` | Accent interactif (boutons, états actifs, filets) |

> Le **Laiton Doré `#C2A261`** reste présent uniquement dans le logo.
