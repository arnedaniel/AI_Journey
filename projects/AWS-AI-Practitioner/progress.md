# Progress Log

A running log of my AWS AI Practitioner journey. Newest entries at the top.

Working toward the **AWS Certified AI Practitioner (AIF-C01)** certification, prepared on AWS Skill Builder. The exam is booked for **Friday 25 September 2026**, sat in German. Foundations until 13 September, question sets from the 14th to the 24th.

---

## 2026-09-12 (Sat) — Day 13: Back to course 1, before a single exam question

- **Repeating: Fundamentals of Machine Learning and Artificial Intelligence** — course 1 of the eight in the learning plan.
- **Understanding first, questions second.** Phase two was due to open with the question sets on the 14th. I am holding them back until the material holds together on its own, so that nothing in them catches me out.
- **Studying it in my knowledge library, a memory palace I designed for this exam.** One room per course. Each room holds ten objects, and the course's terms hang on them. Course 1 is room 1: ten stations, 29 terms.
- **Learning plan: still 8 of 8.** A repeat does not move the count.

**Next up:** the rest of the repeat, then the question sets.

## 2026-09-11 (Fri) — Day 12: Course 8 of 8. Phase one is done, two days early

- **Finished: Essentials of Prompt Engineering** — the eighth and last course of the learning plan. Four lessons: what a prompt is made of, how to change it, the three techniques, and the ways it gets misused.
- **A prompt has four parts, and only one of them is compulsory.** Instructions, context, input data, output indicator. Instructions is the only one you cannot leave out; the other three decide whether the right thing comes back rather than whether anything comes back. The course builds the whole first lesson on one bad example prompt and then adds the missing parts to it one at a time.
- **Negative prompting is the part I did not expect.** Telling a model what *not* to produce is treated as a technique in its own right, not as an afterthought. Which matches something I already do without calling it that: the rules I keep for my own tooling are mostly prohibitions.
- **The three inference parameters do the same job by three different routes.** Temperature reshapes the probability curve. Top p cuts by *share* of the distribution — 0.25 means the words making up the top 25 percent, however many that is. Top k cuts by *count* — fifty words, regardless of what share they add up to. The knowledge check asks about temperature and offers length as a distractor, which only works if you have not separated the two categories.
- **Chain-of-thought is not the third rung of a ladder.** Zero-shot and few-shot are about whether you supply examples. Chain-of-thought is about whether you demand intermediate steps, triggered with *think step by step*, and the course says plainly it can be combined with either of the other two. I had been filing all three as increasing levels of effort.
- **The risk lesson has one distinction the exam will lean on: exposure versus prompt leaking.** In exposure, data from the training material comes back out. In prompt leaking, the instruction itself comes out — and the course says outright that it need not contain protected data to be a problem, because it reveals how the model works. Poisoning is the odd one of the five: it happens during training, the other four happen at runtime through the prompt.
- **Learning plan: 8 of 8. Phase one finished on the 11th rather than the 13th.**

**Next up:** phase two. Question sets under exam conditions, and the first real measurement of where I actually stand.

## 2026-09-10 (Thu) — Day 11: Course 7 of 8, three hours, and the pattern behind the wrong answers

