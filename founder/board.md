# Edurance: board summary

Memos: [Offers lens](board/offers.md) · [Monopoly lens](board/monopoly.md) · [Product lens](board/product.md) · [Brief](board/brief.md)

The three lenses summarise published frameworks. They are not the views of the people who wrote those frameworks.

## 1. The vote

**3 FUND IF, 0 FUND, 0 PASS. Average score 4.0 / 10.**

| Lens | Score | Vote | In one line |
|---|---|---|---|
| Offers | 4 | FUND IF | The pain is real and schools are easy to reach, but nobody has a reason yet to believe it works. |
| Monopoly | 4 | FUND IF | The small market and the channel are well defined. There is no moat, and the cost of the channel is unknown. |
| Product | 4 | FUND IF | A working product, but it does too many things, the first session is a test, and five handovers between parties can each break. |

A 4 does not mean the idea is bad. It means the evidence is missing. All three lenses say the score moves on pilot evidence, not on more features. The Monopoly lens says it would switch to **PASS** if pilots cannot show that the channel works and that each paid user makes money.

**A correction to the memos.** Two memos call pilots and users "zero". The brief does not say that. It says these numbers are *not yet known*. Read "zero" as "unverified" until the founders give the real numbers (see section 10).

## 2. Risks more than one lens raised

1. **No proof that it works** (Offers, Monopoly, Product). There is no measured learning gain, retention or school uptake yet. A school is asked to trust an AI product, and a parent is asked to pay ₹299, with nothing to show either of them.
2. **The payer is unclear** (Offers, Product). The school carries the effort, the student uses the product, and the parent may pay. The parent may never have seen it working when asked to pay. The design should work backwards from whoever pays.
3. **Unknown unit economics** (Offers, Monopoly). Net revenue after the school's share and the AI/TTS cost per student are both unknown. Without them, nobody can say whether ₹299 is profitable.
4. **The channel costs a lot and has seams** (Monopoly, Product). A long sales cycle, done by hand by four founders, with handovers from decision-maker to teacher to student to parent to payment. Founder-hours per school are the hidden cost.

**Where the lenses disagree** (keep this tension, do not smooth it over):

- **Add or cut?** The Offers lens wants a *bigger* offer: a guarantee, risk reversal and a fuller set of included services. The Product lens wants the product *cut* to one subject, one grade and one loop. They can both be right: a narrow product sold with a strong outcome guarantee. But the founders have to choose this on purpose.
- **How much the moat matters now.** The Monopoly lens treats the lack of defensibility (everything is built on public AI APIs) as the risk most likely to kill the business. The other two hardly mention it, because they see proving value as the first problem. The chair's view: prove value first, but collect data from day one in a way that can later become a moat.
- **Who should pay.** The Offers lens leans towards testing parents' willingness to pay. The Product lens questions whether the parent should be the payer at all. This is still open, and the 30-day plan tests it.

## 3. Conditions checklist

Later founder skills (consumer panel, pricing, CFO) will test many of these.

- [ ] **Narrow the focus.** One subject, one grade band, one core loop (find the gap → teach it → show it closed). Freeze everything else. *(Product)*
- [ ] **Redesign the first session.** A student finishes a lesson they want to repeat in the first few minutes. Spread the diagnostic through the lessons rather than putting a full test up front. *(Product)*
- [ ] **Name the payer.** Decide whether the school, the parent, or both pays. Settle the billing period for ₹299 and the school's revenue share in writing. *(Offers, Product)* → `/founder-pricing`
- [ ] **Rewrite the offer around one outcome.** A named, measurable result, a time frame, and a risk reversal for the pilot school. *(Offers)* → `/founder-offer`
- [ ] **Take effort off the school.** The Edurance team runs onboarding, not the teachers. *(Offers)*
- [ ] **Sign 2–3 structured pilots** from the 150 schools, recording time to close and founder-hours per school. *(Monopoly, Offers)*
- [ ] **Measure learning honestly.** Run the baseline diagnostic again at the end of the pilot and report the change, good or bad. Use a comparison group if possible. *(Offers)*
- [ ] **Report observed numbers.** Activation, repeat use and retention, before expanding across the 150-school map. *(Product, Monopoly)*
- [ ] **Unit economics per paid user.** Revenue after the school's share, minus the AI/TTS cost per active student measured in the pilots, must be positive. *(Offers, Monopoly)* → `/founder-cfo`
- [ ] **Map and own every seam.** Write down every handover from contract to payment, with one founder named for each. *(Product)*
- [ ] **Name the moat in writing.** For example, diagnostic data for each school, curriculum alignment, or switching costs for schools. Show the first measurable sign of it in the pilots. *(Monopoly)*
- [ ] **Competitor map.** What do the 150 schools and their parents already use and pay for? *(Monopoly, Offers)* → `/founder-competitors`
- [ ] **Child-data compliance before onboarding a student.** *(Chair: see the privacy seat in section 5)*

