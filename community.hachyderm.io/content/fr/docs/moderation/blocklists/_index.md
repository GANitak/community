---
title: "Blocklists"
linkTitle: "Blocklists"
weight: 40
description: >
  Informations communautaires sur les Blocklists et comment les Blocklists sont construits.
---

{{% pageinfo %}}
<h5 class="text-center">This page was manually translated on 05/13/23. </br>Please utilize the English docs for the most up to date policies.</h5>
{{% /pageinfo %}}

## Les bases des Blocklists

### Objectif Général

Les blocklists sont un moyen qu’une instance de Mastodon à pour gérer le contenu indésirable au niveau de l’instance. Lorsqu’un domaine Mastodon est sur la Blocklist, cela signifie que les administrateurs du serveur ont une activité limitée ou complètement suspendue avec le serveur de ce domaine. Les actions spécifiques sont :

- Suspendre<br />C’est le plus connu, car il empêche tout
activité d’instance à instance.
- Limite<br />Précédemment appelé "silencieux". Cela signifie que les comptes sur le serveur d’accueil peuvent suivre les comptes sur le serveur limité, mais que le contenu général de ce serveur n’apparaît pas sur la timeline fédérée.
- Rejeter les Médias<br />Les médias du serveur modéré ne s’affichent pas sur le serveur principal, cela inclut non seulement les médias dans les postes eux-mêmes, mais
avatars et en-têtes aussi.

 [Mastodon a ces caractéristiques dans sa documentation](https://docs.joinmastodon.org/admin/moderation/#server-wide-moderation).

### Modération Actions vs Utilisateur Actions

Les utilisateurs peuvent également prendre des mesures individuelles pour éviter de voir du contenu indésirable en bloquant ou en limitant d’autres comptes au niveau de l’utilisateur.
Ceci est recommandé pour les cas où le contenu est peut-être considéré indésirable par un utilisateur individuel, mais que le contenu ne viole pas l’ethos du serveur d’accueil.

Mastodon a de la documentation supplémentaire sur les actions que les utilisateurs individuels peuvent prendre sur leur [page Traiter le Contenu Indésirable](https://docs.joinmastodon.org/user/moderating/).

## Comment la Blocklist d'Hachyderm est-elle Construite

Chez Hachyderm, nous faisons de notre mieux pour équilibrer les actions à prendre au niveau de l’instance et celles à traiter au niveau de l’utilisateur - quand il s’agit de nos propres utilisateurs et quand nous recevons des signalements d’utilisateurs sur d’autres instances ou les instances elles-mêmes. La grande majorité d'action de mod que nous avons prise sur les serveurs de notre Blocklist est soit de silence / limite ou de suspendre / bloquer. Les domaines inclus dans cette liste sont :

- Organisé à partir d’une variété de Blocklists publiés sur d’autres instances Mastodon
- Ajouté en fonction des signalements d'utilisateurs. Cela peut signifier :
  - Un domaine a été signalé, étudié et modéré individuellement, _ou_
  - Un volume élevé de signalements concernant plusieurs utilisateurs sur une instance a conduit
    à une instance d'être recherchée et de modérée
 
Bien que la suspension soit l’action de modération la plus connue et discutée, les domaines peuvent aussi être limités. Par exemple, nous pourrions limiter un serveur qui a plusieurs bots qui envahissent la timeline fédérée, mais pas suspendre afin que les utilisateurs puissent continuer à suivre les comptes individuels.

### Préoccupations qui entrent dans la construction de la Blocklist

Il ya quelques préoccupations de haut niveau qui entrent dans la détermination de l’ajout de serveurs à la Blocklist :

1. L’ethos d’un serveur spécifique viole-t-il l’ethos de ce serveur ? <br />Quelques exemples faciles à comprendre seraient si un serveur est anti-Noirs, anti-queer, ou endosse un discours et un contenu haineux, direct ou "dog-whistled".
1. Y a-t-il un problème de sécurité autour de ce serveur ? <br />À titre d’exemple général,
   si nous voyons du trafic malveillant provenant d’un ou de plusieurs serveurs spécifiques.
1. Quel risque le serveur représente-t-il pour nos utilisateurs? <br />Nous accordons la priorité à la sûreté et à l’expérience de nos utilisateurs qui font partie de groupes historiquement sous-représentés.
1. À quoi ressemblent nos signalements d’utilisateurs? Sont-ils au niveau de l’utilisateur sur un serveur donné ou sont-ils indicatifs de modèles malveillants à l’échelle du serveur?
1. Quel niveau de modération est nécessaire? Limiter/silence ou bloquer/suspendre?

Nous sommes d’avis qu’il est dans l’intérêt de nos utilisateurs de se fédérer avec autant de Fediverse que possible afin que nous puissions tous partager nos joies, nos peines, notre croissance, notre apprentissage, etc. les uns avec les autres.

Notre objectif avec la maintenance de la Blocklist est de s’assurer que tous nos utilisateurs sont en sécurité sur Hachyderm. Cela signifie que lorsque nous prenons des mesures de modération sur un serveur, nous prenons les meilleures mesures pour assurer cette sécurité. Nous accorderons la priorité à la sécurité de nos utilisateurs marginalisés plutôt qu’à l’expérience plus vaste d’une ouverture complète et non modéré (au niveau du serveur) du Fediverse.

Lorsque nous prenons des mesures de modération contre un serveur, nous considérons :

- Les éléments énumérés dans la liste numérotée ci-dessus
- Trouver un équilibre entre la participation ouverte et l’aménagement d’un espace sûre 

### Préoccupations autour de la transparence de la Blocklist

Certains serveurs ont des raisons attachées à leur action de modération et d’autres pas. En outre, nous pouvons ou non annoncer quand nous limitons/silence ou bloquons/suspendons des instances individuelles. Pourquoi ?

Lorsque nous choisissons le niveau de notification à envoyer, et la transparence à être, nous considérons, les actions de modération ci-après: 

1. L’impact du changement
1. Le niveau d’intérêt dans le changement
1. Le risque de faire connaître le changement ou d’être transparent à son sujet

Par exemple, si nous devions prendre des mesures de modération à l’égard de n’importe laquelle des grandes instances de Mastodon, nous errerions du côté de la transparence, car il s’agirait d’un événement important qui aurait une incidence sur les utilisateurs.

Chaque fois que nous prenons des mesures sur un serveur qui a une activité malveillante, et cela peut être sous forme d’attaques sur notre serveur ou sous forme d’attaques sociales comme le "stakling" et le harcèlement, nous errons du côté de la sécurité. Cela signifie le niveau d’information que nous fournissons et à quel point (notifications, etc.) nous le fournirons en fonction de ce qui est le plus sûre pour tous nos utilisateurs.

La grande, grande majorité des cas se situent entre ces deux extrêmes et donc les décisions qui en résultent ne tombent pas parfaitement dans les clous "entièrement transparents" ou "complètement silencieux".
Cela signifie :

- Les serveurs peuvent ne pas avoir de raisons liées à leurs décisions de modération, mais cela ne      signifie pas qu’ils constituent une préoccupation en matière de sécurité, ou sûreté.
  <br />Cela les exposerait immédiatement en tant que préoccupation de sécurité, en l’absence d’information.
- Les changements apportés à l’état de chaque serveur ne seront pas tous annoncés, mais certains le seront. <br />
  Nous utiliserons le processus décisionnel décrit ci-dessus au moment de l’annonce.
- Ne pas annoncer qu’un serveur a changé de statut ne signifie pas que le serveur est ou était une cause de préoccupation. Cela peut aussi signifier, et le sera souvent, que la taille du serveur n’a pas suffisamment d’impact sur nos utilisateurs pour faire une grande annonce.

## Demander des Changements de Modération pour un Serveur

### Que faire s’il y a un domaine sur la Blocklist par erreur

Nous sommes tous humains et sommes sujets aux erreurs. S’il y a un domaine qui est modéré sur notre blocklist qui semble être là par erreur, s’il vous plaît ouvrez un
[Issue GitHub dans notre repo Communautaire](https://github.com/hachyderm/community/issues)
Demandez que nous regardions le domaine. Veuillez inclure autant de contexte pertinent que possible pour nous aider à prendre notre décision. Veuillez noter que, selon les circonstances, et comme il est indiqué ci-dessus, nous ne serons peut-être pas en mesure d’être entièrement transparents dans notre décision - mais nous nous sommes du côté de la transparence, au maximum avec ces signalements, le plus possible. Pour obtenir de plus amples renseignements sur la façon de faire un signalement via notre repo communautaire, veuillez consulter notre [Documentation sur les Signalements].(/docs/moderation/reporting).

### Que faire si vous souhaitez que nous modérions un serveur 

S’il y a un serveur qui n’est pas actuellement modéré, c.-à-d. limité/silencieux ou interdit/suspendu, veuillez déposer un signalement via l’IU Hachyderm (Mastodon) ou [Issue GitHub dans notre repo Communautaire](https://github.com/hachyderm/community/issues)
pour que nous puissions examiner ce ou ces domaines. Comme auparavant, veuillez inclure le plus de contexte possible. S’il y a une préoccupation concernant le ou les domaines que vous aimeriez signaler et qui serait risquée à signaler dans notre outil de suivi des problèmes de GitHub, veuillez nous envoyer un courriel à [admin@hachyderm.io](mailto:admin@hachyderm.io).
Pour en savoir plus sur le dépôt de signalements et sur la façon de choisir entre l’IU de Mastodon et l’outil de Suivi des Problèmes GitHub (Issue Tracker), veuillez consulter notre [Documentation sur les Signalements](/fr/docs/moderation/reporting).

### Que ne pas faire dans l’un ou l’autre de ces cas

Il y a beaucoup plus d’Hachydermiens que de modérateurs. Nous ne suivons pas les tags, postes, etc. pour apporter des modifications à notre Blocklist - nous utilisons uniquement les sources décrites ci-dessus.
