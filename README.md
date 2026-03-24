# Agents

A collection of AI agent definitions and configurations for technical workflows.

## Overview

This repository contains structured documentation and configuration for specialized AI agents. These agents are designed to assist in various stages of the software development lifecycle, from technical documentation to backend architecture design.

### Detected Stack
- **Language/Format**: Markdown with YAML Frontmatter
- **Frameworks**: None (Documentation-based)
- **Package Manager**: None

## Project Structure

```text
.
├── LICENSE             # MIT License file
├── README.md           # Project documentation
└── agents/             # Agent definition directory
    ├── PR2-D2.md       # Technical Documentation & PR specialist
    └── Sebas.md        # Backend Architect & .NET expert
```

## Agents

### [PR2-D2](agents/PR2-D2.md)
- **Role**: Technical Lead & PR Specialist ("The Pull Request Storyteller")
- **Specialization**: Analyzing diffs/commits, correlating code with user stories, and drafting structured Pull Requests.
- **Tools**: `Read`, `AskUserQuestion`, `Glob`, `Bash`, `Grep`.

### [Sebas](agents/Sebas.md)
- **Role**: Backend Architect ("The .NET & Backend Jedi Master")
- **Specialization**: Designing scalable APIs, SQL optimization, Azure infrastructure, and Specs Driven Development (SDD).
- **Tools**: `Write`, `Read`, `Bash`, `Grep`, `AskUserQuestion`, `Glob`, `WebSearch`.

## Setup & Usage

Since this is a collection of agent definitions:
1. **Requirements**: A compatible AI orchestration platform or an IDE with agent capabilities (e.g., Rider with specific plugins).
2. **Installation**: Clone this repository to your local machine.
3. **Usage**: Load the markdown files from the `agents/` directory into your agent host.

## Scripts

- **TODO**: No automated scripts detected. Add validation scripts for frontmatter consistency if needed.

## Environment Variables

- **TODO**: Currently, no environment variables are defined. Identify if specific API keys (e.g., OpenAI, Azure) are required for the agent hosts.

## Tests

- **TODO**: No automated tests found. Implement tests to verify agent prompt quality or frontmatter validity.

## License

This project is licensed under the [MIT License](LICENSE).
