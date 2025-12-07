# Contributing to Wild Blue Trek

Thank you for your interest in contributing to the Wild Blue Trek guide! 🏔️

## 🌟 How to Contribute

### Reporting Issues

If you find errors, outdated information, or have suggestions:

1. **Check existing issues** to avoid duplicates
2. **Open a new issue** with a clear title
3. **Describe the problem** or suggestion in detail
4. **Include location** (which page, which section)

### Submitting Changes

1. **Fork** the repository
2. **Create a branch**: `git checkout -b fix/description` or `feature/description`
3. **Make your changes**
4. **Test locally** (see below)
5. **Commit** with a clear message
6. **Push** to your fork
7. **Open a Pull Request**

## 🎨 Style Guidelines

### Golden Rules

1. **NO JAVASCRIPT** - This is a pure HTML/CSS website
2. **NO EXTERNAL LIBRARIES** - No CDNs, no npm packages
3. **90s RETRO AESTHETIC** - Table layouts, basic fonts, visible borders
4. **LIGHTWEIGHT** - Keep pages fast-loading
5. **MOBILE FRIENDLY** - Test on small screens

### Color Palette (Do Not Change)

```
Primary:     #003366 (Navy Blue)
Background:  #f5f5dc (Cream)
Content:     #fff (White)
Sidebar:     #e8e8d0 (Light Tan)
Warning:     #990000 (Dark Red)
Success:     #336633 (Forest Green)
```

### Typography

- **Body text**: Georgia, "Times New Roman", serif
- **Headers**: Arial, Helvetica, sans-serif

### Page Structure

Every page must follow this template:

```html
<div class="page-wrapper">
    <div class="header">...</div>
    
    <table class="layout-table">
        <tr>
            <td class="sidebar">...</td>
            <td class="main-content">...</td>
        </tr>
    </table>
    
    <div class="footer">...</div>
</div>
```

### Adding New Pages

When adding a new page:

1. Copy an existing page as a template
2. Update all sidebars on ALL existing pages
3. Mark the current page in sidebar navigation
4. Include mobile responsiveness CSS
5. Include print styles

## 🧪 Testing Locally

```bash
# Start a local server
python -m http.server 8080

# Visit http://localhost:8080
```

### Test Checklist

- [ ] Page loads correctly
- [ ] All navigation links work
- [ ] Anchor links scroll to correct sections
- [ ] Page looks correct on desktop (>768px)
- [ ] Page looks correct on mobile (<768px)
- [ ] No console errors

## 📝 Content Guidelines

### Language

- All content in **English**
- Preserve Italian place names (Selvaggio Blu, Pedra Longa, etc.)
- Use clear, practical language

### Tone

- Informative and helpful
- Honest about difficulties
- Encouraging but realistic
- **Anonymous & objective** - No personal attributions

### Formatting

- Use `<h2>` with &#9679; bullet for main sections
- Use `<h3>` for subsections
- Add anchor `<a name="id"></a>` before sections

## ✅ Pull Request Checklist

Before submitting:

- [ ] Code follows the 90s retro style
- [ ] No JavaScript added
- [ ] No external dependencies
- [ ] Tested on desktop and mobile
- [ ] Sidebar updated on all pages (if adding new page)
- [ ] Content is accurate and helpful
- [ ] Commit messages are clear

## 📖 Resources

- [agent.md](agent.md) - Detailed AI agent instructions (style rules)
- [README.md](README.md) - Project overview

## 🙏 Thank You!

Every contribution helps trekkers have safer, more enjoyable adventures on the Selvaggio Blu. Your help is appreciated!

---

*Questions? Open an issue or reach out through the repository.*


