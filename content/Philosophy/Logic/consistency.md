---
id: consistency
title: সামঞ্জস্য
tags:
  - দর্শন
  - যুক্তিবিদ্যা
  - যুক্তি
  - সামঞ্জস্য
  - গণিত
  - কম্পিউটার বিজ্ঞান
  - সমালোচনামূলক চিন্তা
related:
  - logic
  - contradiction
  - logical-truth
  - mathematical-logic
  - classical-logic
  - critical-thinking
---

# সামঞ্জস্য

## সংক্ষিপ্ত পরিচিতি

সামঞ্জস্য (Consistency) হলো এমন একটি বৈশিষ্ট্য যেখানে কোনো বক্তব্যসমষ্টি, যুক্তি, তত্ত্ব বা formal system-এর মধ্যে পরস্পরবিরোধী বক্তব্য বা logical contradiction থাকে না।

সহজভাবে বলা যায়, কোনো তথ্য বা দাবির সেটের বক্তব্যগুলো যদি একে অপরের সঙ্গে যৌক্তিকভাবে সংঘর্ষে না জড়ায়, তাহলে সেই সেটকে সামঞ্জস্যপূর্ণ বা consistent বলা যায়।

যুক্তিবিদ্যা, গণিত, দর্শন, কম্পিউটার বিজ্ঞান, database, formal verification এবং artificial intelligence-এ consistency একটি গুরুত্বপূর্ণ ধারণা।

---

## সামঞ্জস্যের মৌলিক ধারণা

ধরা যাক একটি তথ্যসমষ্টিতে বলা হয়েছে:

- P সত্য।
- Q সত্য।

যদি P এবং Q পরস্পরের সঙ্গে contradiction তৈরি না করে, তাহলে তথ্যসমষ্টিটি consistent হতে পারে।

অন্যদিকে যদি বলা হয়:

- P সত্য।
- P মিথ্যা।

তাহলে classical logic-এর দৃষ্টিতে এই তথ্যসমষ্টিতে contradiction রয়েছে এবং এটি inconsistent।

---

## Consistency ও Contradiction

Consistency এবং contradiction পরস্পরের সঙ্গে ঘনিষ্ঠভাবে সম্পর্কিত।

- Consistency = logical contradiction না থাকা
- Inconsistency = logical contradiction থাকা

উদাহরণ:

P = “আজ বৃষ্টি হচ্ছে।”

তথ্য:

- P

এটি একা consistent হতে পারে।

কিন্তু:

- P
- ¬P

একসঙ্গে গ্রহণ করলে contradiction তৈরি হয় এবং সেটটি inconsistent হয়ে যায়।

---

## Logical Consistency

Logical consistency হলো কোনো set of propositions-এর মধ্যে এমন কোনো contradiction না থাকা যা একই logical system-এর নিয়ম অনুযায়ী প্রকাশিত হয়।

একটি set Γ consistent হলে সাধারণভাবে এমন একটি interpretation বা model থাকার ধারণা ব্যবহৃত হয় যেখানে Γ-এর সব proposition একই সঙ্গে সত্য হতে পারে।

অর্থাৎ:

Γ ⊬ ⊥

এখানে ⊥ সাধারণত contradiction বা falsehood বোঝাতে ব্যবহৃত হয়।

---

## Inconsistency

Inconsistency হলো এমন একটি অবস্থা যেখানে কোনো logical system বা statement set-এর মধ্যে contradiction রয়েছে।

উদাহরণ:

1. সকল মানুষ মরণশীল।
2. সক্রেটিস মানুষ।
3. সক্রেটিস মরণশীল নয়।

যদি এই তিনটি বক্তব্য একই অর্থ ও context-এ সত্য হিসেবে গ্রহণ করা হয়, তাহলে সেটির মধ্যে inconsistency রয়েছে।

---

## Consistency ও Validity

Consistency এবং validity একই বিষয় নয়।

### Consistency

কোনো statement set-এর অভ্যন্তরীণ সামঞ্জস্য নিয়ে আলোচনা করে।

### Validity

কোনো argument-এর premises সত্য হলে conclusion মিথ্যা হওয়া সম্ভব কি না, তা নিয়ে আলোচনা করে।

একটি argument valid হতে পারে, কিন্তু তার premises বাস্তবে সত্য নাও হতে পারে।

