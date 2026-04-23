# Aditya's Portfolio

A modern, fast, and responsive portfolio website built with **Astro**, **Tailwind CSS**, and **Typed.js**. This project showcases software engineering expertise in Astro, React, Next.js, and Node.

## 🚀 Features

- **Blazing Fast Performance**: Built with Astro's zero-JS-by-default architecture.
- **Interactive UI**: Dynamic typing effects using Typed.js.
- **Responsive Design**: Fully responsive layout styled with Tailwind CSS.
- **SEO Optimized**: Pre-configured meta tags and SEO best practices.
- **Clean Code**: Modular components and clean directory structure.

## 🛠️ Tech Stack

- **Framework**: [Astro](https://astro.build/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Interactivity**: [Typed.js](https://mattboldt.github.io/typed.js/)
- **Icons/Layout**: Custom Astro components

## 📖 Astro: Pros & Cons

### Pros
- **Performance**: Astro ships zero JavaScript to the browser by default, resulting in incredibly fast load times.
- **Islands Architecture**: Hydrate only the interactive parts of your page, keeping the rest as static HTML.
- **Framework Agnostic**: You can use React, Vue, Svelte, or Solid components within the same project.
- **SEO Friendly**: Since content is server-rendered as static HTML, search engines can easily crawl it.
- **Developer Experience**: Simple, intuitive component syntax that feels like HTML/Markdown.

### Cons
- **Not for Complex SPAs**: Astro is optimized for content-driven sites. Highly stateful applications (like a dashboard) might be better suited for a traditional SPA framework.
- **SSR/Hydration Logic**: Managing when components hydrate can sometimes add complexity compared to a pure client-side app.
- **Ecosystem**: While growing rapidly, the plugin ecosystem is still smaller than established giants like React or Next.js.
- **Multi-Page Focus**: Astro is primarily a multi-page framework (MPA), which might require extra effort for smooth page transitions (though View Transitions are now supported).

## 🚦 Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AdityaChoubey22/ASTRO-FRAMEWORK-PORTFOLIO.git
   ```
2. Navigate to the project directory:
   ```bash
   cd astro-portfolio-main
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### Development

Start the local development server:
```bash
npm run dev
```
The application will be available at `http://localhost:3000/`.

### Build

To create a production build:
```bash
npm run build
```

## 📄 License

This project is licensed under the MIT License.
