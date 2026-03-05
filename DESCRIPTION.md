# Dominvm — VS Code Theme

A collection of carefully crafted **Light**, **Dark**, and **Dark Solarized** color themes for Visual Studio Code in three warm-toned palettes — **Original**, **Green**, and **Blue** — designed for legibility, reduced eye strain, and a luxurious aesthetic.

---

## Themes

### Dominvm Light

A refined light theme built on a warm, cream-toned palette that eliminates the harsh glare of pure white backgrounds.

- **Editor Background**: Warm White `#FFF9F0`
- **UI Surfaces**: Palladian `#EFE9E0`, Taupe Mist `#DFD9D0`, Timberwolf `#CFC9C0`
- **Text**: Dark Rosewood `#402020`
- **Accents & Links**: Dominvm Rust `#CC3300`, Dominvm Brown `#993300`
- **Headers**: Bold Dominvm Rust `#CC3300`

### Dominvm Dark

A deep, luxurious dark theme with warm undertones that prevent the cold, sterile feel of pure black backgrounds.

- **Editor Background**: Dark Charcoal `#100505`
- **UI Surfaces**: Woodsmoke `#201010`, Black Cherry `#301515`
- **UI Text**: Warm Cream `#D4C4B0`
- **Editor Text & Accents**: Atomic Tangerine `#FF9966`
- **Headers**: Bold Pink `#FF99CC`

### Dominvm Green Light

A nature-inspired light theme with soft sage and mint tones for a calm, focused coding experience.

- **Editor Background**: Mint Cream `#F5FAF0`
- **UI Surfaces**: Sage Mist `#E5EFD8`, Frosted Sage `#D0DFCA`, Silver Sage `#C0CFC0`
- **Text**: Forest Ink `#1E3320`
- **Accents & Links**: Dominvm Green `#2E7D32`, Dominvm Emerald `#1B5E20`
- **Headers**: Bold Dominvm Green `#2E7D32`

### Dominvm Green Dark

A deep forest dark theme that immerses you in rich, earthy greens without harshness.

- **Editor Background**: Deep Forest `#050F05`
- **UI Surfaces**: Woodland `#101E10`, Dark Moss `#152815`
- **UI Text**: Pale Sage `#BCD4B0`
- **Editor Text & Accents**: Spring Green `#66BB6A`
- **Headers**: Bold Orchid Bloom `#CE93D8`

### Dominvm Blue Light

A serene, cool-toned light theme with icy blue undertones for a crisp, professional workspace.

- **Editor Background**: Ice Wash `#F0F5FA`
- **UI Surfaces**: Mist Blue `#DDE8EF`, Steel Whisper `#CCDAE5`, Pewter Blue `#BCC9D0`
- **Text**: Navy Ink `#1A2533`
- **Accents & Links**: Dominvm Blue `#1565C0`, Dominvm Cobalt `#0D47A1`
- **Headers**: Bold Dominvm Blue `#1565C0`

### Dominvm Blue Dark

A midnight-toned dark theme with deep indigo undertones for focused late-night coding sessions.

- **Editor Background**: Midnight Ink `#050810`
- **UI Surfaces**: Dark Navy `#101520`, Deep Indigo `#152030`
- **UI Text**: Pale Steel `#B0C4D4`
- **Editor Text & Accents**: Sky Blue `#64B5F6`
- **Headers**: Bold Rose Quartz `#F48FB1`

### Dominvm Dark Solarized

A warm, lifted-dark theme with rosewood mid-tones — softer contrast than full dark for extended comfort.

- **Editor Background**: Rosewood Dusk `#201215`
- **UI Surfaces**: Claret Ash `#2D1B1E`, Burgundy Smoke `#382428`
- **UI Text**: Warm Cream `#D4C4B0`
- **Editor Text & Accents**: Atomic Tangerine `#FF9966`
- **Headers**: Bold Pink `#FF99CC`

### Dominvm Green Dark Solarized

A nature-forward solarized dark theme with mossy mid-tones for ambient, relaxed coding.

- **Editor Background**: Fern Dusk `#122012`
- **UI Surfaces**: Moss Shadow `#1B2D1B`, Pine Smoke `#243824`
- **UI Text**: Pale Sage `#BCD4B0`
- **Editor Text & Accents**: Spring Green `#66BB6A`
- **Headers**: Bold Orchid Bloom `#CE93D8`

