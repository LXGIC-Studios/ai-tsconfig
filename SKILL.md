---
name: tsconfig-gen
description: Generate optimal tsconfig.json for your project type. Use when setting up TypeScript.
---

# TSConfig Generator

tsconfig.json has a million options. This generates the right config for your project type.

**One command. Zero config. Just works.**

## Quick Start

```bash
npx ai-tsconfig next
```

## What It Does

- Generates optimized tsconfig.json
- Supports Next.js, Node.js, React, libraries
- Sets proper compiler options
- Includes path aliases

## Usage Examples

```bash
# Next.js project
npx ai-tsconfig next

# Node.js backend
npx ai-tsconfig node

# React app
npx ai-tsconfig react

# Library package
npx ai-tsconfig library
```

## Best Practices

- **Enable strict mode** - catch more errors
- **Use path aliases** - cleaner imports
- **Match your runtime** - target the right ES version
- **Exclude properly** - don't type-check node_modules

## When to Use This

- Starting new TypeScript project
- Upgrading TypeScript version
- Not sure what options to use
- Learning tsconfig patterns

## Part of the LXGIC Dev Toolkit

This is one of 110+ free developer tools built by LXGIC Studios. No paywalls, no sign-ups, no API keys on free tiers. Just tools that work.

**Find more:**
- GitHub: https://github.com/LXGIC-Studios
- Twitter: https://x.com/lxgicstudios
- Substack: https://lxgicstudios.substack.com
- Website: https://lxgicstudios.com

## Requirements

No install needed. Just run with npx. Node.js 18+ recommended. Needs OPENAI_API_KEY environment variable.

```bash
npx ai-tsconfig --help
```

## How It Works

Takes your project type and generates a tsconfig.json with optimal settings for that environment. Knows the right module, target, and library settings for each type.

## License

MIT. Free forever. Use it however you want.
