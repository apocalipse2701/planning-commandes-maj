# Planning Commandes — mises à jour

Dernière version : **2.12.0** (31/10/2026).

| | Version manuelle | Version « mail » (commandes relevées dans la boîte mail) |
|---|---|---|
| **Téléphone Android** | [PlanningCommandes.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes.apk) | [PlanningCommandes-mail.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-mail.apk) |
| **PC Windows** | [PlanningPDF.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF.exe) | [PlanningPDF-mail.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF-mail.exe) |

**Pour un proche** (conjoint…) qui veut seulement voir votre planning à jour : [PlanningCommandes-lecture.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-lecture.apk) — à régler avec le kDrive et le code de partage (Réglages › Partage du planning sur votre téléphone).

**PC** : placez l'exe dans votre dossier PlanningPDF habituel (celui qui contient `codes.txt` et le dossier `commande`), à la place de l'ancien — pas dans Téléchargements.

Une fois installées, l'application et le programme PC se mettent à jour d'eux-mêmes à partir d'ici.
Toutes les versions : [Releases](https://github.com/apocalipse2701/planning-commandes-maj/releases).

## Nouveautés de la version 2.12.0


**Suivi des DII envoyées : l'application prévient quand l'accusé de réception arrive (PC et Android)**
- Chaque DII envoyée directement par l'application est gardée avec son identifiant de message. Pendant 30 jours, la boîte de réception est fouillée (lecture seule) pour retrouver :
  - l'**avis de remise** du serveur (ou un **échec** de remise, ou un retard) ;
  - l'**accusé de lecture** du destinataire ;
  - une **réponse** du destinataire.
- **Téléphone** :
  - recherche à l'ouverture, puis toutes les heures en arrière-plan, et sur demande ;
  - **notification** « DII du … : remise au destinataire / lue par le destinataire » ;
  - le **détail du jour** affiche l'état : envoyée le …, remise le …, lue le …, avec un bouton **Vérifier les accusés de réception**.
- **PC** :
  - recherche avec chaque relevé de la boîte (toutes les heures), et toutes les 15 min pendant l'heure qui suit un envoi ;
  - une fenêtre prévient de chaque nouvel accusé ;
  - le détail du jour affiche l'état, et Fichier › **Suivi des DII envoyées…** liste les envois avec **Vérifier maintenant**.
- Fonctionne avec la version « mail » (boîte réglée). L'avis de remise dépend du fournisseur ; l'accusé de lecture dépend du destinataire.

