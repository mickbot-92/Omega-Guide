---
title: "Omega"
sidebar_position: 2
pagination_next: null
pagination_prev: cfw/choose-a-cfw
---

:::info
Vous avez besoin d'une calculatrice débloquée. [Pour la débloquer continuez ici](/docs/intro)
:::

Cette page expliquera comment installer Omega, en considérant que vous avez une calculatrice débloquée.

### Ce dont vous avez besoin

- Un PC avec un navigateur basé Chromium (on recommande d'utiliser directement [Chromium](https://www.chromium.org/chromium-projects/))
- Une calculatrice Numworks débloquée

### Section I - Préparer le mode Recovery

Si votre modèle est n0110, entrez le mode Recovery en mainteant "6" et en appuyant sur "reset".
Si votre modèle est n0110, entrez le mode Recovery en branchant votre calculatrice et en appuyant sur "reset".

### Section II - Installation d'Omega

1. Ouvrez [le site web d'Omega](https://getomega.dev/install)
2. Cloquez sur "Récupération" et sélectionnez "STM32 BOOTLOADER"
3. Attendez un peu jusqu'à ce que la calculatrice affiche "Recovery Mode" sur l'écran
4. Si la calculatrice n'est pas connectée automatiquement, cliquez sur "Détecter la calculatrice" et sélectionnez "Numworks Calculator"
5. Maintenant vous pouvez cliquer sur "Installer Omega" et au bout de quelques secondes, Omega devrait être installé sur votre calculatrice.

### Section III - Comment utiliser votre nouvelle calculatrice (pas pour n0100)

Il y a de nouvelles fonctions sur votre calculatrice, vous devez les connaitre.
Il y a un nouveau système de "Slot". Votre calculatrice a 2 slots et peut stocker 2 firmwares. ils ne peuvent pas fonctionner en même temps mais en utilisant reset vous pouvez passer de l'un à l'autre:
- Maintenez 1 et appuyez sur reset pour lancer le Slot A (contient Omega par défaut)
- Maintenez 2 et appuyez sur reset pour lancer le Slot B (peut être vite ou contenir Epsilon)
- Maintenez 4 et appuyez sur reset pour ouvrir le bootloader, vous serez en mesure de voir quel slot contient quel firmware et vous pourrez installer n'importe quel firmware sans bloquer la calculatrice.
- Vous ne pouvez pas lancer un autre firmware si vous activez le mode examen, vous devez le désactiver pour le faire.

#### Section IV - Comment mettre à jour ?

Pour mettre à jour Omega, ouvrez le bootloader en maintenant 4 et en appuyant sur reset, branchez votre calculatrice au PC, ouvrez le site web d'Omega, et installez-le normalement.

Pour mettre à jour le bootloader, démarrez en mode Recovery en cliquant sur reset en maintenant  la touche 6, branchez votre calculatrice au PC, ouvrez le site web d'Omega, connectez la calculatrice en mode Recovery, et installez Omega de cette manière.

### Fonctions facultatives

Maintenant qu'Omega est installé, il y a certaines choses que vous pouvez faire :

#### Applis externes (pas pour n0100)

Omega supporte les applis externes, il y en a quelques unes mais elles sont utiles. Voici comment les installer:
1. Ouvrez la [page des applis externes](https://external.getomega.dev/)
2. Sélectionnez les applis que vous voulez installer
3. Ajoutez n'importe quel fichier que vous voulez utiliser avec vos applis
4. Ajoutez un fond d'écran si vous le souhaitez
5. Activez le support des icônes si vous voulez de jolies icônes sur vos applis
6. Cliquez sur Installer

#### Installer Epsilon (pas pour n0100)

Vous pouvez installer Epsilon sur bootloader sans bloquer la calculatrice.

Allez voir [Installer Epsilon depuis le Softloader](/docs/cfw/install-epsilon-from-softloader)

#### Créer votre propre version

Omega est open-source, vous pouvez récupérer le code et l'utiliser comme vous le souhaitez. Vous trouverez tout sur le [repo GitHub d'Omega](https://github.com/Omega-Numworks/Omega)

### Fini

Vous avez maintenant Omega installé sur votre calculatrice. Vous pouvez ajouter des scripts Python de la même manière qu'avant depuis le [workshop de Numworks](https://my.numworks.com/python/)
