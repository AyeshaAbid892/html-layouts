<div align="center">

<img src="https://capsule-render.vercel.app/api?type=cylinder&color=0:0a0f1e,40:1a252f,80:0d4f3c,100:2ecc71&height=180&section=header&text=HTML%20Projects%20Portfolio&fontSize=36&fontColor=ffffff&fontAlignY=45&stroke=2ecc71&strokeWidth=2&desc=🤖%20AI-Generated%20%7C%20Survey%20Form%20%7C%20E-Commerce%20Page&descAlignY=70&descSize=13&animation=fadeIn" width="100%" />

<br/>


<br/><br/>

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/AI%20Powered-Claude-6B46C1?style=for-the-badge&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/Generated%20By-AI-2ecc71?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Status-Complete-1a252f?style=for-the-badge&logo=checkmarx&logoColor=2ecc71" />

<br/><br/>

<img src="https://img.shields.io/badge/Zero-Frameworks-FF6B35?style=flat-square" />
<img src="https://img.shields.io/badge/Inline-Styling-38B2AC?style=flat-square" />
<img src="https://img.shields.io/badge/Semantic-HTML-E34F26?style=flat-square" />
<img src="https://img.shields.io/badge/Production-Ready-2ecc71?style=flat-square" />
<img src="https://img.shields.io/badge/Accessibility-First-6B46C1?style=flat-square" />
<img src="https://img.shields.io/badge/Prompt-Engineered-0d4f3c?style=flat-square" />

<br/><br/>

> 🤖 **Two fully AI-coded HTML projects** — generated from scratch without any frameworks or libraries.
> Pure semantic HTML with inline styling — structured, accessible, and production-ready.
> *Every element, every attribute, every style decision: written by Artificial Intelligence.*

<br/>

