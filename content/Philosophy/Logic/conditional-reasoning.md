---
id: conditional-reasoning
title: শর্তাধীন যুক্তি
tags:
  - দর্শন
  - যুক্তিবিদ্যা
  - যুক্তি
  - শর্তাধীন যুক্তি
  - অনুমান
  - Formal Logic
  - Propositional Logic
  - Deductive Reasoning
  - Conditional Logic
  - Critical Thinking
related:
  - logic
  - deductive-reasoning
  - direct-inference
  - indirect-inference
  - proposition
  - inference
  - implication
  - logical-consequence
  - propositional-logic
---

# শর্তাধীন যুক্তি

## সংক্ষিপ্ত পরিচিতি

শর্তাধীন যুক্তি (Conditional Reasoning) হলো এমন এক ধরনের যুক্তিনির্ভর চিন্তা ও অনুমান যেখানে একটি ঘটনা, বক্তব্য বা সিদ্ধান্তকে অন্য একটি শর্তের সঙ্গে সম্পর্কিত করে বিশ্লেষণ করা হয়। সাধারণত এখানে “যদি... তবে...” ধরনের কাঠামো ব্যবহৃত হয়।

উদাহরণ:

«যদি বৃষ্টি হয়, তবে রাস্তা ভিজবে।
বৃষ্টি হচ্ছে।
অতএব, রাস্তা ভিজবে।»

এখানে “বৃষ্টি হওয়া” হলো শর্ত এবং “রাস্তা ভেজা” হলো সেই শর্তের ফল।

শর্তাধীন যুক্তি দর্শন, যুক্তিবিদ্যা, গণিত, কম্পিউটার বিজ্ঞান, প্রোগ্রামিং, আইন, বিজ্ঞান এবং দৈনন্দিন সিদ্ধান্ত গ্রহণে গুরুত্বপূর্ণ ভূমিকা পালন করে।

---

## শর্তাধীন যুক্তির ধারণা

শর্তাধীন যুক্তির মূল কাঠামো হলো:

«যদি P হয়, তবে Q হবে।»

প্রতীকীভাবে:

P → Q

এখানে:

- P = পূর্বশর্ত (Antecedent)
- Q = ফলশর্ত (Consequent)
- → = শর্তাধীন সম্পর্ক বা Implication

উদাহরণ:

P = বৃষ্টি হচ্ছে।
Q = রাস্তা ভেজা।

তাহলে:

P → Q

অর্থ:

«যদি বৃষ্টি হয়, তবে রাস্তা ভেজা হবে।»

---

## পূর্বশর্ত ও ফলশর্ত

একটি conditional proposition সাধারণত দুটি অংশ নিয়ে গঠিত।

### পূর্বশর্ত

Antecedent হলো “যদি” অংশ।

উদাহরণ:

«যদি বিদ্যুৎ চলে যায়, তবে কম্পিউটার বন্ধ হবে।»

এখানে:

«বিদ্যুৎ চলে যায়»

হলো antecedent।

### ফলশর্ত

Consequent হলো “তবে” অংশ।

উপরের উদাহরণে:

«কম্পিউটার বন্ধ হবে»

হলো consequent।

---

## Conditional Proposition

Conditional proposition হলো এমন একটি proposition যেখানে একটি বক্তব্যকে অন্য একটি বক্তব্যের শর্ত হিসেবে প্রকাশ করা হয়।

সাধারণ কাঠামো:

P → Q

পড়া যায়:

«যদি P হয়, তবে Q।»

উদাহরণ:

P = একজন শিক্ষার্থী নিয়মিত পড়াশোনা করে।

Q = তার পরীক্ষায় ভালো করার সম্ভাবনা বৃদ্ধি পায়।

তাহলে:

P → Q

এটি একটি conditional relationship প্রকাশ করে।

তবে বাস্তব জীবনে এমন সম্পর্কের ক্ষেত্রে “P হলে Q অবশ্যই ঘটবে” এবং “P হলে Q ঘটার সম্ভাবনা বেশি”—এই দুই বিষয় আলাদা করে বিবেচনা করা গুরুত্বপূর্ণ।

---

## Material Implication

Classical propositional logic-এ P → Q-কে সাধারণত material implication হিসেবে বিশ্লেষণ করা হয়।

এর truth condition হলো:

P → Q

শুধু তখনই মিথ্যা যখন:

P সত্য এবং Q মিথ্যা।

অন্য সব ক্ষেত্রে এটি সত্য।

Truth table:

| P | Q | P → Q |
|---|---|---|
| সত্য | সত্য | সত্য |
| সত্য | মিথ্যা | মিথ্যা |
| মিথ্যা | সত্য | সত্য |
| মিথ্যা | মিথ্যা | সত্য |

Material implication-কে প্রতীকীভাবে এভাবেও লেখা যায়:

P → Q ≡ ¬P ∨ Q

অর্থাৎ “P হলে Q” এবং “P নয় অথবা Q”—এই দুটি classical propositional logic-এ truth-functionalভাবে সমতুল্য।

---

## Modus Ponens

শর্তাধীন যুক্তির অন্যতম গুরুত্বপূর্ণ valid inference rule হলো Modus Ponens।

কাঠামো:

P → Q  
P  
∴ Q

উদাহরণ:

«যদি আজ বৃষ্টি হয়, তবে রাস্তা ভিজবে।
আজ বৃষ্টি হচ্ছে।
অতএব, রাস্তা ভিজবে।»

এটি একটি valid deductive inference।

---

## Modus Tollens

আরেকটি গুরুত্বপূর্ণ valid inference rule হলো Modus Tollens।

কাঠামো:

P → Q  
¬Q  
∴ ¬P

উদাহরণ:

«যদি বিদ্যুৎ থাকে, তবে বাতি জ্বলবে।
বাতি জ্বলছে না।
অতএব, বিদ্যুৎ নেই।»

এই উদাহরণটি তখনই শক্তিশালী হবে যখন “বিদ্যুৎ থাকলে বাতি অবশ্যই জ্বলবে” এবং অন্য কোনো কারণে বাতি না জ্বলার সম্ভাবনা নেই—এমন শর্ত অনুমান করা হয়।

---

## Affirming the Consequent

Affirming the Consequent একটি সাধারণ logical fallacy।

কাঠামো:

P → Q  
Q  
∴ P

এটি সাধারণভাবে valid নয়।

উদাহরণ:

«যদি বৃষ্টি হয়, তবে রাস্তা ভিজবে।
রাস্তা ভেজা।
অতএব, বৃষ্টি হয়েছে।»

এখানে রাস্তা ভেজার অন্য কারণ থাকতে পারে। তাই শুধু রাস্তা ভেজা দেখে বৃষ্টি হয়েছে বলে নিশ্চিত সিদ্ধান্ত নেওয়া যায় না।

---

## Denying the Antecedent

Denying the Antecedent-ও একটি invalid inference pattern।

কাঠামো:

P → Q  
¬P  
∴ ¬Q

উদাহরণ:

«যদি বৃষ্টি হয়, তবে রাস্তা ভিজবে।
বৃষ্টি হচ্ছে না।
অতএব, রাস্তা ভেজা নয়।»

এটি নিশ্চিতভাবে সঠিক নয়, কারণ অন্য কোনো কারণে রাস্তা ভিজে থাকতে পারে।

---

## Necessary ও Sufficient Condition

Conditional reasoning-এ necessary এবং sufficient condition গুরুত্বপূর্ণ ধারণা।

যদি:

P → Q

তাহলে P হলো Q-এর sufficient condition।

অর্থাৎ P সত্য হলে Q সত্য হওয়ার জন্য এই শর্তটি যথেষ্ট।

অন্যদিকে Q হলো P-এর necessary condition।

অর্থাৎ P সত্য হলে Q সত্য হওয়া প্রয়োজন।

উদাহরণ:

«যদি কোনো সংখ্যা 4 দ্বারা বিভাজ্য হয়, তবে সংখ্যাটি জোড়।»

এখানে:

- 4 দ্বারা বিভাজ্য হওয়া = জোড় হওয়ার sufficient condition
- জোড় হওয়া = 4 দ্বারা বিভাজ্য হওয়ার necessary condition নয়

কারণ 2, 6, 8 ইত্যাদি জোড় সংখ্যা হলেও সবগুলো 4 দ্বারা বিভাজ্য নয়।

---

## Biconditional

দুইটি conditional relationship একসঙ্গে থাকলে biconditional তৈরি হতে পারে।

P ↔ Q

এর অর্থ:

«P তখনই এবং কেবল তখনই Q।»

এটি সাধারণভাবে:

(P → Q) ∧ (Q → P)

এর সমতুল্য।

উদাহরণ:

«একটি পূর্ণসংখ্যা জোড় তখনই এবং কেবল তখনই যখন সেটি 2 দ্বারা নিঃশেষে বিভাজ্য।»

এখানে দুই দিকের সম্পর্কই প্রতিষ্ঠিত।

---

## Conditional Reasoning ও Deduction

শর্তাধীন যুক্তি deductive reasoning-এর সঙ্গে ঘনিষ্ঠভাবে সম্পর্কিত।

