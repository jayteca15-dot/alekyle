# AleKyle Connect — Multi‑Service Business Website

A professional, responsive multi‑page website for **AleKyle Connect**, showcasing four service lines:

- Shuttle service (point‑to‑point transport)
- Courier service (Pretoria, Friday–Sunday)
- Party & event decorations (gallery placeholders for your images)
- Teacher mentorship (online)

This project is designed as a clean portfolio piece for employers: modern UI, strong branding, mobile‑first layout, and clear user flows.

---

## Live Pages

- `home.html` — Home / overview
- `index.html` — Shuttle service
- `courier.html` — Courier service
- `decor.html` — Party & event decor
- `mentor.html` — Teacher mentorship

---

## Key Features

- **Multi‑page site** with consistent navigation and footer
- **Mobile responsive** layout (Tailwind via CDN)
- **Premium UI**: gradients, glass effects, modern cards, hover states
- **Clickable images**:
  - Gallery lightbox where applicable
  - Image zoom / open‑full features
- **WhatsApp + Email hybrid booking** on service pages
  - WhatsApp opens with a **pre‑filled message** relevant to the service
  - Email forms submit to **Web3Forms**
- **Auto‑updating year** in the footer

---

## Tech Stack

- HTML5
- Tailwind CSS (CDN)
- Font Awesome (icons)
- Vanilla JavaScript
- Web3Forms (form handling)

---

## Forms (Web3Forms)

Email forms post to **Web3Forms**.

If you fork this project, you should replace the Web3Forms access key with your own:

1. Create an access key at https://web3forms.com
2. Update the `access_key` hidden field value in each form.

> Note: The site is front‑end only; the access key is visible in the HTML (this is normal for Web3Forms). For production, protect the key by restricting allowed domains in your Web3Forms dashboard.

---

## Images

### Decor page gallery placeholders
The decor page expects 13 images you can add later:

- `1.jpeg` to `13.jpeg` (place in the same folder as the HTML files)

If you don’t add them yet, the placeholders will still render the layout.

---

## Getting Started (Local)

Because this is a static site, you can open files directly, but running a local server is recommended.

### Option A: VS Code Live Server
1. Install the **Live Server** extension
2. Right‑click `home.html` → **Open with Live Server**

### Option B: Python (built‑in)
From the project folder:

```bash
python -m http.server 5500
```

Then open:

- http://localhost:5500/home.html

---

## Deploy on GitHub Pages

1. Push the project to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: `main` (or your default) and `/root`
4. Save.

Your site will be published at the GitHub Pages URL.

---

## Project Structure

```text
.
├── home.html
├── index.html
├── courier.html
├── decor.html
├── mentor.html
└── README.md
```

---

## Contact

Business contact details are included in the site footer:

- Phone: +27 76 907 9104
- Alt phone: +27 67 725 3057
- Email: altheawilliams3@gmail.com
- Email: alistairdavids@gmail.com

---

## License

If you want to open‑source this, add a license file (MIT is common). Otherwise, you can keep it private or proprietary.
