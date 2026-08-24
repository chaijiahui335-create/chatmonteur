# Video-Account QC Gate

## Purpose

Reject edits that are technically valid but editorially weak for a Chinese short-form business/owner talking-head video.

## Blocking checks

### Speaker

- Face is not repeatedly covered.
- Lip movement remains understandable.
- The speaker remains the primary visual character unless a replacement visual is clearly justified.

### Captions

- Chinese phrases are readable on a 9:16 phone frame.
- No caption wall dominates the frame.
- Emphasis is selective.
- Captions do not duplicate an already sufficient graphic.

### Visual rhythm

- No long unexplained static stretch where the content clearly changes.
- No repetitive zoom pattern.
- No effect spam.
- Visual events correspond to semantic changes or useful information.

### B-roll

- Every B-roll insert has a stated editorial reason.
- No unrelated stock footage.
- No repeated decorative inserts.
- Important speaker moments are not unnecessarily replaced.

### Audio

- Speech is intelligible and clearly dominant.
- Music remains underneath speech.
- SFX do not distract from words.
- No obvious clipping, silence, or A/V drift.

### Overall

The edit should look intentionally designed by an editor, not like a generic auto-caption template.

## Revision messages

Use concrete reasons when rejecting:

- `caption_overload`
- `speaker_obscured`
- `broll_unjustified`
- `visual_monotony`
- `effect_repetition`
- `audio_competes_with_voice`
- `meaning_changed_by_cut`

A rejected edit should return to the editorial plan instead of blindly adding more effects.
