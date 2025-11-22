# eigenstudio - Web & App Development Studio

[![Next.js](https://img.shields.io/badge/Next.js-15.4.2-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.1.1-blue?style=flat-square&logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.0-blue?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)

**eigenstudio** is a modern web application development studio specializing in creating cutting-edge websites, web applications, and mobile apps. Built with Next.js 15 and React 19, it showcases our portfolio of projects while demonstrating modern web development practices.

## 🚀 Features

### Core Functionality
- **Portfolio Showcase**: Dynamic project display with detailed case studies
- **Interactive 3D Elements**: Three.js integration for immersive experiences
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Dark/Light Theme**: Theme switching with system preference detection
- **Smooth Animations**: Framer Motion and GSAP for fluid interactions
- **Contact Integration**: Resend-powered contact form system

### Technical Features
- **App Router**: Next.js 15 App Router for modern routing
- **TypeScript**: Full type safety across the application
- **Performance**: Optimized with Turbopack for development
- **Accessibility**: ARIA-compliant components with Radix UI
- **SEO**: Metadata optimization and structured content

## 🛠️ Tech Stack

### Frontend Framework
- **Next.js 15.4.2** - React framework with App Router
- **React 19.1.1** - Latest React with concurrent features
- **TypeScript 5.0** - Type-safe development

### Styling & UI
- **Tailwind CSS 4.0** - Utility-first CSS framework
- **Radix UI** - Accessible component primitives
- **Framer Motion** - Animation library
- **GSAP** - Advanced animations and effects

### 3D & Graphics
- **Three.js** - 3D graphics library
- **React Three Fiber** - React renderer for Three.js
- **React Three Drei** - Useful helpers for React Three Fiber

### Development Tools
- **ESLint** - Code linting and formatting
- **PostCSS** - CSS processing
- **Turbopack** - Fast bundler for development

## 📁 Project Structure

```
eigenstudio/
├── app/                          # Next.js App Router
│   ├── (projects)/              # Dynamic project routes
│   ├── contact/                 # Contact page
│   ├── studio/                  # Studio showcase
│   ├── globals.css              # Global styles
│   ├── layout.tsx               # Root layout
│   └── page.tsx                 # Home page
├── components/                   # React components
│   ├── ui/                      # Reusable UI components
│   ├── home/                    # Home page components
│   ├── studio/                  # Studio page components
│   ├── contact/                 # Contact components
│   ├── magicui/                 # Special UI effects
│   └── [various components]     # Feature components
├── context/                     # React context providers
│   ├── loading-context.tsx      # Loading state management
│   └── smooth-scroll-provider.tsx # Smooth scrolling
├── data/                        # Static data files
│   ├── projects.json            # Project portfolio data
│   └── studio-gallery.json      # Studio gallery data
├── lib/                         # Utility functions
│   └── utils.ts                 # Common utilities
├── public/                      # Static assets
│   └── assets/                  # Images, videos, SVGs
└── types/                       # TypeScript type definitions
```

## 🎯 Portfolio Projects

### Featured Projects

#### 1. **eigenplus** - Engineering Education Platform
- **Type**: Website
- **Tech**: Next.js, 3D Models, Interactive Widgets
- **Description**: Complete website redesign for engineering education platform with 3D visualizations

#### 2. **eigenplus YouTube** - Content Strategy
- **Type**: Design & Content
- **Achievement**: Scaled from 300 to 100K+ subscribers in 3 months
- **Features**: Animated explainers, custom visual language

#### 3. **App Development** - Mobile Applications
- **Type**: Mobile App Collection
- **Downloads**: 500,000+ with 1,000+ five-star reviews
- **Apps**: Engineering calculators, Mohr's Circle visualizers

#### 4. **Solemate** - Smart Insole App
- **Type**: Web & Mobile App
- **Tech**: Real-time sensor data, 3D pressure mapping
- **Partner**: Samakalan Labs

#### 5. **Avkalan Labs** - Computational Engineering
- **Type**: Website
- **Tech**: AI-driven simulations, advanced material modeling
- **Focus**: High-performance computational engineering

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm, yarn, pnpm, or bun

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yogesh-avkalan/eigenstudio.git
   cd eigenstudio
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   # or
   bun install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Available Scripts

- `npm run dev` - Start development server with Turbopack
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 🎨 Customization

### Adding New Projects
1. Add project data to `data/projects.json`
2. Create corresponding route in `app/(projects)/[project]/`
3. Add project images to `public/assets/`

### Theme Customization
- Modify `components/theme-provider.tsx` for theme logic
- Update `tailwind.config.js` for color schemes
- Customize `app/globals.css` for global styles

### Component Development
- Use `components/ui/` for reusable components
- Follow the established component patterns
- Implement proper TypeScript interfaces

## 🔧 Development Features

### Performance Optimizations
- **Turbopack**: Fast development bundling
- **Image Optimization**: Next.js automatic image optimization
- **Font Optimization**: Google Fonts with `next/font`
- **Code Splitting**: Automatic route-based code splitting

### Developer Experience
- **Hot Reload**: Instant feedback during development
- **TypeScript**: Full type safety and IntelliSense
- **ESLint**: Code quality and consistency
- **Component Library**: Reusable UI components

### Accessibility
- **ARIA Support**: Full accessibility compliance
- **Keyboard Navigation**: Complete keyboard support
- **Screen Reader**: Optimized for assistive technologies
- **Color Contrast**: WCAG compliant color schemes

## 📱 Responsive Design

The website is built with a mobile-first approach:
- **Mobile**: Optimized for smartphones and tablets
- **Desktop**: Enhanced experience for larger screens
- **Touch**: Touch-friendly interactions
- **Performance**: Optimized loading across all devices

## 🌐 Browser Support

- **Modern Browsers**: Chrome, Firefox, Safari, Edge (latest versions)
- **Mobile Browsers**: iOS Safari, Chrome Mobile
- **Progressive Enhancement**: Graceful degradation for older browsers

## 🚀 Deployment

### Vercel (https://eigenstudio.vercel.app/)
1. Connect your GitHub repository to Vercel
2. Vercel will automatically detect Next.js
3. Deploy with zero configuration

### Other Platforms
- **Netlify**: Use `npm run build` and deploy `out` directory
- **AWS Amplify**: Connect repository and auto-deploy
- **Docker**: Build and deploy containerized application

## 📊 Performance Metrics

- **Lighthouse Score**: 90+ across all categories
- **Core Web Vitals**: Optimized for user experience
- **Bundle Size**: Optimized with tree shaking
- **Loading Speed**: Fast initial page loads

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is private and proprietary. All rights reserved.

## 📞 Contact

- **Website**: [eigenstudio.com](https://eigenstudio.com)
- **Email**: [hello@eigenstudio.com](mailto:hello@eigenstudio.com)
- **Portfolio**: View our work at [eigenstudio.com/studio](https://eigenstudio.com/studio)

## 🙏 Acknowledgments

- **Next.js Team** - For the amazing framework
- **Vercel** - For hosting and deployment
- **Tailwind CSS** - For the utility-first CSS framework
- **Three.js Community** - For 3D graphics capabilities

---

**Built with ❤️ by eigenstudio Team**

*Last updated: October 2025*