Document ID: KOS-README-001
Version: 1.0
Status: Active
Owner: Codex, Application Engineer
Approver: Caglar Varan
Last Updated: 2026-06-26
Purpose: Serve as the entry point for the Knight OS project.
Audience: Product, engineering, design, and future contributors.
Dependencies: PROJECT_CONTEXT.md, CURRENT_STATE.md
Related Documents: [Project Context](docs/philosophy/PROJECT_CONTEXT.md), [Current State](docs/philosophy/CURRENT_STATE.md), [Product Roadmap](docs/roadmap/Product-Roadmap.md)
Revision History: 2026-06-26 - README converted into project entry point.

# Knight OS

## Table of Contents

- [Overview](#overview)
- [Vision](#vision)
- [Philosophy](#philosophy)
- [Repository Structure](#repository-structure)
- [Documentation](#documentation)
- [Technology](#technology)
- [Development Process](#development-process)
- [Contributing](#contributing)
- [Roadmap](#roadmap)
- [Documentation Navigation](#documentation-navigation)

## Overview

Knight OS is a Personal Operating System for intentional living.

The current working application is Knight OS v13.0.0 - Daily Interaction
Release. The project is moving from passive data entry toward calm, touch-first
daily habit interaction.

## Vision

Knight OS helps people intentionally build the person they want to become
through small daily actions.

The objective is not engagement. The objective is transformation.

## Philosophy

Knight OS supports the user. It does not command the user.

The user is the Knight. Knight OS is a trusted companion.

## Repository Structure

```text
docs/
  handbook/
    Book-0-Founders-Letter/
    Book-I-Constitution/
    Book-II-Design-System/
    Book-III-Product-Strategy/
  philosophy/
  history/
  adr/
  roadmap/
  releases/
  templates/
mockups/
assets/
upload-to-github/
github-ready/
```

## Documentation

Documentation is a first-class project asset.

Official handbook reading order:

1. [Book 0 - The Founder's Letter](docs/handbook/Book-0-Founders-Letter/Founders-Letter.md)
2. [Book I - The Constitution](docs/handbook/Book-I-Constitution/Constitution.md)
3. [Book II - The Design System](docs/handbook/Book-II-Design-System/Design-System.md)
4. [Book III - Product Strategy](docs/handbook/Book-III-Product-Strategy/Product-Strategy.md)

ChatGPT, in the Chief Product Officer role, owns product philosophy and
handbook content. Codex is responsible for publishing, formatting, linking, and
maintaining documentation.

## Technology

- GitHub Pages
- Plain HTML
- Plain CSS
- Plain JavaScript
- localStorage
- Offline-first
- No frameworks
- No build tools
- No backend

The localStorage key is `knightTrackerData`.

## Development Process

Development follows this order:

1. Vision
2. Constitution
3. Design System
4. Product Strategy
5. Engineering
6. Implementation

Code never leads philosophy. Code implements philosophy.

## Contributing

Before changing the application, review:

- [Project Context](docs/philosophy/PROJECT_CONTEXT.md)
- [Current State](docs/philosophy/CURRENT_STATE.md)
- [ADR Library](docs/adr/ADR-000.md)

If implementation requires a product decision, stop and document the trade-offs
before coding.

## Roadmap

See [Product Roadmap](docs/roadmap/Product-Roadmap.md).

## Documentation Navigation

Start here:

1. [Book 0 - The Founder's Letter](docs/handbook/Book-0-Founders-Letter/Founders-Letter.md)
2. [Book I - The Constitution](docs/handbook/Book-I-Constitution/Constitution.md)
3. [Book II - The Design System](docs/handbook/Book-II-Design-System/Design-System.md)
4. [Book III - Product Strategy](docs/handbook/Book-III-Product-Strategy/Product-Strategy.md)
5. [Project Context](docs/philosophy/PROJECT_CONTEXT.md)
6. [Historical Records](docs/history/2026-06-26-Sprint-1.1/Historical-Record.md)
7. [Product Roadmap](docs/roadmap/Product-Roadmap.md)
8. [ADR Library](docs/adr/ADR-000.md)

Release notes:

- [V11](docs/releases/V11.md)
- [V12](docs/releases/V12.md)
- [V13](docs/releases/V13.md)
