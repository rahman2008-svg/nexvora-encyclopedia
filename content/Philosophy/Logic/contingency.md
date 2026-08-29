---
id: contingency
title: Contingency
tags:
  - দর্শন
  - যুক্তিবিদ্যা
  - Contingency
  - আপতিক সত্য
  - প্রস্তাব
  - বচন
  - Modal Logic
  - সত্য
  - মিথ্যা
  - সম্ভাবনা
related:
  - logic
  - proposition
  - truth
  - contradiction
  - consistency
  - tautology
  - logical-truth
  - modal-logic
---

# Contingency

## সংক্ষিপ্ত পরিচিতি

Contingency বা আপতিকতা হলো যুক্তিবিদ্যার এমন একটি ধারণা, যেখানে কোনো proposition বা বচন সব সম্ভাব্য পরিস্থিতিতে সত্য নয় এবং সব সম্ভাব্য পরিস্থিতিতে মিথ্যাও নয়। অর্থাৎ কোনো contingent proposition কিছু পরিস্থিতিতে সত্য হতে পারে এবং অন্য পরিস্থিতিতে মিথ্যা হতে পারে।

সহজভাবে বলা যায়, যে proposition-এর সত্যতা তার logical form-এর কারণে অনিবার্য নয় এবং যার negation-ও অনিবার্যভাবে সত্য নয়, তাকে contingent proposition বলা যায়।

উদাহরণ:

«আজ বৃষ্টি হচ্ছে।»

এই বক্তব্যটি কোনো নির্দিষ্ট সময় ও স্থানে সত্য হতে পারে, আবার অন্য সময় বা স্থানে মিথ্যা হতে পারে। তাই এটি সাধারণভাবে একটি contingent proposition-এর উদাহরণ হতে পারে।

Contingency ধারণাটি বিশেষভাবে propositional logic, modal logic, দর্শন এবং সম্ভাব্য জগতের বিশ্লেষণে গুরুত্বপূর্ণ।

---

## Contingency-এর অর্থ

Contingency বলতে এমন একটি অবস্থা বোঝায় যেখানে কোনো proposition সত্য হওয়া সম্ভব, কিন্তু তা অবশ্যই সত্য হতে হবে এমন নয়।

অন্যদিকে proposition-টি মিথ্যা হওয়াও সম্ভব।

অর্থাৎ:

- Proposition সত্য হতে পারে।
- Proposition মিথ্যাও হতে পারে।
- এটি সব সম্ভাব্য পরিস্থিতিতে সত্য নয়।
- এটি সব সম্ভাব্য পরিস্থিতিতে মিথ্যাও নয়।

এই বৈশিষ্ট্যের কারণে contingent proposition-কে tautology এবং contradiction থেকে আলাদা করা যায়।

---

## Tautology, Contradiction এবং Contingency

Propositional logic-এ proposition-কে truth table-এর মাধ্যমে বিশ্লেষণ করলে সাধারণভাবে তিন ধরনের ফল পাওয়া যায়:

1. Tautology
2. Contradiction
3. Contingency

### Tautology

যে proposition-এর truth value সব সম্ভাব্য ক্ষেত্রে True হয়, তাকে tautology বলা হয়।

উদাহরণ:

P ∨ ¬P

এটি classical logic-এ সবসময় সত্য।

### Contradiction

যে proposition-এর truth value সব সম্ভাব্য ক্ষেত্রে False হয়, তাকে contradiction বলা হয়।

উদাহরণ:

P ∧ ¬P

এটি একই সঙ্গে P এবং P নয় দাবি করে। Classical propositional logic-এ এটি সবসময় মিথ্যা।

### Contingency

যে proposition কিছু ক্ষেত্রে True এবং কিছু ক্ষেত্রে False হয়, তাকে contingent proposition বলা হয়।

উদাহরণ:

P ∧ Q

যদি P ও Q উভয়ই সত্য হয়, তাহলে এটি সত্য। অন্য কোনো combination-এ এটি মিথ্যা হতে পারে।

---

## Truth Table-এর মাধ্যমে Contingency

Contingency বোঝার সবচেয়ে সহজ উপায় হলো truth table ব্যবহার করা।

ধরা যাক:

P ∧ Q

এর truth table:

| P | Q | P ∧ Q |
|---|---|-------|
| True | True | True |
| True | False | False |
| False | True | False |
| False | False | False |

এখানে শেষ column-এ True এবং False উভয়ই রয়েছে।

