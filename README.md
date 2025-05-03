Tutoriel : Installer Docker + Portainer sur une Raspberry Pi via SSH

Ce projet vous guide pas à pas pour transformer une Raspberry Pi (OS Lite 32 bits) en un mini serveur auto-hébergé avec Docker, géré depuis une interface web grâce à Portainer. Le tout est accessible à distance via SSH.

✅ Objectif

Connexion SSH à la Raspberry Pi (mode headless)

Installation de Docker

Déploiement de Portainer pour gérer Docker via une interface web

Mise en ligne du projet sur GitHub

🧰 Prérequis

Une Raspberry Pi (3, 4 ou Zero 2 W)

Carte microSD avec Raspberry Pi OS Lite 32 bits

Connexion réseau (Wi-Fi ou Ethernet)

Un autre ordinateur pour se connecter en SSH

Un compte GitHub (facultatif pour versionner le projet)

1️⃣ Activer SSH (si vous n’avez pas d’écran)

Insérez la carte SD dans votre ordinateur

Accédez à la partition nommée boot

Créez un fichier vide nommé ssh (sans extension)
