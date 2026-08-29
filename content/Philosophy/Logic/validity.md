---
id: validity
title: বৈধতা বা Validity
tags:
  - দর্শন
  - যুক্তিবিদ্যা
  - বৈধতা
  - Validity
  - যুক্তি
  - আনুষ্ঠানিক যুক্তিবিদ্যা
  - অবরোহী যুক্তি
  - Deductive Reasoning
  - Argument
  - Logical Reasoning
related:
  - logic
  - proposition
  - argument
  - premise
  - conclusion
  - inference
  - deductive-reasoning
  - syllogism
  - logical-fallacy
  - soundness
  - truth
---

# বৈধতা বা Validity

## সংক্ষিপ্ত পরিচিতি

Validity বা বৈধতা হলো যুক্তিবিদ্যার একটি মৌলিক ধারণা, যা কোনো Deductive Argument-এর যৌক্তিক কাঠামো সঠিক কি না তা নির্ধারণ করতে ব্যবহৃত হয়।

একটি Deductive Argument Valid হলে এমন কোনো যৌক্তিক পরিস্থিতি থাকে না যেখানে Argument-এর সব Premise সত্য কিন্তু Conclusion মিথ্যা।

সহজভাবে বলা যায়:

> যদি Premise-গুলো সত্য ধরা হয়, তাহলে Logical Structure অনুযায়ী Conclusion-কে মিথ্যা হওয়ার সুযোগ না দেওয়াই Validity-এর মূল ধারণা।

উদাহরণ:

সকল মানুষ মরণশীল।
সক্রেটিস একজন মানুষ।
অতএব, সক্রেটিস মরণশীল।

এই Argument Valid, কারণ Premise দুটি সত্য হলে Conclusion মিথ্যা হতে পারে না।

তবে মনে রাখতে হবে, Validity এবং Truth একই বিষয় নয়। একটি Argument Valid হতে পারে, যদিও তার কোনো Premise বাস্তবে মিথ্যা।

---

## সূচিপত্র

1. Validity-এর ধারণা
2. Validity-এর সংজ্ঞা
3. Validity-এর প্রধান বৈশিষ্ট্য
4. Validity ও Truth
5. Validity ও Argument
6. Validity ও Premise
7. Validity ও Conclusion
8. Validity ও Inference
9. Valid Deductive Argument
10. Invalid Argument
11. Validity-এর Formal Definition
12. Counterexample বা Countermodel
13. Logical Form
14. Argument Form
15. Validity-এর উদাহরণ
16. Invalidity-এর উদাহরণ
17. Modus Ponens ও Validity
18. Modus Tollens ও Validity
19. Hypothetical Syllogism
20. Disjunctive Syllogism
21. Syllogism ও Validity
22. Categorical Logic ও Validity
23. Propositional Logic ও Validity
24. Predicate Logic ও Validity
25. Truth Table দিয়ে Validity পরীক্ষা
26. Semantic Validity
27. Syntactic Validity
28. Formal Proof
29. Soundness ও Validity
30. Validity বনাম Soundness
31. Validity বনাম Truth
32. Validity বনাম Strength
33. Deductive Validity
34. Inductive Argument ও Validity
35. Logical Fallacy ও Invalidity
36. Validity যাচাই করার পদ্ধতি
37. বাস্তব জীবনে Validity
38. Mathematics-এ Validity
39. Computer Science-এ Validity
40. Programming-এ Validity
41. Artificial Intelligence-এ Validity
42. Validity-এর সীমাবদ্ধতা
43. গুরুত্বপূর্ণ পরিভাষা
44. Valid ও Invalid Argument-এর তুলনা
45. একটি সম্পূর্ণ উদাহরণ
46. Validity-এর গুরুত্ব
47. উপসংহার
48. সম্পর্কিত বিষয়
49. তথ্যসূত্র

---

## Validity-এর ধারণা

Validity মূলত কোনো Argument-এর Logical Structure বা যৌক্তিক কাঠামোর বৈশিষ্ট্য।

একটি Argument-এর:

