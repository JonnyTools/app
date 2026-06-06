# Mitglieder-Lifecycle

## Statuswerte

Ein Mitglied kann folgenden Status haben:

```text
Pending
Aktiv
Inaktiv
Archiviert
```

## Neues Mitglied

Beim Hinzufügen werden gespeichert:

- Name
- E-Mail
- Startdatum
- Rolle
- Status
- Beschluss-ID
- Signaturen der aktiven Mitglieder

## Altes Mitglied

Alte Mitglieder sollten nicht gelöscht werden, wenn sie historische Daten haben.

Stattdessen:

```text
Status = Inaktiv
Austrittsdatum speichern
Historie behalten
Aus zukünftigen Aufgaben entfernen
```

## Löschen

Echtes Löschen ist nur erlaubt, wenn:

- keine Ausführungen existieren
- keine Signaturen existieren
- keine Berichte betroffen sind

Sonst wird archiviert oder anonymisiert.
