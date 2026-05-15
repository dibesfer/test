# Fer + Alexos Workflow

## Goal

Use GitHub as the shared working surface between Fer and Alexos.

Not real-time editing.
Reliable turn-based syncing.
Simple commits.
Visible history.

## Core idea

Fer works locally or through GitHub UI.
Alexos reads the repo, edits files, and commits changes.
Fer reviews the result in GitHub, VS Code, GitHub Pages, or local clone.

## Best rhythm

1. Fer explains the goal.
2. Alexos reads the relevant files.
3. Alexos proposes or applies a focused change.
4. Alexos commits.
5. Fer pulls, reviews, tests, and reports back.

## Good use cases

- Text files
- Markdown notes
- HTML/CSS/JS prototypes
- Small code patches
- Project documentation
- MVP workflow logs
- GitHub Pages experiments

## Avoid pain

- Do not edit the same file from both sides at the same time.
- Prefer small commits over giant mystery changes.
- Keep one clear task per commit.
- Use filenames and paths explicitly.
- Fer should tell Alexos when local changes are not pushed yet.

## Source of truth

GitHub repo > committed files.

If something is only local on Fer's computer, Alexos cannot see it until it is pushed or uploaded.

## GitHub Pages note

For public previews, GitHub Pages may take a short moment to update after commits.
Use the repo files as truth; use the live page as preview.

## Working style

Ambition and humility.
Small sharp changes.
No overengineering.
Create > polish > ship.