## 4. The strongest version the board can see

The strongest version of Edurance is **not** "an AI learning platform with adaptive learning, voice, tracking and dashboards". It is a **term-long, school-run program to close gaps in one subject and grade band**. A school signs up a class. The Edurance team does all the onboarding. Students get a short, rewarding first session rather than a test. The school and parents receive a before-and-after report showing the specific gaps that were closed. The school pays for it as a program, or collects the fee as part of an agreed school arrangement. A parent subscription at ₹299 is offered only after the parent has seen that report.

Over time, the diagnostic data built up across a school's students, aligned to the curriculum the school actually teaches, becomes the asset a copycat using the same AI APIs cannot reproduce.

**This is narrower than what was pitched, and on purpose.** It moves the sale from features to a measured outcome, and it moves the request for money to after the proof. Whether the school or the parent should pay is the most important open question.

---

*Sections 5–10 answer your wider brief. The three-lens board covers market, defensibility and product. You also asked for specialist seats, so they are added here.*

## 5. The full board: the seats Edurance needs and what each should challenge

| Seat | What it must challenge | The question it would ask first |
|---|---|---|
| **Education and learning science** | Whether the adaptive flow actually teaches, not just tests. Whether AI explanations are correct, age-appropriate and aligned to the board taught (CBSE / ICSE / Telangana State Board) and to the language of instruction. Whether "mastery" is defined in a way a teacher would accept. Whether pre/post gains are real or just practice on the same test. | "How do you know a student learned, rather than got familiar with your questions?" |
| **School sales and partnerships** | Who decides in a school (owner / management, principal, academic coordinator), the buying calendar (budgets and timetables are set around the academic year), the length of the sales cycle, what the school gets (results, less teacher work, revenue, a point to market to parents), and whether a revenue share creates the right incentive. | "Who signs, when in the year do they sign, and what do they get?" |
| **AI and product technology** | Cost per student of OpenAI and TTS calls, hallucination and accuracy controls, latency and offline behaviour on the devices and networks schools really have, Supabase/Vercel reliability under a class-sized load (40 students logging in at once), and dependence on a single model provider. | "What does one active student cost per month to serve, and what happens when 40 log in at 9 a.m.?" |
| **Finance** | Net revenue per user after the school's share, billing period, collection risk (who collects ₹299 and how), payback on founder time spent per school, cash runway against the budget (not yet given), and pricing compared with what families already spend on tuition. | "After the school's share and API costs, what is left from ₹299, and how long until the business funds itself?" |
| **Child privacy and safety** | Lawful handling of minors' data under India's Digital Personal Data Protection Act, 2023 and its Rules. These broadly require verifiable parental consent to process children's data, and restrict tracking, behavioural monitoring and targeted advertising aimed at children. Also: what student data is sent to third-party AI APIs, where it is stored, retention and deletion, the school data-sharing agreement, and content safety for AI output shown to children. *Get a legal review. This board is not legal advice.* | "Show us the consent flow, the data map and the school agreement before the first student logs in." |
| **Business operations** | Whether four founders can run outreach, pilots, onboarding, support and the product at the same time. Support coverage during school hours, an incident process, a repeatable pilot playbook, and what breaks at 5 schools compared with 1. | "How many schools can the four of you run at once before quality drops?" |

## 6. Business model assessment

