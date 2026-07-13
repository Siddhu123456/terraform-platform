# Documentation Framework

## Purpose

This document defines the documentation standards for the AI-Native Terraform Platform. It establishes a single documentation framework to ensure every document in the repository is consistent, maintainable, easy to navigate, and optimized for both human readers and AI-assisted development.

This framework applies to all documentation created within the repository unless a document explicitly defines an approved exception.

---

## Scope

This framework governs:

* Architecture documentation
* Engineering standards
* Knowledge base documentation
* Templates
* Module documentation
* Environment documentation
* Policies
* Runbooks
* Examples
* AI workspace documentation

It does not define implementation standards for Terraform modules. Those are defined in the Engineering Standards.

---

## Documentation Objectives

The documentation framework has the following objectives:

* Maintain consistency across the repository.
* Improve discoverability of information.
* Eliminate duplicated content.
* Support modular documentation.
* Enable AI-assisted content generation.
* Reduce maintenance effort.
* Support long-term scalability.

---

## Documentation Principles

All documentation shall follow these principles:

1. Documentation is the source of truth.
2. One document shall cover one primary concept.
3. Documentation shall be modular.
4. Documentation shall avoid duplication.
5. Documentation shall be version controlled.
6. Documentation shall be readable by humans and AI.
7. Documentation shall evolve through controlled changes.
8. Examples shall complement documentation, not replace it.

---

## Document Categories

The repository contains the following documentation categories.

| Category       | Purpose                                |
| -------------- | -------------------------------------- |
| Architecture   | Platform design and governance         |
| Standards      | Engineering standards and conventions  |
| Knowledge Base | AWS, Terraform, and platform knowledge |
| Templates      | Reusable implementation templates      |
| Modules        | Terraform module documentation         |
| Environments   | Environment-specific documentation     |
| Policies       | Governance and compliance              |
| Runbooks       | Operational procedures                 |
| Examples       | Reference implementations              |

---

## Standard Document Structure

Documents should use the following structure where applicable.

```text
Title

Purpose

Scope

Objectives

Content

References

Revision History
```

Sections that are not applicable may be omitted.

---

## File Naming Standard

Documentation files shall follow these rules.

* Use uppercase file names for numbered architecture documents.
* Use descriptive names.
* Separate words using underscores.
* Preserve numerical ordering where applicable.

Examples:

```text
00_DOCUMENTATION_FRAMEWORK.md
01_PLATFORM_VISION.md
02_PLATFORM_SCOPE.md
03_PLATFORM_PRINCIPLES.md
```

---

## Directory Organization

Documentation shall be organized by topic.

Example:

```text
knowledge/

aws/

vpc/

README.md
overview.md
terraform-resources.md
best-practices.md
examples.md
```

Large documents should be split into focused documents rather than expanded indefinitely.

---

## Documentation Size Standard

To maintain readability and AI efficiency, documentation shall follow these limits.

| Document Type  |     Preferred |   Maximum |
| -------------- | ------------: | --------: |
| README         | 100–300 lines | 500 lines |
| Architecture   | 200–500 lines | 700 lines |
| Standards      | 200–400 lines | 600 lines |
| Knowledge Base | 150–400 lines | 600 lines |
| Templates      |  50–200 lines | 300 lines |
| Runbooks       | 150–400 lines | 600 lines |

If a document approaches the maximum size, it shall be divided into smaller topic-focused documents.

---

## Writing Guidelines

Documentation should:

* Use clear and concise language.
* Define terminology before use.
* Keep one topic per section.
* Prefer lists and tables where appropriate.
* Use examples to clarify concepts.
* Avoid unnecessary repetition.
* Reference related documentation instead of duplicating information.

---

## Markdown Standards

Documentation shall use standard Markdown.

* One H1 heading per document.
* H2 headings for major sections.
* H3 headings for subsections.
* Fenced code blocks with language identifiers.
* Tables for structured information.
* Relative links for internal references.
* No embedded HTML unless required.

---

## Examples

Examples should:

* Be minimal.
* Be production-oriented.
* Match repository standards.
* Be independently understandable.
* Avoid unnecessary complexity.

---

## Cross References

Documents should reference related documents using relative paths.

Cross references should:

* Improve navigation.
* Avoid duplication.
* Point to authoritative sources.

---

## Documentation Lifecycle

Every document follows the same lifecycle.

```text
Draft

↓

Review

↓

Approval

↓

Implementation

↓

Maintenance

↓

Revision

↓

Archive (if superseded)
```

---

## Review Requirements

Before approval, each document shall be reviewed for:

* Accuracy
* Consistency
* Completeness
* Clarity
* Formatting
* Cross references
* Compliance with repository standards

---

## Compliance

All documentation within the repository shall comply with this framework.

Any deviation requires architectural approval before adoption.

---

## References

Related documents:

* README.md
* 01_PLATFORM_VISION.md
* 03_PLATFORM_PRINCIPLES.md
* 09_DOCUMENTATION_LIFECYCLE.md

---

## Revision History

| Version | Description                     |
| ------- | ------------------------------- |
| 1.0.0   | Initial documentation framework |
