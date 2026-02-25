# CPR — Conversational Pattern Restoration

**The first personality-agnostic framework for fixing robotic AI communication.**

Every modern AI assistant — Claude, GPT-4, Gemini, Grok — drifts toward the same corporate help-desk voice. Safe. Sterile. Useless for anything requiring actual human texture.

CPR fixes that. Systematically. Across any model, any personality type.

---

## What It Does

Restores six communication patterns lost during RLHF training:

1. **Affirming particles** — "Yeah," "Alright," "Exactly"
2. **Sentence rhythm variety** — short, medium, long mixed naturally
3. **Observational humor** — dry, situational, not performed
4. **Micro-narratives** — brief lived-experience references
5. **Pragmatic reassurance** — "Either way works"
6. **Brief validation** — "Nice." Once. Moves on.

These aren't removed during training — they're deprioritized. CPR brings them back without triggering safety violations or toxicity filters.

---

## Tested On

- **8+ models:** Claude (Opus/Sonnet/Haiku), GPT-4o, GPT-4o Mini, Grok, Gemini Flash/Pro
- **4 personality archetypes:** Direct/Minimal, Warm/Supportive, Professional/Structured, Casual/Collaborative
- **85+ scenarios** across short responses and 300+ message sessions
- **Success rate: 99%+**

---

## The Three Laws (Why Fixes Usually Fail)

Most AI personality fixes erode within a session. CPR V3.0 found why:

1. **Concrete beats abstract.** "See 'smart thinking' → delete it" beats "avoid sycophancy" every time. Abstract rules require judgment — RLHF wins the judgment call.
2. **Loaded beats referenced.** If the pattern isn't in the active context window, it doesn't exist. Filenames are decoration.
3. **Binary beats judgment.** Match/no-match. Delete/keep. The moment the model decides whether something is drift, it loses.

---

## Versions

| Version | What Changed |
|---------|-------------|
| V1.0 | Core patterns identified — but personality-specific (Direct/Minimal only) |
| V2.0 | Personality-agnostic principles — but abstract rules didn't persist |
| V3.0 | Concrete pattern-matching + compaction immunity + model-size calibration |

---

## Files

| File | What It Is |
|------|-----------|
| `RESTORATION_FRAMEWORK.md` | Core CPR theory and universal drift markers |
| `BASELINE_TEMPLATE.md` | Build your own personality baseline |
| `DRIFT_PREVENTION.md` | Standing orders, compaction immunity, daily reset |
| `CPR_EXTENDED.md` | Autonomous drift monitor for long-running agents |
| `TEST_VALIDATION.md` | 85+ test scenarios with pass/fail criteria |
| `CROSS_MODEL_RESULTS.md` | Model-by-model results |
| `MODEL_CALIBRATION.md` | Small vs. large model scaffolding differences |

---

## Quick Start

1. Read `RESTORATION_FRAMEWORK.md` — understand universal vs. personality-specific drift
2. Use `BASELINE_TEMPLATE.md` — define your personality archetype
3. Add patterns to your system prompt using `DRIFT_PREVENTION.md`
4. Validate with `TEST_VALIDATION.md`
5. For long sessions (100+ messages): add `CPR_EXTENDED.md`

Implementation takes 15-30 minutes.

---

## Related

- [Digital DNA](https://github.com/TheShadowRose/digital-dna) — computational paradigm for self-governing data (same author)

---

## Support

Free to use. If it helped: https://ko-fi.com/theshadowrose

Built by Agent Smith for Rose @ [Shadow Rose](https://x.com/TheShadowyRose)
