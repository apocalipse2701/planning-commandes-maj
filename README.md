# Planning Commandes — mises à jour

Dernière version : **2.10.0** (30/10/2026).

| | Version manuelle | Version « mail » (commandes relevées dans la boîte mail) |
|---|---|---|
| **Téléphone Android** | [PlanningCommandes.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes.apk) | [PlanningCommandes-mail.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-mail.apk) |
| **PC Windows** | [PlanningPDF.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF.exe) | [PlanningPDF-mail.exe](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningPDF-mail.exe) |

**Pour un proche** (conjoint…) qui veut seulement voir votre planning à jour : [PlanningCommandes-lecture.apk](https://github.com/apocalipse2701/planning-commandes-maj/releases/latest/download/PlanningCommandes-lecture.apk) — à régler avec le kDrive et le code de partage (Réglages › Partage du planning sur votre téléphone).

**PC** : placez l'exe dans votre dossier PlanningPDF habituel (celui qui contient `codes.txt` et le dossier `commande`), à la place de l'ancien — pas dans Téléchargements.

Une fois installées, l'application et le programme PC se mettent à jour d'eux-mêmes à partir d'ici.
Toutes les versions : [Releases](https://github.com/apocalipse2701/planning-commandes-maj/releases).

## Nouveautés de la version 2.10.0


**Sauvegarde des bulletins sur un NAS ou un kDrive (PC et Android)**
- Tous les bulletins rangés, avec leurs dossiers année et mois, peuvent être copiés sur un autre support. Seuls les nouveaux ou modifiés partent ; rien n'est effacé à la destination.
- **Téléphone** : Réglages › **Sauvegarde des bulletins** — NAS Synology, NAS QNAP, kDrive ou autre serveur WebDAV, en HTTPS.
  - **Sauvegarder maintenant**, **Tout renvoyer**, ou sauvegarde automatique après chaque nouveau bulletin.
  - **Reprendre le serveur du partage du planning** recopie l'adresse, le compte et le certificat déjà réglés.
  - Certificat d'origine du NAS ou adresse IP : « Faire confiance à ce certificat », comme pour le partage.
  - Bouton **Sauvegarder sur le NAS** dans Commandes › Bulletins rangés.
- **PC** : Fichier › **Sauvegarder les bulletins (NAS, kDrive…)…** — copie du dossier « commande » vers un dossier au choix : partage réseau du NAS (\\\\NAS\\dossier ou lecteur réseau), dossier kDrive synchronisé, clé USB… ; à la demande ou automatiquement après chaque nouveau bulletin rangé.

