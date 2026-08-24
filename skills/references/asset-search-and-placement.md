# Asset Search and Placement — Chinese Short Video

## Goal

Turn spoken meaning into useful visual support without inventing facts or filling the timeline with generic stock.

## Search intent

Extract concrete nouns, actions, products, places, interfaces, numbers, comparisons, and examples from the transcript. Rank candidate assets by semantic relevance, visual clarity, and source reliability.

## Asset classes

1. User-supplied footage
2. User-supplied photos / product images
3. User-supplied screenshots / documents
4. Approved stock/video assets
5. Simple generated graphics based only on known spoken facts

## Placement modes

- `speaker_plus_asset`: keep the owner visible and place the asset beside/behind them
- `pip`: small supporting video/image while the owner remains primary
- `split`: speaker and asset share the frame
- `full_bleed`: asset fills the frame only when it communicates the point better
- `cutout_overlay`: speaker cutout over a simple asset background
- `detail_punch`: crop into a product/detail without replacing the whole scene

## Timing

Anchor an asset to the phrase that makes it relevant. Avoid arbitrary insert points. Remove the asset as soon as its explanatory job is complete.

## Relevance gate

Reject an asset when:

- it is generic decoration
- it does not match the spoken claim
- it introduces a fact the speaker did not establish
- it is visually impressive but semantically weak
- it repeats another asset without adding information

## No asset available

Do not invent a visual. Use typography, reframing, or a simple graphic instead.
