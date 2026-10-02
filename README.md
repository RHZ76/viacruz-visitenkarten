# viacruz Visitenkarten

Version 0.2.0

Kostenlose PWA zum Erfassen, Verwalten und Durchsuchen von Visitenkarten.

## v0.2.0
- Eigene Schaltflächen „Vorderseite fotografieren“ und „Rückseite fotografieren“
- QR-Code-Erkennung aus fotografierten Karten
- vCard-QR-Codes können Name, Firma, Tätigkeit, Telefon, E-Mail, Website und Adresse automatisch füllen
- Web-, Mail- und Telefon-QR-Codes werden ebenfalls erkannt
- OCR-Texterkennung Deutsch/Englisch direkt im Browser
- Erkannter Text wird in Kontaktfelder übernommen und vollständig durchsuchbar gespeichert
- QR-Inhalt wird separat gespeichert und in die Volltextsuche einbezogen

## Datenschutz
Die Visitenkarten und Bilder bleiben in IndexedDB auf dem Gerät. Für die OCR werden beim ersten Einsatz die Browser-Bibliothek und Sprachdaten aus dem Internet geladen; die eigentliche Erkennung läuft im Browser.
