# P1 Knowledge Base Content Audit

Audit date: 2026-06-30  
Branch: `content/content-quality-audit`

## Scope and method

This audit reviews the major HTML pages in the P1 Knowledge Base, with emphasis on:

- Knowledge
- Lexicon
- Due Diligence
- Financing
- Locations
- Case Studies

No page content was rewritten. The audit classifies pages by current content depth and flags missing page components:

- **Strong / complete**: substantive content, generally coherent structure, and few missing quality elements.
- **Medium / needs expansion**: useful content exists, but it needs richer decision context, more P1-specific interpretation, or stronger structure.
- **Weak / placeholder-like**: short or skeletal content that is unlikely to support independent decision-making.
- **Missing TL;DR**: no explicit TL;DR / executive summary section detected.
- **Missing P1 Insight**: no explicit P1 Insight section detected.
- **Missing sources**: no explicit sources section or source references detected.
- **Missing internal links**: fewer than two body-level internal links detected.

## Executive findings

1. **The strongest content is concentrated in a small number of recent Knowledge and Lexicon pages.** Accessibility, Destination Value, Historic Buildings, Bare Ownership, Czynsz, Usufrutto, and Żabka are comparatively strong.
2. **The most decision-critical sections before the Genova field trip are currently the weakest.** Locations, Due Diligence, Financing, and Genova-related Case Studies are mostly placeholder-like.
3. **The Lexicon has broad coverage but inconsistent page architecture.** Most entries are medium-depth but lack explicit TL;DR and P1 Insight sections.
4. **Sources are uneven.** Many practical pages in Due Diligence, Financing, Locations, and Case Studies lack explicit sources, which reduces confidence for field-trip preparation.
5. **Internal linking is generally better than sourcing, but hub pages need stronger routing logic.** Several index pages function as menus rather than decision-oriented gateways.

## Genova field-trip priority list

These pages should be expanded before the Genova field trip because they directly affect what to inspect, ask, document, and decide on site.

| Priority | Page | Current classification | Upgrade focus |
|---:|---|---|---|
| P0 | `locations/genova.html` | Weak / placeholder-like | Add city-level thesis, investable districts, transport/accessibility, tourism demand, regulatory constraints, red flags, sources, and field-trip questions. |
| P0 | `locations/porto-antico.html` | Weak / placeholder-like | Add micro-location assessment, walking routes, noise/tourism tradeoffs, waterfront liquidity thesis, comparison with old-town alternatives, and field-trip photo checklist. |
| P0 | `case-studies/it-goa-001.html` | Weak / placeholder-like | Convert from candidate stub into diligence dossier: asset facts, underwriting assumptions, comps needed, legal questions, inspection checklist, and go/no-go criteria. |
| P0 | `due-diligence/checklist.html` | Weak / placeholder-like | Make this the field-trip operating checklist with Italy/Genova-specific document, building, legal, tax, HOA, and rental-permission prompts. |
| P0 | `due-diligence/legal-title.html` | Weak / placeholder-like | Expand title-risk workflow for foreign buyer context, notary role, ownership chain, liens, condominium rules, and required evidence. |
| P0 | `due-diligence/building-check.html` | Weak / placeholder-like | Add physical inspection rubric: facade, roof, elevator, moisture, seismic/structural concerns, common areas, utilities, and renovation constraints. |
| P1 | `financing/roi-model.html` | Weak / placeholder-like | Add Genova underwriting model assumptions, sensitivity table, capex bands, tax treatment placeholders, ADR/occupancy scenarios, and break-even thresholds. |
| P1 | `financing/currency-conversion.html` | Weak / placeholder-like | Add EUR cash-flow handling, FX reserve rules, Wise/bank transfer decision path, and timing risks. |
| P1 | `knowledge/location-analysis.html` | Weak / placeholder-like | Convert into reusable location scoring framework used by Genova and Porto Antico. |
| P1 | `knowledge/market-analysis.html` | Weak / placeholder-like | Add market data checklist: supply, STR demand, hotel benchmarks, transaction comps, liquidity, macro/regulatory drivers. |
| P1 | `knowledge/risk-management.html` | Weak / placeholder-like | Add field-trip risk taxonomy and mitigation matrix. |
| P1 | `case-studies/index.html` | Weak / placeholder-like | Add status board separating active Genova candidates, rejected assets, watchlist items, and lessons learned. |
| P2 | `lexicon/adr.html` | Medium / needs expansion | Add TL;DR and P1 Insight; connect ADR to Genova underwriting and platform-risk pages. |
| P2 | `lexicon/cap-rate.html` | Medium / needs expansion | Add TL;DR and P1 Insight; clarify use for stabilized vs short-stay property. |
| P2 | `lexicon/dynamic-pricing.html` | Medium / needs expansion | Add TL;DR and P1 Insight; connect to Genova seasonality assumptions. |
| P2 | `lexicon/platform-risk.html` | Medium / needs expansion | Add TL;DR and P1 Insight; connect to Airbnb / Booking.com dependency risk. |

