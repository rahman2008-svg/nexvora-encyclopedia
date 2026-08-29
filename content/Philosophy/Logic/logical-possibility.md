---
id: logical-possibility
title: যৌক্তিক সম্ভাবনা
tags:
  - দর্শন
  - যুক্তিবিদ্যা
  - যুক্তি
  - যৌক্তিক সম্ভাবনা
  - সম্ভাব্যতা
  - প্রস্তাবনা
  - সত্য
  - মিথ্যা
  - Modal Logic
  - Formal Logic
  - Propositional Logic
  - Predicate Logic
  - গণিত
related:
  - logic
  - logical-necessity
  - logical-truth
  - tautology
  - contradiction
  - contingency
  - logical-equivalence
  - consistency
  - inconsistency
  - proposition
  - modal-logic
  - formal-logic
---

# যৌক্তিক সম্ভাবনা

## সংক্ষিপ্ত পরিচিতি

যৌক্তিক সম্ভাবনা (Logical Possibility) হলো এমন একটি ধারণা, যেখানে কোনো বক্তব্য, ঘটনা বা পরিস্থিতি যুক্তিগতভাবে সম্ভব কি না তা বিশ্লেষণ করা হয়। কোনো বিষয়কে যৌক্তিকভাবে সম্ভব বলা হয় যখন সেটিকে গ্রহণ করলে কোনো মৌলিক যৌক্তিক বিরোধ বা contradiction সৃষ্টি হয় না।

সহজভাবে বলা যায়, কোনো কিছু যদি যুক্তির নিয়ম ভঙ্গ না করে ঘটতে বা সত্য হতে পারে, তাহলে সেটি যৌক্তিকভাবে সম্ভব।

উদাহরণ:

"আগামীকাল বৃষ্টি হতে পারে।"

এটি যৌক্তিকভাবে সম্ভব, কারণ এতে কোনো সরাসরি logical contradiction নেই।

অন্যদিকে:

"একই সময়ে এবং একই অর্থে বৃষ্টি হচ্ছে এবং বৃষ্টি হচ্ছে না।"

Classical logic-এর দৃষ্টিতে এটি একটি contradiction এবং তাই যৌক্তিকভাবে অসম্ভব।

---

## যৌক্তিক সম্ভাবনার ধারণা

Logical possibility মূলত এমন পরিস্থিতি বোঝায় যা অন্তত একটি coherent বা সামঞ্জস্যপূর্ণ logical interpretation-এর অধীনে সত্য হতে পারে।

কোনো proposition-এর ক্ষেত্রে যদি এমন কোনো সম্ভাব্য interpretation থাকে যেখানে proposition-টি সত্য, তাহলে সেটিকে logically possible বলা যেতে পারে।

প্রতীকীভাবে:

◇P

এখানে:

- ◇ = possibility operator
- P = proposition

অতএব:

◇P

এর অর্থ:

"P সম্ভব।"

---

## সম্ভাব্যতা ও অনিবার্যতার সম্পর্ক

Logical possibility এবং logical necessity পরস্পরের সঙ্গে ঘনিষ্ঠভাবে সম্পর্কিত।

Logical necessity:

□P

অর্থ:

"P অনিবার্যভাবে সত্য।"

Logical possibility:

◇P

অর্থ:

"P সম্ভবত সত্য।"

একটি প্রচলিত modal relationship হলো:

◇P ≡ ¬□¬P

অর্থাৎ P সম্ভব তখনই, যখন P-এর negation অনিবার্য নয়।

অন্যভাবে:

□P ≡ ¬◇¬P

অর্থাৎ P অনিবার্য তখনই, যখন P মিথ্যা হওয়া সম্ভব নয়।

---

## Logical Possibility বনাম Actuality

কোনো বিষয় logically possible হলেই সেটি বাস্তবে ঘটেছে বা ঘটবে—এমন নয়।

উদাহরণ:

"আগামীকাল বৃষ্টি হবে।"

এটি যৌক্তিকভাবে সম্ভব হতে পারে।

কিন্তু এটি বাস্তবে সত্য কি না তা আবহাওয়ার তথ্য দিয়ে যাচাই করতে হবে।

তাই:

- Possible = হতে পারে
- Actual = বাস্তবে ঘটেছে বা ঘটছে
- Necessary = হতে বাধ্য

এই তিনটি ধারণা আলাদা।

---

