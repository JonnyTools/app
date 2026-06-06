# API-Design

## Grundprinzipien

- Jede Änderung wird serverseitig validiert.
- Wichtige Aktionen erzeugen Audit-Logs.
- Historische Daten werden nicht direkt überschrieben.
- Genehmigungsregeln werden im Backend erzwungen.

## Beispiel-Endpunkte

```text
POST /members/propose
POST /tasks/propose
POST /tasks/{id}/execute
POST /executions/{id}/approve
POST /decisions
POST /decisions/{id}/sign
POST /reports/monthly/generate
POST /reports/{id}/approve
POST /reports/{id}/send
POST /pdf/import
```

## Antwortstruktur

APIs sollten immer zurückgeben:

```text
success
data
error
audit_log_id
required_approvals
```
