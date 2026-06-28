# Static Growth Pages

Reusable static-site components and templates for high-velocity marketing campaign execution. Built with **Astro**.

## 🚀 Features

- **Static-Site Generation** — Pre-rendered pages with instant load times via Astro
- **Reusable Components** — Header, Footer, CTAButton, FeatureCard, LeadForm
- **ABM Campaign Template** — Personalized landing page with lead capture and campaign attribution
- **Schema.org Markup** — Structured data for AEO/GEO (AI Search Optimization)
- **Lead Capture Forms** — With hidden fields for UTM tracking and CRM integration
- **Responsive Design** — Mobile-first CSS with modern grid layouts
- **Git-Based Workflow** — Ready for CI/CD on Vercel/Netlify

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| [Astro 4](https://astro.build) | Static site generator |
| TypeScript | Type-safe components |
| Schema.org | AEO/GEO structured data |
| Vercel | Deployment platform |

## 📦 Getting Started

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📁 Project Structure

```
src/
├── components/        # Reusable UI components
│   ├── Header.astro
│   ├── Footer.astro
│   ├── CTAButton.astro
│   ├── FeatureCard.astro
│   └── LeadForm.astro
├── layouts/           # Page layouts
│   └── BaseLayout.astro
└── pages/             # Routes
    ├── index.astro    # Home page
    ├── about.astro    # About page
    └── campaigns/     # ABM campaign template
        └── index.astro
```

## 🎯 Use Cases

This project provides building blocks for:

- **Growth Web Engineering** — Fast, reliable page creation and iteration
- **ABM Campaigns** — Targeted landing pages with lead capture
- **AI-Enabled Workflows** — Built with AI assistance, ready for AI-driven optimization
- **Marketing Tech Integration** — Form handling with campaign attribution
- **Static-Site Architecture** — Astro, Vercel, Git-based workflows

## 🚢 Deployment

### Vercel (Recommended)

1. Push to GitHub
2. Import project on [Vercel](https://vercel.com)
3. Zero-config deployment — Vercel auto-detects Astro

### Netlify

1. Push to GitHub
2. Import project on [Netlify](https://netlify.com)
3. Build command: `astro build`
4. Publish directory: `dist`

## 📄 License

MIT

## 👤 Author

**Edward Ojambo** — Full-Stack Engineer & Growth Web Developer
- [Ojambo.com](https://ojambo.com)
- [GitHub](https://github.com/ojambo)
- [LinkedIn](https://linkedin.com/in/ojambo)
