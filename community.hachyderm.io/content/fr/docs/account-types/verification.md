---
title: "Vérification de Compte Spécialisé avec Hachyderm"
linkTitle: "Verifé avec Hachyderm"
weight: 20
description: >
  Comment devenir un compte vérifié, spécialisé, avec Hachyderm.
---
{{% pageinfo %}}
<h5 class="text-center">This page was manually translated on 05/18/23. Please utilize the English docs for the most up to date policies.</h5>
{{% /pageinfo %}}

## Qui doit vérifier?

À l’heure actuelle, seul un sous-ensemble de nos comptes spécialisés sont _requis_ de vérifié. Cela dit, nous recommandons que tous les comptes spécialisés (comptes d’influenceurs au cas par cas) passent par le processus de vérification afin que les utilisateurs d'Hachyderm sachent que votre compte est officiellement reconnu et que vous avez accepté les [Attentes Relatives aux Comptes Spécialisés](../covenant/).


### Vérification requise et facultative

Bien que nous recommandions que tous les comptes qui ne sont pas des comptes d’utilisateur demande à être vérifiés avec nous, seuls les cas suivants doivent être vérifiés :

* [Comptes Corporate](../corporate-accounts/)
* [Robot et Poste-Automatisation](../bot-accounts/)
* [Comptes et Contenu Sélectionnés](../curated-accounts/)

Comptes qui voudront probablement considérer à être vérifiés :

* [Événements Communautaires](../open-source-accounts/)
* [Projets Open Source](../open-source-accounts/)
* Tout compte qui peut sembler semblable à un compte corporatif (mais qui ne l’est pas). Cela peut comprendre :
  * Quelques-unes des organisations sans but lucratif que nous avons accueillis sur notre instance
* Certains de nos [Influencer Accounts](../influencer-accounts/) (mais pas tous)
    * Veuillez noter que la vérification n’est pas ouverte aux utilisateurs généraux pour le moment.
    * En général, cela ne se produit que si votre marque personnelle ou votre style de publication peuvent être confondus avec l’un des types de comptes spécialisés reconnus. Si vous utilisez Hachyderm en tant qu’utilisateur général et que vous avez un grand nombre de followers, vous ne voudriez probablement pas être vérifié pour le moment.

## Quand verifé?

Ce processus a été lancé en février 2023. Nous demandons aux comptes existants qui doivent être vérifiés de le faire d’ici fin mars 2023.

## À quoi ressemble un compte vérifié?
Tous les comptes spécialisés qui ont été vérifiés par l’équipe de modération de Hachyderm auront un lien vérifié pointant vers [community.hachyderm.io/approved](https://community.hachyderm.io/approved) dans leurs liens de profil. Ce lien devrait être intitulé « Approuvé » sur la biographie du compte :

<img src="../approved.png" alt="Capture d’écran de la section des liens approuvés d’un profil.
      Il y a deux liens vérifiés. L’un indique le site web de la compagnie. L’autre pointant vers https://community.hachyderm.io/approved"
    width="400px" />

## Le processus de demande

**Étapes pour obtenir l’approbation**

C’est seulement pour les comptes spécialisés.
Nous n’acceptons pas les demandes d’utilisateurs individuels pour le moment.

_Partie 1 : Obtenir une pré-approbation_

Pour commencer, nous allons créer un problème pour suivre le processus complet, de la création de votre compte à l’achèvement du processus d’approbation.

1. Lire les [Attentes Relatives aux Comptes Spécialisés](../covenant/)
1. Open a "Specialized Account Approval" issue from our ['Community Issue Tracker'](https://github.com/hachyderm/community/issues/new?assignees=&labels=Specialized+Accounts&template=9.Specialized-Account-Approvals.yml&title=Specialized+Accounts%3A+YOUR_ACCOUNT_NAME)
1. Inclure votre consentement aux attentes relatives aux comptes spécialisés dans le numéro GitHub 
1. Soyez patient (nous sommes un groupe de mods bénévoles et communiquerons avec vous dès que possible)
1. Nous prenons une décision
   - Si vous n’êtes pas approuvé, nous vous fournirons une raison et fermerons l'issue GitHub.
   - Si votre demande est approuvée, vous pouvez alors créer votre compte, puis passer à la partie 2 ci-dessous.
     - Remarque : vous devez quitter le GitHub issue _open_.

N’insérez pas par anticipation l’URL d’approbation dans les métadonnées de votre profil.
En raison de la façon dont la vérification fonctionne, Mastodon tentera seulement de vous vérifier _une fois_ par serveur lorsque vous ajoutez un URL. Cela signifie que l’instance d'Hachyderm ne vérifiera l’URL que lorsque vous l’ajoutez, avant son approbation, et ne vérifiera pas à nouveau.
Vous serez invité à ajouter l’URL à l’étape appropriée ci-dessous afin que l’URL soit active lorsque Hachyderm vérifie.

Si vous avez ajouté le champ de façon préventive au profil du compte, vous devrez enregistrer de nouveau l’adresse URL d’approbation avec votre compte indiqué à la partie 2 ci-dessous.

_Partie 2 : Fin de la Configuration du compte_

If you've pre-emptively added the field to the account profile, you'll need to re-save after the
approval URL is live with your account listed in Part 2 below.

_Part 2: Finishing account setup_

1. Assurez-vous que vous êtes déjà [vérifié avec votre domaine officiel](/docs/mastodon/user/verification/)
    - Ne supprimez pas le lien de référence. Les mods l’utiliseront pendant leur processus de validation.
1. Nous ajouterons votre étiquette de vérification sous l’en-tête approprié dans le fichier approuvé. (Soyez patient, nous sommes un groupe de bénévoles et nous mettrons à jour dès que possible.)
1. Nous mettrons à jour l'issue GitHub lorsque ce sera fait.
1. À l’aide des [étapes de vérification](/docs/mastodon/user/verification/), ajoutez ce qui suit aux métadonnées de votre profil
    - Étiquette 'label' : APPROUVÉ
    - Contenu : https://community.hachyderm.io/approved
1. Vérifiez que vous pouvez voir le champ approprié surligné en vert et le crochet vert.
1. Une fois que vous avez ajouté ce qui précède à vos métadonnées de profil et que la vérification est réussie, veuillez mettre à jour et fermer le problème GitHub.
   - Ne supprimez pas le lien approuvé une fois que vous avez terminé le processus. Ce champ permet à nos utilisateurs de savoir que vous êtes un compte approuvé et empêchera que votre compte soit signalé comme un compte non approuvé.
2. __Facultatif, mais recommandé :_ Assurez-vous de dire que vous êtes un compte approuvé et d’indiquer que cela signifie que vous avez accepté les [Attentes Relatives aux Comptes Spécialisés](../covenant/)!
