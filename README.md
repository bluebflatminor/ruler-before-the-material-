# The Ruler Before the Material

**Standardizing graphene as a photonic device layer: the tier that exists, the tier that doesn't, and the standardized measurand the missing tier extends.**

A pre-standardization working brief. Published as a single-page HTML technical note with automatic dark mode, deployed via GitHub Pages.

- **Live page:** `index.html` (GitHub Pages)
- **Status:** rev. 5 — 10 June 2026
- **License:** CC0 1.0 Universal — public domain, no rights reserved

---

## The argument in four sentences

Graphene standardization for photonics runs on two coupled tracks: a material tier (IEC TC 113 / ISO TC 229) that largely exists, and a photonic-integration tier — the complex sheet optical conductivity σₛ(λ, E_F, T) at the operating wavelength, Γ-normalized on the integrated stack — that doesn't. The portable measurand already has series precedent: IEC TS 62607-6-10:2021 standardizes complex sheet conductivity extraction at terahertz frequencies, so the proposal is the interband, on-stack extension of an existing 62607-6-x measurand, not the invention of a new one. The measurement *method* can lead the material specification by roughly one development cycle; its *validation* (round-robins, reference materials, the σₛ→KPI link) co-evolves with the material and remains open research. Build the ruler first — by extending the ruler the field already owns.

## What changed in rev. 5

Rev. 5 is a June 2026 literature-and-field update that changed the brief's framing, not just its references:

1. **The 62607-6-10 reframe (central change).** Rev. 4 treated σₛ as an unstandardized measurand. It isn't: IEC TS 62607-6-10:2021 extracts the frequency-dependent complex sheet conductivity from a THz transmission function, with Drude-fit carrier density and mobility maps. The committee pitch changes from "create a measurand" to "extend a standardized one" — across two changes the brief now states explicitly: intraband (Drude, THz) → interband (1550 nm, Pauli blocking), and bare film → integrated stack (Γ enters).
2. **Hall correction.** Rev. 4 claimed carrier-density standardization awaited IEC TS 62607-6-37. A Hall-bar method (62607-6-23) is already in the series; 6-37 is the extension in development. The operating-point caution survives in corrected form: a Hall bar is a structure beside the device, not the film in the mode.
3. **Empirical anchor.** The imec–Graphenea 300 mm pilot-CMOS run (graphene EAMs, 50 ± 4 dB/mm across 400 devices, ~15 GHz) is added to Sections 04, 07, 08 and critical-path step 04 as proof that the test-vehicle-with-statistics pattern and per-wafer device populations are producible in a foundry — and as the first dataset with the right shape for the σₛ→KPI construct-validity experiment.
4. **Materials tier completed.** ISO/TS 9651:2025 (classification) and ISO/TS 23359:2025 (chemical characterization) added to Track A; ISO/AWI TS 23879 and the 2025 *2D Materials* TWA 41 pipeline review added to Section 06.
5. **Industrial pull with a clock.** Section 09 adds the adoption constituency: CamGraPhIC's €211M Italian state-aid package (EC-approved April 2026; Milan-area pilot line operational 2028), the Graphene Flagship 2D pilot-line MPW expansion, PIXEurope, and Black Semiconductor's acquisition of Applied Nanolayers. A TS that exists before pilot lines qualify suppliers gets adopted by default.
6. **Repair.** A malformed sentence in Section 03 (rev. 4 HTML bug) was reconstructed.

## Revision history

| Rev | Date | Change |
|-----|------|--------|
| 5 | 2026-06-10 | 6-10 reframe (extension, not invention); Hall-bar correction; imec empirical anchor; ISO materials tier; industrial-pull section; Section 03 repair |
| 4 | 2026-06-04 | Red-team demotions: attribution → scaffold, "fix" → "bound" the operating point, Γ-portability → conditional; feasibility pre-studies and construct-validity check added as true gates |
| 1–3 | 2026-05/06 | Initial two-track framing, measurand definition, committee pathway, critical path |

## Methodology

This brief follows the same workflow as the rest of this research program: physics-problem framing → drafting in dialogue with an AI system (Claude, Anthropic) → structured multi-AI adversarial review → triage of objections into fold-in / reframe / discard → revision → GitHub Pages deployment. Rev. 5 additionally incorporated a targeted web-literature sweep (standards catalogues, VAMAS/NPL outputs, graphene-photonics industrialization news through June 2026). The adversarial-review posture is the point: claims are demoted when the evidence doesn't carry them, and the provenance block in the document footer records what was demoted and why.

## What this is not

It is a roadmap argument, not a validated methodology. Explicitly open: post-transfer, in-situ E_F metrology on the finished stack; self-consistent Γ extraction for strongly-perturbed modes; transfer reproducibility (feasibility pre-study step 00); and the σₛ-to-performance link (step 04, the load-bearing experiment). Standards existence and scope were checked against catalogue records and secondary literature; edition dates, scopes (notably 62607-6-23), and clause content should be verified against the IEC/ISO catalogues before formal citation.

## Companion work

- *From Nanojoules to Spec Sheets* — the metrology-as-enabling-layer argument this brief extends (photonic device integration metrology, IEC TC 113 / VAMAS TWA 41 pipelines).

## License

CC0 1.0 Universal. This work is dedicated to the public domain. Reuse, adapt, and republish freely, with or without attribution.
