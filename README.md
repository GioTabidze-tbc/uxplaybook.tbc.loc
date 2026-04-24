# UX Playbooks for TBC Prodcut teams

Non‑financial, non‑regulated internal product playbook system for maintaining user experience standards and design, code, and writing guidelines used by all TBC agile product teams.

## POC Result
PoC Result

Installed the Docus project locally without issues.
Replaced the default landing page with a custom version.
Added three documentation components using ready-made Docus components.
Each component renders correctly and follows the existing documentation patterns.
Setup confirms fast bootstrap, easy theming, and low effort for adding structured docs.

## ✨ Features

- 🎨 **Clear Design** - Clean, modern documentation theme
- 📱 **Responsive** - Mobile-first responsive design  
- 🌙 **Dark Mode** - Built-in dark/light mode support
- 🔍 **Search** - Full-text search functionality
- 📝 **Markdown Enhanced** - Extended markdown with custom components
- 🎨 **Customizable** - Easy theming and brand customization
- ⚡ **Fast** - Optimized for performance with Nuxt 4
- 🔧 **TypeScript** - Full TypeScript support

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

Your documentation site will be running at `http://localhost:3000`

## 📁 Project Structure

```
my-docs/
├── content/              # Your markdown content
│   ├── index.md         # Homepage
│   ├── 1.getting-started/  # Getting started section
│   └── 2.essentials/    # Essential documentation
├── public/              # Static assets
└── package.json         # Dependencies and scripts
```

## ⚡ Built with

This starter comes pre-configured with:

- [Nuxt 4](https://nuxt.com) - The web framework
- [Nuxt Content](https://content.nuxt.com/) - File-based CMS
- [Nuxt UI](https://ui.nuxt.com) - UI components
- [Nuxt Image](https://image.nuxt.com/) - Optimized images
- [Tailwind CSS 4](https://tailwindcss.com/) - Utility-first CSS
- [Docus Layer](https://www.npmjs.com/package/docus) - Documentation theme

## 📖 Documentation

For detailed documentation on customizing your Docus project, visit the [Docus Documentation](https://docus.dev)

### 🤖 AI Assistant Skill

Get started quickly with Docus by adding specialized knowledge to your AI assistant (Cursor, Claude, etc.):

```bash
npx skills add nuxt-content/docus
```

This skill helps you create documentation faster by providing your AI assistant with best practices, MDC component usage, ready-to-use templates, writing guidelines, and configuration tips for Docus. Perfect for quickly scaffolding new documentation projects.

## 🚀 Deployment

Build for production:

```bash
npm run build
```

The built files will be in the `.output` directory, ready for deployment to any hosting provider that supports Node.js.

## 📄 License

[MIT License](https://opensource.org/licenses/MIT) 
