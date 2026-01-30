# ai-error-handler

[![npm version](https://img.shields.io/npm/v/ai-error-handler.svg)](https://www.npmjs.com/package/ai-error-handler)
[![npm downloads](https://img.shields.io/npm/dm/ai-error-handler.svg)](https://www.npmjs.com/package/ai-error-handler)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-error-handler)](https://github.com/lxgic-studios/ai-error-handler/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Generate complete error handling middleware for any framework. Custom error classes, async wrappers, proper status codes, the works.

## Install

```bash
npm install -g ai-error-handler
```

## Usage

```bash
npx ai-error-handler express
# Generates Express error handling middleware

npx ai-error-handler fastify -l javascript
# JavaScript version for Fastify

npx ai-error-handler nextjs -o lib/errors.ts
# Save to file
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## Options

- `-l, --lang <language>` - typescript or javascript (default: typescript)
- `-o, --output <path>` - Save to file

## License

MIT
