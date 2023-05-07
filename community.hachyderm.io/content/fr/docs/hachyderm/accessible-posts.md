---
title: "Publication Accessible"
linkTitle: "Publication Accessible"
weight: 40
description: >
  Introduction à la publication accessible pour les nouveaux utilisateurs.
---

## Comment créer des publications accessibles? <!-- omit from toc -->
{{% pageinfo %}}
<h5 class="text-center">This page was manually translated on 05/07/23. </br> Please utilize the English docs for the most up to date policies.</h5>
{{% /pageinfo %}}

Cette page de documentation est un guide d’introduction de publication accessiblement sur Hachyderm. Comme guide d’introduction il y a des sujets et des sections qui devront être ajoutées et améliorées au fil du temps.

Si vous cherchez la version courte de nos questions ici sur Hachyderm,
s’il vous plaît lisez "Que voulons-nous dire quand nous parlons d’accessibilité",
"ce que vous devez savoir et nos demandes", ainsi que le résumé à la fin du document.

Si vous cherchez la nuance et le contexte sous-jacents pour les appliquer plus efficacement et participer activement au maintien de Hachyderm en tant que communauté sûre et active, veuillez lire et réfléchir plus en profondeur à chacune des sections.

- [Qu’entendons-nous par accessibilité?](#what-do-we-mean-when-we-talk-about-accessibility)
  - [Ce que vous devriez savoir et nos demandes](#what-you-should-know-and-our-asks)
  - [Interactions sur internet](#interactions-on-the-internet)
  - [Mastodon et Hachyderm](#mastodon-and-hachyderm)
- [Naviguer la complexité](#navigating-the-complexity)
  - [Sensoriel](#sensory)
    - [Visuel](#visual)
    - [Audio](#audio)
    - [Bruit](#noise)
  - [Interprétatif](#interpretive)
    - [Neurodiverse](#neurodiverse)
    - [Médical](#medical)
    - [Traumatismes et phobies](#traumas-and-phobias)
    - [Accessibilité linguistique et facilité de traduction](#language-accessibility-and-ease-of-translation)
  - [Economique](#economic)
- [Synthèse](#summary)


## Qu’entendons-nous par accessibilité?

L’accessibilité signifie que le plus grand nombre de personnes possible peuvent accéder à votre contenu s’il le souhaite. L’accessibilité ne signifie pas que vous ne pouvez pas _intentionnellement_ gérer votre contenu autrement, par exemple via un [avertissement de contenu](../content-warnings/). L’accessibilité renvoie, plutôt, aux nombreuses façons dont les gens créent habituellement des points de contrôle _non intentionnels_ autour de leur contenu.

### Ce que vous devriez savoir et nos demandes

> Personne sur Hachyderm n’est censé être un expert. Tout le monde sur Hachyderm
> est invité à aborder l’accessibilité dans un esprit de croissance et à l'itérer
> ainsi qu'à la changer au fil du temps.

Chaque fois que vous recevez une demande d’un groupe que vous ne connaissez pas encore ou avec lequel vous n’interagissez pas assez souvent pour avoir une aisance culturelle, veuillez considérer cette demande comme une occasion de croissance. Cette croissance peut se produire avec du temps et des efforts durables de votre part.

#### Nos demandes <!-- omit in toc -->

Lorsque vous publiez accessiblement :

1. Inclure un texte **alt**ernatif efficace pour les images.
   * Notez que vous ne pouvez pas ajouter de texte **alt**ernatif après avoir posté en éditant un message. Cela comprend à la fois la création d’un nouveau texte **alt**ernatif qui a été négligé ou la correction de texte de **alt**ernatif existant. Une technique courante est de commenter votre poste avec le texte **alt**ernatif
1. Utilisez PascalCase ou camelCase pour vos hashtags.
1. Apprenez à rédiger des synthèses efficaces pour du contenu audio ou vidéo.
1. Prioriser le contenu audio avec sous-titres et transcriptions, si possible.
1. Soyez conscient de la fréquence à laquelle vous publiez du contenu payant; tout le monde n’a pas le même pouvoir d’achat.
1. Apprendre comment et quand utiliser [avertissements de contenu efficace](../content-warnings/).
1. Lorsque vous rédigez des messages pour un public international, minimisez l’utilisation de l’argot et métaphore et au lieu d’utiliser littérale, directe, phrasé de manière à être facilement traduit par des outils de traduction.
1. Lorsque quelqu’un commet une erreur à l’égard de l’une ou l’autre des situations ci-dessus, veuillez l’aider si vous avez l’espace émotionnel nécessaire ou passer à autre chose. Ne honte pas ou n'agit pas de manière toxique.

Les avertissements de contenu en particulier sont une fonctionnalité utile qui s’applique à de nombreuses situations. À titre de rappel, nous _demandons_ et _recommendons_ les avertissements de contenu en règle générale plutôt qu'ils soient nécessaires.
[Synthèse de ce document](#summary) pour en savoir plus sur les raisons.)

Le reste de cette page de doc d’introduction fournira le contexte et la nuance aux demandes ci-dessus. L’utilisation des avertissements de contenu viendra fortement pour [la section d’interprétation](#interpretive).

### Interactions sur internet

La décomposition des différentes façons dont nous envoyons, recevons et interprétons le contenu sur internet peut aider à construire un cadre interne pour "ce qui est accessible".

Lorsque _récevoir_ du contenu sur Internet, ce contenu est généralement :

* Visuel<br />
  Le texte sur cette page, images statiques ou animées, vidéo
* Audition<br />
  Contenu audio non visuel comme les podcasts, ou contenu audio avec des visuels comme une vidéo.
* Tactile<br />
  Comment nous interagissons avec le contenu visuel en « cliquant ici » ou autrement en interagissant avec le contenu que nous recevons.<br />
* Economique<br />
  Contenu qui nécessite un achat individuel ou un abonnement pour y accéder.

Lors de _l’envoi_ de contenu sur Internet, le contenu est généralement :

* Visuel<br />
  Même chose que ci-dessus, mais quelque chose que nous envoyons plutôt que de recevoir.
* Audition<br />
  Même chose que ci-dessus, mais quelque chose que nous envoyons plutôt que de recevoir.
* Tactile<br />
  Même chose que ci-dessus, mais quelque chose que nous envoyons plutôt que de recevoir.


Lorsque nous interprétons du contenu sur Internet, nous utilisons :

* Nos sens disponibles
* Notre neurodiversité
* Nos expériences, y compris, mais sans s’y limiter, notre socialisation et notre culture
* Nos compas moraux et nos alignements éthiques
* Notre langue principale, parlée et signée
* Et ainsi de suite.

Générer du _contenu accessible_ est le problème combinatoire de ce qui précède. Le plus souvent,
l’accessibilité est mise en œuvre par la création d’une "sauvegarde sensorielle" de la livraison principale du contenu. Par exemple, si le contenu est audio, il aura une transcription (visuelle). Si le contenu est visuel, il aura un texte descriptif qui peut être lu de façon audible. Et ainsi de suite.

Le contenu de l’aspect interprétation est celui où les "sauvegardes sensorielles" seules sont insuffisantes. Si quelqu’un est un survivant de traumatisme, avoir une "sauvegarde sensorielle" du contenu ne résout pas la difficulté particulière qu’ils ont. Si quelqu’un est submergé sensoriellement, pivoter vers un sens différent _pourrai_ résoudre la difficulté particulière qu’il a, mais il peut aussi ne pas la résoudre. Si la difficulté qu’ils ont est que la page Web est visuellement bruyante, avoir une transcription qui décrit profondément tout ce bruit visuel et la rend auditive ne résout pas nécessairement la difficulté. En fait, ce n’est peut-être même pas souhaitable.


### Mastodon et Hachyderm

Pour le reste de cet article, nous décrirons les façons dont les Hachydermiens peuvent commencer à maximiser l’accessibilité de leurs postes dans le contexte de Mastodon.
Nous _ne décrirons pas_ comment le logiciel Mastodon lui-même peut être amélioré.
C’est seulement parce que cela dépasse la portée de cette
page et notre influence, pas parce qu’il est sans importance. Pour ceux d’entre vous qui ont des idées sur la façon dont Mastodon peut être plus accessible, nous vous recommandons de
[faire des PR ou ouvrir des issues GitHub sur le projet Mastodon repo](https://github.com/mastodon/mastodon).


## Naviguer la complexité

Pour reformuler, ceci est une introduction de ce que vous voudrez apprendre et intérioriser afin de créer des messages qui sont plus accessibles. Notez que nous n’avons pas dit "publications qui sont accessibles", seulement "publications qui sont plus accessibles". La raison en est que la portée de l’humanité est vaste, et apprendre à connaître les autres est un voyage à vie. Être vraiment accessible non seulement avec des messages, mais avec la conception de logiciels et juste la vie en général, est un but final que vous devriez vous efforcer d’atteindre, même si elle ne peut pas être vraiment réalisé.

### Sensoriel

Ce premier ensemble de "choses à considérer" lorsque vous créez du contenu est fondé sur les sens que nous avons décrits ci-dessus et qui sont utilisés lorsque d’autres _reçoivent_ le contenu que vous créez.

#### Visuel

Cette section sera la plus longue et interagira avec les autres sections ci-dessous. C’est parce qu’une grande partie du contenu de Mastodon est de nature _visuelle_, qu’il s’agisse de texte brut, de mèmes ou de GIF animés. Voici quelques exemples courants :

* Images, statiques et animées
* Vidéos
* "Texte fantaisie" et caractères spéciaux
* Emoji
* Mots-clics

Les demandes directs pour chacun de ces :

* Inclure un texte **alt**ernatif efficace
* Devrait avoir une synthèse, semblable à la fonction de texte **alt**ernatif
* Minimiser l’utilisation de "texte fantaisie" et de caractères spéciaux
* Privilégiez les noms emoji complets et plus longs que les noms plus courts
* Utiliser CamelCase

##### The contexte <!-- omit from toc -->

Comment les personnes qui ne voient pas ou ne voient pas clairement ce qui précède interagissent-elles avec le contenu ? Habituellement, avec l’aide de lecteurs d’écran. Les lecteurs d’écran sont conçus non seulement pour lire des documents en clair, comme cette page, mais aussi pour lire tout texte associé à un visuel. Pour les images et les vidéos :

* Images : texte **alt**ernatif requis
    * [Article sur la façon d’écrire un bon texte descriptif par Harvard Digital Accessibility](https://accessibility.huit.harvard.edu/describe-content-images)
*  Vidéos : soit une description récapitulative et/ou une transcription complète, le cas échéant
    * [Page de l’Initiative d’Accessibilité Web du W3C pour le contenu audio et vidéo](https://www.w3.org/WAI/media/av/av-content/)

Mais qu’en est-il du "texte fantaisiste", des émoticônes et des hashtags? En fait, qu’entendons-nous par "texte fantaisiste" ?

Les "textes fantaisistes" et les caractères spéciaux justifient en fait un article qui leur est propre, et Scope a un bel article de 2021 intitulé
[How special characters and symbols affect screen reader accessibility](https://business.scope.org.uk/article/accessibility-screen-readers-special-characters-and-unicode-symbols).
L’article montre comment différentes "polices" de caractères spéciaux, habituellement utilisées pour créer des italiques ou d’autres effets visuels, sont lues par les lecteurs d’écran pour ceux qui les utilisent.

Le cas est similaire pour les emoji. Alors que dans l’ensemble emoji standard il y a du texte associé pour un lecteur d’écran à lire, comme un pouce en l’air 👍, lors de la lecture du texte pour un emoji personnalisé le seul texte disponible est le nom qui est fourni entre les deux points.

Ce qui est important, c’est pourquoi ici, sur Hachyderm, nous privilégions les noms emoji comme « :verified » plutôt que « :v :», même si ce dernier est plus court. Lorsqu’un lecteur d’écran rencontre le texte « Jayne Cobb :v : :gh:» il se lira « Jayne Cobb v g h ». D’autre part, lorsqu’un lecteur d’écran rencontre « Jayne Cobb :verified : :github:» il se lira « Jayne Cobb verified github ». L’un est beaucoup plus accessible que l’autre.

Hashtags sont les dernier "type" très utilisé dans la section visuelle. Beaucoup de lecteurs d’écran sont conscients et capables de lire des hashtags, mais seulement lorsqu’ils utilisent un "case" alternatif (PascalCase, camelCase). Pour ceux qui ne connaissent pas, cela signifie que vous devriez utiliser le hashtag #SaturdayCaturday
Pour montrer la différence, [Belong AU a un excellent clip de 17 secondes montrant comment les lecteurs d’écran lisent les hashtags](https://twitter.com/BelongAU/status/1450711235704492035).

#### Audio

Les sources courantes de contenu audio ou audiovisuel sur les médias sociaux sont :

* Balados, messages enregistrés, etc.
* Contenu vidéo audio comme YouTube, TikTok, etc.

Les demandes pour ces:

* Lorsque le contenu vous appartient, veuillez avoir une transcription ou un document semblable à votre disposition.
* Lorsque le contenu n’est pas le vôtre, veuillez privilégier le contenu qui comporte une transcription pour un contenu plus long le plus souvent possible.
* Dans les deux cas, lorsque vous publiez le contenu, ajoutez un court résumé (similaire à la fonction de texte **alt**ernatif).

##### The contexte <!-- omit from toc -->

En raison de la taille des fichiers audio dans les publications, la plupart du contenu audio, ou du contenu audiovisuel dans le cas de la vidéo, n’est pas hébergé sur Hachyderm. Le contenu lié provient de diverses pages de nouvelles, pages de podcast, flux Twitch, YouTube, TikTok, et ainsi de suite. Sauf si vous êtes le streamer, cela signifie également que vous n’avez pas autant de contrôle sur la façon dont le contenu est affiché ou rendu, que si vous le feriez pour intégrer un GIF ou un mème (avec le texte **alt**ernatif, etc.). Pour cette raison, la plus grande demande ici est que vous synthétisez audio ou vidéo lorsque vous le publiez, de sorte que quelqu’un peut obtenir l’essentiel de ce qui est publié, même si ils ne peut pas utiliser directement le contenu. Ça aide également à commencer à être conscient des sources qui ont des sous-titres (de nombreux sites vidéo offrent des sous-titres automatisés) ainsi que des transcriptions. Si vous souhaitez obtenir un exemple de balado comportant une transcription, jetez un coup d’œil aux pages de l’épisode de PagerDuty. [Page It to the Limit podcast](https://www.pageittothelimit.com/).

#### Bruit

"Bruit" dans ce sense correspond à :

* Contenu avec "trop" d'audio et/ou visuel
* Contenu audio ou visuel "trop fort"

Les demandes pour ceux-là :

* Veuillez indiquer dans votre publication si votre contenu lié correspond à l’un ou l’autre des énoncés ci-dessus.

##### The contexte <!-- omit from toc -->

Par exemple, ce qui pourrait générer du bruit audiovisuel, essayez de naviguer sur Internet sans adblocker ou bloqueur de script. Risque de logiciels malveillants mis à part, il y a beaucoup de publicités audio et / ou visuelles placées partout sur les pages Web et il y a souvent des fenêtres pop-ups, notifications, et cookies de consentement aussi.

Ces situations sont généralement frustrantes lorsque vous essayez de naviguer dans la situation telle quelle, sans parler de ce qui se passe lorsque vous essayez de convertir la page à un sens particulier (auditif ou visuel).

La plupart de ces situations _ne s’appliquent pas_ directement sur le Fediverse. Elles apparaissent lorsque des liens vers d’autres pages et contenus apparaissent. Pour être clair, sur Hachyderm nous ne vous demandons pas d’être responsable de l’intégralité de l’internet. Cela dit, si vous publiez du contenu qui pourrait être "bruyant", cela pourrait valoir la peine de le mentionner dans votre post que fournit un lien.

### Interpretive

L’accessibilité interprétative concerne la façon dont notre esprit comprend l’information présentée. Il s’agit d’un ensemble très large de sujets, car nos esprits utilisent un grand nombre de données pour traiter l’information. En guise d’introduction, voici quelques points communs à considérer pour faciliter l’interprétation.

Presque exclusivement, la demande d’aide à l’interprétation accessible est :

* [Utiliser des avertissements bien écrits](../content-warnings/).

Puisque la question est presque toujours la même, contrairement à la section ci-dessus, cette section n’aura pas un "exemples communs" et "demande directe" modèle.  En guise d’introduction, nous soulignons certains des obstacles les plus courants à l’interprétation, nous offrons une suggestion à traiter et nous rappelons à tout le monde que nous ne demandons pas ou n’exigeons pas que quiconque devienne expert. Notre principale demande est que vous continuiez à apprendre et à grandir en conscience.

#### Neurodiverse

La neurodiversité est le terme général pour "la gamme des différences dans la fonction cérébrale individuelle et les traits comportementaux, considérés comme faisant partie de la variation normale dans la population humaine". (Oxford Dictionary) Quelques attributs communs qui font partie de la neurodiversité sont:

* TDAH
* Dyslexie, dyscalculie
* Autisme/spectre

Il y a plus que ça. Les principaux facteurs sous-jacents qui définissent les différents aspects de la neurodiversité sont des choses comme les compétences verbales et écrites, l’hyperfocus et l’hypofocus, l’interprétation sensorielle (p. ex., submerger lorsqu’il y a trop d’intrants sensoriels), la visualisation mentale, et ainsi de suite.
[L’article du Guide d’Accessibilité du Contenu Web sur l’Accessibilité Numérique et la Neurodiversité](https://wcag.com/blog/digital-accessibility-and-neurodiversity/)
a quelques excellents conseils sur le niveau de conception du logiciel qui peut également vous aider à construire votre modèle mental tout en interagissant avec d’autres.

Dans le contexte de Mastodon, ceux-ci apparaîtront généralement via des liens vers du contenu partagé plutôt que tout ce qui est hébergé sur la plateforme elle-même. Cela signifie que ce que vous pouvez faire est d’inclure les informations pertinentes lorsque vous publiez un lien vers d’autres contenus. Cela peut se faire par le biais d’une description dans le poste lui-même ou, le cas échéant, l’élaboration d’un [avertissement de contenu](../content-warning/) pour le post.


#### Médical

L’une des affections médicales les plus courantes qui peut causer des problèmes de contenu audiovisuel est la saisie.
Les convulsions photosensibles peuvent être déclenchées par stroboscopie, scintillement, et des effets visuels similaires.
Cela ne se produirait que si/quand un utilisateur a posté une image animée ou une vidéo qui contenait des effets similaires à ceux-ci. Si vous souhaitez en savoir plus à ce sujet, veuillez consulter
[Page Web de Mozilla sur les convulsions et les réactions physiques](https://developer.mozilla.org/en-US/docs/Web/Accessibility/Seizure_disorders).

Les deux autres problèmes de santé primaires qui surviennent lors de l’interaction avec les médias sociaux sont les troubles de l’alimentation et les dépendances. La première peut être déclenchée par des images d’aliments, des discussions sur le gain ou la perte de poids, etc. Cette dernière peut être déclenchée par des images et des discussions sur toute substance qui crée une dépendance, notamment :
la nourriture, l’alcool, diverses drogues récréatives et le jeu.

Nous ne demandons pas que les Hachydermiens soient des experts médicaux afin d’interagir sur la plateforme.
La principale demande est d’être conscient de situations comme celles-ci et d’utiliser des avertissements de contenu lors de la publication de contenu qui pourrait être déclenchant pour ces groupes.

#### Traumatismes et phobies

Le traumatisme est une catégorie très vaste, et la nuance de ce qui peut déclencher un traumatisme varie d’une personne à l’autre. Cela dit, il existe des exemples courants de modèles d’affichage qui peuvent être présumés généralement traumatisants :

* Si l’on affiche un message sur un traumatisme à un membre d’une communauté, soit via d’un cycle de nouvelles ou d’une expérience personnelle, le traumatisme pour le groupe collectif sera vraisemblablement déclenché.
* S’il est question de violence, on peut supposer qu’elle est traumatisante, même pour ceux qui n’ont jamais vécu ce type de violence. Cela comprend diverses formes de traumatismes violents que les humains peuvent s’infliger les uns aux autres, _ainsi que_ la violence envers les animaux et la violence envers notre environnement.
* Si vous publiez des articles sur la richesse et la pauvreté, et sur les sujets intermédiaires, on peut supposer que cela déclenchera le traumatisme de ceux qui ont dû interagir avec les systèmes économiques à partir d’un lieu défavorisé.

Il y a beaucoup plus de traumatismes que ceux-ci. Il y a aussi des phobies communes que les humains ont où les schémas de réponse dans l’esprit et le corps reflètent très directement ce qui se passe chez une personne traumatisée qui a été déclenchée. Les catégories courantes de phobies comprennent :

* Décès
* Maladie
* Espaces clos
* Hauteurs

Nous ne demandons pas aux Hachydermiens d’être des experts en traumatismes et phobies afin d’interagir sur la plateforme. Nous demandons aux utilisateurs d’utiliser des avertissements de contenu lorsqu’ils discutent de sujets lourds comme ce qui précède. C’est parce que, bien qu’il y ait beaucoup à gagner de la discussion, les personnes les plus touchées verront les mêmes conversations traumatisantes encore et encore. Surtout si c’est le Topic Du Jour (ou la semaine) ou quelque chose s’est passé dans un cycle de nouvelles récentes pour provoquer de nombreuses discussions simultanées.

#### Accessibilité linguistique et facilité de traduction

L’objectif principal ici est de s’assurer que le texte en clair et les descriptions textuelles des médias sont copiables/lisibles afin qu’ils puissent être traduits dans une langue différente de celle dans laquelle ils ont été composés. Cela permet aux utilisateurs qui ne maîtrisent peut-être pas suffisamment la langue dans laquelle le texte a été rédigé d’utiliser des outils de traduction.

Par souci de clarté : nous ne nous attendons pas à ce qu’un individu soit hyperpolyglotte. Nous ne nous attendons pas non plus à ce que les Hachydermiens postent des traductions de leurs messages. Ce que nous vous demandons, c’est d’être au courant du problème et de savoir si vous publiez quelque chose qui ne peut pas être copié ou collé dans un outil tiers pour obtenir de l’aide à la traduction si quelqu’un doit le faire.

Quelques exemples :

* Contenu vidéo avec sous-titres dans n’importe quelle langue : un autre outil linguistique peut-il être utilisé pour traduire
      les sous-titres et/ou l’hôte de la vidéo supporte-t-il plusieurs langues pour leurs sous-titres?
* Contenu vidéo avec transcription : cette transcription peut-elle être copiée/collée dans un outil de traduction?
* Poste en texte clair : le poste peut-il être copié/collé dans un outil de traduction?
* Argot : l’argot régional ne se traduit pas bien lorsque vous utilisez des outils. Si vous faites un post que
      vous voulez que les autres puissent traduire facilement, minimiser l’utilisation de l’argot.

### Économique

Dans le contexte de Mastodon, cela apparaît lorsque les "posts" faits redirige vers du contenu payant.
Le paywall peut être un achat direct pour ce contenu spécifique ou le contenu est hébergé par une entité qui nécessite un abonnement pour y accéder.

D’un point de vue d’accessibilité et d’équité : bien que les gens devraient être rémunérés pour leur travail, il est important de se rappeler que ce n’est pas tout le monde qui peut payer pour avoir accès à ce travail. Ils peuvent être désavantagés dans l’ensemble ou vivre à l’extérieur du pays ou des pays qui sont autorisés à payer pour y avoir accès.

Une autre tendance courante est que les données des utilisateurs sont un type de paiement. Dans cette situation, une personne doit généralement fournir son courriel et certains renseignements démographiques pour un accès gratuit au contenu. Comme ce qui précède, il peut s’agir d’un problème d’accessibilité pour ceux qui ont des raisons de partager leurs renseignements avec prudence. Cela est particulièrement vrai à la lumière des violations de données de plus en plus courantes, où les données fournies peuvent être utilisées pour cibler des individus et des groupes.

Ici, sur Hachyderm, _nous ne vous modérons pas_ pour afficher du contenu payant. Dans le contexte de l’accessibilité, nous vous demandons _d’être conscient_ (et de le dire) lorsque vous le faites et de gérer avec soin ce que vous choisissez de partager.

## Synthèse

La longueur de ce document particulier devrait vous indiquer que l’accessibilité exige du temps et des efforts.
En tant que guide d’introduction, il devrait aussi vous dire qu’il se passe beaucoup de choses sur notre sphère de la biodiversité.

La diversité est l’une des principales raisons pour lesquelles nous _demandons_, non pas _exigeons_, l’utilisation d’avertissements de contenu dans la plupart des cas. C’est parce qu’il y a plusieurs façons dont deux ou plusieurs groupes peuvent être dans un état de conflit authentique sans que personne ne soit dans en tort. Un exemple rapide pourrait être si quelqu’un publiait sur la perte ou le gain de poids, en temps que réponse à la récupération d’un problème médical, qui a déclenché le trouble de l’alimentation de quelqu’un d’autre. 
Un autre pourrait être quelqu’un qui a besoin de crier sur la façon dont la transphobie les blesse, tandis que quelqu’un d’autre n’a pas besoin de se rappeler que cela se produit encore aujourd’hui.

Hachyderm doit être en mesure de répondre à toutes ces situations et plus encore. Pour ce faire, nous essayons de créer un espace pour les besoins disparates de coexister. Dans les cas où une politique au niveau de l’instance ne serait pas avantageuse pour la collectivité, nous demandons aux particuliers d'[établir et maintenir leurs limites personnelles dans un espace public](../mental-health). 
Nous demandons également à chacun d’utiliser des mots-clés et des hashtags communs afin que ceux qui cherchent à filtrer ce contenu puissent le faire facilement. Comme toujours, [veuillez signaler](/docs/moderation/reporting/) utilisateurs individuels malveillants et manipulateurs et instances à l’équipe de modération.

À mesure que vous apprenez et que vous grandissez, vous voudrez peut-être aussi aider les autres. C’est formidable ! Rappelez-vous de le faire seulement quand vous avez l’espace émotionnel pour aider avec grâce. Différentes personnes sont à différentes étapes dans différents voyages, ce qui signifie que la personne avec qui vous êtes frustré de ne pas comprendre une facette de l’accessibilité pourrait être très habile avec une facette que vous connaissez très peu.

Si vous vous trouvez dans des situations où vos besoins et ceux des autres entrent en conflit, veuillez vous approcher les uns des autres avec compassion et respect. N’oubliez pas non plus que vous pouvez toujours éviter les conversations irrespectueuses pour n’importe quelle raison. Si l’autre personne ne respecte pas vos limites et/ou l’espace que vous créez pour vous-même, vous pouvez également demander l’intervention du modérateur en nous envoyant un [rapport](/docs/moderation/reporting/).
