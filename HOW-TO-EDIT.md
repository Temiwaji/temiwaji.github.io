# How to update your portfolio

The whole site lives in one file: `index.html`. To change anything after it's live:

1. Go to github.com/Temiwaji/temiwaji.github.io
2. Click `index.html`, then the pencil icon (Edit)
3. Find the text you want to change (Ctrl+F works in the editor)
4. Click "Commit changes" — the live site updates in about a minute

## Where things are in the file

- **Hero headline/tagline** — search for `hero-inner`
- **Rotating job titles** — search for `var roles=`
- **About story** — search for `01 · About`
- **Stats numbers** — search for `data-count`
- **Projects** — each one is a `<details class="proj">` block. Copy a whole block to add a new project; each has the five parts (Challenge, Why It Matters, Approach, Results, Lessons)
- **Map pins** — search for `pin(` near the bottom; format is `pin(latitude, longitude, 'popup text')`
- **Experience** — search for `xp-item`
- **Speaking / Community / Certifications** — search for `06 · Speaking`
- **Colors** — search for `:root` at the top; `--accent` is the green

Nothing needs to be installed or compiled. Edit, save, done.