- **Finished: Security, Compliance, and Governance for AI Solutions** — the seventh of the eight learning-plan courses, and the only one that is a whole exam domain on its own. Two halves with a knowledge check each: applying governance and compliance, then securing the systems themselves.
- **Three words I had been using as one.** Security protects the systems and the data. Governance sets who decides what, and by which rules. Compliance proves the rules were followed. The course separates them in the first minute and then builds everything on that split, which is a good sign that the exam does too.
- **Defense in depth is seven layers with the data in the middle.** Data protection, identity and access, application, network and edge, infrastructure, threat detection and incident response, and policies and awareness on the outside. If one layer falls, the others slow the attacker down instead of the whole thing opening at once.
- **Six services for governance, and two pairs of them collide.** Artifact hands you finished reports about AWS; Audit Manager collects evidence about you. CloudTrail records what someone did; Config records what something looked like. Both pairs sound like the same job and answer opposite questions, and both showed up as answer options in the same list.
- **The Generative AI Security Scoping Matrix is the piece I expect to see again.** Five scopes, from using somebody's public chat tool to training a model from scratch, and each one moves the line for who controls the user data, the fine-tuning data and the training data. It is also the answer to *where does a security strategy start*: classify the application first, pick services second.
- **The threat list is AI-specific and deliberately so.** Prompt injection, training data poisoning, model theft, excessive agency, overreliance — the OWASP Top 10 for LLMs. None of them are the threats I would have listed off the top of my head.
- **The second knowledge check is where it went wrong, and it was the same move twice.** Two of the three questions punish an answer that is true but in the wrong category. Which threats target AI systems: phishing, DDoS and ransomware are real threats and none of them are on the course's list. Which practices secure the data: cleaning out duplicates and splitting the set is good data work and neither is a security practice. Both times I was picking by *is this correct* instead of *is this the category being asked for*, which is a reading habit rather than a gap in the material — and a cheaper one to fix.
- **Three hours, and it broke the trend I had just written down.** Billed at one hour. The four before it ran two hours, two and a half, an hour forty-five and an hour twenty, getting faster each time, and two days ago I planned the last two at ninety minutes on the strength of that. This one took double the plan and longer than any course so far. The reason is the one I flagged when I left it until last: this is the domain I had spent least time in, and it is almost entirely vocabulary — a dozen service names that each differ from their neighbour by one sentence. There was no repeated vocabulary to carry me through it.
- **Learning plan: 7 of 8.**

**Next up:** Essentials of Prompt Engineering, course 8 of 8.

## 2026-09-09 (Wed) — Day 10: The seat is booked, so the date stopped being a preference

*Booked on the 9th, written up on the 10th.*

- **Friday 25 September, 09:00. Sat in German, 100 minutes, at a test centre rather than online.** The plan said book once the practice exam clears. I booked with two courses still open and no measurement taken, which is the opposite order, and I want that written down rather than quietly reframed later. The reason is that a date on the calendar does work that an intention does not: two weeks of "soon" became fifteen days with a number on them.
- **German, and that was not a coin flip.** Every note I have made on this material is in German with the technical terms left in English, because that is how the terms actually appear. Sitting the exam in the same register removes a translation step I would otherwise be doing under time pressure, and the one place it already cost me was a generative-AI question I misread in English back in September.
- **A test centre, not the online proctored option.** Fewer ways for it to go wrong: no room scan, no bandwidth, no software refusing to start twenty minutes before the slot.
- **What is left, honestly.** Two of the eight courses: security, compliance and governance, then prompt engineering. That is roughly three hours. Everything after it is question sets, and I have not sat a single one under exam conditions yet. Fifteen days is enough for that, but only if the two courses land this week rather than drifting.
- **Course 7 is not just the next course, it is a whole exam domain.** Security, Compliance, and Governance for AI Solutions is domain 5 of the five the exam is built from. Leaving it to last means the domain I have spent least time on is also the one I met most recently, which cuts both ways.

**Next up:** Security, Compliance, and Governance for AI Solutions, course 7 of 8.

## 2026-09-08 (Tue) — Day 9: Course 6 of 8, and the metrics are the part that did not land

- **Finished: Optimizing Foundation Models** — the sixth of the eight learning-plan courses, and the one that splits cleanly down the middle. Two ways to make a foundation model better: hand it documents at runtime, or change the model itself. Retrieval-augmented generation on one side, fine-tuning on the other, each with its own business case, its own evaluation section and its own knowledge check.
- **Five ways to fine-tune, and they are not variations of one idea.** Instruction tuning retrains on prompt-and-answer pairs so the model follows commands better. RLHF refines it against human preference until the output matches what people actually want. Domain adaptation feeds it a corpus from one industry — legal documents, medical records. Transfer learning takes a model built for one task and uses it as the starting point for another. Continuous pretraining keeps feeding it new data so it does not go stale.
- **Data preparation is where fine-tuning differs most from the original training.** The first pass wants coverage, diversity and generalisation, and collects as much as it can get. Fine-tuning wants the opposite: a small, tightly curated set where every example is directly relevant. Quality over quantity. Labelling is the step the course singles out, because the labels are what steer the model toward the target domain — governance, bias checking and feedback all matter, but they are not the thing that makes it specialise.
- **What did not land: the evaluation metrics as a group.** The rest of this course sat fine. I can define ROUGE, BLEU and BERTScore one at a time, but I cannot yet reason about them side by side, and side by side is exactly how they get asked. Writing it down rather than letting it slide, because this is the second course in a row where they came up.
- **The knowledge checks tested telling things apart, not remembering them.** One question mixed evaluation metrics into a list of fine-tuning methods as wrong answers. Another asked which of four genuinely correct data-preparation steps is the most critical one. A third asked which metric captures meaning rather than word overlap. Two of the three turned on the same three metrics I had just said I cannot separate. The material is in; the boundaries between neighbouring ideas are not, and that is a different problem needing a different fix.
- **A platform note, small but worth having on record.** With the last section done and both knowledge checks answered, the course player showed 83% while the course page and the learning plan both still listed the course as not started. Clicking through the closing section flipped all three to complete at once. The catalogue appears to carry no in-between state, so a course is either untouched or finished as far as it is concerned. Worth knowing before reading a progress number off the wrong page.
- **Billed at one hour, took an hour twenty, and that is the fastest yet.** Four courses timed now: two hours, two and a half, an hour forty-five, an hour twenty. Course 4 was the peak and every one since has been quicker. The courses are not getting shorter — the vocabulary is repeating, so less of each hour is spent meeting a word for the first time. I set a rule after course 3 to plan these at double their stated length; four measurements later that rule is too generous and I am dropping it. This one I would call manageable rather than hard.
- **Learning plan: 6 of 8.**

**Next up:** Security, Compliance, and Governance for AI Solutions, course 7 of 8.

## 2026-09-07 (Mon) — Day 8: Course 5 of 8, and the vocabulary caught up with the tools

- **Finished: Developing Generative Artificial Intelligence Solutions** — the fifth of the eight learning-plan courses, and the one that covers the generative side end to end. The application lifecycle in five phases: define a use case, select a foundation model, improve its performance, evaluate the results, deploy. The loop closes rather than ends — feedback and metrics from a deployed system flow back and trigger retraining.
- **Four ways to make a model better, and they are not interchangeable.** Prompt engineering changes the wording. RAG hands the model documents at runtime. Fine-tuning changes the weights themselves, either with worked examples or with human feedback. Building from scratch is the expensive last resort. Cost and accuracy both climb from left to right, and the first two leave the model untouched.
- **RAG against fine-tuning is the pair worth getting right.** Dropping the names helps here the same way it did with overfitting: does the model itself change, or does it just get better material on the desk? Open-book exam versus a semester of study. One is cheaper and always current, the other sits deeper.
- **ROUGE, BLEU and BERTScore sound interchangeable and are not.** ROUGE is built for summarisation, BLEU for translation — *bilingual* is in the name — and BERTScore compares meaning rather than overlapping words. The knowledge check leans on exactly that confusion.
- **The terms turned out to describe things I already use.** The notes system I read from before answering questions is retrieval-augmented generation; the file that defines how my agent writes is instruction tuning; every time I say *rewrite that, it sounds off* I am doing by hand what RLHF does at scale. Naming them changed nothing about the tools and quite a lot about how well I can reason about them.
- **Billed at one hour, took an hour forty-five.** Fifth in a row over its listed time, but the first that came anywhere near it. The doubling rule I set after course 3 was generous here — this one is mostly prose and flashcards, where course 4 had the metric arithmetic that ate the extra hour. Quicker than the last one and still nearly twice what the label says.
- **Learning plan: 5 of 8.**

**Next up:** Optimizing Foundation Models, course 6 of 8.

## 2026-09-06 (Sun) — Day 7: Course 4 of 8, and the one I actually enjoyed