| Element | Assessment | Status |
|---|---|---|
| **Customer** | Three parties with different jobs: student (user), school (channel and possibly buyer), parent (possibly payer). The model only works if each one gets enough to justify its effort or spend. | The payer is **undecided**. This is the most important question in the model. |
| **Problem** | Students have uneven learning gaps that one teacher with a full class cannot address one by one. The need is plausible and widely recognised. | **Assumption** for these 150 schools. Not yet confirmed in interviews or by data. |
| **Value proposition** | Find each student's exact gaps and close them, with proof visible to parents and schools. Strong if it can be proved. Today it is described as a list of features, not an outcome. | **Unverified.** No measured learning outcomes yet. |
| **Pricing** | ₹299 per paid user. The billing period, the school's share and willingness to pay are unknown. It cannot be judged until the period and the payer are fixed, since ₹299 a month and ₹299 a year are completely different businesses. | **Unvalidated.** → `/founder-pricing`, `/founder-consumer` |
| **Distribution** | School-led B2B2C to a defined universe of 150 schools in four zones. Efficient if a school brings a cohort of students. Expensive if each school needs many founder-hours. | **Planning assumption.** Funnel targets are not proven conversion rates. |
| **Repeatable revenue** | Possible through subscription renewal and school renewal each academic year. This depends on retention and on proof of outcomes. Expansion inside a school (more grades or subjects) is the natural growth path. | **Unknown.** Needs retention data and a renewal test. |
| **Cost to serve** | AI and TTS calls per student, support, and founder time per school. Audio caching helps. | **Unknown.** Needs measurement → `/founder-cfo` |

**Verdict on the model:** it is coherent and could become repeatable, but every number that decides whether it works is missing. The structure (school as channel, cohort onboarding, renewal tied to the academic year) is sound. What is unproven is whether money and usage actually move through that structure.

## 7. Biggest risks, ranked

Severity: how badly the business is hurt if the risk comes true. Uncertainty: how little we know today. The ranking puts first the risks that are both severe and uncertain.

| # | Risk | Severity | Uncertainty | Why it ranks here |
|---|---|---|---|---|
| 1 | **Schools will not commit to structured pilots** (or will commit only to free, unstructured ones) | Critical | High | Without schools there is no channel. Everything downstream depends on this. |
| 2 | **Students stop using it after onboarding** | Critical | High | No usage means no outcome, no proof and no renewal. A diagnostic-first first session makes this worse. |
| 3 | **Nobody pays ₹299, or it is unclear who would** | Critical | High | No revenue. The payer, the period and the school share are all undefined. |
| 4 | **Unit economics are negative** after the school's share, AI/TTS cost and founder time | High | High | The business can grow and still lose money on every user. |
| 5 | **No measurable learning gain** | High | High | Without proof, schools will not renew and parents will not pay. It is also an ethical issue for a children's product. |
| 6 | **Child-data and privacy non-compliance** | High | Medium | A single incident or complaint could end school partnerships. This is fixable in advance, so it is a gate rather than an unknown. |
| 7 | **Founder capacity and accountability** | Medium–High | Medium | Four people across zones and functions. Seams with no owner. |
| 8 | **Copycats and commoditisation** (built on public AI APIs) | Medium now, High later | Medium | It does not kill the business this year, but caps it later. |
| 9 | **Product reliability at class scale** (simultaneous logins, school networks and devices, model latency) | Medium | Medium | Visible failures in front of a class damage trust with the school. |

### Facts, assumptions and unverified claims

| Known facts (from the brief) | Assumptions (stated as plans) | Unverified claims (need evidence) |
|---|---|---|
| A web product built with Flutter, Supabase, OpenAI and Vercel exists | 150-school prospect universe across four zones | Edurance improves learning outcomes |
| Features exist: auth, diagnostics with saved results, lesson resumption, adaptive flows, AI explanations, TTS with caching, parent features | Funnel conversion targets in the October plan | Students will engage consistently |
| Four co-founders | ₹299 per paid user is the price | Schools and parents value it enough to pay |
| Starting market is Hyderabad/Secunderabad | Schools will act as a distribution channel | The adaptive engine personalises meaningfully |
| Budget, users, retention, outcomes, costs and conversion are **not known** | Schools will accept a revenue share arrangement | The team can deliver onboarding and support at scale |

