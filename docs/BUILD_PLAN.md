# Search Bar Feature — Build Plan

A site-wide search bar that opens a full-screen overlay with a dark backdrop,
accessible from the desktop navbar and the mobile hamburger menu.

---

## Step 1 — Add the search icon to the navbar HTML (all 5 pages)

Place a search icon button inside `.nav-actions` (next to the cart icon on
desktop) and a "Search" link inside `.nav-menu` (so it appears in the hamburger
menu on mobile). No behavior yet — just verify it shows up in the right places
visually.

**Files:** `index.html`, `about.html`, `library.html`, `faq.html`, `contact.html`

---

## Step 2 — Style the search icon

Write CSS so the search icon matches the existing nav style on desktop, and the
search link looks natural inside the mobile slide-down menu. Test both
breakpoints.

**Files:** `styles.css`

---

## Step 3 — Add the overlay HTML (all 5 pages)

Add the two structural elements needed: a dark full-screen backdrop div and a
centered search panel div (containing an `<input>` and a close button). They
will be hidden by default. No JS yet — just verify the DOM is in place.

**Files:** `index.html`, `about.html`, `library.html`, `faq.html`, `contact.html`

---

## Step 4 — Style the overlay

Write CSS for the dark semi-transparent backdrop, the centered white panel, the
input field, and the close button. Make them hidden by default with a class you
will toggle (e.g. `.active`). Test by temporarily adding `.active` in the HTML
to see the final visual.

**Files:** `styles.css`

---

## Step 5 — Wire up the JavaScript (all 5 pages)

Add the open/close logic: clicking the search icon opens the overlay, clicking
the backdrop or close button closes it, and pressing `Escape` also closes it.
Update all 5 pages.

**Files:** `index.html`, `about.html`, `library.html`, `faq.html`, `contact.html`

---

## Step 6 — Polish: focus management and animation

Auto-focus the input when the overlay opens. Add a short fade/scale-in CSS
transition so the panel does not just pop. Verify it feels right on both desktop
and mobile.

**Files:** `styles.css`, `index.html`, `about.html`, `library.html`, `faq.html`, `contact.html`
