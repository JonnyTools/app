# Datenmodell — Aufgabenausführungen

## Task Execution

Jede einzelne Ausführung einer Aufgabe wird separat gespeichert.

```text
id
task_id
task_name_snapshot
task_responsibility_id
assigned_member_id
shared_group_id
completed_by_member_id
completed_at
price_snapshot
currency_snapshot
execution_type
approval_status
source
note
created_at
```

## Execution Types

```text
assigned
shared
open
extra
replacement
correction
imported_from_pdf
```

## Approval Status

```text
accepted
pending
rejected
disputed
corrected
```

## Beispiel

```text
Aufgabe:
Recycling

Geteilt durch:
Jonathan, Anna

Erledigt von:
Jonathan

Datum:
03.04.2026

Preis:
CHF 3

Typ:
shared
```

## Regel

Eine Aufgabe kann geteilt sein, aber jede Ausführung gehört genau zu einer Person, die sie erledigt hat.
