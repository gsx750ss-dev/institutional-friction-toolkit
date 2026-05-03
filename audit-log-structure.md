# Audit Log Structural Requirements ｜ 監査ログ構造要件
(High-Impact AI Systems)

This document defines minimal logging conditions
for decision traceability and post-incident review.

---

## 1. Append-Only Requirement ｜ 追記専用要件

All approval records must be stored in append-only format.

Deletion or overwrite of prior entries is prohibited.

---

## 2. Identity Traceability ｜ 身元追跡性

Each approval must contain:

- Name
- Role
- Date
- Written reasoning

Anonymous collective approval is invalid.

---

## 3. Hash or Integrity Verification ｜ ハッシュまたは完全性検証

Approval logs must include integrity verification
(e.g., cryptographic hash, timestamping, or equivalent mechanism).

The objective is detection of modification,
not prevention of access.

---

## 4. Minority Opinion Preservation ｜ 少数意見の保存

If disagreement exists,
dissenting opinions must be recorded and preserved.

Absence of dissent record does not imply unanimity.

---

## 5. Post-Incident Retrieval ｜ 事後検索可能性

Logs must remain retrievable
for independent review
for a defined retention period.
