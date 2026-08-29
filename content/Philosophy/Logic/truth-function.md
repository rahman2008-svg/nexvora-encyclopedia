---
id: truth-function
title: সত্য-ফাংশন বা Truth Function
tags:
  - দর্শন
  - যুক্তিবিদ্যা
  - সত্য-ফাংশন
  - Truth Function
  - সত্যমূল্য
  - বচন
  - প্রস্তাব
  - প্রস্তাবনামূলক যুক্তিবিদ্যা
  - Formal Logic
  - Propositional Logic
  - Boolean Logic
  - Truth Table
  - Logical Connective
  - গণিত
  - কম্পিউটার বিজ্ঞান
related:
  - logic
  - truth
  - truth-value
  - proposition
  - argument
  - premise
  - conclusion
  - inference
  - validity
  - soundness
  - logical-consequence
  - logical-form
  - logical-structure
  - propositional-logic
  - boolean-logic
  - truth-table
---

# সত্য-ফাংশন বা Truth Function

## সংক্ষিপ্ত পরিচিতি

সত্য-ফাংশন (Truth Function) হলো এমন একটি যৌক্তিক ফাংশন যার ইনপুট হিসেবে এক বা একাধিক বচন বা Proposition-এর সত্যমূল্য গ্রহণ করা হয় এবং নির্দিষ্ট নিয়ম অনুযায়ী একটি সত্যমূল্য আউটপুট হিসেবে পাওয়া যায়।

Classical Propositional Logic-এ সাধারণত দুটি Truth Value ব্যবহৃত হয়:

- True — সত্য
- False — মিথ্যা

Truth Function-এর মাধ্যমে একটি বা একাধিক Proposition-এর Truth Value ব্যবহার করে নতুন Logical Expression-এর Truth Value নির্ধারণ করা যায়।

উদাহরণ:

P = «আজ বৃষ্টি হচ্ছে।»

Q = «রাস্তা ভেজা।»

তাহলে:

P ∧ Q

একটি Truth-Functional Expression। P এবং Q-এর সত্যমূল্যের ওপর নির্ভর করে P ∧ Q-এর সত্যমূল্য নির্ধারিত হবে।

---

## সূচিপত্র

1. সত্য-ফাংশনের ধারণা
2. Truth Function-এর সংজ্ঞা
3. Truth Value ও Truth Function
4. Truth-Functional Expression
5. Unary Truth Function
6. Binary Truth Function
7. Negation
8. Conjunction
9. Disjunction
10. Conditional
11. Biconditional
12. Truth Table
13. Logical Connective
14. Atomic Proposition
15. Compound Proposition
16. Tautology
17. Contradiction
18. Contingency
19. Logical Equivalence
20. De Morgan-এর সূত্র
21. Material Implication
22. Exclusive OR
23. NAND
24. NOR
25. Functionally Complete Connective
26. Propositional Logic
27. Boolean Algebra
28. Boolean Function
29. Digital Logic
30. Computer Science
31. Programming
32. Database
33. Artificial Intelligence
34. Truth Function ও Inference
35. Truth Function ও Argument
36. Truth Function ও Validity
37. Truth Function ও Logical Consequence
38. Truth Function বিশ্লেষণের ধাপ
39. দৈনন্দিন জীবনে Truth Function
40. Truth Function-এর সীমাবদ্ধতা
41. গুরুত্বপূর্ণ পরিভাষা
42. সম্পূর্ণ উদাহরণ
43. উপসংহার
44. সম্পর্কিত বিষয়
45. তথ্যসূত্র

---

## সত্য-ফাংশনের ধারণা

Truth Function-এর মূল ধারণা হলো কোনো Logical Expression-এর সত্যমূল্য তার উপাদানগুলোর সত্যমূল্য থেকে নির্ধারণ করা।

ধরা যাক P এবং Q দুটি Proposition।

P এবং Q-এর Truth Value জানা থাকলে কোনো Truth-Functional Operator ব্যবহার করে P ও Q থেকে তৈরি Expression-এর Truth Value নির্ধারণ করা যায়।

উদাহরণ:

P = True

Q = True

তাহলে:

P ∧ Q = True

আবার:

P = True

Q = False

হলে:

P ∧ Q = False।

---

## Truth Function-এর সংজ্ঞা

Truth Function হলো এমন একটি Formal Function যার Input হিসেবে Truth Value ব্যবহৃত হয় এবং Output হিসেবেও একটি Truth Value পাওয়া যায়।

Classical Two-Valued Logic-এ Truth Function সাধারণভাবে:

f : {T, F}ⁿ → {T, F}

আকারে প্রকাশ করা যায়।

এখানে:

- f = Truth Function
- T = True
- F = False
- n = Input-এর সংখ্যা

---

## Truth Value ও Truth Function

Truth Value এবং Truth Function এক জিনিস নয়।

Truth Value হলো কোনো Proposition সত্য না মিথ্যা তার মান।

Truth Function হলো সেই Truth Value-এর ওপর কাজ করে নতুন Truth Value নির্ধারণ করার একটি Formal Rule।

উদাহরণ:

P = True

¬P = False

এখানে:

- P-এর Truth Value = True
- ¬ = Negation Operator
- ¬P-এর Truth Value = False

---

## Truth-Functional Expression

যে Logical Expression-এর Truth Value তার উপাদান Proposition-এর Truth Value দ্বারা সম্পূর্ণভাবে নির্ধারিত হয়, তাকে Truth-Functional Expression বলা হয়।

উদাহরণ:

- ¬P
- P ∧ Q
- P ∨ Q
- P → Q
- P ↔ Q

Classical Propositional Logic-এ এগুলো Truth-Functional Expression হিসেবে ব্যবহৃত হয়।

---

## Unary Truth Function

Unary Truth Function একটি মাত্র Input গ্রহণ করে।

Classical Two-Valued Logic-এ একটি Truth Value-এর ওপর মোট চারটি সম্ভাব্য Unary Truth Function গাণিতিকভাবে সংজ্ঞায়িত করা যায়। তবে সবচেয়ে গুরুত্বপূর্ণ এবং প্রচলিত Unary Logical Operator হলো Negation।

প্রতীক:

¬P

Truth Table:

| P | ¬P |
|---|---|
| True | False |
| False | True |

---

## Binary Truth Function

Binary Truth Function দুটি Input গ্রহণ করে।

দুটি Input-এর সম্ভাব্য Truth Assignment হলো:

1. True, True
2. True, False
3. False, True
4. False, False

প্রতিটি অবস্থায় Output True অথবা False হতে পারে।

তাই Classical Two-Valued Logic-এ দুটি Input-এর জন্য মোট 16টি সম্ভাব্য Binary Truth Function রয়েছে।

এর মধ্যে বহুল ব্যবহৃত কয়েকটি হলো:

- AND
- OR
- Conditional
- Biconditional
- XOR
- NAND
- NOR

---

## Negation

Negation কোনো Proposition-এর Truth Value উল্টে দেয়।

প্রতীক:

¬P

Truth Table:

| P | ¬P |
|---|---|
| True | False |
| False | True |

উদাহরণ:

P = «আজ বৃষ্টি হচ্ছে।»

তাহলে:

¬P = «আজ বৃষ্টি হচ্ছে না।»

---

## Conjunction

Conjunction সাধারণত AND দ্বারা প্রকাশ করা হয়।

প্রতীক:

P ∧ Q

Truth Table:

| P | Q | P ∧ Q |
|---|---|---|
| True | True | True |
| True | False | False |
| False | True | False |
| False | False | False |

Conjunction তখনই True হয় যখন P এবং Q উভয়ই True।

---

## Disjunction

Disjunction সাধারণত OR দ্বারা প্রকাশ করা হয়।

প্রতীক:

P ∨ Q

Classical Inclusive OR-এর Truth Table:

| P | Q | P ∨ Q |
|---|---|---|
| True | True | True |
| True | False | True |
| False | True | True |
| False | False | False |

অর্থাৎ অন্তত একটি Proposition True হলে P ∨ Q True।

---

## Conditional

Conditional-এর প্রতীক:

P → Q

এটি সাধারণত «যদি P হয়, তবে Q» ধরনের Logical Form প্রকাশ করে।

Truth Table:

