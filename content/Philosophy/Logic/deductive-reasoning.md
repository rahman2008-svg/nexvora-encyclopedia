---
id: deductive-reasoning
title: অবরোহী যুক্তি
tags:
  - দর্শন
  - যুক্তিবিদ্যা
  - যুক্তি
  - অবরোহী যুক্তি
  - Deductive Reasoning
  - Deduction
  - Formal Logic
  - Propositional Logic
  - Predicate Logic
  - Mathematical Logic
  - গণিত
  - সমালোচনামূলক চিন্তা
related:
  - logic
  - argument
  - premise
  - conclusion
  - inference
  - validity
  - soundness
  - proposition
  - logical-consequence
  - logical-form
  - inductive-reasoning
  - abductive-reasoning
  - syllogism
  - formal-logic
---

# অবরোহী যুক্তি

## সংক্ষিপ্ত পরিচিতি

অবরোহী যুক্তি (Deductive Reasoning) হলো এমন একটি যুক্তিনির্ভর চিন্তার পদ্ধতি যেখানে এক বা একাধিক সাধারণ বা নির্দিষ্ট premise থেকে একটি নির্দিষ্ট conclusion যৌক্তিকভাবে প্রতিষ্ঠা করা হয়। এখানে মূল লক্ষ্য হলো premise সত্য হলে এবং reasoning-এর কাঠামো valid হলে conclusion অবশ্যই সত্য হবে কি না তা নির্ণয় করা।

সহজভাবে বলা যায়, অবরোহী যুক্তিতে আমরা এমনভাবে reasoning করি যাতে শুরুতে দেওয়া তথ্য ও নিয়ম থেকে conclusion অনিবার্যভাবে অনুসরণ করে।

উদাহরণ:

> সকল মানুষ মরণশীল।  
> সক্রেটিস একজন মানুষ।  
> অতএব, সক্রেটিস মরণশীল।

এখানে প্রথম দুটি বক্তব্য premise এবং শেষ বক্তব্য conclusion। যদি উভয় premise সত্য হয় এবং argument-এর কাঠামো valid হয়, তাহলে conclusion মিথ্যা হতে পারে না।

---

## অবরোহী যুক্তির ধারণা

Deduction শব্দটি Latin শব্দ *deducere* থেকে এসেছে, যার অর্থ নিচে নিয়ে আসা বা কোনো সাধারণ নীতি থেকে নির্দিষ্ট সিদ্ধান্তে পৌঁছানো।

অবরোহী যুক্তিতে সাধারণত:

```text
Premise
+
Premise
↓
Logical Inference
↓
Conclusion
ব্যবহার করা হয়।
উদাহরণ:
সব ধাতু তাপ পেলে প্রসারিত হয়।
লোহা একটি ধাতু।
অতএব, লোহা তাপ পেলে প্রসারিত হয়।
এখানে একটি সাধারণ নিয়ম এবং একটি নির্দিষ্ট তথ্য ব্যবহার করে নির্দিষ্ট conclusion তৈরি করা হয়েছে।
অবরোহী যুক্তির মৌলিক কাঠামো
একটি deductive argument সাধারণত তিনটি গুরুত্বপূর্ণ অংশ নিয়ে গঠিত:
Premise
Inference
Conclusion
Premise
Premise হলো এমন বক্তব্য যা conclusion-এর ভিত্তি হিসেবে ব্যবহৃত হয়।
Inference
Inference হলো premise থেকে conclusion-এ পৌঁছানোর যৌক্তিক প্রক্রিয়া।
Conclusion
Conclusion হলো premise থেকে প্রতিষ্ঠা করার চেষ্টা করা ফলাফল।
একটি সাধারণ উদাহরণ
ধরা যাক:
সকল পাখির ডানা আছে।
কাক একটি পাখি।
অতএব, কাকের ডানা আছে।
এখানে:
Premise 1:
সকল পাখির ডানা আছে।

Premise 2:
কাক একটি পাখি।

Conclusion:
কাকের ডানা আছে।
এটি একটি সাধারণ deductive structure।
Logical Form
অবরোহী যুক্তির অন্যতম গুরুত্বপূর্ণ বৈশিষ্ট্য হলো logical form।
উপরের argument-টিকে সাধারণ কাঠামোতে লেখা যায়:
সকল A হলো B।
C হলো A।
অতএব, C হলো B।
এখন A, B এবং C-এর জায়গায় বিভিন্ন ধারণা বসানো যায়।
উদাহরণ:
সকল স্তন্যপায়ী প্রাণী শ্বাস নেয়।
মানুষ একটি স্তন্যপায়ী প্রাণী।
অতএব, মানুষ শ্বাস নেয়।
Logical form একই থাকায় argument-এর deductive structure-ও একই থাকে।
Deductive Reasoning এবং Validity
অবরোহী যুক্তিতে validity অত্যন্ত গুরুত্বপূর্ণ।
একটি deductive argument valid হলে এমন কোনো logically possible পরিস্থিতি থাকে না যেখানে:
সব premise সত্য
কিন্তু conclusion মিথ্যা
অর্থাৎ:
Premises True
+
Valid Form
↓
Conclusion অবশ্যই True
তবে validity নিজে premise-এর বাস্তব সত্যতা নিশ্চিত করে না।
Valid কিন্তু Unsound Argument
একটি deductive argument valid হতে পারে কিন্তু sound নাও হতে পারে।
উদাহরণ:
সকল বিড়াল উড়তে পারে।
টম একটি বিড়াল।
অতএব, টম উড়তে পারে।
এখানে argument-এর structure valid:
সকল A হলো B।
C হলো A।
অতএব, C হলো B।
কিন্তু প্রথম premise বাস্তবে সত্য নয়।
তাই argument-টি valid হলেও sound নয়।
Sound Deductive Argument
একটি deductive argument sound হতে হলে দুটি শর্ত পূরণ করতে হয়:
Argument valid হতে হবে।
সব premise সত্য হতে হবে।
তাই:
Valid + True Premises
=
Sound Argument
Sound argument-এর ক্ষেত্রে conclusion সত্য হওয়া অনিবার্য।
Deductive Certainty
Deductive reasoning-এর একটি গুরুত্বপূর্ণ বৈশিষ্ট্য হলো এর conclusion-এর certainty।
যদি:
premise সত্য হয়
inference valid হয়
তাহলে conclusion অবশ্যই সত্য।
উদাহরণ:
সকল বর্গের চারটি বাহু আছে।
ABCD একটি বর্গ।
অতএব, ABCD-এর চারটি বাহু আছে।
এখানে premise ও logical structure গ্রহণযোগ্য হলে conclusion অনিবার্যভাবে অনুসরণ করে।
Deduction বনাম Induction
Deductive reasoning এবং inductive reasoning এক নয়।
Deduction
সাধারণত premise থেকে conclusion অনিবার্যভাবে অনুসরণ করে।
সাধারণ/প্রদত্ত নীতি
↓
নির্দিষ্ট সিদ্ধান্ত
Induction
নির্দিষ্ট পর্যবেক্ষণ থেকে সম্ভাব্য সাধারণ সিদ্ধান্ত তৈরি করে।
নির্দিষ্ট পর্যবেক্ষণ
↓
সাধারণীকরণ
উদাহরণ:
Deduction:
সকল মানুষ মরণশীল।
রহমান একজন মানুষ।
অতএব, রহমান মরণশীল।
Induction:
অনেক মানুষকে পর্যবেক্ষণ করে দেখা গেল তারা মরণশীল।
অতএব, সম্ভবত মানুষ মরণশীল।
Deductive conclusion সাধারণত অনিবার্য হওয়ার দাবি করে, যেখানে inductive conclusion সম্ভাব্য।
Deduction বনাম Abduction
Abductive reasoning কোনো পর্যবেক্ষণের সবচেয়ে সম্ভাব্য ব্যাখ্যা খোঁজে।
উদাহরণ:
রাস্তা ভেজা।
সম্ভবত বৃষ্টি হয়েছে।
এটি deduction নয়, কারণ রাস্তা ভেজার অন্য কারণও থাকতে পারে।
Deduction:
বৃষ্টি হলে রাস্তা ভিজে।
বৃষ্টি হয়েছে।
অতএব, রাস্তা ভিজেছে।
এখানে নির্দিষ্ট logical premises থেকে conclusion তৈরি করা হচ্ছে।
Syllogism এবং Deductive Reasoning
Syllogism হলো deductive reasoning-এর একটি ঐতিহ্যবাহী কাঠামো।
উদাহরণ:
সকল মানুষ মরণশীল।
সক্রেটিস মানুষ।
অতএব, সক্রেটিস মরণশীল।
এটি categorical syllogism-এর একটি পরিচিত উদাহরণ।
এখানে:
Major premise: সকল মানুষ মরণশীল।
Minor premise: সক্রেটিস মানুষ।
Conclusion: সক্রেটিস মরণশীল।
Modus Ponens
Modus Ponens deductive logic-এর একটি গুরুত্বপূর্ণ inference rule।
এর কাঠামো:
P → Q
P
∴ Q
অর্থ:
যদি P হয়, তবে Q।
P সত্য।
অতএব, Q সত্য।
উদাহরণ:
যদি বৃষ্টি হয়, তাহলে রাস্তা ভিজবে।
বৃষ্টি হচ্ছে।
অতএব, রাস্তা ভিজছে।
Modus Tollens
Modus Tollens-এর কাঠামো:
P → Q
¬Q
∴ ¬P
অর্থ:
যদি P হয়, তবে Q।
Q সত্য নয়।
অতএব, P সত্য নয়।
উদাহরণ:
যদি বিদ্যুৎ থাকে, তাহলে বাতি জ্বলবে।
বাতি জ্বলছে না।
অতএব, বিদ্যুৎ নেই।
বাস্তব reasoning-এ অবশ্য প্রথম premise-এর শর্তগুলো যথাযথ হতে হবে; যেমন বাতি নষ্ট হওয়া বা সংযোগ বিচ্ছিন্ন হওয়ার মতো অতিরিক্ত কারণ থাকলে argument-এর বাস্তব soundness আলাদা করে যাচাই করতে হবে।
Hypothetical Syllogism
Hypothetical syllogism-এর কাঠামো:
P → Q
Q → R
∴ P → R
উদাহরণ:
যদি পড়াশোনা করি, তাহলে জ্ঞান বাড়বে।
যদি জ্ঞান বাড়ে, তাহলে বিষয়টি ভালোভাবে বোঝা যাবে।
অতএব, যদি পড়াশোনা করি, তাহলে বিষয়টি ভালোভাবে বোঝা যাবে।
Disjunctive Syllogism
Disjunctive syllogism-এর একটি সাধারণ কাঠামো:
P ∨ Q
¬P
∴ Q
উদাহরণ:
আজ স্কুলে অথবা বাড়িতে থাকব।
আজ স্কুলে থাকব না।
অতএব, আজ বাড়িতে থাকব।
এখানে ∨ দ্বারা OR বোঝানো হয়েছে।
Deductive Argument-এর বৈশিষ্ট্য
একটি deductive argument-এর গুরুত্বপূর্ণ বৈশিষ্ট্য হলো:
Premise নির্দিষ্ট থাকে
Logical relationship গুরুত্বপূর্ণ
Conclusion premise থেকে অনুসরণ করে
Validity পরীক্ষা করা যায়
Formal rules ব্যবহার করা যায়
Mathematical proof-এ ব্যবহার করা যায়
Conclusion-এর certainty logical structure-এর ওপর নির্ভর করে
Formal Deductive Reasoning
Formal deduction-এ নির্দিষ্ট inference rules ব্যবহার করে conclusion derive করা হয়।
উদাহরণ:
1. P → Q
2. P
3. Q
এখানে ৩ নম্বর statement, ১ ও ২ নম্বর premise থেকে Modus Ponens-এর মাধ্যমে derive করা হয়েছে।
Formal system-এ প্রতিটি inference নির্দিষ্ট rule দ্বারা সমর্থিত হতে পারে।
Natural Deduction
Natural deduction হলো formal proof-এর একটি পদ্ধতি যেখানে মানুষের স্বাভাবিক reasoning-এর কাছাকাছি inference rules ব্যবহার করা হয়।
উদাহরণ:
1. P → Q    Premise
2. P        Premise
3. Q        → Elimination
এখানে implication elimination ব্যবহার করে Q পাওয়া হয়েছে।
Deduction এবং Mathematical Proof
গণিতের theorem প্রমাণে deductive reasoning অপরিহার্য।
একটি সাধারণ proof structure:
Axiom
↓
Definition
↓
Lemma
↓
Inference
↓
Theorem
উদাহরণস্বরূপ, জ্যামিতি, সংখ্যা তত্ত্ব এবং algebra-এর বহু theorem formal deductive reasoning-এর মাধ্যমে প্রমাণ করা হয়।
Deduction এবং Mathematics
গণিতের বিভিন্ন ক্ষেত্রে deduction ব্যবহৃত হয়:
Algebra
Geometry
Number Theory
Set Theory
Calculus
Discrete Mathematics
Mathematical Logic
একটি theorem-এর conclusion প্রতিষ্ঠার জন্য পূর্ববর্তী সংজ্ঞা, axiom এবং theorem থেকে যৌক্তিকভাবে inference তৈরি করা হয়।
Deduction এবং Computer Science
Computer science-এর সঙ্গে deductive reasoning-এর গভীর সম্পর্ক রয়েছে।
এটি ব্যবহৃত হয়:
Formal verification
Automated theorem proving
Type systems
Logic programming
Program verification
Knowledge representation
Compiler correctness
Database reasoning
ইত্যাদিতে।
Deduction এবং Programming
Programming-এ conditional statements এবং Boolean expressions deductive reasoning-এর সঙ্গে সম্পর্কিত।
উদাহরণ:
if age >= 18:
    allow_access
এখানে system একটি condition পরীক্ষা করে এবং condition সত্য হলে নির্দিষ্ট conclusion বা action গ্রহণ করে।
আরও formalভাবে:
Age >= 18
→ Access Allowed
তবে বাস্তব program-এ একাধিক condition, exception এবং state থাকতে পারে।
Deduction এবং Boolean Logic
Boolean logic-এ True এবং False truth value ব্যবহার করে logical inference তৈরি করা হয়।
উদাহরণ:
P = True
P → Q = True
তাহলে Modus Ponens অনুযায়ী:
Q = True
এ ধরনের logical structure computer circuits এবং software conditions-এ ব্যাপকভাবে ব্যবহৃত হয়।
Deduction এবং Artificial Intelligence
AI-এর কিছু symbolic reasoning system-এ deductive inference ব্যবহার করে knowledge base থেকে নতুন তথ্য derive করা যায়।
উদাহরণ:
Human(Rahman)
∀x Human(x) → Mortal(x)
Inference:
Mortal(Rahman)
এখানে system পূর্ববর্তী knowledge থেকে একটি নতুন conclusion তৈরি করছে।
আধুনিক AI-এর সব পদ্ধতি deductive reasoning-এর ওপর নির্ভরশীল নয়। Machine learning এবং statistical inference-ও গুরুত্বপূর্ণ।
Deduction এবং Database
Database query-তে stored facts এবং rules ব্যবহার করে information derive করা যায়।
উদাহরণ:
Student(Rahman)
Student(x) → HasAccess(x)
Inference:
HasAccess(Rahman)
Logic programming এবং rule-based database system-এ এই ধরনের reasoning বিশেষভাবে গুরুত্বপূর্ণ।
Deduction এবং Critical Thinking
Critical thinking-এ deductive reasoning ব্যবহার করে দেখা যায়:
Premise কী?
Conclusion কী?
Premise থেকে conclusion অনুসরণ করে কি?
Argument valid কি?
Premise সত্য কি?
কোনো hidden assumption আছে কি?
কোনো logical fallacy আছে কি?
এভাবে কোনো argument-এর structure পরিষ্কারভাবে বিশ্লেষণ করা যায়।
Deductive Fallacy
সব deduction সঠিক নয়।
একটি deductive argument-এর conclusion premise থেকে logically follow না করলে argument invalid হতে পারে।
উদাহরণ:
যদি বৃষ্টি হয়, রাস্তা ভিজবে।
রাস্তা ভিজেছে।
অতএব, বৃষ্টি হয়েছে।
এটি সাধারণভাবে valid deduction নয়।
প্রতীকী কাঠামো:
P → Q
Q
∴ P
এটি Affirming the Consequent নামে পরিচিত একটি invalid inference pattern।
রাস্তা অন্য কারণেও ভিজতে পারে।
Valid Deduction বনাম Invalid Deduction
Valid
P → Q
P
∴ Q
এটি Modus Ponens।
Invalid
P → Q
Q
∴ P
এটি Affirming the Consequent।
তাই conclusion সত্য হয়ে গেলেও reasoning-এর structure valid নাও হতে পারে।
Hidden Premise
অনেক দৈনন্দিন argument-এ কিছু premise সরাসরি বলা হয় না।
উদাহরণ:
“রহমান আজ পরীক্ষায় ভালো করবে, কারণ সে প্রতিদিন পড়াশোনা করে।”
এখানে একটি hidden assumption থাকতে পারে:
নিয়মিত পড়াশোনা করলে পরীক্ষায় ভালো করার সম্ভাবনা বৃদ্ধি পায়।
Argument বিশ্লেষণের সময় এই ধরনের implicit premise শনাক্ত করা গুরুত্বপূর্ণ।
Deductive Reasoning-এর ধাপ
একটি deductive argument বিশ্লেষণ করার সময় সাধারণভাবে নিচের ধাপগুলো অনুসরণ করা যায়:
ধাপ ১: Premise শনাক্ত করা
কোন তথ্য বা statement থেকে reasoning শুরু হচ্ছে তা নির্ধারণ করা।
ধাপ ২: Conclusion শনাক্ত করা
কী সিদ্ধান্তে পৌঁছানো হচ্ছে তা নির্ধারণ করা।
ধাপ ৩: Logical form নির্ণয় করা
Argument-এর structure চিহ্নিত করা।
ধাপ ৪: Inference rule পরীক্ষা করা
কোন rule ব্যবহার করে conclusion পাওয়া হয়েছে তা পরীক্ষা করা।
ধাপ ৫: Validity পরীক্ষা করা
Premise সত্য কিন্তু conclusion মিথ্যা—এমন কোনো সম্ভাব্য situation আছে কি না দেখা।
ধাপ ৬: Soundness পরীক্ষা করা
Premise বাস্তবে সত্য কি না যাচাই করা।
Deductive Reasoning-এর সুবিধা
অবরোহী যুক্তির মাধ্যমে:
নিশ্চিত logical conclusion পাওয়া যায়
Mathematical proof তৈরি করা যায়
Argument-এর structure পরীক্ষা করা যায়
Contradiction শনাক্ত করা যায়
Formal system তৈরি করা যায়
Software verification করা যায়
Rule-based AI তৈরি করা যায়
Decision system তৈরি করা যায়
Critical thinking উন্নত করা যায়
Deductive Reasoning-এর সীমাবদ্ধতা
Deductive reasoning-এর শক্তি তার premises-এর ওপর নির্ভরশীল।
যদি premise ভুল হয়, তাহলে valid structure থাকা সত্ত্বেও বাস্তব conclusion ভুল হতে পারে।
উদাহরণ:
সকল মাছ আকাশে উড়তে পারে।
রুই একটি মাছ।
অতএব, রুই আকাশে উড়তে পারে।
Structure valid হতে পারে, কিন্তু premise বাস্তবসম্মত নয়।
তাই বাস্তব জীবনে deduction-এর পাশাপাশি evidence ও premise যাচাই গুরুত্বপূর্ণ।
Deduction এবং বাস্তব জীবন
দৈনন্দিন জীবনে মানুষ বিভিন্ন ধরনের deductive reasoning ব্যবহার করে।
উদাহরণ:
যদি দোকান বন্ধ থাকে, তাহলে সেখানে কেনাকাটা করা যাবে না।
দোকানটি বন্ধ।
অতএব, সেখানে কেনাকাটা করা যাবে না।
আবার:
যাদের পরীক্ষার প্রবেশপত্র নেই তারা পরীক্ষায় প্রবেশ করতে পারবে না।
আমার প্রবেশপত্র নেই।
অতএব, আমি পরীক্ষায় প্রবেশ করতে পারব না।
তবে বাস্তব নিয়মের ব্যতিক্রম থাকলে conclusion পরিবর্তিত হতে পারে। তাই বাস্তব deduction-এ premises-এর সঠিকতা ও completeness গুরুত্বপূর্ণ।
Deduction এবং Scientific Reasoning
বিজ্ঞান deduction এবং induction উভয়ই ব্যবহার করে।
উদাহরণ:
একটি বৈজ্ঞানিক hypothesis থেকে নির্দিষ্ট prediction তৈরি করা deduction-এর মাধ্যমে করা যেতে পারে।
Hypothesis
↓
Deductive Prediction
↓
Observation / Experiment
↓
Comparison
তবে prediction সত্য হওয়া hypothesis-এর সম্পূর্ণ সত্যতা নিশ্চিত করে না। বৈজ্ঞানিক জ্ঞানে empirical evidence অপরিহার্য।
Deduction এবং Legal Reasoning
আইনগত reasoning-এ আইন, precedent, facts এবং rules থেকে conclusion তৈরি করা হতে পারে।
সরল উদাহরণ:
Rule:
যদি নির্দিষ্ট শর্ত A পূরণ হয়, তাহলে rule B প্রযোজ্য।

Fact:
শর্ত A পূরণ হয়েছে।

Conclusion:
Rule B প্রযোজ্য।
বাস্তব আইনগত reasoning অবশ্য আরও জটিল এবং interpretation, evidence ও jurisdiction-এর মতো বিষয়ের ওপর নির্ভর করে।
Deductive Reasoning-এর ঐতিহাসিক গুরুত্ব
অবরোহী যুক্তির ইতিহাস প্রাচীন দর্শনের সঙ্গে গভীরভাবে সম্পর্কিত।
প্রাচীন গ্রিক দর্শনে Aristotle syllogism এবং deductive argument-এর systematic analysis করেন।
পরবর্তীতে formal logic, symbolic logic এবং mathematical logic-এর বিকাশ deduction-কে আরও আনুষ্ঠানিক ও শক্তিশালী করে।
Aristotle এবং Deduction
Aristotle deductive argument এবং syllogism-এর systematic study-এর জন্য বিশেষভাবে পরিচিত।
তার categorical syllogism-এর কাঠামো বহু শতাব্দী ধরে logic শিক্ষার গুরুত্বপূর্ণ অংশ ছিল।
উদাহরণ:
সকল মানুষ মরণশীল।
সক্রেটিস মানুষ।
অতএব, সক্রেটিস মরণশীল।
এটি deductive reasoning-এর একটি ঐতিহাসিকভাবে পরিচিত উদাহরণ।
Modern Deductive Logic
আধুনিক logic-এ deduction শুধু syllogism-এর মধ্যে সীমাবদ্ধ নয়।
এতে অন্তর্ভুক্ত হয়েছে:
Propositional logic
Predicate logic
First-order logic
Modal logic
Proof theory
Automated reasoning
Natural deduction
Sequent calculus
Resolution
এই ক্ষেত্রগুলো mathematics এবং computer science-এর সঙ্গে গভীরভাবে সম্পর্কিত।
Deductive Reasoning-এর Logical Structure
একটি সাধারণ deductive structure:
Premise 1
Premise 2
Premise 3
...
Premise n
────────────
Conclusion
মূল প্রশ্ন হলো:
সব premise সত্য হলে conclusion কি মিথ্যা হতে পারে?
যদি উত্তর “না” হয়, তাহলে argument valid।
একটি পূর্ণাঙ্গ উদাহরণ
ধরা যাক:
সকল প্রোগ্রামার কম্পিউটার ব্যবহার করে।
আরিফ একজন প্রোগ্রামার।
অতএব, আরিফ কম্পিউটার ব্যবহার করে।
Premise 1
সকল প্রোগ্রামার কম্পিউটার ব্যবহার করে।
Premise 2
আরিফ একজন প্রোগ্রামার।
Conclusion
আরিফ কম্পিউটার ব্যবহার করে।
Logical Form
All A are B.
C is A.
Therefore C is B.
Reasoning Type
Deductive reasoning।
Validity
Structure valid।
Soundness
Soundness নির্ভর করবে premise-গুলোর বাস্তব সত্যতার ওপর।
আরেকটি Formal উদাহরণ
ধরা যাক:
P = আজ বৃষ্টি হচ্ছে।
Q = রাস্তা ভেজা।
Premises:
P → Q
P
Conclusion:
Q
অর্থাৎ:
যদি বৃষ্টি হয়, রাস্তা ভিজবে।
বৃষ্টি হচ্ছে।
অতএব, রাস্তা ভিজছে।
এটি Modus Ponens-এর উদাহরণ।
Deductive Reasoning-এর সারসংক্ষেপ
Deductive Reasoning
│
├── Premises
│   ├── General Rule
│   └── Specific Fact
│
├── Inference
│   └── Logical Rule
│
└── Conclusion
    └── Necessarily follows
এখানে conclusion-এর logical status premises এবং inference-এর ওপর নির্ভর করে।
গুরুত্বপূর্ণ পরিভাষা
English
বাংলা
Deductive Reasoning
অবরোহী যুক্তি
Deduction
অবরোহ
Premise
প্রতিজ্ঞা
Conclusion
উপসংহার
Inference
অনুমিতি
Argument
যুক্তি
Validity
বৈধতা
Soundness
সুপ্রতিষ্ঠিততা
Invalidity
অবৈধতা
Proposition
প্রস্তাব / বচন
Logical Form
যৌক্তিক রূপ
Logical Consequence
যৌক্তিক ফল
Inference Rule
অনুমিতির নিয়ম
Modus Ponens
মোডাস পোনেন্স
Modus Tollens
মোডাস টোলেন্স
Syllogism
অবয়বী যুক্তি / Syllogism
Premise
পূর্বপক্ষ / প্রতিজ্ঞা
Conclusion
উপসংহার
Proof
প্রমাণ
Contradiction
বিরোধ
Consistency
সামঞ্জস্য
Formal Logic
আনুষ্ঠানিক যুক্তিবিদ্যা
Natural Deduction
প্রাকৃতিক অবরোহ
Inductive Reasoning
আরোহী যুক্তি
Abductive Reasoning
ব্যাখ্যাভিত্তিক যুক্তি
Deductive Reasoning-এর সঙ্গে সম্পর্কিত ধারণা
অবরোহী যুক্তিকে ভালোভাবে বুঝতে নিচের ধারণাগুলোও গুরুত্বপূর্ণ:
Logic
Proposition
Premise
Conclusion
Argument
Inference
Validity
Soundness
Logical Consequence
Syllogism
Formal Logic
Propositional Logic
Predicate Logic
Mathematical Logic
Inductive Reasoning
Abductive Reasoning
Logical Necessity
Logical Possibility
Logical Impossibility
উপসংহার
অবরোহী যুক্তি হলো এমন একটি reasoning পদ্ধতি যেখানে premise এবং নির্দিষ্ট logical rules ব্যবহার করে এমন conclusion তৈরি করা হয় যা premises সত্য এবং argument valid হলে অনিবার্যভাবে অনুসরণ করে।
এর মূল শক্তি হলো logical certainty। তবে এই certainty কেবল তখনই কার্যকর যখন premises সত্য এবং inference সঠিক।
গণিতের proof, formal logic, programming, computer science, database, artificial intelligence, legal reasoning এবং critical thinking—বিভিন্ন ক্ষেত্রে deductive reasoning গুরুত্বপূর্ণ ভূমিকা পালন করে।
সহজভাবে বলা যায়:
অবরোহী যুক্তি হলো এমন যুক্তি যেখানে গ্রহণযোগ্য premise ও বৈধ logical structure থেকে একটি conclusion অনিবার্যভাবে অনুসরণ করে।
তথ্যসূত্র
Aristotle — Organon
Irving M. Copi — Introduction to Logic
Patrick J. Hurley — A Concise Introduction to Logic
Graham Priest — Logic: A Very Short Introduction
Stanford Encyclopedia of Philosophy — Logic
Stanford Encyclopedia of Philosophy — Deductive Logic
Stanford Encyclopedia of Philosophy — Aristotle's Logic
