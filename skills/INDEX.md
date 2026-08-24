# ChatMonteur — Skill Index

The agent's editorial brain. Thin routers here; heavy reference material in `references/`, loaded on demand.

| Skill | Read when | Status |
|---|---|---|
| `montage.md` | Any edit session — the pipeline orchestrator. **Holds the capability map: what exists and when to call it.** Routes mechanical vs editorial, phases ①②③④ and the pre-preview privacy scan | ✅ ported |
| `video-account.md` | Chinese short-form/video-account talking-head work. Read for speaker-first editing, hook, visual-event, semantic text, visual assets, B-roll, Chinese caption, masking, and QC rules | ✅ custom |
| `premium-talking-head.md` | User wants a polished, high-end talking-head edit with designed text, images/video inserts, product moments, masking, and a coherent visual grammar | ✅ custom |
| `viral-chinese-talking-head.md` | User wants current Chinese viral-style talking-head editing; use as a reference for hook, rhythm, 花字, supplementary visuals, keyframe motion, sound, and anti-template checks | ✅ custom |
| `visual-storyboard.md` | Plan the visual story from the transcript before rendering; maps semantic beats to framing, text, assets, and layouts | ✅ custom |
| `cutting.md` | Removing pauses (deterministic branch) or fillers/stumbles/retakes (LLM branch) | ✅ ported |
| `hook-editing.md` | Voice and visuals recorded separately, matched by meaning (sidecar hook) | ✅ ported |
| `subtitles.md` | Building/burning captions (Netflix-grade standard, Cyrillic-aware) | ✅ standard FIXED 2026-07-26: no plate, no outline, colour accents only, karaoke default. Burn only on explicit request |
| `motion.md` | Graphics, zooms, b-roll: anchor-word sync, motion philosophy, visual-interest rules | ✅ ported |
| `sound.md` | Music beds, ducking, SFX placement (decisions; execution in references) | ✅ written |
| `production-rules.md` | Always — hard correctness rules (CFR, no stream-copy, loudnorm-last) | ✅ exists |

## Chinese video-account references (`references/`)

| Reference | Contents | Status |
|---|---|---|
| `broll-doctrine.md` | When B-roll earns its place, selection order, timing, layouts, anti-patterns | ✅ custom |
| `chinese-subtitles.md` | Chinese short-form caption segmentation, emphasis, placement, and mobile readability | ✅ custom |
| `spoken-text-layout.md` | **Editorial spoken-text layout, not ASR subtitles**: spoken caption layer, emphasis layer, context/title layer, Chinese line breaking, semantic timing, text-picture interaction, and QC | ✅ custom |
| `text-layout.md` | Semantic text hierarchy, emphasis phrases, headline cards, mobile-safe compositions | ✅ custom |
| `premium-text-layout.md` | Three-level Chinese text hierarchy, composition, timing, contrast cards, anti-patterns | ✅ custom |
| `visual-assets.md` | Image/video insert system, speaker+asset, PiP, full-screen inserts, source/rights discipline | ✅ custom |
| `asset-matching.md` | Semantic matching of real product footage, screenshots, photos, B-roll, and graphics to spoken anchors | ✅ custom |
| `visual-asset-manifest.md` | Machine-executable asset events, layouts, source validation, timing, and asset QC | ✅ custom |
| `edit-decision-engine.md` | Converts semantic segments into executable edit events: speaker, text, visual, layout, motion, reason | ✅ custom |
| `asset-search-and-placement.md` | Asset classes, semantic search intent, placement modes, relevance gate, no-invention rule | ✅ custom |
| `premium-composition.md` | Stable premium composition states, hierarchy, transitions, rhythm, and anti-template rules | ✅ custom |
| `short-video-retention.md` | Opening, information rhythm, repetition control, payoff, and CTA rules | ✅ custom |
| `mobile-safe-area.md` | 9:16 phone safe-area and collision rules for faces, products, captions, and UI regions | ✅ custom |
| `talking-head-effects.md` | Reframe/zoom rules, semantic anchors, anti-patterns | ✅ custom |
| `portrait-masking.md` | Speaker cutout/masking compositions and usage triggers | ✅ custom |
| `video-account-qc.md` | Blocking quality gate for speaker, captions, rhythm, B-roll, audio, and overall editorial quality | ✅ custom |

## General references (`references/`, loaded on demand)

| Reference | Contents | Status |
|---|---|---|
| `ffmpeg-cookbook.md` | NVENC presets, micro-fades, voice chain, xfade/J-cut, overlays, Ken Burns | ✅ ported |
| `known-issues.md` | FATAL anti-patterns + warnings (the "never do this" list) | ✅ ported |
| `effects.md` | Karaoke captions (pysubs2/\\kf), xfade transitions, LUT grading | ✅ ported |
| `playbooks.md` | P1–P11 operation playbooks (phrase removal, concat, overlays, oval mask…) | ✅ ported |
| `multiscene-pipeline.md` | Multi-scene assembly + LOCKED YouTube final render + concat-filter lesson | ✅ ported |
| `final-render-and-audio.md` | ONE-PASS final render, EQ-pocket + gentle duck canon, mixing levels | ✅ written |
| `edit-sequence.md` | Why the 4-phase order is load-bearing (lock cut → geometry → color → top layers → sound → encode) | ✅ written |
| `hyperframes-registry.md` | **Read before building any graphic.** The 138-item registry, block vs component, wiring, pointing the registry at our own brand items, and the determinism/caption rules that are not optional | ✅ written 2026-07-31 |
| `engineering-facts.md` | **The numbers that make an edit read as professional** — ducking/mix/SFX values, cutting thresholds, rhythm & B-roll doctrine, screencast zoom table, the quality-gate scoring that blocks a boring edit, vetted libraries, interchange truths. Mined 2026-07-30 | ✅ written |
