# YogaFlow interactive prototype

A browser-based requirements prototype for the Yoga H’om studio project. It supports seven proposed use-case areas: class schedule, pass purchase, pass status, class check-in, schedule management, corrections, and reports.

## Run

Open [`index.html`](index.html) in a modern browser. No installation or local server is required.

Use **Preview as** to switch among Manager, Staff, Instructor, and Customer views. Changes are stored in the browser's local storage. **Reset sample data** restores the starting records.

## Demo path

1. Filter the class schedule.
2. Record a sample 10-Class Pass for Alex Morgan.
3. Check Alex into Gentle Yoga with that pass. The remaining uses decrease by one.
4. Observe that a second check-in is blocked.
5. Review the roster and report, then reverse the entry with a reason in Corrections.

## Scope

This is a front-end mockup for validating requirements. It uses sample data and has no server or payment integration. Studio policies for prices, pass validity, senior discounts, multiple active passes, workshop attendance, reservations, and user permissions remain to be confirmed.

## Files

- `index.html` — app shell
- `styles.css` — responsive visual design
- `app.js` — local data and interactions
- `README.txt` — short plain-text usage guide
