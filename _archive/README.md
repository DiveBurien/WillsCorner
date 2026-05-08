# Archived Site Versions

Snapshots of every previous `docs/index.html` + `docs/style.css` we built, in case you want to revisit one. **Outside `/docs/`, so none of these deploy to GitHub Pages** — only the current `/docs/` directory does.

| Folder | Style | Commit | Description |
|---|---|---|---|
| `v1-dark-website/` | Dark cybersecurity portfolio | `e5a5870` | First version — dark theme (`#0a0e14`), GitHub-green accent, hero with stats, animated nav, project cards. Looked great visually but content was thin. |
| `v2-resume-layout/` | Light resume layout | `4092d88` | Traditional resume look — white paper, Source Serif headings, navy accent, dense bullet-point projects, includes a Print/Save-as-PDF button. |
| `v3-dark-dense-website/` | Dark website + resume density | `4006b40` | Tried to combine v1's dark aesthetic with v2's content density. Added a terminal-styled skills matrix and bullet-point project cards. |

The current live site (`/docs/`) is the **modern-resume-theme inspired** version (commit `2790d40`).

## How to use

To swap a previous version back in:
```bash
cp _archive/v1-dark-website/index.html docs/index.html
cp _archive/v1-dark-website/style.css  docs/style.css
git add docs/ && git commit -m "Restore v1 site"
git push
```
