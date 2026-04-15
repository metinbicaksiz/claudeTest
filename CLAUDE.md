# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview
*The repository currently contains no source files, README, or other documentation. The following sections serve as a template to be filled in as the codebase evolves.*

## Common Development Commands
- **Build**: *(Insert build command once a build system is introduced, e.g., `npm run build` or `make`.)*
- **Lint**: *(Insert lint command, e.g., `npm run lint` or `flake8 .`.)*
- **Run Tests**: *(Insert test runner command, e.g., `npm test`, `pytest`, or `go test ./...`.)*
- **Run a Single Test**: *(Specify how to target an individual test, such as `npm test -- -t "MyTest"` or `pytest tests/test_example.py::test_specific`.)*

## High‑Level Architecture (to be completed)
- **Entry Point**: *(Describe the main executable or server entry, e.g., `src/main.ts` or `cmd/app/main.go`.)*
- **Core Modules**: *(List major packages or directories and their responsibilities.)*
- **Data Layer**: *(Explain how data persistence is handled – databases, ORMs, file storage.)*
- **API Layer**: *(Outline any REST/GraphQL/websocket interfaces.)*
- **Frontend**: *(If applicable, describe UI framework and entry point.)*
- **Testing Strategy**: *(Unit, integration, e2e tests and their locations.)*

*These placeholders should be updated as the codebase grows to reflect the actual structure and responsibilities of each component.*

## Project‑Specific Rules & Guidelines
- **Cursor Rules**: If a `.cursor/rules/` directory or `.cursorrules` file appears, incorporate any specific style or automation rules defined there.
- **Copilot Instructions**: If a `.github/copilot-instructions.md` file is added, summarize key guidance for AI‑generated code.
- **README Highlights**: When a `README.md` is added, extract essential information such as project purpose, setup steps, and contribution guidelines.

## Updating CLAUDE.md
Whenever new top‑level documentation, build scripts, or architectural components are added, revisit this file to:
1. Fill in concrete command examples.
2. Document the actual architecture and module responsibilities.
3. Summarize any newly introduced Cursor or Copilot rules.
4. Reference important sections from the `README.md`.
