# MSJ Homepage

A bilingual website with English as the primary language and Chinese as the secondary language.

## Features

- **Bilingual Support**: English (primary) and Chinese (secondary) language options
- **Language Persistence**: User's language preference is saved in localStorage
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Modern UI**: Glass morphism effects and smooth animations
- **Single Page Navigation**: Navigation between pages without opening new tabs

## Files Structure

- `index.html` - Main homepage with MSJ branding and language switcher
- `function.html` - Function area page
- `favicon-16.png` - 16x16 favicon
- `favicon-32.png` - 32x32 favicon
- `_redirects` - Cloudflare Pages redirect configuration

## Deployment

This project is designed for Cloudflare Pages deployment. The `_redirects` file ensures proper routing for single-page application behavior.

### Cloudflare Pages Deployment Steps:

1. Push your code to a Git repository (GitHub, GitLab, etc.)
2. Connect your repository to Cloudflare Pages
3. Set the build command to empty (since this is a static site)
4. Set the build output directory to `msj-homepage`
5. Deploy

## Language Switching

- Click the language buttons (EN/中文) in the top-right corner to switch languages
- The language preference is automatically saved and restored on subsequent visits
- English is set as the default language

## Browser Compatibility

- Modern browsers with CSS Grid and Flexbox support
- Requires JavaScript for language switching functionality
- Compatible with Cloudflare Pages hosting
