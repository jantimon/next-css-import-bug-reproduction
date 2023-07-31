# Bug Reproduction

## Startup

```bash
npm install
npm run dev
```

```bash
pnpm install
pnpm run dev
```

```bash
yarn install
yarn run dev
```

## Reproduction

1. Open http://localhost:3000/use-client in your browser.
2. You will see a **red** text saying "Demo".
3. Open http://localhost:3000/rsc in your browser.
4. You will see a text saying "Demo" - however it is black.
5. Both texts will have the very same css class names.

## Expected behavior

The text should be red in both cases.