তাই:

P ∧ Q

একটি contingent proposition।

---

## Contingent Proposition

Contingent proposition হলো এমন proposition যার truth value পরিস্থিতি বা interpretation-এর ওপর নির্ভর করে।

উদাহরণ:

«ঢাকায় আজ বৃষ্টি হচ্ছে।»

নির্দিষ্ট একটি সময়ে এটি সত্য হতে পারে।

অন্য সময়ে এটি মিথ্যা হতে পারে।

তাই এর সত্যতা logical necessity দ্বারা নির্ধারিত নয়।

---

## Logical Contingency

Logical contingency বলতে proposition-এর এমন বৈশিষ্ট্য বোঝায় যেখানে তার logical form তাকে সর্বদা সত্য বা সর্বদা মিথ্যা করে না।

একটি proposition logically contingent হলে অন্তত একটি interpretation বা valuation-এ এটি সত্য এবং অন্তত একটি interpretation বা valuation-এ এটি মিথ্যা হবে।

অর্থাৎ:

∃ valuation V₁ : V₁(P) = True

এবং

∃ valuation V₂ : V₂(P) = False

---

## Contingency ও Tautology-এর পার্থক্য

Tautology সব সম্ভাব্য valuation-এ সত্য।

Contingent proposition সব valuation-এ সত্য নয়।

উদাহরণ:

P ∨ ¬P

একটি tautology।

অন্যদিকে:

P ∧ Q

একটি contingent proposition।

কারণ P এবং Q-এর truth value পরিবর্তিত হলে পুরো expression-এর truth value-ও পরিবর্তিত হতে পারে।

---

## Contingency ও Contradiction-এর পার্থক্য

Contradiction সব সম্ভাব্য valuation-এ মিথ্যা।

Contingent proposition কিছু valuation-এ সত্য এবং কিছু valuation-এ মিথ্যা।

উদাহরণ:

P ∧ ¬P

একটি contradiction।

অন্যদিকে:

P ∧ Q

একটি contingency।

---

## Contingency শনাক্ত করার পদ্ধতি

কোনো propositional expression contingent কি না তা নির্ণয় করার একটি সাধারণ পদ্ধতি হলো truth table তৈরি করা।

ধাপগুলো:

1. Proposition-এর atomic variables শনাক্ত করতে হবে।
2. সব সম্ভাব্য truth-value combination তৈরি করতে হবে।
3. প্রতিটি combination-এর জন্য expression-এর truth value নির্ণয় করতে হবে।
4. যদি সব ফল True হয়, তাহলে এটি tautology।
5. যদি সব ফল False হয়, তাহলে এটি contradiction।
6. যদি True এবং False উভয় ফল পাওয়া যায়, তাহলে এটি contingency।

---

## উদাহরণ: P → Q

ধরা যাক:

P = বৃষ্টি হচ্ছে।

Q = রাস্তা ভেজা।

তাহলে:

P → Q

এর truth table:

| P | Q | P → Q |
|---|---|-------|
| True | True | True |
| True | False | False |
| False | True | True |
| False | False | True |

এখানে True এবং False উভয় ফল রয়েছে।

তাই:

P → Q

একটি contingent proposition।

---

## Contingency এবং Logical Form

কোনো proposition-এর logical form তার contingency নির্ধারণে গুরুত্বপূর্ণ ভূমিকা পালন করতে পারে।

একই বিষয়বস্তুকে ভিন্ন logical form-এ প্রকাশ করলে তার logical status পরিবর্তিত হতে পারে।

উদাহরণ:

P ∨ ¬P

সবসময় True।

অন্যদিকে:

P ∧ Q

সবসময় True নয় এবং সবসময় False-ও নয়।

তাই প্রথমটি tautology এবং দ্বিতীয়টি contingency।

---

## Contingency ও Truth Value

Contingent proposition-এর truth value পরিবর্তনশীল হতে পারে।

তবে এর অর্থ এই নয় যে proposition-এর সত্যতা সম্পূর্ণ এলোমেলো।

বরং এর truth value নির্ভর করতে পারে:

- বাস্তব পরিস্থিতির ওপর
- সময়ের ওপর
- স্থানের ওপর
- interpretation-এর ওপর
- variable-এর truth value-এর ওপর
- empirical facts-এর ওপর

---

## Contingency ও বাস্তব ঘটনা

দৈনন্দিন জীবনের অনেক factual statement contingent হতে পারে।

উদাহরণ:

«আজ স্কুল খোলা।»

এটি কোনো নির্দিষ্ট দিনে সত্য হতে পারে এবং অন্য দিনে মিথ্যা হতে পারে।

আরেকটি উদাহরণ:

«আজ আকাশ মেঘলা।»

এটি নির্দিষ্ট পরিস্থিতিতে সত্য বা মিথ্যা হতে পারে।

তাই এগুলোকে সাধারণভাবে contingent statement হিসেবে বিবেচনা করা যায়।

---

## Contingency এবং Necessity

Contingency বোঝার জন্য necessity বা আবশ্যিকতার ধারণাও বোঝা গুরুত্বপূর্ণ।

Necessary proposition এমন proposition যার সত্যতা সব relevant possible situation-এ বজায় থাকে।

Contingent proposition-এর ক্ষেত্রে:

- এটি সত্য হতে পারে।
- এটি মিথ্যাও হতে পারে।

অর্থাৎ contingent proposition necessary নয়।

---

## Contingency এবং Possibility

Contingent proposition সাধারণত possibility-এর সঙ্গে ঘনিষ্ঠভাবে সম্পর্কিত।

একটি contingent proposition-এর ক্ষেত্রে অন্তত একটি possible situation রয়েছে যেখানে proposition সত্য এবং অন্তত একটি possible situation রয়েছে যেখানে proposition মিথ্যা।

সরলভাবে:

Possible(P) এবং Possible(¬P)

উভয়ই সত্য হলে P contingent হতে পারে।

---

## Modal Logic-এ Contingency

Modal logic-এ necessity এবং possibility formalভাবে বিশ্লেষণ করা হয়।

একটি proposition P contingent হওয়ার একটি সাধারণ modal characterization হলো:

◇P ∧ ◇¬P

এখানে:

- ◇P = P সম্ভব
- ◇¬P = P মিথ্যা হওয়াও সম্ভব

অর্থাৎ P সত্য হওয়া সম্ভব এবং P মিথ্যা হওয়াও সম্ভব।

এই অর্থে P neither necessary nor impossible।

---

## Contingent Truth

কোনো proposition বাস্তবে সত্য হতে পারে কিন্তু logical necessity-এর কারণে সত্য না-ও হতে পারে।

এ ধরনের সত্যকে contingent truth বলা যায়।

উদাহরণ:

«বাংলাদেশের রাজধানী ঢাকা।»

এটি বাস্তব বিশ্বের একটি factual truth। কিন্তু এটি pure logical form-এর কারণে সত্য নয়।

অন্য কোনো সম্ভাব্য পরিস্থিতিতে রাজধানী অন্য শহর হতে পারত।

তাই এর সত্যতা logical necessity-এর পরিবর্তে বাস্তব তথ্য ও ইতিহাসের ওপর নির্ভরশীল।

---

## Necessary Truth বনাম Contingent Truth

দুটি ধারণার মধ্যে পার্থক্য:

### Necessary Truth

যে proposition মিথ্যা হওয়া সম্ভব নয় বা সংশ্লিষ্ট formal system-এ সব relevant অবস্থায় সত্য, সেটি necessary truth।

উদাহরণ:

P ∨ ¬P

Classical propositional logic-এ এটি necessary/logically true হিসেবে বিবেচিত হয়।

### Contingent Truth

যে proposition বাস্তবে সত্য কিন্তু অন্য কোনো possible situation-এ মিথ্যা হতে পারে, সেটি contingent truth।

উদাহরণ:

«পৃথিবীতে সাতটি মহাদেশ আছে।»

এটি একটি factual claim; এর সত্যতা logical form থেকে সরাসরি আসে না।

---

## Contingency ও Empirical Knowledge

Empirical knowledge-এর অনেক proposition contingent।

বিজ্ঞান সাধারণত পৃথিবী সম্পর্কে পর্যবেক্ষণযোগ্য তথ্য নিয়ে কাজ করে।

যেমন:

- কোনো পদার্থের নির্দিষ্ট বৈশিষ্ট্য
- কোনো স্থানের আবহাওয়া
- কোনো গ্রহের অবস্থান
- কোনো জীবের বৈশিষ্ট্য

এসব তথ্য বাস্তব জগতের অবস্থার ওপর নির্ভর করে।

তাই এগুলো logical necessity-এর মতো নয়।

---

## Contingency ও Science

