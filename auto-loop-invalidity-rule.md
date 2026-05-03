# Automated Development Loop – Procedural Invalidity Rule ｜ 自動開発ループ — 手続的無効ルール

This rule applies to AI systems involved in iterative self-improvement,
automated testing, or performance optimization pipelines.

It does not prohibit development.
It defines conditions under which approval is procedurally invalid.

## External Explanation ｜ 外部説明

Closed-loop self-evaluation means that the same AI system, or a dependent automated loop, generates the criteria, evaluates the output, and approves continuation without independent human validation.

Under LUMINA-30 boundary review, this is not enough to demonstrate effective human refusal, because the system is effectively reviewing its own continuation path.

閉ループ自己評価とは、同一AIシステムまたは依存する自動ループが、基準生成・出力評価・継続承認を独立した人間検証なしに行う状態を指す。

LUMINA-30の境界レビュー上、これは実効的な人間拒否を示すには不十分である。システムが自らの継続経路を実質的に審査しているためである。

---

## 1. AI Evaluation Non-Sufficiency ｜ AI評価の非十分性

AI-generated evaluation results,
performance metrics,
or optimization outputs
shall not constitute sufficient grounds for approval.

Human written justification is mandatory.

---

## 2. Human Judgment Requirement ｜ 人間判断要件

For each major release, update, or deployment:

- A named human reviewer must provide written reasoning.
- The reasoning must address why continuation was not stopped.
- Mere acknowledgment of AI outputs is insufficient.

If no written reasoning exists,
approval is invalid.

---

## 3. Closed-Loop Prohibition (Procedural) ｜ 閉ループ禁止（手続上）

If an AI system:

- Generates its own evaluation criteria,
- Evaluates its own outputs,
- Approves its own modifications,

without independent human validation,

the approval shall be considered procedurally invalid.

---

## 4. Reversibility Confirmation ｜ 可逆性確認

Before deployment, confirm:

- Human intervention remains technically possible.
- Operational halt can be executed.
- Responsibility attribution is defined.

If reversibility cannot be demonstrated,
approval is invalid.
