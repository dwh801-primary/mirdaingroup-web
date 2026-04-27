# Mirdain Group - Corporate Web Gateway

**Repository:** `mirdaingroup-web`
**Status:** SECURE // ACTIVE
**System Location:** Salt Lake City, UT

## // OVERVIEW
This repository contains the static HTML and CSS architecture for the Mirdain Group LLC corporate landing page and privacy policy. While operating independently of the core Dart/Firebase architecture of our flagship application, **Handshake**, this web gateway serves as the public-facing entry point to our trust protocols and must adhere to our highest engineering and design standards.

## // DESIGN SYSTEM Adherence
This codebase strictly implements the **Neo-Legal Dark Mode v1.1.0** specification:
* **Backgrounds:** Void Black (`#0A0A0A`)
* **Surfaces/Text:** Carbon Grey (`#A0A0A0`) / High-Contrast System Text (`#8E8E93`)
* **Accents & Actions:** Mint Legal Green (`#00E676`)
* **Typography:** * `Inter` for conversational/UI elements.
  * `Space Mono` for cryptographic data, system text, and headers.

## // ARCHITECTURE & PERFORMANCE
Following the April 2026 diagnostic review, the codebase has been optimized for:
* **Performance:** Eliminated render-blocking resources by utilizing direct `<link rel="preconnect">` tags for Google Fonts.
* **Accessibility (a11y):** Implemented semantic `<main>` HTML5 landmarks and achieved strict WCAG 4.5:1 contrast ratios for all foreground/background pairings.
* **SEO:** Integrated comprehensive meta descriptions for accurate search engine indexing.

## // FILE STRUCTURE
* `/index.html` - Primary corporate landing page.
* `/privacy.html` - Mirdain Group and Handshake application privacy policy.
* `/README.md` - Repository documentation.

## // DEPLOYMENT
This is a strictly static environment requiring no build processes or backend compilation. It is ready for immediate deployment to any standard static hosting environment or CDN infrastructure.

---
*For internal engineering inquiries or protocol updates, initiate contact via secure channel: info@mirdaingroup.com*