| P | Q | P → Q |
|---|---|---|
| True | True | True |
| True | False | False |
| False | True | True |
| False | False | True |

Classical Material Implication-এ কেবল P True এবং Q False হলে P → Q False হয়।

---

## Biconditional

Biconditional-এর প্রতীক:

P ↔ Q

এটি «তখনই এবং কেবল তখনই» ধরনের Logical Relationship প্রকাশ করে।

Truth Table:

| P | Q | P ↔ Q |
|---|---|---|
| True | True | True |
| True | False | False |
| False | True | False |
| False | False | True |

P এবং Q-এর Truth Value একই হলে Biconditional True হয়।

---

## Truth Table

Truth Table হলো Truth Function বিশ্লেষণের একটি গুরুত্বপূর্ণ পদ্ধতি।

এতে সম্ভাব্য সব Input Truth Assignment এবং প্রতিটি অবস্থায় Output Truth Value দেখানো হয়।

উদাহরণ:

P ∧ Q

| P | Q | P ∧ Q |
|---|---|---|
| T | T | T |
| T | F | F |
| F | T | F |
| F | F | F |

---

## Logical Connective

Logical Connective ব্যবহার করে Proposition-গুলোকে যুক্ত করে Compound Expression তৈরি করা হয়।

প্রধান Logical Connective:

| নাম | প্রতীক | সাধারণ অর্থ |
|---|---|---|
| Negation | ¬ | নয় |
| Conjunction | ∧ | এবং |
| Disjunction | ∨ | অথবা |
| Conditional | → | যদি...তবে |
| Biconditional | ↔ | তখনই এবং কেবল তখনই |

---

## Atomic Proposition

Atomic Proposition হলো এমন একটি Proposition যা সংশ্লিষ্ট Logical System-এ আরও ছোট Proposition-এ বিভক্ত করা হয় না।

উদাহরণ:

P = «আজ সোমবার।»

এখানে P একটি Atomic Proposition হিসেবে ব্যবহৃত হতে পারে।

---

## Compound Proposition

একাধিক Proposition-কে Logical Connective-এর মাধ্যমে যুক্ত করলে Compound Proposition তৈরি হয়।

উদাহরণ:

P ∧ Q

P ∨ Q

P → Q

(P ∧ Q) → R

---

## Tautology

Tautology হলো এমন Logical Expression যা সব সম্ভাব্য Truth Assignment-এর ক্ষেত্রে True হয়।

উদাহরণ:

P ∨ ¬P

Classical Propositional Logic-এ এটি একটি Tautology।

Truth Table:

| P | ¬P | P ∨ ¬P |
|---|---|---|
| True | False | True |
| False | True | True |

---

## Contradiction

Contradiction হলো এমন Logical Expression যা সব সম্ভাব্য Truth Assignment-এর ক্ষেত্রে False হয়।

উদাহরণ:

P ∧ ¬P

Truth Table:

| P | ¬P | P ∧ ¬P |
|---|---|---|
| True | False | False |
| False | True | False |

---

## Contingency

Contingency হলো এমন Logical Expression যা কিছু Truth Assignment-এর ক্ষেত্রে True এবং অন্য কিছু Truth Assignment-এর ক্ষেত্রে False হয়।

উদাহরণ:

P ∧ Q

এটি Tautology নয় এবং Contradiction-ও নয়।

---

## Logical Equivalence

দুটি Logical Expression-এর Truth Value যদি প্রতিটি সম্ভাব্য Truth Assignment-এর ক্ষেত্রে একই হয়, তাহলে তাদের Logical Equivalence বলা হয়।

প্রতীক:

≡

উদাহরণ:

P → Q ≡ ¬P ∨ Q

Classical Propositional Logic-এ এই দুটি Expression Logically Equivalent।

---

## De Morgan-এর সূত্র

Truth Function-এর গুরুত্বপূর্ণ Logical Equivalence-এর মধ্যে De Morgan-এর দুটি সূত্র রয়েছে।

প্রথমটি:

¬(P ∧ Q) ≡ ¬P ∨ ¬Q

দ্বিতীয়টি:

¬(P ∨ Q) ≡ ¬P ∧ ¬Q

Truth Table ব্যবহার করে এই Equivalence যাচাই করা যায়।

---

