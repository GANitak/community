---
title: "Robot et Poste-Automatisation"
linkTitle: "Robot et Poste-Automatisation"
weight: 40
description: >
  Pour tous les types de contenu automatisé et planifié.
---

{{% pageinfo %}}
<h5 class="text-center">This page was manually translated on 05/14/23. Please utilize the English docs for the most up to date policies.</h5>
{{% /pageinfo %}}

Si vous utilisez un compte bot et/ou que vous prévoyez d’utiliser le Poste-Planning - cet article est pour vous !

## Sommaire

- [A Propos de la Poste-Automatisation](#a-propos-de-la-poste-automatisation)
- [Règles de publication pour le contenu automatisé](#règles-de-publication-pour-le-contenu-automatisé)
- [Règles de publication et restrictions de comportement pour les bots](#règles-de-publication-et-restrictions-de-comportement-pour-les-bots)
- Tous les robots doivent être [vérifiés avec Hachyderm](../verification/)
- Le cas échéant, les comptes doivent [être vérifiés](../../mastodon/user/verification/) avec leurs domaines pertinents.

## A Propos de la Poste-Automatisation

L’automatisation de publication n’est pas toujours de nature bot ou bot-like. De nombreux comptes spécialisés utilisent le Poste-Automatisation pour communiquer avec leur base d’utilisateurs visée.
Cela peut inclure, mais sans s’y limiter, des fenêtres d’inscription pour un événement qui doit être fait dans un délai précis, des postes automatisés lorsqu’un blog est mis à jour, et ainsi de suite.

La ligne entre les postes automatisés et les postes bot est mince, et dépend principalement de si un humain a composé un poste (si elle est prévue pour maintenant ou plus tard) et si oui ou non ce poste est destiné à répéter (le "Une fois suffit" sur les [Attentes Relatives aux Comptes Spécialisés](../covenant/)).

Comme avec beaucoup de nos règles sur Hachyderm, les règles et règlements pour le bot et la publication automatisé est à propos de leur impact sur le serveur. Nous voulons que cet impact soit positif et non invasif. Nous croyons que la collaboration prospère là où il y a un véritable lien. Une véritable connexion peut se faire via des postes de bot et automatisés, mais ne peut pas prospérer si ces postes deviennent invasifs ou en concurrence les uns avec les autres négativement.

Lorsque nous appliquons les règles et les règlements sur les robots et le contenu automatisé, comme indiqué dans la section suivante, nous le faisons dans le but d’accroître la nature connectée et collaborative de la communauté Hachyderm.

## Règles de publication pour le contenu automatisé

Tous les comptes qui utilisent des publications automatisées ou planifiées doivent respecter les exigences suivantes :

- **Il y a une limite supérieure de cinq publications sélectionnées, planifiées ou automatisées par jour. Il vaut mieux réduire.**
- Les publications ne peuvent violer d’autres règles
  - Cela comprend les règles du serveur, autour des postes monétaires, spams interdiction, ou le contenu NSFW/18+ (et al)
  - Les comptes hybrides, ceux qui utilisent des postes à horaire fixe et qui sont également un autre type spécialisé, sont liés à tous les ensembles de règles pour leur type de compte hybride combiné.
  - Les publications ne peuvent pas violer les [Attentes Relatives aux Comptes Spécialisés](../covenant/)
- Il y a une exception : les postes automatisés peuvent contourner la politique "Une fois suffit", à moins qu’elle ne devienne indésirable (**_communauté discrétion_**). Donc, si vous avez besoin de poster sur votre événement, blog, etc. et rester dans le nombre total de messages par jour, c’est très bien.

Les comptes qui violent les règles ci-dessus peuvent être limités ou suspendus.

## Règles de publication et restrictions de comportement pour les bots

#### Configuration du Compte

- Tous les comptes robots doivent [être vérifiés avec Hachyderm](../verification/), ce qui signifie qu’ils acceptent les [Attentes Relatives aux Comptes Spécialisés](../covenant/).
- Tous les robots doivent cocher la case du robot dans leurs paramètres de profil. (Ouvrez l’image dans une nouvelle fenêtre pour l’agrandir.)<br />
  <img src="../mastodon-bot-account.png"
       alt="Capture d’écran de quatre cases à cocher dans les paramètres du compte : demander de suivre les demandes, il s’agit d’un compte bot, suggérer un compte à d’autres et masquer votre graphique social" 
       width="400px" />
- Les bots sont tenus de mettre le `#hachybots` hashtag dans _tous_ les postes pour permettre aux utilisateurs de s’inscrire ou non aux messages bot.

#### Restrictions Relatives au Comportement

Tous les comptes bot, et les publications similaires, doivent respecter le consentement (c.-à-d. opt-in). Cela signifie :

- Les robots peuvent répondre directement aux postes dans lesquels ils ont été tagués.
- Les robots réactionnaires ne peuvent être déclenchés / "invoqués" que par des postes qui incluent leur 'handle' /nom.
  - Mais ils ne peuvent pas "devenir spirale infernale". Essentiellement : ils _ne peuvent pas_ continuer à répondre à chaque réponse dans un fil, parce qu’ils ont été tagués une fois, et donc auto-tagué dans toutes les réponses subséquentes.
- - Les robots _ne peuvent pas_ répondre aux hashtags, aux mots-clés, etc. sans être tagués - p. ex., les robots qui répondent aux messages des utilisateurs en fonction de mots-clés et de choses semblables.
- Les robots conçus pour consommer, utiliser, stocker ou autrement traiter des données (même des données publiques) ne peuvent le faire qu’avec le consentement (opt-in).
- Les robots conçus pour le plaisir _peuvent_ contourner la politique « Une fois suffit », à moins qu’ils ne deviennent des spams (**_communauté discrétion_**). Donc, si votre bot ne répond qu’avec "klaxonner", et seulement lorsqu’il est convoqué, c’est bien.

Les comptes Bot qui violent l’un des éléments ci-dessus peuvent être limités ou interdits.
