# Planning Commandes — mises à jour

Dernière version : **2.7.0** (27/10/2026).

| | Version manuelle | Version « mail » (commandes relevées dans la boîte mail) |
|---|---|---|
| **Téléphone Android** | [PlanningCommandes.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes.apk) | [PlanningCommandes-mail.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-mail.apk) |
| **PC Windows** | [PlanningPDF.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF.exe) | [PlanningPDF-mail.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF-mail.exe) |

Une fois installées, l'application et le programme PC se mettent à jour d'eux-mêmes à partir d'ici.
Toutes les versions : [Releases](https://github.com/apocalipse2701/planning-commandes-maj/releases).

## Nouveautés de la version 2.7.0


**Confirmer la réception d'une commande à l'expéditeur (PC et Android)**
- Bouton **Confirmer la réception** sur chaque commande :
  - **téléphone** : dans les résultats de l'ajout et dans « Commandes importées » ;
  - **PC** : fenêtre ouverte dès qu'une commande arrive par mail, et Fichier › Confirmer la réception d'une commande….
- Le message est préparé à partir d'un modèle réglable : Réglages › Confirmation de réception, ou sur le PC Fichier › Message de confirmation….
  - `{type}`, `{debut}`, `{fin}`, `{edition}` et `{agent}` y sont remplacés.
  - Il est relu, et modifiable, avant l'envoi.
- **Version « mail »** : envoi **direct par l'application**, sans ouvrir d'autre application.
  - Depuis la boîte réglée, avec le même mot de passe.
  - En réponse au mail reçu, donc dans le même fil de discussion.
  - Toujours chiffré : SMTP sur le port 465 en SSL, ou 587 avec STARTTLS. Sans chiffrement, rien ne part.
  - Le serveur d'envoi est rempli d'après le fournisseur (Free, Orange, SFR, Bbox, La Poste, Gmail, Yahoo, iCloud, GMX, Infomaniak) ; il est modifiable dans « Serveur de messagerie ».
- **Version manuelle** : l'application mail (ou la messagerie du PC) s'ouvre avec le message prêt.
- **Destinataire** : l'expéditeur du mail reçu (adresse de réponse). Pour un bulletin ajouté à la main, le destinataire est l'adresse réglée ou un expéditeur connu.
- La commande affiche ensuite « ✓ Réception confirmée à … le … ».