## Logical Possibility বনাম Logical Necessity

দুটি ধারণার মধ্যে প্রধান পার্থক্য:

### Logical Possibility

কোনো proposition মিথ্যা না হয়েও সত্য হতে পারে।

প্রতীক:

◇P

### Logical Necessity

কোনো proposition মিথ্যা হওয়ার সুযোগ নেই।

প্রতীক:

□P

উদাহরণ:

"আজ বৃষ্টি হচ্ছে" — contingent বা সম্ভাব্য সত্য।

"হয় P সত্য, অথবা P সত্য নয়" — classical logic-এ necessary truth হিসেবে বিবেচিত হতে পারে।

---

## Logical Possibility বনাম Logical Impossibility

Logical impossibility হলো এমন কোনো proposition যা কোনো coherent interpretation-এ সত্য হতে পারে না।

উদাহরণ:

P ∧ ¬P

এখানে একই সঙ্গে P এবং P-এর negation দাবি করা হচ্ছে।

Classical propositional logic-এ:

P ∧ ¬P

একটি contradiction।

তাই এটি logically impossible।

---

## Logical Possibility ও Contingency

Contingent proposition এমন একটি proposition যা সত্যও হতে পারে এবং মিথ্যাও হতে পারে।

উদাহরণ:

"ঢাকায় আজ বৃষ্টি হচ্ছে।"

নির্দিষ্ট দিনে এটি সত্য হতে পারে এবং অন্য দিনে মিথ্যা হতে পারে।

এই ধরনের proposition সাধারণত:

- necessary নয়
- impossible নয়
- possible এবং contingent

অর্থাৎ contingency হলো এমন একটি অবস্থা যেখানে proposition-এর সত্যতা পরিবর্তিত হতে পারে।

---

## Modal Logic-এ Logical Possibility

Modal logic হলো এমন একটি formal logical framework যেখানে necessity এবং possibility বিশ্লেষণ করা হয়।

এখানে সাধারণত দুটি modal operator ব্যবহৃত হয়:

### Necessity Operator

□P

অর্থ:

"P necessarily true."

### Possibility Operator

◇P

অর্থ:

"P possibly true."

উদাহরণ:

◇(বৃষ্টি হচ্ছে)

এর অর্থ:

"বৃষ্টি হওয়া সম্ভব।"

আর:

□(P ∨ ¬P)

এর অর্থ:

"classical logical framework-এ P অথবা P নয়—এটি অনিবার্য।"

---

## Possible Worlds

Modal logic-এ logical possibility বোঝাতে possible worlds বা সম্ভাব্য জগতের ধারণা ব্যবহার করা হয়।

এখানে "world" বলতে বাস্তব পৃথিবীর মতো কোনো নির্দিষ্ট গ্রহ বা স্থান বোঝানো হয় না। এটি একটি সম্পূর্ণ সম্ভাব্য state of affairs বা পরিস্থিতির formal representation হতে পারে।

ধরা যাক:

P = "আজ বৃষ্টি হচ্ছে।"

একটি possible world-এ P সত্য হতে পারে।

অন্য একটি possible world-এ P মিথ্যা হতে পারে।

যদি অন্তত একটি appropriate possible world-এ P সত্য হয়, তাহলে modal framework-এ P-কে possible বলা যেতে পারে।

---

## Possible World ও Necessary Truth

যদি কোনো proposition সব relevant possible world-এ সত্য হয়, তাহলে সেটিকে necessary বলা হয়।

প্রতীকীভাবে:

□P

আর যদি অন্তত একটি relevant possible world-এ P সত্য হয়:

◇P

সুতরাং:

- সব possible world-এ সত্য → Necessary
- অন্তত একটি possible world-এ সত্য → Possible
- কোনো possible world-এই সত্য নয় → Impossible

---

## Truth Table ও Logical Possibility

Propositional logic-এ কোনো formula satisfiable কি না পরীক্ষা করে logical possibility সম্পর্কে ধারণা পাওয়া যায়।

উদাহরণ:

P ∧ Q

Truth table:

| P | Q | P ∧ Q |
|---|---|---|
| সত্য | সত্য | সত্য |
| সত্য | মিথ্যা | মিথ্যা |
| মিথ্যা | সত্য | মিথ্যা |
| মিথ্যা | মিথ্যা | মিথ্যা |

এখানে অন্তত একটি row-তে formula সত্য।

তাই:

P ∧ Q

satisfiable।

অর্থাৎ এটি logically possible।

---

## Tautology ও Logical Possibility

Tautology এমন formula যা সব possible truth assignment-এ সত্য।

উদাহরণ:

P ∨ ¬P

এটি tautology।

তাই এটি অবশ্যই logically possible।

আরও শক্তিশালীভাবে, classical propositional logic-এর অধীনে এটি necessary truth হিসেবেও বিবেচিত হয়।

---

## Contradiction ও Logical Possibility

Contradiction এমন formula যা কোনো truth assignment-এ সত্য হয় না।

উদাহরণ:

P ∧ ¬P

এটি unsatisfiable।

অতএব:

P ∧ ¬P

logically impossible।

---

## Satisfiability

Logical possibility বোঝার ক্ষেত্রে satisfiability একটি গুরুত্বপূর্ণ ধারণা।

একটি formula satisfiable হলে এমন অন্তত একটি interpretation বা truth assignment থাকে যেখানে formula-টি সত্য।

উদাহরণ:

P ∧ Q

এর জন্য:

P = সত্য

Q = সত্য

নির্ধারণ করলে formula-টি সত্য হয়।

তাই এটি satisfiable এবং logically possible।

---

## Unsatisfiability

কোনো formula unsatisfiable হলে কোনো truth assignment বা interpretation-এই formula-টি সত্য হয় না।

উদাহরণ:

P ∧ ¬P

এটি unsatisfiable।

কারণ P একই সঙ্গে সত্য এবং মিথ্যা হতে পারে না—classical logic-এর কাঠামোতে।

তাই এটি logically impossible।

---

## Logical Possibility ও Consistency

Consistency-এর সঙ্গে logical possibility-এর ঘনিষ্ঠ সম্পর্ক রয়েছে।

যদি একটি set of propositions এমন হয় যে তাদের সবাইকে একই interpretation-এর অধীনে সত্য করা যায়, তাহলে সেটটি consistent বা satisfiable হতে পারে।

উদাহরণ:

P

¬Q

এই দুই statement একসঙ্গে সত্য হতে পারে।

তাই:

{P, ¬Q}

একটি consistent set।

অন্যদিকে:

{P, ¬P}

classical logic-এ inconsistent।

---

## উদাহরণ: দুটি শর্ত

ধরা যাক:

P = "রহমান ছাত্র।"

Q = "রহমান ডাক্তার।"

তাহলে:

P ∧ Q

এর অর্থ:

"রহমান ছাত্র এবং ডাক্তার।"

এতে কোনো logical contradiction নেই।

তাই এটি logically possible হতে পারে।

কিন্তু বাস্তবে রহমান একই সঙ্গে ছাত্র ও ডাক্তার কি না, সেটি empirical information-এর বিষয়।

---

## Logical Possibility ও বাস্তব সম্ভাবনা

Logical possibility এবং practical বা physical possibility এক নয়।

উদাহরণ:

"মানুষ পৃথিবী ছেড়ে অন্য গ্রহে বসবাস করবে।"

এটি বর্তমানে বাস্তব বা প্রযুক্তিগতভাবে সহজ নাও হতে পারে।

কিন্তু বক্তব্যটির মধ্যে সরাসরি logical contradiction নেই।

তাই কোনো formal framework-এ এটি logically possible হতে পারে, যদিও বর্তমানে বাস্তবায়ন করা কঠিন।

অতএব:

Logical possibility ≠ Practical possibility

এবং:

Logical possibility ≠ Physical possibility

---

## Logical Possibility ও Physical Possibility

Physical possibility প্রকৃতির নিয়মের সঙ্গে সম্পর্কিত।

Logical possibility logical contradiction-এর সঙ্গে সম্পর্কিত।

একটি বিষয় logical possible হতে পারে কিন্তু physical law-এর কারণে বাস্তবে সম্ভব নাও হতে পারে—এমন পার্থক্য দর্শনের modal reasoning-এ গুরুত্বপূর্ণ।

তাই কোনো proposition পরীক্ষা করার সময় প্রশ্ন করা দরকার:

1. এটি logical contradiction তৈরি করছে কি?
2. এটি formal system-এর নিয়ম মেনে চলছে কি?
3. এটি physical law-এর সঙ্গে সামঞ্জস্যপূর্ণ কি?
4. বাস্তবে এটি ঘটেছে কি?

---

## Logical Possibility ও Mathematical Logic

Mathematical logic-এ কোনো formula satisfiable কি না তা পরীক্ষা করা logical possibility বোঝার একটি formal পদ্ধতি।

যদি:

∃ valuation V such that V(P) = True

তাহলে P satisfiable।

অর্থাৎ অন্তত একটি valid valuation-এ P সত্য।

আর যদি এমন কোনো valuation না থাকে:

∀V, V(P) = False

তাহলে P unsatisfiable।

---

## Predicate Logic-এ Logical Possibility

Predicate logic-এ logical possibility আরও সমৃদ্ধভাবে বিশ্লেষণ করা যায়।

উদাহরণ:

∃x Student(x)

এর অর্থ:

"অন্তত একজন ছাত্র রয়েছে।"

যদি এমন একটি model তৈরি করা যায় যেখানে অন্তত একজন ব্যক্তি Student predicate পূরণ করে, তাহলে formula-টি satisfiable।

অন্যদিকে:

∀x (Student(x) ∧ ¬Student(x))

একটি contradiction তৈরি করে।

Classical logic-এর অধীনে এটি satisfiable নয়।

---

## Logical Possibility ও Model

Model হলো এমন একটি formal interpretation যেখানে নির্দিষ্ট logical statements সত্য হয়।

যদি কোনো proposition-এর জন্য অন্তত একটি model পাওয়া যায়, তাহলে proposition-টি satisfiable।

উদাহরণ:

Student(Rahman)

এর জন্য এমন একটি model তৈরি করা যায় যেখানে Rahman একজন student।

তাই formula-টি logically possible।

---

## Logical Possibility ও Argument

একটি argument-এর ক্ষেত্রে logical possibility ব্যবহার করে counterexample বিশ্লেষণ করা যায়।

ধরা যাক:

Premise:
P → Q

Premise:
P

Conclusion:
Q

এখানে এমন কোনো interpretation নেই যেখানে premises সত্য কিন্তু Q মিথ্যা।

তাই argument valid।

অন্যদিকে কোনো argument-এর premises সত্য রেখে conclusion মিথ্যা করা সম্ভব হলে argument invalid।

এই কারণে logical possibility validity বিশ্লেষণেও গুরুত্বপূর্ণ।

---

## Counterexample

Counterexample হলো এমন একটি সম্ভাব্য interpretation যেখানে argument-এর premises সত্য কিন্তু conclusion মিথ্যা।

উদাহরণ:

সব বিড়াল প্রাণী।

সব কুকুর প্রাণী।

অতএব, সব কুকুর বিড়াল।

এখানে premises সত্য হতে পারে, কিন্তু conclusion মিথ্যা হতে পারে।

তাই একটি counterexample সম্ভব।

অতএব argument-টি valid নয়।

---

## Logical Possibility ও Critical Thinking

কোনো দাবি শুনলে critical thinking-এর ক্ষেত্রে প্রশ্ন করা যেতে পারে:

- দাবিটি logically possible কি?
- এর মধ্যে contradiction আছে কি?
- এর বিপরীত অবস্থা logically possible কি?
- দাবিটি necessary নাকি contingent?
- দাবিটির পক্ষে empirical evidence আছে কি?
- এটি physical possibility-এর সঙ্গে সামঞ্জস্যপূর্ণ কি?

এগুলো আলাদা করে দেখলে reasoning আরও পরিষ্কার হয়।

---

## দর্শনে যৌক্তিক সম্ভাবনা

দর্শনে possibility এবং necessity নিয়ে দীর্ঘ আলোচনা রয়েছে।

বিশেষ করে modal metaphysics-এ প্রশ্ন করা হয়:

- কোন বিষয় সত্য হতে পারত?
- কোন বিষয় অন্যভাবে হওয়া সম্ভব নয়?
- কোন বিষয় কেবল বাস্তবে সত্য?
- কোন বিষয় সব possible situation-এ সত্য?
- কোনো ঘটনা logically impossible কি না?

এই প্রশ্নগুলো modal reasoning-এর গুরুত্বপূর্ণ অংশ।

---

## Logical Possibility ও Identity

কোনো object বা entity-এর identity নিয়ে reasoning করার ক্ষেত্রেও possibility গুরুত্বপূর্ণ।

উদাহরণ:

"একটি বস্তুকে একই অর্থে একই সময়ে সম্পূর্ণভাবে নিজস্ব এবং নিজস্ব নয় বলা যায় কি?"

