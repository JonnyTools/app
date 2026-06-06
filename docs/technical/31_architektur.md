# Systemarchitektur

## Komponenten

```text
Mobile App
Backend/API
PostgreSQL-Datenbank
PDF Processing Service
Email Service
File Storage
Scheduler
```

## Mobile App

Zuständig für:

- Login
- Aufgabenansicht
- Ausführung erfassen
- WG-Sitzung UI
- Signaturen
- Berichtprüfung
- Analyseansicht

## Backend

Zuständig für:

- Berechtigungen
- Datenvalidierung
- Vorschläge und Genehmigungen
- Berichtsgenerierung
- E-Mail-Versand
- Audit-Log
- PDF-Verarbeitung anstoßen

## Scheduler

Zuständig für:

- Monatsbericht automatisch erzeugen
- Review-Phase starten
- E-Mail nach Freigabe senden
