---
title: "Signalement des problèmes et communication avec les modérateurs/trices"
linkTitle: "Signaler et Communiquer"
weight: 40
description: >
  Comment signaler les problèmes et interagir avec l’équipe de modération.
---
{{% pageinfo %}}
<h5 class="text-center">This page was manually translated on 05/10/23. </br>Please utilize the English docs for the most up to date policies.</h5>
{{% /pageinfo %}}

Il y a trois façons de correspondre avec l’équipe de Modération d'Hachyderm  :

- [Attentes](#expectations)
- [Comment et quand utiliser le Courriel](#how-and-when-to-use-email)
- [Comment et quand utiliser l’Interface Utilisateur de Mastodon](#how-and-when-to-use-the-mastodon-ui)
  - [Ce que vous devriez inclure dans votre rapport](#what-you-should-include-in-your-report)
    - [Limites de l’Interface d’Administration de Mastodon](#limitations-of-the-mastodon-admin-interface)
- [Comment et quand utiliser l’outil de Suivi des Problèmes GitHub](#how-and-when-to-use-the-github-issue-tracker)

En général, l’interface utilisateur de Mastodon (c.-à-d. la fonctionnalité "rapport" sur Hachyderm.io) est utilisée spécifiquement pour signaler les postes, les utilisateurs et les domaines. Le suivi des problèmes de la communauté GitHub est destiné à d’autres types de rapports, ainsi qu’à soulever d’autres questions et conversations avec l’équipe de modération d'Hachyderm. En option, les utilisateurs peuvent également nous envoyer des informations par e-mail si ni les rapports Mastodon ni les GitHub Issues ne sont appropriés pour la conversation.

## Attentes

Nos règles de serveur s’appliquent toujours lors du dépôt d’un rapport ou de toute autre communication avec les équipes de modération et d’infrastructure.

## Comment et Quand utiliser le Courriel ?

En général, l’équipe de modération ne doit être contactée que par courriel à :

* Compléter un rapport/signalement dans l’Interface Utilisateur Mastodon
* Fournir un rapport ou une autre communication qui ne peut pas se trouver dans un forum public, comme l’outil de "Suivi des Problèmes" (Issue Tracker) de GitHub, et qui ne peut pas être soumis via l’IU Mastodon.
* Demander des informations sur la création d’un [compte spécialisé](../../account-types/).

En bref : veuillez prioriser l’utilisation de l’Interface Utilisateur Mastodon et/ou GitHub aussi souvent que possible. Cela dit, si vous devez communiquer avec l’équipe d’administration pour l’une des situations ci-dessus ou une autre zone grise, veuillez utiliser [admin@hachyderm.io](mailto:admin@hachyderm.io).

## Comment et Quand utiliser l’IU Mastodon

L’IU Mastodon, c.-à-d. ce que vous voyez lorsque vous utilisez Hachyderm.io ou l’instance Mastodon de votre choix, devrait généralement être utilisé pour signaler les problèmes qui peuvent être signalés via des publications individuelles. Ceci est généralement utilisé pour :

* Signaler les publications individuelles, mais pas l’utilisateur dans son ensemble
* Signaler un utilisateur via ses publications
* Reporting d’un domaine via les posts de leurs utilisateurs

Pour en savoir plus sur la fonctionnalité de rapport et ce que nous voyons lorsque vous nous envoyez un rapport, veuillez consulter notre [page de documentation Fonctionnalité de Signalement](../../mastodon/moderation/report-feature/).

### Ce que vous devriez inclure dans votre signalement

* Inclure des publications spécifiques, le cas échéant
    * Ceci inclut si vous signalez un utilisateur spécifique en tant qu’individu ou en tant que représentation générale d’un serveur dédié à ce type de comportement.
    * Notez qu’il est important d’inclure les postes, le cas échéant, car la fonctionnalité de signalement conserve les postes même si l’utilisateur / son administrateur serveur supprime les postes ou suspend le compte de l’utilisateur. Donc, si un utilisateur a posté et supprimé ces messages, nous ne le verrons pas en regardant la chronologie (timeline), mais l’interface les conservera si vous les incluez.
* Toujours inclure le contexte lorsque vous êtes invité à entrer des Commentaires Supplémentaires, même si c’est évident. Cela peut être aussi succinct que "spam".
    * Si vous nous envoyez un rapport pour une violation de serveur et que le contenu publié n’est pas en anglais, veuillez fournir la traduction et le contexte pertinent. Dans de nombreux cas, les outils de traduction en ligne ne peuvent traduire directement les mots, mais pas le sens communément compris (ou "dogwhistled"). Si vous manquez de caractères, veuillez soumettre le rapport et nous dire que vous nous avez envoyé un courriel, et envoyez-nous un courriel à [admin@hachyderm.io](mailto:admin@hachyderm.io).
    * Si vous nous envoyez un rapport avec une brève description, même un mot, assurez-vous qu’il reflète bien la situation. Si la description ne correspond pas à ce qui est inclus dans le rapport, nous fermerons le rapport.
    * Si vous nous envoyez un rapport de contenu problématique où les éléments visuels peuvent être traumatisants en eux-mêmes, vous _pouvez_ choisir de ne pas inclure
      les postes, mais veuillez toujours inclure ce que nous verrons lorsque nous regarderons
      le compte de l’utilisateur déclaré ou le serveur signalé. Nous avons des modérateurs pour des tâches comme celles-ci quand elles apparaissent.

 
Ce qu’il faut savoir au sujet des Commentaires Supplémentaires :

La limitation la plus importante que vous devriez savoir est que le champ Commentaires Supplémentaires à une limite de caractères de 1000 caractères (à l'heure où nous écrivons). Si vous avez besoin de fournir plus de contexte, ou la traduction prend plus de 1000 caractères, s’il vous plaît :

* Envoyer le rapport avec ce que vous pouvez 
* Assurez-vous de laisser suffisamment d’espace pour nous informer qu’il y a un courriel supplémentaire.
* Envoyez-nous un courriel à [admin@hachyderm.io](mailto:admin@hachyderm.io)

**_Remarque : si nous recevons un rapport vide et que nous ne voyons pas de cause claire, nous fermerons le rapport sans action de modération._**

#### Limites de l’Interface d’Administration de Mastodon

Lorsque nous recevons un rapport, nous ne pouvons pas faire de suivi auprès de l’utilisateur pour lui demander des renseignements supplémentaires à l’aide des outils d’administration.

Comment cela vous touche :

Si vous signalez un problème et que vous n’incluez pas suffisamment d’information ou de moyen pour que nous puissions communiquer avec vous.
Clairement, nous pourrions ne pas être en mesure de prendre les mesures appropriées.
Veuillez donc vous assurer d’inclure les publications, les commentaires et le contexte, et envoyez-nous un courriel à [admin@hachyderm.io](mailto:admin@hachyderm.io) au besoin.

## Comment et Quand utiliser l’outil de Suivi des Problèmes GitHub

Le [Community's GitHub Issues](https://github.com/hachyderm/community/issues),
a.k.a. Issue Tracker, est pour communiquer avec les équipes modération _et_ d'infrastructure 
Pour créer une "issue" :

1. Allez à [github.com/hachyderm/community/issues](https://github.com/hachyderm/community/issues)
1. Cliquez sur "New Issue" dans le coin supérieur droit.
1. Sélectionnez l’un des modèles de problème qui s’applique à vous ou à votre situation.
1. Entrez les renseignements nécessaires sur le problème. Selon le modèle, il peut y avoir des indications sur les renseignements à inclure.

"The Community Issues" peuvent toujours être utilisés pour rapporter des domaines, comme vous le feriez dans l’interface utilisateur.
Il peut également être utilisé pour demander des émoticônes, signaler une panne de service (vous pouvez également utiliser
[omg.hachyderm.io](https://omg.hachyderm.io) pour cela),
demander des mises à jour ou des changements aux documents, etc. Il existe des modèles de problèmes pour les problèmes les plus courants, qui incitent les utilisateurs à obtenir l’information dont nous avons besoin pour répondre efficacement aux demandes. Selon la nature de la demande ou de la discussion, un membre de l’équipe responsable de l’infrastructure ou de l’équipe de modération répondra.

