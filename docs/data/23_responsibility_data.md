# Datenmodell — Zuständigkeiten und geteilte Aufgaben

## Responsibility Types

```text
single_member
shared
open_wg
extra
replacement
```

## Task Responsibility

```text
id
task_id
responsibility_type
valid_from
valid_until
frequency
distribution_rule
decision_id
created_at
```

## Task Responsibility Member

```text
id
task_responsibility_id
member_id
share_percentage
order_index
created_at
```

## Distribution Rules

```text
equal_split
alternating
flexible
weighted_split
```

## Beispiel

```text
Aufgabe:
Recycling

Zuständigkeit:
shared

Mitglieder:
Jonathan 50%
Anna 50%

Regel:
alternating

Gültig ab:
01.07.2026
```
