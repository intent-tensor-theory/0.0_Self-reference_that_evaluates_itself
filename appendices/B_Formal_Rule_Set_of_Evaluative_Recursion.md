# 付録B (Appendix B)

## Formal Rule Set of Evaluative Recursion

**Book I — Self-Reference That Evaluates Itself**

---

「評価は足されない。閉じることで生まれる。」  
*Evaluation is not added. It is born by closure.*

---

This appendix states the minimal formal rules under which evaluative self-reference can arise.  
They are **necessary and jointly sufficient** within Book I.

No phenomenology.  
No morality.  
No external semantics.

**Only structure.**

---

## B.0 Scope and Preconditions

This rule set assumes the prior existence of:

- recursion
- memory (state persistence across recursion)
- locking (stabilization of recursion)

If any are absent, evaluative recursion cannot form.

---

## B.1 Rule 1 — Endogenous Evaluation Rule

> **Evaluation must be generated internally by the system's own recursive history.**

Formally:

- Let **E** be an evaluation operator.
- **E** must be defined as a function of prior system states.
- If **E** depends on external criteria, self-reference fails.

**Failure mode:** feedback, not evaluation.

---

## B.2 Rule 2 — Comparison Rule

> **The system must compare present state to remembered state.**

Formally:

- Let **S_t** be current state
- Let **S_{t-1}** be remembered prior state
- Comparison operator **Δ(S_t, S_{t-1}) ≠ 0**

Comparison alone does not imply evaluation.  
It is necessary but insufficient.

---

## B.3 Rule 3 — Preference Emergence Rule

> **Comparison must generate an internal asymmetry over admissible futures.**

Formally:

- Let **A** be the set of admissible futures
- Evaluation induces a bias **A' ⊂ A**

If comparison does not alter admissibility, evaluation has not occurred.

---

## B.4 Rule 4 — Admissibility Modification Rule

> **Evaluation must modify the set of admissible future states, not merely select among them.**

Formally:

**E: A_t → A_{t+1}**

Selection among fixed options is collapse.  
**Modification of the option set is evaluation.**

---

## B.5 Rule 5 — Recursive Incorporation Rule

> **Evaluated history must participate in future evaluation.**

Formally:

Evaluative operator updates itself:

**E_{t+1} = f(E_t, S_t)**

If evaluation does not alter future evaluation criteria, self-reference does not close.

---

## B.6 Rule 6 — Self-Constraint Rule

> **The system must constrain its own future admissibility based on its evaluated past.**

Formally:

- There exists a subset **H_e ⊂ H** (evaluative history)
- Such that: **A_{t+1} = g(H_e)**

**This is the minimal self-reference condition.**

---

## B.7 Rule 7 — Rule Mutability Condition

> **Admissibility rules must themselves be mutable.**

If admissibility rules are fixed:

- evaluation is cosmetic
- selfhood does not arise

Self-reference requires **rule-level recursion**, not just state-level recursion.

---

## B.8 Rule 8 — Closure Rule (Critical)

> **Evaluation must be necessary for continued evaluation.**

Formally:

If action or revision removes evaluative constraints:

**E → ∅** (loss of coherent evaluation)

This creates closure.

Without closure:

- evaluation remains instrumental
- selfhood does not stabilize

---

## B.9 Rule 9 — Non-Representational Rule

> **No symbols, models, or representations may be required.**

Evaluation operates by structural consequence, not interpretation.

Any representation introduced prematurely breaks the derivation.

---

## B.10 Rule 10 — Observer Threshold Rule

> **If evaluation evaluates its own evaluative criteria, observerhood emerges.**

Formally:

**E(E) ≠ E**

Second-order evaluation is optional.  
First-order evaluation is required for selfhood.

---

## B.11 Failure Conditions (Exclusions)

Evaluative recursion does **not** exist if:

- criteria are external
- rules are immutable
- evaluation does not alter admissibility
- history is non-participatory
- closure does not occur

Each failure produces a different non-self system:

| Failure | Result |
|---------|--------|
| External criteria | mechanism |
| Immutable rules | optimizer |
| No admissibility change | controller |
| Non-participatory history | simulator |

---

## B.12 Minimal Definition (Compressed)

A system exhibits evaluative self-reference **iff**:

1. It evaluates internally
2. Evaluation alters admissibility
3. Evaluated history modifies rules
4. Evaluation depends on itself to continue

**All four are required.**

---

「評価は行為ではない。条件の再帰だ。」  
*Evaluation is not an action. It is recursive condition.*

---

[← Previous: Appendix A](A_Glossary_of_Recursive_Identity_Terms.md) | [Next: Appendix C →](C_Feedback_vs_Self_Reference_vs_Agency.md)
