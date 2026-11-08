# NEXORA Devs Toolbox

Publications officielles de **NEXORA Devs Toolbox** pour Windows.

## Installer

1. Télécharge [NEXORA-Devs-Toolbox.exe](https://github.com/Trdgi4djyds/NEXORA-portable/releases/latest/download/NEXORA-Devs-Toolbox.exe) (dernière version).
2. Lance-le : il vérifie la signature du manifeste et l’empreinte SHA-256 de chaque fichier, installe NEXORA dans ton dossier utilisateur (sans droits d’administrateur), crée les raccourcis et tient le logiciel à jour.

Une licence NEXORA (gratuite ou Pro) est demandée au premier lancement.

## Vérifier une publication

Chaque version contient `nexora.manifest.json`, signé (`nexora.manifest.sig`, Ed25519), et `SHA256SUMS.txt`. Le lanceur refuse toute publication non signée, modifiée ou plus ancienne que celle déjà installée.
