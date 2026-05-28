<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a252f,100:2ecc71&height=200&section=header&text=HTML%20Projects%20Portfolio&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Survey%20Form%20%7C%20E-Commerce%20Product%20Page&descAlignY=58&descSize=16&animation=fadeIn" width="100%" />

<br/>

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/Responsive-Design-38B2AC?style=for-the-badge&logo=google-chrome&logoColor=white" />
<img src="https://img.shields.io/badge/Manual-Code-FF6B35?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
<img src="https://img.shields.io/badge/Status-Complete-2ecc71?style=for-the-badge" />

<br/><br/>

> **Two fully hand-coded HTML projects** built from scratch without any frameworks or libraries.
> Pure semantic HTML with inline styling — structured, accessible, and production-ready.

<br/>

[![GitHub Stars](https://img.shields.io/github/stars/yourusername/html-projects?style=social)](https://github.com)
[![GitHub Forks](https://img.shields.io/github/forks/yourusername/html-projects?style=social)](https://github.com)
[![Visitors](https://visitor-badge.laobi.icu/badge?page_id=html-projects)](https://github.com)

</div>

---

## 📁 Repository Structure

```
html-projects/
│
├── 📄 survey-form/
│   └── index.html              ← freeCodeCamp Survey Form
│
├── 📄 ecommerce-page/
│   ├── index.html              ← Luxury Watch Product Page
│   ├── heroo.jpeg              ← Main product hero image
│   ├── img1.jpeg               ← Thumbnail angle 1
│   ├── img2.jpeg               ← Thumbnail angle 2
│   ├── img3.jpeg               ← Thumbnail angle 3
│   ├── img4.jpeg               ← Thumbnail angle 4
│   ├── img5.jpeg               ← Thumbnail angle 5
│   └── img6.jpeg               ← Thumbnail angle 6
│
└── 📄 README.md                ← You are here
```

---

## 📋 Table of Contents

| # | Section |
|---|---------|
| [01](#-project-1--survey-form) | Project 1 — Survey Form |
| [02](#-project-2--e-commerce-product-page) | Project 2 — E-Commerce Product Page |
| [03](#-html-concepts-used) | HTML Concepts Used |
| [04](#-what-i-built-manually) | What I Built Manually |
| [05](#-key-learnings) | Key Learnings |

---

<br/>

# 📋 Project 1 — Survey Form

<div align="center">

![Survey Form Preview](https://images.unsplash.com/photo-1586281380349-632531db7ed4?w=900&q=80&auto=format&fit=crop)
*Survey Form — Built for freeCodeCamp's Responsive Web Design Challenge*

</div>

<br/>

## 🧾 Project Overview

A fully functional, accessible **survey form** built manually in pure HTML.
This project was part of the **freeCodeCamp Responsive Web Design Certification**. Every single line of code was written by hand — no copy-paste, no frameworks, no shortcuts.

The form collects:
- Personal info (Name, Email, Age)
- User role (student, job, learner, etc.)
- Recommendation likelihood (radio buttons)
- Favorite freeCodeCamp feature (dropdown)
- Improvement suggestions (checkboxes)

---

## 🗂️ Page Structure — How It's Built

```
<body>
  │
  ├── <h1> ─────────────── Page Title: "Survey Form"
  │
  └── <table> ──────────── Main white card container (width: 1050px)
        │
        └── <form> ──────── Wraps all inputs (action="/submit-survey" method="POST")
              │
              └── <table> ── Inner layout table — 2 columns: label | input
                    ├── Row 1: Name (text input)
                    ├── Row 2: Email (email input)
                    ├── Row 3: Age (number input)
                    ├── Row 4: Role (select dropdown)
                    ├── Row 5: Recommendation (radio buttons)
                    ├── Row 6: Most liked feature (select dropdown)
                    └── Row 7: Improvements (checkboxes)
```

---

## 🔍 Detailed Element Breakdown

### 🌊 Page Background & Wrapper

```html
<body bgcolor="#a2dad2" style="font-family: Arial, sans-serif; margin: 0; padding: 40px 10px;">
```

**What I did here:**
- Set the **teal background color** (`#a2dad2`) using the `bgcolor` attribute on the body
- Applied `font-family`, `margin: 0`, and `padding` using the `style` attribute
- The `padding: 40px 10px` adds breathing room — 40px top/bottom, 10px left/right

**Visual output:**
```
┌──────────────────────────────────────────────────┐
│           (teal background #a2dad2)              │
│   ┌─────────────────────────────────────────┐   │
│   │        [WHITE CARD CONTAINER]           │   │
│   └─────────────────────────────────────────┘   │
└──────────────────────────────────────────────────┘
```

---

### 📦 White Card Container (Table as Layout)

```html
<table width="1050px" bgcolor="#ffffff" cellspacing="0" cellpadding="40"
  align="center" style="border-radius: 5px; box-shadow: 0px 2px 10px rgba(0,0,0,0.05);">
```

**What I did here:**
- Used a `<table>` as the white card container — a classic HTML layout technique
- `width="1050px"` → Fixed width of the card
- `bgcolor="#ffffff"` → White background
- `cellspacing="0"` → No gaps between cells
- `cellpadding="40"` → 40px inner padding on all sides
- `align="center"` → Centers the card on the page
- `box-shadow` → Adds a subtle drop shadow for depth

---

### 📝 The Form Tag

```html
<form action="/submit-survey" method="POST">
```

**What I did here:**
- `action="/submit-survey"` → Where form data gets sent on submit
- `method="POST"` → Sends data securely in request body (not in URL)
- Wraps ALL input fields — required for form submission to work

---

### 🔤 Text Input — Name Field

```html
<label for="name">* Name:</label>
<input type="text" id="name" placeholder="Enter your name" required
  style="width: 350px; padding: 6px; border: 1px solid #cccccc; border-radius: 3px;">
```

**What I did here:**
- `<label for="name">` → Linked to input via matching `id="name"` — accessibility best practice
- `type="text"` → Standard single-line text field
- `placeholder` → Ghost text shown before user types
- `required` → HTML5 built-in validation — form won't submit if empty
- `width: 350px` → Consistent input width across all fields

---

### 📧 Email Input

```html
<input type="email" id="email" placeholder="Enter your Email" required
  style="width: 350px; padding: 6px; border: 1px solid #cccccc; border-radius: 3px;">
```

**What I did here:**
- `type="email"` → Browser automatically validates email format (must contain `@`)
- On mobile devices, this triggers the email keyboard automatically
- `required` → Cannot be left blank on submit

---

### 🔢 Number Input — Age Field

```html
<input type="number" id="age" placeholder="Age" min="1" max="120" required
  style="width: 350px; padding: 6px; border: 1px solid #cccccc; border-radius: 3px;">
```

**What I did here:**
- `type="number"` → Shows numeric keyboard on mobile, adds up/down arrows on desktop
- `min="1" max="120"` → HTML5 built-in range validation — no scripts needed
- Browser rejects values outside this range automatically

---

### 📌 Dropdown Select — Role

```html
<select id="role" style="width: 140px; padding: 5px; border: 1px solid #cccccc;
  border-radius: 3px; background-color: #efefef;">
  <option value="student">Student</option>
  <option value="job">Full Time Job</option>
  <option value="learner">Full Time Learner</option>
  <option value="preferNo">Prefer not to say</option>
  <option value="other">Other</option>
</select>
```

**What I did here:**
- `<select>` creates the dropdown container
- Each `<option>` is one choice in the list
- `value` attribute is what gets submitted to server; text inside is what user sees
- `background-color: #efefef` → Light grey to distinguish it from plain inputs

---

### 🔘 Radio Buttons — Recommendation

```html
<input type="radio" id="recom-definitely" name="recommendation" value="definitely" checked>
<label for="recom-definitely">Definitely</label>

<input type="radio" id="recom-maybe" name="recommendation" value="maybe">
<label for="recom-maybe">Maybe</label>
```

**What I did here:**
- All 3 radio buttons share `name="recommendation"` → This groups them so only ONE can be selected at a time
- `checked` on the first option → Pre-selects "Definitely" as the default
- Each radio has a unique `id` that matches its `<label for="...">` — clicking the label also selects the radio

---

### ☑️ Checkboxes — Improvements

```html
<input type="checkbox" id="imp-frontend" name="improvement" value="frontend">
<label for="imp-frontend">Front-end Projects</label>

<input type="checkbox" id="imp-backend" name="improvement" value="backend">
<label for="imp-backend">Back-end Projects</label>
```

**What I did here:**
- Unlike radio buttons, **multiple checkboxes can be selected simultaneously**
- Same `name="improvement"` but multiple can be checked
- Used `<br><br>` for vertical spacing between checkboxes — a straightforward HTML spacing technique

---

### 📸 Final Output Preview

<div align="center">

![Form Structure](https://images.unsplash.com/photo-1611532736597-de2d4265fba3?w=800&q=80&auto=format&fit=crop)
*Clean two-column form layout with labels on left, inputs on right*

</div>

```
┌────────────────────────────────────────────────────────────┐
│               Survey Form                                  │
│     Let us know how we can improve freeCodeCamp            │
│                                                            │
│  * Name:       [________________________]                  │
│  * Email:      [________________________]                  │
│  * Age:        [___]                                       │
│  Role:         [ Student ▼ ]                               │
│  Recommend?    ⦿ Definitely  ○ Maybe  ○ Not sure           │
│  Like most:    [ Select an option ▼ ]                      │
│  Improve:      ☐ Front-end  ☐ Back-end  ☐ Data Viz        │
└────────────────────────────────────────────────────────────┘
```

---

<br/>

# 🛍️ Project 2 — E-Commerce Product Page

<div align="center">

![E-Commerce Preview](https://images.unsplash.com/photo-1523275335684-37898b6baf30?w=900&q=80&auto=format&fit=crop)
*Luxury Watch E-Commerce Product Page — Fully Hand-Coded*

</div>

<br/>

## 🧾 Project Overview

A complete **luxury watch e-commerce product page** built entirely in raw HTML — no CSS file, no JavaScript frameworks. This replicates a real-world product detail page (like you'd see on Rolex, Omega, or any premium watch store) with:

- Navigation header with search
- Full product image gallery (hero + 6 thumbnails)
- Pricing with discount and strike-through
- Star ratings
- Quantity selector
- Add to Bag button
- Limited-time offer promo section

---

## 🗂️ Page Structure — How It's Built

```
<body>
  │
  ├── <header> ─────────── Navigation bar (logo | search | links)
  │     └── <table> ────── 3-column nav layout
  │
  ├── <hr> ──────────────── Visual divider line
  │
  └── <main> ───────────── Outer page wrapper
        └── <table> ─────── Main product card (1150px white card)
              └── <table> ── Two-column layout: images LEFT | details RIGHT
                    ├── LEFT TD: Hero image + 6 thumbnail images
                    └── RIGHT TD: Product info card table
                          ├── Title + Brand
                          ├── Price + Discount
                          ├── Description
                          ├── Star Rating
                          ├── Quantity Selector
                          ├── Add to Bag Button
                          └── Promo Banner Table
```

---

## 🔍 Detailed Element Breakdown

### 🧭 Navigation Header

```html
<header>
  <table width="100%" cellspacing="0" cellpadding="10">
    <tr>
      <td align="left">
        <strong>TIMELESS WATCHES</strong>
      </td>
      <td align="center">
        <input type="text" placeholder="Search..." size="60">
        <button type="button">🔍</button>
      </td>
      <td align="right">
        <a href="#">Shop</a> &nbsp;&nbsp;
        <a href="#">New Arrivals</a> &nbsp;&nbsp;
      </td>
    </tr>
  </table>
</header>
```

**What I did here:**
- Used `<header>` semantic tag — tells browser this is the page header
- A `<table>` with 3 `<td>` cells creates 3 columns: **Logo | Search | Links**
- `align="left"`, `align="center"`, `align="right"` distributes each section
- `<strong>` makes the brand name bold without needing CSS
- `&nbsp;&nbsp;` are HTML entities for spacing between nav links
- `size="60"` on the search input makes it visually wide

**Visual output:**
```
┌────────────────────────────────────────────────────────────┐
│ TIMELESS WATCHES    [Search...____________🔍]   Shop  New  │
└────────────────────────────────────────────────────────────┘
```

---

### 🖼️ Product Image Gallery

```html
<!-- HERO IMAGE -->
<img src="heroo.jpeg" alt="Elegant Luxury Watch Featured View Profile"
  width="512" style="display: block; border-radius: 4px;">

<!-- THUMBNAILS -->
<img src="img1.jpeg" alt="Angle Perspective 1" width="74"> &nbsp;
<img src="img2.jpeg" alt="Angle Perspective 2" width="70"> &nbsp;
<img src="img3.jpeg" alt="Angle Perspective 3" width="70"> &nbsp;
```

**What I did here:**
- `heroo.jpeg` is the main large product image (512px wide)
- `display: block` removes default inline spacing below images
- `border-radius: 4px` softens the image corners slightly
- 6 thumbnail images are placed inline with `&nbsp;` spacing between them
- Each `alt` attribute is descriptive — important for SEO and accessibility
- Different `width` values (70–75px) are used for thumbnails to fit neatly in one row

**Visual output:**
```
┌──────────────────────────────┐
│                              │
│      [HERO IMAGE 512px]      │
│                              │
└──────────────────────────────┘
[74] [70] [70] [75] [70] [70]  ← thumbnails
```

---

### 💰 Pricing Section — Price + Discount

```html
<h3>
  <span style="font-size: 1.45em;"><strong>$499.99</strong></span> &nbsp;&nbsp;
  <span style="color: #999999; font-weight: normal;"><del>$799.99</del></span> &nbsp;&nbsp;
  <span style="color: #d9534f; font-weight: bold;">38% OFF</span>
</h3>
```

**What I did here:**
- Three `<span>` elements inside one `<h3>` — inline elements sitting side-by-side
- `<strong>` + larger `font-size` → Current price stands out visually
- `<del>` tag → Strikes through the old price — semantic HTML for deleted/crossed-out text
- `color: #999999` on old price → Greys it out to de-emphasize
- `color: #d9534f` on discount → Bootstrap-style red, draws the eye

**Visual output:**
```
$499.99   ~~$799.99~~   38% OFF
 (bold)    (grey/strike)  (red bold)
```

---

### ⭐ Star Rating

```html
<p style="font-size: 0.95em;">
  <span style="color: #ffcc00;">⭐⭐⭐⭐⭐</span> &nbsp; Rated 4.8/5 (256 reviews)
</p>
```

**What I did here:**
- Used Unicode emoji stars (`⭐`) — no images or icon libraries needed
- `color: #ffcc00` → Golden yellow color applied via inline style
- Text "Rated 4.8/5 (256 reviews)" follows the stars inline on same line

---

### 🔢 Quantity Selector

```html
<div>
  <button type="button" style="padding: 6px 14px;">-</button>
  <input type="text" value="1" size="2" style="text-align: center; padding: 5px; border: 1px solid #ccc;">
  <button type="button" style="padding: 6px 12px;">+</button>
</div>
```

**What I did here:**
- Three elements placed inline: `[-]` button, text input showing quantity, `[+]` button
- `type="button"` → Prevents accidental form submission
- `value="1"` → Default quantity is 1
- `size="2"` → Makes the input box small (about 2 characters wide)
- `text-align: center` → Centers the "1" inside the input box
- No JavaScript added — these buttons are visual only (pure HTML implementation)

**Visual output:**
```
[ - ]  [ 1 ]  [ + ]
```

---

### 🛒 Add to Bag Button

```html
<button type="button" style="width: 100%; padding: 14px;
  background-color: #1a252f; color: white; border: none;
  font-weight: bold; font-size: 1em; cursor: pointer; border-radius: 4px;">
  Add to Bag
</button>
```

**What I did here:**
- `width: 100%` → Button stretches full width of its container
- `background-color: #1a252f` → Deep navy/dark color — luxury feel
- `color: white` → White text for contrast
- `border: none` → Removes the default browser button border
- `cursor: pointer` → Shows hand cursor on hover — tells user it's clickable
- `border-radius: 4px` → Slightly rounded corners — modern style
- `padding: 14px` → Generous vertical padding makes the button feel premium

**Visual output:**
```
┌────────────────────────────────────────┐
│              Add to Bag                │  ← dark navy bg, white text
└────────────────────────────────────────┘
```

---

### 🎁 Promo / Offer Banner

```html
<table width="100%" bgcolor="#f9f9f9" cellspacing="0" cellpadding="15"
  style="border: 1px solid #e5e5e5; border-radius: 6px;">
  <tr>
    <td align="center">
      <h4 style="margin-top: 0;">Limited-Time Offer!</h4>
      <p style="font-size: 0.9em; color: #555555; margin-bottom: 12px;">
        Get an additional 10% off your first purchase when you sign up for our newsletter.
      </p>
      <button type="button" style="padding: 8px 20px; background-color: #1a252f;
        color: white; border: none; cursor: pointer; border-radius: 4px;">
        Sign Up Now
      </button>
    </td>
  </tr>
</table>
```

**What I did here:**
- Used a `<table>` as a styled "card" inside the right column — gives it a distinct bordered box
- `bgcolor="#f9f9f9"` → Off-white background distinguishes it from the main white card
- `border: 1px solid #e5e5e5` → Subtle border frames the promo area
- `border-radius: 6px` → Rounded corners on the promo box
- `margin-top: 0` on `<h4>` → Removes extra spacing at top of heading
- Same dark navy button style as "Add to Bag" for visual consistency

**Visual output:**
```
┌──────────────────────────────────────┐
│         Limited-Time Offer!          │
│  Get an additional 10% off your      │
│  first purchase when you sign up.    │
│         [ Sign Up Now ]              │
└──────────────────────────────────────┘
```

---

### 📸 Final Output Preview

<div align="center">

![Product Page Layout](https://images.unsplash.com/photo-1517245386807-bb43f82c33c4?w=900&q=80&auto=format&fit=crop)
*Two-column product detail layout — image gallery + info card*

</div>

```
┌──────────────────────────────────────────────────────────────────┐
│ TIMELESS WATCHES      [Search...🔍]      Shop  New  Brands  About│
├──────────────────────────────────────────────────────────────────┤
│                                                                  │
│   ┌──────────────────────┐   ┌────────────────────────────────┐  │
│   │                      │   │  Elegant Luxury Watch          │  │
│   │   [HERO IMAGE]       │   │  PRESTIGE TIME CO.             │  │
│   │     512px wide       │   │                                │  │
│   │                      │   │  $499.99  ~~$799.99~~  38% OFF │  │
│   └──────────────────────┘   │                                │  │
│   [74][70][70][75][70][70]   │  ⭐⭐⭐⭐⭐ 4.8/5 (256 reviews) │  │
│   ← 6 thumbnails →          │                                │  │
│                              │  [-] [1] [+]                   │  │
│                              │  [     Add to Bag     ]        │  │
│                              │  ┌──────────────────────────┐  │  │
│                              │  │   Limited-Time Offer!    │  │  │
│                              │  │   [ Sign Up Now ]        │  │  │
│                              │  └──────────────────────────┘  │  │
│                              └────────────────────────────────┘  │
└──────────────────────────────────────────────────────────────────┘
```

---

<br/>

# 🧠 HTML Concepts Used

<div align="center">

![HTML Concepts](https://images.unsplash.com/photo-1542831371-29b0f74f9713?w=900&q=80&auto=format&fit=crop)
*Core HTML concepts applied throughout both projects*

</div>

<br/>

| Concept | Used In | How It Was Used |
|---------|---------|-----------------|
| `<table>` layout | Both | Page structure, form layout, product card |
| Semantic tags `<header>`, `<main>`, `<form>` | Both | Meaningful page structure |
| Input types: `text`, `email`, `number` | Survey Form | Data collection with built-in validation |
| Input types: `radio`, `checkbox`, `select` | Survey Form | Choice selection |
| `required` attribute | Survey Form | HTML5 client-side validation |
| `min` / `max` on number input | Survey Form | Age range restriction |
| `<label for="">` + `id` linking | Survey Form | Accessibility — click label = focus input |
| `<del>` tag | E-Commerce | Strikethrough original price |
| `<strong>` tag | Both | Bold text with semantic importance |
| `&nbsp;` entity | Both | Horizontal spacing without CSS |
| `bgcolor` attribute | Survey Form | Background color on table/body |
| `inline style` | Both | All CSS applied directly in HTML |
| `cellspacing` / `cellpadding` | Both | Table spacing control |
| `align` / `valign` | Both | Content alignment in table cells |
| `placeholder` | Both | Input hint text |
| `action` + `method` on `<form>` | Survey Form | Form submission target and method |
| `href="#"` | E-Commerce | Placeholder links |
| `alt` attribute on images | E-Commerce | Accessibility + SEO |
| Unicode emoji | E-Commerce | Stars ⭐ and search 🔍 without icon libs |

---

<br/>

# 🏗️ What I Built Manually

### Everything written by hand — zero generators, zero frameworks

```
✅ HTML document structure (DOCTYPE, html, head, body)
✅ Navigation header with 3-column table layout
✅ Search bar with search button
✅ Semantic tags: <header>, <main>, <form>, <strong>, <del>
✅ Two-column product layout using nested tables
✅ Hero image + 6-thumbnail gallery row
✅ Product title, brand, description
✅ Price display with discount and strike-through
✅ Star rating using Unicode emoji
✅ Quantity selector (-, input, +)
✅ Full-width CTA button with hover cursor
✅ Promotional offer card
✅ Complete survey form with 7 different field types
✅ HTML5 form validation (required, min, max, type)
✅ Label-to-input accessibility linking (for + id)
✅ All styling via inline CSS (no external stylesheet)
✅ Box shadows, border-radius, colors — all manual
```

---

<br/>

# 📚 Key Learnings

<div align="center">

![Learnings](https://images.unsplash.com/photo-1456513080510-7bf3a84b82f8?w=900&q=80&auto=format&fit=crop)
*Key skills and concepts gained through building these projects*

</div>

<br/>

### 01 — Table-Based Layout

Using `<table>` for page layout taught me how websites were structured before CSS Grid and Flexbox. Understanding this foundation makes modern layout approaches much clearer.

### 02 — Form Fundamentals

Building the survey form from scratch reinforced that forms are the backbone of web interactivity — every login page, checkout, and contact form uses exactly these same elements.

### 03 — Inline Styling vs External CSS

Writing all CSS inline highlighted why external stylesheets exist — inline styles are harder to maintain at scale, but excellent for understanding which CSS property does what.

### 04 — Semantic HTML Matters

Using `<header>`, `<main>`, `<form>`, `<strong>`, and `<del>` instead of plain `<div>` everywhere gave me a clear understanding of why semantics improve SEO and accessibility.

### 05 — HTML5 Native Validation

`required`, `min`, `max`, `type="email"` — these do real validation work before any JavaScript. This means safer forms with less code.

### 06 — The `<label for="">` + `id` Link

Connecting labels to inputs is not just good practice — it's what makes forms work properly on mobile and with screen readers. Clicking the label focuses the input.

---

<br/>
## Author

**Your Name**
- 🐙 GitHub: [@your_username](https://github.com/your_username)
- 💼 LinkedIn: [your-profile](https://linkedin.com/in/your-profile)

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2ecc71,100:1a252f&height=120&section=footer&text=Built%20with%20Pure%20HTML&fontSize=24&fontColor=ffffff&fontAlignY=65&animation=fadeIn" width="100%" />

<br/>

**If this helped you, please give it a ⭐ — it means a lot!**

<br/>

![Made with HTML](https://img.shields.io/badge/Made%20with-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![No Frameworks](https://img.shields.io/badge/Zero-Frameworks-1a252f?style=for-the-badge&logo=html5&logoColor=white)
![Manual Code](https://img.shields.io/badge/100%25-Manual%20Code-2ecc71?style=for-the-badge)

</div>