*The founders stated the product capabilities. The board has not seen a demo. A one-session product walkthrough is a cheap way to turn these into verified facts.*

## 8. Founder execution: who owns what

The four functions are stated (technology, business and partnerships, operations, product), but who holds which is **not confirmed**. Each founder also manages a geographic zone. Two roles each means two loads, and that is where accountability usually blurs.

| Responsibility | Proposed owner (by function) | Accountable for (one metric each) |
|---|---|---|
| School pipeline, meetings, proposals, contracts, revenue share terms | Business and partnerships | Signed pilots; time to close |
| Pilot delivery: educator orientation, student onboarding, support during school hours, pilot playbook | Operations | % of students activated; founder-hours per school |
| Learning experience: first session, core loop, diagnostics, choice of subject and grade, quality of AI explanations | Product | Week-1 return rate; learning gain on taught topics |
| Reliability, cost to serve, analytics and instrumentation, data security | Technology | Uptime and errors during class; AI/TTS cost per active student |
| Parent communication, payment and conversion | **Unclear: must be assigned** | Parent conversion rate |
| Child privacy, consent and school data agreements | **Unclear: must be assigned** (Technology implements, one named founder owns) | Consent collected for 100% of students before onboarding |
| Learning-outcome measurement (pre/post, comparison groups, honest reporting) | **Unclear: Product, separate from whoever sells** | A pilot outcome report |
| Finance: unit economics, budget, runway | **Unclear: must be assigned** | Net revenue and cost per user |
| Zone ownership versus function ownership | **Unclear** | Decide whether zones mean "relationship owner" while functions own delivery, so a school always knows who to call |

**Main accountability gaps:** (1) nobody owns parent conversion, the moment revenue happens; (2) nobody owns privacy; (3) the person who sells a pilot should not be the person who grades its outcome. Please confirm who holds which role, and whether each founder is full-time.

## 9. Validation experiments

These are cheap tests run before committing significant money. The thresholds are **proposed decision rules for the founders to adjust, not predictions**.

| # | Test | Method | Cost | Success criteria (proposed) |
|---|---|---|---|---|
| E1 | **School demand** | Pick 25–30 schools from the 150 across all four zones. Use a one-page pilot offer naming one outcome, one subject and grade, the team-run onboarding and clear terms. Track each stage. | Founder time | ≥ 8 decision-maker meetings; **≥ 2 signed structured pilots** (named class, named teacher, start date, data agreement) |
| E2 | **Who pays** | In every meeting, put two options to the school: (a) the school pays per student as a program, (b) parents pay ₹299 with the school endorsing it. Record the choice and the reason. | Nil | A clear majority preference. Also find out whether a school revenue share is even wanted. |
| E3 | **First session** | Test the first five minutes with 10–20 students from a friendly school or network, before the pilots start. Watch, don't help. | Nil | ≥ 80% finish a first lesson unaided; students can say what they learned |
| E4 | **Activation and repeat use** | In each pilot class, instrument logins, lessons completed and return visits. | Nil (analytics in Supabase) | ≥ 80% activated in the first class session; ≥ 50% return in week 2 without a teacher prompt (if home use is intended) |
| E5 | **Learning signal** | Baseline diagnostic → 3–4 weeks of use → re-test on taught topics, using *different items* from the baseline. Compare with a class not using the product if a school allows it. | Nil | A measurable gain larger than the comparison group. Reported in full even if negative. |
| E6 | **Parent willingness to pay** | After parents receive a progress report: offer continued access at ₹299 for a stated period, with a refundable deposit or pre-order. Then run `/founder-pricing` (Van Westendorp) on the real responses. | Low | A target set by the founders *before* the test, for example ≥ 20% of parents of active students committing |
| E7 | **Cost to serve** | Log OpenAI and TTS spend per active student per week from the pilots. | Nil | Cost per student per month is a small fraction of net revenue per user (calculated once the school share is known) |
| E8 | **Delivery load** | Track founder-hours per school, from first contact to an activated class. Track support requests and errors during class. | Nil | A number the four founders can sustain across the target number of schools |
| Gate | **Privacy readiness** | Parental consent flow, a data map (what goes to which third-party API), a school data agreement and a deletion policy. Get a legal review. | Low (legal review cost: ask before spending) | **No student is onboarded until this is in place** |

