# Discover Kigali — Travel & City Guide Website

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

> A multi-page travel and city guide website showcasing Kigali, Rwanda — built as an HTML & CSS class project.

**Live Demo:** https://visit-kigali-omega.vercel.app/

---

## Table of Contents

- [Features](#features)
- [HTML Pages Included](#html-pages-included)
- [What This Project Demonstrates](#what-this-project-demonstrates)
- [Design Concept](#design-concept)
- [Media Features](#media-features)
- [How to Run](#how-to-run)
- [Student Information](#student-information)

---

## Features

- **Multi-page navigation** — five linked HTML pages with a consistent sticky header and active-link highlighting
- **Hero banners** — each page opens with a full-screen background image driven by a CSS custom property (`--hero`)
- **Destination cards** — grid-based article cards with images, category tags, descriptions, and call-to-action buttons
- **Click-to-play video thumbnails** — YouTube embeds shown as poster images that load the iframe only after the visitor clicks, keeping the page fast
- **Embedded audio player** — a native `<audio>` element with browser controls for background Rwandan music
- **Photo galleries** — `<figure>` and `<figcaption>` grids on multiple pages
- **Data table** — a structured facts table for transport, food, and visitor behavior on the home page; an events and hours table on the KCC page
- **Ordered and unordered lists** — used throughout for guides, itinerary steps, and food information
- **Newsletter signup form** — collects first name, last name, email, interest selection, and a message
- **Embedded Google Maps** — location maps on the home page and memorial page
- **Flexbox and CSS Grid layouts** — used for cards, galleries, split sections, and the navigation bar
- **Responsive design** — a media query at 850 px collapses the layout for narrower screens
- **Internal and external links** — in-page anchors (`#plan`, `#places`) alongside links to official tourism sites
- **Kigali Midnight & Gold theme** — a consistent dark-navy and brushed-gold color palette across all five pages

---

## HTML Pages Included

| File | Page Title | Description |
|------|-----------|-------------|
| `index.html` | Home | Overview of Kigali with destination cards, a planning guide, photo gallery, two video embeds, an audio player, a quick facts table, a signup form, and a map |
| `kcc.html` | Kigali Convention Centre | Highlights the KCC dome, nearby hotels and dining, an events table, and a photo gallery |
| `nyamirambo.html` | Nyamirambo | Showcases the neighborhood with a guided walk itinerary, local tips, and an image gallery |
| `cuisine.html` | Rwandan Cuisine | Covers traditional dishes, a detailed dish card grid, Kimironko Market information, and a Rwandan music video embed |
| `memorial.html` | Kigali Genocide Memorial | Provides respectful educational information, visitor guidance, a photo gallery, and a location map |

---

## What This Project Demonstrates

- Correct semantic HTML page structure (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<figure>`)
- Multi-page website architecture with shared navigation
- CSS custom properties (variables) used for the hero background images and the site color palette
- Flexbox and CSS Grid for card grids, split layouts, and navigation
- Images embedded with `<img>` and `<figure>` / `<figcaption>`
- YouTube video integration using click-to-play thumbnail wrappers around `<iframe>` embeds
- Native `<audio>` element with browser controls
- Google Maps embedded with `<iframe>`
- HTML tables with `<thead>` and `<tbody>` for structured visitor data
- Ordered (`<ol>`) and unordered (`<ul>`) lists for guides and feature sets
- A `<form>` using `<input>`, `<select>`, `<textarea>`, and `<button>` elements
- Internal anchor links and external links with `target="_blank"` and `rel="noopener"`
- Responsive layout using a media query breakpoint at 850 px
- One external CSS file per HTML page

---

## Design Concept

The website uses a custom visual theme called **"Kigali Midnight & Gold"**:

- **Background:** Clean light tones (`#F8F9FA`) for comfortable readability
- **Navigation:** Dark midnight (`#0F1419`) for a modern, elegant header
- **Accent color:** Brushed gold (`#C5A059`) for buttons, tags, hover states, and the play button on video thumbnails
- **Hover interactions:** Smooth color transitions and subtle scale effects

The theme is meant to reflect **Modern Kigali** — a clean, growing city that is vibrant by day and striking at night.

---

## Media Features

- High-quality images of Kigali landmarks, food, and neighborhoods sourced from Wikimedia Commons and Visit Rwanda
- Two YouTube video embeds on the home page (official Visit Rwanda tourism video and a 4K city timelapse), both displayed with poster thumbnails
- One YouTube music playlist embed on the cuisine page, also displayed with a thumbnail
- A native `<audio>` element on the home page for a traditional Rwandan music track
- Two Google Maps embeds (home page and memorial page)

---

## How to Run

1. Download or clone the repository
2. Open the project folder
3. Open `index.html` directly in a browser **or** use the Live Server extension in VS Code for the best experience

No build tools, frameworks, or dependencies are required — this is a pure HTML and CSS project.

---

## Student Information

**Name:** Honnete Nishimwe  
**Course:** Frontend — HTML & CSS Project

---

*This project reflects both technical skills and creativity in designing a real-world travel website, and demonstrates a solid understanding of HTML and CSS fundamentals while presenting Kigali as a beautiful and welcoming destination.*
