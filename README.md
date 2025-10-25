# Mateusz Samborski - Portfolio

A modern, responsive portfolio website built with Astro, featuring a bilingual interface (English/Polish) and interactive animations.

## 🚀 Features

- **Bilingual Support** - Toggle between English and Polish
- **Responsive Design** - Works on all devices
- **Interactive Animations** - 3D hover effects, floating orbs, morphing shapes
- **Sideways Scrolling** - Unique showcase section with horizontal scroll
- **CV Download** - Modal with language-specific CV downloads
- **Modern Tech Stack** - Astro, TypeScript, Tailwind CSS

## 🛠️ Tech Stack

- **Framework**: Astro
- **Styling**: Tailwind CSS
- **Language**: TypeScript
- **Icons**: Lucide React
- **Animations**: CSS3 + JavaScript

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/M0dlyn/Portfolio.git
cd Portfolio
```

2. Install dependencies:
```bash
npm install
# or
pnpm install
```

3. Install Astro (if not already installed):
```bash
# Option 1: Install globally
npm install -g astro

# Option 2: Use npx (recommended - no global installation needed)
# npx will automatically download and use the latest Astro
```

4. Start the development server:
```bash
npx astro dev
# or if installed globally
astro dev
# or using npm scripts
npm run dev
# or
pnpm dev
```

5. Open [http://localhost:4321](http://localhost:4321) in your browser.

## 🏗️ Build

To build the project for production:

```bash
npx astro build
# or if installed globally
astro build
# or using npm scripts
npm run build
# or
pnpm build
```

## 📁 Project Structure

```
├── public/                 # Static assets
│   ├── Me.png            # Profile photo
│   ├── nCV.pdf           # English CV
│   └── PLnCV.pdf         # Polish CV
├── src/
│   ├── pages/
│   │   └── index.astro   # Main page
│   └── styles/
│       └── global.css    # Global styles
├── components/            # Reusable components
└── lib/                   # Utility functions
```

## 🌐 Deployment

The portfolio is designed to be deployed on any static hosting service:

- **Vercel** (recommended)
- **Netlify**
- **GitHub Pages**
- **Cloudflare Pages**

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

- **Email**: msamborski04@gmail.com
- **Website**: [msamborski.dev](https://msamborski.dev)
- **LinkedIn**: [Your LinkedIn Profile]

---

Built with ❤️ by Mateusz Samborski
