# Honeysuckle Website Resources

Brand assets for Honeysuckle Enterprise and its entities (Automation, Scoring System, Blink). Consumed by other Honeysuckle repos as a git submodule.

## Layout

- `01_Vector_Master/` — full-color badge masters and monochrome stitch masters (4 entities × 2 = 8 SVGs)
- `04_Apparel_Variants/` — hat lockups and left-chest horizontal lockups (8 SVGs)
- `05_Docs/README.txt` — embroidery + brand notes from the production pack

## Brand colors

- Dark green: `#143629` (primary)
- Gold: `#B88A2A` (accent)

## Entities and icons

| Entity | Icon |
|---|---|
| Honeysuckle Enterprise (umbrella) | stacked blocks |
| Honeysuckle Automation | gear |
| Honeysuckle Scoring System | target |
| Honeysuckle Blink Timelapse | camera + arc arrow |

## Consuming this repo

Add as a git submodule in the consuming repo:

```bash
git submodule add https://github.com/HoneysuckleDesigns/Website_Resources.git public/brand
git submodule update --init --recursive
```

Refresh after assets change:

```bash
git submodule update --remote public/brand
```