### Dominvm Blue Dark Solarized

A refined solarized dark theme with deep cobalt mid-tones — the warmth of twilight in a code editor.

- **Editor Background**: Cobalt Dusk `#0C1828`
- **UI Surfaces**: Sapphire Ash `#142235`, Navy Smoke `#1C2C42`
- **UI Text**: Pale Steel `#B0C4D4`
- **Editor Text & Accents**: Sky Blue `#64B5F6`
- **Headers**: Bold Rose Quartz `#F48FB1`

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

### Original (Warm Red)

| Name              | Hex       | Usage                        |
|-------------------|-----------|------------------------------|
| Warm White        | `#FFF9F0` | Light editor background      |
| Palladian         | `#EFE9E0` | Light sidebar / tiles        |
| Taupe Mist        | `#DFD9D0` | Light activity bar / borders |
| Timberwolf        | `#CFC9C0` | Light title bar / shadows    |
| Dark Rosewood     | `#402020` | Light text                   |
| Black Cherry      | `#301515` | Dark UI surface              |
| Dominvm Rust      | `#CC3300` | Light accents & headers      |
| Dominvm Brown     | `#993300` | Light icons & constants      |
| Dark Charcoal     | `#100505` | Dark editor background       |
| Woodsmoke         | `#201010` | Dark sidebar / surfaces      |
| Atomic Tangerine  | `#FF9966` | Dark accents & editor text   |
| Warm Cream        | `#D4C4B0` | Dark UI chrome text          |

### Green

| Name              | Hex       | Usage                        |
|-------------------|-----------|------------------------------|
| Mint Cream        | `#F5FAF0` | Light editor background      |
| Sage Mist         | `#E5EFD8` | Light sidebar / tiles        |
| Frosted Sage      | `#D0DFCA` | Light activity bar / borders |
| Silver Sage       | `#C0CFC0` | Light title bar / shadows    |
| Forest Ink        | `#1E3320` | Light text                   |
| Dominvm Green     | `#2E7D32` | Light accents & headers      |
| Dominvm Emerald   | `#1B5E20` | Light icons & constants      |
| Deep Forest       | `#050F05` | Dark editor background       |
| Woodland          | `#101E10` | Dark sidebar / surfaces      |
| Dark Moss         | `#152815` | Dark UI surface              |
| Spring Green      | `#66BB6A` | Dark accents & editor text   |
| Pale Sage         | `#BCD4B0` | Dark UI chrome text          |

### Blue

| Name              | Hex       | Usage                        |
|-------------------|-----------|------------------------------|
| Ice Wash          | `#F0F5FA` | Light editor background      |
| Mist Blue         | `#DDE8EF` | Light sidebar / tiles        |
| Steel Whisper     | `#CCDAE5` | Light activity bar / borders |
| Pewter Blue       | `#BCC9D0` | Light title bar / shadows    |
| Navy Ink          | `#1A2533` | Light text                   |
| Dominvm Blue      | `#1565C0` | Light accents & headers      |
| Dominvm Cobalt    | `#0D47A1` | Light icons & constants      |
| Midnight Ink      | `#050810` | Dark editor background       |
| Dark Navy         | `#101520` | Dark sidebar / surfaces      |
| Deep Indigo       | `#152030` | Dark UI surface              |
| Sky Blue          | `#64B5F6` | Dark accents & editor text   |
| Pale Steel        | `#B0C4D4` | Dark UI chrome text          |

### Solarized Surfaces

| Name              | Hex       | Family   | Usage                     |
|-------------------|-----------|----------|---------------------------|
| Rosewood Dusk     | `#201215` | Original | Solarized editor BG       |
| Claret Ash        | `#2D1B1E` | Original | Solarized sidebar         |
| Burgundy Smoke    | `#382428` | Original | Solarized activity bar    |
| Fern Dusk         | `#122012` | Green    | Solarized editor BG       |
| Moss Shadow       | `#1B2D1B` | Green    | Solarized sidebar         |
| Pine Smoke        | `#243824` | Green    | Solarized activity bar    |
| Cobalt Dusk       | `#0C1828` | Blue     | Solarized editor BG       |
| Sapphire Ash      | `#142235` | Blue     | Solarized sidebar         |
| Navy Smoke        | `#1C2C42` | Blue     | Solarized activity bar    |

---

## License

[MIT](LICENSE)

