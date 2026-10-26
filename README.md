# Darwin's Edge

[![Live Demo](https://img.shields.io/badge/Live_Demo-Access_Platform-blue?style=for-the-badge&logo=netlify)](https://darwinsedge.netlify.app/)

A luxury eco-lodge hospitality and sustainable tourism web platform set in the Galápagos Islands. Built with React 18, Vite, TypeScript, Tailwind CSS, Framer Motion, and Firebase Firestore.

![Darwin's Edge Preview](public/preview.png)

<div align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white" alt="Framer Motion" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/License-MIT-44CC11?style=for-the-badge" alt="MIT License" />
</div>

---

## Features

### 🌋 Immersive Galápagos Experience
- Cinematic volcanic and archipelago visual design powered by Framer Motion entrance animations.
- Sustainable hospitality storytelling centered on conservation and low-impact tourism.

### 🛎️ Real-Time Reservation & Availability Engine
- Interactive booking bar with date-range pickers and dynamic guest selection.
- Room tier showcase: Oceanfront Villas, Volcanic Suites, and Canopy Treehouses.

### 📊 Administrative Management Dashboard
- Integrated booking calendar and reservation tracking.
- Protected authentication routes backed by Firebase.

---

## Project Structure

```
DARWIN'S EDGE/
├── src/
│   ├── components/      # UI components (Hero, BookingBar, AccommodationsSlider, Header)
│   ├── pages/           # Application views (Index, Booking, Dashboard, Login)
│   ├── lib/             # Utility helpers and Firestore configuration
│   └── assets/          # High-resolution Galápagos imagery and visual assets
├── public/              # Static assets and favicon
│   └── preview.png      # Application hero screenshot preview
├── server/              # Backend payment / notification microservice
└── index.html           # Application root entrypoint
```

---

## Getting Started

### Prerequisites
- Node.js 18+
- npm or bun

### Installation
```bash
# Clone the repository
git clone https://github.com/adriangbustos/Darwins-Edge.git
cd Darwins-Edge

# Install dependencies
npm install

# Start development server
npm run dev
```
Open `http://localhost:5173` in your web browser.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
