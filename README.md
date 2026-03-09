# Oil Shock 2026 — Expert Interpretation & Conclusions

---

> **Last updated: March 2026.**
> Section VIII documents a material real-world development — approximately **6 mb/d of Middle Eastern supply currently offline** — that stress-tests and revises several of the model's baseline assumptions and price conclusions. Readers should treat the original model outputs (Sections I–VII) as the analytical foundation and Section VIII as the live scenario overlay.

---

## I. SVAR Impulse Response Functions (IRFs)

### What the Model Found

The Cholesky-identified SVAR imposes a recursive contemporaneous ordering: a supply disruption hits Brent first, S&P 500 second, and Gold third. This is structurally well-grounded — commodity markets clear before equities fully reprice, and gold re-prices as the final risk thermometer.

**Brent Crude response to its own supply shock:**
- The IRF peaks sharply within **trading days 1–3** and decays toward zero by approximately day **10–15**.
- This is consistent with how oil futures markets actually behave during geopolitical shocks: the 2019 Abqaiq drone strike sent Brent up ~15% intraday on Day 1 before partial reversal over two weeks as Saudi Aramco restored output.
- In plain terms: **markets price in the worst case immediately, then revise down as the supply situation clarifies.**

**S&P 500 response:**
- The equity market responds **negatively** — a classical demand-destruction channel.
- Higher energy input costs compress corporate margins (transport, manufacturing, chemicals), raise inflation expectations, and trigger tighter monetary policy fears — all landing simultaneously as a growth headwind.
- The magnitude is consistent with energy-to-equity transmission observed during the 2022 Russian invasion of Ukraine, when the S&P 500 fell ~12% over the first six weeks of the oil price surge.

**Gold response:**
- Gold registers a **positive safe-haven spike**, confirming that financial actors simultaneously hedge geopolitical risk while liquidating risk assets.
- This dual signal — oil up, equities down, gold up — is the canonical "geopolitical risk trinity" documented by Caldara & Iacoviello (2022) in their Geopolitical Risk Index.

### Forecast Error Variance Decomposition (FEVD)

The FEVD chart is arguably the most analytically important output:

| Horizon | Supply Shock | Demand Shock | Risk Shock |
|---|---|---|---|
| Short (1–5 days) | Dominant (~70–80%) | Minor | Negligible |
| Medium (10–15 days) | Declining | Growing | Moderate |
| Long (20 days) | ~50–60% | ~25–35% | ~10–15% |

**Real-world interpretation:**

- In the first week after a Hormuz disruption, **oil prices are driven almost entirely by supply-side fear** — the market does not yet know how long the disruption will last.
- By week two to four, **demand expectations start mattering equally** — recession fears, demand destruction from $120+ oil, and central bank tightening signals begin to re-enter the price.
- This bifurcation explains why oil spikes during the Gulf War (1990–91) and the 2022 Russian gas crisis followed a two-phase dynamic: a sharp supply-panic spike followed by a sustained plateau or partial reversal driven by demand revision.

**Key takeaway for traders and policymakers:** The first 5 trading days are supply-dominated and thus the window when emergency SPR releases have maximum price-suppression impact. Beyond day 10, the demand signal dominates and monetary/fiscal response matters more.

---

## II. Scenario Analysis — Projected Price Paths

The model seeds from the **latest downloaded Brent price** (approximately **$70–75/bbl** as of early 2026, consistent with current market conditions where oversupply concerns and weak Chinese demand have pushed prices down from 2022 highs).

> **Note:** With ~6 mb/d currently offline (see Section VIII), these model-output price peaks represent the **lower bound** of a realistic conflict scenario. Revised peaks accounting for the degraded supply buffer are provided in Section VIII.

### Scenario A — Tactical Strike (+15%, 30-day decay)
**Model output peak: ~$81–86/bbl | Revised peak (current conditions): ~$90–100/bbl**

- Represents a precision strike on IRGC facilities, a drone attack on a refinery, or a naval skirmish in the Gulf — with no closure of the Strait itself.
- **Historical analogue:** The September 2019 Abqaiq/Khurais attack: a 15% intraday spike that was fully retraced within 3 weeks as Saudi Aramco restored output ahead of schedule and US sanctions diplomacy resumed.
- **Real-world consequence at this price level:** Mild inflationary pressure in oil-importing economies (EU, Japan, India). Central banks would likely look through this as a transient supply shock. No emergency IEA coordination required.
- Most likely scenario in the event of a limited US military strike authorized by executive order without Congressional escalation.