Classical logic-এর কাঠামোতে এই ধরনের contradiction logical impossibility তৈরি করতে পারে।

---

## Logical Possibility ও Language

প্রাকৃতিক ভাষার কোনো বক্তব্য logically possible কি না নির্ধারণ করার সময় context গুরুত্বপূর্ণ হতে পারে।

উদাহরণ:

"ব্যাংকটি বন্ধ।"

এখানে "ব্যাংক" বলতে আর্থিক প্রতিষ্ঠান নাকি নদীর তীর—তা context অনুযায়ী ভিন্ন হতে পারে।

Formalization ambiguity কমাতে সাহায্য করে।

---

## Logical Possibility ও Artificial Intelligence

AI-এর symbolic reasoning system-এ logical possibility বিভিন্নভাবে ব্যবহার করা যায়।

যেমন:

- Knowledge representation
- Automated reasoning
- Constraint solving
- Planning
- SAT solving
- Model checking
- Theorem proving

কোনো knowledge base-এর statements একসঙ্গে consistent কি না এবং একটি নতুন proposition সম্ভব কি না—এসব প্রশ্ন formal reasoning system বিশ্লেষণ করতে পারে।

---

## Computer Science-এ ব্যবহার

Logical possibility computer science-এর বিভিন্ন ক্ষেত্রে গুরুত্বপূর্ণ।

### SAT Solver

কোনো Boolean formula-এর satisfying assignment আছে কি না নির্ধারণ করা হয়।

### Model Checking

কোনো system-এর নির্দিষ্ট state বা behavior সম্ভব কি না পরীক্ষা করা যায়।

### Formal Verification

Software বা hardware নির্দিষ্ট logical property মেনে চলে কি না পরীক্ষা করা হয়।

### Constraint Solving

একাধিক constraint একই সঙ্গে পূরণ করা সম্ভব কি না নির্ধারণ করা হয়।

---

## বাস্তব জীবনের উদাহরণ

ধরা যাক কেউ বলল:

"একটি মানুষ একই সময়ে ঢাকায় এবং চট্টগ্রামে একই physical location-এ আছে।"

এখানে "একই সময়ে" এবং "একই physical location" শব্দগুলোর অর্থ স্পষ্ট করলে claim-টির logical structure বিশ্লেষণ করা যায়।

আবার:

"একজন মানুষ একই সময়ে সম্পূর্ণ জেগে এবং সম্পূর্ণ ঘুমন্ত।"

এটি কীভাবে ব্যাখ্যা করা হবে তা নির্ভর করে terms-এর সংজ্ঞা ও context-এর ওপর।

অতএব logical possibility বিশ্লেষণে সংজ্ঞা অত্যন্ত গুরুত্বপূর্ণ।

---

## যৌক্তিক সম্ভাবনা নির্ধারণের ধাপ

কোনো proposition logically possible কি না পরীক্ষা করতে সাধারণভাবে:

1. proposition-টির অর্থ নির্ধারণ করতে হবে।
2. ambiguous terms পরিষ্কার করতে হবে।
3. proposition-টিকে formal form-এ প্রকাশ করতে হবে।
4. contradiction আছে কি না পরীক্ষা করতে হবে।
5. truth table তৈরি করা যেতে পারে।
6. satisfiability পরীক্ষা করা যেতে পারে।
7. প্রয়োজনে একটি model নির্মাণ করা যেতে পারে।
8. proposition-টি necessary, contingent নাকি impossible তা নির্ধারণ করা যেতে পারে।

---

## Logical Possibility-এর তিনটি মৌলিক অবস্থা

একটি proposition-কে সাধারণভাবে তিনভাবে শ্রেণিবদ্ধ করা যায়:

### Necessary

সব relevant interpretation বা possible world-এ সত্য।

প্রতীক:

□P

### Contingent

কিছু interpretation-এ সত্য এবং কিছু interpretation-এ মিথ্যা।

### Impossible

কোনো relevant interpretation-এ সত্য নয়।

প্রতীকীভাবে:

¬◇P

---

## একটি সম্পূর্ণ উদাহরণ

ধরা যাক:

P = "আজ বৃষ্টি হচ্ছে।"

### P

এটি contingent হতে পারে।

কারণ:

- বৃষ্টি হতে পারে।
- বৃষ্টি নাও হতে পারে।

