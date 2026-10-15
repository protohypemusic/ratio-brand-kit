# Ratio Accounting brand kit

Everything you need so the documents, spreadsheets, decks and emails you make
(with or without Claude) look and sound like the rest of Ratio: the logo, the
colors, the fonts and the writing rules.

**Quick download for Claude:**
[ratio-brand.zip](https://github.com/protohypemusic/ratio-brand-kit/releases/latest/download/ratio-brand.zip)

## What's inside

| Folder | What it is |
|---|---|
| `ratio-brand/` | The brand guide as a Claude skill. `SKILL.md` is the one-page summary. |
| `ratio-brand/reference/writing.md` | How Ratio writes to clients, and what never to say. |
| `ratio-brand/reference/documents.md` | Exact settings for Word, PDF, Excel, slides and email. |
| `ratio-brand/assets/logo/` | Logo files: color for light backgrounds, white for dark, plus the triangle mark. |
| `ratio-brand/assets/fonts/` | Lexend (headings) and Source Sans 3 (body). Free to install and share. |
| `ratio-brand/assets/icons/` | The small icons used in the monthly client report email. |
| `logos-hi-res/` | Full-resolution logos for print. |
| `meet-backgrounds/` | Ratio backgrounds for Google Meet video calls (navy and light). |

## Setup (about 5 minutes)

### 1. Give Claude the brand (the important one)

1. Download **[ratio-brand.zip](https://github.com/protohypemusic/ratio-brand-kit/releases/latest/download/ratio-brand.zip)**. Do not unzip it.
2. Open Claude (the desktop app or claude.ai) and go to **Settings**.
3. Find **Capabilities**. Make sure **Code execution and file creation** is
   turned on (Claude needs it to make Word, Excel and PDF files).
4. Find **Skills** and choose **Upload skill**. Pick `ratio-brand.zip`.
5. Make sure the **ratio-brand** skill is switched on.

From then on, when you ask Claude for a memo, report, spreadsheet, deck or
client email, it applies the Ratio brand on its own. You can also say "use the
Ratio brand" to be sure.

If you don't see Skills or the upload is blocked, the Team plan owner has to
allow skills once under **Admin settings**. They can also add this skill for
the whole team there, so nobody has to upload it.

### 2. Install the fonts on your computer

So Word, Excel and PowerPoint show Ratio's fonts.

- **Windows:** download this repo (green **Code** button, then **Download
  ZIP**), unzip it, open `ratio-brand/assets/fonts`, select all the `.ttf`
  files, right-click, **Install**.
- **Mac:** same download, double-click each `.ttf` file, **Install Font**.

Restart Word/Excel afterwards.

### 3. Try it

Paste this into a new Claude chat:

> Using the Ratio brand, make a one-page Word memo to a client explaining
> which documents we still need for their 2025 tax return.

You should get a file with the green Ratio logo top left, navy Lexend
headings, and clean writing with no long dashes.

## Google Meet backgrounds

Use one of these on video calls so everyone at Ratio looks the same on screen.
Navy suits most rooms; light is better if you sit in a bright room.

- **[Download the navy background](https://github.com/protohypemusic/ratio-brand-kit/releases/download/meet-backgrounds/ratio-meet-background-navy.jpg)**
- **[Download the light background](https://github.com/protohypemusic/ratio-brand-kit/releases/download/meet-backgrounds/ratio-meet-background-light.jpg)**

To set one up:

1. Download the image.
2. In Google Meet, before you join a call, click the sparkle icon (**Apply
   visual effects**) under your camera preview. During a call it's under the
   three dots menu.
3. Open **Backgrounds**, click the **+** tile, and pick the file.

Meet mirrors your own preview, so the logo looks backwards to you. Everyone
else sees it the right way round.

## Other ways to use it

- **Claude Project instead of a skill:** create a Project called "Ratio work",
  add the files from `ratio-brand/` (SKILL.md, the two reference files and the
  logo PNGs) as project knowledge, and put this in the project instructions:
  "Follow the Ratio brand files in this project for anything client-facing."
- **Claude Code (the Code tab):** open the unzipped `ratio-brand-kit` folder.
  `CLAUDE.md` tells Claude to follow the brand automatically.

## Good habits

- Never paste a full SSN, EIN or bank account number into Claude. Last four
  digits are enough.
- Read everything before it goes to a client. Claude drafts, you send.

## Updates

When the brand kit changes, download `ratio-brand.zip` again and upload it in
Settings to replace the old one.

Questions: Max.