- **Finished: Developing Machine Learning Solutions** — the fourth of the eight learning-plan courses. The machine learning lifecycle end to end, which AWS service belongs at which stage of it, where models come from and how you judge whether one is any good, and MLOps as the part that turns a model that works once into a model that keeps working.
- **The most interesting course of the four so far, by a distance.** The first three explained what things are. This one explained how the pieces fit into a process, and a process is something I can picture myself doing rather than reciting.
- **Billed at one hour, took me two and a half.** Fourth course in a row over its listed time. The rule I set after course 3 held, so I am keeping it: plan these at twice their stated length, and for this one that was still short.
- **Knowledge checks: 5 of 6.** The miss was overfitting against underfitting, which I have now mixed up more than once, so it goes in the log rather than quietly past me. What fixed it was dropping the words and asking one question instead: how did it do on the material it trained on? Good on the training set and bad on new data is overfitting — it memorised the examples instead of the rule. Bad on both is underfitting — it never got the rule at all. I taught maths for four years and both of those were sitting in front of me every week; I just never named them.
- **Learning plan: 4 of 8.**

**Next up:** Developing Generative Artificial Intelligence Solutions, course 5 of 8.

## 2026-09-04 (Fri) — Day 6: Course 3 of 8, and an hour that took two

- **Finished: Responsible Artificial Intelligence Practices** — the third of the eight learning-plan courses, and the one that feeds domain 4 of the exam. Four parts: what responsible AI is and the core dimensions it gets measured on, how to build a responsible system and which AWS tooling exists for it, what to weigh when choosing a model and preparing the data, and finally transparency and explainability — what a transparent model actually costs you in trade, and what human-centred design means when the explanation has to reach the person the decision affects.
- **Billed at one hour. It took me two.** Second time now: course 1 was billed the same way and also ran over. The listed hour counts the material, not the working through it — these courses carry knowledge checks and interactive sections, and I stop at them rather than clicking past. I am planning the remaining five at double their stated length instead of being surprised by it again.
- **Learning plan: 3 of 8.** Two counters, still separate, still not adding up into one number.
- **Skill Builder locked me out for most of the day** — The platform answered *Not Subscribed* and refused every course, while the billing page showed the subscription running to August 2027. Signing out and back in changed nothing. It came back on its own in the evening. Logged because it cost the day, not because it needed solving in the end.

**Next up:** Finish the practice question set, then sit the pretest cold.

---

## 2026-09-01 (Tue) — Day 5: Course 2 of 8, and a lesson about reading

- **Finished: Exploring Artificial Intelligence Use Cases and Applications** — the second of the eight learning-plan courses. Where course 1 was the mechanics of machine learning, this one is about matching a business problem to the right kind of solution, and knowing when the answer is not AI at all.
- **Learning plan: 2 of 8.** Two lists, two counters, and they never add up into one number.
- **I got a generative AI question wrong by misreading it** — Not the material, the reading. It was late in the day and I answered the question I thought was there instead of the one on the page. I went back over the section afterwards and the content sits fine now.
- **Worth logging because the exam works the same way** — A foundational exam tests whether you read carefully as much as whether you know the service. Tired reading is a failure mode I can plan around, so it goes in the log rather than quietly out of it.

**Next up:** Finish the practice question set, then sit the pretest cold and let the result decide how much of the remaining six courses I actually sit through.

---

## 2026-08-31 (Mon) — Day 4: Read the plan properly, then started it

- **Finished: Fundamentals of Machine Learning and Artificial Intelligence** — the first of eight courses in the learning plan. Billed as an hour; it took me longer.
- **Two plans, not one** — This tripped me up all day. The **exam prep plan** is 19 items in four steps: reviews, practices, a pretest and a practice exam, one for each of the five domains. The **learning plan** is 8 courses. They are separate lists with separate progress, and the courses feed the domains rather than appearing in them. So today moved the learning plan from 0 to 1 of 8, and left the prep plan at 1 of 19.
- **How they connect** — Courses 1, 2 and 4 feed domain 1, course 5 feeds domain 2, courses 6 and 8 feed domain 3, course 3 feeds domain 4, course 7 feeds domain 5. Courses 6 and 8 are the retrieval and prompting stack I keep seeing in job adverts.
- **Claimed the student subscription, then cancelled the auto-renewal.** The twelve months run from the day you redeem, so redeeming on the day I start was the point. Every practice item is open now; on the free tier I would have had the videos and not one question.
- **Corrected my own method.** I had the pretest pencilled in near the end. It belongs at the start and taken cold — it diagnoses, the practice exam confirms.
- **Dropped the free-voucher route.** It is earned through ninety-day posting and liking streaks, not through study. I would be starting conversations for a counter rather than an answer, and I would know the difference every day I did it. I will pay for the seat and book it on readiness.

