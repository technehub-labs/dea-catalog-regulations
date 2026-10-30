# CR-REG-CAT-02: Initial Population

| Field | Value |
|---|---|
| **CR** | CR-REG-CAT-02 |
| **Title** | Initial population: the eight jurisdiction anchors of the information classification scheme |
| **Status** | Landed |
| **Layer** | Catalogue (L2 Risk & Compliance) |
| **Programme** | Org-wide catalog advancement (Wave 1) |
| **Repository** | `technehub-labs/dea-catalog-regulations` |
| **Author** | Emmanuel A. Otchere |
| **Date** | 2026-11-02 |
| **Depends on** | CR-REG-CAT-01 (kit); CR-IC-CAT-08 (the jurisdiction vocabulary this population grounds) |
| **Trigger** | The information-classes catalogue's jurisdiction-regime classification (CR-IC-CAT-08, binding axis 3) names eight statutes/standards as regime anchors with definitions but no owning catalogue records. This is that record set. |

## 1. Executive summary

Eight canonical Regulation records are admitted, one per value in the information-classes `jurisdiction-regime-classifications.yaml` vocabulary (eu-gdpr, uk-gdpr, us-ccpa-cpra, us-hipaa, pci-dss, us-dtsa, eu-trade-secrets-directive, and the vocabulary's eighth member). Each record's description quotes the vocabulary's definition and names the regime(s) it anchors; the evidence source is the committed vocabulary file.

## 2. Seed selection (FOUNDATIONS D-5)

Every seed is a committed classification vocabulary value corroborated at admission. No regulations beyond the cited vocabulary are admitted.

## 3. Scope

In scope: 8 record subtrees, CATALOG.yaml regeneration, register row, CHANGELOG.

Out of scope: jurisdiction modeling beyond the vocabulary's anchor roles; IC-side changes (their vocabulary already cites these anchors); metamodel lifecycle backfill (wave boundary).

## 4. Acceptance criteria

1. Gates 1-6 all `Findings: 0` with 8 canonical records.
2. `CATALOG.yaml` counts: entities 8, canonical 8, open_change_requests 0.

## 5. NOT-list

1. No regulations beyond the eight vocabulary anchors.
2. No legal-text summarization beyond the committed definitions.
