# CLAUDE.md

## Project purpose

This repo is an index of console game recompilations targeting x86 (PC) or ARM (Android/iOS) that the user has come across.

## Workflow

1. User provides a URL to a game recompilation project.
2. Fetch and summarize the page: what game it covers, what platforms it targets, and any key details.
3. Add an entry to `README.md` as a table row under the appropriate console/platform section.
4. If no section exists for that console yet, create one.

## README structure

- Top-level sections by original console (e.g. `## Nintendo GameCube / Wii`, `## PlayStation 2`, etc.)
- Each section has a markdown table with columns: `Game | Repo | Targets | Notes`
- `Targets` lists the output platforms (Windows, macOS, Linux, Android, iOS, etc.)
- `Notes` includes relevant details: GPU requirements, ROM/ISO format needed, accuracy goals, etc.
- Repos link directly to the GitHub (or equivalent) URL provided by the user.
