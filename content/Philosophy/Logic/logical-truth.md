---
id: logical-truth
title: যৌক্তিক সত্য
tags:
  - যুক্তিবিদ্যা
  - দর্শন
  - যুক্তি
  - সত্য
  - প্রস্তাবনা
  - গাণিতিক যুক্তিবিদ্যা
  - গণিত
  - কম্পিউটার বিজ্ঞান
  - সমালোচনামূলক চিন্তা
related:
  - logic
  - proposition
  - truth-value
  - validity
  - mathematical-logic
  - critical-thinking
---

# যৌক্তিক সত্য

## সংক্ষিপ্ত পরিচিতি

যৌক্তিক সত্য (Logical Truth) হলো এমন একটি proposition বা logical statement, যা তার যৌক্তিক কাঠামোর কারণে সব সম্ভাব্য উপযুক্ত interpretation বা truth assignment-এর অধীনে সত্য থাকে।

অর্থাৎ কোনো নির্দিষ্ট ব্যক্তি, স্থান, সময় বা বাস্তব ঘটনার ওপর নির্ভর না করে যদি একটি logical expression তার কাঠামোর কারণে সর্বদা সত্য হয়, তাহলে তাকে যৌক্তিক সত্য বলা হয়।

যৌক্তিক সত্য যুক্তিবিদ্যার একটি গুরুত্বপূর্ণ ধারণা। এটি truth, proposition, tautology, validity, logical equivalence এবং formal reasoning বোঝার ক্ষেত্রে গুরুত্বপূর্ণ ভূমিকা পালন করে।

সহজভাবে বলা যায়, কোনো বক্তব্যের সত্যতা যদি তার logical structure থেকেই নিশ্চিত হয়, তাহলে সেটি logical truth-এর উদাহরণ হতে পারে।

---

## সূচিপত্র

1. যৌক্তিক সত্যের ধারণা
2. যৌক্তিক সত্যের বৈশিষ্ট্য
3. Proposition ও যৌক্তিক সত্য
4. Truth Value
5. Logical Form
6. Tautology
7. Contradiction
8. Contingent Proposition
9. Logical Validity
10. Logical Truth ও Validity-এর পার্থক্য
11. Classical Logic-এ যৌক্তিক সত্য
12. Propositional Logic-এ যৌক্তিক সত্য
13. Predicate Logic-এ যৌক্তিক সত্য
14. Truth Table
15. Logical Equivalence
16. Law of Identity
17. Law of Non-Contradiction
18. Law of Excluded Middle
19. Necessary Truth
20. Analytic Truth
21. A Priori Truth
22. Logical Truth ও Mathematical Truth
23. Logical Truth ও Empirical Truth
24. Logical Truth ও Argument
25. Logical Truth ও Inference
26. যৌক্তিক সত্যের উদাহরণ
27. দৈনন্দিন ভাষায় যৌক্তিক সত্য
28. কম্পিউটার বিজ্ঞানে যৌক্তিক সত্য
29. Artificial Intelligence-এ যৌক্তিক সত্য
30. Database-এ যৌক্তিক সত্য
31. Formal Verification-এ যৌক্তিক সত্য
32. যৌক্তিক সত্যের ইতিহাস
33. যৌক্তিক সত্যের সীমাবদ্ধতা
34. যৌক্তিক সত্য নির্ণয়ের পদ্ধতি
35. গুরুত্বপূর্ণ পরিভাষা
36. উপসংহার
37. তথ্যসূত্র

---

## যৌক্তিক সত্যের ধারণা

যৌক্তিক সত্য (Logical Truth) হলো এমন একটি proposition বা formula যা তার logical structure-এর কারণে সব সম্ভাব্য উপযুক্ত interpretation বা valuation-এর অধীনে সত্য।

ধরা যাক:

```text
P ∨ ¬P
Classical propositional logic-এ এটি একটি যৌক্তিক সত্য।
এর অর্থ:
P অথবা P নয়।
P সত্য হলে প্রথম অংশ সত্য এবং P মিথ্যা হলে দ্বিতীয় অংশ সত্য। তাই P-এর truth value যাই হোক না কেন, পুরো expression সত্য থাকে।
যৌক্তিক সত্যের বৈশিষ্ট্য
একটি যৌক্তিক সত্যের কয়েকটি গুরুত্বপূর্ণ বৈশিষ্ট্য হলো:
এর সত্যতা logical structure-এর ওপর নির্ভর করে।
Classical propositional logic-এ এটি সব possible truth assignment-এর অধীনে সত্য হতে পারে।
এর সত্যতা কোনো নির্দিষ্ট empirical observation-এর ওপর নির্ভর করে না।
এটি logical reasoning ও formal proof-এর ক্ষেত্রে গুরুত্বপূর্ণ।
Tautology logical truth-এর একটি গুরুত্বপূর্ণ উদাহরণ।
Logical truth এবং factual truth একই বিষয় নয়।
Proposition ও যৌক্তিক সত্য
Proposition হলো এমন একটি ঘোষণামূলক বক্তব্য যাকে সত্য অথবা মিথ্যা হিসেবে মূল্যায়ন করা যায়।
উদাহরণ:
ঢাকা বাংলাদেশের রাজধানী।
এটি একটি proposition।
কিন্তু proposition হওয়া মানেই সেটি logical truth নয়।
Logical truth হতে হলে proposition বা formula-টি তার logical structure-এর কারণে সব উপযুক্ত interpretation বা valuation-এর অধীনে সত্য হতে হবে।
উদাহরণ:
P ∨ ¬P
এটি একটি logical truth-এর উদাহরণ।
Truth Value
Truth value হলো কোনো proposition সত্য না মিথ্যা তা নির্দেশকারী মান।
Classical logic-এ সাধারণত দুটি truth value ব্যবহৃত হয়:
True
False
ধরা যাক:
P = বৃষ্টি হচ্ছে।
যদি বৃষ্টি হয়:
P = True
যদি বৃষ্টি না হয়:
P = False
কিন্তু:
P ∨ ¬P
P True অথবা False যাই হোক না কেন, পুরো expression True থাকবে।
Logical Form
Logical form হলো কোনো proposition বা argument-এর এমন কাঠামো যা তার logical relationship প্রকাশ করে।
উদাহরণ:
সকল মানুষ মরণশীল।
সক্রেটিস একজন মানুষ।
অতএব, সক্রেটিস মরণশীল।
এর সাধারণ logical structure:
সকল A হলো B।
C হলো A।
অতএব, C হলো B।
Logical truth বিশ্লেষণের ক্ষেত্রে এই ধরনের structure গুরুত্বপূর্ণ।
Tautology
Tautology হলো এমন একটি propositional formula যা classical propositional logic-এ সব possible truth assignment-এর অধীনে সত্য।
উদাহরণ
P ∨ ¬P
এটি একটি tautology।
আরেকটি উদাহরণ:
P → P
P সত্য অথবা মিথ্যা যাই হোক না কেন, P → P সত্য।
Truth Table
P
¬P
P ∨ ¬P
True
False
True
False
True
True
তাই:
P ∨ ¬P
একটি tautology।
Contradiction
Contradiction হলো এমন একটি propositional formula যা classical logic-এ সব possible truth assignment-এর অধীনে মিথ্যা।
উদাহরণ
P ∧ ¬P
P সত্য হলে ¬P মিথ্যা।
P মিথ্যা হলে P মিথ্যা।
তাই উভয় ক্ষেত্রেই:
P ∧ ¬P = False
এটি একটি contradiction।
Contingent Proposition
Contingent proposition হলো এমন একটি proposition বা formula যা কিছু ক্ষেত্রে সত্য এবং কিছু ক্ষেত্রে মিথ্যা হতে পারে।
উদাহরণ
P ∧ Q
P এবং Q উভয় সত্য হলে expression-টি সত্য।
অন্য কোনো truth assignment-এ এটি মিথ্যা হতে পারে।
তাই এটি tautology নয় এবং contradiction-ও নয়।
Logical Validity
Validity হলো argument-এর একটি বৈশিষ্ট্য।
একটি deductive argument valid হলে এমন কোনো possible interpretation থাকে না যেখানে সব premise সত্য কিন্তু conclusion মিথ্যা।
উদাহরণ
P → Q
P
∴ Q
এটি Modus Ponens-এর একটি standard logical form।
যদি:
P → Q = True
P = True
তাহলে:
Q = True
হতে হবে।
Logical Truth ও Validity-এর পার্থক্য
Logical truth এবং validity পরস্পরের সঙ্গে সম্পর্কিত হলেও একই ধারণা নয়।
বিষয়
Logical Truth
Validity
কী নিয়ে আলোচনা করে
Proposition বা formula
Argument
প্রধান প্রশ্ন
Formula কি সব ক্ষেত্রে সত্য?
Premise সত্য হলে conclusion কি মিথ্যা হতে পারে?
প্রয়োগ
Logical formula
Deductive argument
উদাহরণ
P ∨ ¬P
P → Q, P ∴ Q
অর্থাৎ:
Logical truth হলো proposition বা formula-এর বৈশিষ্ট্য।
Validity হলো argument-এর বৈশিষ্ট্য।
Classical Logic-এ যৌক্তিক সত্য
Classical logic-এ সাধারণত proposition-এর truth value হিসেবে True এবং False ব্যবহৃত হয়।
Classical logic-এর গুরুত্বপূর্ণ principle-এর মধ্যে রয়েছে:
Law of Identity
Law of Non-Contradiction
Law of Excluded Middle
উদাহরণ:
P ∨ ¬P
Classical propositional logic-এ এটি একটি tautology।
তবে সব ধরনের non-classical logic-এ একই সূত্র একইভাবে গ্রহণ করা হয় না।
Propositional Logic-এ যৌক্তিক সত্য
Propositional logic-এ সম্পূর্ণ proposition-কে মৌলিক logical unit হিসেবে বিবেচনা করা হয়।
ধরা যাক:
P = বৃষ্টি হচ্ছে।
Q = রাস্তা ভেজা।
তাহলে:
P → Q
এর অর্থ:
যদি বৃষ্টি হয়, তাহলে রাস্তা ভেজা।
কিন্তু এটি নিজে logical truth নয়, কারণ P সত্য এবং Q মিথ্যা হলে formula-টি মিথ্যা হয়।
অন্যদিকে:
P ∨ ¬P
একটি logical truth বা tautology।
Predicate Logic-এ যৌক্তিক সত্য
Predicate logic-এ object, property, relation এবং quantifier নিয়ে কাজ করা হয়।
উদাহরণ:
∀x (P(x) → P(x))
এটি predicate logic-এর একটি logical truth।
কারণ যেকোনো x-এর ক্ষেত্রে:
P(x) → P(x)
সত্য।
Predicate logic-এ logical truth নির্ণয় propositional logic-এর তুলনায় আরও জটিল হতে পারে।
Truth Table
Truth table হলো logical formula-এর সম্ভাব্য truth values বিশ্লেষণের একটি পদ্ধতি।
উদাহরণ:
P → P
Truth table:
P
P → P
True
True
False
True
তাই:
P → P
একটি tautology।
Truth table ব্যবহার করে propositional logic-এর বহু formula logical truth কি না তা পরীক্ষা করা যায়।
Logical Equivalence
দুটি proposition বা formula তখন logically equivalent যখন তাদের সব possible valuation-এর অধীনে একই truth value থাকে।
একটি প্রচলিত প্রতীক:
P ≡ Q
উদাহরণ
De Morgan's Law:
¬(P ∧ Q) ≡ (¬P ∨ ¬Q)
দুটি expression-এর truth value সব possible valuation-এর অধীনে একই।
Law of Identity
Law of Identity অনুসারে কোনো বিষয় নিজেই নিজের সঙ্গে অভিন্ন।
প্রতীকীভাবে:
A = A
এটি যুক্তিবিদ্যার ঐতিহ্যবাহী মৌলিক নীতিগুলোর একটি।
Law of Non-Contradiction
Law of Non-Contradiction অনুসারে একই অর্থে এবং একই পরিস্থিতিতে কোনো proposition এবং তার negation একই সঙ্গে সত্য হতে পারে না।
প্রতীকীভাবে:
¬(P ∧ ¬P)
Classical logic-এ এটি একটি গুরুত্বপূর্ণ logical principle।
Law of Excluded Middle
Law of Excluded Middle অনুসারে একটি proposition অথবা তার negation-এর অন্তত একটি সত্য হতে হবে।
প্রতীকীভাবে:
P ∨ ¬P
Classical logic-এ এটি একটি tautology।
Necessary Truth
Necessary truth হলো এমন একটি truth যা যথাযথ logical বা modal অর্থে অন্যভাবে হতে পারে না।
Logical truth-কে অনেক ক্ষেত্রে necessary truth-এর একটি বিশেষ ধরনের উদাহরণ হিসেবে বিবেচনা করা হয়।
তবে “necessary truth” এবং “logical truth” সব philosophical context-এ সম্পূর্ণ সমার্থক নয়।
Analytic Truth
Analytic truth হলো এমন proposition যার সত্যতা তার অর্থ বা ধারণাগত সম্পর্কের মাধ্যমে প্রতিষ্ঠিত হয়।
উদাহরণ:
সকল অবিবাহিত পুরুষ অবিবাহিত।
এখানে “অবিবাহিত” ধারণার অর্থের মধ্যেই বক্তব্যটির সত্যতা নিহিত।
Analytic truth দর্শনের philosophy of language এবং epistemology-তে গুরুত্বপূর্ণ একটি ধারণা।
A Priori Truth
A priori truth হলো এমন সত্য যা প্রতিষ্ঠার জন্য প্রত্যক্ষ empirical observation অপরিহার্য নয়।
Logic এবং mathematics-এর কিছু truth-কে ঐতিহাসিকভাবে a priori জ্ঞানের সঙ্গে সম্পর্কিত করা হয়েছে।
তবে a priori truth এবং logical truth একই ধারণা নয়।
Logical Truth ও Mathematical Truth
Logic এবং mathematics-এর মধ্যে গভীর সম্পর্ক রয়েছে।
উদাহরণ:
1 + 1 = 2
এটি একটি mathematical truth।
অন্যদিকে:
P ∨ ¬P
এটি classical logic-এর একটি logical truth।
Mathematical truth কীভাবে প্রতিষ্ঠিত হবে তা ব্যবহৃত axioms, definitions এবং formal system-এর ওপর নির্ভর করতে পারে।
Mathematical logic mathematics-এর formal structure এবং logical foundations বিশ্লেষণ করে।
Logical Truth ও Empirical Truth
Empirical truth observation, experiment, measurement বা বাস্তব জগতের evidence-এর সঙ্গে সম্পর্কিত।
উদাহরণ:
পৃথিবী সূর্যের চারদিকে ঘোরে।
এটি একটি empirical claim, যার সত্যতা পর্যবেক্ষণ ও বৈজ্ঞানিক evidence-এর সঙ্গে সম্পর্কিত।
অন্যদিকে:
P ∨ ¬P
এর সত্যতা কোনো physical experiment-এর ওপর নির্ভর করে না।
তাই logical truth এবং empirical truth আলাদা ধারণা।
Logical Truth ও Argument
Argument হলো এক বা একাধিক premise থেকে একটি conclusion প্রতিষ্ঠার চেষ্টা।
Logical truth এবং logical validity ব্যবহার করে argument-এর structure বিশ্লেষণ করা যায়।
একটি valid deductive argument-এর ক্ষেত্রে এমন কোনো interpretation থাকতে পারে না যেখানে সব premise সত্য কিন্তু conclusion মিথ্যা।
Logical Truth ও Inference
Inference হলো premise থেকে conclusion-এ পৌঁছানোর reasoning process।
উদাহরণ:
P → Q
P
∴ Q
এটি Modus Ponens-এর একটি valid inference pattern।
Logical inference-এর একটি গুরুত্বপূর্ণ উদ্দেশ্য হলো premise-এর truth সংরক্ষণ করে conclusion-এ পৌঁছানো।
যৌক্তিক সত্যের উদাহরণ
উদাহরণ ১
P ∨ ¬P
Classical logic-এ এটি একটি tautology।
উদাহরণ ২
P → P
এটিও একটি tautology।
উদাহরণ ৩
(P ∧ Q) → P
যদি P এবং Q উভয় সত্য হয়, তাহলে P অবশ্যই সত্য।
তাই এটি classical propositional logic-এ tautology।
উদাহরণ ৪
(P → Q) ↔ (¬Q → ¬P)
এটি implication-এর contrapositive equivalence প্রকাশ করে এবং classical propositional logic-এ tautology।
দৈনন্দিন ভাষায় যৌক্তিক সত্য
দৈনন্দিন ভাষায় logical truth সাধারণত formal symbol-এর পরিবর্তে সাধারণ বাক্যে প্রকাশিত হয়।
উদাহরণ:
হয় বৃষ্টি হচ্ছে, অথবা বৃষ্টি হচ্ছে না।
এটি classical logic-এর:
P ∨ ¬P
structure-এর মতো।
তবে প্রাকৃতিক ভাষায় ambiguity এবং context থাকতে পারে। তাই formal logic-এ statement-কে symbolic form-এ রূপান্তর করা প্রায়ই বেশি নির্ভুল।
কম্পিউটার বিজ্ঞানে যৌক্তিক সত্য
Computer science-এর বিভিন্ন ক্ষেত্রে logical truth গুরুত্বপূর্ণ।
এর মধ্যে রয়েছে:
Boolean expressions
Formal methods
Program verification
Automated theorem proving
Digital circuits
Type systems
Database queries
Constraint solving
কোনো program-এর condition বা property সব valid state-এ সত্য কি না তা logic ব্যবহার করে যাচাই করা যেতে পারে।
Artificial Intelligence-এ যৌক্তিক সত্য
Artificial Intelligence-এর symbolic reasoning system-এ logical truth গুরুত্বপূর্ণ।
Knowledge representation system-এ বিভিন্ন proposition এবং rule সংরক্ষণ করা যায়।
উদাহরণ:
Human(Rahman)
∀x (Human(x) → Mortal(x))
এই তথ্যের ভিত্তিতে inference করা যায়:
Mortal(Rahman)
তবে আধুনিক AI-এর সব system symbolic logic-এর ওপর নির্ভর করে না। Machine learning, probabilistic reasoning এবং neural networks-ও AI-এর গুরুত্বপূর্ণ পদ্ধতি।
Database-এ যৌক্তিক সত্য
Database query-তে Boolean condition এবং logical expression ব্যাপকভাবে ব্যবহৃত হয়।
উদাহরণ:
age >= 18 AND country = "Bangladesh"
এখানে AND logical connective-এর মতো কাজ করে।
SQL উদাহরণ:
SELECT *
FROM users
WHERE age >= 18 AND country = 'Bangladesh';
Database filtering, searching এবং query processing-এ logical conditions গুরুত্বপূর্ণ ভূমিকা পালন করে।
Formal Verification-এ যৌক্তিক সত্য
Formal verification-এ software বা hardware system-এর behavior mathematical এবং logicalভাবে যাচাই করা হয়।
কোনো system একটি নির্দিষ্ট property সব valid state-এ মেনে চলে কি না তা formal logic-এর মাধ্যমে প্রকাশ করা যায়।
উদাহরণ:
System State → Safety Condition
Formal verification-এর মাধ্যমে system-এর বিভিন্ন property সম্পর্কে mathematical proof বা verification result তৈরি করা যেতে পারে।
যৌক্তিক সত্যের ইতিহাস
Logical truth-এর ধারণা যুক্তিবিদ্যার দীর্ঘ ইতিহাসের সঙ্গে সম্পর্কিত।
প্রাচীন গ্রিক দর্শনে argument, inference এবং logical structure নিয়ে systematic আলোচনা শুরু হয়। Aristotle-এর syllogistic logic পরবর্তী পশ্চিমা যুক্তিবিদ্যার ওপর দীর্ঘস্থায়ী প্রভাব ফেলে।
পরবর্তীকালে symbolic logic এবং mathematical logic-এর বিকাশের মাধ্যমে logical truth-এর formal analysis আরও উন্নত হয়।
George Boole, Gottlob Frege, Bertrand Russell, Alfred North Whitehead, David Hilbert, Kurt Gödel এবং Alfred Tarski-এর মতো চিন্তাবিদদের কাজ আধুনিক logic-এর বিকাশে গুরুত্বপূর্ণ ভূমিকা রাখে।
যৌক্তিক সত্যের সীমাবদ্ধতা
Logical truth অত্যন্ত গুরুত্বপূর্ণ হলেও এটি সব ধরনের জ্ঞান প্রদান করে না।
একটি formula logical truth হতে পারে, কিন্তু সেটি বাস্তব জগতের নির্দিষ্ট কোনো তথ্য প্রদান নাও করতে পারে।
উদাহরণ:
P ∨ ¬P
এটি P কী সম্পর্কে তা বলে না।
অন্যদিকে:
বাংলাদেশের রাজধানী ঢাকা।
এটি একটি নির্দিষ্ট factual claim।
তাই বাস্তব জ্ঞান অর্জনের জন্য logical reasoning-এর পাশাপাশি empirical evidence, observation এবং reliable information গুরুত্বপূর্ণ।
যৌক্তিক সত্য নির্ণয়ের পদ্ধতি
কোনো proposition বা formula logical truth কি না নির্ণয় করার জন্য কয়েকটি পদ্ধতি ব্যবহার করা যায়।
১. Logical Form নির্ণয়
প্রথমে proposition-টির logical structure নির্ণয় করতে হবে।
২. Truth Table তৈরি
Propositional logic-এর ক্ষেত্রে সব possible truth assignment পরীক্ষা করা যায়।
৩. Counterexample খোঁজা
যদি এমন কোনো valuation পাওয়া যায় যেখানে formula মিথ্যা, তাহলে সেটি logical truth নয়।
৪. Formal Proof
জটিল formula-এর ক্ষেত্রে formal deduction বা proof ব্যবহার করা যেতে পারে।
৫. Semantic Analysis
Predicate বা modal logic-এর ক্ষেত্রে উপযুক্ত semantic framework ব্যবহার করে formula-এর truth নির্ণয় করা যায়।
গুরুত্বপূর্ণ পরিভাষা
English
বাংলা
Logical Truth
যৌক্তিক সত্য
Truth
সত্য
Truth Value
সত্যমান
True
সত্য
False
মিথ্যা
Proposition
প্রস্তাবনা
Statement
বক্তব্য
Logical Form
যৌক্তিক রূপ
Tautology
সর্বসত্য / চিরসত্য সূত্র
Contradiction
স্ববিরোধী সূত্র
Contingent Proposition
আপতিক প্রস্তাবনা
Validity
বৈধতা
Invalidity
অবৈধতা
Logical Equivalence
যৌক্তিক সমতুল্যতা
Necessity
আবশ্যকতা
Necessary Truth
আবশ্যিক সত্য
Analytic Truth
বিশ্লেষণাত্মক সত্য
A Priori Truth
পূর্বানুভবনিরপেক্ষ সত্য
Inference
অনুমিতি
Deduction
অবরোহী যুক্তি
Premise
প্রতিজ্ঞা
Conclusion
উপসংহার
Predicate
বিধেয়
Quantifier
পরিমাণ নির্দেশক
Negation
নাকরণ
Conjunction
সংযোজন
Disjunction
বিকল্প সংযোজন
Implication
অনুবন্ধ / শর্তযুক্ত সম্পর্ক
Biconditional
দ্বিশর্তযুক্ত সম্পর্ক
Formal Logic
আনুষ্ঠানিক যুক্তিবিদ্যা
Mathematical Logic
গাণিতিক যুক্তিবিদ্যা
উপসংহার
যৌক্তিক সত্য যুক্তিবিদ্যার একটি মৌলিক ধারণা। এটি এমন proposition বা logical formula বোঝাতে ব্যবহৃত হয় যার সত্যতা তার logical structure-এর কারণে প্রতিষ্ঠিত হয়।
Tautology, truth table, logical equivalence, validity এবং formal inference-এর মতো ধারণাগুলোর সঙ্গে logical truth-এর ঘনিষ্ঠ সম্পর্ক রয়েছে।
Classical propositional logic-এ:
P ∨ ¬P
এর মতো formula logical truth-এর একটি গুরুত্বপূর্ণ উদাহরণ।
Logical truth এবং empirical truth এক নয়। Logical truth logical structure-এর ওপর নির্ভর করে, আর empirical truth বাস্তব জগতের observation, measurement ও evidence-এর ওপর নির্ভর করতে পারে।
আধুনিক যুগে logical truth শুধু দর্শন ও যুক্তিবিদ্যার মধ্যেই সীমাবদ্ধ নয়। Mathematics, computer science, artificial intelligence, database, software verification এবং automated reasoning-এর মতো ক্ষেত্রেও এর গুরুত্বপূর্ণ ব্যবহার রয়েছে।
যুক্তিবিদ্যার এই ধারণা মানুষের reasoning-এর কাঠামো বিশ্লেষণ করতে এবং formal system-এর সঠিকতা বোঝার ক্ষেত্রে গুরুত্বপূর্ণ ভিত্তি প্রদান করে।
তথ্যসূত্র
Aristotle — Organon
George Boole — An Investigation of the Laws of Thought
Gottlob Frege — Begriffsschrift
Bertrand Russell ও Alfred North Whitehead — Principia Mathematica
Alfred Tarski — Truth and Formal Semantics
Kurt Gödel — Mathematical Logic
Stanford Encyclopedia of Philosophy — Logic
Encyclopaedia Britannica — Logic
