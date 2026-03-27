# 🪔 Vedic Utsav Planner

A comprehensive event planning platform specializing in Vedic and traditional Indian celebrations. Built with Next.js 15, TypeScript, and Supabase.

![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-94.5%25-blue?logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-Database-green?logo=supabase&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-Styling-06B6D4?logo=tailwindcss&logoColor=white)

---

## ✨ Features

- **Multi-Event Planning** — Weddings, Birthday Parties, Corporate Events, Educational Events, Kitty Parties, and Ritual Events
- **Service Packages and Pricing** — Customizable packages with features, descriptions, and popularity indicators
- **Image Gallery** — Portfolio showcase of past events with titles and descriptions
- **AI Chatbot** — Interactive customer support for event inquiries
- **Multilingual Support** — Language switcher for international reach (i18n)
- **Blog Section** — Dynamic blog with slug-based routing for content marketing
- **Admin Dashboard** — Content management panel for managing events and bookings
- **SEO Optimized** — Dynamic meta tags, sitemap, and robots.txt generation
- **Fully Responsive** — Mobile-first design with Tailwind CSS

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Next.js 15 | React framework with App Router |
| TypeScript | Type-safe development |
| React 19 | UI library |
| Supabase | Backend, Database and Auth |
| Tailwind CSS | Utility-first styling |
| Heroicons | Icon library |
| Recharts | Data visualization |
| next-i18n | Internationalization |

---

## 📁 Project Structure

```
vedic-utsav-planner-freelance-/
├── src/
│   ├── app/
│   │   ├── admin/              # Admin dashboard
│   │   ├── api/                # API routes
│   │   ├── homepage/           # Landing page
│   │   ├── blog/               # Blog with dynamic [slug] routing
│   │   ├── weddings/           # Wedding planning page
│   │   ├── birthday-parties/   # Birthday event planning
│   │   ├── corporate-events/   # Corporate event planning
│   │   ├── education-events/   # Educational event planning
│   │   ├── kitty-party/        # Kitty party planning
│   │   ├── rituals-events/     # Ritual event planning
│   │   ├── layout.tsx          # Root layout
│   │   ├── not-found.tsx       # 404 page
│   │   ├── robots.ts           # SEO robots file
│   │   └── sitemap.ts          # XML sitemap generator
│   ├── components/
│   │   ├── common/             # Chatbot, Footer, LanguageSwitcher
│   │   └── ui/                 # Reusable UI components
│   ├── lib/
│   │   ├── supabase/           # Supabase client and server setup
│   │   ├── i18n.tsx            # i18n configuration
│   │   ├── seo.ts              # SEO utilities
│   │   └── site-content.ts     # Static content
│   └── styles/                 # Global CSS
├── public/                     # Static assets
├── supabase/migrations/        # Database migrations
├── next.config.mjs
├── tailwind.config.js
├── tsconfig.json
└── package.json
```

---

## 🚀 Quick Start

### Prerequisites

- Node.js 18+
- npm or yarn
- Supabase account ([supabase.com](https://supabase.com))

### Installation

```bash
# Clone the repository
git clone https://github.com/dipk2003/vedic-utsav-planner-freelance-.git
cd vedic-utsav-planner-freelance-

# Install dependencies
npm install
```

### Environment Setup

Create a `.env.local` file in the root directory:

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### Development

```bash
npm run dev
```

App runs at `http://localhost:4028`

### Production Build

```bash
npm run build
npm start
```

---

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start development server |
| `npm run build` | Create production build |
| `npm start` | Start production server |
| `npm run lint` | Run ESLint |
| `npm run lint:fix` | Auto-fix lint issues |
| `npm run format` | Format code with Prettier |
| `npm run type-check` | Run TypeScript type checking |

---

## 🏠 Homepage Sections

1. **Hero Section** — Eye-catching introduction with CTA
2. **Services Section** — Overview of all event planning categories
3. **Portfolio Section** — Gallery of past events
4. **Process Section** — How the planning methodology works
5. **Testimonials** — Client reviews and feedback
6. **Contact Form** — Lead generation and inquiry form

---

## 🌐 Deployment

Optimized for deployment on **Netlify** or **Vercel**.

```bash
npm run build
netlify deploy --prod
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

Made with ❤️ by [Dipanshu Pandey](https://github.com/dipk2003)