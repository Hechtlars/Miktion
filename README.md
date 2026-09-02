# Blasentagebuch

Mobile-first Web-App/PWA für ein digitales Miktions- und Blasentagebuch.

## Funktionen
- Schnell-Erfassung: Getrunken, Wasser gelassen, Urinverlust
- automatische Uhrzeit, manuell korrigierbar
- Trink- und Harnmengen
- Harndrang
- Inkontinenzsituation und Vorlagenwechsel
- Schlafzeiten für spätere Nacht-Auswertung
- 3 Tage als Standard, optional 4/7 Tage
- lokale Speicherung im Browser
- JSON-Sicherung/Import
- druckbare ärztliche Zusammenfassung
- installierbare PWA / Offline-Grundfunktion

## GitHub Pages
1. Dateien in ein neues Repository hochladen.
2. `Settings` → `Pages`.
3. Unter `Build and deployment` als Source `Deploy from a branch` wählen.
4. Branch `main`, Ordner `/(root)` auswählen und speichern.
5. Die App ist anschließend unter der von GitHub angezeigten Pages-Adresse erreichbar.

Alle Pfade sind relativ, damit die App auch als GitHub-Project-Page unter `/REPOSITORY/` funktioniert.

## Medizinischer Rahmen
Die App ist als Dokumentationshilfe gedacht und stellt keine Diagnose. Die erste Version orientiert sich funktional an den typischen Inhalten eines Blasen-/Miktionstagebuchs (Trinkmenge, Miktionszeit/-volumen, Harndrang, Inkontinenzereignisse, Vorlagen) und verwendet drei Tage als Standard-Erhebungsdauer. Vor klinischer Veröffentlichung sollten Definitionen, Berechnungen, Datenschutztext und medizinische Kennzahlen final gegen die jeweils aktuelle deutsche Leitlinie und EAU-Leitlinie validiert werden.

## Datenschutz
Die Einträge werden in dieser Version mit `localStorage` ausschließlich lokal im jeweiligen Browser gespeichert. Es gibt kein Backend und keinen Cloud-Upload durch die App.


## Version 1.1
- Startfehler der Eingabekacheln behoben.
- Erste Kachel heißt jetzt Trinkmenge.
- PWA-Cache aktualisiert.

## Version 1.2
- Trinkgefäße als alltagstaugliche Schnellwahl: Tasse, Glas, großes Glas mit ca.-ml-Angaben; ml-Auswahl bleibt erhalten.
- Saftschorle ergänzt.
- Hintergrund wird bei geöffneten Eingabefenstern fixiert; nur das Eingabefenster scrollt.
- Harndrang als horizontale visuelle 5-Stufen-Skala.
- Nachtruhe kompakt in der Tagesübersicht; kein separater Nacht-Reiter.
- Pädiatrische Frage „Bett war nachts nass“ aus der Erwachsenen-Version entfernt.
