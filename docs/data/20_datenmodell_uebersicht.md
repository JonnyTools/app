# Datenmodell — Übersicht

## Grundidee

Die App speichert nicht nur aktuelle Zustände, sondern auch historische Ereignisse.

Wichtige Datenobjekte:

```text
Member
Task
Task Price Version
Task Responsibility
Task Responsibility Member
Task Execution
WG Decision
WG Decision Signature
Audit Log
Monthly Report
Correction Request
PDF Import
Email Log
```

## Wichtiges Prinzip

Historische Daten dürfen nicht still überschrieben werden.

Beispiel:

```text
Falsch:
Preis direkt von CHF 2 auf CHF 3 ändern.

Richtig:
Neue Preisversion ab 01.07.2026 erstellen.
```
