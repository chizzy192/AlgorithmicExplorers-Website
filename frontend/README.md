# Algorithmic Explorers — Frontend

Frontend for the **Algorithmic Explorers Website**, built with **React**, **TypeScript**, and **Vite**.  
Includes **Tailwind CSS**, **React Router**, **Framer Motion**, and **Swiper** for UI/animations and carousel components.

---

## Tech Stack

- **React + TypeScript** (UI + type safety)
- **Vite** (dev server + builds)
- **Tailwind CSS** (utility-first styling)
- **react-router-dom** (routing)
- **framer-motion** (animations)
- **swiper** (carousel/swiper components)
- **ESLint** (linting)

---

## Getting Started

### Prerequisites
- **Node.js** (recommended: latest LTS)
- **npm**

### Install dependencies
```bash
cd frontend
npm install
```

### Run the dev server
```bash
npm run dev
```

### Build for production
```bash
npm run build
```

### Preview the production build
```bash
npm run preview
```

### Lint
```bash
npm run lint
```

---

## Available Scripts

From `frontend/package.json`:

- `npm run dev` – start Vite dev server
- `npm run build` – typecheck + build
- `npm run preview` – preview production build locally
- `npm run lint` – run ESLint

---

## Project Structure

```text
frontend/
├─ .gitignore
├─ README.md
├─ eslint.config.js
├─ index.html
├─ next-arrow.png
├─ package-lock.json
├─ package.json
├─ tsconfig.json
├─ tsconfig.app.json
├─ tsconfig.node.json
├─ vite.config.ts
├─ public/
│  ├─ background.jpg
│  ├─ badge 1.png
│  ├─ badge 2.png
│  ├─ badge 3.png
│  ├─ btn-members.png
│  ├─ chart.png
│  ├─ descript-logo.png
│  ├─ favicon.png
│  ├─ ghana 1.png
│  ├─ Grammarly-logo.png
│  ├─ guru-preview.png
│  ├─ image.png
│  ├─ Intercom-logo.png
│  ├─ next-arrow.png
│  ├─ Notion-logo.png
│  ├─ Pasted image.png
│  ├─ Screenshot from 2025-11-23 23-09-45.png
│  ├─ testimonials-person.png
│  ├─ trust-chart.png
│  ├─ unsplash-logo.png
│  └─ Vector.png
└─ src/
   ├─ main.tsx
   ├─ App.tsx
   ├─ index.css
   ├─ assets/
   │  ├─ 4c8a9da61a41a42f6778ce275a3103d54783f85c.png
   │  ├─ Rectangle 85.png
   │  └─ react.svg
   ├─ components/
   │  ├─ CohortsSection.tsx
   │  ├─ CommunitySection.tsx
   │  ├─ Footer.tsx
   │  ├─ Navbar.tsx
   │  ├─ ScrollFadeIn.tsx
   │  ├─ TestimonialSwiper.tsx
   │  └─ WhoWeAre.tsx
   └─ pages/
      └─ Homepage.tsx
```

---

## Notes

- Static images live in `public/` (served directly).
- App code lives in `src/`.
- Page-level components live in `src/pages/`.
- Reusable UI components live in `src/components/`.

---

## Contributing

1. Create a new branch for your change
2. Run `npm install` and `npm run dev`
3. Before pushing, run:
   - `npm run lint`
   - `npm run build`

---

## License

See the repository root for license information (if provided).