## Section-level imbalance

| Section | Current state | Main imbalance | Recommended intervention |
|---|---|---|---|
| Knowledge | Mixed: 4 strong pages, 1 field-trip page strong but missing P1 Insight, 6 weak pages. | New thematic pages are strong, but core frameworks remain placeholders. | Expand core frameworks first: location analysis, market analysis, risk management, investment strategy, property management, interior design. |
| Lexicon | Broad but mostly medium. | Many pages have adequate definitions but lack TL;DR / P1 Insight consistency. | Add a standard lexicon template and update highest-impact terms first. |
| Due Diligence | Uniformly weak. | The most operationally important section is least developed. | Prioritize as the field-trip playbook. Add checklists, required evidence, red flags, and source-backed workflows. |
| Financing | Uniformly weak. | ROI and liquidity decisions lack robust modeling context. | Build from ROI Model outward: assumptions, scenarios, reserves, FX, LEND, liquidity. |
| Locations | Uniformly weak. | Location pages do not yet support field research or investment comparison. | Expand Genova and Porto Antico first, then Gdańsk / Polish micro-locations. |
| Case Studies | Mostly weak, with three medium people/contact pages. | Candidate pages lack due-diligence structure and source-backed decision criteria. | Convert candidate pages into dossiers; make contact/person pages explain roles and relevance. |

## Page classification matrix

### Knowledge

| Page | Classification | Missing TL;DR | Missing P1 Insight | Missing sources | Missing internal links | Notes |
|---|---|---:|---:|---:|---:|---|
| `knowledge/accessibility-as-investment-factor.html` | Strong / complete | No | No | No | No | Good model for evidence-based thematic content. |
| `knowledge/bt-pilot-trip.html` | Strong / complete | No | Yes | No | No | Strong operational page; add explicit P1 Insight to align with newer pages. |
| `knowledge/destination-value.html` | Strong / complete | No | No | No | No | Strong page; can be cross-linked from Genova and Porto Antico. |
| `knowledge/historic-buildings.html` | Strong / complete | No | No | No | No | Strong page; relevant to Genova older-building diligence. |
| `knowledge/index.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Hub is too thin; should explain how frameworks connect. |
| `knowledge/interior-design.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs design standards, cost bands, STR durability, and photo standards. |
| `knowledge/investment-strategy.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs core P1 thesis, target asset profile, and decision rules. |
| `knowledge/location-analysis.html` | Weak / placeholder-like | Yes | Yes | Yes | No | High priority because Genova pages need this framework. |
| `knowledge/market-analysis.html` | Weak / placeholder-like | Yes | Yes | Yes | No | High priority for market evidence and comp collection. |
| `knowledge/property-management.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs operator criteria, fee structures, platform split, and escalation workflows. |
| `knowledge/risk-management.html` | Weak / placeholder-like | Yes | Yes | Yes | No | High priority for go/no-go criteria and risk controls. |

### Lexicon