- Premise থাকতে পারে
- Conclusion থাকতে পারে
- Premise এবং Conclusion-এর মধ্যে Logical Relationship থাকতে পারে

Validity পরীক্ষা করে সেই Logical Relationship যথাযথ কি না।

উদাহরণ:

P → Q
P
∴ Q

এই Argument Form Valid।

কারণ P সত্য এবং P থেকে Q অনুসরণ করার Rule গ্রহণ করলে Q অবশ্যই অনুসরণ করে।

---

## Validity-এর সংজ্ঞা

Formal Logic-এ একটি Deductive Argument Valid তখনই যখন এমন কোনো সম্ভাব্য Interpretation বা পরিস্থিতি নেই যেখানে:

- সব Premise সত্য
- কিন্তু Conclusion মিথ্যা

অর্থাৎ:

Premises সত্য + Conclusion মিথ্যা

এমন কোনো Logical Model যদি না থাকে, তাহলে Argument Valid।

সংক্ষেপে:

> Validity হলো এমন একটি Logical Property যেখানে Premise-গুলোর সত্যতা Conclusion-এর মিথ্যাকে অসম্ভব করে দেয়।

---

## Validity-এর প্রধান বৈশিষ্ট্য

### ১. এটি মূলত Argument-এর বৈশিষ্ট্য

Validity সাধারণত একটি সম্পূর্ণ Deductive Argument-এর ক্ষেত্রে প্রযোজ্য।

### ২. Logical Structure গুরুত্বপূর্ণ

Argument-এর বিষয়বস্তুর চেয়ে তার Logical Form গুরুত্বপূর্ণ।

### ৩. Premise সত্য হওয়া Validity-এর শর্ত নয়

একটি Argument-এর Premise বাস্তবে মিথ্যা হলেও Argument Valid হতে পারে।

### ৪. Conclusion বাস্তবে সত্য হওয়া Validity-এর শর্ত নয়

একটি Valid Argument-এর Conclusion সত্য হতে পারে, কিন্তু সেটি Validity-এর সংজ্ঞার মূল শর্ত নয়।

### ৫. Counterexample দিয়ে Invalidity দেখানো যায়

যদি এমন একটি পরিস্থিতি দেখানো যায় যেখানে সব Premise সত্য কিন্তু Conclusion মিথ্যা, তাহলে Argument Invalid।

---

## Validity ও Truth

Truth এবং Validity দুটি আলাদা ধারণা।

Truth সাধারণত Proposition-এর বৈশিষ্ট্য।

Validity হলো Argument-এর বৈশিষ্ট্য।

উদাহরণ:

"ঢাকা বাংলাদেশের রাজধানী।"

এটি একটি Proposition এবং এর Truth Value রয়েছে।

অন্যদিকে:

সকল মানুষ মরণশীল।
সক্রেটিস মানুষ।
অতএব, সক্রেটিস মরণশীল।

এটি একটি Argument এবং এর Logical Validity বিশ্লেষণ করা যায়।

---

## Validity ও Argument

Validity মূলত Deductive Argument মূল্যায়নে ব্যবহৃত হয়।

একটি Argument:

Premise 1
Premise 2
...
Conclusion

এই কাঠামোতে থাকে।

যদি Premise-গুলো সত্য হলে Conclusion অবশ্যই অনুসরণ করে, তাহলে Argument Valid।

---

## Validity ও Premise

Validity নির্ধারণ করার সময় Premise-এর বিষয়বস্তু নয়, বরং Premise থেকে Conclusion Logicalভাবে অনুসরণ করে কি না তা দেখা হয়।

উদাহরণ:

সব বিড়াল উড়তে পারে।
টম একটি বিড়াল।
অতএব, টম উড়তে পারে।

বাস্তবে প্রথম Premise মিথ্যা।

কিন্তু Argument-এর Logical Form:

All A are B.
x is A.
Therefore x is B.

এই Form Valid।

তাই Argument-টি Valid হলেও Sound নয়।

---

## Validity ও Conclusion

একটি Valid Argument-এ যদি সব Premise সত্য হয়, তাহলে Conclusion মিথ্যা হতে পারে না।

