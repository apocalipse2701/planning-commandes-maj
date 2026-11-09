# Planning Commandes — mises à jour

Dernière version : **2.15.3** (09/11/2026).

| | Version manuelle | Version « mail » (commandes relevées dans la boîte mail) |
|---|---|---|
| **Téléphone Android** | [PlanningCommandes.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes.apk) | [PlanningCommandes-mail.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-mail.apk) |
| **PC Windows** | [PlanningPDF.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF.exe) | [PlanningPDF-mail.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF-mail.exe) |

**Pour un proche** (conjoint…) qui veut seulement voir votre planning à jour : [PlanningCommandes-lecture.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-lecture.apk) — à régler avec le kDrive et le code de partage (Réglages › Partage du planning sur votre téléphone).

**PC** : placez l'exe dans votre dossier PlanningPDF habituel (celui qui contient `codes.txt` et le dossier `commande`), à la place de l'ancien — pas dans Téléchargements.

Une fois installées, l'application et le programme PC se mettent à jour d'eux-mêmes à partir d'ici.
Toutes les versions : [Releases](https://github.com/apocalipse2701/planning-commandes-maj/releases).

## Nouveautés de la version 2.15.3


**Android 6 / anciennes tablettes : boutons sans effet (Android)**
- Cause : une expression de recherche de lettres accentuées (`\p{L}`) que les anciennes WebView ne comprennent pas. Tout le script de l'application était refusé, donc aucun bouton ne répondait. Elle est remplacée par une liste de lettres (A-Z, accents français).
- Le script de l'application et les bibliothèques PDF sont maintenant réécrits pour les WebView anciennes (Chrome 51 et plus, 2016) :
  - syntaxe récente transformée ;
  - pdf.js chargé en scripts classiques (sans module) ;
  - fonctions manquantes ajoutées.
- Si une erreur survient malgré tout, un bandeau rouge l'affiche en bas de l'écran avec la version de la WebView (à transmettre pour diagnostic).
- Fond des fenêtres et filigrane GRÈVE : positionnement compatible avec les anciennes WebView.

