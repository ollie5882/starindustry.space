# Website Update Plan — Refocus on Consultancy + CONVERj

_Draft plan · July 2026 · not yet implemented_

## 1. The shift

**From:** a three-tier "consultancy → products → platforms" story
(Tier 1 Services · Tier 2 Products [composites + CONVERj] · Tier 3 Vehicles [GravityWorks]),
bootstrapping from composites to in-orbit production.

**To:** a focused **engineering-analysis consultancy** whose spine is **mission
architecture definition and mission analysis**, backed by **CONVERj** — the in-house
engine that powers that work and is being productised into a standalone tool.

Agreed framing (confirmed):
- **Consultancy-led.** The analysis consultancy is the front door, presented as **three
  capability pillars**:
  1. **Mission Analysis (MA)** — trajectory/performance analysis, systems engineering,
     trade studies, AIT support, technical governance.
  2. **Flight Safety Analysis (FSA)** — safety-case development support, QRA via
     trajectory optimisation + Monte Carlo, hazard/blast/debris/overpressure analysis,
     range-safety support.
  3. **Mission Architecture + CONVERj** — architecture definition and requirements
     flow-down, delivered on **CONVERj**, our in-house engine. This is the thread CONVERj
     supports, and CONVERj is being productised into a standalone tool.
- **FSA is a headline pillar with strong credentials.** Approved public wording:
  _"Led a CAA launch operator's licence application through to approval"_ and
  _"Demonstrated best-in-class analysis to White Sands Missile Range (WSMR)"_. NG-4 is a
  public illustration of the same hazard/blast analysis capability.
- **Confidential for now — keep OFF the site:** the **Deimos** relationship underpinning
  the QRA/Monte Carlo work, and the **Starbound × CONVERj** partnership. Describe the
  capability, not the tooling partner.
- Composites (CFRP tanks, COPVs) and GravityWorks / in-space production **come off the
  public site** (see §6 — proposed removal, pending your confirmation).

One-line positioning for the new site:
> _Star Industry is a space-engineering consultancy for mission architecture, mission
> analysis and flight-safety analysis — powered by CONVERj, our converged trade-study
> engine._

## 2. New homepage (index.html) structure

| # | Section | Change |
|---|---------|--------|
| 1 | **Hero** | Rewrite. Drop "advanced composites … GravityWorks in-space production bus". New line built around mission architecture & analysis + CONVERj. CTAs → "Talk to us" / "Explore CONVERj". |
| 2 | **Mission** | Rewrite. Remove "build the European engineering base and the vehicles … in-space production platforms tomorrow / one shared technology stack across every product line". Replace with the consultancy mission: de-risk missions through rigorous architecture and analysis. |
| 3 | **What we do** | Replace the 3-tier accordion with **three consultancy pillars**. **(1) Mission Analysis (MA)** — trajectory/performance analysis, systems engineering, trade studies, AIT, technical governance. **(2) Flight Safety Analysis (FSA)** — safety-case development support, QRA via trajectory optimisation + Monte Carlo, hazard/blast/debris/overpressure, range-safety support; credentials: "Led a CAA launch operator's licence application through to approval" and "Demonstrated best-in-class analysis to WSMR". **(3) Mission Architecture + CONVERj** — architecture definition & requirements flow-down delivered on CONVERj; doubles as the CONVERj feature block linking to converj.html. |
| 4 | **CONVERj feature** | Pillar 3 above _is_ the CONVERj feature — promoted from a nested sub-accordion to a full homepage block. Short pitch + dashboard image + "the engine behind our mission-architecture work, becoming a standalone product" + link to converj.html. |
| 5 | **Case study / proof** | FSA proof: the **CAA licence approval** and **WSMR** credentials (lead credibility) plus the **NG-4 forensic blast analysis** (public, illustrative). Keep ARCAS as CONVERj proof (lives on converj page). Consider a short "safety analysis" proof strip / mini-case for FSA analogous to the CONVERj/ARCAS treatment. |
| 6 | **Roadmap** | **Drop the section entirely** (composites→in-orbit-production is gone with the refocus). |
| 7 | **Team / About** | Keep (about.html). Trim any composites/vehicle framing in bios if present. |
| 8 | **Contact / CTA** | Keep. Adjust copy so scoping is for analysis engagements, not only CONVERj trade studies. |
| 9 | **Footer** | Rework "Offerings" column (remove Tier 1/2/3 + Vehicles). Update address (see §5). |

## 3. CONVERj page (converj.html) — updates from CONVERj_v2 deck

The deck materially upgrades the CONVERj story. Current page pitches "trade studies in
minutes, not weeks". The v2 positioning is broader and stronger:

- **Reposition the hero** from _trade-study-only_ to **"one model of the vehicle, useful
  at every phase"** — continuous integration for hardware. Keep the "minutes not weeks"
  line as a supporting proof, not the headline.
- **Add the lifecycle strip:** Trade Studies → Design → Qualification → Production, all
  reading/writing one architecture file (deck slide 4). This is the biggest new idea.
- **Expand scope** beyond launch vehicles: orbital + suborbital **and satellites**
  (microsat → largesat; power / comms / microgravity models). Current page is
  launch-vehicle-only (deck slides 7–9).
