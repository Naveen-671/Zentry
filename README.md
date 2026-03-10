# Zentry 🎮

<div align="center">

**The Metagame, The Game of Games To Elevate Gaming Culture**

[![React](https://img.shields.io/badge/React-18.3.1-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-5.4.10-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-3.4.14-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![GSAP](https://img.shields.io/badge/GSAP-3.12.5-88CE02?style=for-the-badge&logo=greensock&logoColor=white)](https://greensock.com/gsap/)

[Live Demo](#) • [Documentation](#) • [Report Bug](https://github.com/Naveen-671/Zentry/issues) • [Request Feature](https://github.com/Naveen-671/Zentry/issues)

</div>

---

## 📖 About Zentry

Zentry is an innovative gaming platform that serves as a **metagame layer** for the gaming industry, uniting players from countless games and platforms into a single, interconnected shared adventure. We're building the world's largest **Play Economy** where gaming activities are rewarded and interconnected across digital and physical gaming experiences.

### 🎯 Vision

Transform gaming from isolated experiences into an interconnected ecosystem where:
- Players from all games and platforms can unite
- Gaming activities are recognized and rewarded universally
- Web3 and Web2 gaming experiences converge seamlessly
- Communities thrive in a gamified social environment

---

## ✨ Features

### 🌟 Core Products

- **🎮 Radiant** - Cross-platform metagame app that bridges Web2 and Web3 games
- **🖼️ Zigma** - Anime and gaming-inspired NFT collection
- **🌐 Nexus** - Gamified social hub for Web3 communities
- **🤖 Azul** - AI Agent enabling cross-world gameplay experiences

### 🎨 Website Features

- **Interactive Hero Section** - Dynamic video carousel with cinematic animations
- **Smooth Animations** - Powered by GSAP for fluid, professional motion design
- **3D Effects** - Interactive tilt effects and mouse-tracking animations
- **Responsive Design** - Optimized for all screen sizes and devices
- **Modern UI/UX** - Clean, gaming-inspired aesthetic with custom fonts and colors
- **Video Backgrounds** - Immersive multimedia experience throughout the site

---

## 🛠️ Tech Stack

### Frontend
- **[React](https://reactjs.org/)** (v18.3.1) - Modern UI library
- **[Vite](https://vitejs.dev/)** (v5.4.10) - Lightning-fast build tool
- **[Tailwind CSS](https://tailwindcss.com/)** (v3.4.14) - Utility-first CSS framework
- **[GSAP](https://greensock.com/gsap/)** (v3.12.5) - Professional-grade animation library

### Additional Libraries
- **[@gsap/react](https://www.npmjs.com/package/@gsap/react)** - React bindings for GSAP
- **[react-icons](https://react-icons.github.io/react-icons/)** - Icon library
- **[react-use](https://github.com/streamich/react-use)** - Collection of essential React hooks
- **[clsx](https://github.com/lukeed/clsx)** - Utility for constructing className strings

### Development Tools
- **ESLint** - Code linting and quality assurance
- **Prettier** - Code formatting
- **PostCSS** - CSS transformation and optimization
- **Autoprefixer** - Automatic CSS vendor prefixing

---

## 📁 Project Structure

```
Zentry/
├── src/
│   ├── components/
│   │   ├── About.jsx          # About section with animations
│   │   ├── AnimatedTitle.jsx  # Reusable animated text component
│   │   ├── Button.jsx         # Custom button with hover effects
│   │   ├── Contact.jsx        # Contact and CTA section
│   │   ├── Features.jsx       # Product showcase with bento grid
│   │   ├── Footer.jsx         # Footer with social links
│   │   ├── Hero.jsx           # Hero section with video carousel
│   │   ├── Navbar.jsx         # Navigation with scroll detection
│   │   ├── Story.jsx          # Narrative storytelling section
│   │   └── VideoPreview.jsx   # 3D video preview component
│   ├── App.jsx                # Main application component
│   ├── main.jsx               # React entry point
│   └── index.css              # Global styles and Tailwind config
├── public/
│   ├── img/                   # Images and logos (WebP format)
│   ├── videos/                # Video assets (MP4 format)
│   ├── audio/                 # Audio files
│   └── fonts/                 # Custom font files (WOFF2)
├── package.json               # Project dependencies
├── vite.config.js             # Vite configuration
├── tailwind.config.js         # Tailwind customization
├── postcss.config.js          # PostCSS configuration
├── eslint.config.js           # ESLint rules
└── index.html                 # HTML entry point
```

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** (v16 or higher)
- **npm** or **pnpm** package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Naveen-671/Zentry.git
   cd Zentry
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```
   or if you prefer pnpm:
   ```bash
   pnpm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```
   The application will be available at `http://localhost:5173`

### Build for Production

Create an optimized production build:

```bash
npm run build
```

The built files will be in the `dist/` directory.

### Preview Production Build

Preview the production build locally:

```bash
npm run preview
```

### Linting

Run ESLint to check code quality:

```bash
npm run lint
```

---

## 🎨 Customization

### Fonts
The project uses custom fonts defined in `src/index.css`:
- **Zentry** - Display font
- **General** - Body font
- **Circular Web** - Alternative sans-serif
- **Robert Medium/Regular** - Accent fonts

### Colors
Custom color palette defined in `tailwind.config.js`:
- **Blue variants** - Primary brand colors (50, 75, 100, 200, 300)
- **Violet** - Accent color for highlights
- **Yellow** - Call-to-action colors (100, 300)

### Animations
Powered by GSAP with ScrollTrigger for:
- Scroll-based animations
- 3D transforms and perspective effects
- Clip-path polygon animations
- Hover and interaction effects

---

## 📸 Screenshots

> *Add screenshots of your application here*

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. **Fork the repository**
2. **Create your feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Development Guidelines
- Follow the existing code style and conventions
- Write clean, readable, and maintainable code
- Test your changes thoroughly before submitting
- Update documentation as needed

---

## 📝 License

This project is private and proprietary. All rights reserved.

---

## 📧 Contact & Community

<div align="center">

[![Discord](https://img.shields.io/badge/Discord-Join_Us-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/zentry)
[![Twitter](https://img.shields.io/badge/Twitter-Follow-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/zentry)
[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/zentry)
[![Twitch](https://img.shields.io/badge/Twitch-Watch-9146FF?style=for-the-badge&logo=twitch&logoColor=white)](https://twitch.tv/zentry)

**GitHub:** [@Naveen-671](https://github.com/Naveen-671)

</div>

---

## 🙏 Acknowledgments

- [GSAP](https://greensock.com/) for providing industry-leading animation tools
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [React](https://reactjs.org/) team for the amazing UI library
- [Vite](https://vitejs.dev/) for blazing-fast development experience
- All contributors and community members who help improve Zentry

---

<div align="center">

**Built with ❤️ by the Zentry Team**

*Elevating Gaming Culture, One Game at a Time*

[⬆ Back to Top](#zentry-)

</div>
