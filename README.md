# The Ruler Before the Material

**A pre-standardization methodology for qualifying graphene as a photonic device layer.**

Standardizing graphene for photonics runs on two coupled tracks: a material tier that the standards bodies have largely built, and a photonic-integration tier that does not yet exist. This brief maps that gap, proposes the measurement-first method to close it, and names the interface that joins the two.

**Read the brief:** [rendered document](https://bluebflatminor.github.io/ruler-before-the-material/) (once GitHub Pages is enabled) — or open `index.html` locally. Light/dark themes follow your device setting.

## The argument in brief

- **Standardize the measurement first.** You cannot reduce variance you cannot measure the same way twice, so agreed, traceable metrology is the earliest scalable coordination mechanism — even before the material is reproducible. ("Before" means first-class priority, not strict sequence; metrology and process stabilization co-evolve.)
- **Two coupled tracks.** *Track A* — graphene as a material (the supplier's certificate; largely standardized already). *Track B* — graphene in the photonic stack (the foundry's certificate; the gap). They are joined by an **interface** — an electronic–photonic material passport — where the transfer step also lives, since it is neither a Track A characteristic nor a Track B measurand.
- **The gap is the optical tier specifically.** Electrical and structural metrology is well underway (IEC TC 113 `62607-6-x`; ISO/TS 21356). No standard yet covers optical loss or σ_s at the operating wavelength.
- **The portable measurand is the complex sheet optical conductivity** σ_s(λ, E_F, T), reported normalized to modal overlap Γ so it ports across platforms — letting a foundry use its own waveguide geometry as the test vehicle. The standard fixes the *extraction*, not the layout.

## What this is — and what it isn't

A pre-standardization working brief describing a methodology. It is **not** a ratified standard and claims **no** committee standing. The hard standardization work — the reference test vehicle, multi-laboratory round-robins, ratification — belongs to the chartered bodies and the national metrology institutes. The aim is to let the argument enter the pre-standardization discourse on its merits, where a chartered party can pick it up.

## Builds on

- The NPL-led **VAMAS Technical Working Area 41** interlaboratory comparisons — the proven pipeline this method extends (published in *2D Materials*; the first Raman round-robin cut measurement uncertainty by up to a factor of fifteen).
- Romagnoli, Sorianello, Koppens, … Ferrari, "Graphene-based integrated photonics for next-generation datacom and telecom," *Nature Reviews Materials* **3**, 392–414 (2018) — the device-requirement anchor Track B normalizes to.
- The existing material tier: IEC TC 113 (`IEC TS 62607-6-4 / 6-7 / 6-8 / 6-27`, and `6-37` in development) and ISO/TC 229 (`ISO/TS 21356-2`, `ISO/TS 80004-13`).

## Method and provenance

Drafted with AI assistance (Claude, Anthropic), disclosed in full. The brief was pressure-tested through several independent AI adversarial-review passes (Perplexity, Gemini, Copilot, DeepSeek, GPT) used as a structural hedge against sycophancy.

Those passes hardened the technical claims rather than inflating them — for example: the σ_s relation reframed as perturbative, up to a geometry-dependent constant, with Γ defined by complex modal perturbation theory rather than naive area overlap; Raman demoted to a non-traceable operating-point estimator with a stated laser power-density limit; the metrology/process relationship made explicitly recursive; storage-atmosphere specification and GUM-style uncertainty framing added.

Specification-grade demands the reviews surfaced — a full interface schema with a worked attribution example, a validity-range / negative case, the exact boundary condition and overlap integral, expanded failure modes — were **deliberately not** forced into the brief. They belong in a future Technical Specification skeleton, kept separate so this stays a scoping document rather than a bloated pseudo-standard.

Edition dates and clause content of the cited standards should be verified against current IEC/ISO catalogues before formal citation.

## Companion

*From Nanojoules to Spec Sheets* — the metrology-as-enabling-layer argument this piece extends (separate brief).

## License

Released under **CC0 1.0 Universal** — a public-domain dedication. No rights reserved. Reuse, adapt, translate, and republish freely, with or without attribution. See [`LICENSE`](LICENSE).
