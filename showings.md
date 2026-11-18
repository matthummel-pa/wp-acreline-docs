# Showings

A showing request is a form on the public site. It creates a **Booking** post. It does not write to a calendar, charge a card, or confirm a time by itself.

## What the visitor sees

The form asks for the property and a requested time, plus the optional fields you leave on under **Appearance → Acreline Settings → Bookings**. Submit goes to the theme’s bookings endpoint and stores the request.

## What you do next

Open **Bookings** in wp-admin and move the status forward (new, confirmed, completed, or the statuses your screen shows). Email the visitor yourself. The theme stores the request so you have a record.

## What this is not

- Not an MLS scheduling link
- Not OpenTable, Calendly, or a paid booking product, unless you paste your own calendar URL on an agent profile
- Not a place to collect card numbers

Keep real client notes out of public GitHub issues. See [Support](support.md).
