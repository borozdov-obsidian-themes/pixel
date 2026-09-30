# Borozdov Pixel

A theme from the Borozdov collection. Two faces — light **Gridline**, a violet pixel-grid
over drafting-paper white, and dark **Voxel**, the same grid cut from block lines on
near-black glass. Slate ink for prose, near-black headlines, hairline cards instead of
shadows, one violet accent, and a terminal-dark panel for code that reads like a data
readout in either face.

![Borozdov Pixel in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/pixel/main/screenshots/light.png)

![Borozdov Pixel in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/pixel/main/screenshots/dark.png)

## Principles

- **The grid is the page, not decoration.** A violet dot-grid travels with the text on
  Gridline; Voxel cuts the same spacing into block lines instead of dots. Either way it
  stops at embeds, popovers and canvas cards — it never reads as noise under long prose.
- **Violet means it's live.** Links, tags and the active file carry the one accent;
  everything else in the interface stays slate and near-black.
- **The code panel is a fixed readout.** Block code keeps the same terminal-dark background
  in both faces — a data readout punched into the page — while inline code sits on each
  face's own surface tone.
- **Hairline, never shadow.** Cards and floating panels are held by a 1px line; shadow is
  reserved for floating panels (menus, modals, embeds), tinted with the theme's own slate.
- **Mono is the stamp, not the voice.** Pixel Mono sets code, tags, table headers, callout
  titles and property names in small tracked capitals; headings and prose stay in the
  platform's own sans.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts as plain hairline cards; the type's colour lives only in the stamped title and
  icon, never in a tinted background
- Block code as a fixed terminal-dark readout with syntax tokens in violet, pink and pale
  lavender; inline code on the surface tone
- Tables with a single frame and no doubled cell borders, headers in small mono capitals
- Tags stamped as pill-shaped mono capitals; property names read as labels, not boxed
  fields
- Quiet editing: no focus ring around the note, its title or form fields while you type
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours, grid and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory:** Settings → Appearance → Themes → Manage, search for
**Borozdov Pixel**, then **Install and use**.

**By hand:** download `manifest.json` and `theme.css` from the [latest
release](https://github.com/borozdov-obsidian-themes/pixel/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Pixel/`, then choose Borozdov Pixel under
Settings → Appearance → Themes.

## Font

Pixel Mono is embedded in `theme.css` as base64 WOFF2 under the SIL Open Font License 1.1
— see [`fonts/OFL.txt`](fonts/OFL.txt). It is a Latin and Cyrillic subset of Fira Mono
(© 2012–2015 The Mozilla Foundation and Telefonica S.A.), renamed because the original
carries a Reserved Font Name ("Fira") and the OFL forbids a modified copy from keeping it —
name IDs 1, 2, 3, 4, 6, 16 and 17, and the CFF top dict's font and family names, were
changed to "Pixel Mono" while the copyright notice was left untouched. One weight, scoped
to the monospace context only: code, inline code, tags, table headers, callout titles and
property names — never the reading voice.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Сетка» (Gridline) —
фиолетовая точечная сетка на чертёжной белой бумаге, и тёмный «Воксель» (Voxel) — та же
сетка, вырезанная блочными линиями на почти чёрном стекле. Пепельный текст, почти чёрные
заголовки, карточки на тонкой линии вместо тени, один фиолетовый акцент и терминально-тёмная
панель кода, читающаяся как показания прибора в обоих ликах. Моноширинный Pixel Mono
(урезанный и переименованный Fira Mono — у оригинала зарезервированное имя) отвечает только
за код, теги, заголовки таблиц, подписи колл-аутов и имена свойств. Устанавливается из
каталога: Настройки → Оформление → Темы → Настроить → Borozdov Pixel → Установить и
применить.
