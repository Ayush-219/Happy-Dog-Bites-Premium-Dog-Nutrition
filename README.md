# Happy Dog Bites — Product Page

A clean, responsive product landing page for **Happy Dog Bites**, a premium dog nutrition brand. Built from a Figma design (Product page - POD - CS Shopify Test) using plain HTML and CSS — no frameworks, no dependencies.

---

## 📁 Project Structure

```
project/
├── index.html       # Main HTML file
├── style.css        # All styles
├── README.md        # This file
└── images/          # Add your local images here (optional)
    ├── bowl.jpg
    ├── dog-product.jpg
    ├── dachshunds.jpg
    └── kibble.jpg
```

---

## 🖥️ Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | **What Makes Us Different** | 3-column layout with bowl image, 4 feature cards, CTA button, and payment icons |
| 2 | **Nutrition is the Foundation** | Stats (97%, 84%, 92%), key points, and product image |
| 3 | **Gastrointestinal Health** | Reversed two-column layout with image and body copy |
| 4 | **Prebiotics** | Text + close-up kibble image with rounded corners |

---

## 🚀 Getting Started

### 1. Clone or Download
Download the project files and place them in a folder on your computer.

### 2. Open in Browser
Simply open `index.html` in any modern browser — no build step or server required.

```bash
# Or serve locally with VS Code Live Server, or:
npx serve .
```

### 3. Use Local Images (Recommended)
The page currently uses Unsplash URLs. To use your own photos:

1. Create an `images/` folder next to `index.html`
2. Add your photos (JPG or PNG)
3. In `index.html`, replace each `src="https://..."` with `src="images/your-photo.jpg"`

---

## 🎨 Customization

### Colors
All colors are defined as CSS variables at the top of `style.css`:

```css
:root {
  --orange:       #e8633a;   /* Primary button & accent color */
  --orange-hover: #d4522b;   /* Button hover state */
  --ink:          #1a1a1a;   /* Headings */
  --ink-muted:    #6b6b6b;   /* Body text */
  --bg:           #ffffff;   /* White sections */
  --bg-alt:       #f9f9f9;   /* Light grey sections */
}
```

### Fonts
The page uses **Manrope** loaded from Google Fonts. To change it:
1. Replace the `<link>` in `index.html` with your preferred Google Font
2. Update `--font` in `style.css`

### Button Text
Search for `btn-primary` in `index.html` and update the link text and `href="#"` to your actual URL.

---

## 📱 Responsive Breakpoints

| Breakpoint | Behavior |
|------------|----------|
| `> 900px`  | Full desktop layout — multi-column grids |
| `≤ 900px`  | Single column, bowl image moves to top |
| `≤ 600px`  | Compact padding, smaller font sizes, stacked trust row |

---

## 🛠️ Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, CSS Grid, Flexbox, `clamp()` for fluid type
- **Google Fonts** — Manrope (400, 500, 600, 700, 800)
- **No JavaScript** — Fully static, no dependencies

---

## 🖼️ Image Sources

Current placeholder images are from [Unsplash](https://unsplash.com) (free to use). Replace them with your actual product photos for production use.

To download the placeholders:
1. Copy the `src` URL from any `<img>` tag in `index.html`
2. Paste into your browser → right-click → **Save image as**
3. Place in your `images/` folder and update the `src`

---

## 📄 License

This project is for internal/client use. All copy and brand assets belong to **Happy Dog Bites**. Placeholder images are from Unsplash and subject to the [Unsplash License](https://unsplash.com/license).
