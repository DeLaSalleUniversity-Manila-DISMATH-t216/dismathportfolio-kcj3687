# dismathportfolio-kcj3687
dismathportfolio-kcj3687 created by Classroom for GitHub

#Week 1
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

#Week 2
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

#Week 3
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
     P → Q
     1. Assume p is **TRUE**
     2. Show that q is also **TRUE**
 
#Week 4
-Learned other types of **Mehods of Proof**.
   - **Contraposition/Indirect Proof**
     ¬Q → ¬P
     1. Assume ¬q is **TRUE**.
     2. Show that ¬P must be **TRUE**.

   - **Vacuous Proof**
     ¬P → (P → Q)
     1. Show that P is **FALSE** .
     2. Because P → Q must be true when p is **FALSE**.

   - **Trivial Proof**
     Q → (P → Q)
     1. Show that Q is **TRUE**.
     2. It follows that P → Q must also be **TRUE**.
  
   - **Proof by Contradiction**.
     ¬(Premise) = T
     1. Assume that the premise is not **TRUE**
     2. Show that the premise will end up in a contradiction.
  
- Learned the definition of a rational number which is {a/b | a, b ∈ ℤ, b≠0, a & b have no common factors other than ±1}.

#Week 5
   - **Proof by Equivalence**(Biconditionals)
     (P ↔ Q) ↔ [(P → Q) ∧ (Q → P)]
     1. Show that P → Q .
     2. Q → P are both **TRUE**.
 - The new lesson **Mathematical Induction**.
   - Two steps of Mathematical Induction.
    - Basis
      - Show that P(1) or P(0) to be **True**
    - Direct Proof
      - Asumme P(k) ≡ T
      - Show P(k+1) ≡ T


#Week 6
#Week 7
#Week 8
#Week 9
 **Searching Algorithm** - The Problem of locationg an algorithm in an ordered list.
   - Linear Search Algorithm.<br>
   - Binary Search Algorithm.<br>

 **Sorting Algorithms** - The problem of putting elements in increasing order.
   - Bubble Sort Algorithm.<br>
   - Insertion Sort Algorithm.<br>

#Week 10
 **Greedy Algorithms** - algorithms that make what seems to be the “best” choice at each step
  - **Growth of Functions**
     - **Big-O Notation** - Let f and g be functions from the set of integers or the set of real numbers to the set of real numbers. We say that f(x) is O(g(x)) if there are constants C and k such that |f (x)| ≤ C|g(x)| whenever x > k. It provides the upper bound for the size of f(x)
     - **Big-Omega Notation** - Let f and g be functions from the set of integers or the set of real numbers to the set of real numbers. We say that f(x) is 􏰰(g(x)) if there are positive constants C and k such that |f(x)| ≥ C|g(x)| whenever x > k. It provides the lower bound for the size of f(x).
     - **Big-Theta Notation** - It provides upper and lower bound.
  - C (Constant Multipier) and k (Number of input values) are called **witnesses**.
  **Complexity of Algorithms**
   - 
  **Division and Modulo Operator**
   - Let **a** be an interger and **d** a positive interger. Then where is a unique **Q** and **r**, with 0 ≤ r < d that a = dQ + r.<br>
    Q = a div d<br>
    r = a mod d<br>
   -

