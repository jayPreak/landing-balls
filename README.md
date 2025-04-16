# Landing Balls - Interactive Portfolio Website

A modern, interactive portfolio website featuring a dynamic background with animated balls and connections. Built with React, TypeScript, and D3.js.

![Screenshot of the landing page](screenshot.png)

## Features

- 🎨 Interactive background with animated balls and dynamic connections
- 🚀 Modern, responsive design
- ⚡ Built with Vite for fast development and optimized production builds
- 🎯 TypeScript for type safety
- 💅 Tailwind CSS for styling
- 📱 Fully responsive layout

## Tech Stack

- React 18
- TypeScript
- D3.js for animations
- Tailwind CSS
- Vite
- Lucide React for icons

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or pnpm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/landing-balls.git
cd landing-balls
```

2. Install dependencies:
```bash
npm install
# or
pnpm install
```

3. Start the development server:
```bash
npm run dev
# or
pnpm dev
```

4. Open your browser and navigate to `http://localhost:5173`

## Project Structure

```
landing-balls/
├── src/
│   ├── App.tsx          # Main application component
│   ├── main.tsx         # Application entry point
│   └── index.css        # Global styles
├── public/              # Static assets
├── package.json         # Project dependencies
├── tsconfig.json        # TypeScript configuration
└── vite.config.ts       # Vite configuration
```

## Customization

### Changing Colors

The background gradient and ball colors can be modified in the `InteractiveBackground` component in `src/App.tsx`.

### Adding Social Links

Update the social media links in the navigation section of `App.tsx`:

```tsx
<div className="flex space-x-6">
  <a href="YOUR_TWITTER_URL" className="hover:text-gray-300"><Twitter className="w-6 h-6" /></a>
  <a href="YOUR_LINKEDIN_URL" className="hover:text-gray-300"><Linkedin className="w-6 h-6" /></a>
  <a href="YOUR_GITHUB_URL" className="hover:text-gray-300"><Github className="w-6 h-6" /></a>
</div>
```

## Building for Production

To create a production build:

```bash
npm run build
# or
pnpm build
```

The build files will be generated in the `dist` directory.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [D3.js](https://d3js.org/) for the interactive visualizations
- [Lucide React](https://lucide.dev/) for the beautiful icons
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework 