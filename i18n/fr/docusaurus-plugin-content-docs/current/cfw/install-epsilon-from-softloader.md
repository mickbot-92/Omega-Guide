---
title: "Installer Epsilon depuis le softloader"
sidebar_position: 4
pagination_next: null
pagination_prev: cfw/choose-a-cfw
---

:::danger
Suivre ce guide peut mettre en danger votre calculatrice. Installer Epsilon de la mauvaise manière sur votre calculatrice pourrait la bloquer. Suivez **STRICTEMENT** ce qui est dit sur cette page pour être sûr(e) que votre calculatrice n'est pas en danger.
:::

:::caution
La dernière version d'Epsilon pourrait ne pas être sûre, vérifiez la dernière version. Dernière version sûre connue: **22.2.0**
:::

:::info
Cette page est inutile si vous avez une n0100, étant donné que vous pouvez changer entre un CFW et Epsilon sans bloquer votre calculatrice. La n0100 n'est pas compatible avec les bootloader custom.
:::

### Lecture obligatoire

Nous allons maintenant installer Epsilon sur un slot de la calculatrice, en considérant que vous avez un bootloader qui le permet

### Ce dont vous avez besoin

- Un PC avec un navigateur basé Chromium (on recommande d'utiliser directement [Chromium](https://www.chromium.org/chromium-projects/))
- Un bootloader custom compatible installé (si vous ne savez pas, regardez [cette page](/docs/cfw/choose-a-cfw))

### Section I - Ouvrir le bootloader

Si votre CFW inclut un bootloader qui permet d'installer un firmware depuis celui-ci, vous devriez donc ouvrir le bootloader et le rendre prêt à installer quoi que ce soit. De l'aide peut être trouvée sur [cette page](/docs/cfw/choose-a-cfw)

### Section II - Installation

1. Vérifiez que votre calculatrice est dans le bootloader, prête à installer quoi que ce soit. Elle **NE DOIT PAS** être en mode Recovery (écran noir + LED rouge) étant donné que ça permettrait à Numworks de bloquer votre calculatrice
2. Ouvrez la [page de mise à jour Numworks](https://numworks.com/update)
3. Suivez les instructions mais s'il vous demande de faire quoi que ce soit sur votre calculatrice, ne le faites pas à moins que ce soit la connecter à votre PC. Le site devrait voir la version 0.0.0
4. À la fin l'installateur sera bloqué et pourrait donner une erreur, c'est parce qu'il ne peut pas redémarrer la calculatrice. Ne vous inquiétez pas, Epsilon est installé, appuyez juste sur RESET et tout est bon.

Maintenant vous avez Epsilon avec un bootloader custom donc votre calculatrice n'est pas bloquée.

Epsilon a normalement été installé sur les deux slots. Donc si vous aviez un CFW, il a été effacé, seul le bootloader reste. Pour le réinstaller vous pouvez le faire normalement depuis le bootloader ou en mode Recovery, faites juste attention à ne pas installer Epsilon à la place.

Il est recommandé de garder votre CFW en Slot A.

### GG

Vous avez maintenant Epsion et un CFW en même temps, Epsilon sur un slot, votre CFW sur l'autre. Vous pouvez maintenant changer quand vous voulez, cela fonctionne différemment en fonction de votre CFW mais l'objectif est juste de changer entre les deux slots.
