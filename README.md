# @rccpr/ui

A library of components for React, Next.js, and Tailwind CSS.

## Installation

Add it with your preferred package manager.

### npm

```bash
npx jsr add @rccpr/ui
```

### bun (recommended)

```bash
bunx jsr add @rccpr/ui
```

### pnpm

```bash
pnpm dlx jsr add @rccpr/ui
```

### yarn

```bash
yarn dlx jsr add @rccpr/ui
```

## Usage

Add it to the transpiled packages in your `next.config.ts` file.

```ts
const nextConfig: NextConfig = {
  transpilePackages: ["@rccpr/ui"],
};
```

Then, you can use the components in your project.

```tsx
import { Button } from "@rccpr/ui";
```
