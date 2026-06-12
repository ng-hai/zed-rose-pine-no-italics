<p align="center">
    <img src="https://github.com/rose-pine/rose-pine-theme/raw/main/assets/icon.png" width="80" />
    <h2 align="center">Rosé Pine Recast for Zed</h2>
</p>

<p align="center">All natural pine, faux fur and a bit of soho vibes for the classy minimalist — the VSCode Rosé Pine syntax mapping, recast for Zed without italics.</p>

<p align="center">
    <a href="https://github.com/rose-pine/rose-pine-theme">
        <img src="https://img.shields.io/badge/community-rosé%20pine-26233a?labelColor=191724&style=for-the-badge" />
    </a>
</p>

## About

This is **not** the official Zed theme with italics switched off. It ports the syntax token-to-color mapping from the [**VSCode** Rosé Pine](https://github.com/rose-pine/vscode) theme to Zed — which scopes colors differently from the official Zed port (over 20 token scopes remapped, several defined that the Zed port doesn't) — and removes italics from code (retained only on markdown emphasis and AI ghost text). The canonical Rosé Pine palette is unchanged: the **Rosé Pine** name credits the palette, and *Recast* marks the reworked syntax mapping.

Because it's a different syntax design rather than a toggle, it ships as a standalone theme alongside — not a replacement for — the official Rosé Pine for Zed.

## Usage

1. Install the **Rosé Pine Recast** extension from Zed extensions
2. Select your desired variant from the theme selection menu

## Variants

- Rosé Pine Recast
- Rosé Pine Recast Moon
- Rosé Pine Recast Dawn

## Customizing

This theme ships without italics by design. If you'd like italic comments, add a `theme_overrides` block to your Zed `settings.json` — it overrides the theme in place, no fork needed:

```json
{
  "theme_overrides": {
    "Rosé Pine Recast": {
      "syntax": {
        "comment": { "font_style": "italic" }
      }
    }
  }
}
```

`theme_overrides` targets one theme at a time — repeat the block for `Rosé Pine Recast Moon` and `Rosé Pine Recast Dawn` if you use those variants.

## Gallery

### Rosé Pine Recast

![Rosé Pine Recast editor preview](assets/rose-pine.png)

### Rosé Pine Recast Moon

![Rosé Pine Recast Moon editor preview](assets/rose-pine-moon.png)

### Rosé Pine Recast Dawn

![Rosé Pine Recast Dawn editor preview](assets/rose-pine-dawn.png)

## Credits

Built on the canonical [Rosé Pine palette](https://rosepinetheme.com), with the syntax-color mapping ported from the [VSCode Rosé Pine](https://github.com/rose-pine/vscode) theme. Inspired by the official [Rosé Pine for Zed](https://github.com/rose-pine/zed) theme. The italic removal and any further tweaks are specific to this variant.

## License

[MIT](LICENSE)
