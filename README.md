# Planning Commandes — mises à jour

Dernière version : **2.9.4** (28/10/2026).

| | Version manuelle | Version « mail » (commandes relevées dans la boîte mail) |
|---|---|---|
| **Téléphone Android** | [PlanningCommandes.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes.apk) | [PlanningCommandes-mail.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-mail.apk) |
| **PC Windows** | [PlanningPDF.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF.exe) | [PlanningPDF-mail.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF-mail.exe) |

**Pour un proche** (conjoint…) qui veut seulement voir votre planning à jour : [PlanningCommandes-lecture.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-lecture.apk) — à régler avec le kDrive et le code de partage (Réglages › Partage du planning sur votre téléphone).

**PC** : placez l'exe dans votre dossier PlanningPDF habituel (celui qui contient `codes.txt` et le dossier `commande`), à la place de l'ancien — pas dans Téléchargements.

Une fois installées, l'application et le programme PC se mettent à jour d'eux-mêmes à partir d'ici.
Toutes les versions : [Releases](https://github.com/apocalipse2701/planning-commandes-maj/releases).

## Nouveautés de la version 2.9.4


**Partage du planning par un NAS Synology (Android)**
- Le partage avec la version lecture peut passer par votre **NAS Synology** : son accès WebDAV (paquet gratuit « WebDAV Server ») sert à la place du kDrive, dont l'offre gratuite n'a pas de WebDAV.
- Réglages › Partage du planning : choix du serveur **NAS Synology** (proposé d'abord), **kDrive** ou **Autre WebDAV**. Les champs, l'aide et le dossier proposé s'adaptent :
  - NAS : adresse DDNS (ex. `monnas.synology.me`, port 5006 en HTTPS pris par défaut), utilisateur du NAS, mot de passe, dossier partagé `Planning`.
- « Comment faire ? » pour le NAS : installer WebDAV Server (HTTPS), créer le dossier partagé et un utilisateur réservé, DDNS et port 5006 sur la box, certificat Let's Encrypt.
- Messages d'erreur adaptés : NAS injoignable (port non redirigé, NAS éteint), certificat non reconnu, droits de l'utilisateur, WebDAV non autorisé, dossiers partagés visibles.
- Les adresses en `http://` sont refusées : le mot de passe et le planning ne circulent qu'en HTTPS.
- Programme PC : aucun changement.

