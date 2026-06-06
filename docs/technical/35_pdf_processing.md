# PDF-Verarbeitung

## Ziel

PDF-Ämtlipläne sollen eingelesen und in strukturierte Aufgaben umgewandelt werden.

## Pipeline

```text
1. PDF hochladen
2. Text/Tabelle extrahieren
3. Aufgaben, Mitglieder, Daten und Markierungen erkennen
4. Unsichere Werte markieren
5. Review-Screen anzeigen
6. Korrigierte Daten importieren
7. Import im Audit-Log dokumentieren
```

## Herausforderungen

- PDF kann echte Tabelle oder Bild sein
- Farben sind schwer zuverlässig zu erkennen
- Namen und Aufgaben können unterschiedlich geschrieben sein
- Markierungen müssen manuell überprüfbar sein

## Regel

PDF-Import ist eine Hilfe, keine endgültige Wahrheit.
