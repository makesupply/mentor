# Finance Fundamentals — The Numbers Layer

Read when the founder doesn't know their numbers, faces a pricing/spend/funding decision, or describes progress in adjectives ("growing," "doing well," "almost profitable"). Adjectives are the tell. Convert every adjective to a number before coaching anything else.

## Unit economics from first principles

The causal chain, in order — each stage funds the next: **contribution margin funds acquisition; acquisition at payback funds growth; growth without margin is just expensive shrinking.** A founder who can't recite their chain is guessing.

| Term | Definition — tight, no substitutes | Trap |
|---|---|---|
| Price | What the customer actually pays after discounts, not list | Founders quote list price |
| COGS | Landed cost per unit: product + freight + duties + packaging | Freight and duties "forgotten" |
| Contribution margin | Price − COGS − shipping-to-customer − payment/channel fees − per-order variable costs | Quoting gross margin and calling it contribution |
| CAC | Fully-loaded acquisition cost ÷ NEW customers (ad spend + creative + agency/tools) | Blending new and returning customers to flatter it |
| Payback period | Months until cumulative contribution from a customer repays CAC | Computed on revenue instead of contribution |
| LTV | Cumulative contribution per customer over a defined window (12-month default) — not lifetime fantasy | Projected 5-year LTV justifying today's CAC |
| LTV:CAC | ≥3:1 viable, below 2:1 unprofitable [practitioner, doctrine.md Law 3] | Rising ratio from shrinking spend, not improving economics |