আবার কোনো statement set consistent হতে পারে, কিন্তু সেটি কোনো নির্দিষ্ট conclusion প্রমাণ করে না।

---

## Consistency ও Soundness

Soundness-এর সঙ্গে consistency-এর সম্পর্ক রয়েছে, কিন্তু দুটি ধারণা এক নয়।

একটি deductive argument sound হতে হলে:

1. argument valid হতে হবে।
2. সব premise সত্য হতে হবে।

অন্যদিকে consistency মূলত বক্তব্যসমষ্টির মধ্যে contradiction আছে কি না তা নিয়ে আলোচনা করে।

---

## Syntactic Consistency

Syntactic consistency formal proof system-এর সঙ্গে সম্পর্কিত।

একটি formal theory syntactically consistent হলে সেই theory থেকে একই proposition এবং তার negation—দুটিই প্রমাণ করা যায় না।

প্রতীকীভাবে:

T ⊬ P

এবং

T ⊬ ¬P

একই proposition P-এর জন্য উভয়টি theorem হিসেবে derivable হওয়া উচিত নয়।

আরও সাধারণভাবে:

T ⊬ ⊥

অর্থাৎ theory থেকে contradiction derivable নয়।

---

## Semantic Consistency

Semantic consistency model-এর ধারণার সঙ্গে সম্পর্কিত।

যদি কোনো theory-এর জন্য অন্তত একটি model থাকে যেখানে theory-এর সব statement সত্য হয়, তাহলে সেই theory-কে satisfiable বলা যায়।

অনেক classical logical system-এ satisfiability এবং consistency-এর মধ্যে গভীর সম্পর্ক রয়েছে।

সহজভাবে:

> যদি এমন একটি interpretation পাওয়া যায় যেখানে সব statement একসঙ্গে সত্য হতে পারে, তাহলে statement set-টি সামঞ্জস্যপূর্ণ।

---

## Satisfiability

Satisfiability হলো কোনো logical formula বা formula set-এর জন্য এমন truth assignment বা model থাকা যাতে formula সত্য হয়।

উদাহরণ:

P ∨ Q

এটি satisfiable, কারণ P সত্য এবং Q মিথ্যা হলে formula সত্য হয়।

অন্যদিকে:

P ∧ ¬P

কোনো truth assignment-এই সত্য হয় না।

তাই এটি unsatisfiable এবং classical propositional logic-এ contradiction।

---

## Consistency ও Tautology

Tautology এমন একটি formula যা সব possible truth assignment-এ সত্য।

উদাহরণ:

P ∨ ¬P

এটি tautology।

Consistency কোনো formula সবসময় সত্য কি না তা বলে না। এটি মূলত contradiction বা incompatibility-এর বিষয়।

তাই tautology এবং consistency আলাদা ধারণা।

---

## Consistency ও Contingency

Contingent proposition কিছু ক্ষেত্রে সত্য এবং কিছু ক্ষেত্রে মিথ্যা হতে পারে।

উদাহরণ:

P ∧ Q

P এবং Q উভয় সত্য হলে formula সত্য।

কিন্তু consistency-এর জন্য formula-টি সবসময় সত্য হওয়া প্রয়োজন নেই। contradiction না থাকাই মূল বিষয়।

---

## Truth Table দ্বারা Consistency

ধরা যাক:

P = “বৃষ্টি হচ্ছে।”

Q = “রাস্তা ভেজা।”

Statement set:

- P
- Q

যদি এমন truth assignment থাকে যেখানে P এবং Q উভয় সত্য, তাহলে set-টি satisfiable এবং consistent।

অন্যদিকে:

- P
- ¬P

এর কোনো truth assignment নেই যেখানে উভয় statement একই সঙ্গে সত্য।

তাই এটি inconsistent।

---

## Classical Logic-এ Consistency

Classical logic-এ contradiction একটি গুরুত্বপূর্ণ সমস্যা।

যদি একটি classical theory-তে:

P

এবং

¬P

দুটিই derivable হয়, তাহলে theory-টি inconsistent।

Classical logic-এর principle of explosion-এর কারণে inconsistency গুরুতর পরিণতি তৈরি করতে পারে।

---

## Principle of Explosion

Classical logic-এ contradiction থেকে যেকোনো proposition derive করা সম্ভব হতে পারে।

