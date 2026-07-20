---
title: Politique de confidentialité — Examen Civique
---

# Politique de confidentialité

**Dernière mise à jour : 20 juillet 2026**

## 1. Qui sommes-nous

L'application **Examen Civique** (`fr.civicexam.app`) est éditée par **Victor Pérez Ngounou**, à titre individuel, responsable du traitement des données au sens du Règlement Général sur la Protection des Données (RGPD).

Contact pour toute question relative à vos données personnelles : **vngounou26@gmail.com**

> Examen Civique est une application non officielle et indépendante, sans lien avec l'État français ou toute administration. Elle ne garantit pas la réussite à l'examen civique officiel.

## 2. Données que nous collectons

L'utilisation de l'application nécessite la création d'un compte. Nous collectons :

- **Données de compte** : adresse email, nom affiché, et mot de passe — jamais stocké en clair, uniquement sous forme de hachage sécurisé (PBKDF2-SHA256, 210 000 itérations). Si vous choisissez de vous connecter avec Google, nous conservons à la place l'identifiant Google associé à votre compte, sans stocker de mot de passe.
- **Préférences d'affichage** : thème, taille de police, préférences sonores et haptiques.
- **Données d'utilisation et de progression** : vos sessions d'examen, vos réponses, vos scores par thème, vos erreurs (pour la fonction de révision), vos questions favorites, et votre série de jours d'activité consécutifs.
- **Données techniques d'authentification** : un jeton de connexion (JWT) de courte durée et un jeton de rafraîchissement, stocké sous forme hachée, qui permettent de vous maintenir connecté en sécurité.

Nous ne collectons **aucune donnée de localisation, de contacts ou de caméra** : l'application ne demande que les permissions Android strictement nécessaires à son fonctionnement (accès à l'état du réseau, vibration).

Nous n'intégrons **aucun outil tiers d'analyse d'audience, de publicité ou de suivi** (pas de Google Analytics, Firebase, AdMob ou équivalent).

## 3. Pourquoi nous utilisons ces données

- Créer et gérer votre compte, et vous authentifier de façon sécurisée.
- Vous permettre de suivre votre progression et personnaliser votre expérience (thèmes maîtrisés, erreurs à revoir, favoris).
- Assurer la sécurité et le bon fonctionnement du service (détection d'abus, rotation des jetons de connexion).

La base légale de ces traitements est l'**exécution du contrat** qui vous lie à nous lorsque vous utilisez l'application, ainsi que notre **intérêt légitime** à assurer la sécurité du service.

## 4. Avec qui vos données sont-elles partagées

Vos données ne sont **ni vendues, ni louées, ni partagées à des fins commerciales ou publicitaires**.

Elles peuvent être traitées par :

- **Microsoft Azure**, notre hébergeur (base de données, exécution de l'application, gestion des secrets via Azure Key Vault), en tant que sous-traitant.
- **Google**, uniquement si vous choisissez de vous connecter via « Se connecter avec Google » : Google traite alors votre demande d'authentification conformément à sa propre politique de confidentialité.

## 5. Durée de conservation

Vos données sont conservées tant que votre compte reste actif. Vous pouvez demander la suppression de votre compte et de l'ensemble des données associées à tout moment (voir « Vos droits » ci-dessous).

## 6. Sécurité

- Les mots de passe sont hachés (PBKDF2-SHA256, 210 000 itérations) : nous ne pouvons pas consulter votre mot de passe en clair.
- Les jetons de rafraîchissement sont stockés sous forme hachée, jamais en clair.
- Les jetons de connexion (JWT) ont une durée de vie courte.
- Les secrets d'infrastructure (clé de signature, chaîne de connexion à la base de données) sont stockés dans Azure Key Vault, jamais dans le code source.

## 7. Vos droits (RGPD)

Conformément au RGPD, vous disposez des droits suivants sur vos données personnelles : accès, rectification, effacement, limitation du traitement, portabilité et opposition.

Pour exercer l'un de ces droits — notamment la **suppression de votre compte et de vos données** — écrivez-nous à **vngounou26@gmail.com**. Nous nous engageons à répondre dans un délai maximal d'un mois.

Vous disposez également du droit d'introduire une réclamation auprès de la CNIL (Commission Nationale de l'Informatique et des Libertés) : [www.cnil.fr](https://www.cnil.fr).

## 8. Public visé

Examen Civique s'adresse à des personnes majeures préparant l'examen civique dans le cadre d'une démarche administrative (titre de séjour, carte de résident, naturalisation). L'application n'est pas destinée aux mineurs et ne collecte pas sciemment de données concernant des enfants.

## 9. Modifications de cette politique

Cette politique peut être mise à jour ponctuellement. La date de dernière mise à jour figure en haut de ce document. Toute modification substantielle vous sera signalée dans l'application.

## 10. Contact

Pour toute question relative à cette politique : **vngounou26@gmail.com**
