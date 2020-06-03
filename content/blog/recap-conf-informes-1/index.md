---
title: Récapitulatif Conf-Informés
date: "2020-06-03"
description: "Hello World"
---


# Topics

## Deno introduction

https://www.notion.so/keziahmoselle/Article-Deno-26bd9db5d2de4074878438788ccbd99a

## Vite and VitePress

Vite is an opinionated web dev build tool that serves your code via native ES Module imports during dev and bundles it with [Rollup](https://rollupjs.org/) for production.

- Lightning fast cold server start
- Instant hot module replacement (HMR)
- True on-demand compilation

Projet similaire : Snowpack. [Les différences étant](https://github.com/vuejs/vite#how-is-this-different-from-snowpack) :

- HMR localisé contrairement à un reload de la page
- Vite a pour but d'améliorer l'expérience de dev de Vue et de minimiser le besoin de configuration (pour avoir un rapide démarrage sans prise de tête)
- Vite peut faire fonctionner d'autres frameworks que Vue (React avec es-react ou React depuis Pika CDN)
**Projets / Idées de projets**

- VitePress
    - Blog Dev Corner

## Webflow

@edimitchel TO COMPLETE

## Visual Studio Code Custom Editor API
Pour faire une transition avec Webflow et clore nos discussions (ça fait quand même déjà 1h30 qu'on est ensemble!), j'aimerai vous parler d'une fonctionnalité d'un IDE bien connu (VS Code).

Depuis peu, VSCode propose une nouvelle API nommée Custom Editor API.

[https://code.visualstudio.com/api/extension-guides/custom-editors](https://code.visualstudio.com/api/extension-guides/custom-editors)

En résumé, cette API permet de pouvoir substituer l'éditeur de texte brut par un éditeur personnalisé (rapatrié par une extension). Ainsi, il sera possible de :

- Visualiser des assets, comme des élément 3D ou simples images directement depuis VS Code.
- Créer un éditeur WYSIWYG pour des contenus riches (Markdown, YAML).
- Proposer un affichage alternative aux fichiers de données struturés (CSV, JSON ou XML).
- Créer une expérience d'édition inédite de fichier texte ou binaires.

Une super API qui permet d'étendre l'utilisation que l'on pourrait faire de VS Code !

**Projets / Idées de projets**

- Un genre de Webflow (drag and drop de composants React ou Vue) lié à ES Lint pour un formatage de code aux oignons.

    — Quelques uns on fait part de leur enthousiasme envers ce projet, il sera prévu prochainement des discussions autour de ce projet, pour mettre à plat nos idées, conceptualiser et planifier les fonctionnalités.