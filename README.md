# TypeScript Minimum Config

This repo includes the minimum requirements for a TypeScript project.

1. typescript
2. node types
3. tsconfig

The default test using `node:test` is at `src/first.test.ts` and can be run using `npm test`

This project can also be initialized from scratch by following these steps:
- `npm init -y` to create package.json (-y to use all defaults)
- `npm install --save-dev typescript @types/node`
- `npx tsc --init`
