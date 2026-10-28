# Heritage Web Framework

A reusable, accessible editorial website framework for authors, ministries, nonprofits, and other publishers.

## Project goals

- Fine Art + Heritage visual design with responsive layouts and WCAG 2.2 AA as a testing target.
- Simple publishing experience for nontechnical writers.
- GitHub-owned source code, transferable to client-owned deployments.
- Independent client installations; no client content or credentials in the master template.
- Preserve original blog titles, dates, slugs, embedded media, and internal links during migration.
- No production hosting commitment until the chosen publishing architecture is validated.

## Architecture decision (not final)

We are evaluating **traditional WordPress with a custom theme** versus **a Git-backed CMS with Vercel**. These are alternatives, not interchangeable deployment targets. The framework must not claim WordPress runs directly on Vercel. We will decide based on publisher usability, total cost, media volume, and shop requirements.

## First client implementation

Sons of St. Joseph is the first planned implementation. Its content and assets belong in a separate client-specific project, not in this master template. The shop is out of scope for the first milestone.

## Development milestones

1. Select and document the CMS/hosting architecture.
2. Build a reusable design system, templates, responsive navigation, and accessible components.
3. Prepare a migration inventory from the public website and eventual WordPress export.
4. Test a nontechnical author publishing an article, image, and correction unaided.
5. Verify original URL mapping, accessibility, performance, backup/restore and owner handover.

See [docs/PROJECT-PLAN.md](docs/PROJECT-PLAN.md).
