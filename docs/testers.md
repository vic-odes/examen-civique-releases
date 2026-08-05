---
title: Note de version — Testeurs — Examen Civique
---

# Note de version pour les testeurs — Examen Civique

**Version couverte : v1.2.0 — Mise à jour au 5 août 2026**

Ce document liste **toutes les fonctionnalités** de l'application, à l'usage des
testeurs. Il sert de base de test : parcourez chaque section et vérifiez que le
comportement décrit correspond à ce que vous observez sur votre appareil.

> Pour installer l'APK : voir la [page des releases](../../releases) et le
> [README](../../) du dépôt.

## 🆕 À tester en priorité (nouveautés récentes)

Ces fonctionnalités sont les plus récentes et méritent une attention particulière :

- **Notifications push** : activables dans Réglages → Notifications. Vérifier la
  demande de permission Android (Android 13+), la réception d'un rappel de série
  quotidienne, et — si une date d'examen est renseignée — les rappels à J-7, J-3,
  J-1 et J0. Un bouton « Tester les notifications » est disponible en interne
  (build non-production uniquement).
- **Date d'examen déclarée** : Réglages → activer « J'ai une date d'examen » →
  choisir une date. Vérifier la persistance après redémarrage de l'app.
- **Vérification d'adresse email** : à l'inscription, un code à 6 chiffres est
  envoyé par email (valable 15 minutes) ; vérifier la page de saisie du code et
  le renvoi du code.
- **Widget « astuce du jour »** (écran d'accueil Android) : ajouter le widget,
  vérifier qu'il affiche une astuce liée à vos leçons et qu'il se rafraîchit
  périodiquement, y compris quand l'application est fermée.
- **Liens profonds (deep links)** : ouvrir un lien `civicexam://…` (ex. depuis un
  email ou une notification) et vérifier que l'app s'ouvre directement sur le bon
  écran.
- **Lecture audio des questions** : vérifier la lecture à voix haute automatique
  (question + correction) et à la demande (bouton haut-parleur), en mode
  entraînement et flashcards ; les clips audio sont téléchargés depuis un CDN,
  vérifier le comportement hors-ligne / réseau lent.

## Authentification et compte

- Inscription par email/mot de passe, avec vérification d'email.
- Connexion via « Se connecter avec Google » (Google Sign-In).
- Mot de passe oublié / réinitialisation.
- Suppression de compte et de toutes les données associées (voir
  [Suppression de compte](./delete-account.html)).

## Écran d'accueil (Dashboard)

- Vue d'ensemble de la progression : score global, thèmes maîtrisés, série de
  jours d'activité consécutifs (streak).
- Accès rapide aux modes d'entraînement et aux cours.

## Cours (contenu pédagogique)

- Navigation **Thèmes → Rubriques → Leçons**, couvrant les 5 thématiques
  officielles :
  1. Principes et valeurs de la République
  2. Système institutionnel et politique
  3. Droits et devoirs
  4. Histoire, géographie et culture
  5. Vivre dans la société française
- Lecture des leçons, avec lecture à voix haute optionnelle.

## Modes d'entraînement et d'examen

- **Examen blanc** : conditions réelles — 40 questions (28 connaissance + 12
  mises en situation), 45 minutes, seuil de réussite 80 % (32/40). Disponible
  pour les 3 mentions : carte de séjour pluriannuelle (CSP), carte de résident
  (CR), naturalisation.
- **Entraînement rapide** : série courte avec correction immédiate.
- **Révision par thème** : questions filtrées sur un thème choisi.
- **Refaire les erreurs uniquement** : rejoue les questions déjà manquées.
- Correction immédiate (pulsation verte / secousse rouge), retour sonore et
  haptique, explication affichée et lue à voix haute.
- Ajout d'une question aux favoris directement pendant l'entraînement.

## Flashcards

- Mode carte recto/verso (question / réponse), navigation au swipe, lecture
  à voix haute de chaque face.

## Favoris et erreurs à revoir

- Liste des questions marquées comme favorites.
- Liste des erreurs commises, avec possibilité de les rejouer en mode dédié.

## Résultats

- Détail d'une session terminée : score global, score par thème, temps passé,
  réponses correctes/incorrectes avec explication.

## Réglages

- Thème clair / sombre.
- Taille de police (accessibilité).
- Son et vibrations (haptique) activables/désactivables.
- Réduction des animations (accessibilité).
- Lecture à voix haute : activation générale et lecture automatique.
- Notifications et date d'examen (voir section « À tester en priorité »).
- Suppression de compte.

## Notifications et emails transactionnels

- Rappel de série quotidienne (streak) par notification push.
- Rappels avant la date d'examen déclarée (J-7/J-3/J-1/J0), par notification
  push avec repli par email si aucun jeton de notification n'est disponible.
- Email de vérification d'adresse à l'inscription.

## Confidentialité

Pour le détail des données collectées et des sous-traitants (Microsoft Azure,
Google / Firebase Cloud Messaging / Gmail, Cloudflare), voir la
[Politique de confidentialité](./privacy.html).

## Remonter un bug

Merci de préciser : version de l'app, modèle et version Android de l'appareil,
étapes de reproduction, et si possible une capture d'écran ou vidéo. Contact :
**vngounou26@gmail.com**.
