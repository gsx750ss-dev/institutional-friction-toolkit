# Audit Log Structural Requirements
(High-Impact AI Systems)

This document defines minimal logging conditions
for decision traceability and post-incident review.

---

## 1. Append-Only Requirement

All approval records must be stored in append-only format.

Deletion or overwrite of prior entries is prohibited.

---

## 2. Identity Traceability

Each approval must contain:

- Name
- Role
- Date
- Written reasoning

Anonymous collective approval is invalid.

---

## 3. Hash or Integrity Verification

Approval logs must include integrity verification
(e.g., cryptographic hash, timestamping, or equivalent mechanism).

The objective is detection of modification,
not prevention of access.

---

## 4. Minority Opinion Preservation

If disagreement exists,
dissenting opinions must be recorded and preserved.

Absence of dissent record does not imply unanimity.

---

## 5. Post-Incident Retrieval

Logs must remain retrievable
for independent review
for a defined retention period.
