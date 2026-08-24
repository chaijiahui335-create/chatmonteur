# Chinese Video-Account Talking-Head Editorial Skill

## Purpose

This skill adapts ChatMonteur for Chinese short-form video-account content built around a real business owner or expert speaking to camera. The goal is not merely to remove pauses and burn captions. The goal is to produce a clear, human, information-dense 9:16 edit with deliberate visual events while keeping the speaker as the primary character.

## Required references

For every Chinese video-account edit, load these references as needed:

- `references/text-layout.md` for semantic text hierarchy and composition.
- `references/visual-assets.md` for image/video insert decisions and composition.
- `references/broll-doctrine.md` for B-roll relevance and timing.
- `references/talking-head-effects.md` for reframing and motion.
- `references/portrait-masking.md` for speaker cutout compositions.
- `references/chinese-subtitles.md` for mobile caption readability.
- `references/video-account-qc.md` before delivery.

## Editorial hierarchy

1. Meaning and spoken clarity
2. The speaker's credibility and presence
3. Hook and retention in the opening seconds
4. Visual variety that improves comprehension
5. Semantic text design
6. Relevant B-roll / screenshots / graphics / video inserts
7. Music and SFX
8. Decorative effects

Never sacrifice meaning, natural delivery, or speaker visibility for decoration.

## Default output

- Aspect ratio: 9:16.
- Preserve the original voice as the primary audio source.
- Preserve source resolution through the working timeline; do not create a 720p master merely for convenience.
- Prefer a clean, natural talking-head look over aggressive template effects.
- The speaker remains visible for most of the runtime unless a B-roll replacement materially improves understanding.
- Use one primary transition language across the edit; hard cuts are preferred.

## Phase 1: understand before cutting

Transcribe with word-level timing. Segment the transcript into semantic units such as:

- hook
- problem
- opinion / thesis
- explanation
- example / case
- evidence / number
- contrast / turn
- conclusion
- call to action

Remove only filler, unusable silence, false starts, repeated takes, and stumbles that do not contribute to the intended meaning. Do not over-cut natural breathing, emphasis, or short rhetorical pauses.

## Hook rule

The opening must communicate a reason to keep watching. Prefer the strongest usable sentence or short sequence from the recording. Do not manufacture claims that the speaker did not make.

During the first 1-3 seconds, create at least one intentional visual event when appropriate: a tighter crop, semantic headline, keyword treatment, graphic cue, or meaningful B-roll. Do not stack several effects merely to force activity.

## Visual-event doctrine

A static talking-head stretch becomes a candidate for a visual event when the content changes meaningfully or when visual monotony would reduce retention.

Possible events:

- subtle push-in / pull-back
- crop or reframing
- semantic emphasis text
- relevant image or short video insert
- screenshot / photo / document
- simple diagram or number card
- speaker cutout / masked composition when it improves explanation
- short punch-in on an important phrase
- product close-up when the spoken content refers to the product

Do not create an event just because a timer says one is due. Meaning controls timing.

## Text is not "automatic subtitles"

Never use raw ASR output as the final visual design. The transcript supplies timing and meaning; the editorial layer creates a separate text hierarchy.

Every segment may have:

1. spoken caption: compact phrase-level support
2. emphasis phrase: a short visual takeaway derived from the current idea
3. headline/card: only at major structural turns

The emphasis phrase must not simply repeat the entire sentence. It should compress the point into a few words the viewer can notice immediately.

## Zoom rules

- Default framing is 100%.
- Use small reframes for normal emphasis.
- Use stronger push-ins only for high-value phrases.
- Avoid repeating the same zoom direction and magnitude on consecutive events.
- Return toward the base composition after a cluster of emphasis unless the continued close-up is editorially justified.
- Never use zooms to hide a bad cut if a clean cut is possible.

## Speaker-first rule

The owner/expert is the hero of the edit.

- B-roll supports the spoken idea; it does not exist merely because it is available.
- Do not cover the speaker's face with captions, graphics, or B-roll.
- When possible, use picture-in-picture, masked overlays, side-by-side, or a short insert so the speaker remains part of the visual story.
- Full-screen B-roll is allowed when it explains a concrete object, process, interface, place, example, or evidence better than the speaker frame.
- Return to the speaker after the information has been delivered.

## B-roll decision test

Before inserting B-roll, answer:

1. What exact spoken idea does this visual clarify?
2. Is the visual concrete, relevant, and understandable without extra explanation?
3. Would the edit be clearer without it?

If the answer to the third question is yes, do not insert it.

Avoid generic office shots, random people typing, unrelated stock footage, repeated screenshots, and visual metaphors that do not add information.

## Chinese caption doctrine

Captions are an editorial layer, not a transcript dump.

- Break captions by meaning and natural Chinese reading rhythm.
- Prefer short lines and compact phrase groups.
- Emphasize only important words or short phrases.
- Keep the speaker's face and important graphics unobstructed.
- Do not display the entire transcript as a wall of text.
- Do not add an outline/plate unless the project explicitly requests it.
- Karaoke-style timing may be used when it improves rhythm, but it must remain readable.
- Avoid excessive color changes, bouncing text, and word-by-word decoration.

## Mask / cutout mode

Use speaker cutout when it creates a clear information hierarchy, for example:

- speaker in foreground + related screenshot behind
- speaker beside a large example image
- speaker over a simple topic card
- speaker pointing toward a highlighted number or phrase

Do not use cutout as a permanent effect. It is an emphasis mode for selected sections.

## Sound

- Voice is always the priority.
- Music must sit clearly below speech and duck under it.
- Use SFX sparingly for meaningful entrances, emphasis, or transitions.
- Never use a sound effect to compensate for weak editing.
- Do not let music masking or processing change the natural character of the speaker's voice.

## Quality gate

Before delivery, reject the edit if any of these are true:

- the speaker is repeatedly obscured
- B-roll is unrelated or decorative-only
- captions are difficult to read on a phone
- the same zoom/effect repeats mechanically
- a long section has no meaningful visual change when the content clearly calls for one
- captions occupy too much of the screen
- cuts remove natural emphasis or change the intended meaning
- music competes with speech
- the edit looks like an automatic template rather than an intentional editorial decision

## Review loop

Produce a mechanical draft first, then an editorial plan and preview. When the user gives feedback such as "太乱", "字幕太多", "这里放大", "这里不要 B-roll", "这里加插图", or "这里插一段视频", treat that feedback as an editorial constraint for the current project and apply it consistently to subsequent revisions.

## Non-goals

This skill does not generate a fictional speaker, invent claims, or replace the speaker with a digital avatar. It edits supplied real footage.
