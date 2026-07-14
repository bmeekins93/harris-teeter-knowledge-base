# Harris Teeter Knowledge Base

A central reference hub for store operations, policies, procedures, training, contacts, and forms — published as a simple website with GitHub Pages.

## What's here

- **`index.html`** — the knowledge base homepage. It's fully self-contained (all styles and scripts are inline), so nothing else is required for it to render. This is what GitHub Pages serves.

## Live site

Once GitHub Pages is enabled (Settings → Pages → Deploy from a branch → `main` / root), the site is published at:

```
https://<your-username>.github.io/harris-teeter-knowledge-base/
```

Changes pushed to the `main` branch go live automatically within a minute or two.

## Editing

Open `index.html` and edit directly:

- **Replace the placeholder section cards** with your real links, documents, and notes.
- **Add a new card** by copying an existing `<a class="card">…</a>` block.
- The `data-keywords` attribute on each card feeds the search box — add relevant terms there so sections are easy to find.

No build step, no dependencies — edit the file, commit, and it's live.

## Notes

- This repository is **public**, which is what lets GitHub Pages publish for free. Keep sensitive or internal-only details out of it.