- **Add "Six working views"**: Mission · Architecture · Optimise · Product Tree ·
  Trajectory · Compare. Current page shows only a partial dashboard set (deck slide 14).
  Suggest turning the existing dashboard-tabs component into these six.
- **Strengthen the "why"**: two-part problem — trade studies don't fit a spreadsheet
  (manual transfer / convergence loops / no comparison) **and** agile development never
  stops (moving target / coupled changes / never final). Slides 5–6.
- **Add the data-structure / conductor / SysON-bridge explainer** (single source of
  truth, dependency-ordered model chain, tank⇄COPV convergence loop, extract-seed /
  inject-record round-trip). Slides 10–13.
- **Add KPIs & extensibility**: consistent KPIs (max payload, total ΔV, wet mass,
  T/W liftoff, total cost, cost/kg, payload fraction, convergence) and "add a model or
  KPI by config, not code — 1 config file, 0 code changes". Slides 28–29.
- **Trajectory**: 3DOF ascent flown to orbit; launch azimuth solved by bisection;
  gravity/drag losses measured from the flown trajectory, not a fudge factor. Slides 19/30.
- **Engagement model**: keep the three phases (Scope & Seed / Trade Study / Handover) as
  a description of _how_ we work, but **drop the fixed-price / binding-deliverables /
  LOI commercial language**. Reframe the CTA around **"contact us for a bespoke
  arrangement"** — every engagement scoped and priced individually. Same change on the
  homepage contact section.
- **Keep ARCAS** worked example (heritage-validated, converged in 3 minutes).

**Deliberately excluded from the public page:** the Starbound × CONVERj partnership
(Part 03 — Virgil / Pythia, combined platform vision, competitive frame vs Flow / Jama).
The deck marks this "CONFIDENTIAL · FOR DISCUSSION", so it stays off the public site
unless you say otherwise.

## 4. Nav / cross-linking

- Nav currently: Offerings · CONVERj · Roadmap · Case Studies · About · Contact.
- Proposed: **Consultancy** (or "What we do") · **CONVERj** · **Case Studies** ·
  **About** · **Contact**. Drop "Roadmap" from nav (or rename to reflect the new
  section). Remove Tier 1/2/3 anchor labels everywhere.
- CONVERj eyebrow currently reads "Tier 2 · Digital Engineering" — retire the "Tier 2"
  language sitewide.

## 5. Global / housekeeping

- **Address**: **remove the physical address entirely** from footers (currently "Forres,
  Inverness, UK") — it's irrelevant. Company no. 17048178 stays.
- **Meta description** (both pages): rewrite away from "advanced composites … CONVERj
  … the vehicles that follow" to the consultancy + CONVERj positioning.
- **Footer tagline** "// Engineering the in-space economy" — consider a tagline that
  fits analysis/consultancy (e.g. "// Mission architecture, analysed"). Optional.
- **Contact email**: site uses both `hello@` and `company@starindustry.space`;
  standardise on one (deck uses `company@`).

## 6. Content to remove (proposed) — preserve, don't lose

Recommend **removing from the homepage but keeping a backup** so nothing is destroyed:
- Copy current `index.html` to `examples/` (or `backup/`) before editing.
- Remove: Tier 2 composites sub-accordion (CFRP tanks / COPVs / Forres factory),
  Tier 3 Vehicles / GravityWorks (version tree, envelope), and the
  composites→in-orbit-production roadmap.
- Orphaned assets after removal: `assets/gravityworks.png`, `assets/factory.png`,
  `assets/phoenix.png` (if hero art changes), plus GravityWorks strand imagery. Leave
  the files in `assets/` (harmless) but stop referencing them.

## 7. Assets to source

- Updated CONVERj screenshots for the six views (Mission, Architecture, Optimise,
  Product Tree, Trajectory, Compare) — the deck slides can be exported as stand-ins if
  live app captures aren't ready.
- Possibly a new hero image that reads "analysis / mission architecture" rather than the
  phoenix-over-composites vibe (optional; phoenix can stay as brand mark).

## 8. Decisions (confirmed)

1. **Composites + GravityWorks** — remove from homepage entirely (back up first).
2. **Roadmap section** — drop entirely.
3. **Address** — remove from footers entirely; keep company no. 17048178.
4. **CONVERj commercial language** — drop fixed-price/LOI wording; reframe as
   "contact us for a bespoke arrangement".
5. **Consultancy structure** — three pillars: Mission Analysis · Flight Safety Analysis ·
   Mission Architecture + CONVERj.
6. **FSA credential wording (approved)** — "Led a CAA launch operator's licence
   application through to approval" and "Demonstrated best-in-class analysis to White
   Sands Missile Range (WSMR)".
7. **Deimos** — off-site; describe QRA/Monte Carlo capability without naming the partner.

## 9. Suggested build order (once approved)

1. Back up current `index.html`.
2. Homepage: hero + mission rewrite → replace 3-tier block with consultancy + CONVERj →
   roadmap decision → footer/nav/meta.
3. CONVERj page: hero reposition → add lifecycle, scope, six views, conductor/bridge,
   KPIs/extensibility, trajectory → engagement wording → keep ARCAS.
4. Sitewide: retire "Tier" language, fix address/email, update meta.
5. Verify: check all internal links, render both pages, proof against this plan.
