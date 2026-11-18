# Troubleshooting

## “Vite manifest not found”

The theme cannot find `public/build`. The installable zip includes that folder. A raw copy of the private source repository does not, until someone runs the theme build. Install `acreline.zip` from your receipt, not a Git clone.

## The homepage looks like the old sample copy

Page content lives in WordPress. Replacing theme files does not rewrite pages, listings, or agents. Edit those in wp-admin. The concept demo is updated on its host separately from a theme release.

## A template edit does not show

WordPress caches compiled templates. After a theme update this clears itself. On a development copy, clear the Acorn view cache from the host (the theme’s WP-CLI command `wp acorn view:clear`).

## Showing form does nothing

Confirm the site is using the Acreline theme (`get_template()` is `acreline`) and that the page includes the form. Submissions create **Bookings** posts. Check that list before looking for an email. Mail depends on the host.

## Styles look unstyled after an update

Hard-refresh the browser. If a cache plugin is active, purge it. The CSS file name changes when the theme is rebuilt.

## License screen is missing

The account screen appears after the Freemius product id and public key are set on that copy of the theme. An empty id leaves the screen off on purpose. Author installs keep using **Appearance → Update Theme**. See [License and updates](license-and-updates.md).

## Demo bar on a site you bought

Remove the **Acreline demo bar** plugin if it was ever copied onto a buyer site. It is only for [acreline.matthummel.com](https://acreline.matthummel.com/). The theme’s fiction banner is part of the concept content, not the purchase bar.