## 10. 30-day validation plan

Thirty days is enough for leading indicators: school demand, the payer decision, activation, early usage, cost per student and an early learning signal. It is **not** enough for term-long retention, solid learning outcomes or paid conversion. Those come in the following term, and the plan sets them up.

**Days 1–7: decide and prepare**
- Answer the questions below. Confirm founder roles and the single owner of each gap in section 8.
- Choose **one subject and one grade band** for the pilots. Freeze other features in the pilot build.
- Set up instrumentation: activation, lessons completed, returns, AI/TTS cost per student.
- Build the privacy gate: consent flow, data map, school agreement template.
- Write the one-page pilot offer: one outcome, a time frame, team-run onboarding, clear terms.
- Start E1 outreach to the first 25–30 schools. Evidence: a log of contacts → meetings → proposals → signatures.

**Days 8–14: sell and polish the first session**
- Hold meetings and demos. Run E2 in every meeting.
- Run E3 with 10–20 students and fix the first five minutes based on what you observe.
- Run `/founder-competitors`: what do these schools and parents already use and pay for?
- Target: first pilot signed, with consent collected.

**Days 15–21: start pilots**
- Team-run orientation and onboarding. Baseline diagnostic (spread through lessons, not one long test).
- Daily E4 tracking. Record every handover that breaks (login, device, network, teacher confusion).
- Log E7 cost and E8 founder-hours from the start.

**Days 22–30: measure and decide**
- Early E5 re-test on the topics taught. Send parents the first progress report and run E6.
- Write a pilot report: what was observed, including bad news.
- **The board meets again with real numbers.**

**Decisions that depend on the results**

| If the day-30 evidence shows… | Then… |
|---|---|
| ≥ 2 signed pilots and activation on target | Continue outreach to the rest of the 150, using the same offer |
| < 1 pilot from about 30 schools contacted | Stop broad outreach. Change the offer, the payer model or the school segment (for example board or fee level) before contacting more schools |
| Students do not come back in week 2 | Pause selling. Fix the core loop and first session before onboarding more students |
| Schools clearly prefer to pay as a program | Rebuild pricing around school contracts. Keep ₹299 for parents as an optional add-on |
| Cost per student is high relative to revenue | Change models, add caching and limit usage before scaling |
| No learning signal on taught topics | Review teaching quality with an education adviser before any paid conversion push |
| Any data or consent problem | Stop onboarding until it is fixed |

**What not to decide yet:** hiring, paid tools, paid marketing or expansion outside Hyderabad/Secunderabad. Wait for the budget and the day-30 evidence.

## 11. Information needed from the founders

These facts materially change the evaluation. The board has not guessed any of them.

1. **Budget:** how much money (and runway) is available for the next 3–6 months?
2. **Current commitments:** any schools already in conversation, interested, or signed (even informally)? Any pilots run before?
3. **Users so far:** how many students have used the product, and is there any activation, retention or outcome data?
4. **Price details:** is ₹299 per month, per term or per year? Who is meant to pay, the parent or the school?
5. **School share:** what revenue share (if any) has been proposed to schools?
6. **Cost to serve:** current monthly spend on OpenAI, TTS, Supabase and Vercel, and the number of active users behind it.
7. **Target segment:** which grades, subjects and boards (CBSE / ICSE / State) and language of instruction? What fee level are the target schools?
8. **Team:** who holds which role and zone, and is each founder full-time?
9. **Access:** do target students use the product in school labs, on shared devices or at home? What are network conditions like?
10. **Privacy:** what consent and data handling exists today, and what student data is sent to third-party APIs?

## Next step in the founder pack

`/founder-competitors` to map what these 150 schools and their parents already use, or `/founder-consumer` to put the pilot offer in front of 100 simulated buyers (schools and parents) before the real outreach.
