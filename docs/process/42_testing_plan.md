# Testplan

## Testarten

### Funktionale Tests

Prüfen:

- Mitglied hinzufügen
- Mitglied deaktivieren
- Aufgabe erstellen
- Aufgabe teilen
- Aufgabe ausführen
- Zusatzaufgabe erfassen
- Bericht generieren

### Governance-Tests

Prüfen:

- Preisänderung braucht Zustimmung
- Facilitator kann nicht allein entscheiden
- Signaturen sperren Beschluss
- alte Daten werden nicht überschrieben

### Datenintegritäts-Tests

Prüfen:

- Ausführung speichert Preis-Snapshot
- alte Berichte bleiben gleich
- Korrekturen erzeugen neuen Eintrag
- Audit-Log wird erstellt

### PDF-Tests

Prüfen:

- PDF wird hochgeladen
- Daten werden extrahiert
- Review ist möglich
- Import wird dokumentiert
