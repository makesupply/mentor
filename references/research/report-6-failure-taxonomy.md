# Why Small Businesses and Startups Fail, Stall, or Plateau: A Failure-Cause Taxonomy with Base Rates

## Overview

This report builds an evidence-graded taxonomy of small-business and startup failure, stall, and plateau causes for use in an AI mentor system. Every claim is tagged by evidence type — [government data], [peer-reviewed], [practitioner survey], or [anecdotal] — with sample sizes and years where available, and self-reported founder attributions are flagged for attribution bias (failed founders tend to externalize blame onto financing/market conditions and under-report their own managerial or strategic errors).

## 1. Survival Base Rates

### Government data: the actual survival curve

The Bureau of Labor Statistics' Business Employment Dynamics (BED) program tracks every private-sector establishment cohort opened since March 1994 [government data]. Averaged across cohorts opened 1994–2024, roughly **79 of 100** new private-sector establishments survive to year one, **~49 of 100** survive to year five, and **~34 of 100** survive to year ten. This directly contradicts the popular "90% fail in year one" myth — the actual first-year failure rate is closer to 20%, not 90%.

| Milestone | Survival rate (all industries) |
|---|---|
| Year 1 | ~79.6% |
| Year 5 | ~48.9–50.6% |
| Year 10 | ~33.9–34.7% |

Source: BLS BED, 1994–2024 cohorts.

Survival varies meaningfully by industry [government data]:

| Sector | 1-yr survival | 5-yr survival | 10-yr survival |
|---|---|---|---|
| Agriculture, forestry, fishing | 87.5% | 66.2% | 50.5% |
| Health care & social assistance | 82.7% | 55.5% | 39.5% |
| Real estate, rental & leasing | 83.9% | 58.7% | 42.2% |
| Construction | 76–77% | 48–54% | 31–40% |
| Restaurants/food services | 77–83% | 35–45% | — |
| Information | 74.9% | 44.3% | 29.1% |
| Mining/oil & gas | 79.4% | 40.2% | 24.5% |

Source: BLS BED Table 7, industry-level breakdowns.

A peer-reviewed reanalysis using 1.9 million establishment-level BLS microdata (81,000 restaurants, 20-year window, western US) found that only **17%** of independent full-service restaurants failed in year one — lower than the 19% average for all other service-providing startups — directly refuting the "90% of restaurants fail in year one" folklore claim [peer-reviewed]. Median restaurant lifespan is about 4.5 years.

### International comparisons

Cross-country OECD data (structural business demography, multiple cohorts) shows the "most homogenous" survival benchmark internationally is roughly **60% survival at 3 years, ~50% at 5 years, ~40% at 7 years**, with substantial national variance: 3-year survival ranges from ~55% (Netherlands, Denmark) to over 70% (Sweden) [government data]. A 2023 Korean National Assembly audit found domestic Korean startups had only a **33.8%** 5-year survival rate, versus an OECD-28 average of **54.6%**; Sweden topped the list at 63.3%, the US came in near the OECD average at 50.2%, and only Portugal and Lithuania scored lower than Korea [government data]. Roughly half of newly created firms across OECD regions fail to survive their first three years on average [government data].

### Failure by business model and funding type

Venture-backed startups show markedly different — and in some framings, worse — attrition than the broader small-business population. Practitioner analysis states that **~70%** of venture-backed startups shut down or fail to return capital within their funding lifecycle, while survey-based long-run failure estimates across all startups (including non-VC-backed) run closer to **90%** [practitioner survey]. Funding-stage attrition estimates (aggregated industry sources, not a single controlled study) suggest ~60% of startups fail between pre-seed and Series A, and ~35% of Series A companies fail before reaching Series B [practitioner survey — unverified methodology]. These figures should be treated cautiously: they aggregate different definitions of "failure" (shutdown vs. failure to return capital vs. acquihire) and are not government-verified.