**Next up:** Finish the question set, then sit the pretest cold and let the result decide which of the remaining seven courses I actually need.

---

## 2026-08-30 (Sun) — Day 3: The voucher route was a dead end

- **What I found out** — The route I had planned, earning an exam voucher through the community programme, does not lead to the certification. The courses and the badges are real; the path from them to the exam is not.
- **Logged late** — *Machine Learning Foundations* got its own entry below, on the day I actually did it. It had been sitting unlogged for five days.
- **Which of the two actually matters** — *Machine Learning Foundations*, by a distance. *Cloud 101* is general cloud vocabulary; ML Foundations sits inside the exam's own subject matter. The 90 % is the more useful number of the two.
- **What I am not doing** — Deleting the last entry. It happened, I spent seven hours on it, and a log that only shows the parts that worked is not a log.
- **What the seven hours were worth** — Two passed courses, two badges, and the vocabulary the exam assumes: S3, EC2, Lambda, IAM, VPC, the Shared Responsibility Model, the Well-Architected Framework, plus the machine learning groundwork. What I lost was the shortcut to the exam, not the learning or the credentials.
- **The new route** — AWS Skill Builder, the official exam prep plan, with the practice question set and the pretest that go with it. I have a student subscription available for it, though as I found out the next day, availability and activation are not the same thing.
- **The plan** — Ten days at three hours a day, about thirty hours. With ML Foundations already behind me that is enough for a foundational exam. Target date around 11 September.
- **Why not later** — I first pencilled in 3 October, the day before the semester. That leaves no way back: a bad result there and the whole thing waits for next year. Sitting in mid-September puts three weeks of retake room behind me instead.
- **Why I cannot book early** — The discount code that pays for the exam is only issued once every badge on the path is collected. So the booking is the last link in the chain, not the first: finish the courses, collect the badges, get the code, then find a slot. I would rather have locked a date on day two and studied toward it, but that is not how this one works.

**Next up:** Check what the exam prep plan actually contains right now, and read the official exam guide before touching any of the courses.

---

## 2026-08-25 (Tue) — Day 2: Machine Learning Foundations, 90 %

*Written up on 30 August. I did the course the day after Cloud 101 and never logged it — so it goes in here, on the day it happened, rather than being folded into a later entry.*

- **Machine Learning Foundations** — Worked through the course and passed the assessment with **90 %**, well clear of the mark. In English again, same reasoning as Cloud 101.
- **Why this one counts more than Cloud 101** — Cloud 101 teaches the cloud around the problem; this one teaches the problem. Types of machine learning, how a model is trained and evaluated, where the AWS services fit. That is the AI Practitioner exam's own subject matter, not the scaffolding around it.
- **Badge** — Claimed and received, same as Cloud 101.

**Next up:** Onboard the Emerging Talent Community and start earning points toward the exam voucher.

---

## 2026-08-24 (Mon) — Day 1: Registered on AWS Educate and passed Cloud 101

- **AWS Educate registration** — Created the account with an AWS Builder ID using my university email. Chose "Learn cloud skills" + the AWS Educate program.
- **Introduction to Cloud 101 (in English)** — Worked through the full course. Decided to do everything in English to learn the terminology the way it's actually used and practice the language at the same time.
- **Core AWS services learned** — S3 (storage), EC2 (compute), Lambda (serverless), VPC (private network), IAM (access control), CloudWatch (monitoring), RDS (relational DB), DynamoDB (NoSQL key-value).
- **Key concepts** — Cloud = on-demand + pay-as-you-go; economies of scale; Shared Responsibility Model; public vs. private subnets; Well-Architected Framework.
- **Final assessment** — Passed on the first try: **73.33%** (pass mark 70%). ✅
- **Badge** — Claimed the Cloud 101 completion badge. ✅ Credly email arrives within 24h → confirm → add to LinkedIn.
- **Repo** — Set up this project as a self-contained folder under `projects/` with its own README, study plan, and this progress log.

**Next up:** Wait for the Emerging Talent Community to unlock (up to 72h), complete ETC onboarding, then start earning points toward the exam voucher.