### Scenario B — Partial Blockade (+40%, 90-day decay)
**Model output peak: ~$98–105/bbl | Revised peak (current conditions): ~$120–135/bbl**

- Represents Iran mining approaches to the Strait, deploying fast-attack boats, and degrading tanker insurance availability such that a significant fraction of tankers avoid the route — without a full naval confrontation.
- **Historical analogue:** The 1987–88 Tanker War, where insurance premiums rose 300% and effective throughput through the Strait was reduced by ~30–40%, contributing to a multi-month oil price premium.
- **Real-world consequence at ~$100/bbl:** This level triggers the political pain threshold for most OECD governments. IEA emergency coordination kicks in (obligation under IEA treaty: release if >7% supply disruption). The US Federal Reserve faces a stagflationary dilemma — cut rates to support growth, or hold/hike to contain oil-driven CPI.
- India and China, the two largest buyers of Middle Eastern crude, would face currency depreciation pressure (both current account deficits would widen), with the Indian Rupee most vulnerable.

### Scenario C — Infrastructure Damage (+60%, 180-day decay)
**Model output peak: ~$112–120/bbl | Revised peak (current conditions): ~$150–175/bbl**

- Represents a strike on the Kharg Island terminal (handles ~90% of Iranian crude exports AND is logistically near Saudi loading operations), combined with Abqaiq-scale damage to Saudi infrastructure, or a prolonged Iranian naval blockade.
- **Historical analogues:** The 1973 Arab Oil Embargo (prices quadrupled over 6 months) and the August 1990 Kuwait invasion (prices doubled in 90 days before reversing on coalition military victory).
- **Real-world consequence at $112–120/bbl:**
  - Global GDP growth contracts by an estimated 0.5–1.5% according to IMF oil shock transmission models.
  - Aviation and petrochemical sector distress (airlines hedged for ~6 months typically, thereafter exposed).
  - Emerging market debt crises accelerate as dollar-denominated energy import bills balloon.
  - US domestic shale production would accelerate within 60–90 days (Permian Basin break-even is ~$45–60/bbl), but upstream lead times mean relief only arrives after the price peak.
  - **Political pressure to negotiate** intensifies rapidly — the 180-day decay is realistic because at $120/bbl, demand destruction alone (substitution, efficiency changes, recession) would mechanically reduce prices even without supply restoration.

---

## III. Hormuz Factor Impact Model — Heatmap Analysis

This is the most granular and policy-relevant output. The model deducts 4 mb/d bypass capacity (Iraq-Turkey pipeline, UAE Fujairah pipeline) and 1 mb/d SPR release from total blocked supply to isolate the **actual net supply gap**.

### Supply Gap Arithmetic

| Closure Level | Blocked (mb/d) | After Bypass+SPR (Net Gap, mb/d) | % of Global Supply |
|---|---|---|---|
| 25% | 5.25 | 0.25 | 0.25% |
| 50% | 10.5 | 5.5 | 5.5% |
| 100% | 21.0 | 16.0 | 16.0% |

**Critical insight: the 25% closure is nearly fully absorbed.** This is the model's most important and underappreciated result. As long as bypass infrastructure and coordinated SPR are activated promptly, a limited harassment campaign against the Strait does not create a structural oil crisis — it creates **a volatility event, not a supply crisis**. This explains why oil markets repeatedly spiked and recovered during the 2019–2020 Gulf of Oman tanker attacks without sustained price dislocations.

> **Current conditions caveat:** This finding is materially weakened by the ~6 mb/d already offline (Section VIII). If bypass and SPR capacity is already committed to covering existing disruptions, the 25% closure buffer effectively disappears. See the revised gap table in Section VIII.

**The 50% closure (~$100–120/bbl range at durations >4 weeks)** is the critical threshold where bypass capacity is genuinely overwhelmed and SPR buffers become material but insufficient. At ~5.5 mb/d net gap, this exceeds the 1973 Arab embargo's shortfall (~4.4 mb/d) — the last time a supply disruption triggered a structural price regime change in global oil markets.

