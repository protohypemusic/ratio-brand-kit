---
name: ratio-brand
description: Ratio Accounting's brand and writing rules. Use for ANY work that carries the Ratio name or goes to a client or prospect, including Word documents, PDFs, client reports and write-ups, memos, letters, proposals, spreadsheets, slide decks, charts, one-pagers and emails. Covers the logo files, colors, fonts, layout and how Ratio writes.
---

# Ratio Accounting brand

Everything Ratio sends should look and sound like it came from the same firm.
Follow this file for anything with the Ratio name on it.

## Before you make anything

1. Words a client or prospect will read: read `reference/writing.md` first.
2. A file (Word, PDF, Excel, slides, email): read the matching section of
   `reference/documents.md`.
3. Use the logo files in `assets/logo/`. Never retype, redraw, recolor or
   stretch the logo.

## The logo

| File | Use it on |
|---|---|
| `assets/logo/ratio-logo-color.png` | White or light backgrounds. The default. |
| `assets/logo/ratio-logo-white.png` | Navy or dark backgrounds only. |
| `assets/logo/ratio-logo-color-on-white.jpg` | Apps that mishandle transparent PNGs. |
| `assets/logo/ratio-logo-*-small.png` | Email and on-screen use (600px wide). |
| `assets/logo/ratio-mark-color.png` / `ratio-mark-white.png` | The triangle alone, for small square spots (slide corners, icons). Only when the full logo already appears somewhere on the same piece. |

Rules: keep it at its own proportions; leave clear space around it at least
half the height of the word RATIO; never smaller than 1.25 in (print) or
140 px (screen) wide; never on a busy photo; never add effects, shadows or
outlines.

## Colors

| Name | Hex | Use |
|---|---|---|
| Navy | `#0F172A` | Headings, table header fill, title slides, outlined buttons. The main brand color in documents. |
| Ink | `#1E293B` | Body text. |
| Blue | `#2563EB` | Links, the one highlighted number or series in a chart, small accents. |
| Light blue | `#DBEAFE` | Soft highlight behind a key figure or callout box. |
| Slate | `#64748B` | Secondary text, captions, footers. |
| Muted | `#94A3B8` | Fine print, placeholder text. |
| Border | `#E2E8F0` | Table lines, dividers, card outlines. |
| Paper | `#F8FAFC` | Light panel or alternating table row. |
| Positive | `#059669` | Only for a number that went the right way. |
| Negative | `#DC2626` | Only for a number that went the wrong way or is overdue. |
| Caution | `#D97706` | Only for a warning. |
| Ratio Green | `#377051` | Belongs to the logo. Do not use it as a general accent color. |
| Orange | `#F97316` | Website "Get a Proposal" buttons only. Never in client documents. |

White is the default background. Navy is punctuation: a title slide, a table
header, a footer band. Never a full page of navy in a document.

Chart series order: Blue `#2563EB`, Navy `#0F172A`, Slate `#94A3B8`,
Sky `#60A5FA`, then Positive/Negative only where they mean good/bad.

## Fonts

| Role | Font | Weight |
|---|---|---|
| Headings, titles, labels, buttons | **Lexend** | SemiBold (600) for titles, Medium (500) for smaller headings |
| Body text, tables, numbers | **Source Sans 3** | Regular (400), SemiBold (600) for emphasis, Bold (700) for totals |

Font files are in `assets/fonts/` (free to share under the SIL Open Font
License). When building a PDF or slides in code, load them from there so the
output really uses them. In Word and Excel files, set the fonts by name. If a
font is not available, fall back to Arial for both and keep the same sizes.

Numbers in tables line up: right-aligned, same number of decimals, thousands
separators, negatives in parentheses for financial statements.

## Firm details (use exactly)

- Name: **Ratio Accounting** (not "Ratio Accounting LLC" unless legal text needs it)
- Website: ratio-accounting.com
- Phone: 415-481-9008
- Serves clients nationwide
- Tagline (marketing only, never in a client report): Accounting Forward

## Icons

`assets/icons/` holds the small icons used in Ratio's monthly client report
email (revenue, profit, payroll, expenses, growth, trend, calendar, projects,
watch). Use them for the matching section of a client update. Do not mix in
emoji.
