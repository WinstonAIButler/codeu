# CodeU

Prototype site for an online college for coding and AI integration.
Single-file static site: `index.html` (no build step, no dependencies).

## Deploy (GitHub Pages)
1. Push this folder to a GitHub repo.
2. Repo Settings -> Pages -> Source: "Deploy from a branch" -> Branch: `main` / `/ (root)`.
3. Site publishes at https://<username>.github.io/<repo>/ within a minute or two.

## Notes
- The "office hours" AI chat only runs inside the Claude viewer. On a plain
  static host it degrades to an explanatory note; wiring it up on your own
  domain needs a small backend that calls the Anthropic API server-side.
- Not an accredited institution. See the site footer / Accreditation page.
