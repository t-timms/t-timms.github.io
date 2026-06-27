# t-timms.github.io

Personal portfolio site for **Tremayne Timms** — ML &amp; AI Engineer (DFW).

Single static `index.html`, no build step, no dependencies. Served by GitHub Pages
at <https://t-timms.github.io/>.

## Deploy

This is a GitHub user page, so the repo **must** be named `t-timms.github.io`
under the `t-timms` account. Pushing to the default branch publishes automatically
once Pages is enabled (Settings → Pages → Branch: `main` / root).

```bash
# from this directory
git add -A
git commit -m "feat: portfolio landing page"
git push -u origin main
```

## Edit

Everything lives in `index.html` (inline CSS, dark/light auto via
`prefers-color-scheme`). Update the project cards or skills directly in the markup.
