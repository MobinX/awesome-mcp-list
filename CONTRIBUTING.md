# Contributing to Awesome MCP List

Thanks for helping keep this list useful and consistent.

## What belongs here

- Real **MCP servers** that people can run or connect to
- A **public GitHub repository** for the server (required)
- One clear category fit in the existing README sections

Website-only / hosted endpoints **without** a public GitHub repo are not accepted,
even if the server is listed on the MCP Registry.

## Required entry format

Add **exactly one** new bullet to `README.md` in the right category.
Copy this template and fill it in:

```markdown
-   **[owner/repo](https://github.com/owner/repo)** [![GitHub stars](https://img.shields.io/github/stars/owner/repo?style=social)](https://github.com/owner/repo): Short one-line description of what the MCP server does.
```

Rules:
- Use three spaces after `-`
- Bold linked `owner/repo` pointing at the public GitHub repo
- Include the GitHub stars badge for the **same** `owner/repo`
- Keep the description to one concise sentence
- Do not reformat unrelated lines
- Do not add duplicates (search the README for your repo first)

## How to open a pull request

1. Fork this repository
2. Create a branch from `main`
3. Add your single README bullet in the correct category section
4. Open a PR with:
   - Title like: `Add owner/repo to <Category>`
   - A short note: what the server does, repo URL, and which category you chose
5. Make sure the PR only changes `README.md` (unless maintainers asked for something else)

## Checklist before you submit

- [ ] Public GitHub repo exists and is not archived
- [ ] Entry uses the exact format above
- [ ] Placed in the best existing category
- [ ] Not already listed in the README
- [ ] Description is accurate and concise
- [ ] Diff is a single new bullet (no drive-by edits)

## What gets closed

PRs/issues are usually closed when they:
- Link only a website or hosted MCP URL (no public GitHub repo)
- Use the wrong format (missing badge, wrong spacing, no `owner/repo`)
- Duplicate an existing listing or another open PR
- Point at a dead/404 repository
- Rewrite large parts of the README unrelated to the new entry

If we close your PR for format reasons, fix it and open a new PR — happy to merge clean submissions.