| Page | Classification | Missing TL;DR | Missing P1 Insight | Missing sources | Missing internal links | Notes |
|---|---|---:|---:|---:|---:|---|
| `lexicon/adr.html` | Medium / needs expansion | Yes | Yes | No | No | Important for Genova underwriting; add P1 interpretation. |
| `lexicon/airbnb.html` | Medium / needs expansion | Yes | Yes | No | No | Add platform-risk framing and Genova relevance. |
| `lexicon/bare-ownership.html` | Strong / complete | No | No | No | No | Strong legal/investment explanation. |
| `lexicon/booking-com.html` | Medium / needs expansion | Yes | Yes | No | No | Add P1 distribution strategy angle. |
| `lexicon/bruttorendite.html` | Medium / needs expansion | Yes | Yes | No | No | Add relation to net yield and ROI model. |
| `lexicon/cap-rate.html` | Medium / needs expansion | Yes | Yes | No | No | Add stabilized-income caveats for STR assets. |
| `lexicon/cashflow.html` | Medium / needs expansion | Yes | Yes | No | No | Add reserve and downside-case framing. |
| `lexicon/czynsz.html` | Strong / complete | No | Yes | No | No | Add explicit P1 Insight for consistency. |
| `lexicon/dead-zone.html` | Medium / needs expansion | Yes | Yes | No | No | Add examples from micro-location analysis. |
| `lexicon/due-diligence.html` | Medium / needs expansion | Yes | Yes | No | No | Link more directly to due-diligence checklist. |
| `lexicon/dynamic-pricing.html` | Medium / needs expansion | Yes | Yes | No | No | Important for Genova seasonality model. |
| `lexicon/exit-strategy.html` | Medium / needs expansion | Yes | Yes | No | No | Add resale-buyer lens and liquidity-risk link. |
| `lexicon/faktura-zaliczkowa.html` | Medium / needs expansion | Yes | Yes | No | No | Useful but should connect to payment-flow page. |
| `lexicon/fomo.html` | Medium / needs expansion | Yes | Yes | No | No | Add explicit anti-FOMO investment rules. |
| `lexicon/hybrid-management.html` | Medium / needs expansion | Yes | Yes | No | No | Add operating model implications. |
| `lexicon/index.html` | Medium / needs expansion | Yes | Yes | Yes | No | Good inventory; needs category pathways and source policy. |
| `lexicon/kawalerka.html` | Medium / needs expansion | Yes | Yes | No | No | Add comparison to pseudo-1BR. |
| `lexicon/krs.html` | Medium / needs expansion | Yes | Yes | No | No | Good candidate for due-diligence cross-links. |
| `lexicon/ksiega-wieczysta.html` | Medium / needs expansion | Yes | Yes | No | No | Key legal term; add explicit P1 title-risk interpretation. |
| `lexicon/lend.html` | Medium / needs expansion | Yes | Yes | No | No | Align with financing LEND page. |
| `lexicon/liquidity-risk.html` | Medium / needs expansion | Yes | Yes | No | No | Critical risk term; add P1 exit thresholds. |
| `lexicon/micro-location.html` | Medium / needs expansion | Yes | Yes | No | No | Should become a gateway into location analysis. |
| `lexicon/mlode-miasto.html` | Medium / needs expansion | Yes | Yes | No | No | Add location-library cross-links. |
| `lexicon/nip.html` | Medium / needs expansion | Yes | Yes | No | No | Practical; add buyer/admin workflow notes. |
| `lexicon/noi.html` | Medium / needs expansion | Yes | Yes | No | No | Important for ROI; add formula and exclusions. |
| `lexicon/notaranderkonto.html` | Medium / needs expansion | Yes | Yes | No | No | Add payment-flow cross-link. |
| `lexicon/pcc.html` | Medium / needs expansion | Yes | Yes | No | No | Add transaction-cost model link. |
| `lexicon/pesel.html` | Medium / needs expansion | Yes | Yes | No | No | Add foreign-buyer workflow caveats. |
| `lexicon/platform-risk.html` | Medium / needs expansion | Yes | Yes | No | No | High priority for STR strategy. |
| `lexicon/porto-style.html` | Medium / needs expansion | Yes | Yes | No | No | Could support design/storytelling pages. |
| `lexicon/prestige-1.html` | Medium / needs expansion | Yes | Yes | No | No | Clarify how prestige differs from luxury. |
| `lexicon/proforma.html` | Medium / needs expansion | Yes | Yes | No | No | Add payment-flow cross-link. |
| `lexicon/pseudo-1br.html` | Medium / needs expansion | Yes | Yes | No | No | Important for layout underwriting. |
| `lexicon/robyg.html` | Medium / needs expansion | Yes | Yes | No | No | Needs developer-risk framing. |
| `lexicon/rooftop-premium.html` | Medium / needs expansion | Yes | Yes | No | No | Add view durability and exit-premium nuance. |
| `lexicon/spolka-z-o-o.html` | Medium / needs expansion | Yes | Yes | No | No | Add ownership/tax decision tree caveat. |
| `lexicon/stress-test.html` | Medium / needs expansion | Yes | Yes | No | No | Link to cashflow stress-test tool and ROI model. |
| `lexicon/usufrutto.html` | Medium / needs expansion | No | No | No | No | Structurally better than most lexicon entries. |
| `lexicon/vat.html` | Medium / needs expansion | Yes | Yes | No | No | Add purchase vs rental-operation implications. |
| `lexicon/view-durability.html` | Medium / needs expansion | Yes | Yes | No | No | Useful for Genova / Porto Antico views. |
| `lexicon/walkability.html` | Medium / needs expansion | Yes | Yes | No | No | Add scoring method and field-trip measurement. |
| `lexicon/wise.html` | Medium / needs expansion | Yes | Yes | No | No | Connect to currency-conversion page. |
| `lexicon/yield-compression.html` | Medium / needs expansion | Yes | Yes | No | No | Add relation to timing and exit strategy. |
| `lexicon/zabka.html` | Medium / needs expansion | No | No | No | No | Narrow but coherent; not urgent for Genova. |