### P ∨ ¬P

এটি classical logic-এ tautology।

তাই এটি necessary truth-এর উদাহরণ।

### P ∧ ¬P

এটি contradiction।

তাই এটি logically impossible।

এখানে তিনটি ধারণার পার্থক্য স্পষ্ট:

- P → contingent
- P ∨ ¬P → necessary
- P ∧ ¬P → impossible

---

## গুরুত্বপূর্ণ পরিভাষা

| English | বাংলা |
|---|---|
| Logical Possibility | যৌক্তিক সম্ভাবনা |
| Possibility | সম্ভাবনা |
| Logical Necessity | যৌক্তিক অনিবার্যতা |
| Logical Impossibility | যৌক্তিক অসম্ভবতা |
| Possible World | সম্ভাব্য জগত |
| Possible State | সম্ভাব্য অবস্থা |
| Actuality | বাস্তবতা |
| Contingency | আপতিকতা |
| Satisfiability | সন্তোষণীয়তা / সন্তৃপ্তিযোগ্যতা |
| Unsatisfiability | অসন্তোষণীয়তা |
| Model | মডেল |
| Interpretation | ব্যাখ্যা / অভিব্যক্তি |
| Valuation | সত্যমান নির্ধারণ |
| Tautology | টটোলজি |
| Contradiction | বিরোধ / স্ববিরোধ |
| Consistency | সামঞ্জস্য |
| Inconsistency | অসামঞ্জস্য |
| Necessity Operator | অনিবার্যতা অপারেটর |
| Possibility Operator | সম্ভাবনা অপারেটর |
| Modal Logic | মডাল যুক্তিবিদ্যা |
| Logical Consequence | যৌক্তিক পরিণতি |
| Counterexample | খণ্ডন-উদাহরণ |

---

## যৌক্তিক সম্ভাবনার গুরুত্ব

Logical possibility বোঝা গুরুত্বপূর্ণ কারণ এটি আমাদের বিভিন্ন ধরনের সত্য ও সম্ভাবনাকে আলাদা করতে সাহায্য করে।

এর মাধ্যমে বোঝা যায়:

- কোন বিষয় logically possible
- কোন বিষয় logically impossible
- কোন proposition necessary
- কোন proposition contingent
- কোন formula satisfiable
- কোন formula contradiction
- কোনো argument-এর counterexample আছে কি না
- কোনো set of propositions consistent কি না

---

## যৌক্তিক সম্ভাবনার সীমাবদ্ধতা

Logical possibility কোনো proposition বাস্তবে সত্য কি না তা নিশ্চিত করে না।

একটি proposition logically possible হতে পারে, কিন্তু:

- বাস্তবে সত্য নাও হতে পারে
- physical law-এর সঙ্গে অসামঞ্জস্যপূর্ণ হতে পারে
- বর্তমানে প্রযুক্তিগতভাবে সম্ভব নাও হতে পারে
- empirical evidence দ্বারা সমর্থিত নাও হতে পারে

তাই logical possibility এবং factual truth আলাদা করে বিচার করতে হয়।

---

## উপসংহার

যৌক্তিক সম্ভাবনা যুক্তিবিদ্যার একটি গুরুত্বপূর্ণ ধারণা, যা কোনো proposition বা পরিস্থিতি logical contradiction ছাড়াই সম্ভব কি না তা বিশ্লেষণ করে।

Modal logic-এ এটি ◇P দ্বারা প্রকাশ করা হয়। কোনো proposition অন্তত একটি appropriate possible world, interpretation বা model-এ সত্য হতে পারলে সেটিকে logically possible হিসেবে বিবেচনা করা যায়।

Logical possibility-এর সঙ্গে logical necessity, contingency, contradiction, consistency এবং satisfiability-এর গভীর সম্পর্ক রয়েছে।

গণিত, দর্শন, computer science, artificial intelligence, formal verification এবং critical thinking-এ এই ধারণার গুরুত্বপূর্ণ ব্যবহার রয়েছে।

সবচেয়ে গুরুত্বপূর্ণ বিষয় হলো—কোনো কিছু logically possible হওয়া মানেই সেটি বাস্তবে সত্য বা বাস্তবায়নযোগ্য হওয়া নয়। Logical possibility শুধু নির্দেশ করে যে সেটি যৌক্তিক কাঠামোর মধ্যে অসম্ভব নয়।
