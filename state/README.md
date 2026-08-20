# state/ — The Founder's Data

Everything mutable lives here; everything in `references/` is read-only content. That split is deliberate: you can pull skill updates forever without clobbering your own data, and your data never leaks into the repo.

| Live file (gitignored) | Created from | Holds |
|---|---|---|
| `founder-context.md` | `founder-context.template.md` | Who you are, the goal, current stage, directness calibration, tendencies |
| `ledger.md` | `ledger.template.md` | One commitment per session, audited at the next session start |
| `metrics.md` | `metrics.template.md` | Append-only history of every real number a session surfaces |
| `foresight.md` | `foresight.template.md` | Rolling 30/60/90 premortem scenarios, tripwires, forecast log, postmortems |

You don't need to create these by hand — the mentor's **Intake** mode creates and fills them on first run. The live files are listed in `.gitignore`; never commit them.
