---
layout: default
title: Datenschutzrichtlinie
---

<div style="text-align: right; margin-bottom: 16px;">
  <a href="privacy">English</a> · <strong>Deutsch</strong> · <a href="privacy-fr">Français</a> · <a href="privacy-es">Español</a>
</div>

# Datenschutzrichtlinie

**Zuletzt aktualisiert: 28. Februar 2026**

SmartRow Companion („die App") wird von Greg Burlingame entwickelt. Diese Datenschutzrichtlinie beschreibt, wie die App mit Ihren Daten umgeht.

## Datenerhebung

SmartRow Companion erhebt, überträgt oder verkauft **keine** personenbezogenen Daten an Dritte. Die App enthält keinerlei Analysewerkzeuge, Werbung oder Tracking.

## Auf Ihrem Gerät gespeicherte Daten

Die App speichert folgende Daten lokal auf Ihrem Gerät:

* **Trainingseinheiten** — Rudermetriken jeder Einheit (Distanz, Pace, Leistung, Schlagrate, Herzfrequenz, Kraftkurven, Kalorien und Zeitstempel) werden mit Apples SwiftData-Framework auf Ihrem Gerät gespeichert.
* **App-Einstellungen** — Ihre Einstellungen (Exportoptionen, Anzeigeoptionen, Feedback-Schalter) werden lokal mit UserDefaults gespeichert.
* **Bluetooth-Geräteinformationen** — Die Kennung Ihres gekoppelten SmartRow-Geräts und Herzfrequenzmessers wird lokal gespeichert, damit die App sich automatisch wieder verbinden kann.
* **Strava-Authentifizierungstoken** — Wenn Sie Ihr Strava-Konto verbinden, wird ein OAuth-Token sicher im iOS-Schlüsselbund auf Ihrem Gerät gespeichert. Dieses Token wird ausschließlich zum Hochladen von Trainingsdaten auf Ihr Strava-Konto verwendet.

## iCloud-Synchronisation

Wenn Sie auf Ihrem Gerät bei iCloud angemeldet sind, werden Trainingseinheiten automatisch über Apples CloudKit zwischen Ihren Geräten synchronisiert. Diese Daten werden in Ihrem privaten iCloud-Konto gespeichert und sind weder für den Entwickler noch für Dritte zugänglich. Sie können diese Daten über Ihre iCloud-Einstellungen verwalten oder löschen. Wenn Sie nicht bei iCloud angemeldet sind, bleiben alle Daten lokal auf Ihrem Gerät.

## Apple Health

Wenn Sie den Apple-Health-Export aktivieren, schreibt die App Trainingsdaten (Dauer, Distanz, Kalorien und Herzfrequenzmessungen) in Apple Health über HealthKit. Wenn Sie Herzfrequenzzonen mit der Einstellung „Vom Alter" aktivieren, liest die App Ihr Geburtsdatum aus Apple Health, um Ihre altersbasierte maximale Herzfrequenz zu berechnen. Ihr Geburtsdatum wird ausschließlich für diese Berechnung verwendet und wird niemals gespeichert, übertragen oder weitergegeben. Die Freigabe von Gesundheitsdaten wird vollständig von Ihnen über die Berechtigungen der Health-App gesteuert.

## Strava

Wenn Sie den Strava-Export aktivieren, lädt die App Trainingsdaten (Leistung, Distanz, Herzfrequenz, Pace und Zeitstempel) als FIT-Datei auf Ihr Strava-Konto hoch. Dieser Upload nutzt die Strava-API und erfordert Ihre Autorisierung über Stravas OAuth-Anmeldung. Sie können diesen Zugriff jederzeit über Ihre Strava-Kontoeinstellungen widerrufen. Die App liest keine Daten von Ihrem Strava-Konto.

## Herzfrequenzdaten

Wenn Sie einen Bluetooth-Herzfrequenzmesser koppeln, werden Herzfrequenzdaten während Ihrer Trainingseinheit über Bluetooth LE empfangen. Diese Daten werden in Echtzeit angezeigt, mit Ihrer Trainingseinheit gespeichert und in Exporte zu Apple Health und Strava einbezogen, falls diese Funktionen aktiviert sind. Herzfrequenzdaten werden niemals anderweitig übertragen.

## Bluetooth

Die App kommuniziert mit Ihrem SmartRow-Sensor und optionalem Herzfrequenzmesser über Bluetooth Low Energy (BLE). Die gesamte Bluetooth-Kommunikation erfolgt direkt zwischen Ihrem Gerät und den Sensoren. Es werden keine Bluetooth-Daten an Server oder Dritte übertragen.

## Datenspeicherung

Alle Trainingsdaten werden auf Ihrem Gerät gespeichert (und in Ihrem privaten iCloud-Konto, falls iCloud aktiviert ist). Sie können einzelne Einheiten innerhalb der App löschen. Die Deinstallation der App entfernt alle lokal gespeicherten Daten.

## Datenschutz für Kinder

Die App erhebt wissentlich keine Daten von Kindern unter 13 Jahren.

## Änderungen dieser Richtlinie

Wenn diese Datenschutzrichtlinie aktualisiert wird, wird die überarbeitete Version mit einem aktualisierten Datum auf dieser Seite veröffentlicht.

## Kontakt

Wenn Sie Fragen zu dieser Datenschutzrichtlinie haben, erstellen Sie bitte ein [Issue auf GitHub](https://github.com/gburlingame/smartrow-app/issues).
