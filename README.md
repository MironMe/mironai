# Mironai

**Zero credits. Zero limits. Instant AI access.**

Mironai is a modern AI platform built for creators, builders, and teams who want instant access to powerful AI tools without credit barriers or payment friction.

## Features

- ⚡ **Zero-Credit Access** — Start using AI immediately, no paywall
- 💬 **AI Chat** — Instant responses for ideas, planning, and research
- 🎨 **Visual Generation** — Create mockups, concepts, and art direction
- 🔄 **Automation** — Build repeatable AI workflows for your team
- 📊 **Dashboard** — Track usage and manage your workspace
- ⚙️ **Settings** — Configure your domain and preferences

## Quick Start

### Local Development

```bash
# Clone the repository
git clone https://github.com/MironMe/mironai.git
cd mironai

# Start a local server
python -m http.server 8000

# Open in browser
# http://localhost:8000
```

### Pages

- **Homepage** — `index.html` — Landing page with features and pricing
- **Dashboard** — `dashboard.html` — User dashboard with stats and settings link
- **Settings** — `settings.html` — Retro-themed settings panel for domain and account configuration

## Deployment

### GitHub Pages

1. Go to your repo settings: https://github.com/MironMe/mironai/settings
2. Scroll to **Pages**
3. Enable GitHub Pages from the `main` branch
4. Your site will be available at: `https://mironme.github.io/mironai/`

### Custom Domain (mironai.com)

1. In GitHub Pages settings, enter your custom domain: `mironai.com`
2. At your domain provider, add these DNS records:
   - **A records:**
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - **CNAME (optional for www):**
     - www → MironMe.github.io
3. Wait 5-15 minutes for DNS propagation
4. Your site will be live at: `https://mironai.com`

## Project Structure

```
mironai/
├── index.html          # Landing page
├── dashboard.html      # User dashboard
├── settings.html       # Settings panel
├── styles.css          # Main stylesheet
├── script.js           # Interactive features
├── CNAME              # Custom domain configuration
├── README.md          # This file
├── LICENSE            # MIT License
└── .gitignore         # Git ignore rules
```

## Technologies

- **HTML5** — Semantic markup
- **CSS3** — Modern styling with CSS variables and grid
- **Vanilla JavaScript** — Lightweight interactivity
- **GitHub Pages** — Free static hosting

## Styling

The site uses a modern dark theme with:
- Cyan (`#6ee7ff`) and purple (`#8f7bff`) accent colors
- Semi-transparent panels with backdrop blur
- Smooth transitions and hover effects
- Responsive grid layout
- Mobile-first design

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## License

MIT License — See LICENSE file for details

## Support

For issues or questions:
- Create an issue: https://github.com/MironMe/mironai/issues
- Email: mironmeenaghan@gmail.com

---

**Built with ❤️ for creators and builders.**