তবে কোনো একটি Premise মিথ্যা হলে Conclusion সত্য বা মিথ্যা যেকোনোটি হতে পারে।

এ কারণে Validity এবং Truth আলাদা করে বিবেচনা করা হয়।

---

## Validity ও Inference

Inference হলো Premise থেকে Conclusion-এ পৌঁছানোর Reasoning Process।

Validity পরীক্ষা করে সেই Inference-এর Logical Structure যথাযথ কি না।

উদাহরণ:

P → Q
P
∴ Q

এখানে Modus Ponens-এর মাধ্যমে Q-তে পৌঁছানো হয়েছে।

এই Inference Valid।

---

## Valid Deductive Argument

একটি Valid Deductive Argument এমন একটি Argument যার Logical Structure এমন যে Premise-গুলো সত্য হলে Conclusion মিথ্যা হতে পারে না।

উদাহরণ:

সকল স্তন্যপায়ী প্রাণী শ্বাস নেয়।
তিমি একটি স্তন্যপায়ী প্রাণী।
অতএব, তিমি শ্বাস নেয়।

এটি Valid Argument Form অনুসরণ করে।

---

## Invalid Argument

একটি Deductive Argument Invalid যদি এমন অন্তত একটি Logical Possibility থাকে যেখানে:

- সব Premise সত্য
- Conclusion মিথ্যা

উদাহরণ:

যদি বৃষ্টি হয়, রাস্তা ভিজবে।
রাস্তা ভেজা।
অতএব, বৃষ্টি হয়েছে।

এটি Invalid।

কারণ রাস্তা অন্য কারণেও ভেজা হতে পারে।

Formal Form:

P → Q
Q
∴ P

এই Form Valid নয়।

এটি Affirming the Consequent-এর উদাহরণ।

---

## Validity-এর Formal Definition

ধরা যাক একটি Argument-এর Premise:

P₁, P₂, P₃, ..., Pₙ

এবং Conclusion:

C

Argument Valid হবে যদি:

P₁ ∧ P₂ ∧ P₃ ∧ ... ∧ Pₙ

সত্য হওয়ার সময়:

C

মিথ্যা হওয়ার কোনো সম্ভাব্য Interpretation না থাকে।

অন্যভাবে:

Premises ⊨ Conclusion

এখানে:

⊨

চিহ্নটি Semantic Entailment বোঝাতে ব্যবহৃত হয়।

---

## Counterexample বা Countermodel

কোনো Argument Invalid প্রমাণ করার একটি গুরুত্বপূর্ণ পদ্ধতি হলো Counterexample বা Countermodel দেখানো।

যদি এমন একটি পরিস্থিতি তৈরি করা যায় যেখানে:

- সব Premise সত্য
- Conclusion মিথ্যা

তাহলে Argument Invalid।

উদাহরণ:

সব কুকুর প্রাণী।
সব বিড়াল প্রাণী।
অতএব, সব কুকুর বিড়াল।

এখানে Premise দুটি সত্য হতে পারে।

কিন্তু Conclusion মিথ্যা হতে পারে।

তাই Argument Invalid।

---

## Logical Form

Validity বিশ্লেষণের জন্য Argument-এর Logical Form গুরুত্বপূর্ণ।

উদাহরণ:

সব A হলো B।
C হলো A।
অতএব, C হলো B।

এটি একটি Valid Form।

কিন্তু:

সব A হলো B।
C হলো B।
অতএব, C হলো A।

এই Form Valid নয়।

---

## Argument Form

একই Logical Form বিভিন্ন বিষয়বস্তুর Argument-এ ব্যবহার করা যায়।

উদাহরণ:

P → Q
P
∴ Q

এর বাস্তব উদাহরণ:

যদি বিদ্যুৎ থাকে, বাতি জ্বলবে।
বিদ্যুৎ আছে।
অতএব, বাতি জ্বলবে।

এখানে Logical Form:

P → Q
P
∴ Q

---

## Validity-এর উদাহরণ

### উদাহরণ ১

সকল মানুষ মরণশীল।
সক্রেটিস মানুষ।
অতএব, সক্রেটিস মরণশীল।

