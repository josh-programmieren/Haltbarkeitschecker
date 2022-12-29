# Haltbarkeitschecker
Eine App zum Verwalten von Artikeln und deren Mindesthaltbarkeitsdaten.
## Funktionen
- Hinzufügen, abhaken und entfernen von Artikeln
- Verwalten von Artikel-Details
- Beim Abhaken von Artikeln kann das Mindesthaltbarkeitsdatum eingegeben werden
- Basierend auf dem Mindesthaltbarkeitsdatum werden Artikel vorgeschlagen
- Persistente Speicherung in der Cloud (Google Firebase)
- Login-System
## Technelogien
- Apache Cordova
- HTML, CSS, JavaScript
- Google Firebase
## Installation und Ausführung
1. Lade das Repository herunter und entpacke es.
2. Öffne eine Kommandozeile und wechsle in das Projektverzeichnis.
3. Führe den folgenden Befehl aus, um die benötigten Abhängigkeiten zu installieren:
```	npm install ```
4. Füge die Plattform deiner Wahl hinzu. Momentan werden leider nur Browser und Electron unterstützt. Dafür gibst du entweder ```cordova platform add browser```oder ```cordova platform add electron``` ein. Alternativ kannst du auch ```npm run serve``` eingeben.
5. Baue das Projekt für deine Plattform oder führe es direkt aus:
- Bauen:
```npm run browser:build``
```npm run electron:build```
- Direkt starten:
```npm run browser:start```
```npm run electron:start```