# AGENTS.md

## Cursor Cloud specific instructions

This is a **Jekyll static site** (ACSL academic research lab website) based on the [al-folio](https://github.com/alshedivat/al-folio) theme.

### Services

| Service | Command | Notes |
|---|---|---|
| Jekyll dev server | `bundle exec jekyll serve` | Serves at `http://localhost:4000` by default. Add `--host 0.0.0.0` if needed for external access. |

### Quick reference

- **Install dependencies:** `sudo bundle install` (requires `ruby-full`, `build-essential`, `zlib1g-dev` system packages)
- **Build:** `bundle exec jekyll build` — output goes to `_site/`
- **Serve (dev):** `bundle exec jekyll serve` — live-reloads on file changes
- **Detached serve:** `bundle exec jekyll serve --detach` — runs in background; note the PID printed to stop later

### Non-obvious caveats

- There is no `Gemfile.lock` committed; `bundle install` resolves versions fresh each time.
- The `jekyll-github-metadata` plugin may emit a Faraday retry warning — this is cosmetic and does not affect the build.
- Sass deprecation warnings (`@import` rules, `lighten()`/`darken()`) are expected from the al-folio theme's SCSS and do not block the build.
- No linter or automated test suite is configured in this repository.
- The site has no backend, database, or external service dependencies.