**The 100% closure scenario ($130–160+/bbl at 8–12 weeks)** is extreme but not historically unprecedented in terms of price percentage-change. The 1973 embargo produced a ~300% price increase. The current model's ~100–120% increase at peak (from ~$75 to ~$150+) for a 12-week full closure implicitly assumes faster market adaptations, better-diversified supply chains, and more responsive monetary policy — all of which are defensible post-2000 structural adjustments.

### Duration Sensitivity — The Square Root Rule

The model uses a `sqrt(duration)` scaling, which is technically elegant and economically justified:

- **Short disruptions (1–3 weeks):** Storage and floating inventory (there are ~3 billion barrels in commercial storage globally) smooth prices — markets draw down stocks rather than repricing structurally.
- **Medium disruptions (4–8 weeks):** Storage depletion occurs, demand destruction kicks in, tanker re-routing through the Cape of Good Hope adds ~7–10 days and ~$3–5/bbl in freight costs.
- **Long disruptions (9–12 weeks):** Structural repricing occurs — refiners sign alternative supply contracts, US LTO producers accelerate completions, OPEC+ members face immense pressure to compensate. The square root captures diminishing marginal price sensitivity as these adjustment mechanisms activate.

This is empirically consistent with the academic literature (Hamilton 2009, Kilian 2014) which shows oil price elasticities are not linear with disruption duration.

---

## IV. Cross-Method Synthesis — Coherence Check

The three methods are internally consistent, which strengthens confidence in the conclusions:

| Metric | SVAR | Scenario Analysis | Hormuz Factor |
|---|---|---|---|
| Short-term peak timing | Day 1–3 | Day 0–5 (immediate) | — |
| Medium disruption price | — | $98–105 (Scenario B) | $92–118 (50% / 4–8 wks) |
| Severe disruption price | — | $112–120 (Scenario C) | $130–160+ (100% / 12 wks) |
| Decay/mean-reversion | 10–20 days | 30–180 days | Embedded in sqrt rule |

**The Scenario Analysis and Hormuz Factor models converge around $100–120/bbl for a serious but non-catastrophic disruption** — this is the model's central estimate for the most probable "real conflict" scenario. This is also consistent with sell-side analyst consensus estimates from Goldman Sachs and IEA scenario publications on Hormuz disruption risk.

> **Updated cross-method range under current conditions (6 mb/d offline):** Medium disruption $120–135/bbl; severe disruption $150–175/bbl. See Section VIII.

---

## V. Real-World Policy & Market Implications

### For Central Banks (Fed, ECB, RBI)
- The **FEVD result implies a 5-day intervention window** where supply-side policy (SPR, diplomatic signals) meaningfully suppresses prices. Beyond that, monetary policy transmission through demand channels is more relevant.
- A 50% Hormuz closure sustained for 8+ weeks would likely force the Fed into a stagflationary policy bind last experienced in 1979–80.
- **Under current conditions:** With 6 mb/d already offline, even a partial blockade could trigger this stagflationary dynamic within 4 weeks rather than 8+.

