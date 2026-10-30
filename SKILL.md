---
name: botanical-premium-poster-skill
description: Generate a Simplified-Chinese 9:16 poster in the 「植物轻奢」(botanical-premium) style by 一张有戏. Use when the user wants a 植物轻奢 / botanical premium poster.
---

# 植物轻奢 · botanical-premium poster skill

一张有戏「植物轻奢」风格海报技能。输出一张 9:16 竖版、简体中文的独立海报。

## 用法
1. 确定一个主标题（2–4 字）和一句短句。
2. 画面只出现三段文字：主标题、短句、页脚「一张有戏 · 视觉习作」。
3. 版式可选：editorial-column, frame-within-frame。
4. 参照下方完整提示词模板，替换 Headline / Supporting phrase / 场景描述。

## 示例主题
- 玉兰：让盛放保留呼吸的空间（editorial-column）— One sculptural ivory magnolia branch with natural velvety petals on charcoal/ivory, boutique botanical editorial photography.
- 银杏：在一片叶子里看见季节（frame-within-frame）— Two golden fan-shaped ginkgo leaves and subtle natural shadows on warm ivory linen, quiet refined type and olive detail.
- 山茶：把颜色停在花瓣之间（editorial-column）— One deep blush camellia bloom with real layered petals and glossy deep-green leaves, generous warm white premium space.
- 竹叶：让轻与直共享一种节奏（frame-within-frame）— One fresh bamboo leaf branch with slender coherent veins and deep olive shadow, ivory field and minimal refined serif-like Chinese type.
- 莲：把清雅留在一处轮廓里（editorial-column）— One pale lotus blossom and broad matte leaf crop, soft natural water-like shadow, sage/ivory/charcoal refined botanical composition.
- 芍药：让繁盛拥有安静的秩序（frame-within-frame）— One sculptural pale-blush peony blossom photographed close with authentic petal structure, dark olive backdrop and airy ivory margins.
- 蕨：从细密的纹理读到生长（editorial-column）— One curled fern frond unfurling with coherent leaflets and fine hairs, deep green/ivory macro editorial, calm negative space.
- 兰：让一枝花留下自己的姿态（frame-within-frame）— One elegant orchid spray with plausible ivory petals and slender dark stem, warm ivory ceramic-like field, sparse muted gold detail.

## 完整提示词模板（第 1 张原文）
```
Use case: ads-marketing. Create exactly ONE polished professional 9:16 portrait poster, static flat artwork, Chinese-mainland cultural/creative studio portfolio concept.
Language: Simplified Chinese. Headline: 玉兰. Supporting phrase: 让盛放保留呼吸的空间. Tiny plain footer: 一张有戏 · 视觉习作. Exact visible text ONLY these three phrases, every character correctly formed. No English, random numbers, fake events, dates, addresses, awards, offers, prices, affiliations, calls to action or status labels. All content is fictional/conceptual creative brief, no real client claim.

SOURCE UNIVERSAL RULES:


These rules apply to every poster. Do not repeat them in layout or style notes.

- Build around one dominant message, one clear focal point, and one communication goal.
- Establish a simple reading order: headline -> focal image -> supporting copy -> supplied details.
- Preserve required copy exactly unless the user explicitly asks for rewriting.
- Keep important text readable, high-contrast, and inside safe margins.
- Use confident spacing and avoid overstuffed layouts.
- Avoid fake extra text, random logos, QR codes, decorative clutter, malformed typography, and generic AI-poster noise.
- Treat the poster canvas as static print/editorial artwork rather than a clickable interface. If the source explicitly requests a product UI, browser window, dashboard, or device mockup, preserve that depicted content inside the poster.
- CTA copy is extractive-only: include it only when the source explicitly supplies the wording. When output language differs, verify the translated CTA against a recorded exact source quote. Never invent action or status labels.
- If no CTA is sourced, leave the action area empty. If one is sourced, render it as ordinary poster typography in a footer or text lockup. Do not place poster-level action copy inside a button, rounded rectangle, pill, chip, capsule, tab, input field, or any other clickable-looking UI container; do not decorate it with a shadow, arrow, chevron, or cursor icon.



SELECTED STYLE — STRICTLY THIS VISUAL SYSTEM, DO NOT MIX OTHER STYLES:
# Botanical Premium

## Intent

Create a sophisticated botanical poster with refined natural forms, premium packaging sensibility, and calm organic luxury.

## Typography

- Use elegant serif or refined sans-serif with generous spacing.
- Keep text quiet and polished.
- Pair product/event name with botanical Latin-style label only if relevant.

## Palette

Sage, olive, deep green, ivory, moss, clay, blush, charcoal, muted gold.

## Imagery

Botanical closeups, leaves, petals, herbs, shadows, glass bottles, ceramic vessels, natural ingredients.

## Texture / Material

Matte paper, soft film grain, natural shadow, linen, ceramic, glass, pressed botanical details.

## Composition Rules

- Use botanical forms as elegant framing or central subject.
- Preserve airy negative space.
- Keep palette muted and expensive.
- Avoid rustic clutter; aim for boutique editorial.

## Avoid

Generic spa clichés, overcrowded leaves, bright artificial greens, childish floral patterns, and low-end eco labels.


INTERNAL COMPOSITION:
# Editorial Column

## Composition Structure

- Use one large typographic area and one narrower supporting column.
- Create asymmetric balance with image, negative space, or rule lines.
- Place metadata in a disciplined column or margin note.
- Let the layout feel like a high-end magazine page converted into a poster.

## Hierarchy Rules

1. Large headline or image creates first read.
2. Column copy provides context.
3. Source-supplied metadata sits in a small typographic lockup. Source-supplied action copy may appear only as plain text.

## Text Placement

- Use strong alignment and column widths.
- Keep body copy brief and readable.
- Use margins intentionally, including large empty zones.

## Image Treatment

Use editorial photography, cropped object, art detail, or abstract field.

## Spacing Rules

Whitespace is an active design element. Avoid filling the entire page.

## Aspect-Ratio Behavior

Best in `2:3`, `3:4`, `4:5`, and `16:9`. In square, use one dominant column and one compact side note.

## Avoid

Centered brochure layouts, generic event flyer structure, too many font styles, and long body copy.


SPECIFIC SUBJECT AND ART DIRECTION:
One sculptural ivory magnolia branch with natural velvety petals on charcoal/ivory, boutique botanical editorial photography.

Quality: exquisite thoughtful art direction, one immediate focal point, sophisticated typographic spacing and clear reading order, original expressive composition with wide enough safe margins. Headline large and readable at phone thumbnail; secondary text restrained, not generic template. Typography adapted sensitively to real Chinese glyphs, with the visual weight demanded by style. Material/light/print treatment consistent with selected style. If any person appears, fictional mainland Chinese adult, natural anatomy and authentic face; otherwise no people. All props physically coherent unless the SPECIFIC surreal idea deliberately changes physics. No trademarks or label text on products, no fake logos/watermarks/QR. No poster mockup, wall frame, multiple-poster collage, UI buttons or decorative website components. The creative theme must determine composition; vary crop, hierarchy and negative space across the series. Output one finished poster only.
```

全部 8 条提示词见 `PROMPTS.json`，来源见 `SOURCES.md`。
