# 🌯 Steezy's Panenka — Restaurant Website

A fast, mobile-first website for a South African street food spot in Potchefstroom. Customers browse the menu, customise their order with extras, and get sent straight to WhatsApp to complete the order — no app, no account, no friction.

**Live site:** [steezyspanenka.co.za](https://steezyspanenka.co.za)

---

## What It Does

- Full menu display with pricing in ZAR (R26–R85)
- Click any menu item → modal pops up → customer adds extras → one tap sends a pre-filled WhatsApp order to the business
- Floating WhatsApp button for direct ordering at any point
- Location, hours, and contact info section
- Google-indexable via JSON-LD structured data (Restaurant schema)
- Open Graph tags for clean WhatsApp/social link previews

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, Vanilla JavaScript |
| Fonts | Google Fonts (Montserrat, Poppins) |
| Icons | Font Awesome 6 |
| Hosting | Custom domain (steezyspanenka.co.za) |
| Orders | WhatsApp API (wa.me deep link) |

No backend. No database. No dependencies to install.

---

## Key Features

**WhatsApp ordering flow** — clicking a menu card opens a branded modal where the customer can add extras (cheese, bacon, riblets, etc.). On confirm, the app builds a pre-filled message and opens `wa.me` with it. The business receives a clean, structured order on WhatsApp instantly.

**SEO & discoverability** — includes a full `application/ld+json` Restaurant schema block with address, phone, hours, price range, and cuisine type. This feeds Google's rich results and local search.

**Zero-dependency ordering** — the entire order flow runs in ~50 lines of vanilla JS. No frameworks, no build step, no backend costs.

---

## Local Setup

```bash
# Clone the repo
git clone https://github.com/your-username/steezys-panenka.git
cd steezys-panenka

# No build step — just open the file
open index.html

# Or serve locally
npx serve .
```

---

## Project Structure

```
/
└── index.html    # Everything — markup, styles, and logic in one file
```

---

## Screenshots

> *(Add screenshots here — hero, menu grid, order modal, mobile view)*

---

## Built By

[BBA Media](https://bbamedia.co.za) — Web design agency based in Johannesburg, South Africa.

---

## What It Does

- Full menu display with pricing in ZAR (R26–R85)
- Click any menu item → modal pops up → customer adds extras → one tap sends a pre-filled WhatsApp order to the business
- Floating WhatsApp button for direct ordering at any point
- Location, hours, and contact info section
- Google-indexable via JSON-LD structured data (Restaurant schema)
- Open Graph tags for clean WhatsApp/social link previews

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, Vanilla JavaScript |
| Fonts | Google Fonts (Montserrat, Poppins) |
| Icons | Font Awesome 6 |
| Hosting | Custom domain (steezyspanenka.co.za) |
| Orders | WhatsApp API (wa.me deep link) |

No backend. No database. No dependencies to install.

---

## Key Features

**WhatsApp ordering flow** — clicking a menu card opens a branded modal where the customer can add extras (cheese, bacon, riblets, etc.). On confirm, the app builds a pre-filled message and opens `wa.me` with it. The business receives a clean, structured order on WhatsApp instantly.

**SEO & discoverability** — includes a full `application/ld+json` Restaurant schema block with address, phone, hours, price range, and cuisine type. This feeds Google's rich results and local search.

**Zero-dependency ordering** — the entire order flow runs in ~50 lines of vanilla JS. No frameworks, no build step, no backend costs.

---

## Local Setup

```bash
# Clone the repo
git clone https://github.com/your-username/steezys-panenka.git
cd steezys-panenka

# No build step — just open the file
open index.html

# Or serve locally
npx serve .
```

---

## Project Structure

```
/
└── index.html    # Everything — markup, styles, and logic in one file
```

---

## Screenshots

> *(Add screenshots here — hero, menu grid, order modal, mobile view)*

<img width="617" height="912" alt="image" src="https://github.com/user-attachments/assets/deaf4990-a764-4656-b5b1-162a77b3989c" />

<img width="572" height="884" alt="image" src="https://github.com/user-attachments/assets/c671b730-1b84-49b7-9536-5604ee902ccc" />
<img width="592" height="917" alt="image" src="https://github.com/user-attachments/assets/23cb3cbd-afd8-4b2e-919d-b11b3f49aa32" />
<img width="533" height="515" alt="image" src="https://github.com/user-attachments/assets/253d6862-ecd4-4930-a887-bfd745a8163f" />

## Built By

[BBA Media](https://bbamedia.co.za) — Web design agency based in Johannesburg, South Africa.
