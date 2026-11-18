# Developers

The theme source is the private repository `matthummel-pa/wp-acreline`. It is a Sage 11 theme (Blade, Tailwind CSS v4, Vite, Acorn). This docs repository has no PHP.

## Layout

- `app/` — PHP modules (settings, updater, content types)
- `resources/views/` — Blade templates
- `resources/css/` and `resources/js/` — front-end source
- `public/build/` — compiled assets, created by the build, not committed
- `plugins/acreline-demo-bar/` — concept-demo purchase bar only; not in the buyer zip

## Freemius

`functions.php` calls the Freemius SDK with empty product id, public key, and plan id constants until those values exist. Do not commit a secret key or an API token. Plan shape, when filled in, is one annual plan with license counts of 1, 5, and unlimited at $59.99, $99.99, and $199.99. See [License and updates](license-and-updates.md).

Filters used by the theme:

- `acreline/freemius_enabled` — return false to keep the SDK off
- `acreline/show_github_updater` — return true to show the author GitHub updater even when Freemius is on

## Build

From the theme directory: install Composer and npm dependencies, then `npm run build`. Without that build, the front end cannot find the Vite manifest.

## Text domain

User-facing strings use the text domain `acreline`.
