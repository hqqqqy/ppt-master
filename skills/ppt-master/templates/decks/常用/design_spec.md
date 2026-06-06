---
deck_id: 常用
kind: deck
category: scenario
summary: Clean blue-accent academic template with full-page photo background, ghost-text watermarks, and parallelogram TOC motif. Suits thesis defense, conference presentations, and research reports.
keywords: [academic, blue, minimal, research, thesis]
primary_color: "#0B88FF"
canvas_format: ppt169
replication_mode: fidelity
page_count: 11
page_types: [cover, toc, chapter, content, ending]
---

# 常用蓝色简约学术模板 — Design Specification

## I. Template Overview

Light-mode academic template built around a full-page photographic background (cover_bg.png), vivid `#0B88FF` blue accents, and large faded-grey English watermark text for compositional depth. Every slide shares a consistent chrome: thick blue top-left bar, circular brand emblem top-right, and a dual-bar bottom-left corner badge. Content pages add a bottom-right section label (two-tone: blue / black, italic) with a ghost English watermark. The TOC and chapter pages use a distinctive slanted-parallelogram motif echoing the blue-photo aesthetic. Ideal for 6-chapter academic presentations (15–30 slides).

## II. Color Scheme

| Role | Hex | Usage |
|---|---|---|
| Primary | `#0B88FF` | Lines, active highlights, section label first word, button fill |
| Accent-yellow | `#FECB00` | Invisible spacer glyph in section label (kerning trick) |
| Ghost | `#F2F2F2` | Large EN watermark text, parallelogram fill on TOC |
| Muted | `#BFBFBF` | TOC inactive number text, subtle icon fills |
| Divider | `#D9D9D9` | Tab underlines, thin separator lines |
| Text-primary | `#000000` | All readable text |
| Card-blue-light | `#CEE7FF` | Outer border of double-border content cards |
| Card-blue | `#9DCFFF` | Secondary quadrant fill in 4-box grid |
| Background | full-page photo | cover_bg.png (consistent across all pages) |

## III. Typography

Non-standard fonts — install before use:

| Role | Font family | Fallback |
|---|---|---|
| EN display / numbers | "Tw Cen MT Condensed Extra Bold" | sans-serif |
| ZH bold title | "碳纤维正中黑简体" | sans-serif |
| ZH body / serif | "方正宋刻本秀楷简体" | serif |
| ZH secondary | "等线" | sans-serif |
| Corner badge | "微软雅黑" | sans-serif |

Body baseline: 26.67 px (≈ 20 pt at 96 dpi).

## IV. Signature Design Elements

1. **Top-left blue bar** — 60 px horizontal line at y=51, stroke-width 6.667, `#0B88FF`. Present on every page.
2. **Bottom-left corner badge** — same bar at y=671 plus "CASE STUDY / RESEARCH." in 18.67 px bold MicrosoftYaHei above it. This is the fixed project-type label.
3. **Brand emblem circle** — cover_bg-adjacent asset `brand_emblem.png` at top-right (x=1149, y=46, 69×69 px). Present on every page.
4. **Ghost EN watermark** — 48 px italic Tw-Cen, `#F2F2F2`, bottom-right area. Text mirrors the section English name.
5. **Two-tone section label** — bottom-right, 26.67 px bold italic, letter-spacing 2.67: first word `#0B88FF`, rest `#000000`. Connected to the watermark by a short `#0B88FF` line.
6. **Parallelogram TOC motif** — slanted parallelograms (skew ~-17°) used in TOC and chapter pages; filled `#F2F2F2` at 80% opacity.
7. **Cover ghost title** — oversized EN ghost title (~107 px Tw-Cen `#F2F2F2`) behind Chinese main title (53 px 锐黑粗 `#000000`).

## V. Page Roster

| File | Type | Description |
|---|---|---|
| `01_cover.svg` | cover | Full-bg photo; top-left org badge; oversized ghost EN title behind Chinese main title; 3-field author row; corner date display. Placeholders: `{{TITLE}}`, `{{SUBTITLE}}`, `{{AUTHOR}}`, `{{DATE}}` |
| `02_toc.svg` | toc | 6 slanted parallelograms each holding chapter number (48px italic), Chinese chapter name (32px bold), EN chapter name (24px italic). Placeholders: `{{TOC_ITEM_1_TITLE}}`…`{{TOC_ITEM_6_TITLE}}` + `{{TOC_ITEM_1_DESC}}`…`{{TOC_ITEM_6_DESC}}` |
| `03_chapter.svg` | chapter | Same 6-parallelogram layout; active chapter parallelogram filled `#0B88FF`, others `#F2F2F2`. Placeholders: `{{CHAPTER_NUM}}`, `{{CHAPTER_TITLE}}` |
| `04a_content_tabs.svg` | content | 3-tab navigation bar (active tab underlined blue) with 3-column text area below. `{{PAGE_TITLE}}`, `{{SECTION_NUM}}`, `{{SECTION_NAME}}`, `{{SECTION_EN}}`, `{{CONTENT_AREA}}` |
| `04b_content_three_col.svg` | content | 3-column bullet layout with parallelogram category buttons at bottom; dashed grid separators. Same placeholders as content. |
| `04c_content_four_box.svg` | content | 2×2 card grid; each card double-bordered (outer `#CEE7FF`, inner `#0B88FF`); top icon + heading + body text. Same content placeholders. |
| `04d_content_two_card.svg` | content | 2 rounded-rect cards (white, shadow); each with large icon, text heading, body. Bottom gradient bar (blue / black). Same content placeholders. |
| `04e_content_image.svg` | content | Left: clipped slanted parallelogram image area (`{{IMAGE}}`); Right: 2 vertically stacked text+icon blocks. Same content placeholders. |
| `04f_content_timeline.svg` | content | Left: circular KPI / diagram area; Right: 3 horizontal rows (icon dot, heading, body) connected by vertical blue line. Same content placeholders. |
| `04g_content_list.svg` | content | 3 stacked 3D-notebook shapes (parallelogram outline + tab indicator); each with heading + body text; right-side flowing text column. Same content placeholders. |
| `05_ending.svg` | ending | Full-bg photo; oversized ghost "THANKS" behind Chinese closing line. Placeholders: `{{THANK_YOU}}`, `{{CLOSING_MESSAGE}}` |

## VI. Assets

| File | Size | Usage |
|---|---|---|
| `cover_bg.png` | 1280×720 (photo) | Full-page background on every slide |
| `brand_emblem.png` | 69×69 (circle) | Top-right brand logo on every slide |
