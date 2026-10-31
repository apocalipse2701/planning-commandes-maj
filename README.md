# Planning Commandes — mises à jour

Dernière version : **2.13.0** (31/10/2026).

| | Version manuelle | Version « mail » (commandes relevées dans la boîte mail) |
|---|---|---|
| **Téléphone Android** | [PlanningCommandes.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes.apk) | [PlanningCommandes-mail.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-mail.apk) |
| **PC Windows** | [PlanningPDF.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF.exe) | [PlanningPDF-mail.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF-mail.exe) |

**Pour un proche** (conjoint…) qui veut seulement voir votre planning à jour : [PlanningCommandes-lecture.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-lecture.apk) — à régler avec le kDrive et le code de partage (Réglages › Partage du planning sur votre téléphone).

**PC** : placez l'exe dans votre dossier PlanningPDF habituel (celui qui contient `codes.txt` et le dossier `commande`), à la place de l'ancien — pas dans Téléchargements.

Une fois installées, l'application et le programme PC se mettent à jour d'eux-mêmes à partir d'ici.
Toutes les versions : [Releases](https://github.com/apocalipse2701/planning-commandes-maj/releases).

## Nouveautés de la version 2.13.0


**Grève posée seulement à la réception de l'avis de l'établissement (PC et Android)**
- À l'envoi d'une DII, le filigrane GRÈVE n'est plus posé tout de suite. Nouvelle case (envoi direct) : « Filigrane GRÈVE à la réception de l'avis de l'établissement (cadre partie 1 rempli) ».
- L'application cherche dans la boîte mail le formulaire DII renvoyé par l'établissement : en pièce jointe d'une réponse, ou d'un message du destinataire.
- Elle vérifie que la **partie 1 du « Cadre réservé à l'établissement »** est remplie intégralement : n° de DII, représentant, fonction, service, nom de l'agent, date et heure de réception, mode de réception, lieu et date.
  - **Complète** : l'avis est noté et le **filigrane GRÈVE est posé** sur le jour déclaré, avec un message (notification sur le téléphone).
  - **Incomplète**, ou formulaire imprimé, scanné ou aplati : pas de grève. L'application dit ce qui manque, avec **Ouvrir l'avis reçu** et **Avis vérifié : mettre la grève** pour valider soi-même.
- Où le voir : détail du jour (téléphone et PC) et Fichier › Suivi des DII envoyées (PC).
- Envoi par l'application mail ou la messagerie du PC : la grève se pose à la main (« Jour de grève ») à la réception de l'avis.
- Le bouton « Jour de grève » reste disponible à tout moment.

