# Mentor — A Blunt AI Business Mentor for Founders

**A power coach, performance coach, and business therapist in one installable skill — with memory, modes, and a sourced evidence base.**

Generic AI is agreeable and amnesiac. Ask it about your business and you get encouragement, seven suggestions, and no follow-up — ever. Founders don't need another pleasant chat; they need direct challenge grounded in evidence, ONE commitment at a time, and someone who remembers what they promised last week and asks about it first. That is a process, and process can be specified and installed. This repository is that specification.

## What changes, concretely

| Without | With |
|---|---|
| "Great progress! Here are 7 ideas…" | The single constraint gating revenue, named, with the founder who faced it and what they did. |
| Every session starts from zero | Session starts by auditing last session's commitment: kept, broken, or renegotiated. |
| Invented statistics delivered confidently | Every claim carries an evidence tier — [peer-reviewed] / [practitioner] / [inference] — and benchmarks name their vertical. |
| Vague intentions ("I'll try to launch soon") | One commitment, as an if-then plan, with a deadline, written to a ledger. |
| Endless agreeable conversation | A session with no number, no hard thing, and no commitment doesn't close — drift itself gets named. |

## The mode system

The skill routes each session by what the founder says:

| Mode | Triggered by | What happens |
|---|---|---|
| **Intake** | First run | Discovery interview → builds the founder-context file, sets the directness contract (how hard to push, 1–10), ends with a real commitment |
| **Quick Counsel** | One tactical question | Direct answer with the doctrine citation — no ceremony |
| **Validate** | Pre-revenue, "is this idea worth building" | Evidence-ladder placement, Mom-Test discovery, proceed/pivot/kill gates set before the test |
| **Strategy Session** | "What should I focus on" (default) | Bill Campbell's five-topic 1:1: personal check, gate metrics, the one constraint, doctrine direction, close |
| **Unblock** | "I'm stuck / overwhelmed / can't start" | Names the block, administers the matched intervention (WOOP, fear-setting, if-then, complicity question) step by step |
| **Decision Gate** | "Should I X or Y" | Reversibility triage, compressed fear-setting, doctrine check, a clear recommendation — recorded and audited later |
| **Weekly Review** | "Weekly review / check in" | Ledger audit, week-over-week gate numbers, tripwire check, focus accounting, boundary check, top-3 → one commitment |
| **Foresight** | "What could go wrong", a new quarter or launch ahead | Rolling 30/60/90 premortem → tripwires with pre-agreed responses → blameless postmortem when one fires |
| **Crisis** | Cash crunch, platform ban, defect, legal notice | Strict triage: protect cash → size exposure in numbers → communicate → fix → build the system the crisis teaches |
| **Hard Truth** | "Audit me / give it to me straight" | Full audit against the doctrine laws, failure patterns, and the founder's own recorded tendencies |

## How it works

- **`SKILL.md`** — the always-loaded constitution: voice rules, mode routing, session close protocol.
- **`references/`** — read-only knowledge modules loaded per mode: the 12 doctrine laws, 12 founder dossiers, stage playbooks ($0→$1M→$10M→$100M), unblocking protocols, plus seven entrepreneur modules (validation, finance, marketing, sales & pricing, hiring, crisis, operating cadence).
- **`state/`** — the memory that makes candor personal: founder context, a commitment ledger audited every session, and an append-only metrics history. Created from templates at Intake, gitignored, never committed.

## The evidence base

Seven deep-research reports (200+ cited sources) sit in `references/research/`: documented founder case studies (Gymshark, Ridge, Native, Spanx, RXBAR, ButcherBox, Obvi, AG1, True Classic, MVMT, Liquid Death, HexClad), stage benchmarks for bootstrapped DTC, peer-reviewed coaching/performance psychology (implementation intentions, WOOP, feedforward, radical candor), and B2B founder case studies (Mailchimp, Basecamp, Ahrefs, ConvertKit, Atlassian, Zapier, DesignJoy, McKinsey/Bower, plus manufacturing and wholesale cases). The distilled modules cite them; the mentor labels evidence tiers out loud and names the vertical a benchmark came from before applying it to yours.

## Install

**Claude Code — personal (all projects):**

```bash
git clone https://github.com/makesupply/mentor.git ~/.claude/skills/mentor
```

Windows: clone into `%USERPROFILE%\.claude\skills\mentor\`.

**Claude Code — per project:** clone or copy the folder to `<repo>/.claude/skills/mentor/` instead.

**claude.ai:** zip the folder so `SKILL.md` sits at the top level of the zip, then upload under Settings → Capabilities → Skills. Note: on claude.ai the ledger can't persist as a file between chats — keep it in a Project's knowledge instead; Claude Code is the full experience.

**First session:** invoke `/mentor`. It will notice there's no founder context and run Intake — a discovery interview that builds your files and ends with your first commitment. From session two onward, expect the ledger audit first.

## What this is not

- **Not therapy or clinical care.** The skill carries a wellbeing floor: persistent clinical-grade strain gets a plain "get real professional support," then continued business help.
- **Not financial, legal, or tax advice.** Consequential irreversible moves in those domains always get "professional check" attached to the recommendation.
- **Not timeless.** Research gathered August 2026; benchmarks and revenue figures age. The mentor says "as of the research" and verifies live when precision matters.
- **Not universal doctrine.** The evidence base is deepest in bootstrapped DTC e-commerce. The laws carry a scope note; the mentor translates rather than transplants for other business models, and says so.

## Customizing

Edit `state/founder-context.md` freely — it's yours, including the directness calibration (1–10). Adjust or extend `references/` modules for your industry; add modes by extending the routing table in `SKILL.md`. Keep user data out of `references/` — the state/content split is what makes updates safe.

## What's in the box

```
SKILL.md                      # constitution: voice, modes, close protocol
references/
  doctrine.md                 # the 12 laws, with scope note
  founder-dossiers.md         # 12 documented founders, indexed by situation
  stage-playbooks.md          # $0→$1M→$10M→$100M gates and levers
  b2b-playbook.md             # B2B structure diagnosis, patterns, dossiers
  failure-taxonomy.md         # real base rates, failure causes, early-warning signals
  foresight-protocols.md      # premortem, tripwires, reference-class checks, postmortems
  unblocking-protocols.md     # block table + 10 administered interventions
  validation-playbook.md      # idea → first paying customer
  finance-fundamentals.md     # unit economics, cash, funding ladder
  marketing-acquisition.md    # channel doctrine, creator playbook, paid discipline
  sales-and-pricing.md        # pricing architecture, raise protocol, negotiation
  hiring-and-delegation.md    # delegation ladder, leverage menu, keeper test
  crisis-protocols.md         # triage order + per-crisis table
  operating-cadence.md        # daily/weekly/quarterly/annual rhythm
  research/                   # the sourced research reports (160+ citations)
state/                        # your data: context, ledger, metrics (templates + README)
examples/                     # sample sessions showing the register
```

## Versioning

SemVer: MAJOR = mode-system/voice/state-format changes; MINOR = new modules, modes, or research refreshes; PATCH = corrections. Changelog in [Keep a Changelog](https://keepachangelog.com/) style. Dated research claims are never silently edited — refreshes bump MINOR and update the research-date line.

## License

MIT-0 — use, modify, redistribute freely. Attribution appreciated, not required.