Valid।

### উদাহরণ ২

যদি P হয়, তাহলে Q।
P সত্য।
অতএব, Q।

Valid।

### উদাহরণ ৩

P → Q
Q → R
∴ P → R

Valid।

---

## Invalidity-এর উদাহরণ

### উদাহরণ ১

P → Q
Q
∴ P

Invalid।

### উদাহরণ ২

P → Q
¬P
∴ ¬Q

সাধারণভাবে Invalid।

এটি Denying the Antecedent-এর কাঠামো।

### উদাহরণ ৩

সব A হলো B।
C হলো B।
অতএব, C হলো A।

Invalid।

---

## Modus Ponens ও Validity

Modus Ponens একটি Valid Inference Rule।

Formal Form:

P → Q
P
∴ Q

উদাহরণ:

যদি পরীক্ষা হয়, শিক্ষার্থীরা প্রস্তুতি নেবে।
পরীক্ষা হচ্ছে।
অতএব, শিক্ষার্থীরা প্রস্তুতি নেবে।

Logical Structure অনুযায়ী এটি Valid Form।

---

## Modus Tollens ও Validity

Modus Tollens-ও একটি Valid Inference Rule।

Formal Form:

P → Q
¬Q
∴ ¬P

উদাহরণ:

যদি নির্দিষ্ট শর্ত পূরণ হয়, তাহলে সিস্টেম চালু হবে।
সিস্টেম চালু হয়নি।
অতএব, সেই নির্দিষ্ট শর্ত পূরণ হয়নি।

এখানে Logical Form Valid।

---

## Hypothetical Syllogism

Formal Form:

P → Q
Q → R
∴ P → R

এটি একটি Valid Inference Form।

উদাহরণ:

যদি P হয়, তাহলে Q।
যদি Q হয়, তাহলে R।
অতএব, যদি P হয়, তাহলে R।

---

## Disjunctive Syllogism

একটি প্রচলিত Valid Form:

P ∨ Q
¬P
∴ Q

উদাহরণ:

আজ বৃষ্টি হবে অথবা আকাশ পরিষ্কার থাকবে।
আজ বৃষ্টি হবে না।
অতএব, আকাশ পরিষ্কার থাকবে।

এখানে “অথবা” কোন অর্থে ব্যবহৃত হচ্ছে তা Formal Logic-এ গুরুত্বপূর্ণ।

---

## Syllogism ও Validity

Syllogism-এর Validity নির্ভর করে তার Logical Form-এর ওপর।

উদাহরণ:

সকল মানুষ মরণশীল।
সকল দার্শনিক মানুষ।
অতএব, সকল দার্শনিক মরণশীল।

এটি একটি Valid Categorical Syllogism।

---

## Categorical Logic ও Validity

Categorical Logic-এ Subject এবং Predicate-এর মধ্যে সম্পর্ক বিশ্লেষণ করা হয়।

যেমন:

All S are P.

No S are P.

Some S are P.

Some S are not P.

এ ধরনের Proposition-এর Logical Relationship ব্যবহার করে Syllogism-এর Validity পরীক্ষা করা যায়।

---

## Propositional Logic ও Validity

Propositional Logic-এ Proposition-কে Symbol দিয়ে প্রকাশ করা হয়।

যেমন:

P
Q
R

এবং Logical Connective:

- ¬
- ∧
- ∨
- →
- ↔

ব্যবহার করা হয়।

উদাহরণ:

P → Q
P
∴ Q

এটি Valid।

---

## Predicate Logic ও Validity

Predicate Logic-এ ব্যক্তি, বস্তু, বৈশিষ্ট্য এবং সম্পর্কের Logical Structure বিশ্লেষণ করা হয়।

উদাহরণ:

∀x (Human(x) → Mortal(x))
Human(Socrates)
∴ Mortal(Socrates)

এটি একটি Valid Deductive Inference।

---

## Truth Table দিয়ে Validity পরীক্ষা

Propositional Logic-এ Truth Table ব্যবহার করে Argument Validity পরীক্ষা করা যায়।

উদাহরণ:

P → Q
P
∴ Q

