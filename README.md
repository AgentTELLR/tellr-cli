# TELLR CLI

TELLR CLI is a developer toolkit for building hybrid Web 4.0 agents with optional trading modules, memory, observability, and secure API-first execution.

The CLI provides a complete workflow for developers to authenticate, create agent workspaces, run agents locally, and deploy them to production environments.

## Overview

TELLR is designed for the next generation of intelligent agent infrastructure.

Instead of treating AI as simple chat interfaces, TELLR provides a runtime system for building modular agent architectures.

Core capabilities include:

- Web 4.0 agent architecture
- Tool-based modular systems
- Persistent memory support
- Local development workflow
- Production deployment pipeline
- Secure API-first execution
- Observability-ready infrastructure

## Installation

Install the CLI globally:

```bash
npm install -g @tellr/cli
```

For local development in this repository:

```bash
npm install
npm link
```

Verify installation:

```bash
tellr --help
```

## Authentication

```bash
tellr login
```

Authenticates your local environment with the TELLR platform.

## Create an Agent Workspace

```bash
tellr agent init
```

Creates a new Web4 agent workspace with a starter template.

## Local Development

```bash
tellr agent dev
```

Starts a local development runtime where your agent can:

- execute tools
- access memory
- simulate production behavior
- support debugging and testing

## Deployment

```bash
tellr deploy
```

Deploys your agent and prints a simulated endpoint and API key placeholder.

## Example Workflow

```bash
npm install -g @tellr/cli

tellr login

tellr agent init

tellr agent dev

tellr deploy
```

## Project Structure

```text
tellr-cli/
├─ bin/
├─ src/
│  ├─ commands/
│  ├─ core/
│  └─ utils/
├─ templates/
│  └─ starter-agent/
├─ .env.example
├─ .gitignore
├─ LICENSE
├─ package.json
└─ README.md
```

## Scripts

```bash
npm start
```

## Use Cases

TELLR can be used to build:

- AI assistants
- Autonomous workflow agents
- Trading copilots
- Web4 native applications
- Automation systems
- Research agents
- API-based AI services

## Security

Sensitive credentials should always be stored using environment variables.

Recommended practices:

- use `.env` files
- separate development and production environments
- rotate API keys regularly
- restrict tool permissions

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Submit a pull request

## License

MIT License

## Links

- Website: https://tellr.xyz

## Tagline

Build hybrid Web 4.0 agents with tools, memory, observability, and secure deployment.
