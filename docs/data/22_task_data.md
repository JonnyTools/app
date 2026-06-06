# Datenmodell — Aufgaben

## Task

```text
id
name
category
description
active
created_at
deactivated_at
created_by_member_id
```

## Task-Kategorien

Beispiele:

```text
Reinigung
Entsorgung
Einkauf
Küche
Organisation
Sonstiges
```

## Task Price Version

```text
id
task_id
price
currency
valid_from
valid_until
decision_id
created_at
```

## Regeln

- Preise sind versioniert.
- Ausführungen speichern immer einen Preis-Snapshot.
- Alte Berichte ändern sich nicht durch neue Preise.