Truth Table তৈরি করলে দেখা যাবে এমন কোনো Row নেই যেখানে:

P → Q = True
P = True
Q = False

একসঙ্গে সত্য হয়।

তাই Argument Valid।

---

## Semantic Validity

Semantic Validity হলো এমন Validity যেখানে সব সম্ভাব্য Interpretation বা Model বিবেচনা করা হয়।

যদি কোনো Model-এ সব Premise সত্য এবং Conclusion মিথ্যা না হয়, তাহলে Argument Semantically Valid।

প্রতীক:

Γ ⊨ C

এখানে Γ হলো Premises-এর Set এবং C হলো Conclusion।

---

## Syntactic Validity

Syntactic বা Proof-Theoretic দৃষ্টিকোণে কোনো Conclusion নির্দিষ্ট Formal Rules ব্যবহার করে Premise থেকে প্রমাণ করা যায় কি না তা বিবেচনা করা হয়।

উদাহরণ:

P → Q
P
∴ Q

Formal Inference Rule ব্যবহার করে Q Derive করা যায়।

---

## Formal Proof

Formal Proof হলো নির্দিষ্ট Rules অনুসরণ করে Conclusion প্রতিষ্ঠা করার একটি পদ্ধতি।

উদাহরণ:

1. P → Q
2. P
3. Q — Modus Ponens

এখানে ৩ নম্বর ধাপটি প্রথম দুটি Premise থেকে Valid Rule ব্যবহার করে পাওয়া হয়েছে।

---

## Soundness ও Validity

Soundness এবং Validity এক নয়।

একটি Deductive Argument Sound হতে হলে সাধারণভাবে:

1. Argument Valid হতে হবে।
2. সব Premise সত্য হতে হবে।

অর্থাৎ:

Soundness = Validity + True Premises

তাই:

সব Sound Argument Valid।

কিন্তু:

সব Valid Argument Sound নয়।

---

## Validity বনাম Soundness

| বিষয় | Validity | Soundness |
|---|---|---|
| Logical Form | গুরুত্বপূর্ণ | গুরুত্বপূর্ণ |
| Premise সত্য হওয়া | প্রয়োজনীয় নয় | প্রয়োজনীয় |
| Conclusion | Premise সত্য হলে মিথ্যা হতে পারে না | সত্য হতে বাধ্য |
| প্রয়োগ | Deductive Logic | বাস্তবভাবে প্রতিষ্ঠিত Deductive Argument |

---

## Validity বনাম Truth

| বিষয় | Truth | Validity |
|---|---|---|
| প্রযোজ্য | Proposition | Argument |
| প্রশ্ন | বক্তব্যটি সত্য কি? | যুক্তির কাঠামো সঠিক কি? |
| Truth Value | থাকে | থাকে না |
| প্রধান বিষয় | Statement | Logical Relationship |

---

## Validity বনাম Strength

Deductive Argument সাধারণত Valid বা Invalid হিসেবে মূল্যায়ন করা হয়।

Inductive Argument-এর ক্ষেত্রে সাধারণত:

- Strong
- Weak

শব্দ ব্যবহার করা হয়।

Inductive Conclusion সাধারণত Premise থেকে Logical Necessity হিসেবে অনুসরণ করে না।

তাই Inductive Reasoning মূল্যায়নে Strength এবং Probability বেশি গুরুত্বপূর্ণ।

---

## Deductive Validity

Deductive Validity-এর মূল বিষয় হলো Logical Necessity।

যদি Premise-গুলো সত্য হয় এবং Argument Valid হয়, তাহলে Conclusion মিথ্যা হওয়া সম্ভব নয়।

এটাই Deductive Validity-এর কেন্দ্রীয় ধারণা।

---

## Inductive Argument ও Validity

“Validity” শব্দটি সাধারণত Deductive Argument-এর জন্য ব্যবহৃত হয়।

Inductive Argument-এ সাধারণত:

- Strength
- Weakness
- Probability
- Cogency

ইত্যাদি ধারণা বেশি ব্যবহৃত হয়।

---

## Logical Fallacy ও Invalidity