## Material Implication

Classical Propositional Logic-এ:

P → Q

Material Implication হিসেবে বিশ্লেষণ করা যায়।

এটি:

¬P ∨ Q

এর সঙ্গে Logically Equivalent।

অর্থাৎ:

P → Q ≡ ¬P ∨ Q

---

## Exclusive OR

Exclusive OR বা XOR এমন একটি Binary Truth Function যেখানে ঠিক একটি Input True হলে Output True হয়।

প্রতীক:

P ⊕ Q

Truth Table:

| P | Q | P ⊕ Q |
|---|---|---|
| True | True | False |
| True | False | True |
| False | True | True |
| False | False | False |

---

## NAND

NAND হলো AND-এর Negation।

প্রতীক:

P ↑ Q

অথবা:

¬(P ∧ Q)

Truth Table:

| P | Q | P NAND Q |
|---|---|---|
| True | True | False |
| True | False | True |
| False | True | True |
| False | False | True |

NAND একটি Functionally Complete Operator।

---

## NOR

NOR হলো OR-এর Negation।

প্রতীক:

P ↓ Q

অথবা:

¬(P ∨ Q)

Truth Table:

| P | Q | P NOR Q |
|---|---|---|
| True | True | False |
| True | False | False |
| False | True | False |
| False | False | True |

NOR-ও Functionally Complete।

---

## Functionally Complete Connective

কিছু Logical Operator ব্যবহার করে অন্যান্য Logical Operator প্রকাশ করা যায়।

NAND এবং NOR প্রত্যেকটি এককভাবে Functionally Complete।

অর্থাৎ শুধুমাত্র NAND অথবা শুধুমাত্র NOR ব্যবহার করেও বিভিন্ন Boolean ও Propositional Logical Operation প্রকাশ করা সম্ভব।

---

## Propositional Logic

Propositional Logic হলো Formal Logic-এর একটি গুরুত্বপূর্ণ শাখা যেখানে সম্পূর্ণ Proposition-কে Logical Variable হিসেবে ব্যবহার করা হয়।

সাধারণত:

- P
- Q
- R
- S

ইত্যাদি Symbol ব্যবহার করা হয়।

উদাহরণ:

(P ∧ Q) → R

এখানে P, Q এবং R হলো Proposition Variable।

---

## Boolean Algebra

Boolean Algebra-তে সাধারণত:

- 1 = True
- 0 = False

ধরা হয়।

প্রধান Operation:

- AND
- OR
- NOT

Truth Function এবং Boolean Algebra-এর মধ্যে ঘনিষ্ঠ সম্পর্ক রয়েছে।

---

## Boolean Function

Boolean Function এমন একটি Function যা Boolean Input গ্রহণ করে এবং Boolean Output প্রদান করে।

উদাহরণ:

f(P, Q) = P ∧ Q

যদি:

P, Q ∈ {0, 1}

তাহলে:

f(P, Q) ∈ {0, 1}

---

## Digital Logic

Digital Electronics-এ Truth Function-এর ধারণা Logic Gate-এর মাধ্যমে বাস্তবায়িত হয়।

প্রধান Logic Gate:

- AND Gate
- OR Gate
- NOT Gate
- NAND Gate
- NOR Gate
- XOR Gate
- XNOR Gate

প্রতিটি Gate নির্দিষ্ট Logical Function বাস্তবায়ন করে।

---

## Computer Science

Computer Science-এর বিভিন্ন ক্ষেত্রে Truth Function এবং Boolean Logic গুরুত্বপূর্ণ।

ব্যবহার ক্ষেত্র:

- Boolean Expression
- Algorithm
- Conditional Logic
- Digital Circuit
- Database Query
- Formal Verification
- Computer Hardware
- Programming Language
- Automated Reasoning

---

## Programming

Programming-এ Boolean Expression-এর মাধ্যমে Condition তৈরি করা হয়।

উদাহরণ:

