# Dominvm — VS Code Theme

A pair of carefully crafted **Light** and **Dark** color themes for Visual Studio Code, designed for legibility, reduced eye strain, and a warm, premium aesthetic.

---

## Themes

### Dominvm Light

A refined light theme built on a warm, cream-toned palette that eliminates the harsh glare of pure white backgrounds.

- **Editor Background**: Warm White `#FFF9F0`
- **UI Surfaces**: Palladian `#EFE9E0`, Taupe Mist `#DFD9D0`, Timberwolf `#CFC9C0`
- **Text**: Dark Rosewood `#402020`
- **Accents & Links**: DOMINVM Rust `#CC3300`, DOMINVM Brown `#993300`
- **Headers**: Bold DOMINVM Rust `#CC3300`

### Dominvm Dark

A deep, luxurious dark theme with warm undertones that prevent the cold, sterile feel of pure black backgrounds.

- **Editor Background**: Dark Charcoal `#100505`
- **UI Surfaces**: Woodsmoke `#201010`, Dark Rosewood `#402020`
- **UI Text**: Warm Cream `#D4C4B0`
- **Editor Text & Accents**: Atomic Tangerine `#FF9966`
- **Headers**: Bold Pink `#FF99CC`

---

## Design Principles

- **WCAG AA Compliant**: All syntax tokens meet or exceed 4.5:1 contrast ratio for normal text
- **Eye Strain Reduction**: Warm-tinted backgrounds instead of pure white/black to reduce glare and haloing
- **Visual Hierarchy**: Distinct colors for UI chrome vs. editor content to prevent monotone fatigue
- **Semantic Coloring**: Each syntax category (keywords, strings, functions, types, etc.) has a unique, distinguishable hue

## Recommended Font

For the full Dominvm experience, add this to your VS Code `settings.json`:

```json
{
  "editor.fontFamily": "'DM Mono', 'Courier New', monospace"
}
```

## Color Palette

| Name              | Hex       | Usage                        |
|-------------------|-----------|------------------------------|
| Warm White        | `#FFF9F0` | Light editor background      |
| Palladian         | `#EFE9E0` | Light sidebar / tiles        |
| Taupe Mist        | `#DFD9D0` | Light activity bar / borders |
| Timberwolf        | `#CFC9C0` | Light title bar / shadows    |
| Dark Rosewood     | `#402020` | Light text / Dark UI surface |
| DOMINVM Rust      | `#CC3300` | Light accents & headers      |
| DOMINVM Brown     | `#993300` | Light icons & constants      |
| Dark Charcoal     | `#100505` | Dark editor background       |
| Woodsmoke         | `#201010` | Dark sidebar / surfaces      |
| Atomic Tangerine  | `#FF9966` | Dark accents & editor text   |
| Warm Cream        | `#D4C4B0` | Dark UI chrome text          |

---

## License

[MIT](LICENSE)
