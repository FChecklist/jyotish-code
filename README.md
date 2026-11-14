# jyotish-code (rules data)
Rule database for the jyotish-engine project: 24,171 structured astrology rules (v8), split into ~2 MB JSONL parts in `rules/`.
- Fields: id, system, engine_role, life_area, input, outcome, timing, strength_note, remedy, source, confidence. (The `quote_short` column is left out of this copy.)
- Join parts in order to rebuild the file. Count after joining must be 24,171.
- Code lives in FChecklist/jyotish-engine. Plan: this data moves to Cloudflare D1.
- Status: public for now by the owner's decision (2026-11-14); may be made private later.
