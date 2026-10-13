# The Way Ministry of Evangelism

Website for The Way Ministry of Evangelism, a Christian ministry proclaiming Jesus with clarity and courage, starting in the Houston and Galveston region.

Plain HTML, CSS and JavaScript with no build step. Open `index.html` through any static web server (for example `python3 -m http.server`) or host the folder on GitHub Pages or any web host.

| Page | File |
|---|---|
| Home | `index.html` |
| Our Mission | `about/index.html` |
| Get Involved / Prayer request | `get-involved/index.html` |
| Contact | `contact/index.html` |

`assets/` holds the stylesheet (`way.css`), shared script (`way.js`), the three.js hero scene (`road.js`, loads three.js 0.169.0 from jsdelivr), self-hosted fonts and the banner and logo.

## Structured data
Each page has an Organization JSON-LD block whose `url` and `logo` assume GitHub Pages at https://cyrusw17.github.io/thewayweb/. Change them if the site moves to its own domain.

## Still to fill in
Search the HTML for `class="ph"` to find every placeholder: ministry email and phone, meeting day/time/place, outreach dates, leader names, giving link and the statement of faith.

The prayer request and contact forms do not send anything yet. To make them work, point each `<form>` at a form service or your own endpoint, and remove the `data-preview` attribute and the "Preview site" notes.
