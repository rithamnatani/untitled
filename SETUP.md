# Zed And Obsidian Setup

This vault is plain Markdown, so it opens in both Zed and Obsidian.

## Zed On Windows

1. Install Markdown Oxide:

```powershell
winget install -e --id FelixZeller.markdown-oxide
```

2. Restart Zed after the install finishes.

3. Open this folder in Zed.

4. Keep the `.zed/settings.json` file and `.moxide.toml` file in the repo root.

## What The Repo Already Does

- `.zed/settings.json` tells Zed to use `markdown-oxide` for Markdown files.
- `.moxide.toml` marks the folder as a Markdown Oxide vault root.
- Notes use `[[wikilinks]]`, so backlinks work in Obsidian-style workflows.

## For Your Friend

1. Clone the repo.
2. Install Markdown Oxide with the same `winget` command above.
3. Restart Zed.
4. Open the repo folder.

If `winget` is not available on their machine, they need to install `markdown-oxide` some other way and make sure the `markdown-oxide` command is on `PATH`.

