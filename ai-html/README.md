# 🕰️ Frontend Web Projects — AI-Assisted HTML/CSS

> **Two structured, production-style HTML projects built using AI-assisted development (Claude by Anthropic). Projects cover a luxury e-commerce product page and a data collection survey form — both using table-based layouts, inline styling, and native HTML form elements.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS Inline](https://img.shields.io/badge/Inline%20CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![AI Assisted](https://img.shields.io/badge/AI--Assisted-Claude%20by%20Anthropic-blueviolet?style=for-the-badge)
![No Framework](https://img.shields.io/badge/Framework-None-lightgrey?style=for-the-badge)

---

## 📌 Table of Contents

- [About This Repository](#about-this-repository)
- [AI-Assisted Development — Methodology](#ai-assisted-development--methodology)
- [Projects Included](#projects-included)
  - [Project 1 — Timeless Watches (E-Commerce Product Page)](#project-1--timeless-watches-e-commerce-product-page)
  - [Project 2 — Survey Form (Data Collection UI)](#project-2--survey-form-data-collection-ui)
- [Tech Stack](#tech-stack)
- [Folder Structure](#folder-structure)
- [Layout Architecture](#layout-architecture)
  - [E-Commerce Layout Tree](#e-commerce-layout-tree)
  - [Survey Form Layout Tree](#survey-form-layout-tree)
- [Component Breakdown](#component-breakdown)
- [Design Decisions](#design-decisions)
- [Color Palette](#color-palette)
- [How to Run Locally](#how-to-run-locally)
- [Author](#author)

---

## About This Repository

This repository contains **two frontend HTML projects** developed using an **AI-assisted workflow** with Claude (by Anthropic). The goal was to produce clean, well-structured, professional-grade HTML pages while learning how to effectively direct, prompt, and iterate with AI tools to achieve a specific design outcome.

Both projects are:
- Fully self-contained (single `.html` file per project)
- Built with **zero external CSS files**, **zero JavaScript**, **zero frameworks**
- Structured using **table-based HTML layouts** — the standard approach for HTML emails and legacy-compatible web pages
- Styled entirely through **inline styles** and **HTML presentation attributes**

---

## AI-Assisted Development — Methodology

These projects were built using **Claude by Anthropic** as an AI coding assistant. This is a transparent, honest account of the development process.

### What AI Did
- Generated the initial HTML structure based on design requirements I provided
- Implemented the table-based grid system and nested layout logic
- Wrote inline styling, color values, font attributes, and spacing
- Suggested component structure (nav bar, product card, thumbnail row, form fields)

### What I Did (My Contribution)
- **Defined the full project scope** — decided what pages to build, what sections to include, and what the final product should look like
- **Directed all design decisions** — chose the color palette (`#1e2a3a` navy, teal `#9ED4C9`), layout structure (two-column product page, label-aligned form), and component requirements
- **Reviewed and evaluated every output** — read through the generated code, understood what each element does, and approved or requested changes
- **Iterated on the design** — gave follow-up instructions to refine spacing, fix alignment, adjust sizing, and improve visual hierarchy
- **Learned the underlying structure** — studied the table nesting patterns, inline styling techniques, and form element types used throughout
- **Organized and published** — structured the files, named assets correctly, and prepared the project for version control

### Why This Approach Matters
AI-assisted development is a **real and growing professional skill**. The ability to:
1. Clearly define requirements and communicate them to an AI
2. Critically evaluate AI-generated code for correctness and quality
3. Iterate intelligently based on output
4. Understand the code well enough to explain, modify, and maintain it

...is exactly what modern development workflows demand. This project documents that skill honestly.

---

## Projects Included

### Project 1 — Timeless Watches (E-Commerce Product Page)

**File:** `timeless-watches.html`

A fully structured e-commerce product detail page for a fictional luxury watch brand. Designed to replicate the layout pattern of real-world product pages.

#### Sections Built
| Section | Description |
|---|---|
| Navigation Bar | Full-width dark header with brand name, search input, and 5 nav links |
| Product Card | Centered white card (1150px wide) containing the full product layout |
| Image Column | Hero image (480×480px) + thumbnail row of 6 images |
| Product Info Column | Title, brand, pricing, description, star rating, quantity selector, CTA buttons |
| Pricing Row | Sale price + original strikethrough price + red discount badge |
| Quantity Selector | Bordered −/input/+ widget built with a 3-cell table |
| Add to Bag Button | Full-width dark navy CTA button (table-based, no `<button>` tag) |
| Newsletter Promo Box | Bordered offer card with secondary Sign Up CTA |

#### Key Design Requirements I Specified
- Two-column layout: image left, product details right
- Dark navy (`#1e2a3a`) used for the navbar and both CTA buttons for brand consistency
- Discount badge in red (`#cc4444`) to draw attention
- Star rating using HTML entity `&#9733;` in gold (`#f5a623`)
- Thumbnail row with 6px gaps between images using `cellspacing="6"`
- Newsletter box visually separated using a light grey background (`#f9f9f9`) and border

---

### Project 2 — Survey Form (Data Collection UI)

**File:** `survey-form.html`

A clean, structured survey form UI. Built using a two-column table layout that aligns labels on the right with inputs on the left — the standard pattern for accessible, readable forms.

#### Form Fields Built
| Field | Input Type | Notes |
|---|---|---|
| Name | `type="text"` | Required field (`*` indicator) |
| Email | `type="email"` | Required field, email validation built-in |
| Age | `type="number"` | Required field |
| Current Role | `<select>` | 4 options: Student, Full Time, Part Time, Other |
| Recommendation | `type="radio"` | 3 options, `name="recommend"` groups them |
| Like Most | `<select>` | 3 options + default placeholder option |
| Things to Improve | `type="checkbox"` | 3 options, multi-select via `name="improve"` |

#### Key Design Requirements I Specified
- Teal page background (`#9ED4C9`) for a calm, non-distracting form environment
- White card container (960px) for the form — centred on the page
- All labels right-aligned in a 420px column, inputs in a 480px column
- Multi-line labels (radio + checkbox sections) handled using nested tables to maintain right-alignment
- `name="recommend"` attribute on all radio buttons so they behave as a mutually exclusive group
- Required fields visually marked with `*` prefix in the label text

---

## Tech Stack

| Technology | Role in This Project |
|---|---|
| HTML5 | Full document structure and all content |
| `<table>` layout | Grid system — rows, columns, spacing, alignment |
| Inline `style=""` | `border-radius`, `cursor`, `line-height`, `font-size`, specific overrides |
| HTML presentation attributes | `bgcolor`, `align`, `valign`, `cellpadding`, `cellspacing`, `width`, `height` |
| `<font>` tag | Typography: `size`, `color`, `face` attributes |
| Native HTML form elements | `<input>`, `<select>`, `<option>`, radio, checkbox, number inputs |
| HTML character entities | `&#9733;` (star), `&#9679;` (dot), `&nbsp;` (space) |
| External image (Unsplash CDN) | Thumbnail 4 in the watch gallery |
| Claude by Anthropic | AI assistant used to generate and refine the code |

---

## Folder Structure

```
📁 project-root/
│
├── 📄 timeless-watches.html      →  E-Commerce product page
├── 📄 survey-form.html           →  Survey data collection form
│
├── 🖼️  heroimg.jpeg               →  Main product hero image (480×480)
├── 🖼️  img1.jpeg                  →  Thumbnail 1
├── 🖼️  img2.jpeg                  →  Thumbnail 2
├── 🖼️  img3.jpeg                  →  Thumbnail 3
├── 🖼️  img5.jpeg                  →  Thumbnail 5
├── 🖼️  img6.jpeg                  →  Thumbnail 6
│
└── 📄 README.md                   →  This file
```

> **Note on Thumbnail 4:** Loaded from Unsplash CDN —
> `https://images.unsplash.com/photo-1587836374828-4dbafa94cf0e?w=120&q=60`
> No local file required. Needs an active internet connection to display.

---

## Layout Architecture

### E-Commerce Layout Tree

```
<body> [bgcolor="#f0f0f0"]
│
├── TABLE (width=100%, bgcolor="#1e2a3a") ── NAVIGATION BAR
│     └── TR [valign="middle"]
│           ├── TD (width=500)  →  Brand name: "TIMELESS WATCHES"
│           ├── TD              →  Search <input> + dot symbol
│           └── TD (width=380, align=right)  →  5 nav <a> links
│
└── TABLE (width=100%, cellpadding=40) ── PAGE WRAPPER
      └── TR > TD [align="center"]
            └── TABLE (width=1150, bgcolor="#fff") ── PRODUCT CARD
                  └── TR [valign="middle"]
                        │
                        ├── TD (width=500) ── LEFT: IMAGE COLUMN
                        │     └── TABLE
                        │           ├── TR → <img> heroimg.jpeg (480×480)
                        │           ├── TR → spacer (height=15)
                        │           └── TR → TABLE (cellspacing=6)
                        │                     └── TR
                        │                           ├── TD → img1.jpeg (70×65)
                        │                           ├── TD → img2.jpeg (70×65)
                        │                           ├── TD → img3.jpeg (70×65)
                        │                           ├── TD → Unsplash img (70×65)
                        │                           ├── TD → img5.jpeg (70×65)
                        │                           └── TD → img6.jpeg (70×65)
                        │
                        └── TD ── RIGHT: PRODUCT DETAIL COLUMN
                              └── TABLE (width=100%)
                                    ├── TR → Product Title (font size=6, bold)
                                    ├── TR → Brand subtitle (font size=2, #555555)
                                    ├── TR → spacer (height=15)
                                    ├── TR → Pricing row
                                    │         ├── Sale price (size=5, bold)
                                    │         ├── Original price (size=3, strikethrough)
                                    │         └── Discount badge (size=2, #cc4444)
                                    ├── TR → spacer (height=15)
                                    ├── TR → Description text (size=3, #444444)
                                    ├── TR → spacer (height=15)
                                    ├── TR → Star rating (&#9733; × 5, #f5a623) + review count
                                    ├── TR → spacer (height=20)
                                    ├── TR → QUANTITY SELECTOR
                                    │         └── TABLE (border=1, bordercolor=#cccccc)
                                    │               └── TR
                                    │                     ├── TD (35×35) → "−" button
                                    │                     ├── TD (50×35) → <input type=number>
                                    │                     └── TD (35×35) → "+" button
                                    ├── TR → spacer (height=20)
                                    ├── TR → ADD TO BAG BUTTON
                                    │         └── TABLE (width=100%)
                                    │               └── TR > TD (bgcolor=#1e2a3a, height=48)
                                    │                         └── "Add to Bag" white text
                                    ├── TR → spacer (height=20)
                                    └── TR → NEWSLETTER PROMO BOX
                                              └── TABLE (border=1, bgcolor=#f9f9f9)
                                                    └── TR > TD [align=center]
                                                          ├── "Limited-Time Offer!" heading
                                                          ├── Offer description text
                                                          └── TABLE (bgcolor=#1e2a3a)
                                                                └── "Sign Up Now" button
```

---

### Survey Form Layout Tree

```
<body> [bgcolor="#9ED4C9"]
│
├── TABLE (width=100%) ── PAGE TITLE
│     └── TR > TD [align="center"]
│           └── "Survey Form" (font size=7, bold)
│
└── TABLE (width=960, bgcolor="#ffffff", align=center) ── FORM CARD
      └── TR > TD
            └── TABLE (width=100%) ── INNER FORM TABLE
                  │
                  ├── TR [colspan=2, align=center, height=60]
                  │     └── Subtitle: "Let us know how we can improve freeCodeCamp"
                  │
                  ├── TR [valign=middle] ── NAME FIELD
                  │     ├── TD (width=420, align=right) → "* Name:" label
                  │     └── TD (width=480) → <input type="text">
                  │
                  ├── TR [valign=middle] ── EMAIL FIELD
                  │     ├── TD (align=right) → "* Email:" label
                  │     └── TD → <input type="email">
                  │
                  ├── TR [valign=middle] ── AGE FIELD
                  │     ├── TD (align=right) → "* Age:" label
                  │     └── TD → <input type="number">
                  │
                  ├── TR [valign=middle] ── ROLE DROPDOWN
                  │     ├── TD (align=right) → "Which option...role?" label
                  │     └── TD → <select> [Student / Full Time / Part Time / Other]
                  │
                  ├── TR [valign=top] ── RECOMMENDATION RADIO GROUP
                  │     ├── TD (align=right)
                  │     │     └── TABLE (2 rows) → wrapped label text
                  │     └── TD
                  │           └── TABLE (3 rows)
                  │                 ├── TR → <radio value="definitely"> Definitely
                  │                 ├── TR → <radio value="maybe"> Maybe
                  │                 └── TR → <radio value="notsure"> Not sure
                  │
                  ├── TR [valign=middle] ── PREFERENCE DROPDOWN
                  │     ├── TD (align=right) → "What do you like most in FCC:"
                  │     └── TD → <select> [Challenges / Projects / Community]
                  │
                  ├── TR [valign=top] ── IMPROVEMENT CHECKBOXES
                  │     ├── TD (align=right)
                  │     │     └── TABLE (2 rows) → wrapped label text
                  │     └── TD
                  │           └── TABLE (3 rows)
                  │                 ├── TR → <checkbox value="frontend"> Front-end Projects
                  │                 ├── TR → <checkbox value="backend"> Back-end Projects
                  │                 └── TR → <checkbox value="datavis"> Data Visualization
                  │
                  └── TR → spacer (colspan=2, height=40)
```

---

## Component Breakdown

### Navigation Bar
Full-width `<table>` with `bgcolor="#1e2a3a"`. Three `<td>` cells handle brand (left), search (center), nav links (right). All `<a>` tags override default link styling with `style="color:white; text-decoration:none;"` inline. `&nbsp;` entities add spacing between links.

### Hero Image
Single `<img>` tag at `480×480px` with `border-radius: 4px` inline style for slight rounding. The `alt` attribute is set for accessibility.

### Thumbnail Gallery
A nested `<table>` with `cellspacing="6"` creates natural gaps between thumbnails. Each `<td>` holds one `<img>` at `70×65px`. Thumbnail 4 uses an external Unsplash URL as a live CDN image.

### Pricing Row
Three inline elements in one `<td>`: sale price (`<font size="5">`), original price wrapped in `<s>` strikethrough tags (`<font color="#888888">`), and discount badge (`<font color="#cc4444">`). `&nbsp;&nbsp;` creates spacing between them.

### Star Rating
Five `&#9733;` HTML star entities inside a `<font color="#f5a623">` tag. Review count sits beside it in a smaller, muted font. No images or icon libraries — pure character entities.

### Quantity Selector
A `<table border="1" bordercolor="#cccccc">` creates the visible border box. Three `<td>` cells: minus (35px wide), number input (50px with `border:none` to remove default input border), plus (35px). `cursor: pointer` on both button cells gives interactive feel without JavaScript.

### CTA Buttons (Add to Bag / Sign Up Now)
Both buttons are `<table>` elements with `bgcolor="#1e2a3a"` and `border-radius: 4px`. The "button" is actually a styled `<td>` cell — a standard technique in table-layout HTML where CSS `<button>` elements are unavailable or unsupported.

### Newsletter Promo Box
Outer `<table>` with `border="1"` `bordercolor="#dddddd"` and `bgcolor="#f9f9f9"` creates a visually distinct card. The Sign Up button is a nested inner table using the same navy button pattern.

### Survey Form Fields
Every input pair = one `<tr>` with two `<td>` cells. Label cell: `width="420"`, `align="right"`. Input cell: `width="480"`. Multi-line labels (radio, checkbox) use a **nested table** inside the label `<td>` — each row holds one line of text — maintaining consistent right-alignment without breaking the column widths.

### Radio Button Grouping
All three recommendation radio inputs share `name="recommend"`. This HTML attribute makes them **mutually exclusive** — selecting one automatically deselects the others. This is native browser behaviour, no JavaScript needed.

### Checkbox Group
All three improvement checkboxes share `name="improve"`. Unlike radio buttons, checkboxes with the same name allow **multiple selections** simultaneously — the correct input type for "check all that apply" scenarios.

---

## Design Decisions

### Why Table-Based Layout?
Table layouts were chosen intentionally for two reasons:
1. **HTML email compatibility** — Table-based structure is the industry standard for HTML emails, which still do not support CSS Grid or Flexbox in most email clients (Outlook, Gmail, Apple Mail). Learning this pattern has direct real-world application.
2. **Foundational understanding** — Understanding how browsers render block elements without modern CSS is a skill that distinguishes developers who truly understand the web from those who only know framework syntax.

### Why Inline Styles Over an External CSS File?
Inline styling keeps each HTML file fully **self-contained and portable** — open it anywhere, no missing stylesheet. This also reflects the constraints of HTML email development where external CSS is often stripped by email clients.

### Why `<font>` Tags?
`<font>` is deprecated in HTML5 but was used deliberately here to maintain consistency with the table-layout paradigm. In production code, these would be replaced with CSS classes — but understanding legacy markup is valuable for reading and maintaining older codebases.

### Why a `<table>` as a Button?
Native `<button>` and `<a>` tags with heavy CSS styling were not used in order to stay consistent with the pure-table, pure-attribute approach of the project. The table-as-button technique (`<td bgcolor="..." align="center" style="cursor:pointer">`) is the standard approach in HTML email CTA buttons.

---

## Color Palette

### Timeless Watches

| Role | Hex Code | Used In |
|---|---|---|
| Primary Dark (Navy) | `#1e2a3a` | Navbar background, CTA buttons |
| Page Background | `#f0f0f0` | Body background |
| Card Background | `#ffffff` | Product card |
| Discount Badge | `#cc4444` | "38% OFF" text |
| Star Rating Gold | `#f5a623` | 5-star rating icons |
| Body Text | `#444444` | Product description |
| Muted Text | `#555555` | Brand name, review count |
| Strikethrough Price | `#888888` | Original price |
| Promo Box Background | `#f9f9f9` | Newsletter offer card |
| Border Colour | `#dddddd` | Promo box border |
| Thumbnail Border | `#cccccc` | Quantity selector border |

### Survey Form

| Role | Hex Code | Used In |
|---|---|---|
| Page Background (Teal) | `#9ED4C9` | Body background |
| Form Card | `#ffffff` | White form container |
| Label Text | `#333333` | All form labels |

---

## How to Run Locally

No build process. No installs. No terminal commands needed.

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# 2. Navigate into the folder
cd YOUR_REPO_NAME
```

Then simply **open either `.html` file directly in your browser**:

```bash
# macOS
open timeless-watches.html
open survey-form.html

# Windows
start timeless-watches.html
start survey-form.html

# Linux
xdg-open timeless-watches.html
xdg-open survey-form.html
```

Or drag and drop any `.html` file into a browser window.

> ⚠️ **Image Note:** The watch page requires `heroimg.jpeg`, `img1.jpeg`, `img2.jpeg`, `img3.jpeg`, `img5.jpeg`, and `img6.jpeg` to be present in the **same folder** as `timeless-watches.html`. Thumbnail 4 loads from Unsplash CDN and requires an internet connection.

---

## Author

**Your Name**
- 🐙 GitHub: [@your_username](https://github.com/your_username)
- 💼 LinkedIn: [your-profile](https://linkedin.com/in/your-profile)

---

> *Built with AI assistance (Claude by Anthropic). Directed, reviewed, iterated, and published by me.*