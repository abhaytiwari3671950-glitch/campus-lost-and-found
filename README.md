# ReFound — Campus Lost & Found
A responsive frontend created with HTML, CSS and vanilla JavaScript. No framework, backend, build step, or API keys.

## Run
Open index.html in a modern browser. Alternatively use VS Code Live Server.

## Features
- Illustrated sample lost/found/reunited listings
- Search across title, location, spot and description
- Category, location, status and saved filters; date sorting
- Report form with validation and photo preview
- Local photo resizing before storage
- My reports, save/unsave, mark reunited/reopen, confirmed deletion
- Details and explicitly simulated claim flow
- Responsive styling and keyboard-accessible native dialogs

Data is saved in localStorage on the current origin/browser only. It is not shared across devices or users. All claims are previews, not real messages. Clearing browser data removes reports. Storage failures are shown without silently discarding prior saved data. Sample listings are illustrative and not reports from Chandigarh University. No personal contact details are collected.

Files: index.html, style.css, script.js. Sample illustrations are inline SVG created in JavaScript. No external assets or runtime network requests.

## Updated interface
Search-first board with left-side category/location filters, grid/list views, saved-items navigation, right-side detail drawer, three-step report wizard (item, location/photo, review), and mobile bottom navigation. Existing localStorage key is preserved.
