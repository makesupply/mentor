# Foresight Protocols — Premortem, Tripwires, and the Learning Loop

Read when running Foresight mode, when a tripwire fires, and during the quarterly premortem re-run. Condensed from Report 10 (`references/research/report-10-foresight-systems.md`); scenario raw material lives in `references/failure-taxonomy.md`. State lives in `state/foresight.md`.

The system in one sentence: imagine the failure before it happens (premortem), convert the top scenarios into observable numbers with pre-agreed responses (tripwires), check them on a short mechanical cadence, and when one fires, learn without blame (postmortem) — then refresh before the whole thing becomes ritual.

## 1. The Premortem — administered, write-first

Evidence: prospective hindsight ("it HAS failed — explain why") generates measurably more, and more concrete, action-based reasons than "it might fail" framing — the widely cited ~30% figure from Mitchell, Russo & Pennington 1989 [peer-reviewed]. State the caveat when it matters: the study measured the NUMBER of reasons generated, not their accuracy — popularizations blur this. Klein operationalized it (HBR 2007); documented use at NASA, Google, the US Army [practitioner/documented].

Solo-founder administration (the silent-writing discipline is the active ingredient — it exists to prevent anchoring, and for a solo founder the anchor is their own optimism):

1. Set the frame exactly: "It is [date +90 days]. The plan failed — not stumbled, failed completely. You're writing the autopsy."
2. WRITE before discussing: the founder lists every reason for the failure — push past the first three (those are the obvious ones; the value is in the tail). No rebutting, no rationalizing, no "but I'd handle that" until the list is done.
3. Rank by probability × severity as a JUDGMENT CALL, spoken aloud — never as a numeric matrix score (see §6).
4. For the top 3–5: what would you SEE, in a number, before this scenario arrived? That's the tripwire candidate (§2).
5. Revise the plan against the top scenario now — one prevention action becomes the session commitment.

## 2. Tripwires — the premortem's output

Doctrine: US Army decision points — pre-identified conditions in time/space where a decision MUST be made, war-gamed before execution, not improvised during it [military-institutional doctrine]. Boyd's OODA frame: pre-set triggers accelerate observe/orient — the founder who has already decided what a signal means acts faster than the one re-deliberating each week.

A tripwire has three parts, all written into `state/foresight.md`:
- **Signal** — a leading indicator the founder actually observes (runway in weeks, pipeline conversion, biggest-account %, DSO, CPM trend, first-reorder rate), never a lagging one (revenue after the fact). See the early-warning table in `references/failure-taxonomy.md`.
- **Threshold** — one number. "Monitor cash" is a ritual; "runway < 6 weeks" is a tripwire.
- **Pre-agreed response** — decided NOW, calm, in writing: "→ freeze discretionary spend, invoke the cash plan." The whole point is deciding before the stress arrives (`crisis-protocols.md` decision hygiene).

Statuses: ARMED / FIRED / RETIRED. A fired tripwire triggers two things: the pre-agreed response, and a blameless postmortem (§5). A tripwire nobody checks is worse than none — it manufactures false safety.

## 3. Reference-Class Check — the outside view on any forecast

Evidence: the planning fallacy — forecasters build optimistic inside-view scenarios and ignore base rates [peer-reviewed, Kahneman & Lovallo]. Flyvbjerg's reference-class forecasting measurably reduced cost overruns where governments applied it; his megaproject data: 9 of 10 rail projects overestimated demand (avg +106%), only ~8.5% of megaprojects hit both cost and time [peer-reviewed]. Kahneman: the outside view is "the single most important piece of advice regarding how to increase accuracy in forecasting."

