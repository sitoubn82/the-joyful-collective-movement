# The Joyful Collective Movement

A modern business landing page built with Astro, Tailwind CSS, and TypeScript, featuring dark mode support.

## Features

- ⚡ **Astro** - Fast, modern static site generator
- 🎨 **Tailwind CSS** - Utility-first CSS framework
- 🌙 **Dark Mode** - Built-in dark mode toggle with localStorage persistence
- 📱 **Responsive** - Mobile-first responsive design
- 🔒 **TypeScript** - Type-safe development with strictest settings
- 🎯 **SEO Ready** - Optimized meta tags and semantic HTML

## Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── CTA.astro
│   │   ├── DarkModeToggle.astro
│   │   ├── Features.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   └── Hero.astro
│   ├── layouts/
│   │   └── BaseLayout.astro
│   ├── pages/
│   │   └── index.astro
│   └── env.d.ts
├── astro.config.mjs
├── tailwind.config.mjs
└── tsconfig.json
```

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Install dependencies:

```bash
npm install
```

2. Start the development server:

```bash
npm run dev
```

3. Open [http://localhost:4321](http://localhost:4321) in your browser.

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run astro` - Run Astro CLI commands

## Dark Mode

The site includes a fully functional dark mode toggle that:
- Saves user preference to localStorage
- Respects system color scheme preference
- Smoothly transitions between light and dark themes
- Uses Tailwind's `dark:` variant for styling

## Customization

### Colors

Modify the Tailwind config in `tailwind.config.mjs` to customize the color scheme.

### Content

- Edit `src/pages/index.astro` to modify the main page
- Update component files in `src/components/` to customize sections
- Modify `src/layouts/BaseLayout.astro` for global HTML structure

## Deployment

Build the site for production:

```bash
npm run build
```

The static files will be generated in the `dist/` directory, ready to deploy to any static hosting service.

## License

MIT