Logical Fallacy হলো এমন Reasoning Pattern যা যুক্তিগতভাবে ত্রুটিপূর্ণ হতে পারে।

কিছু Fallacy সরাসরি Invalid Deductive Form তৈরি করে।

উদাহরণ:

P → Q
Q
∴ P

এটি Affirming the Consequent।

আর:

P → Q
¬P
∴ ¬Q

এটি Denying the Antecedent।

এগুলো Valid Deductive Forms নয়।

---

## Validity যাচাই করার পদ্ধতি

কোনো Deductive Argument Valid কি না পরীক্ষা করতে:

### ধাপ ১ — Premise শনাক্ত করুন

Argument-এর সব Premise আলাদা করুন।

### ধাপ ২ — Conclusion শনাক্ত করুন

কোন বক্তব্য প্রতিষ্ঠা করার চেষ্টা করা হচ্ছে তা নির্ধারণ করুন।

### ধাপ ৩ — Logical Form বের করুন

Argument-কে Symbol ব্যবহার করে প্রকাশ করুন।

### ধাপ ৪ — Inference Rule পরীক্ষা করুন

Modus Ponens, Modus Tollens বা অন্য কোনো Valid Rule প্রয়োগ হয়েছে কি না দেখুন।

### ধাপ ৫ — Counterexample খুঁজুন

এমন পরিস্থিতি সম্ভব কি না দেখুন যেখানে:

সব Premise সত্য

কিন্তু:

Conclusion মিথ্যা।

### ধাপ ৬ — Truth Table ব্যবহার করুন

Propositional Logic হলে Truth Table দিয়ে পরীক্ষা করুন।

### ধাপ ৭ — Formal Proof তৈরি করুন

প্রয়োজনে Natural Deduction বা অন্য Proof System ব্যবহার করুন।

---

## বাস্তব জীবনে Validity

দৈনন্দিন জীবনে মানুষ বিভিন্ন Argument তৈরি করে।

উদাহরণ:

সব স্কুলের শিক্ষার্থী পরিচয়পত্র বহন করে।
রহিম এই স্কুলের শিক্ষার্থী।
অতএব, রহিম পরিচয়পত্র বহন করে।

এটি Valid হতে পারে যদি প্রথম Premise এবং দ্বিতীয় Premise-এর অর্থ যথাযথভাবে নির্ধারিত থাকে।

তবে বাস্তব জীবনে Premise সত্য কি না সেটিও যাচাই করা জরুরি।

---

## Mathematics-এ Validity

Mathematical Proof-এর ক্ষেত্রে Valid Logical Inference অত্যন্ত গুরুত্বপূর্ণ।

একটি Theorem প্রমাণ করতে:

- Definition
- Axiom
- Lemma
- পূর্ববর্তী Theorem
- Inference Rule

ব্যবহার করা হয়।

প্রতিটি ধাপের Logical Validity গুরুত্বপূর্ণ।

---

## Computer Science-এ Validity

Computer Science-এ Logical Validity ব্যবহৃত হয়:

- Formal Verification
- Automated Theorem Proving
- Program Verification
- Logic Programming
- Database Theory
- Knowledge Representation
- Model Checking

ইত্যাদিতে।

---

## Programming-এ Validity

Programming-এর Conditional Logic-এ Logical Structure গুরুত্বপূর্ণ।

উদাহরণ:

যদি user লগইন করা থাকে এবং permission থাকে, তাহলে নির্দিষ্ট resource access করা যাবে।

Formalভাবে:

LoggedIn ∧ Permission → Access

Program-এর Logic সঠিকভাবে কাজ করছে কি না তা যাচাই করার জন্য Formal Reasoning ব্যবহার করা যায়।

---

## Artificial Intelligence-এ Validity

Symbolic AI এবং Rule-based AI-তে Valid Inference গুরুত্বপূর্ণ।

উদাহরণ:

Human(Rahim)
∀x (Human(x) → Mortal(x))

Inference:

Mortal(Rahim)

Knowledge Base থেকে Conclusion Derive করার ক্ষেত্রে Logical Validity গুরুত্বপূর্ণ।