```text
age >= 18
এটি True অথবা False হতে পারে।
আর:
age >= 18 AND has_permission
এখানে দুটি Boolean Condition AND দ্বারা যুক্ত হয়েছে।
Database
Database Query-তে Logical Condition ব্যবহার করা হয়।
উদাহরণ:
age > 18 AND country = "Bangladesh"
এখানে দুটি Condition:
age > 18
country = "Bangladesh"
AND-এর মাধ্যমে যুক্ত হয়েছে।
Artificial Intelligence
Symbolic AI এবং Rule-Based System-এ Truth-Functional Logic ব্যবহার করা যেতে পারে।
উদাহরণ:
P = «ব্যবহারকারী যাচাইকৃত।»
Q = «ব্যবহারকারী সিস্টেমে প্রবেশ করতে পারবে।»
Rule:
P → Q
এই Rule-এর মাধ্যমে P ও Q-এর মধ্যে একটি Logical Relationship প্রকাশ করা হয়।
তবে আধুনিক AI-এর সব পদ্ধতি Classical Propositional Logic বা Truth Function-এর ওপর নির্ভরশীল নয়। Machine Learning এবং Probabilistic Methods-ও আধুনিক AI-এর গুরুত্বপূর্ণ অংশ।
Truth Function ও Inference
Truth Function এবং Inference একই ধারণা নয়।
Truth Function কোনো Expression-এর Truth Value নির্ধারণ করে।
Inference হলো Premise থেকে Conclusion-এ যৌক্তিকভাবে পৌঁছানোর প্রক্রিয়া।
উদাহরণ:
P → Q
P
∴ Q
এটি একটি Inference Pattern।
Truth Function ও Argument
একটি Logical Argument-এর Premise এবং Conclusion Proposition হতে পারে।
Truth Table ব্যবহার করে বিভিন্ন Truth Assignment পরীক্ষা করে Argument-এর Validity বিশ্লেষণ করা যায়।
উদাহরণ:
P → Q
P
∴ Q
এখানে Premise:
P → Q
P
Conclusion:
Q
Truth Function ও Validity
Propositional Argument-এর Validity Truth Table ব্যবহার করে পরীক্ষা করা যায়।
একটি Argument Invalid হওয়ার জন্য এমন একটি Truth Assignment থাকতে হবে যেখানে:
সব Premise True
Conclusion False
যদি এমন কোনো Truth Assignment না থাকে, তাহলে Argument Valid।
Truth Function ও Logical Consequence
Logical Consequence-এর ক্ষেত্রে পরীক্ষা করা হয় Premise-গুলো True হলে Conclusion False হতে পারে কি না।
যদি Premise-গুলো True থাকা অবস্থায় Conclusion False হওয়া অসম্ভব হয়, তাহলে Conclusion Premise-এর Logical Consequence।
প্রতীক:
Γ ⊨ φ
এখানে:
Γ = Premise-এর সেট
φ = Conclusion
Truth Function বিশ্লেষণের ধাপ
কোনো Truth-Functional Expression বিশ্লেষণ করার সময়:
Atomic Proposition শনাক্ত করতে হবে।
প্রতিটি Logical Variable নির্ধারণ করতে হবে।
Logical Connective শনাক্ত করতে হবে।
Operator-এর Scope নির্ধারণ করতে হবে।
সম্ভাব্য Truth Assignment তৈরি করতে হবে।
প্রতিটি Sub-expression-এর Truth Value নির্ধারণ করতে হবে।
Final Expression-এর Truth Value নির্ধারণ করতে হবে।
প্রয়োজন হলে Truth Table তৈরি করতে হবে।
Expression Tautology, Contradiction অথবা Contingency কি না পরীক্ষা করতে হবে।
দৈনন্দিন জীবনে Truth Function
দৈনন্দিন সিদ্ধান্ত গ্রহণেও Boolean বা Truth-Functional চিন্তার কাঠামো দেখা যায়।
উদাহরণ:
P = «আজ স্কুল খোলা।»
Q = «আজ পরীক্ষা আছে।»
তাহলে:
P ∧ Q
এর অর্থ:
«আজ স্কুল খোলা এবং আজ পরীক্ষা আছে।»
আবার:
¬P
এর অর্থ:
«আজ স্কুল খোলা নয়।»
এভাবে Logical Condition ব্যবহার করে সিদ্ধান্তের কাঠামো স্পষ্ট করা যায়।
Truth Function-এর সীমাবদ্ধতা
Truth Function অত্যন্ত গুরুত্বপূর্ণ হলেও এর কিছু সীমাবদ্ধতা রয়েছে।
১. Natural Language-এর জটিলতা
প্রাকৃতিক ভাষায় Context, Ambiguity এবং অর্থের সূক্ষ্মতা থাকে। সব ক্ষেত্রে এগুলোকে সরাসরি Classical Truth Function দিয়ে প্রকাশ করা যায় না।
২. Modal Concepts
Necessity এবং Possibility-এর মতো ধারণার জন্য Modal Logic প্রয়োজন হতে পারে।
৩. Temporal Concepts
সময়-নির্ভর বক্তব্য বিশ্লেষণের জন্য Temporal Logic-এর মতো Formal System ব্যবহার করা যেতে পারে।
৪. Probability
অনিশ্চয়তা এবং Probability Classical Two-Valued Logic-এর সরাসরি বিষয় নয়।
৫. Degrees of Truth
কোনো বক্তব্য আংশিক সত্য বা বিভিন্ন মাত্রায় সত্য—এ ধরনের ধারণার জন্য Fuzzy Logic-এর মতো পদ্ধতি ব্যবহার করা যেতে পারে।
গুরুত্বপূর্ণ পরিভাষা
English
বাংলা
Truth Function
সত্য-ফাংশন
Truth Value
সত্যমূল্য
True
সত্য
False
মিথ্যা
Truth-Functional Expression
সত্য-ফাংশনভিত্তিক অভিব্যক্তি
Logical Connective
যৌক্তিক সংযোজক
Negation
নঞর্থকরণ
Conjunction
সংযোজন
Disjunction
বিকল্প
Conditional
শর্তযুক্ত বচন
Biconditional
দ্বিশর্তযুক্ত বচন
Exclusive OR
একচেটিয়া অথবা
NAND
ন্যান্ড
NOR
নর
Boolean Function
বুলিয়ান ফাংশন
Boolean Algebra
বুলিয়ান বীজগণিত
Truth Table
সত্যক সারণি
Tautology
অনিবার্য সত্য
Contradiction
স্ববিরোধ
Contingency
আপতিক
Logical Equivalence
যৌক্তিক সমতুল্যতা
Propositional Logic
প্রস্তাবনামূলক যুক্তিবিদ্যা
Logic Gate
লজিক গেট
Input
ইনপুট
Output
আউটপুট
Valuation
সত্যমূল্য নির্ধারণ
Functionally Complete
কার্যগতভাবে সম্পূর্ণ
সম্পূর্ণ উদাহরণ
ধরা যাক:
P = «বৃষ্টি হচ্ছে।»
Q = «রাস্তা ভেজা।»
Negation
¬P
যদি:
P = True
তাহলে:
¬P = False
Conjunction
P ∧ Q
যদি:
P = True
এবং:
Q = True
তাহলে:
P ∧ Q = True
Disjunction
P ∨ Q
যদি:
P = False
এবং:
Q = True
তাহলে:
P ∨ Q = True
Conditional
P → Q
যদি:
P = True
এবং:
Q = False
তাহলে:
P → Q = False
Biconditional
P ↔ Q
যদি:
P এবং Q উভয়ই True হয়, তাহলে:
P ↔ Q = True
Truth Table বিশ্লেষণ
Expression:
(P ∧ Q) → Q
Truth Table:
P
Q
P ∧ Q
(P ∧ Q) → Q
True
True
True
True
True
False
False
True
False
True
False
True
False
False
False
True
শেষ Column-এর প্রতিটি Value True।
অতএব:
(P ∧ Q) → Q
একটি Tautology।
Truth Function ও Truth Value-এর পার্থক্য
Truth Value হলো:
True
False
Truth Function হলো:
এক বা একাধিক Truth Value নিয়ে একটি নতুন Truth Value নির্ধারণ করার Formal Rule।
উদাহরণ:
P = True
¬P = False
এখানে:
True = Input Truth Value
¬ = Logical Operator
False = Output Truth Value
Truth Function-এর গুরুত্ব
Truth Function যুক্তিবিদ্যার একটি মৌলিক ধারণা। এর মাধ্যমে:
Proposition বিশ্লেষণ করা যায়।
Compound Proposition-এর Truth Value নির্ধারণ করা যায়।
Truth Table তৈরি করা যায়।
Tautology শনাক্ত করা যায়।
Contradiction শনাক্ত করা যায়।
Contingency শনাক্ত করা যায়।
Logical Equivalence পরীক্ষা করা যায়।
Propositional Argument-এর Validity বিশ্লেষণ করা যায়।
Boolean Expression তৈরি করা যায়।
Digital Logic বোঝা যায়।
Programming Condition বিশ্লেষণ করা যায়।
Database Query-এর Logical Condition বোঝা যায়।
উপসংহার
সত্য-ফাংশন (Truth Function) যুক্তিবিদ্যার একটি মৌলিক এবং গুরুত্বপূর্ণ ধারণা। এটি এক বা একাধিক Proposition-এর Truth Value গ্রহণ করে নির্দিষ্ট Logical Rule অনুযায়ী একটি নতুন Truth Value প্রদান করে।
Classical Two-Valued Logic-এ Truth Value সাধারণত True এবং False। Negation, Conjunction, Disjunction, Conditional এবং Biconditional-এর মতো Logical Operator Truth-Functional Expression তৈরিতে গুরুত্বপূর্ণ ভূমিকা পালন করে।
Truth Table ব্যবহার করে একটি Truth Function-এর প্রতিটি সম্ভাব্য Input এবং Output বিশ্লেষণ করা যায়। এর মাধ্যমে Tautology, Contradiction, Contingency এবং Logical Equivalence নির্ধারণ করা সম্ভব।
Truth Function শুধু Philosophy বা Logic-এর মধ্যে সীমাবদ্ধ নয়। Boolean Algebra, Digital Logic, Computer Science, Programming, Database, Algorithm Design, Formal Verification এবং Symbolic Artificial Intelligence-এর বিভিন্ন ক্ষেত্রে এর ব্যবহার রয়েছে।
Truth Function এবং Inference আলাদা ধারণা। Truth Function কোনো Logical Expression-এর Truth Value নির্ধারণ করে, আর Inference Premise থেকে Conclusion-এর যৌক্তিক সম্পর্ক নিয়ে কাজ করে। তবে Truth Table এবং Truth-Functional Semantics ব্যবহার করে Propositional Argument-এর Validity ও Logical Consequence বিশ্লেষণ করা যায়।
যুক্তিবিদ্যা শেখার ক্ষেত্রে Truth Function বোঝা অত্যন্ত গুরুত্বপূর্ণ। এটি ভালোভাবে বোঝা গেলে Truth Table, Logical Connective, Tautology, Contradiction, Logical Equivalence এবং Propositional Validity-এর মতো পরবর্তী বিষয়গুলো আরও সহজে বোঝা যায়।
সম্পর্কিত বিষয়
যুক্তিবিদ্যা (article:logic)
সত্য (article:truth)
সত্যমূল্য (article:truth-value)
বচন বা প্রস্তাব (article:proposition)
যুক্তি বা Argument (article:argument)
Premise বা যুক্তির ভিত্তি (article:premise)
উপসংহার (article:conclusion)
অনুমান বা Inference (article:inference)
Validity (article:validity)
Soundness (article:soundness)
অবৈধ যুক্তি (article:invalid-argument)
যৌক্তিক পরিণতি (article:logical-consequence)
যৌক্তিক রূপ (article:logical-form)
যৌক্তিক কাঠামো (article:logical-structure)
প্রস্তাবনামূলক যুক্তিবিদ্যা (article:propositional-logic)
সত্যক সারণি (article:truth-table)
বুলিয়ান যুক্তি (article:boolean-logic)
যৌক্তিক সংযোজক (article:logical-connective)
তথ্যসূত্র
Irving M. Copi, Carl Cohen & Kenneth McMahon — Introduction to Logic
Patrick J. Hurley — A Concise Introduction to Logic
Elliott Mendelson — Introduction to Mathematical Logic
Herbert B. Enderton — A Mathematical Introduction to Logic
George Boole — An Investigation of the Laws of Thought
Stanford Encyclopedia of Philosophy — Logic
Internet Encyclopedia of Philosophy — Logic
