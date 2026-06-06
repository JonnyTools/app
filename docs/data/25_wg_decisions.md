# Datenmodell — WG-Beschlüsse

## WG Decision

```text
id
decision_number
meeting_date
effective_date
created_by_member_id
summary
status
approval_rule
locked_at
created_at
```

## Status

```text
draft
waiting_for_signatures
approved
rejected
locked
cancelled
```

## Decision Change

```text
id
decision_id
change_type
target_type
target_id
old_value_json
new_value_json
reason
```

## Beispiel

```text
Beschluss:
DEC-2026-07-001

Änderungen:
- Sofia wird aktives Mitglied.
- Marco wird ab 01.07.2026 inaktiv.
- Recycling kostet ab 01.07.2026 CHF 3.
- Recycling wird Jonathan und Anna gemeinsam zugewiesen.
```
