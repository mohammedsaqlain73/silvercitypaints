# Silvercity Paints & Construction – Business Website

**Live URL:** [https://silvercitypaintsandsupply.netlify.app](https://silvercitypaintsandsupply.netlify.app)

A complete, mobile‑friendly business website for **Silvercity Paints & Construction Solutions** – a one‑stop supplier of automotive paints, primers, sundries, and construction chemicals in Cuttack & Bhubaneswar, Odisha.

 ![Website Preview](https://raw.githubusercontent.com/mohammedsaqlain73/silvercitypaints/main/preview.jpg) 
*(Replace with an actual screenshot from your live site)*

---

## About the Business

Silvercity serves:
- **Automotive** workshops & garages (ASPA/PPG paints, thinners, hardeners, fillers)
- **Sundries** (masking tape, brushes, rollers, sandpaper)
- **Construction** (waterproofing, tile adhesives, wall putty, grouts)

**Owner:** Mohammed Karamat Alli  
**Location:** Brahmana Jharilo, Cuttack, Odisha – 754001  
**Phone:** 78150 49345 / 93489 86726

---

## Features

- 📱 **Fully responsive** – works perfectly on desktop, tablet, and mobile.
- 🎨 **Product catalogue** – divided into three divisions (Automotive, Sundries, Construction) with category tabs and live division filters.
- 🔧 **Partner garages page** – lists trusted body shops in Cuttack & BBSR with ratings, tags, and direct call/directions.
- 💬 **WhatsApp ordering** – every product has a “Order via WhatsApp” button, plus a dedicated Order page.
- 🌐 **Bilingual** – English / ଓଡ଼ିଆ (Odia) toggle.
- 🧭 **Bottom navigation** – quick access to Home, Products, Garages, Order, Contact.
- 🖼️ **Image placeholders** – products without images show a stylish placeholder; you can add your own photos easily.
- ⚡ **Same‑day delivery** – order before 11am, delivered by 3pm (within 30km of Cuttack).

---

## Tech Stack

- **HTML5** – semantic structure
- **CSS3** – custom properties, flexbox, grid, animations
- **Vanilla JavaScript** – no frameworks, no build step
- **Google Fonts** – Oswald (headings) & Inter (body)
- **Font Icons** – emojis + SVG icons (no external icon library)
- **Hosting** – [Netlify](https://www.netlify.com/) (static site)

---

## Editing the Website

All content is stored in **one HTML file** (`index.html`). To edit:

### 1. Change phone numbers / WhatsApp number
Search for `919348986726` (country code + number) and replace with your own. Also edit the `tel:` links and the visible number strings (e.g., `93489 86726`).

### 2. Update products
Locate the `PRODUCTS` array (inside the `<script>` tag). Each product object looks like:
```js
{ d:'Automotive', c:'Thinners', n:'NC Thinner', u:'Per litre', s:'in', img:'images/nc-thinner.jpg' }
