# Tuft Your Scene

Turn a photo into a cute, recognizable illustrated Tufting rug. The skill preserves the subject's identity and a useful middle level of detail, simplifies photographic clutter, balances lively colors, and creates believable high/low pile texture.

## What it does

- Keeps 3–8 identifying features so the subject remains recognizable at thumbnail size.
- Uses a balanced 8–18 major shapes instead of literal photographic detail or extreme abstraction.
- Uses five to nine coordinated colors: mostly medium saturation, supported by light breathing space and a dark anchor.
- Creates believable cut-pile, loop-pile, carved grooves, and two to three pile heights.
- Outputs no text, letters, numbers, logos, captions, or watermarks unless the user explicitly provides the exact requested string.
- Prevents gray casts, neon overload, poster layouts, detailed miniatures, and generic yarn filters.

## Install

Download this repository and place the `tuft-your-scene` folder in your Codex skills directory.

## Use

Upload a photo and ask:

```text
Use $tuft-your-scene to turn this photo into a cute, recognizable illustrated Tufting rug with no text.
```

The default output is a single finished-rug image on a clean neutral surface with absolutely no text. Text is only allowed when the user explicitly supplies the exact string.

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
