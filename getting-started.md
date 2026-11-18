# Getting started

Acreline is a WordPress theme. You install it like any other theme: **Appearance → Themes → Add New Theme → Upload Theme**, then choose `acreline.zip` and activate it.

Requirements: WordPress 6.6 or newer, PHP 8.3 or newer. The zip already contains compiled CSS and JavaScript and the PHP libraries the theme needs. You do not run Composer or npm on the host.

## Before you upload

1. Buy from [matthummel.com/shop](https://matthummel.com/shop/) or [matthummel.com/product/acreline/](https://matthummel.com/product/acreline/). Checkout is the Freemius window on that page. See [License and updates](license-and-updates.md).
2. Download `acreline.zip` from the receipt or from **Appearance → Acreline** after the license is active. Upload that zip. Do not upload a seller pack or a “demo bar” zip into WordPress.
3. Optional: `acreline-child.zip` if you want a child theme, and `acreline-core.zip` if you use the companion plugin that ships in the install pack.

## First hour

1. Activate **Acreline**.
2. Visit the front end once. A fresh install can create the sample pages (home, listings, areas, guide, agents, contact, blog), sample listings, agents, and showings. That content is fiction. Replace it with your own, or delete the samples.
3. Open **Appearance → Customize → Identity** and set the brokerage name, phone, address, hours, and social links. See [Office and hours](office-and-hours.md).
4. Open **Appearance → Acreline Settings** and turn sections on or off. See [Theme Settings](theme-settings.md).
5. Add a real listing under **Listings**, an agent under **Agents**, and send yourself a test showing from the public form. See [Listings](listings.md), [Agents](agents.md), and [Showings](showings.md).
6. Set **Settings → Reading** so the homepage is the page that uses the Home template, if WordPress did not already.
7. Activate the license under **Appearance** once Freemius shows the account screen. Until the product id is on your copy, updates still come from the author channel described in [License and updates](license-and-updates.md).

## What the sample site is

[acreline.matthummel.com](https://acreline.matthummel.com/) is a concept demo. Phones use the `555` exchange. Emails use `@acreline-concept.test`. Street numbers and ZIP codes are fake. A line on every page says the site is fiction. It is not a live MLS, a licensed brokerage, or a booking system that confirms appointments with a real calendar.

## Pages and templates

Marketing pages use the block editor. Each main page also has a named template (home, listings, areas, guide, agents, contact). Listings, agents, and showings use their own post types and classic field boxes, not the block editor.

## If the front end is blank

The theme loads CSS and JavaScript from a Vite manifest inside the zip. A checkout of the source repository without a build will show “Vite manifest not found”. The buyer zip already includes that build. See [Troubleshooting](troubleshooting.md).
