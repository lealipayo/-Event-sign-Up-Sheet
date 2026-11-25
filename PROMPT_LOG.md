# Prompt Log — AI-Use Record

## 1 — Initial App Architecture & UI Scaffold
- **Prompt:** Build a single-page web application (`index.html`) using HTML5, CSS3, and vanilla JavaScript with `localStorage` persistence for Medina College Ipil, Incorporated — Campus Information & Alert Center (Ipil, Zamboanga Sibugay), featuring a live clock header, Campus Status banner, Alert Composer, category/search filters, and summary cards.
- **Result:** Generated the core single-page structure with institutional header branding (`MC · IPIL · 2002`), form inputs, feed container, and summary counters.
- **Verified:** Opened `index.html` in browser and confirmed all sections render cleanly.
- **Commit:** Initial build of Campus Information & Alert Center

## 2 — Alert Composer & localStorage Persistence (FR-01)
- **Prompt:** Implement JavaScript functions to save new campus notices to `localStorage`, support pinning notices to the top of the feed, and add a "Reset Sample Advisories" button to populate realistic campus demo data.
- **Result:** Added `localStorage` read/write state management, form validation for required fields (`Category`, `Priority Level`, `Title`, `Details`), and sample advisory seeding.
- **Verified:** Posted test notices, reloaded the page on mobile Chrome, and confirmed entries and pinned order persisted.
- **Commit:** Add localStorage persistence, pinning, and sample advisories reset

## 3 — Campus Status Banner & Active Alert Resolution
- **Prompt:** Connect the Campus Status banner to dynamically reflect active vs. resolved notices, and wire up the "View Active" and "Resolve Active Alerts" buttons along with the live summary counters (Active Alerts, Urgent Notices, Total Advisories).
- **Result:** Added dynamic status detection, bulk/individual alert resolution, and automatic counter recalculation on every state change.
- **Verified:** Posted an Urgent Emergency alert, verified counters incremented, clicked "Resolve Active Alerts," and confirmed status returned to "No Active Alerts."
- **Commit:** Implement dynamic campus status banner and summary counters

## 4 — Category Filter Tabs & Real-Time Search
- **Prompt:** Add interactive filter tabs (All Notices, Active Only, Emergency / Weather Alert, Class / Office Advisory, Event / Org Notice, Health & Safety) and a real-time search bar with a Clear button.
- **Result:** Implemented combined category-tab filtering and case-insensitive keyword matching across titles, details, and target departments.
- **Verified:** Tested switching tabs and searching department codes; confirmed Clear button resets search results.
- **Commit:** Add category filter tabs and live keyword search

## 5 — Android Mobile Responsiveness & Repository Documentation
- **Prompt:** Optimize button spacing and card layout for Android mobile viewports, and create `.gitignore`, `README.md` (with community problem and FR-01), `PROJECT_BRIEF.md`, and `PROMPT_LOG.md`.
- **Result:** Refined mobile CSS breakpoints and finalized repository documentation files.
- **Verified:** Tested live deployment at `https://lealipayo.github.io/-Event-sign-Up-Sheet/` on Android.
- **Commit:** Add mobile UI polish and project documentation

