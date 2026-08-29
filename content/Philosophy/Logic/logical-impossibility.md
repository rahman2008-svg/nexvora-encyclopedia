---
id: logical-impossibility
title: যৌক্তিক অসম্ভবতা
tags:
  - দর্শন
  - যুক্তিবিদ্যা
  - যুক্তি
  - যৌক্তিক অসম্ভবতা
  - Formal Logic
  - Propositional Logic
  - Predicate Logic
  - Modal Logic
  - গণিত
  - সমালোচনামূলক চিন্তা
related:
  - logic
  - proposition
  - logical-truth
  - contradiction
  - consistency
  - inconsistency
  - tautology
  - contingency
  - logical-equivalence
  - logical-necessity
  - logical-possibility
---

# যৌক্তিক অসম্ভবতা

## সংক্ষিপ্ত পরিচিতি

যৌক্তিক অসম্ভবতা (Logical Impossibility) হলো এমন একটি অবস্থা যেখানে কোনো proposition, statement বা ঘটনার সত্য হওয়া সংশ্লিষ্ট logical rules, definitions বা premises-এর সঙ্গে সামঞ্জস্যপূর্ণ নয়। অর্থাৎ কোনো বক্তব্যকে সত্য ধরে নেওয়ার চেষ্টা করলে সরাসরি contradiction বা যৌক্তিক বিরোধ সৃষ্টি হয়।

সহজভাবে বলা যায়, কোনো কিছু যদি **যুক্তির নিয়ম মেনে কোনোভাবেই সত্য হতে না পারে**, তাহলে সেটিকে যৌক্তিকভাবে অসম্ভব বলা হয়।

উদাহরণ:

> “একই সময়ে এবং একই অর্থে একটি বস্তু সম্পূর্ণভাবে A এবং A নয়।”

Classical logic-এর Law of Non-Contradiction অনুযায়ী এই ধরনের proposition সত্য হতে পারে না।

---

## যৌক্তিক অসম্ভবতার ধারণা

Logical impossibility মূলত কোনো proposition-এর সম্ভাব্য truth condition নিয়ে আলোচনা করে।

যদি এমন কোনো logically possible situation বা model না থাকে যেখানে একটি proposition সত্য হতে পারে, তাহলে proposition-টি logically impossible।

প্রতীকীভাবে একটি proposition `P`-এর logical impossibility প্রকাশ করা যায়:

```text
¬◇P
অথবা modal logic-এর ভাষায়:
□¬P
অর্থাৎ P সম্ভব নয়, অথবা P অবশ্যই মিথ্যা।
সহজ উদাহরণ
ধরা যাক:
P = একটি বস্তু একই সময়ে সম্পূর্ণ গোল এবং সম্পূর্ণ গোল নয়।
Classical logic-এর দৃষ্টিতে এটি contradiction তৈরি করে।
কারণ:
P ∧ ¬P
একটি proposition এবং তার negation একই সঙ্গে সত্য হতে পারে না।
তাই এই ধরনের statement logically impossible।
Logical Impossibility বনাম সাধারণ অসম্ভবতা
সব ধরনের অসম্ভবতা logical impossibility নয়।
কোনো ঘটনা বাস্তবে ঘটতে না পারলেও তা logically impossible নাও হতে পারে।
উদাহরণ:
“একজন মানুষ চাঁদে হাঁটছে।”
এটি কোনো নির্দিষ্ট সময় বা বাস্তব পরিস্থিতিতে অসম্ভব বা অত্যন্ত কঠিন হতে পারে, কিন্তু বক্তব্যটির মধ্যে নিজস্ব কোনো logical contradiction নেই।
অন্যদিকে:
“একটি ত্রিভুজের চারটি বাহু আছে।”
যদি “ত্রিভুজ” শব্দটির সংজ্ঞা তিন বাহুবিশিষ্ট বহুভুজ হিসেবে নির্ধারিত হয়, তাহলে এটি সংজ্ঞাগতভাবে contradiction তৈরি করে।
অতএব, logical impossibility এবং physical impossibility এক নয়।
Logical Impossibility এবং Contradiction
Logical impossibility-এর সঙ্গে contradiction-এর ঘনিষ্ঠ সম্পর্ক রয়েছে।
একটি proposition যদি এমন কোনো contradiction তৈরি করে যার কারণে সেটি কোনো possible interpretation-এ সত্য হতে পারে না, তাহলে সেটি logically impossible হতে পারে।
উদাহরণ:
P = P এবং P নয়
প্রতীকীভাবে:
P ∧ ¬P
Classical propositional logic-এ এই formula সব valuation-এর অধীনে মিথ্যা।
তাই এটি একটি contradiction এবং logically impossible proposition-এর উদাহরণ।
Logical Impossibility এবং Tautology
Tautology এবং logical impossibility একে অপরের বিপরীত ধারণা হিসেবে বোঝা যায়।
একটি tautology সব সম্ভাব্য truth assignment-এর অধীনে সত্য।
অন্যদিকে একটি contradiction সব সম্ভাব্য truth assignment-এর অধীনে মিথ্যা।
উদাহরণ:
P ∨ ¬P
এটি classical logic-এ tautology।
অন্যদিকে:
P ∧ ¬P
এটি contradiction।
তাই:
Tautology → সব ক্ষেত্রে সত্য
Contradiction → সব ক্ষেত্রে মিথ্যা
Contingency → কিছু ক্ষেত্রে সত্য, কিছু ক্ষেত্রে মিথ্যা
Truth Table-এর মাধ্যমে যৌক্তিক অসম্ভবতা
Propositional logic-এ truth table ব্যবহার করে কোনো formula logically impossible কি না পরীক্ষা করা যায়।
ধরা যাক:
P ∧ ¬P
Truth table:
P
¬P
P ∧ ¬P
True
False
False
False
True
False
শেষ কলামে সব ক্ষেত্রেই False পাওয়া যাচ্ছে।
অতএব:
P ∧ ¬P
একটি contradiction এবং classical propositional logic-এ logically impossible।
Logical Possibility-এর সঙ্গে সম্পর্ক
Logical possibility হলো কোনো proposition অন্তত একটি logically consistent situation-এ সত্য হতে পারার সম্ভাবনা।
যদি কোনো proposition-এর সত্য হওয়ার মতো একটি possible model থাকে, তাহলে সেটি logically possible।
অন্যদিকে যদি কোনো possible model-এই সেটি সত্য না হতে পারে, তাহলে সেটি logically impossible।
সহজভাবে:
Logical possibility:
অন্তত একটি সম্ভাব্য model-এ সত্য।

Logical impossibility:
কোনো সম্ভাব্য model-এ সত্য নয়।
Logical Necessity-এর সঙ্গে সম্পর্ক
Logical necessity হলো এমন একটি অবস্থা যেখানে proposition সব logically possible situation-এ সত্য।
Logical impossibility তার বিপরীত ধারণার সঙ্গে সম্পর্কিত।
যদি:
□P
দ্বারা বোঝানো হয় “P অবশ্যই সত্য”, তাহলে:
□¬P
বোঝায় “P অবশ্যই মিথ্যা”।
এক্ষেত্রে P logically impossible।
Formal Logic-এ Logical Impossibility
Formal logic-এ logical impossibility নির্ণয়ের জন্য syntax, semantics এবং inference rules ব্যবহার করা হয়।
কোনো formula-এর logical status বোঝার জন্য দেখা হয়:
Formula-এর structure
Truth conditions
Possible interpretations
Models
Valuations
Consistency
Contradiction
Inference rules
যদি কোনো interpretation বা model formula-টিকে সত্য করতে না পারে, তাহলে সেটি logically impossible হতে পারে।
Propositional Logic-এ যৌক্তিক অসম্ভবতা
Propositional logic-এ proposition-কে P, Q, R ইত্যাদি প্রতীক দিয়ে প্রকাশ করা হয়।
উদাহরণ:
P ∧ ¬P
এটি logically impossible।
আরেকটি উদাহরণ:
(P → Q) ∧ P ∧ ¬Q
এখানে:
P → Q
P
¬Q
একসঙ্গে সত্য হতে পারে না।
কারণ P সত্য হলে Q সত্য হতে হবে, কিন্তু একই সঙ্গে Q মিথ্যা বলা হচ্ছে।
তাই পুরো conjunction-টি inconsistent।
Predicate Logic-এ যৌক্তিক অসম্ভবতা
Predicate logic-এ object, property এবং relation-এর মাধ্যমে আরও জটিল logical impossibility প্রকাশ করা যায়।
উদাহরণ:
∃x (Human(x) ∧ ¬Human(x))
এর অর্থ:
“এমন অন্তত একজন x আছে যে একই সঙ্গে মানুষ এবং মানুষ নয়।”
Classical predicate logic-এ এটি logically impossible।
আরেকটি উদাহরণ:
∀x (P(x) → ¬P(x))
এটি নিজে সবসময় contradiction নয়; এটি নির্দিষ্ট domain ও additional premises-এর ওপর নির্ভর করতে পারে। তাই logical impossibility বিশ্লেষণের সময় পুরো formula এবং তার interpretation বিবেচনা করা গুরুত্বপূর্ণ।
সংজ্ঞাগত অসম্ভবতা
কোনো ধারণার সংজ্ঞার মধ্যেই যদি contradiction থাকে, তাহলে সেটি definitional বা conceptual impossibility তৈরি করতে পারে।
উদাহরণ:
“বিবাহিত অবিবাহিত ব্যক্তি”
যদি “বিবাহিত” এবং “অবিবাহিত” একই অর্থে পরস্পর বিরোধী property হিসেবে ব্যবহৃত হয়, তাহলে ধারণাটি contradiction তৈরি করে।
তবে প্রাকৃতিক ভাষায় শব্দের অর্থ context-এর ওপর নির্ভর করতে পারে। তাই formal analysis-এ definitions স্পষ্টভাবে নির্ধারণ করা গুরুত্বপূর্ণ।
গাণিতিক যুক্তিতে যৌক্তিক অসম্ভবতা
গণিতের proof এবং formal systems-এ contradiction গুরুত্বপূর্ণ ভূমিকা পালন করে।
ধরা যাক:
P
¬P
দুটি premise একসঙ্গে গ্রহণ করা হয়েছে।
Classical logic-এ এগুলো পরস্পরবিরোধী।
Proof by contradiction-এর ক্ষেত্রে কোনো proposition-এর negation ধরে নিয়ে contradiction পাওয়া গেলে সেই proposition প্রতিষ্ঠার চেষ্টা করা হয়।
এখানে contradiction একটি গুরুত্বপূর্ণ reasoning technique।
Proof by Contradiction
Proof by contradiction বা বিরোধের মাধ্যমে প্রমাণ একটি গুরুত্বপূর্ণ mathematical reasoning method।
সাধারণ কাঠামো:
যে proposition প্রমাণ করতে হবে তার বিপরীত ধরে নেওয়া।
সেই assumption থেকে logical consequence বের করা।
contradiction পাওয়া।
contradiction-এর কারণে original assumption প্রত্যাখ্যান করা।
কাঙ্ক্ষিত proposition প্রতিষ্ঠা করা।
প্রতীকীভাবে:
Assume ¬P
↓
Logical consequences
↓
Contradiction
↓
Therefore P
তবে নির্দিষ্ট proof system ও logic-এর ধরন অনুযায়ী এই পদ্ধতির বৈধতা ও ব্যাখ্যা ভিন্ন হতে পারে।
Consistency এবং Logical Impossibility
Consistency হলো কোনো set of statements-এর মধ্যে contradiction না থাকার বৈশিষ্ট্য।
যদি একটি theory-তে এমন statement থাকে যার ফলে একই proposition এবং তার negation উভয়ই প্রতিষ্ঠিত হয়, তাহলে theory-টি inconsistent হতে পারে।
উদাহরণ:
P
¬P
এখানে একই proposition সম্পর্কে বিরোধ রয়েছে।
অতএব, consistency পরীক্ষা করার সময় logical impossibility গুরুত্বপূর্ণ বিষয়।
Model-এর মাধ্যমে বোঝা
Model হলো এমন একটি interpretation যেখানে কোনো formal statement সত্য হতে পারে।
যদি কোনো theory-এর অন্তত একটি model থাকে, তাহলে সেটি সাধারণত satisfiable বা consistent হওয়ার গুরুত্বপূর্ণ প্রমাণ দেয়।
অন্যদিকে কোনো theory-এর কোনো model না থাকলে সেটি unsatisfiable।
সহজভাবে:
At least one model exists
→ Satisfiable

No model exists
→ Unsatisfiable
একটি formula logically impossible হলে সাধারণত সেটির কোনো satisfying model থাকে না।
Logical Impossibility বনাম Physical Impossibility
দুটি ধারণার পার্থক্য গুরুত্বপূর্ণ।
Logical Impossibility
যুক্তির নিয়ম বা সংজ্ঞার কারণে কোনো কিছু সম্ভব নয়।
উদাহরণ:
একই অর্থে P এবং not-P একসঙ্গে সত্য।
Physical Impossibility
প্রকৃতির পরিচিত নিয়মের কারণে কোনো ঘটনা সম্ভব নয় বা বাস্তবে ঘটতে পারে না।
উদাহরণ:
পরিচিত পদার্থবিজ্ঞানের নিয়ম অনুযায়ী কোনো massive object আলোর বেগে পৌঁছানো।
এখানে বক্তব্যটির logical structure নিজে contradiction নাও হতে পারে।
Logical Impossibility বনাম Practical Impossibility
কোনো কাজ বাস্তবে করা খুব কঠিন হলেও সেটি logically impossible নয়।
উদাহরণ:
একজন ব্যক্তি এক মুহূর্তে পৃথিবীর দুই ভিন্ন স্থানে একই অবস্থায় উপস্থিত।
এটি কীভাবে সংজ্ঞায়িত করা হচ্ছে তার ওপর physical বা practical সমস্যা থাকতে পারে। কিন্তু formal logic-এ statement-এর logical structure আলাদাভাবে পরীক্ষা করতে হয়।
তাই:
Difficult ≠ Impossible
Physically impossible ≠ Logically impossible
Logically impossible → কোনো consistent interpretation-এ সত্য নয়
Modal Logic-এ Logical Impossibility
Modal logic possibility এবং necessity নিয়ে কাজ করে।
সাধারণভাবে:
◇P
অর্থ:
P সম্ভব।
আর:
□P
অর্থ:
P অনিবার্যভাবে সত্য।
Logical impossibility প্রকাশ করা যায়:
¬◇P
অথবা সমতুল্য modal formulation:
□¬P
অর্থাৎ P কোনো possible world-এ সত্য নয়।
Possible World ধারণা
Modal logic-এ possible world ধারণা ব্যবহার করে possibility ও necessity ব্যাখ্যা করা হয়।
যদি কোনো proposition অন্তত একটি logically possible world-এ সত্য হয়, তাহলে সেটি logically possible।
যদি কোনো proposition কোনো possible world-এই সত্য না হয়, তাহলে সেটি logically impossible।
উদাহরণ:
P = P ∧ ¬P
Classical logical semantics-এ কোনো possible world-এ এটিকে সত্য করা যায় না।
অতএব এটি logically impossible।
Logical Impossibility এবং Contradictory Set
একটি statement-এর set যদি এমন হয় যে সব statement একসঙ্গে সত্য হতে পারে না, তাহলে সেটিকে inconsistent set বলা যায়।
উদাহরণ:
P
P → Q
¬Q
এখানে:
P সত্য।
P → Q সত্য।
তাই Q সত্য হওয়া উচিত।
কিন্তু ¬Q-ও সত্য বলা হয়েছে।
ফলে contradiction তৈরি হয়।
এই set-এর কোনো classical model নেই।
বাস্তব জীবনে যৌক্তিক অসম্ভবতা
দৈনন্দিন জীবনে logical impossibility শনাক্ত করা গুরুত্বপূর্ণ।
উদাহরণ:
“এই নিয়মে প্রত্যেক ব্যক্তি একই সঙ্গে সম্পূর্ণভাবে নির্বাচিত এবং নির্বাচিত নয়।”
যদি “নির্বাচিত” ও “নির্বাচিত নয়” একই অর্থে ব্যবহৃত হয়, তাহলে বক্তব্যে contradiction রয়েছে।
এ ধরনের contradiction শনাক্ত করা:
বিতর্ক বিশ্লেষণ
আইনগত যুক্তি
বৈজ্ঞানিক reasoning
নীতি নির্ধারণ
সমস্যা সমাধান
critical thinking
ইত্যাদিতে সহায়ক।
Programming-এ যৌক্তিক অসম্ভবতা
Programming-এ logical impossibility সাধারণত condition এবং state analysis-এর মাধ্যমে দেখা যেতে পারে।
উদাহরণ:
if age >= 18 and age < 10:
    access = true
একই integer age-এর জন্য age >= 18 এবং age < 10 একই সঙ্গে সত্য হতে পারে না।
তাই condition-টি unsatisfiable।
এ ধরনের condition শনাক্ত করলে:
Dead code শনাক্ত করা যায়
Validation উন্নত করা যায়
Bugs কমানো যায়
Program logic পরীক্ষা করা যায়
Formal verification সহজ হয়
Database-এ যৌক্তিক অসম্ভবতা
Database query-তেও contradictory conditions থাকতে পারে।
উদাহরণ:
age > 50 AND age < 10
সাধারণ সংখ্যাগত অর্থে কোনো একটি age একই সঙ্গে ৫০-এর বেশি এবং ১০-এর কম হতে পারে না।
তাই query condition-টি unsatisfiable হতে পারে।
Database optimization-এ এমন condition শনাক্ত করা query planning-এর জন্য উপকারী।
Artificial Intelligence-এ যৌক্তিক অসম্ভবতা
AI-এর knowledge representation system-এ contradictory knowledge শনাক্ত করা গুরুত্বপূর্ণ।
উদাহরণ:
Human(Rahman)
¬Human(Rahman)
একই knowledge base-এ যদি উভয় statement থাকে, তাহলে contradiction তৈরি হয়।
Logic-based AI system-এ consistency checking, automated reasoning এবং knowledge validation-এর ক্ষেত্রে এই ধরনের সমস্যা গুরুত্বপূর্ণ।
তবে আধুনিক AI-এর সব system classical logic ব্যবহার করে না। Machine learning-based system-এ logical impossibility-এর ধারণা ভিন্নভাবে প্রয়োগ হতে পারে।
Logical Impossibility শনাক্ত করার পদ্ধতি
কোনো proposition logically impossible কি না পরীক্ষা করার জন্য কয়েকটি পদ্ধতি ব্যবহার করা যায়:
১. Contradiction পরীক্ষা
দেখতে হবে proposition-টি কি নিজের সঙ্গে বা অন্য premise-এর সঙ্গে contradiction তৈরি করছে।
২. Truth Table
Propositional logic-এর formula-এর সব truth assignment পরীক্ষা করা যায়।
৩. Formal Derivation
Rules of inference ব্যবহার করে contradiction derive করা যায় কি না দেখা যায়।
৪. Model Checking
কোনো satisfying model রয়েছে কি না পরীক্ষা করা যায়।
৫. Satisfiability Testing
Formula satisfiable কি না পরীক্ষা করা যায়।
যদি formula unsatisfiable হয়, তাহলে সেটি logically impossible হওয়ার শক্তিশালী নির্দেশনা দেয়।
Logical Status-এর সঙ্গে সম্পর্ক
একটি proposition-এর logical status বিভিন্নভাবে শ্রেণিবদ্ধ করা যায়:
Logical Status
বৈশিষ্ট্য
Tautology
সব ক্ষেত্রে সত্য
Contradiction
সব ক্ষেত্রে মিথ্যা
Contingency
কিছু ক্ষেত্রে সত্য, কিছু ক্ষেত্রে মিথ্যা
Logical Necessity
সব logically possible situation-এ সত্য
Logical Possibility
অন্তত একটি logically possible situation-এ সত্য
Logical Impossibility
কোনো logically possible situation-এ সত্য নয়
এই শ্রেণিবিভাগ formal reasoning বোঝার জন্য গুরুত্বপূর্ণ।
গুরুত্বপূর্ণ পার্থক্য
Logical Impossibility বনাম Falsehood
একটি proposition মিথ্যা হওয়া এবং logically impossible হওয়া এক বিষয় নয়।
উদাহরণ:
“আজ ঢাকায় তুষারপাত হয়েছে।”
এটি কোনো নির্দিষ্ট দিনে মিথ্যা হতে পারে, কিন্তু statement-এর logical structure contradiction তৈরি করে না।
অন্যদিকে:
“একটি বর্গ একই অর্থে বর্গ এবং বর্গ নয়।”
এখানে contradiction রয়েছে।
Logical Impossibility বনাম Inconsistency
Logical impossibility সাধারণত কোনো proposition বা formula-এর logical status বোঝায়।
Inconsistency সাধারণত একটি set of propositions, theory বা assumptions-এর মধ্যে contradiction বোঝায়।
অর্থাৎ:
একটি formula impossible
এবং:
একটি theory inconsistent
দুটি সম্পর্কিত হলেও এক নয়।
Logical Impossibility-এর গুরুত্ব
Logical impossibility বোঝা গুরুত্বপূর্ণ কারণ এটি আমাদের:
contradiction শনাক্ত করতে
ভুল assumptions খুঁজে বের করতে
argument বিশ্লেষণ করতে
mathematical proof যাচাই করতে
formal system পরীক্ষা করতে
software condition বিশ্লেষণ করতে
database query উন্নত করতে
AI knowledge base যাচাই করতে
critical thinking উন্নত করতে
সহায়তা করে।
শিক্ষার্থীদের জন্য সহজ উদাহরণ
ধরা যাক:
P = আজ সোমবার।
তাহলে:
P ∧ ¬P
এর অর্থ দাঁড়ায়:
“আজ সোমবার এবং আজ সোমবার নয়।”
Classical logic-এ এটি একই সঙ্গে সত্য হতে পারে না।
তাই:
P ∧ ¬P
একটি logically impossible formula।
একটি পূর্ণাঙ্গ বিশ্লেষণ
ধরা যাক:
P = বৃষ্টি হচ্ছে।
Statement:
P ∧ ¬P
ধাপ ১: P-এর অর্থ
P = বৃষ্টি হচ্ছে।
ধাপ ২: ¬P-এর অর্থ
¬P = বৃষ্টি হচ্ছে না।
ধাপ ৩: AND ব্যবহার
P ∧ ¬P
এর অর্থ:
বৃষ্টি হচ্ছে এবং একই সঙ্গে বৃষ্টি হচ্ছে না।
ধাপ ৪: Truth value পরীক্ষা
যদি P = True হয়, তাহলে ¬P = False।
যদি P = False হয়, তাহলে ¬P = True।
কোনো ক্ষেত্রেই দুটো একসঙ্গে True হয় না।
সিদ্ধান্ত
P ∧ ¬P
একটি contradiction এবং classical propositional logic-এ logically impossible।
গুরুত্বপূর্ণ পরিভাষা
English
বাংলা
Logical Impossibility
যৌক্তিক অসম্ভবতা
Impossible
অসম্ভব
Contradiction
বিরোধ / স্ববিরোধ
Consistency
সামঞ্জস্য
Inconsistency
অসামঞ্জস্য
Tautology
টটোলজি
Contingency
আপতিক সত্যতা / আপতিকতা
Logical Possibility
যৌক্তিক সম্ভাবনা
Logical Necessity
যৌক্তিক অনিবার্যতা
Proposition
প্রস্তাব / বচন
Formula
সূত্র
Model
মডেল / ব্যাখ্যামূলক কাঠামো
Valuation
সত্যমূল্য নির্ধারণ
Satisfiable
সন্তোষজনক / সত্যায়নযোগ্য
Unsatisfiable
অসন্তোষজনক / সত্যায়ন-অসম্ভব
Negation
নাকরণ
Inference
অনুমিতি
Premise
প্রতিজ্ঞা
Conclusion
উপসংহার
যুক্তিবিদ্যায় যৌক্তিক অসম্ভবতার স্থান
যুক্তিবিদ্যার বৃহত্তর কাঠামোর মধ্যে logical impossibility-এর সম্পর্ক রয়েছে:
Logic
├── Proposition
├── Truth
├── Validity
├── Consistency
├── Contradiction
├── Tautology
├── Contingency
├── Logical Necessity
├── Logical Possibility
└── Logical Impossibility
এই ধারণাগুলো পরস্পরের সঙ্গে সম্পর্কিত এবং formal reasoning বোঝার জন্য একসঙ্গে অধ্যয়ন করা উপকারী।
উপসংহার
যৌক্তিক অসম্ভবতা হলো এমন একটি logical status যেখানে কোনো proposition কোনো logically consistent পরিস্থিতিতে সত্য হতে পারে না। সাধারণত contradiction, incompatible conditions, inconsistent assumptions বা unsatisfiable formula-এর মাধ্যমে এই অবস্থা প্রকাশ পায়।
Logical impossibility বোঝার মাধ্যমে truth, contradiction, consistency, possibility এবং necessity-এর মধ্যে সম্পর্ক পরিষ্কারভাবে বোঝা যায়। এটি দর্শন ও যুক্তিবিদ্যার পাশাপাশি গণিত, computer science, programming, database, formal verification এবং artificial intelligence-এর বিভিন্ন ক্ষেত্রেও গুরুত্বপূর্ণ।
সবচেয়ে সহজভাবে বলা যায়:
যে বক্তব্য যুক্তির নিয়ম মেনে কোনো সম্ভাব্য অবস্থাতেই সত্য হতে পারে না, সেটিই যৌক্তিকভাবে অসম্ভব।
তথ্যসূত্র
Aristotle — Organon
George Boole — An Investigation of the Laws of Thought
Gottlob Frege — Begriffsschrift
Bertrand Russell ও Alfred North Whitehead — Principia Mathematica
Irving M. Copi — Introduction to Logic
Graham Priest — Logic: A Very Short Introduction
Patrick J. Hurley — A Concise Introduction to Logic
Stanford Encyclopedia of Philosophy — Logic
Stanford Encyclopedia of Philosophy — Modal Logic
Stanford Encyclopedia of Philosophy — Paraconsistent Logic
