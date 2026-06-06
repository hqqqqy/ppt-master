---
deck_id: 蓝色简约
kind: deck
display_name: 蓝色简约论文答辩模板
summary: 清爽蓝白配色的学术论文答辩模板，以倾斜平行四边形为标志性元素，结合双线蓝边卡片、浅灰英文水印装饰，适合毕业答辩、研究汇报等学术场景。
canvas_format: ppt169
primary_color: "#0B88FF"
category: scenario
keywords: [蓝色, 简约, 学术, 答辩, 论文]
page_count: 9
page_types: [cover, toc, chapter, content, ending]
replication_mode: standard
---

# 蓝色简约论文答辩模板

## I. Template Overview

**Design intent**: A clean, professional academic presentation deck built around bright blue (#0B88FF) accents on a light textured white background. The signature motif is the italic parallelogram (平行四边形) used for TOC navigation and chapter transitions — the active chapter is highlighted in solid blue while others appear in translucent light gray. Content pages use double-stroke blue border cards with subtle drop shadows.

**Use cases**: Undergraduate/graduate thesis defense, academic seminar reporting, research paper presentation, competition project showcase.

**Tone**: Academic precision meets visual elegance. Bilingual Chinese/English decorative text throughout (e.g., section English names appear as large faded watermarks at bottom-right).

## II. Color Scheme

| Role | Hex | Usage |
|---|---|---|
| Primary Blue | `#0B88FF` | Active section highlight, thick stroke lines, icons, key accents |
| Light Blue | `#CEE7FF` / `#9DCFFF` | Card border shadow offset, secondary accent |
| Dark Text | `#000000` | All primary body and title text |
| Light Gray | `#F2F2F2` | Inactive parallelograms, background cards |
| Mid Gray | `#BFBFBF` | Secondary text, inactive decorative elements |
| Yellow Accent | `#FECB00` | Occasional letter-spacing accent in chapter labels |
| Off-white | `#FFFFFF` | Card fill backgrounds |
| Faded Gray Text | `#F2F2F2` | Large italic English watermark text (bottom-right) |

Background: Full-slide light textured PNG (`bg_texture.png`), no solid color fill.

## III. Typography

- **Section number** (e.g., "1.1"): Tw Cen MT Condensed Extra Bold, 29.33px, bold, #000000
- **Section title** (Chinese): 碳纤维正中黑简体 / 微软雅黑, 26.67px, bold, #000000
- **Cover main title**: 锐字云字库锐黑粗GB / 微软雅黑, 53.33px, #000000
- **Cover watermark**: Tw Cen MT Condensed Extra Bold, 106.67px, #F2F2F2 (ghost)
- **TOC chapter numbers**: Tw Cen MT Condensed Extra Bold, 48px, bold, italic
- **TOC chapter names**: 碳纤维正中黑简体, 32px, bold, italic
- **Content body**: 方正宋刻本秀楷简体 / 微软雅黑, 26.67px
- **Content titles/subtitles**: 碳纤维正中黑简体 / 方正宋刻本秀楷简体, 32px, bold
- **Bottom-right watermark EN**: Tw Cen MT Condensed Extra Bold, 48px, #F2F2F2, italic

## IV. Signature Design Elements

1. **Parallelogram navigation** (TOC & chapter pages): 6 skewed rhomboids span full width (y=249–471), active one solid #0B88FF, others #F2F2F2 at 0.8 opacity. Chapter number (48px, white, italic) floats at top-inside; Chinese name (32px, bold, italic) centered in lower band; English name (24px, white, italic) at very bottom.

2. **Page chrome (all content pages)**:
   - **Top-left thick blue line**: `x1=68, y1=51, x2=128, y2=51`, `stroke-width=6.667`, `#0B88FF`
   - **Top-left section number + title**: section number (29.33px, bold) at ~(71,95); Chinese title (26.67px, bold) at ~(120,96)
   - **Top-right brand logo**: `brand_logo.png` at `x=1149, y=46, w=69, h=69`
   - **Bottom-left decorative text**: 2-line small italic EN text + blue thick horizontal line at y=671
   - **Bottom-right indicator**: Chapter name Chinese (blue first char + black rest, 26.67px, bold, italic) + blue horizontal line + large faded EN translation (48px, #F2F2F2, italic)

3. **Double-stroke card**: Two concentric rectangles offset by 6–8px; outer border `#CEE7FF`, inner border `#0B88FF`, both `stroke-width=2.667`. Creates a layered depth effect.

4. **Colored tab underline**: Thin colored rounded rectangle (h=4.8px, rx=2.4) below tab labels; active tab gets `#0B88FF`, inactive `#A6A6A6`.

5. **Blue highlight parallelogram bars** (chapter transition bottom): 3 parallelograms at y≈501–563, solid #0B88FF fills with label text.

## V. Page Roster

| File | Type | Description |
|---|---|---|
| `001_cover.svg` | cover | Cover: large faded EN watermark + bold CN main title + info bar (presenter / institution / date) |
| `002_toc.svg` | toc | Table of contents: 6 parallelogram slots (first highlighted), chapter titles + EN sub-labels |
| `003_chapter.svg` | chapter | Chapter divider: section number header + 3 bottom parallelogram call-outs |
| `004a_content_text.svg` | content | Full-width content: header + intro paragraph + 3-column text grid with dashed separators |
| `004b_content_two_col.svg` | content | Two-column card layout: each column in a white rounded-rect card with blue bottom bar |
| `004c_content_three_col.svg` | content | Three-column icon card: icon + title + body text per column, bottom parallelogram labels |
| `004d_content_quote.svg` | content | Left narrative + right chart/figure placeholder with left-edge vertical accent |
| `004e_content_steps.svg` | content | Horizontal process steps: numbered circles connected by arrows |
| `005_ending.svg` | ending | Ending: large "THANKS" faded + bold CN closing message |
