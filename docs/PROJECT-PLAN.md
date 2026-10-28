# Project plan

## Reusable master versus client instances

This repository contains framework code, generic design components, tooling and documentation. A client's copied deployment should have its own repository, accounts, content, domain, billing and backups. Third-party license notices must be retained. Do not place credentials or private commerce data in GitHub.

## Design direction

Fine Art Editorial + Heritage Magazine: warm ivory, oxblood, aged gold, print-inspired serif typography, restrained photography, rich whitespace, strong keyboard focus and readable typography.

## WordPress migration

Preferred source: Tools > Export > All Content (WXR XML), plus an independent copy of wp-content/uploads and a record of menus, custom fields and installed plugins. Public scraping can inventory only accessible content and is not equivalent to a full backup.

Migration must track original URL, destination URL, title, publication date, tags/categories, featured images, embedded media and link status. Never redirect navigation to the old site as a substitute for imported content.

## Joseph's publishing acceptance test

A nontechnical writer can sign in, create a post, upload an image, save a draft, publish, edit a typo, and find the published URL without developer intervention.

## Hosting guardrails

GitHub stores source code, not a running PHP application. Traditional WordPress requires PHP, database, and media storage on compatible hosting. Headless WordPress still requires WordPress hosting. Git-backed CMSs can avoid PHP hosting but add authentication, Git deployments, and potentially commerce limitations.

## Security, accessibility and handover

Target WCAG 2.2 AA; validate with automated checks and manual keyboard/mobile testing. Document backups and test restoration. Transfer accounts and recovery methods to the client at handover. Treat free hosting as a conditional option; confirm use policy, storage, support, renewal costs and reliability.