বিজ্ঞানে contingent facts অত্যন্ত গুরুত্বপূর্ণ।

বৈজ্ঞানিক গবেষণায় কোনো proposition সত্য কি না তা নির্ণয় করতে সাধারণত:

- Observation
- Experiment
- Measurement
- Evidence
- Statistical analysis

ব্যবহার করা হয়।

Logic argument-এর structure পরীক্ষা করতে সাহায্য করে, কিন্তু কোনো contingent factual claim সত্য কি না তা জানতে empirical evidence প্রয়োজন হতে পারে।

---

## Contingency ও Mathematics

গণিতের formal systems-এ কিছু proposition theorem হিসেবে necessary হতে পারে, আবার কিছু statement-এর সত্যতা নির্দিষ্ট mathematical structure বা assumptions-এর ওপর নির্ভর করতে পারে।

একটি theorem সাধারণত নির্দিষ্ট axioms ও rules of inference থেকে প্রমাণ করা হয়।

অন্যদিকে কোনো statement যদি নির্দিষ্ট model-এ সত্য কিন্তু অন্য model-এ মিথ্যা হয়, তাহলে model-theoretic অর্থে সেটি সেই theory-র অধীনে contingent হতে পারে।

---

## Contingency ও Computer Science

Computer science-এ contingency বিভিন্নভাবে দেখা যায়।

Boolean expression-এর ক্ষেত্রে:

A AND B

এর ফল A ও B-এর truth value-এর ওপর নির্ভর করে।

Database query-তেও একই ধরনের conditional logic ব্যবহৃত হয়।

উদাহরণ:

age > 18 AND country = "Bangladesh"

এটি database-এর নির্দিষ্ট record-এর তথ্য অনুযায়ী True অথবা False হতে পারে।

---

## Contingency ও Programming

Programming-এ conditional expression অনেক সময় contingent truth-এর মতো আচরণ করে।

উদাহরণ:

