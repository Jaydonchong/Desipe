# Desipe

Desipe is a static design system builder for exploring color palettes, typography, spacing, themes, and responsive page previews.

The Builder page shows a landing page or blog article preview. The Components page shows reusable interface patterns styled with the same design tokens.

Preview at:  https://desipe.pages.dev

## Run locally

Serve this folder with any static file server.

## Deploy to Cloudflare Pages

Deploy this folder as Cloudflare Pages static assets with no build command.

Desipe has no backend or build step. It includes 20 locally bundled WOFF2 font files for use without Google Fonts. Google Fonts are still included in copied CSS exports. Each bundled family has its own license notice in `fonts/licenses/`.

## Share and export

The builder writes its complete configuration to the `system` query parameter as controls change. A blank URL creates a randomized design system; shared URLs restore their saved settings.

Use the copy icon at the right end of the floating action bar to copy CSS tokens, including the Google Fonts import.
