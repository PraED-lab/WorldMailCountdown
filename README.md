# ⏳ MailCountdown 1.1.1 – Mail countdown for Tarkov / SPT

![version](https://img.shields.io/badge/version-1.1.1-blue) ![SPT](https://img.shields.io/badge/SPT-4.1.x-green) ![license](https://img.shields.io/badge/license-MIT-lightgrey)

## 📖 Overview
In Escape from Tarkov, mail attachments (refunds, quest rewards, trader packages…) **expire after a set time**, but the game only shows an approximate duration. **MailCountdown** adds a **precise, to-the-second countdown** right on the message, so you never lose a package again.

## ✨ Features
- ⏱️ **Live countdown** shown next to any message with attachments.
- 📅 **Days + time** while more than 24 h remain: `(3D 23:35:46)`.
- 🕛 **Hours/minutes/seconds only** under 24 h: `(23:35:46)`.
- 🌍 **Follows the game language**: `D` for days in English, `J` in French.
- 🪶 **Lightweight**: a single small DLL, no config file, no game files modified on disk.

## 📥 Installation
1. Close the game.
2. Download `MailCountdown_v1.1.1.zip` from the **Releases** section.
3. Copy `BepInEx/plugins/MailCountdown.dll` into your SPT `BepInEx/plugins` folder.
4. Start the game. `BepInEx/LogOutput.log` should show a line starting with *MailCountdown v1.1.1*.

**Update:** replace the old DLL (never keep two versions at the same time).
**Uninstall:** delete `MailCountdown.dll`.

## ✅ Compatibility
- **SPT 4.1.x** with BepInEx.
- No other mod required.
- The mod changes how mail text is displayed, so it may conflict with another mod that edits the same text. Please report any conflict.

## ⚠️ Known limitations
- If a game update changes the mail UI, the countdown may stop showing. The BepInEx log then shows an init or postfix error line.
- Tested on SPT 4.1.x only.

## 🐛 Bug or suggestion?
Open an **issue** and attach your `BepInEx/LogOutput.log`.

## 👤 Author
**PraED_TV** (PraED-lab) · Released under the MIT license.




---------------------------------------------------------------------------------------------------------------





# ⏳ MailCountdown 1.1.1 – Compte à rebours dans le courrier (Tarkov / SPT)

## 📖 Présentation
Dans Escape from Tarkov, les pièces jointes du courrier (remboursements, récompenses de quêtes, colis des marchands…) **expirent au bout d'un certain temps**, mais le jeu n'affiche qu'une durée approximative. **MailCountdown** ajoute un **compte à rebours précis, à la seconde**, directement sur le message, pour que tu ne perdes plus jamais un colis.

## ✨ Fonctionnalités
- ⏱️ **Compte à rebours en temps réel** affiché à côté du message qui contient des pièces jointes.
- 📅 **Affichage jours + heures** tant qu'il reste plus de 24 h : `(3J 23:35:46)`.
- 🕛 **Passage en heures/minutes/secondes** sous les 24 h : `(23:35:46)`.
- 🌍 **Adapté à la langue du jeu** :
  - Français : `J` pour jours
  - Anglais : `D` pour days
- 🪶 **Très léger** : une seule petite DLL, aucun fichier de configuration, aucune modification des fichiers du jeu sur le disque.

## 📥 Installation
1. Ferme le jeu.
2. Télécharge `MailCountdown_v1.1.1.zip` dans la section **Releases**.
3. Copie `BepInEx/plugins/MailCountdown.dll` dans le dossier `BepInEx/plugins` de ton SPT.
4. Lance le jeu. Dans `BepInEx/LogOutput.log`, tu dois voir : *MailCountdown v1.1.1 charge*.

**Mise à jour** : remplace simplement l'ancienne DLL (ne garde pas deux versions en même temps).
**Désinstallation** : supprime `MailCountdown.dll`.

## ✅ Compatibilité
- **SPT 4.1.x** avec BepInEx.
- Aucun autre mod nécessaire.
- Le mod modifie l'affichage du courrier. Il peut entrer en conflit avec un autre mod qui change le même texte. Signale-le-moi si tu en rencontres un.

## ⚠️ Limites connues
- Si une mise à jour du jeu change l'interface du courrier, le compte à rebours peut ne plus s'afficher. Dans ce cas, le journal BepInEx indique « Echec init » ou « Erreur postfix ».
- Mod testé uniquement sur SPT 4.1.x.

## 🐛 Bug ou suggestion ?
Ouvre une **issue** et joins ton `BepInEx/LogOutput.log`.

## 👤 Auteur
**PraED_TV** (PraED-lab)

---

## 🇬🇧 English summary
**MailCountdown** adds a live, to-the-second countdown to mail messages that have attachments in Tarkov / SPT. It shows `(3D 23:35:46)` with days, then switches to `(23:35:46)` under 24 hours. The label follows the game language (J in French, D in English). Install by copying `MailCountdown.dll` into `BepInEx/plugins` with the game closed. Built for SPT 4.1.x; no config file and no dependencies other than BepInEx.
