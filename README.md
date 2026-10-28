# Planning Commandes — mises à jour

Dernière version : **2.9.3** (28/10/2026).

| | Version manuelle | Version « mail » (commandes relevées dans la boîte mail) |
|---|---|---|
| **Téléphone Android** | [PlanningCommandes.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes.apk) | [PlanningCommandes-mail.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-mail.apk) |
| **PC Windows** | [PlanningPDF.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF.exe) | [PlanningPDF-mail.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF-mail.exe) |

**Pour un proche** (conjoint…) qui veut seulement voir votre planning à jour : [PlanningCommandes-lecture.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-lecture.apk) — à régler avec le kDrive et le code de partage (Réglages › Partage du planning sur votre téléphone).

**PC** : placez l'exe dans votre dossier PlanningPDF habituel (celui qui contient `codes.txt` et le dossier `commande`), à la place de l'ancien — pas dans Téléchargements.

Une fois installées, l'application et le programme PC se mettent à jour d'eux-mêmes à partir d'ici.
Toutes les versions : [Releases](https://github.com/apocalipse2701/planning-commandes-maj/releases).

## Nouveautés de la version 2.9.3


**Partage du planning : dépôt refusé par le kDrive (correction, Android)**
- À l'enregistrement, le partage échouait avec « accès refusé par le kDrive pour dépôt du planning ». Quand le dossier n'existe pas encore, kDrive répond « refusé » au lieu de « introuvable » : l'application ne créait donc pas le dossier.
- Elle le crée maintenant dans ce cas aussi (« Private », puis « Planning partagé »), puis dépose le planning.
- Si le kDrive refuse encore, le message dit pourquoi :
  - le dossier de départ n'existe pas : la liste des dossiers présents à la racine du kDrive est affichée, avec le chemin à indiquer ;
  - tout accès est refusé : l'offre kDrive n'inclut sans doute pas le WebDAV, ou l'identifiant n'est pas l'adresse mail du compte.
- Même aide sur le téléphone en lecture.
- Programme PC : aucun changement.

