# AUTHORS.md (authors-md)

AUTHORS.md is a file format standard used in open-source and collaborative software projects to list the original creators, primary authors, and significant contributors of a project. Often required by open-source licenses such as GPL and Apache 2.0 to provide proper attribution, the AUTHORS.md file documents who wrote what portions of a codebase, their email addresses, and the scope of their contributions. Related standards include CONTRIBUTORS.md, All Contributors specification, and REUSE/SPDX contributor attribution frameworks.

**URL:** [https://raw.githubusercontent.com/api-evangelist/authors-md/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/authors-md/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Attribution, Documentation, Open Source, Repository, File Format, Contributor Management, License Compliance, Standard

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## APIs

### All Contributors API

The All Contributors specification provides a standardized way to recognize contributions to open-source projects beyond just code. It includes a bot API for automating contributor management, a configuration schema (.all-contributorsrc), and an emoji-based contribution type taxonomy. The bot responds to GitHub comments to add contributors to the project README.

**Human URL:** [https://allcontributors.org](https://allcontributors.org)

#### Tags:

 - Contributors, Attribution, Open Source, Bot, GitHub

#### Properties

- [Documentation](https://allcontributors.org/docs/en/overview)
- [GettingStarted](https://allcontributors.org/docs/en/bot/installation)
- [Specification](https://allcontributors.org/docs/en/specification)
- [GitHubRepository](https://github.com/all-contributors/all-contributors)
- [JSONSchema](https://raw.githubusercontent.com/api-evangelist/authors-md/refs/heads/main/json-schema/all-contributors-config-schema.json)

## Common Properties

- [GitHubOrganization](https://github.com/api-evangelist)
- [GitHubRepository](https://github.com/api-evangelist/authors-md)

## Features

| Name | Description |
|------|-------------|
| Author Attribution | Documents original creators and primary authors of a project, fulfilling attribution requirements for open-source licenses like GPL and Apache 2.0. |
| Contributor Types | Supports recognition of diverse contribution types beyond code including documentation, design, translation, testing, and community management. |
| Machine-Readable Format | The All Contributors .all-contributorsrc configuration file provides a machine-readable JSON format for managing contributor metadata programmatically. |
| Bot Automation | The All Contributors bot automates contributor recognition by responding to GitHub issue and pull request comments to update contributor tables. |
| License Compliance | Helps projects satisfy attribution requirements in open-source licenses including GPL, LGPL, Apache 2.0, and MPL that require author documentation. |

## Use Cases

| Name | Description |
|------|-------------|
| Open Source License Compliance | Satisfying attribution requirements in GPL, Apache, and other licenses that require listing authors and contributors in distributed software. |
| Project Governance | Documenting contributors for project governance purposes, recognition, and historical record-keeping of who built what portions of a codebase. |
| Contributor Onboarding | Helping new contributors understand the project's authorship history and providing a clear path for getting recognized for their contributions. |
| Copyright Documentation | Maintaining accurate copyright records for legal clarity around intellectual property ownership and contributor rights in collaborative projects. |
| Community Recognition | Publicly recognizing contributors in README files and project documentation to build community engagement and acknowledge diverse contributions. |

## Integrations

| Name | Description |
|------|-------------|
| GitHub | All Contributors bot integrates directly with GitHub repositories, responding to issue and pull request comments to manage contributor attribution. |
| REUSE / SPDX | The REUSE specification by FSFE provides structured SPDX-based attribution that complements AUTHORS.md files with machine-readable copyright headers. |
| GNU Coding Standards | GNU project guidelines specify conventions for AUTHORS files in free software projects, requiring attribution of significant code contributions. |
| CONTRIBUTING.md | AUTHORS.md files work alongside CONTRIBUTING.md files to document both past contributors and guidelines for future contributions. |
| CHANGELOG.md | AUTHORS.md attribution works in conjunction with CHANGELOG.md files to provide a complete history of a project's contributors and changes. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [All Contributors Config Schema](json-schema/all-contributors-config-schema.json)

### JSON Structure

- [All Contributors Config Structure](json-structure/all-contributors-config-structure.json)

### JSON-LD

- [AUTHORS.md Context](json-ld/authors-md-context.jsonld)

### Examples

- [All Contributors Config Example](examples/all-contributors-config-example.json)

## Vocabulary

- [AUTHORS.md Vocabulary](vocabulary/authors-md-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 6 actions, 1 workflow, and 3 personas across operational and capability dimensions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
