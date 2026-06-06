# Datenmodell — PDF-Import

## Zweck

PDF-Ämtlipläne können importiert und in strukturierte Aufgaben übertragen werden.

## PDF Import

```text
id
filename
uploaded_by_member_id
uploaded_at
status
detected_period
reviewed_by_member_id
reviewed_at
```

## PDF Import Row

```text
id
pdf_import_id
raw_text
detected_task_name
detected_member_name
detected_date
detected_week
detected_marker
confidence_score
mapped_task_id
mapped_member_id
review_status
```

## Status

```text
uploaded
parsed
needs_review
reviewed
imported
failed
```

## Regel

PDF-Daten werden nie blind übernommen. Es gibt immer eine Review-Ansicht.
