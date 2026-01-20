# 🍹 Cocktail App

A modern, interactive cocktail showcase application built with React and Vite, featuring smooth animations and responsive design.

## Features

- **Interactive Hero Section** with GSAP animations and video playback synchronized to scroll
- **Responsive Design** using Tailwind CSS and React Responsive
- **Smooth Animations** powered by GSAP and SplitText for text animations
- **Fast Performance** with Vite as the build tool
- **Modern Stack** - React 19, Tailwind CSS 4, and GSAP 3

## Tech Stack

- **React 19.2.0** - UI library
- **Vite 7.2.4** - Build tool
- **GSAP 3.14.2** - Animation library
- **Tailwind CSS 4.1.18** - Utility-first CSS framework
- **React Responsive 10.0.1** - Responsive design queries
- **ESLint** - Code quality

## Getting Started

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

Starts the development server with hot module replacement (HMR).

### Build

```bash
npm run build
```

Builds the application for production.

### Linting

```bash
npm run lint
```

Checks code quality with ESLint.

### Preview

```bash
npm run preview
```

Previews the production build locally.

## Project Structure

```
src/
├── components/
│   ├── Hero.jsx          # Main hero section with video animations
│   └── Navbar.jsx        # Navigation component
├── App.jsx               # Root component
├── main.jsx              # Entry point
├── App.css               # Component styles
└── index.css             # Global styles

public/
├── fonts/                # Custom fonts
├── images/               # Image assets
├── videos/               # Video assets
└── readme/               # Documentation images

constant/
└── index.js              # App constants
```

## Key Components

### Hero Component
Features smooth scroll-triggered animations using GSAP:
- Text animation with character-by-character reveal
- Video playback synchronized to scroll position
- Parallax leaf animations
- Responsive design for mobile and desktop

## Browser Support

Works on all modern browsers that support ES6 and CSS Grid.
