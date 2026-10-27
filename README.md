# Planning Commandes — mises à jour

Dernière version : **2.9.0** (27/10/2026).

| | Version manuelle | Version « mail » (commandes relevées dans la boîte mail) |
|---|---|---|
| **Téléphone Android** | [PlanningCommandes.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes.apk) | [PlanningCommandes-mail.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-mail.apk) |
| **PC Windows** | [PlanningPDF.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF.exe) | [PlanningPDF-mail.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF-mail.exe) |

**Pour un proche** (conjoint…) qui veut seulement voir votre planning à jour : [PlanningCommandes-lecture.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-lecture.apk) — à régler avec le kDrive et le code de partage (Réglages › Partage du planning sur votre téléphone).

**PC** : placez l'exe dans votre dossier PlanningPDF habituel (celui qui contient `codes.txt` et le dossier `commande`), à la place de l'ancien — pas dans Téléchargements.

Une fois installées, l'application et le programme PC se mettent à jour d'eux-mêmes à partir d'ici.
Toutes les versions : [Releases](https://github.com/apocalipse2701/planning-commandes-maj/releases).

## Nouveautés de la version 2.9.0


**Nouvelle application « Planning (lecture) » : votre planning à jour sur le téléphone d'un proche**
- Nouveau fichier `PlanningCommandes-lecture.apk`, à installer sur le téléphone de la personne qui veut consulter votre planning (conjoint…). Les deux autres versions ne changent pas ; celle-ci s'installe à côté sans les remplacer.
- Elle affiche le planning (mois, page A4, détail du jour, export PDF/JPEG, agenda), les widgets et les avis « Contrairement » (fond jaune et notification), sans rien pouvoir modifier : pas d'onglet Commandes, ni note, ni grève.
- Le planning vient de votre téléphone, par votre **kDrive Infomaniak** (WebDAV) : Réglages › **Partage du planning**, à régler sur les deux téléphones avec le même compte, le même dossier et le même **code de partage**.
- Votre téléphone envoie le planning quelques secondes après chaque changement (commande ajoutée, reçue par mail, note, grève…), et à l'ouverture de l'application. Le téléphone du proche le relit à l'ouverture et toutes les heures, et met ses widgets à jour.
- Le fichier déposé sur le kDrive est **chiffré** (AES-256) avec le code de partage : sans ce code, il est illisible.
- Les avis « Contrairement » se valident séparément sur chaque téléphone ; seuls ceux des 14 derniers jours sont montrés au proche.
- Programme PC : aucun changement (le partage part du téléphone).