তবে Machine Learning-এর সব পদ্ধতিকে Validity-এর Classical Logical Framework দিয়ে ব্যাখ্যা করা যায় না।

---

## Validity-এর সীমাবদ্ধতা

Validity নিজে কোনো Argument-এর Premise সত্য কিনা তা নিশ্চিত করে না।

একটি Argument:

- Valid হতে পারে
- কিন্তু Premise মিথ্যা হতে পারে

তাই বাস্তব সিদ্ধান্ত নেওয়ার সময় শুধু Validity যথেষ্ট নয়।

প্রয়োজন হতে পারে:

- সত্য তথ্য
- নির্ভরযোগ্য Evidence
- সঠিক Context
- উপযুক্ত Assumption
- Sound Reasoning

---

## একটি গুরুত্বপূর্ণ উদাহরণ

ধরা যাক:

সকল মাছ উড়তে পারে।
রুই একটি মাছ।
অতএব, রুই উড়তে পারে।

এখানে প্রথম Premise বাস্তবে মিথ্যা।

তবুও Logical Form:

All A are B.
C is A.
Therefore C is B.

এই Form Valid।

তাই:

Argument Valid

কিন্তু:

Argument Sound নয়।

কারণ সব Premise সত্য নয়।

এই উদাহরণ Validity এবং Soundness-এর পার্থক্য বোঝাতে গুরুত্বপূর্ণ।

---

## Validity-এর মূল সূত্র

Validity-এর মূল ধারণাকে এভাবে প্রকাশ করা যায়:

> Premises সত্য এবং Conclusion মিথ্যা — এমন কোনো সম্ভাব্য Logical Situation নেই।

অথবা:

> If the premises are true, the conclusion must be true.

তবে এটি বিশেষভাবে Deductive Validity-এর ক্ষেত্রে প্রযোজ্য।

---

## গুরুত্বপূর্ণ পরিভাষা

| English | বাংলা |
|---|---|
| Validity | বৈধতা |
| Valid | বৈধ |
| Invalid | অবৈধ |
| Argument | যুক্তি |
| Premise | ভিত্তিবাক্য / যুক্তির ভিত্তি |
| Conclusion | উপসংহার |
| Inference | অনুমান / যুক্তিগত সিদ্ধান্ত |
| Logical Form | যৌক্তিক কাঠামো |
| Truth | সত্য |
| Truth Value | সত্যমূল্য |
| Soundness | সুপ্রতিষ্ঠিততা |
| Sound | সুপ্রতিষ্ঠিত |
| Counterexample | খণ্ডনকারী উদাহরণ |
| Countermodel | খণ্ডনকারী মডেল |
| Deduction | অবরোহী যুক্তি |
| Induction | আরোহী যুক্তি |
| Entailment | যৌক্তিক অনুসরণ |
| Formal Logic | আনুষ্ঠানিক যুক্তিবিদ্যা |
| Proof | প্রমাণ |
| Inference Rule | অনুমানের নিয়ম |
| Logical Fallacy | যুক্তিদোষ |
| Syllogism | ন্যায়ানুমান / সিলোজিজম |
| Proposition | বচন / প্রস্তাব |
| Semantic Validity | অর্থগত বৈধতা |
| Syntactic Validity | গঠনগত / প্রমাণভিত্তিক বৈধতা |

---

## Valid ও Invalid Argument-এর তুলনা

| বৈশিষ্ট্য | Valid Argument | Invalid Argument |
|---|---|---|
| Premise সত্য | হতে পারে | হতে পারে |
| Conclusion | Premise সত্য হলে মিথ্যা হতে পারে না | Premise সত্য হলেও মিথ্যা হতে পারে |
| Logical Structure | সঠিক | ত্রুটিপূর্ণ |
| Counterexample | নেই | আছে |
| Deductive Reliability | Logicalভাবে নিশ্চিত | নিশ্চিত নয় |
| Sound হওয়ার সম্ভাবনা | আছে | নেই |

---

## একটি সম্পূর্ণ Validity বিশ্লেষণ

Argument:

সকল মানুষ মরণশীল।
সক্রেটিস মানুষ।
অতএব, সক্রেটিস মরণশীল।

