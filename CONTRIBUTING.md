# Contributing to Project ReCharge Documentation

Thanks for helping keep this project’s documentation useful and accurate. **You do not need to know HTML or JavaScript.**

## Edit a page using GitHub

1. Open the public documentation website and select **Edit this page on GitHub**.
2. Sign in to your GitHub account.
3. Select the pencil icon (**Edit this file**) on the Markdown file.
4. Edit the text using the **Edit** tab; use **Preview** to check formatting.
5. Select **Commit changes**. If you cannot write directly to the repository, GitHub will offer to fork the repository and open a pull request.
6. Describe what you changed. A maintainer reviews and merges your pull request; the site updates after GitHub Pages deploys.

## Which file should I edit?

| Topic | File |
| --- | --- |
| Overview | `docs/index.md` |
| Research and impact | `docs/research.md` |
| Phoenix Pack | `docs/product.md` |
| Automation | `docs/automation.md` |
| Business and partners | `docs/business.md` |
| Project management | `docs/management.md` |

## Formatting basics

```md
## Section heading
### Subheading
A paragraph with **bold text**.
- A bullet point
- Another bullet point
[Related page](product.html)
```

Use the existing page structure. Keep claims supported by evidence, distinguish proposed designs from tested results, and never post private information, confidential partner material, or unsafe battery-handling procedures. Avoid stating that a prototype is certified or approved without documentation.

## Review workflow

- Contributors propose changes through pull requests.
- Maintainers review technical accuracy, safety, clarity, and confidential information.
- Approved changes are merged into `main` and published automatically.
- GitHub commit history preserves earlier versions and attribution.

Repository administrators can enable branch protection/rulesets for `main` and require pull-request review to prevent unreviewed publication.

## Adding images

Upload images to `assets/` and reference them in Markdown. The current lightweight renderer supports headings, paragraphs, lists, bold text, code, and links; image syntax and advanced Markdown tables are **not** supported on the published site yet. Link to images or request a website enhancement if inline images are needed.
