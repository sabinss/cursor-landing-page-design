# Cursor Landing Page

A static recreation of the Cursor marketing landing page, built with HTML and CSS (Flexbox and Grid).

---

## Sections recreated

| Section             | Description                                                                                                            |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| **Header / Navbar** | Logo, nav links (Features, Enterprise, Pricing, Resources), Sign In and Download buttons                               |
| **Hero**            | Main headline, “Download for macOS” button, and product demo image area with gradient background                       |
| **Trusted by**      | “Trusted every day by millions…” line and a row of company cards (Stripe, OpenAI, Linear, etc.)                        |
| **Feature – Agent** | “Agent turns ideas into code” copy, “Learn about Agent” link, and feature screenshot                                   |
| **Feature – Tab**   | “Magically accurate autocomplete” block with GIF and “Learn about Tab” link                                            |
| **Feature cards**   | “The new way to build software” heading and a grid of testimonial/quote cards with avatars                             |
| **Use case**        | “Stay on the frontier” with three cards (models, codebase understanding, enterprise) and images                        |
| **Changelog**       | “Changelog” title, four version cards (date, optional version badge, description), and “See what’s new in Cursor” link |
| **Team / Careers**  | “Cursor is an applied team focused on building the future of coding”, “Join us” button, and team image                 |
| **CTA**             | “Try Cursor now.” heading and “Download for macOS” button                                                              |
| **Footer**          | Five columns: **Product**, **Resources**, **Company**, **Legal**, **Connect**, with link lists and optional copyright  |

---

## Fonts

- **Body / UI:** `Arial, Helvetica, sans-serif`  
  Used for all text across the page (no custom font files or Google Fonts).

---

## Colors

### CSS variables (in `:root`)

| Variable          | Hex       | Usage                                       |
| ----------------- | --------- | ------------------------------------------- |
| `--primary-color` | `#14120b` | Page background, nav, footer, dark surfaces |
| `--card-color`    | `#1b1913` | Cards, feature blocks, changelog cards      |

---

## Tech

- **HTML5** – Semantic sections, links, and lists.
- **CSS** – Flexbox (nav, hero, features, CTA, team block) and Grid (testimonial cards, changelog cards, footer columns).
- **Icons** – Optional: Font Awesome (CDN).

No build step or JavaScript required; open `index.html` in a browser to view.
