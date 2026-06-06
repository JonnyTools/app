# Datenmodell — Berichte und Analyse

## Monthly Report

```text
id
report_month
status
generated_at
generated_by
approved_at
locked_at
sent_at
recipient_email
summary_json
created_at
```

## Report Status

```text
draft
in_review
disputed
approved
locked
sent
```

## Report Line

```text
id
report_id
member_id
task_id
execution_id
task_name_snapshot
completed_at
price_snapshot
execution_type
```

## Analysis Snapshot

```text
id
period_start
period_end
generated_at
filters_json
included_statuses
excluded_statuses
member_summary_json
task_summary_json
fairness_summary_json
```

## Analyse muss dokumentieren

- Zeitraum
- Filter
- enthaltene Daten
- ausgeschlossene Daten
- Erstellungszeitpunkt
