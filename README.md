
# Type System

Combined duodecimal and hexidecimal type scale with pixel-perfect alignment and spacing

http://jxnblk.com/type-system

Type System is a general-purpose design system and stylesheet for beautiful, readable typesetting on the web.
Following tried-and-true typographic principles and inspired by Robert Bringhurst,
Type Systems offers smart defaults for consistently balanced hierarchy and effortless visual rhythm.


## Type Scale

Using CSS custom properties, the type scale offers greater contrast at larger viewport widths.

1. 64px
2. 48px
3. 32px
4. 24px
5. 16px
6. 12px

## Space Scale

Using an em-based scale, margins are derived from the core type scale and always align to an 8px baseline grid.

1. 8px
2. 16px
3. 32px
4. 64px
5. 128px
6. 256px

## Measure

Using 32em as the max-width ensures line lengths never exceed roughly 66 characters, staying within the widely-regarded range of 45 – 75 characters.


## Line Height & Margin

Font Size | Line Height | Pixel Line Height | Margin | Pixel Margin
------|-------|------|--------|------
64px  | 1.0   | 64px | 0.5em  | 32px
48px  | 1.33  | 64px | 0.5em  | 24px
32px  | 1.25  | 40px | 0.5em  | 16px
24px  | 1.33  | 32px | 0.66em | 16px
16px  | 1.5   | 24px | 1em    | 16px
12px  | 1.33  | 16px | 1.33em | 16px

## Space Scale

Font Size | m1 | m2 | m3 | m4
-----|------|------|-------|-------
64px | 32px | 64px | 128px | 256px
48px | 32px | 64px | 128px | 256px
32px | 16px | 32px |  64px | 128px
24px | 16px | 32px |  64px | 128px
16px | 8px  | 16px |  32px |  64px

MIT License

