# Obsidian Cornell Notes Template

A Cornell-style note-taking template for Obsidian, with floating cue callouts and a summary block at the bottom.

## Files
- `Cornell Notes Template.md` — the note template
- `cornell-note.css` — the CSS snippet that creates the Cornell layout

## Install
1. Copy `Cornell Notes Template.md` into your Obsidian Templates folder
2. Copy `cornell-note.css` into `<your-vault>/.obsidian/snippets/`
3. In Obsidian: **Settings → Appearance → CSS snippets** → toggle on **cornell-note**

## Use
1. Create a new note → run **Insert template** (Templater plugin) → pick "Cornell Notes Template"
2. The frontmatter applies `cssclasses: cornell-note`, which activates the layout
3. Capture notes in the main column; add `> [!cue]` callouts where you want cue keywords/questions in the left margin
4. After the session, fill in the `> [!summary]` block at the bottom

Switch to **Reading view** (Cmd+E) to see the Cornell layout.
