# Tuft Your Scene

Turn a photo into a cute, simplified and sculptural Tufting scene rug.

The default look follows three visual anchors: a flower-and-city garden, a steam train crossing a multi-arch bridge, and a forest lake framed by tall pines. It preserves the essential scene relationship while translating photographic detail into layered cut-pile and loop-pile relief.

## Default look

- Starts with a flat, texture-free cartoon pattern before adding any tufting material.
- Keeps only 3–6 identifying features and two to three clear spatial layers.
- Uses roughly 8–16 chunky rounded shapes and 5–8 coordinated, gently warm colors.
- Simplifies hair into one shape, clothing into clean blocks, animals into rounded silhouettes, cars into a few structural cues, and moons into a handful of lunar patches.
- Removes garment folds, fabric shadows, facial shading, fur strands, reflections, wheel spokes, headlight internals and crater noise.
- Builds tactile relief with cut pile, loop pile, carved grooves and two to three pile heights.
- Uses a perfectly uniform solid matte background with no sunlight, window shadows, gradients, vignettes or props.
- Shows the entire rug at about 70%–78% of the canvas, leaving an even 10%–15% margin on all sides.
- Outputs no text, letters, numbers, logos, captions, pseudo-text or watermarks unless the user explicitly supplies the exact string.

## Install

Download this repository and place it in your Codex skills directory as `tuft-your-scene`.

## Use

```text
Use $tuft-your-scene to turn this photo into a cute simplified Tufting rug. First compress it into 8–16 flat rounded shapes and 5–8 gently warm colors; remove realistic folds, shadows, hair strands, fur and tiny mechanical detail. Keep the background perfectly uniform, leave an even margin around the complete rug, and add no text.
```

## Structure

```text
tuft-your-scene/
├── SKILL.md
├── agents/openai.yaml
└── references/
    ├── tufting-language.md
    ├── prompt-recipes.md
    └── quality-rubric.md
```

## License

MIT
