# dismathportfolio-kcj3687
dismathportfolio-kcj3687 created by Classroom for GitHub

#Week1
-Introduction about the subject **"DISMATH(Discrete Mathematics)"**<br>
-DISMATH is all about **Proposition**, **Proof**, **Logical Deduction**, and **Axioms**<br>
-Proposition which is a declarative statement which should be either true (1) or false(2); however, cannot be both.<br>
-The several types of **TRUTH** which are **Legal Truth**, **Authorative Truth**, **Scientific Truth**, **Probable Truth**, and **Philosophical Truth**<br>
-**Logical Connectives** and its usage.<br>

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

-Using the truth table

#Week2
- learned a set of laws and rules for DIAMATH called **Logical Equivalences**.<br>

|                           Equivalence                          |         Name        |
|:--------------------------------------------------------------:|:-------------------:|
|                      p ∧ T ≡ p  //     p v F ≡ p               |    Identity laws    |
|                       p v T ≡ T  //    p ∧ F ≡ F               |   Domination laws   |
|                       p v p ≡ p //     p ∧ p ≡ p               |   Idempotent laws   |
|                            ¬(¬p) ≡ p                           | Double negation law |
|                   p v q ≡ q v p // p ∧ q ≡ q ∧ p               |   Commutative laws  |
|       (p v q) v r ≡ p v (q v r) // (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)   |   Associative laws  |
| p v (q ∧ r) ≡ (p v q) ∧ (p v r) //  p ∧(q v r) ≡ (p ∧ q) v (p ∧ r) |  Distributive laws  |
|              ¬(p ∧ q) ≡ ¬p v ¬q // ¬(p v q) ≡ ¬p ∧ ¬q          |   De Morgan's laws  |
|                 p v (p ∧ q) ≡ p // p ∧ (p v q) ≡ p             |   Absorption laws   |
|                     p v ¬p ≡ T // p ∧ ¬p ≡ F                   |    Negation laws    |

-Proved that SUPERMAN does not exist.<br>
-The predicate Logic which is concerned not only with logic relations betwwen sentences or propositions as WHOLES, but also their internal structure in terms of subject and predicate.<br>
-Qualifiers indicates the generality of the open sentece in which a variable counts.<br>
  - **Extential Quantifier** (∃x) 
  "There exist"
  - **Universal Quantifier** (∀x) 
  "For all"

#Week3
-We learned **Rules of Inference**

|          Name          |   Rules of Inference       |            Tautology           |
|:---------------------: |:-------------------------:|:-----------------------------:|
|      Modus Ponens      |       p<br>p→q<br>∴q      |        (p ∧ (p → q)) → q       |
|      Modus Tollens     |     ¬q<br>p→q<br>∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |
| Hypothetical Syllogism |     p→q<br>q→r<br>∴p→r    |  ((p → q) ∧ (q → r)) → (p → r) |
|  Disjunctive Syllogism |      p∨q<br>¬p<br>∴q      |       ((p ∨ q) ∧ ¬p) → q       |
|        Addition        |       p<br>∴p ∨ q         |           p → (p ∨ q)          |
|      Simplication      |       p ∧ q<br>∴p         |           (p ∧ q) → p          |
|       Conjunction      |      p<br>q<br>∴p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |
|       Resolution       | p ∨ q<br>¬p ∨ r<br>∴q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |

-Also learned **Mehods of Proof**, and its first type which is
   - **Direct Proof**
     1. Assume p is **TRUE**
     2. Show that q is also **TRUE**
 
