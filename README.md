# Planning Commandes — mises à jour

Dernière version : **2.9.5** (28/10/2026).

| | Version manuelle | Version « mail » (commandes relevées dans la boîte mail) |
|---|---|---|
| **Téléphone Android** | [PlanningCommandes.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes.apk) | [PlanningCommandes-mail.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-mail.apk) |
| **PC Windows** | [PlanningPDF.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF.exe) | [PlanningPDF-mail.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF-mail.exe) |

**Pour un proche** (conjoint…) qui veut seulement voir votre planning à jour : [PlanningCommandes-lecture.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-lecture.apk) — à régler avec le kDrive et le code de partage (Réglages › Partage du planning sur votre téléphone).

**PC** : placez l'exe dans votre dossier PlanningPDF habituel (celui qui contient `codes.txt` et le dossier `commande`), à la place de l'ancien — pas dans Téléchargements.

Une fois installées, l'application et le programme PC se mettent à jour d'eux-mêmes à partir d'ici.
Toutes les versions : [Releases](https://github.com/apocalipse2701/planning-commandes-maj/releases).

## Nouveautés de la version 2.9.5


**Partage du planning : NAS joint par son adresse IP (Android)**
- Avec l'adresse IP du NAS (ou son certificat d'origine), l'envoi échouait : « certificat du serveur non reconnu ». Let's Encrypt ne délivre pas de certificat pour une adresse IP.
- L'application propose maintenant de **faire confiance au certificat du NAS** : elle affiche son empreinte SHA-256 ; une fois accepté, seul CE certificat est accepté pour ce serveur. Un autre certificat à la même adresse est refusé, et la question est reposée.
- Rien n'est envoyé (ni identifiant, ni mot de passe, ni planning) tant que le certificat n'est pas accepté.
- Réglages › Partage du planning : l'empreinte acceptée est affichée, pour comparer avec l'autre téléphone, avec un bouton « Ne plus faire confiance ». Changer l'adresse du serveur oublie le certificat accepté.
- Même fonctionnement sur le téléphone en lecture.
- Programme PC : aucun changement.

