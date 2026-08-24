# Edit Decision Engine — Chinese Talking-Head

This is the decision layer between transcript understanding and executable edits.

## Required output

For every semantic segment, produce an edit event with:

- `start`
- `end`
- `role`: hook / point / explanation / example / evidence / transition / conclusion / CTA
- `speaker`: keep / crop / cutout / temporary full-screen replacement
- `text`: none / caption / emphasis / title
- `visual`: none / photo / product / screenshot / video / graphic
- `layout`: full / split / pip / overlay / cutout
- `motion`: none / push / pull / reframe / reveal
- `reason`

## Decision order

1. Protect meaning and natural delivery.
2. Decide whether the speaker frame is sufficient.
3. If not sufficient, choose the smallest visual addition that improves comprehension.
4. Add emphasis text only when the phrase deserves visual hierarchy.
5. Add motion only when it marks a semantic or rhythmic change.
6. Validate that neighboring events are visually different enough without becoming noisy.

## Density targets

These are heuristics, not rigid timers:

- Hook: usually at least one meaningful visual event in the opening.
- Normal talking: visual event roughly every 3–7 seconds when the content benefits from it.
- High-density sections may change faster.
- Storytelling or emotional delivery may remain visually stable longer.
- Never insert a visual merely because a timer threshold was reached.

## Hierarchy

At any moment, there should be one obvious primary element:

1. speaker expression / action
2. concrete product or evidence
3. key text
4. supporting decoration

Never let all four compete equally.

## Edit restraint

A premium edit is allowed to have calm moments. Visual activity is not a goal by itself. Remove any event whose only justification is "the screen has been static".