### Due Diligence

| Page | Classification | Missing TL;DR | Missing P1 Insight | Missing sources | Missing internal links | Notes |
|---|---|---:|---:|---:|---:|---|
| `due-diligence/building-check.html` | Weak / placeholder-like | Yes | Yes | Yes | No | P0 before field trip; needs inspection rubric. |
| `due-diligence/checklist.html` | Weak / placeholder-like | Yes | Yes | Yes | No | P0 before field trip; should become the trip checklist. |
| `due-diligence/index.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs process map and links to all diligence phases. |
| `due-diligence/legal-title.html` | Weak / placeholder-like | Yes | Yes | No | No | P0; sources partially present but content needs expansion. |
| `due-diligence/payment-flow.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs transaction-risk workflow and escrow/proforma handling. |
| `due-diligence/seller-verification.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs ID, authority, entity, broker, and counterparty checks. |

### Financing

| Page | Classification | Missing TL;DR | Missing P1 Insight | Missing sources | Missing internal links | Notes |
|---|---|---:|---:|---:|---:|---|
| `financing/currency-conversion.html` | Weak / placeholder-like | Yes | Yes | No | No | P1 for Genova; add FX timing and reserve policy. |
| `financing/index.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs financing architecture and decision tree. |
| `financing/lend.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs LEND operating policy, risks, and limits. |
| `financing/liquidity-rule.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs reserve rules and stress thresholds. |
| `financing/roi-model.html` | Weak / placeholder-like | Yes | Yes | Yes | No | P1 before field trip; should anchor underwriting. |

### Locations

