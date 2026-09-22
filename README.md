<div align="center">

# Nexa Web Report

**Academic report and evidence repository for the Nexa Web course.**

![Markdown](https://img.shields.io/badge/Markdown-Docs%20as%20Code-000000?style=flat-square&logo=markdown&logoColor=white) ![Git](https://img.shields.io/badge/Git-versioned%20evidence-F05032?style=flat-square&logo=git&logoColor=white) ![Status](https://img.shields.io/badge/status-structured%20baseline-64748B?style=flat-square)

[Report](./report) · [Documentation](./docs) · [Release notes](./docs/releases/) · [Scripts](./scripts)

</div>

---

## Project Entry Flow

The report follows the Web course outline while keeping academic evidence
separate from Nexa Product authority:

1. Accepted Product, Domain, Architecture and Design decisions provide the
   semantic boundary for Nexa claims.
2. `report/` contains the chapter structure, source prose and versioned
   evidence locations for the course report.
3. `docs/` contains repository guidance and release notes.
4. Git and GitHub preserve the history used to review report changes.

## Overview

This repository supports course `1ASI0730 Aplicaciones Web` through a
Markdown-based Docs-as-Code report. The current baseline has an organized
chapter tree, front matter, reserved evidence directories, repository
guidance and a whitespace-validation workflow. Most chapter files are still
section skeletons; the repository does not claim a completed academic report,
implemented Web Product or deployment evidence.

## Report Maturity and Evidence Boundary

- The report outline is versioned and grouped by the course chapters.
- Section files identify the places where authored academic narrative and
  evidence will be maintained.
- `report/assets/` reserves versioned locations for diagrams, images and
  annex evidence; it does not imply that an asset exists.
- The repository documents academic evidence only. It does not redefine the
  accepted Nexa Product, Domain or Architecture model.
- A completed section, runtime implementation, validation result or academic
  acceptance is stated only when its source is present and verifiable.

## Nexa Product Ecosystem

<table>
<tr>
<td width="50%" valign="top">

### [Nexa Mobile Report](https://github.com/nexa-suite/mobile-report)

Academic report and delivery evidence for Nexa Mobile.

![Markdown](https://img.shields.io/badge/Markdown-academic%20evidence-000000?style=flat-square&logo=markdown&logoColor=white)

</td>
<td width="50%" valign="top">

### [Nexa Mobile](https://github.com/nexa-suite/mobile)

Mobile client repository: partial unmerged Operations Android/Kotlin/Jetpack
Compose evidence; Buyer Mobile remains an accepted Flutter/Dart target.

![Operations Android](https://img.shields.io/badge/Operations%20Mobile-partial%20evidence-3DDC84?style=flat-square&logo=android&logoColor=white) ![Buyer target](https://img.shields.io/badge/Buyer%20Mobile-TARGET%20Flutter%2FDart-64748B?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Nexa API](https://github.com/nexa-suite/api)

Authoritative business and integration backbone for Nexa Suite.

![Java](https://img.shields.io/badge/Java-25-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-4.1-6DB33F?style=flat-square&logo=springboot&logoColor=white)

</td>
<td width="50%" valign="top">

### [Nexa Website](https://github.com/nexa-suite/website)

Public product experience and acquisition entry point.

![HTML5](https://img.shields.io/badge/HTML5-static-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-responsive-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Nexa Buyer Portal](https://github.com/nexa-suite/portal)

Buyer-facing Web experience for B2B purchasing and delivery visibility.

![Angular](https://img.shields.io/badge/Angular-22-DD0031?style=flat-square&logo=angular&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178C6?style=flat-square&logo=typescript&logoColor=white)

</td>
<td width="50%" valign="top">

### [Nexa Platform](https://github.com/nexa-suite/platform)

Internal operational Web workspace for tenant teams.

![Angular](https://img.shields.io/badge/Angular-22-DD0031?style=flat-square&logo=angular&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178C6?style=flat-square&logo=typescript&logoColor=white)

</td>
</tr>
</table>

## Report Structure

```text
report/
├── 00-front-matter/
├── 01-introduction/
├── 02-requirements-elicitation-and-analysis/
├── 03-requirements-specification/
├── 04-product-design/
├── 05-product-implementation-validation-deployment/
├── 90-conclusions/
├── 91-video-about-the-team/
├── 92-bibliography/
├── 93-annexes/
└── assets/
docs/
scripts/
README.md
```

## Tools Stack

| Concern | Current repository use |
| --- | --- |
| Source format | GitHub-Flavored Markdown |
| Evidence organization | Numbered chapters and versioned asset directories |
| Validation | `git diff --check` in the current workflow |
| Source control | Git, GitHub and Conventional Commits |
| Export | Not currently provided by this repository |

The Markdown lint configuration is versioned for future use, but the current
workflow does not claim a Markdown-lint or PDF-export gate.

## Getting Started

```bash
git clone https://github.com/nexa-suite/web-report.git
cd web-report
git diff --check
```

Read [`docs/README.md`](./docs/README.md), [`report/README.md`](./report/README.md)
and the relevant chapter source before adding academic content. Keep evidence
and assets relative to the repository so the report remains portable.

## Validation

The deterministic repository check currently available is:

```bash
git diff --check
```

The same check is executed by
[`markdown-validation.yml`](./.github/workflows/markdown-validation.yml).
There is no committed PDF-export script in the current repository.

## Ownership & Boundaries

- Web Report owns its academic narrative, chapter organization and report
  evidence locations.
- Nexa Blueprint remains the canonical Product, Domain and Architecture
  decision source.
- Application repositories provide implementation evidence only when a report
  section cites a verifiable source.
- A report outline or design section is not, by itself, Product Acceptance,
  System Acceptance, deployment proof or production readiness.

## Documentation

- [Repository documentation](./docs/README.md)
- [Report structure](./report/README.md)
- [Report assets index](./report/assets/asset-index.md)
- [Release notes](./docs/releases/)
- [Changelog](./CHANGELOG.md)

## Nexa Engineering & Documentation

<table>
<tr>
<td width="50%" valign="top">

### [Nexa Blueprint](https://github.com/nexa-suite/blueprint)

Canonical Product, Domain, Architecture, data, security and accepted
engineering decision source.

![Markdown](https://img.shields.io/badge/Markdown-canonical%20documentation-000000?style=flat-square&logo=markdown&logoColor=white)

</td>
<td width="50%" valign="top">

### [Nexa Web Report](https://github.com/nexa-suite/web-report)

This repository: academic Web report structure and evidence.

![Docs as Code](https://img.shields.io/badge/Docs%20as%20Code-current-64748B?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Nexa Complementary](https://github.com/nexa-suite/complementary)

Supporting references, reproducible engineering resources and shared tooling.

![Support tooling](https://img.shields.io/badge/Support%20tooling-reference-64748B?style=flat-square)

</td>
<td width="50%" valign="top">

### [Nexa Design Lab](https://github.com/nexa-suite/design-lab)

UX/UI, interaction, design-system, prototype and current design-evidence
workspace.

![Angular](https://img.shields.io/badge/Angular-22-DD0031?style=flat-square&logo=angular&logoColor=white)

</td>
</tr>
</table>

## Legal

Copyright © 2026 Nexa. All rights reserved. No open-source license is claimed
by this README.

<div align="center"><br />Nexa · Evidence first, documentation with clear boundaries</div>