প্রতীকীভাবে:

P, ¬P ⊢ Q

এখানে Q যেকোনো proposition হতে পারে।

এই বৈশিষ্ট্যের কারণে formal mathematical এবং logical systems-এ consistency বজায় রাখা অত্যন্ত গুরুত্বপূর্ণ।

---

## Mathematics-এ Consistency

গণিতের foundation-এর ক্ষেত্রে consistency একটি মৌলিক বিষয়।

একটি mathematical theory consistent হলে theory-এর axioms এবং rules ব্যবহার করে contradiction প্রমাণ করা যাবে না।

উদাহরণ:

যদি কোনো theory থেকে একই সঙ্গে:

P

এবং

¬P

প্রমাণ করা যায়, তাহলে theory-টি inconsistent।

Mathematical logic-এর একটি গুরুত্বপূর্ণ প্রশ্ন হলো বিভিন্ন formal system consistent কি না।

---

## Gödel ও Consistency

Kurt Gödel-এর incompleteness theorems formal mathematical systems সম্পর্কে consistency এবং provability বোঝার ক্ষেত্রে গভীর প্রভাব ফেলেছে।

বিশেষ করে দ্বিতীয় incompleteness theorem দেখায় যে নির্দিষ্ট শক্তিশালী ও যথেষ্ট expressive formal system নিজের consistency-এর একটি উপযুক্ত formal statement সাধারণভাবে নিজের ভেতর থেকে প্রমাণ করতে পারে না, যদি system-টি consistent হয়।

এটি mathematical foundations-এর ইতিহাসে একটি গুরুত্বপূর্ণ ফলাফল।

---

## Computer Science-এ Consistency

Computer science-এ consistency বিভিন্ন অর্থে ব্যবহৃত হয়।

এটি দেখা যায়:

- Formal verification
- Programming languages
- Type systems
- Database systems
- Distributed systems
- Automated reasoning
- Knowledge representation
- Artificial intelligence

একটি system-এর rules, states বা information পরস্পরের সঙ্গে সামঞ্জস্যপূর্ণ রাখা অনেক ক্ষেত্রে গুরুত্বপূর্ণ।

---

## Database Consistency

Database consistency বলতে বোঝায় database-এর data এবং integrity constraints নির্ধারিত নিয়ম মেনে চলছে কি না।

উদাহরণ:

একটি database rule বলছে:

> একজন শিক্ষার্থীর ID অবশ্যই unique হতে হবে।

যদি একই ID দুইজন ভিন্ন শিক্ষার্থীর জন্য ব্যবহৃত হয় এবং uniqueness constraint ভঙ্গ হয়, তাহলে database-এর consistency ক্ষতিগ্রস্ত হতে পারে।

---

## Distributed Systems-এ Consistency

Distributed system-এ একই data একাধিক server বা node-এ থাকতে পারে।

সেখানে consistency বলতে বিভিন্ন node-এ data-এর অবস্থা কীভাবে এবং কত দ্রুত সামঞ্জস্যপূর্ণ থাকবে, তা বোঝাতে পারে।

এখানে logical consistency-এর পাশাপাশি distributed-systems-এর নিজস্ব consistency models রয়েছে।

যেমন:

- Strong consistency
- Eventual consistency
- Causal consistency

এসব ধারণার অর্থ formal logic-এর consistency-এর সঙ্গে পুরোপুরি একই নয়।

---

## Artificial Intelligence-এ Consistency

Knowledge-based AI system-এ consistency গুরুত্বপূর্ণ।

ধরা যাক knowledge base-এ রয়েছে:

- “ঢাকা বাংলাদেশের রাজধানী।”
- “ঢাকা বাংলাদেশের রাজধানী নয়।”

একই context-এ উভয় তথ্য সত্য হিসেবে সংরক্ষণ করলে knowledge base-এ contradiction তৈরি হয়।

AI system-কে তখন information source, reliability, time এবং context বিবেচনা করে contradiction পরিচালনা করতে হতে পারে।

---

## Knowledge Base Consistency

একটি knowledge base consistent হলে তার stored facts এবং rules এমনভাবে সাজানো থাকে যাতে তাদের মধ্যে unwanted contradiction না থাকে।

উদাহরণ:

Fact:

Human(Socrates)

Rule:

∀x Human(x) → Mortal(x)

