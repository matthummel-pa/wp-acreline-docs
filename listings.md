# Listings

Listings are a custom post type. Add them under **Listings** in wp-admin. The public grid and the single listing page read those posts. The homepage search reads the same inventory in the browser (`window.ACRELINE.listings`).

Each listing has classic field boxes (not the block editor): price, beds, baths, size, status, type, photos, open house, tours, and the rest of the detail fields. Which of those appear in public is controlled under **Appearance → Acreline Settings → Listings**.

## Cards and the grid

On the Listings tab you can set grid columns (2, 3, or 4) and show or hide:

- List price, beds, baths, square feet, acres
- Status and type badges
- MLS number, days on market, price per square foot

An MLS number field is a label you type. Acreline does not connect to a live multiple-listing service.

## The listing page

The same tab toggles sections on the single listing:

- Open house banner
- Virtual tour and video or drone tour
- Floor plan
- Property details, utilities, HOA
- Land details, school district, flood zone
- Green features and smart-home features

Turn a section off when you do not use it. Empty sections should not be left on just because the sample listings had them.

## Sample data

The concept demo uses fictional streets, the ZIP `00000`, and township values `Cumberland`, `Straban`, and `Franklin`. On the public site those townships are labeled North Ridge, Mill Creek, and Oak Hollow. Replace sample listings before you point a real domain at the site.

## Open houses

Open house copy is a field on the listing, plus the banner toggle above. It is not a ticketed event and it does not charge a card.
