=== Softoria Plans ===

WordPress plugin for managing and displaying pricing plans with custom post type and [plans] shortcode.

== SCSS Build Instructions ==

This plugin uses SASS for CSS compilation. To build the styles:

1. Install Node.js and npm
2. Navigate to the plugin directory
3. Install dependencies: `npm install`
4. Compile SASS:
   - Development: `npm run sass`
   - Watch mode: `npm run sass:watch`
   - Production: `npm run sass:build`

Source files: `public/css/src/softoria-plans-public.scss`
Compiled files: `public/css/build/softoria-plans-public.css`
