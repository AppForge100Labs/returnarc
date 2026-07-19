# Returnarc website deployment

This public repository is the narrow GitHub Pages deployment mirror for Returnarc's customer support, privacy, and terms pages.

It is **not** the authoritative Returnarc application repository. The authoritative source of truth is the private `AppForge100Labs/appforge100` monorepo:

- iOS source: `apps/ios/habit/HabitApp/`
- Product Record: `apps/ios/habit/docs/PRODUCT_RECORD.md`
- release workflows and configuration: `.github/workflows/habit-app-*` and `apps/ios/habit/app-store/`
- canonical website source: `web/habit/`
- retained release evidence: `release/returnarc/`

Changes to these deployed pages flow one way from `web/habit/` in the monorepo to `main` here. This repository must not acquire application source, a Product Record, App Store configuration, release authority, or independent product decisions.

**Howth Forge 100** is the customer-facing business brand. AppForge100 is the internal factory name. The existing `AppForge100Labs` GitHub organization and `appforge100labs.github.io` URL are retained technical identifiers and do not define the customer brand.
