# Contributing

Thanks for helping grow this list! Here's how to add a tool.

## Quick Rules

1. **It must be free** (or clearly labeled "free tier available").
2. **No affiliate/referral links** — direct links only.
3. **No shady extensions** — nothing with a history of data harvesting, ad injection, or malware flags.
4. **One tool per PR** (unless you're adding several to the same category — then batch them in one PR to that file).
5. **Check for duplicates** before submitting — use Ctrl+F on the category file first.

## How to Add a Tool

### Option A — Pull Request (preferred)

1. Fork the repo.
2. Open the relevant file in `categories/`. If none fit, use `categories/misc.md`.
3. Add your entry in this exact format, alphabetically sorted within its category:

```markdown
### [Tool Name](https://link-to-tool.com)
**Category:** Productivity · **Platforms:** Chrome, Firefox  
One-line description — what it does, why it's useful.
```

4. Open a PR. Fill out the PR template.

### Option B — Issue

No time for a PR? [Open an issue](../../issues/new?template=suggest-tool.yml) with the tool name, link, and a one-liner. A maintainer will add it.

## Review Checklist (what maintainers check)

- [ ] Link works and goes directly to the tool (official site or store page)
- [ ] Tool is actually free
- [ ] Not a duplicate
- [ ] Description is accurate and neutral (no marketing fluff)
- [ ] Correct category and alphabetical placement

## Reporting a Dead Link or Bad Tool

Open an issue with the `dead-link` or `flag` label, or just PR the removal directly — that's welcome too.

## Pull request format

Every pull request must include all of these sections:

1. Screenshots: required for UI changes and visual fixes. Otherwise write `Not applicable: <reason>`.
2. Recordings: required for interaction changes, animations, and flows. Otherwise write `Not applicable: <reason>`.
3. What changed: a description in very simple language.
4. Before / After: what the function or behavior was before, and what it is now.
5. Alignment: why this task was chosen and prioritized over other work.

Keep any other required sections, such as Changelog (when this repo's changelog tooling reads `## Changelog`) and Testing.

Use `.github/pull_request_template.md` when opening a pull request. Do not merge a pull request that is missing any of these sections.

