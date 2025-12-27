# 付録D (Appendix D)

## Symbol Index (Evaluation Operators)

**Book I — Self-Reference That Evaluates Itself**

---

「記号は構造を圧縮する。」  
*Symbols compress structure.*

---

This appendix catalogs the formal symbols and operators used throughout Book I.

All symbols are structural.  
None carry phenomenological or moral content.

---

## Primary Operators

### E — Evaluation Operator

The core operator of Book I.

**E** maps system states to evaluative outcomes that alter admissibility.

**E: S → A'**

Where:
- **S** = current state
- **A'** = modified admissibility set

**E** must be endogenous (internally generated).

---

### Δ — Comparison Operator

Detects non-equivalence between states.

**Δ(S_t, S_{t-1})**

Returns:
- **0** if states are equivalent
- **≠ 0** if states differ

Comparison is necessary but insufficient for evaluation.

---

### R — Revision Operator

Attempts to modify a constraint or preference.

**R(X)**

Where **X** is the target of revision.

If **R(X) → collapse**, then **X** is self-referentially bound.

---

## State Variables

### S_t — Current State

The present configuration of the system at recursion step **t**.

---

### S_{t-1} — Prior State

A remembered state from earlier recursion.

Comparison requires both **S_t** and **S_{t-1}**.

---

### H — History Set

The complete record of past states.

**H = {S_0, S_1, S_2, ...}**

---

### H_e — Evaluative History

The subset of history that participated in evaluation.

**H_e ⊂ H**

Only **H_e** contributes to self-reference.

---

## Admissibility Sets

### A — Admissibility Set

The set of futures currently allowed by system constraints.

**A = {possible future states}**

---

### A' — Modified Admissibility

The admissibility set after evaluation.

**A' ⊂ A** (typically)

Evaluation restricts, not expands, admissibility.

---

### A_t — Admissibility at Time t

The admissibility set at recursion step **t**.

Self-reference requires:

**A_{t+1} = g(H_e)**

---

## Transition Functions

### f — Evaluative Update Function

Updates the evaluation operator based on state and prior evaluation.

**E_{t+1} = f(E_t, S_t)**

This is the core of recursive self-constraint.

---

### g — Admissibility Function

Maps evaluative history to future admissibility.

**A_{t+1} = g(H_e)**

---

## Failure Indicators

### ∅ — Evaluation Collapse

Loss of coherent evaluation.

**E → ∅**

Indicates failure of self-reference or identity dissolution.

---

## Threshold Markers

### E(E) — Second-Order Evaluation

Evaluation applied to itself.

**E(E) ≠ E**

When this condition holds, **observerhood** emerges.

---

## Structural Checkmarks (Chapter Progress)

Throughout the book, progress is marked:

| Symbol | Meaning |
|--------|---------|
| ✔ | Successfully derived |
| ✘ | Not yet present |
| ⏳ | Incipient / emerging |

---

## Comparative Operators

### ≠ — Non-equivalence

Used in comparison operations.

**Δ(S_t, S_{t-1}) ≠ 0** → difference detected

---

### ⊂ — Subset

Used for admissibility restriction.

**A' ⊂ A** → evaluation has constrained futures

---

### → — Maps to / Produces

Used for functional relationships.

**E: S → A'** → evaluation maps states to modified admissibility

---

## Summary Table

| Symbol | Name | Domain |
|--------|------|--------|
| **E** | Evaluation Operator | Core |
| **Δ** | Comparison Operator | Comparison |
| **R** | Revision Operator | Self-constraint |
| **S_t** | Current State | States |
| **S_{t-1}** | Prior State | States |
| **H** | History Set | Memory |
| **H_e** | Evaluative History | Memory |
| **A** | Admissibility Set | Futures |
| **A'** | Modified Admissibility | Futures |
| **f** | Evaluative Update | Transitions |
| **g** | Admissibility Function | Transitions |
| **∅** | Collapse | Failure |
| **E(E)** | Second-Order Evaluation | Observer |

---

「記号は構造の名である。構造なき記号は空である。」  
*Symbols are names for structure. Symbols without structure are empty.*

---

[← Previous: Appendix C](C_Feedback_vs_Self_Reference_vs_Agency.md) | [Back to README →](../README.md)
