# 🏔️ Wild Blue Trek - Selvaggio Blu Self-Guided Adventure Guide

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![No JavaScript](https://img.shields.io/badge/JavaScript-None-yellow)](.)

A retro-styled, static HTML website providing comprehensive information for hikers who want to complete the **Selvaggio Blu** trek in Sardinia, Italy **independently without hiring a guide**.

> 🌐 **Live Site:** Hosted on Cloudflare Pages  
> 📦 **Repository:** [github.com/LORBARCA93/wild-blue-trek](https://github.com/LORBARCA93/wild-blue-trek)

---

## 📸 Preview

| Desktop View | Mobile View |
|--------------|-------------|
| ![Desktop](https://via.placeholder.com/400x300?text=Desktop+Preview) | ![Mobile](https://via.placeholder.com/200x400?text=Mobile+Preview) |

---

## 🎯 Purpose

This website helps international trekkers (primarily English-speaking foreigners) organize and complete the Selvaggio Blu trek on their own. 

**Philosophy:** Adventure should be accessible to everyone - not just those who can afford expensive guided tours (typically €1,500-2,000 per person).

With proper preparation, skills, and a logistics service for food/water delivery, experienced hikers can complete this trek for approximately **€300-500 per person**.

---

## 🗺️ Route Variants

| Route | Duration | Difficulty | Rappelling |
|-------|----------|------------|------------|
| **[Classic Route](index.html)** | 4-5 days | 🔴 Extreme | 8 rappels (up to 50m) |
| **[Short Version](variant-short.html)** | 2-3 days | 🟢 Moderate | None required |
| **[Extended Route](variant-extended.html)** | 5 days | 🔴 Extreme+ | 8+ rappels (up to 45m) |

---

## 🎨 Design Philosophy

- **90s Retro Web Aesthetic**: Table-based layouts, classic fonts (Georgia, Arial), visible borders
- **Pure HTML/CSS**: No JavaScript - keeps it simple and universally accessible
- **Mobile Responsive**: Sidebar hides on small screens for better mobile experience
- **Print Friendly**: CSS print styles for offline use
- **Lightweight**: Instant loading, no external dependencies

---

## 📁 File Structure

```
wild-blue-trek/
├── index.html            # Main trek guide (classic route)
├── about.html            # Project philosophy
├── variant-short.html    # Short version (no ropes)
├── variant-extended.html # Extended route to Cala Gonone
├── README.md             # This file
├── LICENSE               # MIT License
├── agent.md              # AI agent instructions
├── .gitignore            # Git ignore rules
└── .nojekyll             # Disable Jekyll processing
```

---

## 🚀 Deployment

### Cloudflare Pages (Current)

This site is deployed on Cloudflare Pages:

1. Connect your GitHub repository to Cloudflare Pages
2. **Build command:** (none - static HTML)
3. **Build output directory:** `/` (root)
4. **Branch:** `main`

### Alternative Hosting

These are static HTML files - deploy anywhere:
- [GitHub Pages](https://pages.github.com) - Free GitHub hosting
- [Netlify](https://netlify.com) - Drag & drop deployment
- [Vercel](https://vercel.com) - Git integration
- Any traditional web host

**No build process required!**

---

## 💻 Local Development

```bash
# Clone the repository
git clone https://github.com/LORBARCA93/wild-blue-trek.git
cd wild-blue-trek

# Option 1: Python server
python -m http.server 8080

# Option 2: PHP server
php -S localhost:8080

# Option 3: Node.js (npx)
npx serve

# Then visit http://localhost:8080
```

---

## 🎯 Target Audience

- ✅ Experienced trekkers with multi-day hiking experience
- ✅ People comfortable with rappelling/abseiling (for classic route)
- ✅ International visitors who may not have access to Italian-language resources
- ✅ Budget-conscious adventurers seeking world-class trekking

---

## 🎨 Color Palette

| Element | Color | Hex |
|---------|-------|-----|
| Primary (headers) | Navy Blue | `#003366` |
| Background | Cream | `#f5f5dc` |
| Content | White | `#fff` |
| Sidebar | Light Tan | `#e8e8d0` |
| Warning | Dark Red | `#990000` |
| Success | Forest Green | `#336633` |

---

## 📞 Important Contacts

| Purpose | Contact |
|---------|---------|
| Trek booking | selvaggioblu@turismobaunei.eu |
| Phone | +39 349 546 2583 |
| Office hours | Mon-Fri 10:00-13:00, 15:00-16:00 |
| Emergency (EU) | 112 |
| Mountain Rescue | 118 |

---

## 🤝 Contributing

Contributions are welcome! Please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes following the existing style
4. Test locally
5. Commit (`git commit -m 'Add: description'`)
6. Push (`git push origin feature/improvement`)
7. Open a Pull Request

### Guidelines

- ✅ Maintain the 90s retro aesthetic
- ✅ Keep it pure HTML/CSS (no JavaScript)
- ✅ Test on mobile devices
- ✅ Update sidebar navigation on all pages when adding new pages
- ❌ No external dependencies or CDNs

See [agent.md](agent.md) for detailed style guidelines.

---

## 📋 Future Enhancements

- [ ] Additional route variants
- [ ] Photo gallery page
- [ ] Interactive map
- [ ] Multi-language support (IT, DE, FR)
- [ ] Printable PDF version
- [ ] Hosted GPX files

---

## ⚠️ Disclaimer

This guide is for **informational purposes only**. Trekking the Selvaggio Blu is an extreme activity with inherent risks. Users are solely responsible for their own safety.

**Always:**
- Check current conditions before departure
- Register with the Municipality of Baunei (€30 fee)
- Carry appropriate safety equipment
- Have the skills required for technical terrain
- Consider hiring a professional guide if in doubt

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

- Original route pioneers: Mario Verin and Peppino Cicalò (1987)
- Municipality of Baunei for trail management
- The trekking community for sharing their experiences

---

<p align="center">
  <strong>🌊 Buon trekking! 🏔️</strong><br>
  <em>Made with ❤️ for adventurers who prefer independence</em>
</p>

---

*Last updated: December 2024*
