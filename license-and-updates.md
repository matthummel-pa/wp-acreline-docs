# License and updates

Acreline is sold the same way as Cobble & Candle. Freemius is the merchant of record: checkout, tax, the license, the receipt, the zip, and buyer updates. The theme is GPL v2 or later. A license buys updates and email support. An expired license does not turn the theme’s features off.

## Where to buy

- [matthummel.com/shop](https://matthummel.com/shop/)
- [matthummel.com/product/acreline](https://matthummel.com/product/acreline/)

There is no second product URL. The live demo in the Freemius product is [acreline.matthummel.com](https://acreline.matthummel.com/).

## Plans

One annual plan. Checkout asks how many sites to license. Every tier includes a year of updates, email support, and a 30-day refund.

| Tier | Sites | Price | Billing |
| --- | --- | --- | --- |
| 1 site | 1 | $59.99 | Yearly |
| 5 sites | 5 | $99.99 | Yearly |
| Unlimited sites | Unlimited | $199.99 | Yearly |

## After purchase

1. Download `acreline.zip` and upload it under **Appearance → Themes**.
2. Open the Freemius account screen under **Appearance** and activate the license.
3. Later versions arrive through that same screen. You do not need a GitHub token.

The concept demo and the author’s own installs can still update from a GitHub release named `theme-latest` until Freemius is filled in. When Freemius is active, that GitHub updater screen hides so buyers are not asked for a token.

## Purchase bar

The bar on the concept demo (style chips and **Get this theme**) is not part of the buyer zip. It is a small plugin installed only on the demo site. The button goes to the product page above.

## What never goes in git

Product secret keys and API tokens stay in the host’s private config or in GitHub Actions secrets. This docs repository does not contain them. The public product id and public key are added on the theme when the Freemius product exists; they are not secret, and they are not copied from Cobble’s product.
