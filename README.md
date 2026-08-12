# EFW - Brutkasten Startseite

Dieses Projekt ist eine statische HTML/CSS-Webseite fuer den IT-Brutkasten.
Die Startseite dient als Einstiegspunkt zu Profilseiten des Ausbildungsleiters und der Talente.

## Ziel des Projekts

- Gemeinsame, uebersichtliche Landingpage fuer den Brutkasten
- Schneller Zugriff auf Profilseiten ueber Karten mit Bild und Name
- Einfache Wartung ohne Build-Tooling

## Aktueller Funktionsumfang

- Hero-Bereich mit kurzer Einleitung
- Eigener Abschnitt fuer den IT-Ausbildungsleiter
- Eigener Abschnitt fuer Talente mit Kartenlayout
- Profilseite fuer Pascal Wolf
- Fiktive Profilseite fuer Fleißiger Frederik

## Projektstruktur

- index.html: Startseite mit Trainer- und Talent-Bereich
- styles.css: Zentrales Styling fuer Startseite und Profilseiten
- ausbilder/pascal-wolf/visitenkarte.html: Profilseite des Ausbildungsleiters
- talente/fleißiger-frederik/visitenkarte.html: Fiktive Talent-Visitenkarte
- talente/fleißiger-frederik/styles.css: Lokales Styling fuer diese Talent-Seite
- talente/vorlage/: Vorlage fuer weitere Talent-Seiten
- images/: Zentrale Bildablage (z. B. pascal-wolf.png)
- changelog.md: Aenderungsdokumentation nach Datum

## Lokal starten

Da es ein statisches Projekt ist, gibt es zwei einfache Wege:

1. index.html direkt im Browser oeffnen.
2. Optional einen lokalen Server starten (empfohlen bei mehreren Unterseiten):
   - Mit VS Code Live Server
   - Oder mit einem beliebigen statischen Server

## Inhalte pflegen

### Ausbildungsleiter anpassen

- Seite bearbeiten unter ausbilder/pascal-wolf/visitenkarte.html
- Trainer-Karte auf der Startseite bearbeiten unter index.html
- Bei Bildaenderung neue Datei in images ablegen und Pfad in Startseite sowie Profilseite anpassen

### Neues Talent anlegen

1. Ordner unter talente erstellen, zum Beispiel talente/max-mustermann
2. Vorlage aus talente/vorlage uebernehmen
3. Inhalte in visitenkarte.html anpassen
4. Karte auf der Startseite in index.html ergaenzen oder Linkziel austauschen

Hinweis:
Die aktuellen Linkziele fuer Talent 1 bis Talent 6 auf der Startseite zeigen auf Platzhalterdateien (azubi1.html bis azubi6.html). Diese sollten beim Anlegen realer Seiten auf die finalen Talent-Pfade umgestellt werden.

## Technischer Rahmen

- Reines HTML und CSS
- Keine Abhaengigkeiten, kein Package Manager, kein Build-Prozess
- Responsives Layout ueber Media Queries

## Changelog

Aktuelle Aenderungen stehen in changelog.md.