যদি কোনো conditional rule এবং সেই rule-এর প্রয়োজনীয় তথ্য জানা থাকে, তাহলে logical inference-এর মাধ্যমে conclusion তৈরি করা যায়।

উদাহরণ:

P → Q  
P  
∴ Q

এখানে conclusion সরাসরি premises থেকে অনুসরণ করে।

---

## Conditional Reasoning ও দৈনন্দিন জীবন

দৈনন্দিন জীবনে মানুষ নিয়মিত conditional reasoning ব্যবহার করে।

উদাহরণ:

- যদি বৃষ্টি হয়, ছাতা নেব।
- যদি পড়াশোনা শেষ হয়, তারপর খেলব।
- যদি ফোনের চার্জ কম থাকে, চার্জে দেব।
- যদি পরীক্ষায় ভালো করতে চাই, নিয়মিত অনুশীলন করব।
- যদি রাস্তা বন্ধ থাকে, বিকল্প পথ ব্যবহার করব।

এই ধরনের reasoning মানুষের পরিকল্পনা ও সিদ্ধান্ত গ্রহণে সহায়তা করে।

---

## Conditional Reasoning ও গণিত

গণিতে theorem, definition এবং proof-এর ক্ষেত্রে conditional reasoning ব্যাপকভাবে ব্যবহৃত হয়।

উদাহরণ:

«যদি n একটি জোড় পূর্ণসংখ্যা হয়, তবে n² জোড়।»

প্রতীকীভাবে:

n is even → n² is even

যদি:

n = 2k

তাহলে:

n² = (2k)² = 4k² = 2(2k²)

অতএব, n² জোড়।

---

## Conditional Reasoning ও Programming

Programming-এ conditional reasoning অত্যন্ত গুরুত্বপূর্ণ।

যেমন:

```text
if condition:
    execute_action
এখানে condition সত্য হলে একটি নির্দিষ্ট action সম্পাদিত হয়।
উদাহরণ:
if age >= 18:
    allow_access
else:
    deny_access
এখানে program একটি logical condition পরীক্ষা করে এবং condition-এর ফলের ভিত্তিতে সিদ্ধান্ত গ্রহণ করে।
Conditional Reasoning ও Boolean Logic
Boolean logic-এ conditional relationship বিভিন্ন logical operation ব্যবহার করে প্রকাশ করা যায়।
Material implication:
P → Q
এবং:
¬P ∨ Q
classical propositional logic-এ truth-functionalভাবে সমতুল্য।
এই সম্পর্ক computer science এবং digital logic-এর বিভিন্ন ক্ষেত্রে গুরুত্বপূর্ণ।
Conditional Reasoning ও Database
Database query-তেও conditional reasoning ব্যবহৃত হয়।
উদাহরণ:
WHERE age >= 18 AND country = "Bangladesh"
এখানে database নির্দিষ্ট শর্ত পূরণ করা records নির্বাচন করে।
আরও সাধারণভাবে:
IF condition THEN result
ধরনের কাঠামো data processing এবং rule-based systems-এ ব্যবহৃত হয়।
Conditional Reasoning ও Artificial Intelligence
Artificial Intelligence-এর বিভিন্ন rule-based system-এ conditional reasoning গুরুত্বপূর্ণ।
উদাহরণ:
IF temperature > threshold
THEN activate_cooling
এখানে একটি condition পূরণ হলে system একটি নির্দিষ্ট action গ্রহণ করে।
Knowledge representation এবং expert system-এ এই ধরনের rule-based reasoning ঐতিহাসিকভাবে গুরুত্বপূর্ণ।
তবে আধুনিক AI-এর সব system শুধুমাত্র conditional rules-এর ওপর নির্ভর করে না। Machine learning এবং probabilistic methods-ও ব্যাপকভাবে ব্যবহৃত হয়।
Conditional Reasoning ও বিজ্ঞান
বৈজ্ঞানিক গবেষণায় conditional statement hypothesis এবং prediction তৈরিতে ব্যবহৃত হতে পারে।
উদাহরণ:
«যদি কোনো নির্দিষ্ট শর্ত পরীক্ষামূলকভাবে সত্য হয়, তবে নির্দিষ্ট পর্যবেক্ষণ পাওয়ার প্রত্যাশা করা যেতে পারে।»
তবে একটি conditional prediction সত্য হওয়া এবং hypothesis সত্য হওয়া একই বিষয় নয়। বাস্তব বৈজ্ঞানিক সিদ্ধান্তের জন্য পর্যবেক্ষণ, পরীক্ষা, measurement এবং evidence প্রয়োজন।
Conditional Reasoning ও আইন
আইনি reasoning-এও শর্তাধীন কাঠামো ব্যবহৃত হয়।
উদাহরণ:
«যদি কোনো নির্দিষ্ট আইনি শর্ত পূরণ হয়, তবে সংশ্লিষ্ট আইন বা বিধান প্রযোজ্য হতে পারে।»
তবে বাস্তব আইনি সিদ্ধান্তে শুধু একটি conditional structure যথেষ্ট নয়। আইন, প্রমাণ, jurisdiction এবং নির্দিষ্ট পরিস্থিতি বিবেচনা করতে হয়।
Conditional Reasoning-এর সাধারণ ভুল
শর্তাধীন যুক্তিতে কিছু সাধারণ ভুল দেখা যায়:
Affirming the Consequent
Denying the Antecedent
Necessary ও sufficient condition গুলিয়ে ফেলা
Conditional statement-কে biconditional হিসেবে ধরে নেওয়া
বাস্তব কারণ-ফল সম্পর্ককে শুধু logical implication হিসেবে ধরে নেওয়া
প্রয়োজনীয় শর্তকে যথেষ্ট শর্ত মনে করা
পর্যাপ্ত শর্তকে প্রয়োজনীয় শর্ত মনে করা
Conditional Statement ও Causal Statement
“যদি P হয়, তবে Q” এবং “P, Q-এর কারণ”—এই দুই বক্তব্য এক নয়।
উদাহরণ:
«যদি বৃষ্টি হয়, তবে রাস্তা ভিজতে পারে।»
এটি একটি conditional relationship।
কিন্তু “বৃষ্টি রাস্তা ভেজার কারণ” হলো causal claim।
Logical implication নিজে থেকে causal relationship প্রমাণ করে না।
Conditional Reasoning বিশ্লেষণের পদ্ধতি
কোনো conditional argument বিশ্লেষণ করার সময় নিচের ধাপগুলো অনুসরণ করা যায়:
Conditional statement শনাক্ত করা।
Antecedent শনাক্ত করা।
Consequent শনাক্ত করা।
Premise ও conclusion আলাদা করা।
ব্যবহৃত inference rule শনাক্ত করা।
Argument valid কি না পরীক্ষা করা।
Necessary ও sufficient condition আলাদা করা।
কোনো fallacy রয়েছে কি না পরীক্ষা করা।
বাস্তব ক্ষেত্রে অতিরিক্ত assumptions রয়েছে কি না যাচাই করা।
প্রয়োজনে evidence দিয়ে conditional claim পরীক্ষা করা।
একটি সম্পূর্ণ উদাহরণ
ধরা যাক:
«যদি একজন শিক্ষার্থী নিয়মিত অনুশীলন করে, তবে তার দক্ষতা উন্নত হওয়ার সম্ভাবনা থাকে। রহমান নিয়মিত অনুশীলন করে। অতএব, রহমানের দক্ষতা উন্নত হওয়ার সম্ভাবনা রয়েছে।»
এখানে:
Conditional Premise
নিয়মিত অনুশীলন → দক্ষতা উন্নতির সম্ভাবনা
Second Premise
রহমান নিয়মিত অনুশীলন করে।
Conclusion
রহমানের দক্ষতা উন্নত হওয়ার সম্ভাবনা রয়েছে।
এখানে বাস্তব বক্তব্যটি deterministic না হয়ে probabilistic হওয়ায় conclusion-কে সম্ভাব্য সিদ্ধান্ত হিসেবে দেখা উচিত।
Conditional Reasoning-এর গুরুত্ব
শর্তাধীন যুক্তি গুরুত্বপূর্ণ কারণ এটি:
সিদ্ধান্ত গ্রহণকে কাঠামোবদ্ধ করে
জটিল reasoning বিশ্লেষণ করতে সাহায্য করে
mathematical proof-এ ব্যবহৃত হয়
programming-এর ভিত্তি তৈরি করে
Boolean logic বোঝাতে সাহায্য করে
database query-তে ব্যবহৃত হয়
rule-based AI system-এ ব্যবহৃত হয়
scientific hypothesis ও prediction বিশ্লেষণে সহায়তা করে
logical fallacy শনাক্ত করতে সাহায্য করে
critical thinking উন্নত করে
গুরুত্বপূর্ণ প্রতীক
প্রতীক
অর্থ
P
প্রথম proposition
Q
দ্বিতীয় proposition
¬P
P নয়
P → Q
যদি P, তবে Q
P ↔ Q
P তখনই এবং কেবল তখনই Q
∴
অতএব
∧
এবং
∨
অথবা
গুরুত্বপূর্ণ পরিভাষা
English
বাংলা
Conditional Reasoning
শর্তাধীন যুক্তি
Conditional Proposition
শর্তাধীন প্রস্তাব
Antecedent
পূর্বশর্ত
Consequent
ফলশর্ত
Implication
অনুবন্ধ / শর্তযুক্ত সম্পর্ক
Material Implication
বস্তুগত অনুবন্ধ
Modus Ponens
পূর্বশর্ত প্রতিষ্ঠার মাধ্যমে অনুমান
Modus Tollens
ফলশর্ত অস্বীকারের মাধ্যমে অনুমান
Necessary Condition
প্রয়োজনীয় শর্ত
Sufficient Condition
যথেষ্ট শর্ত
Biconditional
দ্বিশর্তীয় সম্পর্ক
Inference
অনুমিতি
Deduction
অবরোহী যুক্তি
Fallacy
যুক্তিদোষ
Causal Relation
কারণগত সম্পর্ক
Proposition
প্রস্তাবনা
Conclusion
উপসংহার
Premise
প্রতিজ্ঞা
Conditional Reasoning-এর সীমাবদ্ধতা
শর্তাধীন যুক্তি একটি শক্তিশালী reasoning framework হলেও এটি বাস্তবতার সব দিক নিজে থেকে নির্ধারণ করে না।
একটি formal conditional valid হতে পারে, কিন্তু তার premise বাস্তবে সত্য নাও হতে পারে।
উদাহরণ:
P → Q
P
∴ Q
এই inference structure valid হলেও P → Q এবং P বাস্তবে সত্য কি না, তা আলাদাভাবে যাচাই করতে হবে।
এছাড়া বাস্তব জগতে causal relationship, uncertainty, incomplete information এবং probabilistic behavior থাকতে পারে। তাই বাস্তব সিদ্ধান্ত গ্রহণে formal logic-এর পাশাপাশি evidence ও context বিবেচনা করা প্রয়োজন।
শর্তাধীন যুক্তি এবং সমালোচনামূলক চিন্তা
Critical thinking-এর ক্ষেত্রে conditional reasoning মানুষকে দাবি ও সিদ্ধান্তের মধ্যকার সম্পর্ক বিশ্লেষণ করতে সাহায্য করে।
কোনো conditional claim দেখলে প্রশ্ন করা যেতে পারে:
শর্তটি কী?
ফলাফল কী?
শর্তটি যথেষ্ট কি?
শর্তটি প্রয়োজনীয় কি?
বিপরীত উদাহরণ আছে কি?
conclusion কি premise থেকে অনুসরণ করে?
কোনো hidden assumption রয়েছে কি?
এটি logical implication নাকি causal claim?
বক্তব্যটি deterministic নাকি probabilistic?
প্রয়োজনীয় evidence কী?
উপসংহার
শর্তাধীন যুক্তি হলো এমন একটি গুরুত্বপূর্ণ reasoning পদ্ধতি যেখানে একটি শর্ত এবং তার সম্ভাব্য ফলাফলের মধ্যে যৌক্তিক সম্পর্ক বিশ্লেষণ করা হয়। “যদি... তবে...” কাঠামো এর অন্যতম মৌলিক রূপ।
Modus Ponens ও Modus Tollens-এর মতো valid inference rule থেকে শুরু করে Affirming the Consequent এবং Denying the Antecedent-এর মতো logical fallacy পর্যন্ত conditional reasoning যুক্তিবিদ্যার একটি গুরুত্বপূর্ণ অংশ।
গণিত, programming, database, computer science, artificial intelligence, বিজ্ঞান, আইন এবং দৈনন্দিন সিদ্ধান্ত গ্রহণে এর ব্যবহার রয়েছে। শর্তাধীন যুক্তি সঠিকভাবে বুঝতে পারলে argument-এর কাঠামো বিশ্লেষণ, logical error শনাক্ত এবং আরও সুসংগঠিতভাবে সিদ্ধান্ত গ্রহণ করা সহজ হয়।
তথ্যসূত্র
Aristotle — Organon
George Boole — An Investigation of the Laws of Thought
Gottlob Frege — Begriffsschrift
Bertrand Russell & Alfred North Whitehead — Principia Mathematica
Irving M. Copi — Introduction to Logic
Patrick J. Hurley — A Concise Introduction to Logic
Mathematical Logic এবং Propositional Logic-এর প্রাথমিক পাঠ্য
Formal Logic ও Critical Thinking-এর প্রামাণ্য শিক্ষাসামগ্রী
