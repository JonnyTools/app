# Rollen und Rechte

## Grundprinzip

Die App soll keine starken permanenten Admins haben.

Empfohlenes Modell:

```text
Alle aktiven Mitglieder können Vorschläge machen.
Ein Facilitator kann eine WG-Sitzung vorbereiten.
Wichtige Änderungen brauchen Zustimmung aktiver Mitglieder.
```

## Rolle: Aktives Mitglied

Kann:

- eigene Aufgaben sehen
- Aufgaben als erledigt markieren
- Zusatzaufgaben erfassen
- Aufgaben für andere erledigen
- Vorschläge erstellen
- über Vorschläge abstimmen
- Monatsbericht prüfen
- Audit-Log ansehen

## Rolle: Facilitator

Kann zusätzlich:

- WG-Sitzung vorbereiten
- Änderungsvorschläge bündeln
- Beschlussentwurf erstellen
- Signaturrunde starten
- Berichtsentwurf vorbereiten

Kann nicht allein:

- Preise ändern
- Aufgaben dauerhaft neu verteilen
- Berichte finalisieren
- alte Daten löschen
- eigene strittige Zusatzaufgaben genehmigen

## Rolle: System

Das System:

- speichert alle Ausführungen
- erzeugt Audit-Logs
- sperrt signierte Beschlüsse
- erstellt Monatsberichte
- sendet Berichte erst nach Freigabe
- erzwingt Genehmigungsregeln
