# Changelog

## [v0.0.5] - 2026-02-02

### Changed
- **Navigation:** Updated desktop and mobile menus to prioritize 'Features' before 'How It Works'.
- **UI:** Updated CTA buttons to be 'rounded-full' with consistent styling across hero and menus.
- **Assets:** Moved `og-image` files to `favicon/` directory for cleaner structure.
- **SEO/Social:** Added cache busting (`?v=0.1`) to Open Graph image URLs.

### Fixed
- **Menu Visibility:** Resolved CSS conflict hiding desktop menu items.
- **Mobile Menu:** Fixed interactivity issues by implementing global event delegation in `Sidebar.js`.
- **URL Handling:** Added client-side redirect to enforce trailing slash for consistent asset loading (`/notet` -> `/notet/`).

## [v0.0.4] - 2026-01-29

### Added
- **Analytics:** Integrated Umami Analytics tracking code.
- **Environment config:** Added `.env` file for managing sensitive configuration (excluded from git).
- **SEO & Social:** 
    - Enhanced Open Graph meta tags (added image dimensions and type).
    - Added Twitter Card meta tags (including `twitter:domain`).
    - Updated references to "Twitter / X".

## [v0.0.3] - 2026-01-22

### Added
- **Client-Side Routing:** Implemented a simple router to handle navigation between the landing page and the notes app without page reloads.
- **History API Support:** Added support for browser back/forward buttons.

### Changed
- **URL Structure:** Cleaned up URLs to be cleaner (e.g., `/notet` instead of `/notet/notes.html`).
- **Page Consolidation:** Merged `notes.html` functionality into `index.html` as a SPA.
- **Landing Page:** Optimized CTA buttons and hero section layout.

### Removed
- **Legacy Files:** Deleted `notes.html` as it is no longer needed.

## [v0.0.2] - 2025-12-26

(Previous changes...)