```text
if user_logged_in:
    show_dashboard
else:
    show_login
এখানে user_logged_in condition-এর truth value অনুযায়ী program-এর behavior পরিবর্তিত হয়।
Logic-এর দৃষ্টিতে conditional behavior বোঝার জন্য Boolean reasoning গুরুত্বপূর্ণ।
Contingency ও Artificial Intelligence
Artificial Intelligence-এ logical reasoning এবং knowledge representation-এর ক্ষেত্রে contingent information গুরুত্বপূর্ণ হতে পারে।
একটি AI system-এর knowledge base-এ এমন তথ্য থাকতে পারে যা বর্তমান অবস্থায় সত্য, কিন্তু পরিস্থিতি পরিবর্তিত হলে সত্য নাও থাকতে পারে।
উদাহরণ:
«ব্যবহারকারী বর্তমানে অনলাইনে আছেন।»
এটি স্থায়ী logical truth নয়। ব্যবহারকারীর status পরিবর্তিত হলে proposition-টির truth value পরিবর্তিত হতে পারে।
Contingency ও Critical Thinking
Critical thinking-এর ক্ষেত্রে কোনো দাবিকে necessary truth ধরে নেওয়ার আগে প্রশ্ন করা গুরুত্বপূর্ণ:
দাবিটি কি logical necessity?
নাকি এটি empirical fact?
কোন evidence-এর ওপর দাবিটি নির্ভর করছে?
পরিস্থিতি পরিবর্তিত হলে দাবিটি কি মিথ্যা হতে পারে?
এর বিপরীতটি logically impossible কি?
নাকি শুধু বর্তমানে সত্য?
এই প্রশ্নগুলো reasoning-কে আরও পরিষ্কার করতে সাহায্য করে।
Contingency ও Argument
একটি argument-এর premise বা conclusion contingent হতে পারে।
উদাহরণ:
«আজ বৃষ্টি হচ্ছে। বৃষ্টি হলে রাস্তা ভেজে। অতএব, রাস্তা ভেজা।»
প্রথম premise একটি contingent factual statement হতে পারে।
কিন্তু argument-এর validity আলাদা বিষয়।
অর্থাৎ:
Premise contingent হতে পারে।
Conclusion contingent হতে পারে।
Argument valid বা invalid হওয়া আলাদা প্রশ্ন।
Contingency ও Validity
Contingency এবং validity একই ধারণা নয়।
একটি proposition contingent হতে পারে, কিন্তু একটি argument valid বা invalid হওয়ার বিষয়টি argument-এর logical structure-এর সঙ্গে সম্পর্কিত।
উদাহরণ:
P → Q
P
∴ Q
এটি একটি valid argument form।
এখানে P বা Q বাস্তবে contingent proposition হলেও argument-এর validity পরিবর্তন হয় না।
Contingency ও Soundness
Soundness-এর জন্য argument valid হতে হবে এবং তার premises সত্য হতে হবে।
Premise যদি contingent হয়, তবুও তা সত্য হতে পারে।
তাই কোনো premise contingent হওয়া argument-কে unsound করে না।
প্রধান প্রশ্ন হলো:
Premise সত্য কি?
Argument valid কি?
Contingency ও Contradiction
Contingency এবং contradiction একে অপরের বিপরীত logical status-এর উদাহরণ হতে পারে।
Contradiction:
P ∧ ¬P
সব সম্ভাব্য valuation-এ False।
Contingency:
P ∧ Q
কিছু valuation-এ True এবং কিছু valuation-এ False।
Contingency ও Consistency
একটি set of propositions consistent হতে পারে যদিও তার সদস্যদের মধ্যে contingent proposition থাকে।
উদাহরণ:
P = «আজ বৃষ্টি হচ্ছে।»
Q = «আজ ঠান্ডা পড়েছে।»
P এবং Q একসঙ্গে সত্য হওয়া সম্ভব হলে তাদের conjunction:
P ∧ Q
consistent হতে পারে।
তবে consistency এবং contingency একই ধারণা নয়।
Contingency নির্ণয়ের সহজ নিয়ম
একটি propositional formula-এর ক্ষেত্রে:
সব row-তে True → Tautology
সব row-তে False → Contradiction
কিছু True এবং কিছু False → Contingency
এটি truth table বিশ্লেষণের একটি গুরুত্বপূর্ণ নিয়ম।
উদাহরণসমূহ
উদাহরণ ১
P
যদি P একটি সাধারণ atomic proposition হয়, তাহলে P contingent হতে পারে।
কারণ P True বা False—দুই অবস্থাই সম্ভব।
উদাহরণ ২
P ∧ Q
এটি contingent।
কারণ কিছু valuation-এ True এবং কিছু valuation-এ False।
উদাহরণ ৩
P ∨ Q
এটিও সাধারণভাবে contingent।
শুধু P এবং Q উভয়ই False হলে এটি False; অন্য অনেক অবস্থায় True।
উদাহরণ ৪
P → Q
এটি contingent।
কারণ P=True এবং Q=False হলে এটি False, অন্য অনেক valuation-এ True।
Contingency-এর গুরুত্ব
Contingency ধারণাটি গুরুত্বপূর্ণ কারণ এটি আমাদের বুঝতে সাহায্য করে যে সব সত্য একই ধরনের নয়।
কিছু truth:
logical necessity-এর কারণে সত্য
কিছু বাস্তব জগতের তথ্যের কারণে সত্য
কিছু নির্দিষ্ট assumptions-এর ওপর নির্ভরশীল
কিছু পরিস্থিতি পরিবর্তনের সঙ্গে পরিবর্তিত হতে পারে
এই পার্থক্য দর্শন, যুক্তিবিদ্যা, গণিত এবং বিজ্ঞানের reasoning-এ গুরুত্বপূর্ণ।
দৈনন্দিন জীবনে Contingency
দৈনন্দিন জীবনের অনেক বক্তব্য contingent।
যেমন:
«আজ বাস সময়মতো এসেছে।»
এটি একটি নির্দিষ্ট দিনের ঘটনা।
অন্যদিন বাস দেরিতে আসতে পারে।
আরেকটি উদাহরণ:
«আজ পরীক্ষায় প্রশ্নটি সহজ ছিল।»
এটি নির্দিষ্ট অভিজ্ঞতার ওপর নির্ভর করে এবং অন্য পরীক্ষায় ভিন্ন হতে পারে।
Contingency বোঝার সহজ উদাহরণ
ধরা যাক একটি বাক্সে একটি বল আছে।
আমরা বললাম:
«বলটি লাল।»
যদি বাস্তবে বলটি লাল হয়, proposition-টি সত্য।
কিন্তু বলটি নীল হলে proposition-টি মিথ্যা।
অর্থাৎ proposition-টির সত্যতা বাস্তব পরিস্থিতির ওপর নির্ভর করছে।
এটি contingency বোঝার একটি সহজ উপায়।
গুরুত্বপূর্ণ বৈশিষ্ট্য
একটি contingent proposition-এর প্রধান বৈশিষ্ট্য:
এটি সত্য হতে পারে।
এটি মিথ্যাও হতে পারে।
এটি logical tautology নয়।
এটি logical contradiction নয়।
এর truth value valuation বা পরিস্থিতির ওপর নির্ভর করতে পারে।
এটি necessity-এর বিপরীত ধারণার সঙ্গে সম্পর্কিত।
এটি possibility-এর সঙ্গে ঘনিষ্ঠভাবে সম্পর্কিত।
এটি modal logic-এ formalভাবে প্রকাশ করা যায়।
Contingency-এর প্রতীকী রূপ
Modal logic-এর একটি সাধারণ characterization:
◇P ∧ ◇¬P
অর্থাৎ:
P সম্ভব এবং P-এর negation-ও সম্ভব।
আরেকভাবে বলা যায়:
¬□P ∧ ¬□¬P
অর্থাৎ:
P necessary নয় এবং P-এর negation-ও necessary নয়।
তবে modal logic-এর নির্দিষ্ট system অনুযায়ী formal interpretation ভিন্ন হতে পারে।
Contingency-এর সঙ্গে সম্পর্কিত ধারণা
Contingency বুঝতে নিচের ধারণাগুলো গুরুত্বপূর্ণ:
Truth
Falsehood
Proposition
Tautology
Contradiction
Consistency
Necessity
Possibility
Validity
Soundness
Modal Logic
Truth Table
Logical Form
Tautology, Contradiction ও Contingency: তুলনা
বৈশিষ্ট্য
Tautology
Contradiction
Contingency
সব ক্ষেত্রে True
হ্যাঁ
না
না
সব ক্ষেত্রে False
না
হ্যাঁ
না
True ও False উভয় ফল
না
না
হ্যাঁ
Logical necessity
সাধারণত হ্যাঁ
অসম্ভবতার সঙ্গে সম্পর্কিত
না
Truth table
সব True
সব False
True + False
শেখার জন্য সংক্ষিপ্ত সূত্র
সহজভাবে মনে রাখার জন্য:
Tautology = সবসময় True
Contradiction = সবসময় False
Contingency = কখনো True, কখনো False
এই তিনটি ধারণা propositional logic-এর মৌলিক শ্রেণিবিভাগ বোঝার জন্য অত্যন্ত গুরুত্বপূর্ণ।
উপসংহার
Contingency বা আপতিকতা যুক্তিবিদ্যার একটি গুরুত্বপূর্ণ ধারণা, যা এমন proposition বা statement বোঝায় যার truth value সব সম্ভাব্য পরিস্থিতিতে একই থাকে না। কোনো ক্ষেত্রে এটি সত্য এবং অন্য ক্ষেত্রে মিথ্যা হতে পারে।
Tautology সবসময় সত্য এবং contradiction সবসময় মিথ্যা হলেও contingency এই দুইয়ের মাঝামাঝি logical status নির্দেশ করে। Truth table-এর মাধ্যমে contingency সহজে শনাক্ত করা যায়।
Modal logic-এ contingency-কে possibility এবং necessity-এর মাধ্যমে আরও আনুষ্ঠানিকভাবে প্রকাশ করা যায়। দর্শন, গণিত, বিজ্ঞান, computer science, programming এবং critical thinking—সব ক্ষেত্রেই এই ধারণা logical reasoning-এর প্রকৃতি বুঝতে সহায়তা করে।
অতএব, কোনো বক্তব্য সত্য হলেই সেটি necessary truth নয়। অনেক সত্যই বাস্তব পরিস্থিতি, তথ্য বা অবস্থার ওপর নির্ভরশীল। এই পার্থক্য বোঝাই contingency ধারণার অন্যতম গুরুত্বপূর্ণ শিক্ষা।
তথ্যসূত্র
Aristotle — Organon
George Boole — An Investigation of the Laws of Thought
Gottlob Frege — Begriffsschrift
Bertrand Russell and Alfred North Whitehead — Principia Mathematica
Irving M. Copi — Introduction to Logic
Patrick Hurley — A Concise Introduction to Logic
Stanford Encyclopedia of Philosophy — Logic and Modal Logic
Internet Encyclopedia of Philosophy — Logic
বিভিন্ন প্রামাণিক logic ও mathematical logic পাঠ্যপুস্তক
