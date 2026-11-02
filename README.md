# Planning Commandes — mises à jour

Dernière version : **2.14.0** (02/11/2026).

| | Version manuelle | Version « mail » (commandes relevées dans la boîte mail) |
|---|---|---|
| **Téléphone Android** | [PlanningCommandes.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes.apk) | [PlanningCommandes-mail.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-mail.apk) |
| **PC Windows** | [PlanningPDF.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF.exe) | [PlanningPDF-mail.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF-mail.exe) |

**Pour un proche** (conjoint…) qui veut seulement voir votre planning à jour : [PlanningCommandes-lecture.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-lecture.apk) — à régler avec le kDrive et le code de partage (Réglages › Partage du planning sur votre téléphone).

**PC** : placez l'exe dans votre dossier PlanningPDF habituel (celui qui contient `codes.txt` et le dossier `commande`), à la place de l'ancien — pas dans Téléchargements.

Une fois installées, l'application et le programme PC se mettent à jour d'eux-mêmes à partir d'ici.
Toutes les versions : [Releases](https://github.com/apocalipse2701/planning-commandes-maj/releases).

## Nouveautés de la version 2.14.0


**DII acceptée : l'application lit les avis du service DII (PC et Android, version « mail »)**
- Nouveau réglage **Avis de l'établissement attendus de** : l'adresse du service DII qui renvoie le formulaire. Plusieurs adresses : séparées par des virgules.
  - Par défaut, c'est l'adresse écrite en haut du formulaire vierge, lue dans le PDF : rien n'est inscrit dans l'application.
  - Téléphone : dans la fenêtre DII, partie Envoi. PC : Fichier › **Suivi des DII (avis de l'établissement)…**
- L'application lit les messages de cette adresse des 60 derniers jours, à chaque relevé (toutes les heures), à l'ouverture et avec **Vérifier**. Elle les lit même si la DII a été envoyée autrement (application mail, papier…).
- Pour chaque formulaire DII joint, elle contrôle le **« Cadre réservé à l'établissement »** :
  - **partie 1** : n° de DII, représentant, fonction, service, nom de l'agent, date et heure de réception, mode de réception, lieu et date ;
  - **partie 2** aussi, si vous avez rempli la vôtre (renoncer ou reprendre).
- **Tout rempli** : DII **acceptée**, et le **filigrane GRÈVE** est posé sur le jour de grève **lu dans le formulaire** (partie 1 de l'agent). Vous êtes prévenu : notification sur le téléphone, fenêtre sur le PC.
- **Incomplet**, ou formulaire scanné : pas de grève. L'application dit ce qui manque, avec **Ouvrir l'avis reçu** et **Avis vérifié : mettre la grève**.
- Formulaire d'un autre agent (nom différent de celui du planning) : ignoré.
- Les avis sont rangés avec les commandes (« 2026-11-03 - DII avis de l'établissement.pdf ») et affichés dans le détail du jour.

