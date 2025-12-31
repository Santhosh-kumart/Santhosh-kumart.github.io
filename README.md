# Purple Theme Portfolio - Color Migration Guide

## Overview
This portfolio has been converted from a **Black/Gold** theme to a **Purple (Reflect)** theme.

## Color Mapping

### Primary Accent Colors
| Original (Gold)              | New (Purple)                    |
|-----------------------------|---------------------------------|
| `--orange-yellow-crayola`   | `--purple-primary` (#8B5CF6)    |
| `--vegas-gold`              | `--purple-light` (#C4B5FD)      |

### Background Colors
| Original                    | New                             |
|-----------------------------|---------------------------------|
| `hsl(240, 1%, 17%)` (onyx)  | `hsl(245, 20%, 12%)` (purple-tinted) |
| `hsl(240, 2%, 13%)` (eerie) | `hsl(240, 17%, 9%)` (deeper purple) |
| `hsl(0, 0%, 7%)` (smoky)    | `hsl(240, 20%, 4%)` (purple-black) |

### Gradient Changes
| Original                    | New                             |
|-----------------------------|---------------------------------|
| `--bg-gradient-yellow-1`    | `--bg-gradient-purple-1`        |
| `--bg-gradient-yellow-2`    | `--bg-gradient-purple-2`        |
| `--text-gradient-yellow`    | `--text-gradient-purple`        |

### New Purple Variables Added
```css
--purple-primary: hsl(263, 90%, 66%);    /* #8B5CF6 - Main accent */
--purple-light: hsl(263, 90%, 80%);      /* #C4B5FD - Light accent */
--purple-glow: hsl(263, 84%, 58%);       /* #7C3AED - Glow effects */
--purple-dark: hsl(263, 70%, 36%);       /* #5B21B6 - Dark accent */
--shadow-purple-glow: 0 4px 20px rgba(139, 92, 246, 0.4);
```

## Purple Spectrum Used (from Reflect Palette)
- **Purple 50:** #FAF5FF
- **Purple 200:** #E9D5FF
- **Purple 300:** #C4B5FD (Light accent)
- **Purple 400:** #A78BFA
- **Purple 500:** #8B5CF6 (Primary)
- **Purple 600:** #7C3AED (Buttons/Glow)
- **Purple 700:** #6D28D9
- **Purple 800:** #5B21B6
- **Purple 900:** #4C1D95
- **Purple 950:** #1A103A

## Files Modified
- `assets/css/style.css` - All color variables and styles updated
- `index.html` - No changes (colors come from CSS)
- `assets/js/script.js` - No changes (functionality only)

## Notes
- All hover effects now use purple glow
- Scrollbar thumb uses purple tint
- Form focus states use purple border
- Skill tags hover with purple background
- Timeline dots use purple gradient
- Navigation active state is purple

## Images
Your SVG icons (icon-bi.svg, icon-data.svg, icon-ml.svg, icon-nlp.svg) may still have gold/yellow colors. 
If you want them to match the purple theme, you'll need to edit the SVG files and change any gold colors to purple (#8B5CF6 or #C4B5FD).