এগুলো একসঙ্গে consistent।

কিন্তু যদি knowledge base-এ একই সঙ্গে থাকে:

Mortal(Socrates)

এবং

¬Mortal(Socrates)

তাহলে contradiction তৈরি হয়।

---

## Paraconsistent Logic

Classical logic-এর বাইরে কিছু logical system contradiction থাকলেও reasoning চালিয়ে যাওয়ার সুযোগ দেয়।

Paraconsistent logic-এর উদ্দেশ্য হলো contradiction থাকলেই যেন system থেকে সব ধরনের proposition derive না হয়ে যায়।

এটি inconsistent information, knowledge representation এবং কিছু AI application-এর ক্ষেত্রে গুরুত্বপূর্ণ হতে পারে।

---

## Consistency Checking

কোনো logical system consistent কি না তা পরীক্ষা করার জন্য বিভিন্ন পদ্ধতি ব্যবহার করা যায়।

সাধারণভাবে:

1. Statements সংগ্রহ করা।
2. Statements-এর logical form নির্ধারণ করা।
3. Contradictory pairs শনাক্ত করা।
4. Rules প্রয়োগ করা।
5. কোনো contradiction derive হয় কি না পরীক্ষা করা।
6. প্রয়োজনে model বা truth assignment খোঁজা।

Formal system অনুযায়ী consistency checking-এর পদ্ধতি ভিন্ন হতে পারে।

---

## বাস্তব জীবনে Consistency

দৈনন্দিন জীবনে consistency বলতে কোনো ব্যক্তির বক্তব্য, তথ্য বা সিদ্ধান্তের মধ্যে সামঞ্জস্য বোঝাতে পারে।

উদাহরণ:

একজন ব্যক্তি সকালে বললেন:

> “আমি আজ স্কুলে যাব।”

পরে একই পরিস্থিতিতে বললেন:

> “আমি আজ স্কুলে যাব না।”

দুটি বক্তব্যের মধ্যে apparent contradiction রয়েছে।

তবে সময় বা context পরিবর্তিত হলে contradiction নাও হতে পারে।

তাই consistency বিচার করার সময় context গুরুত্বপূর্ণ।

---

## Consistency যাচাইয়ের প্রশ্ন

কোনো তথ্যসমষ্টি পরীক্ষা করার সময় প্রশ্ন করা যেতে পারে:

1. সব বক্তব্য একই context-এর কি?
2. কোনো বক্তব্য অন্যটির negation কি?
3. একই সময় বোঝানো হয়েছে কি?
4. কোনো assumption পরস্পরবিরোধী কি?
5. কোনো rule অন্য rule-এর সঙ্গে conflict করছে কি?
6. contradiction থেকে কোনো conclusion derive হচ্ছে কি?
7. তথ্যের উৎস বা সময় আলাদা কি?
8. ভাষার ambiguity-এর কারণে apparent contradiction তৈরি হয়েছে কি?

---

## Consistency-এর উদাহরণ

### উদাহরণ ১ — Consistent

- সব মানুষ মরণশীল।
- সক্রেটিস একজন মানুষ।
- সক্রেটিস মরণশীল।

এই বক্তব্যগুলো পরস্পরের সঙ্গে সামঞ্জস্যপূর্ণ।

### উদাহরণ ২ — Inconsistent

- সক্রেটিস মরণশীল।
- সক্রেটিস মরণশীল নয়।

একই context-এ উভয় বক্তব্য সত্য হলে contradiction তৈরি হয়।

### উদাহরণ ৩ — Context-এর কারণে contradiction নয়

- “আজ দোকান সকাল ৯টায় খোলা ছিল।”
- “আজ দোকান রাত ৯টায় বন্ধ ছিল।”

এগুলো পরস্পরবিরোধী নয়, কারণ সময় আলাদা।

---

## Consistency ও Critical Thinking

Critical thinking-এর ক্ষেত্রে consistency পরীক্ষা করা গুরুত্বপূর্ণ।

কোনো argument বা দাবি বিশ্লেষণের সময়:

- বক্তব্যগুলো পরস্পরের সঙ্গে সামঞ্জস্যপূর্ণ কি না
- conclusion premises-এর সঙ্গে conflict করছে কি না
- একই ব্যক্তি ভিন্ন সময়ে পরস্পরবিরোধী দাবি করছে কি না
- evidence-এর মধ্যে conflict আছে কি না

