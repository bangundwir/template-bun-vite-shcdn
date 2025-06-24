# Bun + Vite + React + shadcn/ui + TypeScript Template

This is a modern React template that combines:
- ⚡ **Bun** - Fast JavaScript runtime and package manager
- ⚡ **Vite** - Lightning fast build tool
- ⛛ **React 19** - Latest React with TypeScript
- 🎨 **shadcn/ui** - Beautiful and accessible UI components
- 🎨 **Tailwind CSS v4** - Utility-first CSS framework

## Quick Start

1. **Create a new project:**
   ```bash
   bun create vite@latest my-project --template react-ts
   cd my-project
   ```

2. **Install dependencies:**
   ```bash
   bun install
   ```

3. **Add Tailwind CSS:**
   ```bash
   bun add tailwindcss @tailwindcss/vite
   bun add -D @types/node
   ```

4. **Initialize shadcn/ui:**
   ```bash
   bunx --bun shadcn@latest init
   ```

5. **Add components:**
   ```bash
   bunx --bun shadcn@latest add button
   ```

6. **Start development server:**
   ```bash
   bun run dev
   ```

## Project Structure

```
src/
├── components/          # React components
│   └── ui/             # shadcn/ui components
├── lib/                # Utility functions
├── App.tsx             # Main app component
├── index.css           # Global styles (Tailwind)
└── main.tsx            # App entry point
```

## Configuration Files

- `tsconfig.json` & `tsconfig.app.json` - TypeScript configuration with path aliases
- `vite.config.ts` - Vite configuration with Tailwind plugin and path resolution
- `components.json` - shadcn/ui configuration
- `package.json` - Dependencies and scripts

## Available Scripts

- `bun run dev` - Start development server
- `bun run build` - Build for production
- `bun run preview` - Preview production build
- `bun run lint` - Run ESLint

## Adding More Components

Add any shadcn/ui component:
```bash
bunx --bun shadcn@latest add [component-name]
```

Available components: button, input, dialog, card, table, form, and many more.

## Path Aliases

Import from `src/` using the `@/` alias:
```typescript
import { Button } from "@/components/ui/button"
import { utils } from "@/lib/utils"
```

## Technologies Used

- [Bun](https://bun.sh/) - JavaScript runtime & package manager
- [Vite](https://vitejs.dev/) - Build tool
- [React](https://react.dev/) - UI library
- [TypeScript](https://www.typescriptlang.org/) - Type safety
- [Tailwind CSS](https://tailwindcss.com/) - Styling
- [shadcn/ui](https://ui.shadcn.com/) - Component library
- [Radix UI](https://www.radix-ui.com/) - Headless UI primitives
# template-bun-vite-shcdn