## 2. Failure-Cause Research: Academic vs. Practitioner Evidence

### Practitioner autopsies (CB Insights): base rates by cause

CB Insights' recurring analysis of startup post-mortems (samples ranging from ~100 to 431 companies across successive updates, most recent update citing 431 VC-backed shutdowns since 2023) is the most widely cited practitioner source [practitioner survey]. Because founders often cite multiple causes, percentages exceed 100%. Two versions of the ranking circulate depending on vintage:

| Cause | % of post-mortems citing it | Note |
|---|---|---|
| Ran out of capital / cash | 70% (2026 update) or ~29–38% (2021–22 vintage) | CB Insights frames this as usually the *final* symptom, not the root cause |
| No market need / poor product-market fit | 42–43% | Most-cited *root* cause across multiple vintages |
| Bad timing / macro conditions | 29% | 2026 cohort, hit climate/food/blockchain hardest |
| Wrong team / team problems | 20–23% | |
| Got outcompeted | 19–20% | |
| Unsustainable unit economics | 19% | |
| Pricing/cost issues | 15–18% | |
| Bad product | ~17% | |
| Lack of business model | ~17% | |
| Lack of focus | 13% | |

This is [practitioner survey] evidence with an important caveat: the data is founder-self-reported in post-mortem blog posts, is not a random or representative sample of failed startups (only companies that publish post-mortems are counted), and is subject to strong **attribution bias** — founders systematically cite external/market causes ("bad timing," "no market need," "ran out of capital") more than internal ones (poor leadership, bad hiring, weak strategy), because self-serving bias predicts people attribute failure to external circumstances rather than their own decisions.

### Practitioner surveys (Skynova and similar)

Skynova's founder survey (~500 founders, 2022 vintage) found different weightings, reflecting a broader (non-VC-only) sample [practitioner survey]: lack of financing/investors (47%), running out of cash (44%), pandemic/bad timing (33%), team disharmony (21%). Notably 91% of surveyed founders blamed lack of finance or cash in some form — a striking convergence on financial causes versus CB Insight's product-market-fit framing, likely reflecting sample differences (VC-backed tech vs. general small business) as well as identical self-report attribution bias.

### Academic/peer-reviewed literature: four-domain taxonomy

Systematic literature reviews converge on a four-domain taxonomy that is more methodologically rigorous than post-mortem surveys, since it synthesizes findings across dozens of controlled or archival studies rather than self-reports alone [peer-reviewed]:

- **Financial**: limited access to capital, poor financial management/liquidity, excessive leverage — cited in the majority of the 95-article systematic review (1968–2016) as among the most frequent causes
- **Managerial/organizational**: lack of experience, poor strategy, weak team capacity — found to be the *most frequently cited* domain, appearing in 35 of 41 reviewed articles in one meta-synthesis
- **Product-market**: inadequate market research, unbeatable competition, wrong pricing, poor product-market fit
- **Legal/environmental**: regulatory burden, macroeconomic instability, institutional support gaps — more prominent in developing-economy studies than developed-economy ones

A 2020 systematic review of 74 papers on new-venture failure similarly grouped causes into resources (human/financial capital), strategic/managerial decisions, product-related issues, and contextual/environmental factors [peer-reviewed]. A separate quality-management-framework study synthesizing quantitative founder data found the CB Insights 12-category taxonomy is largely subsumed within four broader domains (financial, managerial, product-market, legal), and concluded managerial/organizational factors dominate at 35/41 studies [peer-reviewed]. Academic work also distinguishes **"reported" causes** (what failed founders say) from research on **attributional style**, explicitly noting founders' explanations are shaped by self-serving attribution bias — a 45-publication review found scholarship has progressed from studying "perceived" causes toward more objective firm-dynamics analysis precisely because self-reports are unreliable [peer-reviewed].

### Evidence-quality comparison table

