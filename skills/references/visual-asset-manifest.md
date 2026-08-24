# Visual Asset Manifest

The storyboard must describe assets in a machine-executable, reviewable form before rendering.

## Required fields

Each asset event should contain:

- `start`
- `end`
- `type`: `image | video | screenshot | product | graphic | cutout`
- `source`
- `reason`
- `layout`: `fullscreen | pip | side_by_side | masked_background | corner_insert | detail_crop`
- `caption_anchor` when text is attached
- `return_to_speaker`: boolean

## Source rules

`source` must point to an actual project file, approved media resolution, or a generated project-owned graphic. Never invent a filename.

## Review rules

Every event needs a human-readable `reason` tied to a spoken semantic segment. If the reason is only "make it dynamic", reject it.

## Duration

Default insert duration is short and purposeful. Keep a full-screen insert only while it carries information. Product/detail shots can be longer when the viewer needs time to inspect the item.

## Layout rules

- `pip`: speaker remains visible; asset is secondary.
- `side_by_side`: use when comparing or explaining two things.
- `masked_background`: use for selected speaker cutout moments.
- `detail_crop`: use to show a product/detail without losing the speaker context elsewhere in the sequence.
- `fullscreen`: reserve for evidence, demonstration, or a visual that is materially clearer without the speaker frame.

## Asset quality gate

Reject:

- stretched images
- mismatched aspect ratios without deliberate crop
- low-resolution assets scaled beyond sensible limits
- visible watermarks when the source is not licensed for the project
- unrelated generic stock
- asset repeats without a new editorial purpose