| Page | Classification | Missing TL;DR | Missing P1 Insight | Missing sources | Missing internal links | Notes |
|---|---|---:|---:|---:|---:|---|
| `locations/brzezno.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs beach-market thesis and seasonality. |
| `locations/gdansk.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs city thesis and district comparison. |
| `locations/genova.html` | Weak / placeholder-like | Yes | Yes | Yes | No | P0 before field trip; city-level investment thesis missing. |
| `locations/index.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs location comparison framework and status board. |
| `locations/letnica.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs stadium/beach/accessibility tradeoff analysis. |
| `locations/mlode-miasto.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs redevelopment and construction-risk framing. |
| `locations/porto-antico.html` | Weak / placeholder-like | Yes | Yes | Yes | No | P0 before field trip; micro-location thesis missing. |

### Case Studies

| Page | Classification | Missing TL;DR | Missing P1 Insight | Missing sources | Missing internal links | Notes |
|---|---|---:|---:|---:|---:|---|
| `case-studies/index.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs live pipeline / status board. |
| `case-studies/it-goa-001.html` | Weak / placeholder-like | Yes | Yes | Yes | No | P0 before field trip; should become Genova candidate dossier. |
| `case-studies/mateusz.html` | Medium / needs expansion | No | Yes | Yes | No | Clarify role, relevance, and next actions. |
| `case-studies/piotr.html` | Medium / needs expansion | No | Yes | Yes | No | Clarify role, relevance, and source trail. |
| `case-studies/pl-gdn-001.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs complete candidate facts and decision history. |
| `case-studies/remigiusz.html` | Medium / needs expansion | No | Yes | Yes | No | Clarify role, relevance, and next actions. |
| `case-studies/s17.html` | Weak / placeholder-like | Yes | Yes | Yes | No | Needs full rejected-case narrative and evidence. |

## Prioritized roadmap for content upgrades

### Phase 0 — Genova field-trip readiness

Goal: make the KB operational before travel.

1. Expand `locations/genova.html` into a city thesis and field-trip guide.
2. Expand `locations/porto-antico.html` into a micro-location diligence guide.
3. Expand `case-studies/it-goa-001.html` into a candidate dossier.
4. Expand `due-diligence/checklist.html` into the master field-trip checklist.
5. Expand `due-diligence/legal-title.html` and `due-diligence/building-check.html` into inspection/legal workstreams.
6. Expand `financing/roi-model.html` into the underwriting assumptions page for candidate comparison.

### Phase 1 — Decision framework backbone

Goal: make every investment decision traceable to a reusable framework.

1. Expand `knowledge/location-analysis.html`.
2. Expand `knowledge/market-analysis.html`.
3. Expand `knowledge/risk-management.html`.
4. Expand `knowledge/investment-strategy.html`.
5. Expand `financing/liquidity-rule.html` and `financing/currency-conversion.html`.
6. Strengthen `case-studies/index.html` as a pipeline status board.

### Phase 2 — Lexicon consistency pass

Goal: make definitions actionable and P1-specific.

1. Add TL;DR and P1 Insight sections to high-impact terms: ADR, Cap Rate, NOI, Cash Flow, Dynamic Pricing, Platform Risk, Liquidity Risk, Stress Test, Due Diligence, Micro Location, Walkability, Wise.
2. Add cross-links from lexicon terms to the relevant Knowledge, Due Diligence, Financing, Tools, and Location pages.
3. Add or standardize sources where legal, tax, platform, or regulatory claims are made.

### Phase 3 — Polish market / archived candidate depth

Goal: preserve learning from earlier Polish work and rejected cases.

1. Expand `locations/gdansk.html`, `locations/letnica.html`, `locations/brzezno.html`, and `locations/mlode-miasto.html`.
2. Expand `case-studies/pl-gdn-001.html` and `case-studies/s17.html` with full decision histories.
3. Add explicit links from decision logs to case studies and location pages.

### Phase 4 — Operating model and design depth

Goal: prepare post-acquisition execution content.

1. Expand `knowledge/property-management.html`.
2. Expand `knowledge/interior-design.html`.
3. Connect those pages to `lexicon/hybrid-management.html`, `lexicon/dynamic-pricing.html`, `lexicon/platform-risk.html`, and ROI tooling.
4. Add templates for operator interviews, furnishing budgets, guest profile assumptions, and maintenance escalation.

## Recommended standard page components

For future upgrades, every major content page should use a consistent structure:

1. **TL;DR** — 3 to 5 bullets for fast decision context.
2. **P1 Insight** — the opinionated P1 interpretation, not just a generic definition.
3. **Decision relevance** — why this page changes buy / pass / inspect / negotiate behavior.
4. **Checklist or framework** — concrete questions, scoring criteria, or calculations.
5. **Risks / red flags** — what can invalidate the thesis.
6. **Internal links** — at least 3 relevant KB links.
7. **Sources** — primary or high-confidence sources for claims that are legal, fiscal, regulatory, market, or platform-specific.
8. **Last reviewed** — useful for market and regulatory content.

## Source and evidence policy recommendation

Use source sections aggressively for:

- Legal-title and notary workflows.
- Tax / VAT / local registration claims.
- Platform terms and STR regulation.
- Market data, tourism trends, ADR / occupancy assumptions, and transaction comps.
- Transport, accessibility, and urban-development claims.

Avoid over-sourcing purely internal opinions, but clearly label them as P1 judgment.