| Evidence tier | Source example | Sample | Strength | Key limitation |
|---|---|---|---|---|
| Government data | BLS BED survival tables | Full establishment census, 1994–2024 | Highest — census-level, no self-report bias | Reports survival, not causal attribution |
| Peer-reviewed | Systematic literature reviews (95, 74, 41 articles) | Aggregated multi-study | Strong internal validity, synthesizes many designs | Categories vary by author; qualitative coding subjectivity |
| Practitioner survey | CB Insights post-mortems (100–431 firms), Skynova (~500 founders) | Self-selected, non-random | Useful directional signal, widely cited | Convenience sample; self-report attribution bias; percentages don't sum to 100 |
| Anecdotal | Individual startup blog post-mortems | N=1 | Illustrative only | Not generalizable |

## 3. The Stall/Plateau Literature

### Greiner's growth-stages model: empirical status

Greiner's (1972) model proposes firms evolve through five growth phases — creativity, direction, delegation, coordination, collaboration — each ended by a specific "crisis": leadership, autonomy, control, red tape, and (a debated) internal-collaboration crisis [peer-reviewed]. Evolutionary periods run roughly 4–8 years depending on industry speed.

Empirical testing is mixed, which is an important nuance for an AI mentor to communicate honestly:

- Tushman et al. (1986), studying a large cross-industry, cross-country sample of firms, found **no general empirical support** — no consistent pattern in the sequence of frame-breaking organizational changes matching Greiner's stages [peer-reviewed].
- Sukova (2020), studying six large Czech automotive firms, found empirical support for Greiner's model, showing increased vertical differentiation/centralization consistent with stages 3–4 [peer-reviewed].
- A fuzzy-classification study of 97 Hungarian industrial/commercial firms successfully mapped companies onto Greiner stages and cross-validated it against a parallel logistics-maturity model, lending partial support [peer-reviewed].
- A related model (Churchill & Lewis, 1983) tested by Eggers et al. (1994) on a randomly selected sample of small firms found "substantial support," though considerable variability remained between firms [peer-reviewed].
- A verified 11-stage "Nascent Organization Structure Sequence" tested against 62 Inc. 500 "gazelle" high-growth entrepreneurs found 9 of 11 stages statistically significant (p<.05) [peer-reviewed].

**Bottom line for the AI mentor**: Greiner's model is a useful heuristic and diagnostic frame (leadership crisis → need delegation; control crisis → need coordination systems) but is *not* strongly empirically validated as a universal, sequential law — evidence is mixed and sample-dependent, with larger cross-national tests failing to confirm it and smaller single-country/single-industry tests partially confirming it.

### What causes plateaus (founder skill ceilings, complexity thresholds)

Systematic reviews of SME and entrepreneurial failure repeatedly identify **founder skill/versatility limits** and **inability to delegate** as recurring plateau drivers, distinct from outright failure: lack of necessary managerial skills, lack of strategic-management knowledge, and "threat rigidity" (doubling down on familiar strategies under stress) appear across multiple studies as causes of stalled — not necessarily terminated — growth [peer-reviewed]. The Founder's Dilemmas research (cited via CB Insights-adjacent literature) found that **roughly 65% of failed startups involved cofounder conflict** as contributing or primary cause, which is conceptually adjacent to the plateau phenomenon of teams that cannot evolve past founder-centric decision-making [practitioner survey].

