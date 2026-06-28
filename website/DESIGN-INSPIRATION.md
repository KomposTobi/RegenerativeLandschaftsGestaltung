# Design Inspiration: Landscape Architecture Websites

Research analysis of leading European landscape architecture firms' web presence.

---

## Firms Analyzed

| Firm | Location | Scale | Website |
|------|----------|-------|---------|
| Michel Desvigne Paysagiste (MDP) | Paris, France | Large (30+ staff, 400+ projects) | micheldesvignepaysagiste.com |
| BOGL | Copenhagen & Oslo | Medium (25 staff) | bogl.dk / bogl.no |
| Atelier Horizon | Brussels, Belgium | Small-Medium | atelierhorizon.com |
| Bureau Bas Smets | Brussels, Belgium | Medium (21 staff, 100+ projects) | bassmets.be |
| Studio Erde | Berlin & Zurich | Small-Medium | studio-erde.com |
| Kollektif Landscape | Ghent, Belgium | Small (10 staff) | kollektif.be |
| Agence Ter | Paris + 4 offices | Large | agenceter.com |
| Vogt Landscape | Switzerland | Large | vogt-la.com |
| LOLA | Rotterdam + Shenzhen | Large (40+ staff) | lola.land |

---

## 1. Common Patterns Across All Firms

### Visual Design
- **Minimalist aesthetic**: Clean, generous whitespace, restrained color palettes
- **Image-first approach**: Large, high-quality photography dominates the homepage
- **Typography**: Sans-serif fonts, often custom or refined (not system defaults)
- **Muted color schemes**: Earth tones, grays, whites, occasional accent colors
- **Grid-based layouts**: Structured but not rigid, allowing breathing room

### Navigation Structure
- **Simple top-level nav**: 4-6 main sections maximum
- **Common sections**: Projects/Work, About/Office, News, Team, Contact
- **Project filtering**: By type, year, location, or status (built/ongoing)
- **Bilingual options**: Many offer FR/EN or DE/EN switching
- **Sticky/fixed headers**: Logo and navigation always accessible

### Content Approach
- **Project storytelling**: Each project includes context, concept, and technical details
- **Process documentation**: Sketches, diagrams, cross-sections alongside photos
- **News/updates**: Active blogs showing recent awards, publications, events
- **Team transparency**: Individual team member profiles with photos
- **Contact clarity**: Full address, phone, email prominently displayed

### Technical Presentation
- **High-resolution imagery**: Professional photography of completed work
- **Technical drawings**: Plans, sections, and diagrams as design elements
- **Interactive maps**: Some firms show project locations geographically
- **Before/after**: Transformation narratives where applicable

---

## 2. Best Practices for Landscape Architecture Websites

### Portfolio Presentation
1. **Curated selection over exhaustive listing**
   - MDP separates "emblematic projects" from "recent" and "all projects"
   - Quality over quantity in homepage featured work

2. **Rich project pages**
   - Multiple high-quality images (aerial, detail, context)
   - Technical drawings (plans, sections, planting plans)
   - Project data: location, year, size, client, collaborators
   - Narrative text explaining concept and approach

3. **Visual hierarchy**
   - Hero images for impact
   - Consistent image ratios within galleries
   - Captions that inform without cluttering

### About/Office Section
1. **Firm philosophy clearly articulated**
   - BOGL: "We believe beauty creates change"
   - Studio Erde: "Critical and innovative landscape office for Anthropocene"
   - LOLA: "Studies and designs spatial transitions of lost landscapes"

2. **Team with personality**
   - Professional photos, names, roles
   - Brief bios showing expertise and background
   - Contact emails for direct connection

3. **Credentials and recognition**
   - Awards listed (BOGL: Eckersberg Medal 2026)
   - Publications and exhibitions
   - Teaching positions (Bas Smets: Harvard GSD)

### News & Updates
1. **Regular content cadence**
   - Project completions
   - Award announcements
   - Exhibition participation
   - Job postings (signals growth)

2. **Mixed media**
   - Text announcements
   - Photo documentation
   - Video walkthroughs where available

---

## 3. Specific Recommendations for Widdergrün's Redesign

### Visual Identity
**Current gaps to address:**
- Establish consistent typography system
- Define color palette that reflects brand values
- Create image treatment guidelines

