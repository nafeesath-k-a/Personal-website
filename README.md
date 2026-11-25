# Personal Website — Nafeesath K A

Source files for my personal academic website and study notes.

- **Live site:** https://nafeesath-k-a.github.io/Personal-website/
- **Blogger mirror:** https://nafeesath-k-a.github.io/Personal-website/ (main site)
- **Contact:** hs26d001@iittp.ac.in

---

## What's in this repository

| File | What it is |
|---|---|
| `index.html` | Landing page — About Me, Education & CV, Publications, Research, Resources & Notes, Contact (single-page, tabbed). |
| `Lasi_beginners_guide.html` | Standalone guide: *A Beginner's Guide to Working with LASI Data*. |
| `nafeesath.jpg` | Profile photo used in the sidebar. |
| `README.md` | This file. |

The site is plain HTML + CSS + a small amount of vanilla JavaScript.
No build step, no framework, no dependencies. Open any `.html` file in a
browser and it renders exactly as it does on GitHub Pages.

---

## About the LASI guide

**What is LASI?**
The **Longitudinal Ageing Study in India** is a nationally representative,
multi-wave survey of adults aged 45 and above. It tracks health, cognition,
work, household composition, and economic wellbeing over time, and is India's
counterpart to the HRS family of surveys (HRS, SHARE, CHARLS). It is the main
source for studying ageing in India.

**What the guide is.**
A walk-through for students getting started with the data: how to request and
download it, how the survey design and codebooks are organised, and the first
steps in Stata and R. It is a living document — sections, figures, and worked
examples are added as I go. It is a personal set of notes, not a formal manual
or an official LASI publication.

**Data use.**
LASI data are owned by the IIPS / LASI team and are used only under their
data-use agreement. **Nothing in this repository redistributes the data.**

---

## Credits

- The **layout and chapter structure** of the LASI guide are inspired by
  Danielle Navarro's [*Learning Statistics with R*](https://learningstatisticswithr.com/),
  and in particular its
  [regression chapter](https://learningstatisticswithr.com/15-regression.html).
  It is an exceptionally clear model for teaching statistical workflows, and
  any errors in my adaptation are mine.
- Fonts: [Source Serif 4](https://fonts.google.com/specimen/Source+Serif+4),
  [Source Sans 3](https://fonts.google.com/specimen/Source+Sans+3), and
  [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono), via
  Google Fonts.
- Everything else (text, code, design decisions) is my own created with the help of AI.

---

## Running locally

No setup required. Either:

1. Clone the repo and open `index.html` in a browser, **or**
2. Serve it locally:

```bash
git clone https://github.com/nafeesath-k-a/Personal-website.git
cd Personal-website
python3 -m http.server 8000
# then open http://localhost:8000