**Administer — the Unit Economics Walk** (any pricing/spend session where these aren't known cold):
1. Make the founder build one unit's P&L out loud: price → subtract each cost line → contribution dollar. No spreadsheet hiding; say the numbers.
2. Make them state CAC from last 30 days' actual spend and actual new customers. "Roughly" is a no.
3. Divide: how many contribution dollars per order, how many orders to repay CAC, how many months at their real reorder rate?
4. If any input is unknown — stop the session's original topic. The homework is the number, due in 48 hours, as an if-then commitment (unblocking-protocols.md, If-Then Builder).

First-order contribution can be thin or negative in subscription models if 12-month LTV underwrites it — that's a strategy, not an accident, and the founder must be able to say which one theirs is (stage-playbooks.md, Stage 1).

## The weekly cash ritual

Companies die of cash, not of losses [practitioner — universally documented failure mode]. At Stage 1–2 the founder computes this personally, weekly, same day, in one place. No delegation, no dashboard excuse — same discipline as doctrine.md Law 3.

Administer as three questions, in order, answers in numbers:
1. **Cash on hand** — bank balance today, minus known committed outflows (inventory POs, tax set-asides, debt payments). Not "the account," the number.
2. **Burn** — trailing 4-week average net cash out. Not last month's P&L; cash.
3. **Runway in weeks** — cash ÷ weekly burn. Weeks, not months: months hide decay, weeks force action.

Runway under 12 weeks → crisis footing regardless of how revenue "feels" — route to crisis-protocols.md. A founder who last computed this "a while ago" gets this ritual as their session commitment before any growth topic is allowed.

## Cash conversion cycle

CCC = days inventory outstanding + days sales outstanding − days payables outstanding. Plain terms: how many days a dollar is frozen between paying suppliers and collecting from customers.

- **Inventory is frozen cash.** Every unit on a shelf is money that can't buy ads, and gut-feel over-ordering is a documented near-death pattern (doctrine.md Law 7).
- **Subscription/prepay flips CCC negative** — customers pay before inventory is bought, so growth generates cash instead of consuming it (doctrine.md Law 6; benchmarks in stage-playbooks.md). This is the structural reason bootstrap + subscription works at all.
- **Positive-CCC growth eats cash on the way up.** A founder growing fast with 60+ days locked in inventory can be profitable on paper and broke in fact. Make them say their CCC in days; if they can't, that's the finding.

## Pricing floor rules

A price is not real until its margin survives the full gauntlet. Administer as a stress test — make the founder compute each line against their actual price:

1. Start from realistic street price (include the discount a typical customer actually gets — welcome code, bundle, sale cadence).
2. Subtract COGS, fulfillment, payment processing, and channel fees (marketplace/retail take if any channel beyond DTC is planned — Law 4 says one is).
3. Subtract a returns/refunds/chargebacks allowance from their own trailing rate — not zero.
4. What's left must cover CAC at their real payback tolerance **and** leave contribution.

If the price only works with zero discounting, zero returns, and free acquisition, it is a hope, not a price. Rule of administration: **the floor is set before launch and discounts are designed down to it — never discovered after.** Underpricing driven by fear of rejection is a psychology block, not a math problem — route to unblocking-protocols.md (mental contrasting) once the math is on the table. Deeper pricing strategy: sales-and-pricing.md.

## The funding ladder

Doctrine.md Law 6 sequence — each rung is rational only when the prior rung is genuinely exhausted:

| Rung | Rational when | Not rational when |
|---|---|---|
| Bootstrap + prepay | Default. Negative-CCC models self-fund growth | Never irrational; the question is pace |
| Debt / RBF | Unit economics proven, cash gap is inventory/timing, revenue consistent enough to service repayment (stage-playbooks.md, Stage 2) | Funding losses or unproven economics — debt on a broken model just schedules the death |
| Equity | Land-grab dynamics where speed beats ownership, after debt is truly exhausted | Funding operating burn a working model should cover; raising because it feels like a milestone |

**Dilution math — administer before any raise talk proceeds.** Make the founder compute, out loud:
1. Ownership after this round — and after the two future rounds this one implies at assumed dilution per round.
2. Their proceeds at a plausible exit under that final ownership, versus their proceeds bootstrapping to a smaller exit at full ownership.
3. The RBF/debt alternative priced in dollars: total repayment cap versus what the same capital costs in equity at the exit they claim to believe in.
Founders who've run this math raise less, later, or not at all [practitioner — consistent with the bootstrap cases in doctrine.md Law 6]. A founder who won't run it is buying status, not capital — name it.

## Financial red flags

Any of these appearing in a session overrides the founder's agenda for that session:

| Red flag | What it actually means | First question |
|---|---|---|
| Revenue up, cash down | Growth is consuming working capital, or margin is fictional | "Where is the cash going — inventory, CAC, or discounts?" |
| Discounting to make top-line | Buying revenue below the pricing floor; trains customers to wait | "What's contribution on a discounted order? Compute it now." |
| Growth outrunning payback | Every new customer deepens the cash hole before repaying it | "Runway in weeks vs payback in months — which is longer?" |
| Single customer/channel concentration | One partner's policy change is an extinction event (doctrine.md Law 4) | "What % from the top source? What happens the week it halves?" |
| "Profitable except for ads" | Not profitable. CAC is a real cost of the model | "So the model loses money acquiring customers. What's the fix — LTV, margin, or CAC?" |
| No tax/liability set-aside | A surprise bill compounds the next crisis (Ridge precedent, doctrine.md Law 7) | "Where does tax money live right now?" |

## Numbers the founder must know cold — by stage

Cold = answerable in the session, unprompted, within 10%. Vertical benchmarks live in stage-playbooks.md — check answers against that file, don't invent new targets.

- **Every stage, every week:** cash on hand, weekly burn, runway in weeks.
- **Stage 1 ($0→$1M):** price and street price; contribution margin per order; CAC (founder-tracked, weekly — Law 3); second-order/repeat rate (Law 2); payback in months.
- **Stage 2 ($1M→$10M):** everything above, plus monthly churn and skip-vs-cancel split; CCC in days; revenue % of largest channel; inventory weeks-of-cover; debt service coverage if leveraged.
- **Stage 3 ($10M→$100M):** contribution by channel and by SKU; NRR; CCC trend; fixed-cost break-even revenue; ownership % and option-pool position.

A founder missing a stage-appropriate number gets it as homework in if-then format before the next session. Repeat misses go to the ledger as a pattern — that's an accountability conversation (operating-cadence.md), not a finance one.

## Coaching hooks

- "Give me the number, not the adjective. 'Growing' is not a metric — what was contribution per order last week?"
- "You want to talk growth. I want to know your runway in weeks. If you can't tell me, that IS the session."
- "Walk me through one unit: price, minus what, minus what, leaves what? Out loud. If you stall anywhere, we found the problem."
- "Before we discuss raising: what do you own after this round and the two it implies — and what's that worth versus the debt you haven't priced?"
- "Revenue is up and cash is down. One of those numbers is lying to you about how it's going. Which one do you pay suppliers with?"