Directly relevant to the "valley of death" between growth stages: no single peer-reviewed study in this search directly quantifies base rates for stage-transition failure with the rigor of the BLS survival data — this remains a genuine evidence gap. [SOURCE MISSING] for a quantified base rate on the specific "valley of death" transition (e.g., from $1M to $10M revenue). What is well-documented is the *qualitative* mechanism: as firms scale, informal founder-centric coordination breaks down and requires new organizational systems (Greiner's core insight), and firms that fail to build those systems in time stall rather than fail outright [peer-reviewed].

### What distinguishes plateau-breakers

The literature is thinner here than on failure causes, but converges on: deliberate delegation and professionalization of management (validating Greiner's "delegation" and "coordination" phases empirically supported in the Hungarian and Czech studies above), and — per the founder mental-health research below — boundary-setting behavior that prevents burnout-driven decision degradation [practitioner survey].

## 4. Early-Warning Indicators

### Financial/credit-model literature

The dominant academic tradition for predicting business failure is Altman's **Z-Score** model (1968) and its SME-adapted variants (Z′, Z″) [peer-reviewed]. Key documented thresholds:

- Z″ > 2.99: "safe zone"; 1.81–2.9: "grey zone"; below 1.81: "distress zone," historically associated with near-certain bankruptcy in Altman's original sample [peer-reviewed].
- Prediction accuracy degrades sharply with time horizon: one Indonesian study found the Altman Z-Score achieved 51.8% accuracy one year before bankruptcy, but only 11.4% four years out; a rival Ohlson O-Score performed better at longer horizons (73.6% at one year, 58.5% at three years) [peer-reviewed].
- A large Slovak SME study (149,618 companies, 2009–2016, 1,575 failures) found non-financial variables (e.g., firm age, sector) significantly improve discriminatory power beyond the financial ratios alone, while macroeconomic variables did not help and sometimes hurt out-of-sample accuracy [peer-reviewed].
- The newer "Omega Score" (built on a large SME default dataset) found that **change in management, employee turnover ("firing ratio"), and mean employee tenure** significantly improve default prediction beyond traditional financial ratios — an empirically validated non-financial early-warning signal [peer-reviewed].
- Modern SME credit-scoring research using random forest/graph neural network methods improves accuracy over Z-Score baselines (e.g., one comparison: Altman-style Delphi model 69% accuracy vs. random forest 83%) [peer-reviewed].

### Leading indicators from post-mortem literature (non-financial)

Skynova's founder survey identified specific pre-failure setbacks self-reported by struggling founders [practitioner survey]: lack of marketing (45%), not growing fast enough (42%), losing a major client — i.e., **customer concentration risk** (26%), and inability to scale when desired (25%). CB Insights' 2026 cohort analysis states many of the 431 shut-down VC-backed companies showed "measurable deterioration in health" before failure, though the specific metrics tracked are not fully disaggregated in available sources [practitioner survey].

### Founder health as a leading indicator

Multiple independent surveys converge on founder burnout as both a symptom and a contributing cause of failure [practitioner survey, not peer-reviewed on causal effect]: Octopus Ventures analysis attributes an estimated 65% of startup failures to founder burnout or internal conflict rather than market conditions — treat this figure cautiously, as it is a venture-firm estimate, not an independently audited academic study. Convergent survey data: 54% of founders (Sifted, N=138, 2025) experienced burnout in the past 12 months; 87.7% of entrepreneurs (Founder Reports aggregate, N=227 across 46 countries) report at least one mental-health struggle; a larger Lehigh University/Nasdaq Entrepreneurial Center study (N=300+ founders) found founders unable to hold work-life boundaries had 67% high-burnout rates versus just 6% among boundary-setters — a documented behavioral lever, not just a correlation [practitioner survey]. A Forbes-featured 2024 snapshot (N≈400 founders) found 93% show signs of mental-health strain, with anxiety over five times the UK general-population average [practitioner survey].

## 5. Recovery Evidence

Documented, quantified turnaround research specific to small businesses is comparatively sparse in the available literature. The clearest, most defensible recovery-adjacent finding is behavioral rather than financial: the Lehigh/Nasdaq study documented that founders who **changed one behavior — setting and holding work-life boundaries** — saw burnout prevalence fall from 67% to 45% (still not eliminated, but a roughly threefold shift in the low-burnout rate), suggesting boundary-setting is a validated recovery lever for founder-health-driven business decline [practitioner survey]. Separately, pivot research on software startups found that **negative customer reaction and a flawed business model are the most common triggers for pivots** that founders undertake to avoid failure — with Skynova's 2022 survey finding 40% of surveyed startup founders pivoted specifically to avoid failure that year [practitioner survey][peer-reviewed pivot-trigger study]. Beyond these two threads, [SOURCE MISSING] for a rigorous, quantified before/after turnaround dataset (e.g., matched-pair analysis of firms that recovered from near-failure vs. those that didn't) comparable in rigor to the BLS survival curves — this is a genuine gap the AI mentor system should flag as low-confidence territory rather than invent statistics to fill.

## The 15 Most Defensible Facts, Ranked by Evidence Strength

1. **[Government data, census-level]** ~79.6% of new US private-sector establishments survive year one; ~48.9–50.6% survive to year five; ~33.9–34.7% survive to year ten (BLS BED, 1994–2024 cohorts).
2. **[Government data]** The "90% of businesses fail in year one" claim has never appeared in any federal dataset — actual first-year failure is ~20%, not 90%.
3. **[Peer-reviewed, 1.9M-record BLS microdata, 20-year window]** Only 17% of independent full-service restaurants fail in year one, contradicting the "90% of restaurants fail" myth; median restaurant lifespan is ~4.5 years.
4. **[Government data]** Survival varies by industry: 5-year survival ranges from ~37–44% (information, mining) to ~55–66% (healthcare, agriculture).
5. **[Government data, OECD cross-country]** International 5-year survival ranges from ~33.8% (South Korea) to ~63.3% (Sweden) among OECD-28 countries; US sits near the OECD average at ~50.2%.
6. **[Peer-reviewed, empirical test of Greiner]** Empirical tests of Greiner's five-stage growth model are genuinely mixed: large cross-national samples (Tushman et al. 1986) found no general support, while smaller single-country/single-industry samples (Czech, Hungarian firms) found partial-to-substantial support.
7. **[Peer-reviewed, Altman Z-Score]** Financial-ratio bankruptcy prediction models show accuracy that degrades sharply with horizon — e.g., ~52% accuracy at 1 year pre-bankruptcy falling to ~11% at 4 years in one study.
8. **[Peer-reviewed, large SME dataset]** Non-financial variables (management turnover, employee tenure/"firing ratio") meaningfully improve SME default prediction beyond financial ratios alone (the "Omega Score" study).
9. **[Peer-reviewed, systematic review, 41 articles]** Managerial/organizational factors are the single most frequently cited failure domain across academic studies (35 of 41 reviewed articles), ahead of purely financial or product-market causes.
10. **[Practitioner survey, N=431 post-mortems, self-reported]** CB Insights' most recent analysis attributes 70% of VC-backed shutdowns to "ran out of capital," but explicitly frames this as the final symptom rather than root cause, with poor product-market fit (43%) cited as the deeper driver.
11. **[Practitioner survey, N=~500 founders, self-reported]** Skynova's founder survey found 47% cite lack of financing/investors and 44% cite running out of cash as primary failure causes — note this is self-reported and likely externalizes blame.
12. **[Practitioner survey, N=227–300+ across studies]** 54–93% of founders report burnout or mental-health strain depending on the specific survey and population, a remarkably consistent finding across at least five independent surveys.
13. **[Practitioner survey, N=300+, Lehigh/Nasdaq]** Founders unable to maintain work-life boundaries show 67% high-burnout rates vs. 6% among those who set boundaries — the clearest documented behavioral recovery lever in this literature.
14. **[Peer-reviewed, cofounder-conflict research]** Roughly 65% of failed startups involved cofounder conflict as a contributing or primary cause per Wasserman's Founder's Dilemmas research.
15. **[Peer-reviewed, systematic review, 95 articles, 1968–2016]** Across a half-century of academic literature, no single cause explains SME failure — financial constraints, managerial deficiencies, market challenges, and environmental/regulatory factors interact, with regional variation (developed economies skew toward strategic/innovation causes, developing economies skew toward financial/institutional causes).
