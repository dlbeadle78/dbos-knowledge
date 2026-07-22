# Innovate Awarding catalogue schema

This schema defines the minimum fields for Phase 1 catalogue records.

## Required fields

- `sector`
- `product_type` — Apprenticeship or Qualification
- `title`
- `level`
- `standard_reference` — ST/FA reference where applicable
- `product_or_qualification_number`
- `version`
- `status`
- `official_overview_url`
- `source_page`
- `date_checked`
- `verification_notes`

## Status vocabulary

Use one of:

- `current-publicly-listed`
- `future-publicly-listed`
- `closed-for-registrations`
- `superseded-or-legacy-publicly-listed`
- `status-not-confirmed`

## Rules

1. Do not infer that the highest version applies to every learner.
2. Do not merge assessment methods, KSBs or grading rules across versions.
3. Record missing product numbers as `not-shown-on-public-catalogue`.
4. Use exact official titles and references.
5. Treat catalogue presence as evidence that a product is publicly listed, not automatic proof that it is open for all registrations.
6. Recheck operational updates before making high-stakes decisions.

## Primary source

https://innovateawarding.org/services/assessment/

## Last schema review

22 July 2026
