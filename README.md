# Alle möglichen Rezepte

## Local Setup

1. Install `zola` via your package manager ([project site](https://www.getzola.org/))
2. `cd` into the repository
3. Run `zola server`.
4. The server should now run on https://127.0.0.1:1111

Zola automatically detects changes in the markdown files and reloads any open browser tabs.
However, if things break in the meta section of a page (before the `---` line), zola will crash with an error.
