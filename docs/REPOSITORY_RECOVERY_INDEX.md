# ForMySumchins — GitHub source reconciliation index

**Inventory date:** 2026-10-26
**Coverage:** 9 repositories visible to the linked ForMySumchins GitHub installation. Other local/cloud projects or GitHub installations are not audited by this file.
**Purpose:** distinguish code verifiably in GitHub from plans, external archives, and uncommitted sessions. This file is a recovery register, not a claim that all implementations have been restored.

## Verified repository snapshots

| Repository | Checked base | Source observed | Recovery priority and next action |
|---|---|---|---|
| [BzzyAnts](https://github.com/ForMySumchins/BzzyAnts) | `main`; `develop` inspected | README-only on main/develop; governance configuration on `chore/kiro-governance` | **P0.** Retrieve the standalone Ants HTML and A02 production assets from Drive, locate any Codex Cloud React worktree, then submit a separate real implementation PR. Do not invent missing source. |
| [democracy-bot](https://github.com/ForMySumchins/democracy-bot) | `main`, `dumbass-bot` | README-only on main; Node src/test/package.json on `dumbass-bot` | **P0.** Preserve and test the real source branch; document whether and how it should be promoted to canonical development branch. No blind merge. |
| [BzzyBees](https://github.com/ForMySumchins/BzzyBees) | `Main`, `Staging` and default `jules-11031760528795552868-147185b2` | React/Vite source and lockfile on examined code branches | **P1.** Compare divergent branches and establish stable canonical branch; verify website and CallShield features against actual code. Avoid assuming default branch indicates release quality. |
| [P0rniBot](https://github.com/ForMySumchins/P0rniBot) | `main` and `characters/initial-roster` | Multiple docs, HTML, subdirectories, and engine/roster work on secondary branch | **P1.** Compare code and assets before consolidation; preserve historical work and licensing/security controls. |
| [SacredFool](https://github.com/ForMySumchins/SacredFool) | `main`, `jules` | Placeholder README; blocked Jules branch exists | **P1.** Locate actual Discord game code and 9/12-part schema source; record provenance and restore only verified files. |
| [Bzzy](https://github.com/ForMySumchins/Bzzy) | `main`, `BzzyButterfly` and `human/shared-crm-schema` sampled | Placeholder README; named component/CRM branches not shown to hold implementation | **P1.** Treat umbrella and service component plans as design/spec until code is found. Establish verified central source map. |
| [BzzySolutions](https://github.com/ForMySumchins/BzzySolutions) | `Bzzy`, `bzzy-forge`, `bzzy-scout` sampled | Placeholder README on sampled branches | **P1.** Recover service fulfillment implementations and approved package specifications, if any, from source workspaces. |
| [bzzy-grok](https://github.com/ForMySumchins/bzzy-grok) | `main` | Placeholder README only | **P2.** Export actual Grok/SAMA source from its workspace before marking bots committed; never transfer secrets. |
| [DiscordBot](https://github.com/ForMySumchins/DiscordBot) | `main` | Placeholder README only | **P2.** Establish relationship to democracy-bot and actual Discord source, avoid duplicate rebuilds. |

These findings concern **checked branches and roots**, not exhaustive proof that no source exists in other branches, other repositories, or external computers.

## Current Ants source and asset coordinates

- Standalone clickable **HTML** prototype: https://drive.google.com/file/d/1pAr_EF2SCc3Js-qwsPeyOh5hFgCqLLHS/view
- Prototype folder: https://drive.google.com/drive/folders/1zFhDrgsQswM_mqLMOCXghKGzqnzwfe-z
- **A02 Living Desert 17-second media pack:** https://drive.google.com/drive/folders/1-467ua8Uz4P0vmMnzOujRqMF5iCW8BFS
- Ants master production library: https://drive.google.com/drive/folders/18Ueg_FDLlVyB8vaLRio9S65hkuLYSP8t
- Canonical product identity: Ants is **employment-first field-sales enablement**. Mapping and lead inference support workers, not replace that identity.

Media and HTML on Drive do **not** constitute committed React application source in GitHub. A past Codex answer with JSX/Tailwind snippets is not proof of committed work.

## Standard recovery protocol

1. Have every task owner return repo, checkout/worktree path, source branch, git status, commit SHA, PR link and test outputs (or explicitly say **UNCOMMITTED**).
2. Inventory previously finished code from authorized Codex Cloud tasks, Jules/Grok worktrees, local machines and Drive artifacts. Do not speculate about inaccessible files.
3. Copy only recovered, verified and rights-cleared files into a project-specific feature branch; document origin. Preserve existing branches and history.
4. Run actual build/test commands and inspect diffs; label unavailable checks. Open targeted PRs, request review, and merge only with explicit owner approval.
5. Consider GitHub branch protections, required CI and PR templates after recovery; a root `AGENTS.md` improves agent behavior but cannot force an external system to push.

## Non-goals

These administrative documentation PRs do not deploy a website, repair missing code, reclassify branches, or authorize spending, customer outreach, cross-repo migrations, or public launch. Each repository's root `AGENTS.md` spells out the evidence contract.
