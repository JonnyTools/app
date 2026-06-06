# Sicherheitsmodell

## Ziele

- Nur berechtigte Mitglieder sehen WG-Daten.
- Alle wichtigen Aktionen sind nachvollziehbar.
- Keine einzelne Person kann sensible Daten manipulieren.
- Historische Daten bleiben korrekt.

## Authentifizierung

Möglichkeiten:

- E-Mail Login
- Magic Link
- Passwortloser Login
- später: Passkeys

## Berechtigungen

Datenzugriff nach WG und Mitgliedschaft.

Aktive Mitglieder sehen:

- Aufgaben
- Ausführungen
- Berichte
- Beschlüsse
- Audit-Log

Inaktive Mitglieder sehen optional nur alte eigene Berichte.

## Schutzregeln

- Audit-Log nicht bearbeitbar
- Signaturen nicht bearbeitbar
- gesperrte Berichte nicht bearbeitbar
- alte Preise nur über neue Versionen ändern
- Korrekturen statt stiller Edits
