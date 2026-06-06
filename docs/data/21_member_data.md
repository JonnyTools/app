# Datenmodell — Mitglieder

## Member

```text
id
name
email
role
status
joined_at
left_at
created_at
updated_at
```

## Statuswerte

```text
pending
active
inactive
archived
```

## Member Status History

```text
id
member_id
old_status
new_status
valid_from
valid_until
reason
decision_id
created_at
```

## Regeln

- Aktive Mitglieder dürfen abstimmen.
- Inaktive Mitglieder bleiben in alten Berichten sichtbar.
- Mitglieder mit Historie werden nicht hart gelöscht.
