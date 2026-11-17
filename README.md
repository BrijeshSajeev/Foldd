# Foldd

**Your working memory, sorted.** Foldd is a keyboard-friendly, Markdown-first vault for the snippets, architecture decisions, and fixes you want to find again.

Foldd is designed for developers who have saved the same command in three places, remember the Rails fix but not the exact incantation, or want a lightweight home for decisions that do not belong in a project README.

## Try it

No dependencies or build step are required. Clone the repository and open `index.html` in a modern browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## What it does

- Keeps snippets, decisions, and troubleshooting notes in one searchable vault.
- Organizes notes by project and tags, with starred and recently edited views.
- Edits and previews Markdown, including fenced code blocks.
- Saves automatically to browser local storage when you save a note. The starter vault is local to the device and works offline after the page is loaded.
- Imports `.md` files and exports a portable JSON backup of the full vault.
- Supports keyboard-first use: `N` for a note, `⌘/Ctrl K` for search, `⌘/Ctrl Enter` to save, `?` for shortcuts, and `J` / `K` to move through notes.

## Privacy and storage

Foldd has no account, server, analytics, or third-party data service. Notes stay in the browser profile where they were created. Export the vault regularly if you need a backup or want to move it to another browser. Clearing browser storage removes the local copy.

## Built with

Vanilla HTML, CSS, and JavaScript. The app deliberately has no runtime dependencies, so it is quick to run, inspect, and fork.

## Roadmap

- Markdown-folder sync for Git-backed workflows.
- Optional encrypted vault export.
- Better import mapping for note type, project, and tags from front matter.
- Accessible focus treatment and broader screen-reader review.

## Contributing

Ideas and focused pull requests are welcome. For larger changes, open an issue first so the interaction and storage model stay small and predictable.

## License

MIT. See [LICENSE](LICENSE).
