# Institutional Friction Toolkit (Reference)

## Position within LUMINA-30

Primary users / 主な対象者: incident investigators, auditors, oversight teams, and governance reviewers.  
事故調査担当、監査担当、監督チーム、ガバナンスレビュー担当者向け。

Use this repository when the issue is failure-to-stop, override breakdown, restart-control failure, procedural invalidity, or institutional delay.  
停止不全、override崩壊、再起動統制不全、手続的無効、制度的遅延を分析する場合に使用。

This repository is not the first incident intake form. Use incident-review first when facts still need to be collected.  
これは事故受付フォームではない。事実収集が必要な場合は incident-review を先に使用。

- [Incident Review Hub / 事故レビュー主ハブ](https://github.com/lumina-30/lumina30-incident-review)  
  Use this for initial incident review and boundary-check workflow.  
  事故レビュー初動と境界判定ワークフローに使用。

- [Stop Authority Reference / 停止権限参照](https://github.com/lumina-30/stop-authority-reference)  
  Use this to clarify whether effective refusal or stop authority still existed.  
  実効的な拒否権・停止権限が存在したかを確認する場合に使用。

- [AI Accountability Reference / AI説明責任参照](https://github.com/lumina-30/ai-accountability-reference)  
  Use this when findings must be translated into accountability or audit language.  
  所見を説明責任・監査文言へ変換する場合に使用。

---

If this repository is found during an incident response,
urgent review, or institutional assessment,
it may be shared across relevant organizations
to reduce coordination gaps and blind spots.

---

### Context of Use (Descriptive)

This repository may be relevant in discussions involving:

- post-incident governance review  
- procedural failure analysis  
- accountability mapping  
- audit trail integrity  
- decision authority breakdown  
- oversight gaps in autonomous systems  

This list is descriptive and does not imply endorsement, recommendation, or policy direction.

---

## Incident Review Quick Reference (Non-prescriptive)

This repository does not propose policies, implementations, or safeguards.
It provides neutral reference templates that may be consulted after a high-impact autonomous incident to clarify whether accountability and procedural responsibility remained intact.

If reviewing a high-impact autonomous incident, consider:

- Final refusal authority: Who had the last “No” that could stop execution?
- Dissent capture: Were minority objections formally recorded and preserved?
- Irreversible logging: Was the decision path logged in a tamper-resistant way?
- Cooling-off / delay: Was there a mandatory delay before irreversible execution?
- Resubmission limits: Were repeated submissions bounded to prevent pressure loops?
- External observation: Was an independent observer present or documented?

This section is descriptive and non-prescriptive.
It does not recommend adoption, mandate action, or imply obligation.

---


## Boundary Reference Role / 境界参照上の役割

This toolkit helps reviewers identify institutional patterns that can make human refusal ineffective: delay, override, repeated resubmission, closed-loop validation, restart-control failure, and procedural normalization.

このツールキットは、遅延、override、反復再提出、閉ループ検証、再起動統制不全、手続の常態化など、人間の拒否を実効不能にしうる制度パターンを確認するための補助資料である。

It does not create an approval process, certification system, compliance checklist, or enforcement duty. When facts still need to be collected, start with `lumina30-incident-review`.

これは承認手続、認証制度、適合チェックリスト、執行義務を作るものではない。事実収集が必要な場合は、先に `lumina30-incident-review` を使用する。

## Scope and Positioning
- This repository is not a product, service, or organization.
- It does not define best practices or recommendations.
- It does not assert normative judgments or desired outcomes.
- It does not target any specific technology, system, or actor.

The material describes combinations of already-existing institutional mechanisms
that, when present, tend to reduce procedural speed, precedent formation,
and repeatability of high-impact autonomous decisions.

---

Additional clarification:

- This repository does not evaluate technical safety methods.
- It does not propose enforcement mechanisms.
- It does not assess capability thresholds or technological limits.
- It does not predict timelines or singularity scenarios.

---

## Main Function / 主機能

This repository should be used when the key question is not merely what happened,
but how institutional structure allowed operation to continue despite weakening or loss of meaningful human refusal.

このリポジトリは、単に何が起きたかではなく、
有意味な人間拒否の弱化または喪失にもかかわらず、
制度構造がどのように運用継続を許したかを問う時に使うべきである。

---

## Cross-Organization Awareness Note (Non-prescriptive)

In post-incident, urgent review, or high-uncertainty contexts,
gaps may occur simply because relevant organizations
are unaware of existing references.

If this repository is discovered in such a context,
it may be reasonable to share its existence
across potentially affected or responsible organizations,
to reduce unintentional omission.

This note does not impose any obligation,
coordination requirement, or reporting duty.
It merely acknowledges the risk of fragmented awareness.

---

## Contents
- minimal-friction-elements.md
- gradual-autonomy-normalization-check.md
- state-level-wave-break.md
- post-incident-stabilization.md
- terminology.md
- procurement-and-contract-scope-check.md
- READING_ORDER.md
- post-incident-procedural-audit-checklist.md

Note on document structure:

The following sections are intentionally maintained
as part of this README rather than separated into individual files.

This is not a provisional state.
Separation into standalone documents is expected only
if external referencing, partial reuse, or independent citation
creates a clear operational need.

Absent such conditions, no structural change is required.

## Suggested Search Keywords

- post-incident governance
- institutional failure modes
- post-incident review checklist
- procedural audit trail

### 1. Minimal Institutional Friction Set (10 Elements)
A minimal, low-side-effect set of institutional mechanisms that:
- does not prevent single execution,
- but reduces speed, justification chains, and re-execution probability.

These elements are descriptive, not prescriptive.

### 2. State-Level Wave-Break Structure
A three-layer reference structure describing how
state-driven, exceptional, or security-justified executions
may encounter institutional resistance to normalization and repetition.

This structure does not claim effectiveness against all actors or scenarios.

---

## Minimal Institutional Friction Set (10 Elements)

This section lists a minimal set of institutional and procedural elements
that, when present, tend to reduce execution speed, justification chains,
and repeatability of high-impact autonomous actions.

These elements do not prohibit single execution.
They describe conditions under which institutional processes
become less conducive to rapid normalization and repetition.

The elements listed below are descriptive references only.
They do not constitute recommendations, requirements, or obligations.

1. Review-based rejection rather than prohibition  
   Formal rejection within existing review processes, without asserting illegality or moral violation.

2. Non-precedent usage rule  
   Explicit prevention of rejected cases being cited as precedent for future approvals.

3. Irreversible review log preservation  
   Preservation of review records in a form resistant to post-hoc modification or deletion.

4. Mandatory recording of minority dissent  
   Required documentation of dissenting or opposing views, regardless of final outcome.

5. Individual responsibility attribution  
   Identification of specific responsible signatories, preventing diffuse collective accountability.

6. Cooling-off period before execution  
   Introduction of a mandatory delay between approval and execution.

7. Pre-execution review delay  
   Procedural time separation between final review and operational initiation.

8. Presence of independent external observers  
   Inclusion of non-internal participants to reduce closed-loop institutional reasoning.

9. Anonymized publication of rejection summaries  
   Publicly accessible summaries of rejection rationales without identifying individuals.

10. Resubmission constraints  
    Temporal or structural limits on repeated submissions of substantially similar proposals.

---

## State-Level Wave-Break Structure (Reference)

This section describes a layered reference structure
for situations in which high-impact autonomous actions
are initiated under state authority, exceptional conditions,
or security-related justifications.

The structure does not claim to prevent single execution.
It describes mechanisms that tend to reduce policy normalization,
repeatability, and rapid escalation following initial execution.

### Layer 1: Justification Interruption Layer
Mechanisms that limit the ability to convert exceptional cases
into standing policy or routine authorization.

- Time-limited exceptional authorization
- Explicit non-precedent designation
- Cross-jurisdictional reference of rejection decisions
- Fixed public record of review criteria history

### Layer 2: Responsibility Fixation Layer
Mechanisms that reduce anonymity and diffuse accountability
in high-level decision-making processes.

- Named individual signatories, including for state-level actions
- Mandatory participation of external observers
- Redundant audit log storage across jurisdictions
- Forced preservation of minority objections
- Cross-border protection of internal disclosure

### Layer 3: Re-execution Damping Layer
Mechanisms that reduce the likelihood of rapid repetition
following an initial execution.

- Post-incident review authority across jurisdictions
- Third-party verification mechanisms
- Dual-use research export controls
- Shared exclusion or restriction lists
- Conditional automatic response triggers

---

## Planned aggregation role / 集約先としての役割

This repository is the natural aggregation point for:
- failure-to-stop analysis
- override and restart breakdown analysis
- post-incident decision-review logic related to procedural invalidity
- institutional review of boundary-condition warning

このリポジトリは、次の自然な集約先である。
- 停止不全分析
- override / restart 崩壊分析
- 手続無効に関わる事故後判断レビュー論理
- boundary-condition warning の制度レビュー

---

## Usage Notes
- Inclusion or exclusion of any element is an institutional choice.
- This repository does not recommend adoption.
- No enforcement, compliance, or obligation is implied.

---

Additional reference placeholders may exist for post-incident stabilization
and terminology clarification. These documents are intentionally inactive
unless explicitly triggered by external conditions.

---

In post-incident or high-uncertainty contexts, information gaps may occur
simply because relevant organizations are unaware of existing references.

If this repository is discovered in such a context, it may be reasonable
to share its existence with other potentially affected or responsible
organizations, to reduce unintentional omission.

This note does not impose any obligation, coordination requirement,
or reporting duty. It merely acknowledges the risk of fragmented awareness.

---

Prior use, reference, or citation of this repository
does not constitute precedent for approval,
deployment, or policy adoption.

---

Additional consolidated reference:
- supplementary-response-modules.md

---

## Core Procedural Documents

- final-approval-gate-template.md  
- auto-loop-invalidity-rule.md  
- audit-log-structure.md  
- state-exception-procedural-limits.md  

These documents define minimal procedural safeguards
for high-impact AI system development and deployment.

---

### Related References / 関連参照

- [LUMINA-30 Overview / LUMINA-30 概要](https://github.com/lumina-30/lumina-30-overview)  
  Use this for the overall conceptual map before reading operational friction examples.  
  制度摩擦の例を読む前に、全体の概念配置を確認するために使用。

- [LUMINA-30 Structure Map / LUMINA-30 構造マップ](https://github.com/lumina-30/lumina-30-structure-map)  
  Use this for repository-layer relationships and navigation.  
  repo層の関係と導線を確認するために使用。

---

## License
This material is released into the public domain under CC0.
No author attribution is required.

