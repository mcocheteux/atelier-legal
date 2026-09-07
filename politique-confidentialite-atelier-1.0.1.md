# Politique de confidentialité — Atelier (version 1.0.1)

**Dernière mise à jour : 7 septembre 2026**

Cette politique décrit le traitement des données dans l’application iOS **Atelier** (identifiant `atelier.fitness.app`), éditée par Mathieu Cocheteux. Elle correspond à la version **1.0.1** : carnet d’entraînement local, Apple Health en option, synchronisation iCloud privée en option, abonnement **Atelier Premium** optionnel via l’App Store. **Pas de compte Atelier, pas de Sign in with Apple, pas de Friends.**

## 1. Responsable de traitement

**Mathieu Cocheteux**  
Personne physique établie en France  
E-mail : mathieu@cocheteux.eu

Apple est responsable de ses propres services (iCloud, Apple Health, App Store / StoreKit). Atelier est responsable des traitements qu’il détermine dans l’app.

## 2. Données traitées

Aucune publicité, aucun SDK d’analytics, aucun identifiant publicitaire.

### 2.1 Sur l’appareil

- Prénom (facultatif)
- Année de naissance et genre (facultatifs) — vous pouvez les laisser vides
- Poids corporel saisi manuellement (facultatif)
- Historique d’entraînements, séries, modèles, notes, calories estimées
- Compteur local de séances terminées dans l’app (pour le seuil d’essai gratuit de démarrage)
- Statut d’abonnement StoreKit / entitlement Premium (géré par Apple sur l’appareil)
- Préférences (rappels, Health, iCloud)
- Instantanés widgets / Live Activities (nom de séance, exercice, repos) — pas de poids corporel sur l’écran verrouillé

Sans iCloud ni Health, ces données ne quittent pas l’appareil (hors traitements Apple liés à l’App Store si vous achetez Premium).

### 2.2 Apple Health (interrupteur, facultatif)

- **Lecture :** masse corporelle, pour affiner l’estimation des calories
- **Écriture :** séances de musculation ou pilates terminées, et l’énergie active estimée

Atelier ne lit pas votre historique Health d’entraînements. Refuser Health n’empêche pas d’utiliser l’app.

### 2.3 iCloud privé (interrupteur, désactivé par défaut)

Conteneur `iCloud.atelier.fitness.app`, dans **votre** iCloud. Copie privée de vos séances sur vos appareils liés au même compte Apple. Nous n’y écrivons pas les échantillons Apple Health ni le poids corporel. Ce n’est pas un compte Atelier.

### 2.4 Achats App Store (Premium, facultatif)

Si vous souscrivez à Atelier Premium, **Apple** traite le paiement et l’abonnement. Atelier ne stocke pas votre carte bancaire. L’app lit uniquement l’état d’abonnement (entitlement) fourni par StoreKit pour savoir si le démarrage illimité de séances est débloqué.

### 2.5 Ce que cette version ne traite pas

Pas de Sign in with Apple, pas de cercle d’amis, pas d’identifiant de compte Atelier, pas de serveur autre qu’iCloud Apple / App Store, pas de tracking.

## 3. Finalités et bases légales

| Traitement | Finalité | Base (RGPD) |
|---|---|---|
| Journal local | Fournir le carnet | Contrat / mesures précontractuelles, art. 6(1)(b) |
| Prénom | Accueil | Contrat, art. 6(1)(b) |
| Poids, année de naissance, genre | Profil ; le poids peut servir à l’estimation calorique | Consentement, y compris art. 9(2)(a) s’il s’agit de données de santé. Champs distincts des CGU. |
| Apple Health | Calories estimées ; archivage dans Health | Consentement (invite HealthKit + interrupteur), art. 6(1)(a) et 9(2)(a) le cas échéant |
| Sync iCloud privée | Retrouver vos séances sur vos appareils | Consentement (interrupteur), art. 6(1)(a) |
| Compteur de fins de séance / entitlement | Appliquer l’essai gratuit puis Premium | Contrat, art. 6(1)(b) |
| Abonnement Premium | Débloquer le démarrage illimité de séances | Contrat, art. 6(1)(b) |
| Notifications locales | Rappel / reprise de séance | Consentement (invite iOS), art. 6(1)(a) |
| Widgets / Live Activities | Reprendre une séance | Contrat, art. 6(1)(b) |

Pas de décision automatisée. Les calories sont une **estimation** (formule MET), pas une mesure médicale.

Les sets et répétitions ne sont pas, en eux-mêmes, des données de santé. Le **poids corporel** peut l’être. Il n’est pas partagé, pas vendu, pas utilisé pour de la publicité.

Le RGPD s’applique pleinement dès que Health ou iCloud est activé, ou dès qu’un abonnement Apple implique un traitement identifiable côté éditeur. Un journal 100 % local, usage personnel, sans connexion externe, sort du champ RGPD selon la CNIL.

## 4. Destinataires

Vous, sur l’appareil. Apple, pour HealthKit, iCloud et l’App Store / StoreKit si vous les utilisez. Personne d’autre.

## 5. Transferts hors UE

iCloud, HealthKit et l’App Store sont des services Apple. Des données peuvent être traitées hors UE selon les conditions Apple (clauses types / Data Transfer Program). Le journal local sans ces options ne sort pas de l’appareil.

## 6. Durées

- Données locales : jusqu’à suppression dans l’app, ou désinstallation.
- Copie iCloud : tant que l’option est active ; suppression via l’app et/ou iCloud.
- Health : selon vos réglages dans l’app Santé.
- Abonnement : selon votre abonnement Apple ; Atelier ne conserve pas de moyen de paiement.

## 7. Vos droits

Accès, rectification, effacement, limitation, opposition, portabilité, retrait du consentement, réclamation auprès de la **CNIL** (cnil.fr).

Dans l’app : export JSON depuis Réglages ; suppression des données d’entraînement ; interrupteurs Health, iCloud, notifications. Health se révoque aussi dans l’app Santé. Abonnements : Réglages → Identifiant Apple → Abonnements. Délai de réponse : 1 mois. mathieu@cocheteux.eu si vous n’avez plus l’app.

Cette version **n’offre pas** de compte Atelier à supprimer. Une fonction Friends / Sign in with Apple, si elle est ajoutée plus tard, aura sa propre suppression de compte (y compris révocation du jeton Apple) et une politique mise à jour **avant** activation.

## 8. Mineurs

Atelier n’est pas une app pour enfants. Ne saisissez pas les données d’un enfant de moins de 15 ans.

## 9. Santé

Atelier est un **carnet d’entraînement**. Ce n’est pas un dispositif médical, pas un avis médical, pas un outil de diagnostic. Consultez un médecin en cas de doute, douleur ou pathologie. Les calories sont estimées.

Les données HealthKit et le poids ne sont jamais utilisés pour de la publicité ou de la revente.

## 10. Cookies et traceurs

Pas de cookies web, pas de SDK publicitaire, pas de mesure d’audience tierce. Les stockages locaux sont nécessaires au service. Pas de bannière publicitaire.

## 11. Modifications

La date en tête fait foi. Un changement substantiel (compte, Friends, publicité, nouveau destinataire) sera annoncé dans l’app et exigera un nouveau consentement lorsque la loi l’impose.

## 12. Réclamation

CNIL — 3 Place de Fontenoy, TSA 80715, 75334 Paris Cedex 07 — https://www.cnil.fr