**Recommendations:**
- **Primary font**: Clean sans-serif (consider: Inter, Work Sans, or custom)
- **Secondary font**: Optional serif for accents (consider: Source Serif Pro)
- **Colors**: 
  - Primary: Deep green (#2D4A3E or similar) connecting to nature
  - Secondary: Warm neutral (#E8E3D8 or similar) for backgrounds
  - Accent: Subtle earth tone for highlights
  - Text: Near-black (#1A1A1A) for readability, not pure black

### Layout Structure
**Recommended pages:**
1. **Home**
   - Hero: Full-width video or image slider of best work
   - Brief firm introduction (2-3 sentences)
   - Featured projects (3-4 recent highlights)
   - News teaser
   - Contact CTA

2. **Projects**
   - Filterable grid (by type: gardens, public spaces, commercial, etc.)
   - Each project: Large images + technical drawings + narrative
   - Project data sidebar: location, year, size, services provided

3. **About/Philosophy**
   - Company story and values
   - Approach to sustainable landscaping
   - Team profiles with photos
   - Tools and methods (including technical capabilities)

4. **Services**
   - Clear breakdown: planning, design, implementation, maintenance
   - Technical capabilities (3D planning, cross-sections, etc.)
   - Process explanation

5. **News/Journal**
   - Project completions
   - Behind-the-scenes
   - Industry insights
   - Company updates

6. **Contact**
   - Full address with map
   - Phone, email
   - Contact form
   - Social media links
   - Career opportunities (if applicable)

### Navigation
- **Desktop**: Horizontal top nav, logo left, language switcher right
- **Mobile**: Hamburger menu with smooth transitions
- **Footer**: Quick links, social icons, legal info

---

## 4. Typography, Color, and Layout Suggestions

### Typography System

```
Headings (H1): 3.5-4rem, light weight (300), generous letter-spacing
Headings (H2): 2.5rem, regular weight (400)
Headings (H3): 1.5rem, medium weight (500)
Body: 1.125rem, regular weight, 1.6 line-height
Captions: 0.875rem, light weight, uppercase with letter-spacing
```

**Font pairing example:**
- Headings: Inter Light or Work Sans Light
- Body: Inter Regular or system sans-serif stack
- Accent: Source Serif Pro Italic (for quotes, special callouts)

### Color Palette

```css
/* Primary palette */
--green-deep: #2D4A3E;      /* Brand primary, headers */
--green-medium: #4A6B5A;    /* Secondary elements */
--green-light: #7A9B8A;     /* Accents, hover states */

/* Neutrals */
--cream: #F5F2EB;           /* Page backgrounds */
--warm-gray: #E8E3D8;       /* Card backgrounds */
--text-dark: #1A1A1A;       /* Primary text */
--text-medium: #4A4A4A;     /* Secondary text */
--text-light: #8A8A8A;      /* Captions, metadata */

/* Functional */
--white: #FFFFFF;           /* Cards, overlays */
--black: #000000;           /* Rare use, logos only */
```

### Layout Grid

```
Desktop:
- Max width: 1440px
- Content width: 1200px
- 12-column grid
- Gutter: 24px
- Margin: auto

Tablet:
- 8-column grid
- Reduced gutters: 16px

Mobile:
- Single column
- Full-width images
- Stack navigation
```

### Spacing System

```
--space-xs: 0.5rem (8px)
--space-sm: 1rem (16px)
--space-md: 2rem (32px)
--space-lg: 4rem (64px)
--space-xl: 8rem (128px)
```

---

## 5. Presenting Technical Work Professionally

### Maps, Cross-Sections, and Technical Drawings

**Visual treatment:**
1. **Consistent styling**
   - Line weights: Thin (0.5pt) for contours, medium (1.5pt) for boundaries, thick (3pt) for emphasis
   - Color coding: Green for planting, blue for water, gray for hardscape, red/orange for highlights
   - North arrows and scale bars on all maps

2. **Presentation formats**
   - **Plan views**: Top-down, clean linework, minimal color
   - **Cross-sections**: Show terrain, planting layers, construction details
   - **Axonometrics**: 3D perspective for complex sites
   - **Diagram series**: Concept → Development → Final design

3. **Interactive elements**
   - Hover states revealing additional information
   - Before/after sliders for transformations
   - Zoomable high-resolution drawings
   - Layer toggles (planting, hardscape, drainage)

### Technical Drawing Checklist

For each project, consider including:
- [ ] Site analysis map (context, topography, existing conditions)
- [ ] Concept diagram (design drivers)
- [ ] Master plan (final design, top-down)
- [ ] Cross-sections (minimum 2, showing terrain and planting)
- [ ] Planting plan (if applicable)
- [ ] Detail drawings (signature elements)
- [ ] Construction photos (during and after)
- [ ] Aerial photography (for scale and context)

### File Preparation

**For web display:**
- SVG for drawings (scalable, small file size)
- WebP for photos (good compression, quality)
- PDF download option for technical drawings
- Consistent naming convention

**Resolution guidelines:**
- Screens: 72-96 dpi (standard), 144-192 dpi (retina)
- Print downloads: 300 dpi minimum
- Max file size: 500KB per image for fast loading

---

## 6. Platform & Technology Recommendations

### Website Platform Options

**For Widdergrün's needs:**

1. **Webflow** (Recommended)
   - Visual design control without coding
   - CMS for projects and news
   - Responsive by default
   - Good for portfolio sites
   - Hosting included

2. **WordPress + Custom Theme**
   - Maximum flexibility
   - Strong CMS capabilities
   - Requires developer for custom design
   - Good for content-heavy sites

3. **Static Site (Next.js/Astro)**
   - Fastest performance
   - Best for design-heavy sites
   - Requires developer
   - Headless CMS option

### Essential Features

- [ ] Responsive design (mobile-first)
- [ ] Fast loading (<3 seconds)
- [ ] SEO optimized
- [ ] SSL certificate
- [ ] Analytics integration
- [ ] Contact form with spam protection
- [ ] Image lazy loading
- [ ] Sitemap for navigation
- [ ] Multi-language support (DE/EN)
- [ ] Social media integration

### Performance Targets

- Page load: < 3 seconds
- First contentful paint: < 1.5 seconds
- Mobile-friendly: 100% responsive
- Accessibility: WCAG 2.1 AA compliance
- Image optimization: WebP with fallbacks

---

## 7. Competitive Differentiation

### What Makes These Sites Feel Professional vs. Generic

**Professional indicators:**
1. **Intentional typography** - Not default browser fonts
2. **Consistent spacing** - Mathematical rhythm in layouts
3. **High-quality imagery** - Professional photography, not snapshots
4. **Thoughtful interactions** - Smooth transitions, hover states
5. **Clear hierarchy** - Easy to scan, find information
6. **Brand coherence** - Colors, fonts, tone all aligned
7. **Technical credibility** - Drawings, process documentation
8. **Active maintenance** - Recent news, updated content

**Generic site red flags:**
- Template-looking design
- Inconsistent spacing and alignment
- Low-quality or stock imagery
- No clear visual hierarchy
- Outdated content
- Slow loading times
- Poor mobile experience

### Widdergrün's Opportunity

Position between:
- **Technical precision** (like Studio Erde's Anthropocene focus)
- **Warm accessibility** (like BOGL's human-centered approach)
- **Craft quality** (like MDP's 30+ years of refined practice)

**Unique value propositions to highlight:**
- Integrated planning to maintenance
- Technical capabilities (3D, cross-sections)
- Local expertise with international perspective
- Sustainable practices
- Client collaboration approach

---

## 8. Implementation Roadmap

### Phase 1: Foundation (Weeks 1-2)
- [ ] Define brand guidelines (colors, fonts, spacing)
- [ ] Audit existing content
- [ ] Create content inventory
- [ ] Wireframe key pages
- [ ] Select platform

### Phase 2: Content Creation (Weeks 3-6)
- [ ] Professional photography of best projects
- [ ] Technical drawing preparation
- [ ] Write project descriptions
- [ ] Team photos and bios
- [ ] About/philosophy content

### Phase 3: Design & Build (Weeks 7-10)
- [ ] Visual design mockups
- [ ] Responsive development
- [ ] CMS setup
- [ ] Content migration
- [ ] Testing across devices

### Phase 4: Launch & Optimize (Weeks 11-12)
- [ ] Final testing
- [ ] SEO optimization
- [ ] Analytics setup
- [ ] Launch
- [ ] Monitor performance
- [ ] Gather feedback

---

## Appendix: Reference Links

- Michel Desvigne: https://www.micheldesvignepaysagiste.com
- BOGL: https://bogl.dk
- Atelier Horizon: https://atelierhorizon.com
- Bureau Bas Smets: https://www.bassmets.be
- Studio Erde: https://www.studio-erde.com
- Kollektif: https://kollektif.be
- Agence Ter: https://agenceter.com
- Vogt: https://www.vogt-la.com
- LOLA: https://lola.land

---

*Document created: June 2026*
*For: Widdergrün Website Redesign Project*
