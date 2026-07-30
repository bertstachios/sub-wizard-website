# Sub Wizard Website — Theme Reference

Dark-theme values hand-copied from the app repo's `src/style.css`
`:root` block (`sub-wizard/src/style.css`), matching what
`privacy.html` already hardcodes inline. No shared package or build —
each new static page should just copy these into its own `<style>`
block, same as `privacy.html` does.

```css
--bg: #0f1013;
--surface: #16181c;
--border: #26282d;
--text: #f2f0ea;
--text-dim: #8a8a86;
--gold: #d89a3e;
```

- `--bg` — page background
- `--surface` — card/section background
- `--border` — card/section border
- `--text` — primary text
- `--text-dim` — secondary/muted text (timestamps, captions)
- `--gold` — accent color (headings, links)

The app repo also defines a light theme and several other variables
(`--surface-2`, `--purple`, `--danger`, etc.) not reproduced here —
this site only ever uses the dark palette, and only these six values,
matching `privacy.html`'s existing scope.