### Step 1 — Premise

P₁ = সকল মানুষ মরণশীল।

P₂ = সক্রেটিস মানুষ।

### Step 2 — Conclusion

C = সক্রেটিস মরণশীল।

### Step 3 — Logical Form

All Humans are Mortal.

Socrates is Human.

Therefore:

Socrates is Mortal.

### Step 4 — পরীক্ষা

এমন কোনো Logical Situation কি সম্ভব যেখানে:

P₁ সত্য
P₂ সত্য
কিন্তু C মিথ্যা?

না।

তাই Argument Valid।

যদি Premise দুটি বাস্তবেও সত্য হয়, তাহলে Argument Sound-ও হবে।

---

## Validity-এর গুরুত্ব

Validity যুক্তিবিদ্যার অন্যতম গুরুত্বপূর্ণ ধারণা।

এর মাধ্যমে:

- Argument-এর Logical Structure পরীক্ষা করা যায়
- ভুল Reasoning শনাক্ত করা যায়
- Formal Proof যাচাই করা যায়
- Deductive Reasoning বিশ্লেষণ করা যায়
- Logical Fallacy শনাক্ত করা যায়
- Mathematical Proof তৈরি করা যায়
- Computer Program-এর Logic যাচাই করা যায়
- Automated Reasoning করা যায়
- AI Knowledge System-এর Inference পরীক্ষা করা যায়
- Critical Thinking উন্নত করা যায়

---

## উপসংহার

Validity বা বৈধতা হলো Deductive Argument-এর একটি মৌলিক Logical Property।

একটি Deductive Argument Valid তখনই যখন এমন কোনো সম্ভাব্য পরিস্থিতি নেই যেখানে তার সব Premise সত্য কিন্তু Conclusion মিথ্যা।

Validity মূলত Argument-এর Logical Form-এর সঙ্গে সম্পর্কিত। তাই একটি Argument-এর Premise বাস্তবে মিথ্যা হলেও তার Logical Structure Valid হতে পারে।

এ কারণে Validity এবং Soundness আলাদা ধারণা।

একটি Sound Argument-এর ক্ষেত্রে:

- Argument Valid
- এবং সব Premise সত্য

অন্যদিকে Validity শুধুমাত্র Logical Relationship নিয়ে কাজ করে।

Validity বোঝার মাধ্যমে Proposition, Premise, Conclusion, Inference, Argument, Syllogism, Truth Table এবং Formal Proof-এর মতো যুক্তিবিদ্যার গুরুত্বপূর্ণ বিষয়গুলো আরও সহজে বোঝা যায়।

Mathematics, Computer Science, Programming, Formal Verification, Artificial Intelligence এবং Critical Thinking-এর ক্ষেত্রেও Validity গুরুত্বপূর্ণ ভূমিকা পালন করে।

সংক্ষেপে:

**Validity = Premise সত্য হলে Conclusion মিথ্যা হতে না দেওয়ার যৌক্তিক কাঠামো।**

---

## সম্পর্কিত বিষয়

- যুক্তিবিদ্যা (article:logic)
- বচন বা প্রস্তাব (article:proposition)
- যুক্তি বা Argument (article:argument)
- Premise বা যুক্তির ভিত্তি (article:premise)
- উপসংহার (article:conclusion)
- অনুমান বা Inference (article:inference)
- অবরোহী যুক্তি (article:deductive-reasoning)
- আরোহী যুক্তি (article:inductive-reasoning)
- Syllogism (article:syllogism)
- যুক্তিদোষ (article:logical-fallacy)
- Soundness (article:soundness)
- সমালোচনামূলক চিন্তা (article:critical-thinking)

---

## তথ্যসূত্র

1. Aristotle — Prior Analytics
2. George Boole — An Investigation of the Laws of Thought
3. Irving M. Copi, Carl Cohen & Kenneth McMahon — Introduction to Logic
4. Patrick J. Hurley — A Concise Introduction to Logic
5. Stanford Encyclopedia of Philosophy — Logic
6. Internet Encyclopedia of Philoso
