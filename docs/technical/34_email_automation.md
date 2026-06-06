# E-Mail-Automation

## Zweck

Die App soll Monatsberichte automatisch per E-Mail versenden können.

## Ablauf

```text
1. Monatsbericht wird generiert.
2. Bericht geht in Review.
3. Mitglieder prüfen Bericht.
4. Bericht wird genehmigt.
5. Bericht wird final gesperrt.
6. System sendet E-Mail.
7. Versand wird dokumentiert.
```

## Email Log

```text
id
report_id
recipient_email
sent_at
status
provider_message_id
error_message
created_at
```

## Regel

Der finale Monatsbericht wird nicht automatisch gesendet, solange er nicht genehmigt und gesperrt ist.