### For Energy Importers (EU, India, Japan)
- Diversification to pipeline gas (EU from Norway, US LNG), coal-to-power switching, and strategic petroleum reserves are the **only short-term defensive instruments**.
- India is structurally most vulnerable: 85% crude import dependence, majority sourced from the Gulf, with limited domestic SPR (just ~10 days of cover versus IEA's recommended 90 days).

### For Energy Markets & Traders
- The model validates **calendar spread trading strategies** — buy near-month futures (backwardation intensifies in supply shocks), sell deferred contracts. The SVAR confirms the shock decays within 20 trading days, so 3–6 month futures would be structurally underpriced relative to spot in the first week.
- **Gold/oil ratio compression** is expected at shock onset (both rise), but as equity markets destabilize, gold should outperform oil on a risk-adjusted basis.

### For Geopolitical Risk Managers
- ~~The **25% closure = non-event** finding~~ — **This conclusion no longer holds under current conditions.** With 6 mb/d already offline, bypass and SPR buffers are partially or fully committed. A 25% Hormuz closure now constitutes a ~5 mb/d uncushioned shock, comparable to the full 1973 Arab embargo shortfall. See Section VIII for the revised buffer analysis.
- The **12-week full closure** tail risk has shifted from ~$150+/bbl to **$180–200+/bbl** under current market tightness, justifying materially larger energy sector equity hedges and options positions than the base model implies.

---

## VI. Model Limitations in Real-World Context

1. **Constant-volatility assumption understates tail risk.** During the 2022 Russia-Ukraine crisis, Brent implied volatility (OVX) surged from 30% to 70%+ annualized within days. The scenario paths use historical realized vol (~25–30%), significantly underestimating the price band width at crisis onset.

2. **No demand-side feedback loop.** At $120+/bbl, demand destruction is non-trivial — the IEA estimates ~500 kb/d demand loss per $10/bbl sustained price increase. This means actual realized prices would likely be below model projections for durations >8 weeks, as demand erosion self-limits the supply gap.

3. **The k=1.5 sensitivity coefficient is calibrated to the 2019 Abqaiq attack**, a short-duration, rapidly-resolved shock. For a multi-week Hormuz closure — an entirely different regime — k is likely higher in the first 4 weeks (panic premium) and lower thereafter (demand destruction offset). A time-varying k would materially change the heatmap. **Under current conditions (6 mb/d offline), k should be recalibrated upward to ~2.0–2.5 to reflect reduced market slack.**

4. **Geopolitical third-party responses are unmodeled.** Russia could choose to redirect eastern Siberian exports away from Europe toward Asia in a crisis (tightening European supply simultaneously), while China could release its strategic reserves to defend domestic growth. These feedback loops could either amplify or dampen price impacts by 15–25%.

5. **The S&P 500 "demand shock" proxy is imperfect** for the post-2018 US energy landscape. The US became a net petroleum exporter in 2019; a Brent spike now has mixed effects on the S&P 500 as it benefits E&P companies (18% of S&P market cap) while hurting consumer and industrial sectors. The aggregate negative equity response estimated here may overstate the S&P 500 net damage.

6. **The model assumes a balanced market at baseline.** The base model does not account for pre-existing supply disruptions. When significant volumes are already offline, all buffer arithmetic, price sensitivity coefficients, and scenario peaks must be revised upward. See Section VIII.

---

## VII. Conclusion

This notebook provides a structurally rigorous and empirically calibrated multi-method assessment of a US-Iran conflict's oil market impact. The **central policy conclusion** is:

> **A limited, rapidly-resolved conflict (Scenario A, <25% Hormuz disruption) would produce a transient 2–3 week volatility spike to $80–90/bbl with limited macroeconomic consequence. A sustained partial blockade (Scenario B, 50% closure for 6–10 weeks) would constitute a material global supply shock equivalent in scale to the 1973 embargo, driving Brent to $100–120/bbl and triggering IEA emergency coordination, stagflationary pressure in import-dependent economies, and significant equity market volatility. A full, prolonged Hormuz closure (Scenario C / 100% / >8 weeks) represents a tail-risk scenario driving prices to $140–160+/bbl — a level not seen since the 2008 speculative peak — with consequent global recession risk.**

The SVAR's confirmation that the supply shock transmission channel dominates for the first 5 trading days, combined with the Hormuz Factor's finding that 25% closure is largely buffered by bypass and SPR, suggests that **rapid, coordinated emergency policy response in the first week is the single highest-leverage intervention available** to policymakers in any escalation scenario.

> **These conclusions are the model's baseline findings. They are materially revised upward in Section VIII** due to ~6 mb/d of Middle Eastern supply currently offline as of March 2026.

---

## VIII. Current Market Context Overlay — 6 mb/d Already Offline (March 2026)

> This section documents a live real-world condition that stress-tests the model's baseline assumptions and requires upward revision of its price conclusions.

### The Core Problem: The Buffer Is Gone

The model's most consequential assumption is that the global market enters any conflict from a **balanced baseline** — one where the 5 mb/d combined bypass + SPR buffer meaningfully absorbs a Strait disruption. With approximately **6 mb/d of Middle Eastern supply currently offline**, this assumption is violated.

The bypass pipelines (4 mb/d) and SPR release capacity (1 mb/d) that made a 25% Hormuz closure a near non-event may already be committed to offsetting the existing shortfall, leaving **zero residual buffer** for an incremental Hormuz disruption.

### Revised Hormuz Gap Arithmetic

| Closure Level | Blocked (mb/d) | Original Net Gap (mb/d) | Revised Net Gap — 6 mb/d Pre-Offline (mb/d) | Change |
|---|---|---|---|---|
| 25% | 5.25 | 0.25 | ~5.25 | **+5.0** |
| 50% | 10.5 | 5.5 | ~10.5 | **+5.0** |
| 100% | 21.0 | 16.0 | ~21.0 | **+5.0** |

The **25% closure "non-event" conclusion is no longer valid.** Under current conditions it becomes an uncushioned ~5.25 mb/d shock — the rough equivalent of the entire 1973 Arab Oil Embargo shortfall hitting a market with no storage buffer.

### Critical Distinction: Nature of the Offline Supply

The severity of these revisions depends on *why* 6 mb/d is offline:

**If OPEC+ voluntary cuts (most likely scenario):**
- Physical spare capacity exists but is being withheld — not destroyed
- Under sufficient geopolitical pressure, Saudi Arabia and the UAE have historically reversed cuts within 30–60 days (as demonstrated in mid-2022)
- The buffer is **latent, not eliminated** — however, if the disruption is the Iran conflict itself, political willingness to compensate for an adversary's lost volumes is questionable
- **Net effect: buffer is substantially degraded but partially available**

**If conflict-related or infrastructure shutdowns:**
- No spare capacity behind it — buffer is genuinely consumed
- The revised gap arithmetic applies in full with no qualification
- **Net effect: all original price ceilings shift one regime higher**

### Recalibrated Price Sensitivity Coefficient

`k=1.5` was calibrated against the 2019 Abqaiq attack, when the market had 3–4 mb/d of OPEC+ spare capacity as a shock absorber. Academic literature consistently finds that price responses are **convex with respect to market tightness** — the same volumetric shock produces a larger price response when supply-demand slack is thin.

Under current conditions, a recalibrated `k` of **2.0–2.5** is defensible. At `k=2.0`:

| Closure | Duration | Original Peak | Revised Peak |
|---|---|---|---|
| 25% | 4 weeks | ~$82 | **~$95–100** |
| 50% | 8 weeks | ~$110–118 | **~$130–145** |
| 100% | 12 weeks | ~$150–160 | **~$180–200+** |

### Revised Scenario Analysis Peaks

| Scenario | Original Model Peak | Revised Peak (Current Conditions) | Key Driver of Revision |
|---|---|---|---|
| A — Tactical Strike | ~$81–86 | **~$90–100** | No buffer remaining; any incremental supply fear fully transmitted |
| B — Partial Blockade | ~$98–105 | **~$120–135** | k higher + SPR headroom consumed; IEA trigger breached immediately |
| C — Infrastructure Damage | ~$112–120 | **~$150–175** | Market already structurally tight; structural repricing instantaneous |

### What Does Not Change

The following model outputs remain valid regardless of the 6 mb/d context:
- **SVAR transmission dynamics** — the IRF shape, Day 1–3 peak timing, and FEVD proportions are structural relationships, not level-dependent
- **Square root duration scaling** — adjustment mechanisms (demand destruction, re-routing, shale ramp-up) operate on the same timelines
- **IRF decay structure** — 10–20 trading day supply shock reversion remains the best estimate for the pure panic-premium component
- **Gold/S&P 500 directional relationships** — gold up, equities down remains the expected cross-asset response

### Revised Policy Implications

**For Central Banks:** The stagflationary bind threshold — previously estimated at a 50% closure for 8+ weeks — is now reachable with a **25–30% effective disruption sustained for 4 weeks**. The Fed's response timeline compresses materially.

**For SPR Policy:** Emergency SPR releases that could previously suppress a 25% closure to a non-event have diminished firepower. Coordinated IEA releases should be pre-positioned, not reactive — the first-week FEVD intervention window is now even more critical and less equipped.

**For Traders:** The backwardation trade (buy front-month, sell deferred) is more asymmetric than the base model implies. Near-month contracts are starting from a tighter supply base, meaning the spike premium is larger and the mean-reversion tail is longer.

**For Geopolitical Risk Managers:** The window for low-cost diplomatic de-escalation is significantly narrower than the base model implies. At 6 mb/d already offline, even a Scenario A equivalent produces a price response closer to what the base model estimated for Scenario B. The cost of miscalculation — or delayed response — is substantially higher.

---

*All interpretations are academic and for research purposes only, as noted in the notebook's disclaimer.*
