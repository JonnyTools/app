# Datenmodell — Signaturen und Audit-Log

## WG Decision Signature

```text
id
decision_id
member_id
signed_at
accepted
signature_method
comment
created_at
```

## Audit Log

```text
id
actor_member_id
action_type
target_type
target_id
old_value_json
new_value_json
reason
related_decision_id
created_at
```

## Auditierte Aktionen

- Aufgabe erstellt
- Aufgabe geändert
- Preis geändert
- Mitglied hinzugefügt
- Mitglied deaktiviert
- Aufgabe erledigt
- Zusatzaufgabe erstellt
- Bericht generiert
- Bericht gesendet
- Beschluss unterschrieben

## Regel

Das Audit-Log ist für alle aktiven Mitglieder sichtbar und nicht bearbeitbar.
