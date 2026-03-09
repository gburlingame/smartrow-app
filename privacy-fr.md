---
layout: default
title: Politique de confidentialité
---

<div style="text-align: right; margin-bottom: 16px;">
  <a href="privacy">English</a> · <a href="privacy-de">Deutsch</a> · <strong>Français</strong> · <a href="privacy-es">Español</a>
</div>

# Politique de confidentialité

**Dernière mise à jour : 28 février 2026**

SmartRow Companion (« l'application ») est développée par Greg Burlingame. Cette politique de confidentialité décrit comment l'application gère vos données.

## Collecte de données

SmartRow Companion ne collecte, ne transmet et ne vend **aucune** donnée personnelle à des tiers. L'application ne contient aucun outil d'analyse, de publicité ou de suivi.

## Données stockées sur votre appareil

L'application stocke les données suivantes localement sur votre appareil :

* **Séances d'entraînement** — Les métriques d'aviron de chaque séance (distance, allure, puissance, cadence, fréquence cardiaque, courbes de force, calories et horodatages) sont enregistrées sur votre appareil à l'aide du framework SwiftData d'Apple.
* **Paramètres de l'application** — Vos préférences (options d'export, paramètres d'affichage, options de retour) sont stockées localement via UserDefaults.
* **Informations sur les appareils Bluetooth** — L'identifiant de votre appareil SmartRow couplé et de votre cardiofréquencemètre est stocké localement pour permettre la reconnexion automatique.
* **Jeton d'authentification Strava** — Si vous connectez votre compte Strava, un jeton OAuth est stocké de manière sécurisée dans le trousseau iOS de votre appareil. Ce jeton est utilisé uniquement pour envoyer les données d'entraînement vers votre compte Strava.

## Synchronisation iCloud

Si vous êtes connecté à iCloud sur votre appareil, les séances d'entraînement sont automatiquement synchronisées entre vos appareils via CloudKit d'Apple. Ces données sont stockées dans votre compte iCloud privé et ne sont accessibles ni au développeur ni à des tiers. Vous pouvez gérer ou supprimer ces données via vos réglages iCloud. Si vous n'êtes pas connecté à iCloud, toutes les données restent locales sur votre appareil.

## Apple Santé

Si vous activez l'export vers Apple Santé, l'application écrit les données d'entraînement (durée, distance, calories et échantillons de fréquence cardiaque) dans Apple Santé via HealthKit. Si vous activez les zones de fréquence cardiaque avec le réglage « Depuis l'âge », l'application lit votre date de naissance depuis Apple Santé pour calculer votre fréquence cardiaque maximale basée sur l'âge. Votre date de naissance est utilisée uniquement pour ce calcul et n'est jamais stockée, transmise ou partagée. Le partage des données de santé est entièrement contrôlé par vous via les autorisations de l'application Santé.

## Strava

Si vous activez l'export Strava, l'application envoie les données d'entraînement (puissance, distance, fréquence cardiaque, allure et horodatages) vers votre compte Strava sous forme de fichier FIT. Cet envoi utilise l'API Strava et nécessite votre autorisation via le processus OAuth de Strava. Vous pouvez révoquer cet accès à tout moment via les paramètres de votre compte Strava. L'application ne lit aucune donnée de votre compte Strava.

## Données de fréquence cardiaque

Si vous couplez un cardiofréquencemètre Bluetooth, les données de fréquence cardiaque sont reçues via Bluetooth LE pendant votre séance d'entraînement. Ces données sont affichées en temps réel, enregistrées avec votre séance et incluses dans les exports vers Apple Santé et Strava si ces fonctionnalités sont activées. Les données de fréquence cardiaque ne sont jamais transmises ailleurs.

## Bluetooth

L'application communique avec votre capteur SmartRow et votre cardiofréquencemètre optionnel via Bluetooth Low Energy (BLE). Toute la communication Bluetooth s'effectue directement entre votre appareil et les capteurs. Aucune donnée Bluetooth n'est transmise à un serveur ou à des tiers.

## Conservation des données

Toutes les données d'entraînement sont stockées sur votre appareil (et dans votre compte iCloud privé si iCloud est activé). Vous pouvez supprimer des séances individuelles depuis l'application. La désinstallation de l'application supprime toutes les données stockées localement.

## Confidentialité des enfants

L'application ne collecte sciemment aucune donnée d'enfants de moins de 13 ans.

## Modifications de cette politique

Si cette politique de confidentialité est mise à jour, la version révisée sera publiée sur cette page avec une date actualisée.

## Contact

Si vous avez des questions concernant cette politique de confidentialité, veuillez [ouvrir une issue](https://github.com/gburlingame/smartrow-app/issues) sur GitHub.