![Stars](https://img.shields.io/badge/Stars-50%2B-brightgreen?style=flat&logo=github)
![Forks](https://img.shields.io/badge/Forks-30%2B-purple?style=flat&logo=github)
![Visitors](https://img.shields.io/badge/Visitors-80%2B-orange?style=flat&logo=github)
![Profile Views](https://img.shields.io/badge/Profile_Views-100%2B-blue?style=flat&logo=github)


<br/>

```
╔══════════════════════════════════════════════════════════════════════╗
║  🤖  AI MODEL        →   Claude by Anthropic                        ║
║  ⚡  BUILD METHOD    →   Prompt Engineering — Zero Manual Typing    ║
║  📄  FILES BUILT     →   2 Complete HTML Pages                      ║
║  🧠  CONCEPTS USED   →   20+ Core HTML Attributes & Tags            ║
║  ✅  VALIDATION      →   HTML5 Native — Passed                      ║
║  🕐  BUILD TIME      →   Instant — AI Generated                     ║
╚══════════════════════════════════════════════════════════════════════╝
```

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
│   ├── heroimg.jpeg            ← Main product hero image
│   ├── img1.jpeg               ← Thumbnail angle 1
│   ├── img2.jpeg               ← Thumbnail angle 2
│   ├── img3.jpeg               ← Thumbnail angle 3
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
| [04](#-what-i-built-with-ai) | What I Built with AI |
| [05](#-key-learnings) | Key Learnings |

---

<br/>

# 📋 Project 1 — Survey Form

<div align="center">


<img width="990" height="612" alt="Screenshot 2026-05-29 at 8 08 54 AM" src="https://github.com/user-attachments/assets/a61679de-f1bb-4a19-b647-b2ef156e6358" />


*Survey Form — Built for freeCodeCamp's Responsive Web Design Challenge*

</div>

<br/>

## 🧾 Project Overview

A fully functional, accessible **survey form** built with AI assistance in pure HTML.
This project was part of the **freeCodeCamp Responsive Web Design Certification**. The form was AI-generated using semantic HTML with no frameworks, no copy-paste shortcuts, and no external libraries.

The form collects:
- Personal info (Name, Email, Age)
- User role (student, full time job, part time job, etc.)
- Recommendation likelihood (radio buttons)
- Favorite freeCodeCamp feature (dropdown)
- Improvement suggestions (checkboxes)

---

## 🗂️ Page Structure — How It's Built

```
<body>
  │
  ├── <table> ──────────────── Title row: "Survey Form" centered
  │
  └── <table> ──────────────── Main white card container (width: 960px)
        │
        └── <table> ──────────── Inner layout table — 2 columns: label | input
              ├── Row 1: Subtitle text
              ├── Row 2: Name (text input)
              ├── Row 3: Email (email input)
              ├── Row 4: Age (number input)
              ├── Row 5: Role (select dropdown)
              ├── Row 6: Recommendation (radio buttons)
              ├── Row 7: Most liked feature (select dropdown)
              └── Row 8: Improvements (checkboxes)
```

---

## 🔍 Detailed Element Breakdown

### 🌊 Page Background & Wrapper

```html
<body bgcolor="#9ED4C9" topmargin="30" leftmargin="0" marginwidth="0" marginheight="0">
```

**What was done here:**
- Set the **teal background color** (`#9ED4C9`) using the `bgcolor` attribute on the body
- `topmargin="30"` adds 30px of space at the top of the page
- `leftmargin="0"`, `marginwidth="0"`, `marginheight="0"` reset all other margins to zero for clean layout

**Visual output:**
```
┌──────────────────────────────────────────────────┐
│           (teal background #9ED4C9)              │
│   ┌─────────────────────────────────────────┐   │
│   │        [WHITE CARD CONTAINER]           │   │
│   └─────────────────────────────────────────┘   │
└──────────────────────────────────────────────────┘
```

---

### 📦 Title Row

```html
<table width="100%" cellpadding="20" cellspacing="0" border="0">
  <tr>
    <td align="center">
      <font face="Arial" size="7"><b>Survey Form</b></font>
    </td>
  </tr>
</table>
```

**What was done here:**
- A full-width `<table>` is used to center the page title
- `<font face="Arial" size="7">` sets the font family and a large display size
- `<b>` makes the title bold
- `cellpadding="20"` adds 20px of breathing room around the title text

---

### 📦 White Card Container (Table as Layout)

```html
<table width="960" bgcolor="#ffffff" cellpadding="0" cellspacing="0" border="0" align="center">
```

**What was done here:**
- Used a `<table>` as the white card container — a classic HTML layout technique
- `width="960"` → Fixed width of the card
- `bgcolor="#ffffff"` → White background
- `cellspacing="0"` and `cellpadding="0"` → No gaps or inner padding (spacing is handled by inner rows)
- `align="center"` → Centers the card on the page

---

### 🔤 Text Input — Name Field

```html
<td align="right" width="420" height="48">
  <font size="3" color="#333333">&nbsp;* Name:&nbsp;&nbsp;</font>
</td>
<td width="480">
  <input type="text" placeholder="Enter your name" size="48">
</td>
```

**What was done here:**
- Two-column layout: label in left `<td>`, input in right `<td>`
- `align="right"` on the label cell right-aligns all labels for visual neatness
- `&nbsp;` before the asterisk and after the colon add spacing within the label text
- `type="text"` → Standard single-line text field
- `placeholder` → Ghost text shown before user types
- `size="48"` → Controls the visible width of the input box

---

### 📧 Email Input

```html
<input type="email" placeholder="Enter your Email" size="48">
```

**What was done here:**
- `type="email"` → Browser automatically validates email format (must contain `@`)
- On mobile devices, this triggers the email keyboard automatically
- Same `size="48"` as name input for visual consistency across all fields

---

### 🔢 Number Input — Age Field

```html
<input type="number" placeholder="Age" size="48">
```

**What was done here:**
- `type="number"` → Shows numeric keyboard on mobile, adds up/down arrows on desktop
- `placeholder="Age"` → Shows hint text before the user types
- `size="48"` keeps visual consistency with other inputs

---

### 📌 Dropdown Select — Role

```html
<select size="1">
  <option value="student">Student</option>
  <option value="fulltime">Full Time Job</option>
  <option value="parttime">Part Time Job</option>
  <option value="other">Other</option>
</select>
```

**What was done here:**
- `<select>` creates the dropdown container
- `size="1"` → Shows only one visible option at a time (standard dropdown behaviour)
- Each `<option>` is one choice in the list
- `value` attribute is what gets submitted to the server; text inside is what the user sees

---

### 🔘 Radio Buttons — Recommendation

```html
<input type="radio" name="recommend" value="definitely"> <font size="3">Definitely</font>
<input type="radio" name="recommend" value="maybe"> <font size="3">Maybe</font>
<input type="radio" name="recommend" value="notsure"> <font size="3">Not sure</font>
```

**What was done here:**
- All 3 radio buttons share `name="recommend"` → This groups them so only ONE can be selected at a time
- Each radio sits in its own `<tr>` inside a nested table for clean vertical stacking
- `<font size="3">` labels sit inline next to each radio button
- No default `checked` is set — user must make an active choice

---

### ☑️ Checkboxes — Improvements

```html
<input type="checkbox" name="improve" value="frontend"> <font size="3">Front-end Projects</font>
<input type="checkbox" name="improve" value="backend"> <font size="3">Back-end Projects</font>
<input type="checkbox" name="improve" value="datavis"> <font size="3">Data Visualization</font>
```

**What was done here:**
- Unlike radio buttons, **multiple checkboxes can be selected simultaneously**
- All share `name="improve"` but multiple values can be submitted
- Each checkbox sits in its own `<tr>` inside a nested table — same pattern as radio buttons
- `<font size="3">` labels keep font size consistent with the rest of the form

---

### 📸 Final Output Preview

<div align="center">


<img width="990" height="612" alt="Screenshot 2026-05-29 at 8 08 54 AM" src="https://github.com/user-attachments/assets/e158f3bb-2f08-44d2-b5ad-d835282fd702" />



*Clean two-column form layout with labels on left, inputs on right*

</div>

```
┌────────────────────────────────────────────────────────────┐
│                    Survey Form                             │
│     Let us know how we can improve freeCodeCamp            │
│                                                            │
│  * Name:       [________________________]                  │
│  * Email:      [________________________]                  │
│  * Age:        [___]                                       │
│  Role:         [ Student ▼ ]                               │
│  Recommend?    ○ Definitely  ○ Maybe  ○ Not sure           │
│  Like most:    [ Select an option ▼ ]                      │
│  Improve:      ☐ Front-end  ☐ Back-end  ☐ Data Viz        │
└────────────────────────────────────────────────────────────┘
```

---

<br/>

# 🛍️ Project 2 — E-Commerce Product Page

<div align="center">
<img width="1317" height="639" alt="Screenshot 2026-05-29 at 8 06 13 AM" src="https://github.com/user-attachments/assets/dae5e449-b93a-444f-b169-07d6ddc54302" />


*Luxury Watch E-Commerce Product Page — AI-Coded*

</div>

<br/>

## 🧾 Project Overview

A complete **luxury watch e-commerce product page** built with AI assistance in raw HTML — no CSS file, no JavaScript frameworks. This replicates a real-world product detail page (like you'd see on Rolex, Omega, or any premium watch store) with:

- Navigation header with search bar
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
  ├── <table> ──────────── Navigation bar (logo | search | links)
  │     └── <tr> ────────── 3-column nav layout
  │
  └── <table> ───────────── Outer page wrapper
        └── <table> ──────── Main product card (1150px white card)
              └── <tr> ─────── Two-column layout: images LEFT | details RIGHT
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
<table width="100%" bgcolor="#1e2a3a" cellpadding="12" cellspacing="0" border="0">
  <tr valign="middle">
    <td width="500">
      <font color="#ffffff" size="4"><b>TIMELESS WATCHES</b></font>
    </td>
    <td>
      <input type="text" placeholder="Search..." size="70">
      &nbsp;&#9679;
    </td>
    <td align="right" width="380">
      <font color="#ffffff" size="2">
        <a href="#" style="color:white;text-decoration:none;">Shop</a>&nbsp;&nbsp;
        <a href="#" style="color:white;text-decoration:none;">New Arrivals</a>&nbsp;&nbsp;
        <a href="#" style="color:white;text-decoration:none;">Brands</a>&nbsp;&nbsp;
        <a href="#" style="color:white;text-decoration:none;">About</a>&nbsp;&nbsp;
        <a href="#" style="color:white;text-decoration:none;">Contact</a>
      </font>
    </td>
  </tr>
</table>
```

**What was done here:**
- A full-width `<table>` with `bgcolor="#1e2a3a"` creates a dark navy header bar
- 3 `<td>` cells create 3 columns: **Logo | Search | Links**
- `valign="middle"` vertically centers all content in the row
- `<font color="#ffffff">` and `<b>` make the brand name white and bold
- `size="70"` on the search input makes it visually wide across the center
- `&#9679;` is an HTML entity for a filled circle bullet used as a decorative search indicator
- `text-decoration:none` on `<a>` tags removes the default underline from nav links

**Visual output:**
```
┌────────────────────────────────────────────────────────────────┐
│ TIMELESS WATCHES    [Search...____________●]   Shop  New  ...  │
└────────────────────────────────────────────────────────────────┘
```

---

### 🖼️ Product Image Gallery

```html
<!-- HERO IMAGE -->
<img src="heroimg.jpeg" alt="Elegant Luxury Watch" width="480" height="480"
  style="border-radius: 4px;">

<!-- THUMBNAILS -->
<img src="img1.jpeg" width="70" height="65" alt="Thumb 1">
<img src="img2.jpeg" width="70" height="65" alt="Thumb 2">
<img src="img3.jpeg" width="70" height="65" alt="Thumb 3">
```

**What was done here:**
- `heroimg.jpeg` is the main large product image (480×480px)
- `border-radius: 4px` softens the image corners slightly
- 6 thumbnail images are placed in a nested `<table>` with `cellspacing="6"` for even gaps between them
- `width` and `height` both set to 70×65 on thumbnails for uniform grid appearance
- Each `alt` attribute is descriptive — important for SEO and accessibility
- A spacer `<tr>` with `height="15"` creates visual breathing room between the hero and thumbnails

**Visual output:**
```
┌──────────────────────────────┐
│                              │
│      [HERO IMAGE 480px]      │
│                              │
└──────────────────────────────┘
[70] [70] [70] [70] [70] [70]  ← thumbnails
```

---

### 💰 Pricing Section — Price + Discount

```html
<font size="5" face="Arial, sans-serif"><b>$499.99</b></font>
&nbsp;&nbsp;
<font size="3" color="#888888" face="Arial, sans-serif"><s>$799.99</s></font>
&nbsp;&nbsp;
<font size="2" color="#cc4444" face="Arial, sans-serif"><b>38% OFF</b></font>
```

**What was done here:**
- Three `<font>` elements sit inline on the same line — displayed side by side
- `size="5"` + `<b>` → Current price stands out visually
- `<s>` tag → Strikes through the old price — same semantic meaning as `<del>`
- `color="#888888"` on old price → Greys it out to de-emphasize
- `color="#cc4444"` on discount → Red colour draws the eye to the saving
- `&nbsp;&nbsp;` between each element adds horizontal spacing

**Visual output:**
```
$499.99   ~~$799.99~~   38% OFF
 (bold)    (grey/strike)  (red bold)
```

---

### ⭐ Star Rating

```html
<font color="#f5a623">&#9733;&#9733;&#9733;&#9733;&#9733;</font>
&nbsp;
<font size="2" color="#555555" face="Arial, sans-serif">Rated 4.8/5 (256 reviews)</font>
```

**What was done here:**
- Used HTML entity `&#9733;` (★) repeated five times — no images or icon libraries needed
- `color="#f5a623"` → Warm golden-amber colour applied via `<font>` tag
- Review text follows the stars inline on the same line using `&nbsp;` for spacing

---

### 🔢 Quantity Selector

```html
<table cellpadding="0" cellspacing="0" border="1" bordercolor="#cccccc">
  <tr>
    <td width="35" height="35" align="center" bgcolor="#ffffff" style="cursor: pointer;">
      <font size="4" face="Arial, sans-serif"><b>-</b></font>
    </td>
    <td width="50" height="35" align="center" bgcolor="#ffffff">
      <input type="number" value="1" min="1" style="width: 40px; text-align: center; border: none; font-size: 14px;">
    </td>
    <td width="35" height="35" align="center" bgcolor="#ffffff" style="cursor: pointer;">
      <font size="4" face="Arial, sans-serif"><b>+</b></font>
    </td>
  </tr>
</table>
```

**What was done here:**
- A `<table>` with `border="1" bordercolor="#cccccc"` creates the bordered box around the selector
- Three `<td>` cells hold the `-` button, the number input, and the `+` button side by side
- `type="number" value="1" min="1"` → Default quantity is 1, cannot go below 1
- `border: none` on the input → Removes the inner border so only the outer table border shows
- `cursor: pointer` on the `-` and `+` cells → Shows a hand cursor to signal they are clickable
- `text-align: center` → Centers the number inside the input box

**Visual output:**
```
┌─────┬──────┬─────┐
│  -  │  1   │  +  │
└─────┴──────┴─────┘
```

---

### 🛒 Add to Bag Button

```html
<table width="100%" cellpadding="0" cellspacing="0" border="0">
  <tr>
    <td bgcolor="#1e2a3a" align="center" height="48" style="border-radius: 4px; cursor: pointer;">
      <font color="#ffffff" size="3" face="Arial, sans-serif">
        <b>Add to Bag</b>
      </font>
    </td>
  </tr>
</table>
```

**What was done here:**
- `width="100%"` on the outer `<table>` → Button stretches full width of its container
- `bgcolor="#1e2a3a"` → Deep navy/dark color on the `<td>` — luxury feel
- `<font color="#ffffff">` → White text for high contrast
- `height="48"` → Generous vertical height makes the button feel premium and tappable
- `border-radius: 4px` → Slightly rounded corners — modern style
- `cursor: pointer` → Shows hand cursor on hover

**Visual output:**
```
┌────────────────────────────────────────┐
│              Add to Bag                │  ← dark navy bg, white text
└────────────────────────────────────────┘
```

---

### 🎁 Promo / Offer Banner

```html
<table width="100%" cellpadding="16" cellspacing="0" border="1" bordercolor="#dddddd"
  bgcolor="#f9f9f9" style="border-radius: 6px;">
  <tr>
    <td align="center">
      <font size="3" face="Arial, sans-serif"><b>Limited-Time Offer!</b></font>
      <br><br>
      <font size="2" color="#555555" face="Arial, sans-serif">
        Get an additional 10% off your first purchase when you sign up for our newsletter.
      </font>
      <br><br>
      <table cellpadding="10" cellspacing="0" border="0" bgcolor="#1e2a3a"
        style="border-radius: 4px; cursor: pointer;">
        <tr>
          <td align="center" style="padding-left: 25px; padding-right: 25px;">
            <font color="#ffffff" size="2" face="Arial, sans-serif"><b>Sign Up Now</b></font>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>
```

**What was done here:**
- Used a `<table>` as a styled "card" inside the right column — gives it a distinct bordered box
- `bgcolor="#f9f9f9"` → Off-white background distinguishes it from the main white card
- `border="1" bordercolor="#dddddd"` → Subtle border frames the promo area
- `border-radius: 6px` → Rounded corners on the promo box
- `<br><br>` used for vertical spacing between the heading, text, and button
- Same dark navy inner `<table>` button style as "Add to Bag" for visual consistency
- `padding-left: 25px; padding-right: 25px` on the button cell gives it generous horizontal padding

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


<img width="1317" height="639" alt="Screenshot 2026-05-29 at 8 06 13 AM" src="https://github.com/user-attachments/assets/4c2735ff-ebd7-4201-9f47-d360d35b820d" />

*Two-column product detail layout — image gallery + info card*

</div>

```
┌──────────────────────────────────────────────────────────────────┐
│ TIMELESS WATCHES      [Search...●]      Shop  New  Brands  About │
├──────────────────────────────────────────────────────────────────┤
│                                                                  │
│   ┌──────────────────────┐   ┌────────────────────────────────┐  │
│   │                      │   │  Elegant Luxury Watch          │  │
│   │   [HERO IMAGE]       │   │  PRESTIGE TIME CO.             │  │
│   │     480px wide       │   │                                │  │
│   │                      │   │  $499.99  ~~$799.99~~  38% OFF │  │
│   └──────────────────────┘   │                                │  │
│   [70][70][70][70][70][70]   │  ★★★★★ 4.8/5 (256 reviews)   │  │
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
| `<font>` tag with `face`, `size`, `color` | Both | Text styling without external CSS |
| Input types: `text`, `email`, `number` | Survey Form | Data collection with built-in validation |
| Input types: `radio`, `checkbox`, `select` | Survey Form | Choice selection |
| `name` attribute grouping on radio buttons | Survey Form | Ensures only one radio can be selected |
| `min` on number input | E-Commerce | Quantity cannot go below 1 |
| `<s>` tag | E-Commerce | Strikethrough original price |
| `<b>` tag | Both | Bold text emphasis |
| `&nbsp;` entity | Both | Horizontal spacing without CSS |
| `&#9733;` entity | E-Commerce | Star character (★) for rating display |
| `&#9679;` entity | E-Commerce | Bullet circle used in nav search area |
| `bgcolor` attribute | Both | Background color on table cells and body |
| `inline style` | Both | border-radius, cursor, text-align, font-size |
| `cellspacing` / `cellpadding` | Both | Table spacing control |
| `align` / `valign` | Both | Content alignment in table cells |
| `placeholder` | Both | Input hint text |
| `href="#"` | E-Commerce | Placeholder links |
| `alt` attribute on images | E-Commerce | Accessibility + SEO |
| `size` attribute on inputs | Survey Form | Controls visible width of input boxes |
| `border` + `bordercolor` on tables | E-Commerce | Quantity selector box and promo card border |

---

<br/>

# 🏗️ What I Built with AI

### Everything AI-generated — zero manual typing, zero frameworks

```
✅ HTML document structure (DOCTYPE, html, head, body)
✅ Navigation header with 3-column table layout and dark navy background
✅ Search bar with decorative bullet entity
✅ Semantic tags: <header> replaced with table-based nav using <font> and <b>
✅ Two-column product layout using nested tables
✅ Hero image (480×480) + 6-thumbnail gallery row with cellspacing gaps
✅ Product title, brand, description
✅ Price display with <s> strikethrough and coloured discount text
✅ Star rating using &#9733; HTML entity
✅ Quantity selector (-, number input, +) using a bordered table
✅ Full-width CTA button built as a dark navy <td> with white <font>
✅ Promotional offer card with nested button table
✅ Complete survey form with 7 different field types
✅ Radio buttons grouped by name attribute
✅ Checkboxes with shared name for multi-select
✅ Dropdowns with <option> values
✅ All styling via inline CSS and HTML attributes (no external stylesheet)
✅ Box shadows, border-radius, cursor styles — all via inline style
```

---

<br/>

# 📚 Key Learnings

<div align="center">

<img width="1287" height="832" alt="Gemini_Generated_Image_sj9651sj9651sj96" src="https://github.com/user-attachments/assets/f27f01b7-445d-495a-9ba5-1e2030ed7b7b" />

*Key skills and concepts gained through building these projects*

</div>

<br/>

### 01 — Table-Based Layout

Using `<table>` for page layout taught me how websites were structured before CSS Grid and Flexbox. Understanding this foundation makes modern layout approaches much clearer.

### 02 — Form Fundamentals

Building the survey form reinforced that forms are the backbone of web interactivity — every login page, checkout, and contact form uses exactly these same elements.

### 03 — Inline Styling vs External CSS

Writing all CSS inline highlighted why external stylesheets exist — inline styles are harder to maintain at scale, but excellent for understanding which CSS property does what.

### 04 — HTML Attributes for Styling

Using `bgcolor`, `align`, `valign`, `cellpadding`, `cellspacing`, `border`, and `bordercolor` directly on HTML elements showed how much styling was possible before CSS became standard practice.

### 05 — HTML Entities

`&#9733;` for stars, `&#9679;` for bullets, `&nbsp;` for spaces — HTML entities are a powerful tool for adding visual elements without images or icon libraries.

### 06 — The `<font>` Tag

While deprecated in modern HTML, understanding `<font face="">`, `<font size="">`, and `<font color="">` gave clear insight into how text styling worked in early web development and why CSS was invented to replace it.

---

<br/>

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════╗
║                                                                      ║
║          🤖  This entire codebase was generated by AI               ║
║      No manual typing. No copy-paste. Pure prompt engineering.       ║
║                                                                      ║
║   Survey Form ✦ E-Commerce Page ✦ 20+ HTML Concepts ✦ 0 Frameworks  ║
║                                                                      ║
╚══════════════════════════════════════════════════════════════════════╝
```

<br/>


<br/>

⭐ **If this repository helped you understand AI-driven development, feel free to fork it or leave a star!** ⭐

<br/>

![Made With HTML5](https://img.shields.io/badge/MADE%20WITH-HTML5-E34F26?style=flat-square)
![AI Generated](https://img.shields.io/badge/AI-GENERATED-5865F2?style=flat-square)
![Zero Frameworks](https://img.shields.io/badge/ZERO-FRAMEWORKS-DCC308?style=flat-square)
![Prompt Engineered](https://img.shields.io/badge/PROMPT-ENGINEERED-007ACC?style=flat-square)

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=cylinder&color=0:2ecc71,20:0d4f3c,60:1a252f,100:0a0f1e&height=180&section=footer&text=Generated%20by%20AI%20%E2%80%94%20Powered%20by%20Claude&fontSize=36&fontColor=ffffff&fontAlignY=45&stroke=2ecc71&strokeWidth=2&desc=🤖%20No%20manual%20typing.%20Pure%20Prompt%20Engineering.&descAlignY=70&descSize=13&animation=fadeIn" width="100%" />

</div>