Administer on ANY numeric forecast the founder makes (launch revenue, timeline, payback):
1. "What's the reference class — comparable attempts by comparable operators?" (Use `stage-playbooks.md` / `b2b-playbook.md` benchmarks where the vertical matches; the founder's own past launches are the best class of all — pull them from `state/metrics.md`.)
2. "What actually happened across that class?" Base rate FIRST.
3. "Now argue your specific adjustment — with evidence, not enthusiasm."
Elicitation rules [peer-reviewed, Tetlock/Mellers]: force numeric probabilities, not verbal hedges ("likely" means nothing); fine increments beat coarse buckets — superforecasters' 1% granularity was real signal; log the forecast with a revisit date in `state/foresight.md` so calibration becomes checkable. Honest transfer note: training alone improves forecasting only modestly (Brier 0.21→0.19); the bigger gains came from structured, scored, repeated review — which is exactly what the forecast log builds [peer-reviewed].

## 4. Cadence — short, frequent, and refreshed before it rots

Evidence [industry benchmark, large-N, not peer-reviewed — say so]: teams reviewing goals weekly completed 43% more objectives than monthly/ad-hoc reviewers; check-ins peaked in value at 15–20 minutes and DECLINED past 45; skipping the weekly rhythm tripled abandonment of the whole system.

The contract, written into `state/foresight.md`:
- **Weekly (inside Weekly Review, ~5 min, mechanical):** has any tripwire fired? Any signal trending toward its threshold? Nothing else — no re-litigating scenarios weekly.
- **Monthly (~15–20 min):** are the top failure scenarios still the right ones, given what changed? Add/retire tripwires.
- **Quarterly (inside the quarterly review):** re-run the full premortem from scratch. A 90-day-old failure narrative is stale by construction.
- Ritualization warning [practitioner, unquantified — honest]: the value decays the moment the exercise stops being tied to a live, consequential decision. If the last two monthly refreshes changed nothing, say so and dig — either the plan is static (a finding) or the exercise has gone through the motions (a worse finding).

## 5. The Learning Loop — blameless postmortem when something fires or misses

Evidence: the debrief/AAR meta-analysis — 61 studies, 915 teams — found structured after-action reviews improve performance d = 0.79, with effectiveness driven by objective data (not recollection) and timeliness [peer-reviewed]. Blameless-postmortem method is mature practitioner doctrine (Allspaw/Etsy, Google SRE), not outcome-validated in controlled studies [practitioner].

Run within days of a tripwire firing, a plan missing, or a forecast busting — administered:
1. **What happened** — timeline from the numbers in `state/metrics.md`/`state/foresight.md`, not memory.
2. **How it made sense at the time** — local rationality: what did the founder actually know when they decided? No hindsight prosecution. (For a solo founder, blamelessness means no shame spiral — self-blame is as corrosive to learning as scapegoating, and `unblocking-protocols.md` feedforward rules apply.)
3. **The second story** — "human error" is a symptom; what system condition allowed it? Ask "how," not "why did you."
4. **One system change, shipped** — the crisis-is-curriculum rule (doctrine Law 10). Log it in the postmortem section of `state/foresight.md`.

## 6. What NOT to build — evidence-backed exclusions

- **No numeric risk-matrix scores.** Cox 2008 [peer-reviewed]: likelihood×impact matrices correctly rank <10% of random hazard pairs, can rate a smaller risk HIGHER than a bigger one, and multiplying ordinal categories ("3×4=12") is false precision — in some configurations "worse than useless." Hubbard's term: an analysis placebo. Rank scenarios by spoken judgment; spend the rigor on tripwire thresholds instead.
- **No paperwork checklists.** Pronovost's checklist cut ICU line infections 66% WITH stop-authority and culture change; large replications without them (Ontario 200,000+ procedures, "Matching Michigan") found NO effect [peer-reviewed both directions]. A checklist works only when a skipped step halts the process — for a founder, that means a tripwire response the founder has pre-committed to actually execute, not a list they read.
- **Scenario sketching stays lightweight.** Evidence that formal scenario planning improves decisions is thin and case-study-based [honest]. Keep the mechanism that plausibly works — naming more than one future and the observable signal that distinguishes them — as a single page, not a Shell-style exercise.

## Coaching hooks

- "It's ninety days from now and the plan is dead — not wounded, dead. Write me the autopsy. Don't defend anything yet; just write."
- "You gave me a forecast. What's the base rate for people like you trying this? Nine of ten rail forecasts were off by an average of 106% — argue your adjustment AFTER the base rate."
- "'Watch cash closely' is not a plan. Give me the number that fires the alarm and what you'll do the day it fires — decided today, while you're calm."
- "A tripwire fired and you executed the response you wrote a month ago. That's the system working. Now the postmortem: what did you know at the time, and what system change does this buy?"
- "Your last two monthly refreshes changed nothing. Either your plan hasn't moved in sixty days — which is its own finding — or this has become theater. Which is it?"
