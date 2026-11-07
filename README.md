# ROBO .PK | Karachi Lines — Water-Morphism Website

A modern, responsive one-page marketing website for **ROBO .PK | Karachi Lines**, a Karachi-based
electronics/automation business that sells and installs **automatic water-pump control systems**
(sensor-based motor controllers, water-level sensors, submersible dry-run protection and WiFi/app
motor automation).

The site is built in a **water-morphism / glassmorphism** visual style: frosted-glass cards,
drifting liquid blobs, rising bubbles, soft gradients, blur effects and scroll-reveal animations.

---

## Live preview

The site is a single static `index.html` — open it directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

---

## Repository structure

```
robo-pk-water-morphism/
├── index.html                     # The complete one-page website (HTML + CSS + JS, self-contained)
├── images/                        # Product images used by the site (9 JPEGs)
│   ├── product_1.jpg              # Water Sensor Drive Unit (referenced photo)
│   ├── product_2.jpg
│   ├── product_3.jpg
│   ├── product_4.jpg
│   ├── product_5.jpg
│   ├── product_6.jpg
│   ├── product_7.jpg
│   ├── product_8.jpg
│   └── product_9.jpg
├── data/                          # Scraped Facebook page data + audit
│   ├── robo_pk_posts.csv          # 20 recent posts: date, format, plays, shares, reactions, caption, hashtags
│   ├── robo_pk_summary.csv        # Page-level summary metrics
│   └── robo_pk_summary_report.html# Full audit report (health score, strengths, weaknesses, recommendations)
└── README.md
```

---

## Website sections

| Section | What it contains |
|---|---|
| **Hero** | Business name, tagline, primary CTAs, WiFi-controller visual and key stats |
| **About** | The business story (automation since 1998) and an info panel |
| **Products** | Product cards with the 9 product images from the Facebook page |
| **Why choose us** | Six feature cards (sensors, dry-run protection, WiFi control, experience, installation, no manual ON/OFF) |
| **Contact** | Phone numbers, WhatsApp link and service area |
| **Footer** | Brand, data-source note and copyright |

---

## Scraped data & audit summary

- **Page:** ROBO .PK | Karachi Lines (Facebook Page ID `61552661620882`)
- **Category:** Electronics Company · **Verification:** No
- **Followers:** 91 · **Talking about this:** 204
- **Posting cadence:** ~2.55 posts/week (20 most recent posts analysed)
- **Content mix:** ~60% short product-demo videos/Reels, ~40% product photos
- **Engagement:** 525 total shares across 20 posts (avg 26.2); 32 total reactions
- **Health score:** 54/100 (Grade C — Developing)

**Strengths:** clear narrow niche · video-first cadence · strong share behaviour · consistent posting ·
bilingual (Roman-Urdu + English) problem→solution copy.

**Weaknesses:** small audience · no public comments · incomplete profile (no website/email/address,
not verified) · repetitive creative & hashtags · phone-number-only funnel.

**Top recommendations:** convert shares→followers with a pinned "start here" post + follow CTA ·
complete the business profile & get verified · add a comment-driving question to every Reel ·
double down on the winning suction-pump/sensor topics · test Friday/Sunday slots · build a real
funnel (WhatsApp link, price card, lead form) · paid-boost best Reels · diversify creative/hashtags ·
evolve into a trusted local service brand.

---

## Data source & disclosure

- **Source:** public Facebook page HTML (crawler user-agent fetch) + the `lookaside.fbsbx.com`
  crawler media endpoint. **Collection date: 2026-11-07.**
- **Actually retrieved:** page name, ID, category, about/tagline, followers (91), "talking about this"
  (204), verification status, phone, the 20 most recent posts (permalinks, dates, format, video plays,
  shares, reactions, captions, hashtags) and 9 product images.
- **Not retrieved / estimated:** page *likes* (Facebook shows followers only), comment counts,
  reach/impressions, audience demographics, growth trend, and posts older than the ~20 most recent.
  The 32.4% engagement-per-post figure is a derived estimate inflated by non-follower shares —
  directional only. **No metric was invented.**

---

## Tech

- Pure **HTML + CSS + vanilla JavaScript** — no build step, no dependencies.
- Responsive layout (mobile → desktop), CSS custom properties, `backdrop-filter` glass effects,
  keyframe animations and `IntersectionObserver` scroll reveals.

---

## Notes on assets

The product images in this repository are **web-optimised copies** (max 384 px, JPEG q55) so the
repo stays lightweight; the cards render at ~300 px on desktop. Full-resolution originals remain
with the business.

---

## Usage

Product images and business details belong to **ROBO .PK | Karachi Lines**. The site code is provided
for the business's own use. Please do not reuse the product photography without permission.
