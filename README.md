# create-tailwindvite-react <a href="https://npmjs.com/package/create-tailwindvite-react"><img src="https://img.shields.io/npm/v/create-tailwindvite-react" alt="npm package"></a>

Scaffold a new React project with Tailwind CSS and Vite - A modern, fast, and lightweight template for building React applications.

## 🚀 Quick Start

### Using npm
```bash
npm create tailwindvite-react my-app
cd my-app
npm install
npm run dev
```

### Using yarn
```bash
yarn create tailwindvite-react my-app
cd my-app
yarn install
yarn dev
```

### Using pnpm
```bash
pnpm create tailwindvite-react my-app
cd my-app
pnpm install
pnpm dev
```

### Using npx
```bash
npx create-tailwindvite-react my-app
cd my-app
npm install
npm run dev
```



## 🎨 Customization

### Tailwind CSS Configuration

The template uses Tailwind CSS v4 with the new CSS-first configuration. You can customize your design system by editing the CSS variables in `src/index.css`:

```css
@import "tailwindcss";

@theme {
  --color-primary: #3b82f6;
  --color-secondary: #64748b;
  /* Add your custom theme variables */
}
```

