# Anne Arundel Theme

A custom Hugo theme for the Anne Arundel County Guide, based on Blowfish.

## Phi-Distributed Color Scheme

This theme features a unique color scheme based on the **golden ratio** (φ ≈ 1.618) and the **golden angle** (≈ 137.5°), following the phyllotaxis pattern found in nature like pine cones and sunflowers.

### The Four Phi-Distributed Colors

Using the golden angle on the color wheel, we positioned four colors evenly:

| Position | Angle | Color | RGB Value | Usage |
|----------|-------|-------|-----------|-------|
| **Primary** | 0.0° | Red | (230, 34, 34) | Accent colors |
| **Primary** | 137.5° | Emerald Green | (34, 230, 91) | **Main accent** (links, buttons, highlights) |
| **Secondary** | 275.0° | Vibrant Purple | (148, 34, 230) | **Secondary accent** (highlights, special elements) |
| **Tertiary** | 52.5° | Golden Yellow | (230, 205, 34) | Warning, attention indicators |

### Why Phi Distribution?

The golden angle creates a natural, pleasing color harmony that:
- Appears in nature (sunflower seeds, pine cones, nautilus shells)
- Provides excellent visual balance
- Creates high contrast between colors
- Is aesthetically pleasing to human eyes

### Color Scale

The theme provides a full CSS color scale for both primary and secondary colors:
- `50-100`: Very light shades (for backgrounds)
- `200-400`: Light shades (for borders, hover states)
- `500`: Base color (main usage)
- `600-900`: Dark shades (for text, active states)

### Usage

The color scheme is automatically applied when using the `anne-arundel` color scheme in your Hugo configuration:

```toml
[params]
  colorScheme = "anne-arundel"
```

## Customization

### Hero Image

The hero layout uses a custom hero image:

```toml
homepage.homepageImage = "/img/anne-arundel-hero.svg"
```

### Homepage Layout

The site uses the hero layout for an engaging homepage:

```toml
homepage.layout = "hero"
```

## Credits

- Original Blowfish theme by [Nuno Coração](https://github.com/nunocoracao/blowfish)
- Golden ratio mathematics based on natural phyllotaxis patterns
