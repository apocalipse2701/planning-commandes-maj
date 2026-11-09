# Planning Commandes — mises à jour

Dernière version : **2.15.4** (09/11/2026).

| | Version manuelle | Version « mail » (commandes relevées dans la boîte mail) |
|---|---|---|
| **Téléphone Android** | [PlanningCommandes.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes.apk) | [PlanningCommandes-mail.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-mail.apk) |
| **PC Windows** | [PlanningPDF.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF.exe) | [PlanningPDF-mail.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF-mail.exe) |

**Pour un proche** (conjoint…) qui veut seulement voir votre planning à jour : [PlanningCommandes-lecture.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-lecture.apk) — à régler avec le kDrive et le code de partage (Réglages › Partage du planning sur votre téléphone).

**PC** : placez l'exe dans votre dossier PlanningPDF habituel (celui qui contient `codes.txt` et le dossier `commande`), à la place de l'ancien — pas dans Téléchargements.

Une fois installées, l'application et le programme PC se mettent à jour d'eux-mêmes à partir d'ici.
Toutes les versions : [Releases](https://github.com/apocalipse2701/planning-commandes-maj/releases).

## Nouveautés de la version 2.15.4


**Android 6 / WebView Chrome 55 (tablette sans mise à jour possible)**
- Corrige l'erreur « replaceChildren is not a function », affichée par le bandeau d'erreur sur la tablette : les fonctions de page récentes manquantes sont ajoutées (replaceChildren, toggleAttribute…).
- Copie profonde complète (structuredClone) pour la lecture des PDF sur les anciennes WebView. Sans elle, les bulletins n'étaient pas lus.
- Mises en page de remplacement quand la WebView ne connaît pas la grille CSS (Chrome < 57) : calendrier compact, onglets, détail du jour, champs, aide au paramétrage.