এসব পরীক্ষা করা যায়।

---

## Consistency ও Formal Verification

Software এবং hardware-এর correctness যাচাইয়ে formal methods ব্যবহার করা হয়।

System-এর:

- Rules
- States
- Constraints
- Specifications

পরস্পরের সঙ্গে সামঞ্জস্যপূর্ণ কি না তা পরীক্ষা করা যেতে পারে।

কোনো specification-এ contradiction থাকলে system-এর desired behavior নির্ধারণ করা কঠিন হতে পারে।

---

## Consistency-এর গুরুত্ব

Consistency গুরুত্বপূর্ণ কারণ এটি:

- contradiction শনাক্ত করতে সাহায্য করে
- reasoning নির্ভরযোগ্য করতে সাহায্য করে
- mathematical proof-এর ভিত্তি শক্তিশালী করে
- database integrity বজায় রাখতে সাহায্য করে
- AI knowledge base পরিচালনায় সহায়তা করে
- software verification সহজ করে
- critical thinking উন্নত করে
- formal systems বিশ্লেষণে সাহায্য করে

---

## গুরুত্বপূর্ণ পরিভাষা

| English | বাংলা |
|---|---|
| Consistency | সামঞ্জস্য |
| Inconsistency | অসামঞ্জস্য |
| Consistent | সামঞ্জস্যপূর্ণ |
| Inconsistent | অসামঞ্জস্যপূর্ণ |
| Contradiction | বিরোধ / স্ববিরোধ |
| Satisfiability | সন্তোষণীয়তা |
| Unsatisfiable | অসন্তোষণীয় |
| Logical Consistency | যৌক্তিক সামঞ্জস্য |
| Syntactic Consistency | বাক্যগত / প্রমাণগত সামঞ্জস্য |
| Semantic Consistency | অর্থগত সামঞ্জস্য |
| Theory | তত্ত্ব |
| Model | মডেল |
| Axiom | স্বতঃসিদ্ধ |
| Proof | প্রমাণ |
| Validity | বৈধতা |
| Soundness | সুপ্রতিষ্ঠিত বৈধতা |

---

## সংক্ষিপ্ত সারাংশ

সামঞ্জস্য (Consistency) হলো এমন একটি বৈশিষ্ট্য যেখানে কোনো statement set, theory বা formal system-এর মধ্যে পরস্পরবিরোধী logical বক্তব্য থাকে না।

Classical logic-এ:

P এবং ¬P

একসঙ্গে সত্য হিসেবে গ্রহণ করলে contradiction এবং inconsistency তৈরি হয়।

Consistency mathematics, logic, computer science, databases, AI, formal verification এবং critical thinking-এর একটি গুরুত্বপূর্ণ ধারণা।

---

## উপসংহার

সামঞ্জস্য বা Consistency যুক্তিবিদ্যার অন্যতম গুরুত্বপূর্ণ ধারণা। এটি কোনো বক্তব্যসমষ্টি বা formal system-এর মধ্যে logical conflict আছে কি না তা বোঝার জন্য ব্যবহৃত হয়।

একটি consistent system-এ এমন contradiction থাকা উচিত নয় যা তার logical rules-এর মাধ্যমে প্রমাণ করা যায়। গণিতের foundations থেকে শুরু করে database, software verification এবং AI knowledge representation পর্যন্ত consistency গুরুত্বপূর্ণ ভূমিকা পালন করে।

তবে বিভিন্ন ক্ষেত্রে “consistency” শব্দটির নির্দিষ্ট অর্থ ভিন্ন হতে পারে। Formal logic-এ এটি contradiction ও satisfiability-এর সঙ্গে সম্পর্কিত, আর distributed systems বা databases-এ consistency ভিন্ন technical অর্থে ব্যবহৃত হতে পারে।

---

## তথ্যসূত্র

- Aristotle — Organon
- George Boole — An Investigation of the Laws of Thought
- Gottlob Frege — Begriffsschrift
- Bertrand Russell and Alfred North Whitehead — Principia Mathematica
- Kurt Gödel — On Formally Undecidable Propositions of Principia Mathematica and Related Systems
- Stanford Encyclopedia of Philosophy — Consistency
- Encyclopaedia Britannica — Logic
