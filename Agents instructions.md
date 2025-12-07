# Agent Instructions

> **IMPORTANT:** All AI agents must read this document before making ANY changes to this repository.

---

## Project Identity

**Wild Blue Trek** - A self-guided adventure guide for the Selvaggio Blu trek in Sardinia, Italy.

**Core Mission:** Help international trekkers complete the Selvaggio Blu independently, without expensive guided tours.

---

## Golden Rules

### 1. NO JAVASCRIPT
- This is a **pure HTML/CSS website**
- Do NOT add any JavaScript, ever
- Do NOT add any JavaScript frameworks or libraries
- All interactivity must be achieved with HTML anchor links and CSS only

### 2. NO EXTERNAL LIBRARIES
- Do NOT install npm packages
- Do NOT add CDN links
- Do NOT add external CSS frameworks (no Bootstrap, Tailwind, etc.)
- Do NOT add icon libraries (use HTML entities like `&#9679;` instead)
- Keep everything self-contained in the HTML files

### 3. 90s RETRO AESTHETIC - MANDATORY
The website MUST maintain a nostalgic 1990s web style:
- **Table-based layouts** for page structure
- **Basic system fonts**: Georgia, "Times New Roman", Arial, Helvetica
- **Visible borders** and horizontal rules (`<hr>`)
- **Simple color scheme**: Navy blue (#003366), cream (#f5f5dc), white backgrounds
- **No rounded corners** or shadows
- **No gradients** (solid colors only)
- **HTML entities** for decorations (&#9679;, &#9658;, &#9733;, etc.)
- Keep the "Best viewed with Netscape Navigator 4.0" joke in footers

### 4. LIGHTWEIGHT & FAST
- **No images** unless explicitly requested by the user
- Keep HTML files small and efficient
- Inline CSS in `<style>` tags (no external CSS files)
- No unnecessary markup or bloated code
- Target: Each page should load instantly

### 5. RESPONSIVE WITHIN RETRO CONSTRAINTS
- Use percentage widths where appropriate
- Main content table: `width: 100%` with max reasonable width
- Sidebar should remain functional on smaller screens
- Content must be readable at any screen size

---

## Style Consistency

### Color Palette (DO NOT CHANGE)
```
Primary:        #003366 (Navy Blue)
Background:     #f5f5dc (Cream/Beige)
Content BG:     #fff (White)
Sidebar BG:     #e8e8d0 (Light Tan)
Warning:        #990000 (Dark Red)
Success/Green:  #336633 (Forest Green)
Tip/Gold:       #996600 (Brown/Gold)
```

### Typography (DO NOT CHANGE)
```
Body:     Georgia, "Times New Roman", Times, serif
Headers:  Arial, Helvetica, sans-serif
```

### Page Structure Template
Every page MUST follow this structure:
```html
<div class="page-wrapper">
    <!-- Header -->
    <div class="header">...</div>
    
    <!-- Main Layout Table -->
    <table class="layout-table">
        <tr>
            <!-- Sidebar -->
            <td class="sidebar">...</td>
            
            <!-- Main Content -->
            <td class="main-content">...</td>
        </tr>
    </table>
    
    <!-- Footer -->
    <div class="footer">...</div>
</div>
```

---

## Sidebar Navigation Rules

### All Pages Must Have:
1. **Pages section** - Links to main pages (index.html, about.html)
2. **Variants section** - Links to all variant routes
3. **Sections/On This Page** - Anchor links for current page

### When Adding New Pages:
- Update the sidebar on ALL existing pages
- Mark current page with `class="current-page"`
- Use consistent link styling

### Sidebar Link Formats:
```html
<!-- Page link -->
<li class="page-link"><a href="page.html">&#9658; Page Name</a></li>

<!-- Current page -->
<li class="page-link current-page"><a href="current.html">&#9658; Current</a></li>

<!-- Variant link -->
<li style="background-color: #e0e8d0;"><a href="variant-x.html" style="color: #336633;">&#9658; Variant Name</a></li>

<!-- Section anchor -->
<li><a href="#section-id">Section Name</a></li>
```

---

## Content Guidelines

### Language
- All content in **English** (target audience: international trekkers)
- Preserve Italian place names (Selvaggio Blu, Pedra Longa, Cala Goloritzè, etc.)
- Use clear, practical language - this is a guide, not marketing

### Tone
- Informative and helpful
- Honest about difficulties and requirements
- Encouraging but realistic
- Respectful of local guides and regulations
- **ANONYMOUS & OBJECTIVE** - No personal attributions, no "I", no specific guide names
- Use passive voice or third person when giving advice (e.g., "it is recommended" not "I recommend")

### Structure
- Use `<h2>` for main sections (with &#9679; bullet)
- Use `<h3>` for subsections
- Use `<h4>` for minor headings
- Always add anchor `<a name="id"></a>` before sections

---

## CSS Classes Reference

Use these existing classes - DO NOT create new ones unless absolutely necessary:

| Class | Purpose |
|-------|---------|
| `.warning-box` | Red-bordered warnings/dangers |
| `.info-box` | Green-bordered helpful info |
| `.tip-box` | Blue left-border tips |
| `.contact-box` | Light blue contact details |
| `.day-box` | Route day breakdown |
| `.pro-tip` | Yellow dashed pro tips |
| `.data-table` | Styled data tables |
| `.checklist-table` | Equipment checklists |
| `.download-box` | Green CTA/download boxes |
| `.stats-box` | Statistics display |
| `.compare-table` | Comparison tables |
| `.highlight-box` | Yellow highlighted features |

---

## File Naming Conventions

- Main pages: `lowercase.html` (e.g., `index.html`, `about.html`)
- Variant pages: `variant-name.html` (e.g., `variant-short.html`)
- No spaces in filenames
- Use hyphens, not underscores

---

## Before Making Changes

### Checklist:
- [ ] Have I read this entire document?
- [ ] Does my change maintain the 90s retro aesthetic?
- [ ] Am I avoiding JavaScript and external libraries?
- [ ] Will the page remain lightweight and fast?
- [ ] Have I updated sidebars on ALL pages if adding a new page?
- [ ] Am I using existing CSS classes instead of creating new ones?
- [ ] Does my HTML follow the established page structure?

---

## Forbidden Actions

❌ DO NOT add JavaScript  
❌ DO NOT add external libraries or CDNs  
❌ DO NOT add images without explicit user request  
❌ DO NOT change the color scheme  
❌ DO NOT change the fonts  
❌ DO NOT add CSS frameworks  
❌ DO NOT use modern CSS features (flexbox, grid, CSS variables)  
❌ DO NOT add build processes or package.json  
❌ DO NOT change the table-based layout structure  
❌ DO NOT add personal attributions or names (keep content anonymous)  
❌ DO NOT use first person ("I", "my", "we", "our") - use objective language  

---

## Allowed Actions

✅ Add new HTML pages following the template  
✅ Add new content sections  
✅ Add new variant routes  
✅ Fix typos and improve translations  
✅ Add new CSS classes if truly necessary (same style)  
✅ Improve accessibility within retro constraints  
✅ Update contact information if provided by user  

---

## Quick Reference

```
Main Trek Guide:     index.html
About Page:          about.html
Short Variant:       variant-short.html (no rappelling, 2-3 days)
Extended Variant:    variant-extended.html (T6+ to Cala Gonone, 5 days)
Documentation:       README.md
Agent Instructions:  agent.md (this file)
```

---

**Remember:** When in doubt, keep it simple. This website celebrates the charm of 1990s web design while providing genuinely useful information for adventurous trekkers.

*— Instructions last updated: December 2024*

