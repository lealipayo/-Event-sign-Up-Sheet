Act as a senior front-end web developer. Build a complete, single-file responsive web application (`index.html`) using HTML5, CSS3, and vanilla JavaScript with `localStorage` persistence for **Medina College Ipil, Incorporated — Campus Information & Alert Center** (located in Ipil, Zamboanga Sibugay).

Include the following exact structure and features:

1. **Header & Live Clock**
   - Institutional branding with seal placeholder (`./medina-college-logo.png`), badge (`MC · IPIL · 2002`), location (`Ipil, Zamboanga Sibugay`), title (`Medina College Ipil, Incorporated — Campus Information & Alert Center`), and subtitle (`Official Campus Announcements, Emergency & Weather Alerts, Advisories, and Notices`).
   - A real-time updating date and digital clock display (`Loading date...` / `--:--:-- --`).
   - A **Reset Sample Advisories** button to restore default sample campus notices into `localStorage`.

2. **Campus Status Banner**
   - Dynamically displays **No Active Alerts** ("All campus advisories are currently normal or resolved.") when zero alerts are active, or highlights active alerts when present.
   - Include **View Active** and **Resolve Active Alerts** action buttons.

3. **Alert & Campus Information Composer**
   - Form inputs for:
     - **Category \*** (Dropdown: `Emergency / Weather Alert`, `Class / Office Advisory`, `Event / Org Notice`, `Health & Safety`)
     - **Priority Level \*** (Dropdown: `Urgent`, `Important`, `General Info`)
     - **Title \*** (Text input, required)
     - **Details \*** (Textarea, required)
     - **Target Department / Course** (Text input)
     - **Expiry / Effective Date** (Date input)
     - **Pin this notice to the top of the feed** (Checkbox)
   - Submit button: **+ Post Campus Info / Alert**.

4. **Campus Information & Alerts Feed**
   - Live item count badge (`0 Items`).
   - Filter tabs: `All Notices`, `Active Only`, `Emergency / Weather Alert`, `Class / Office Advisory`, `Event / Org Notice`, `Health & Safety`.
   - Real-time **Search** input with a **Clear** button.
   - Notice cards displaying category badge, priority level, pinned status, target department/course, effective date, timestamp, and actions to resolve/toggle status or delete.

5. **Live Campus Info & Alert Summary Dashboard**
   - Three summary cards tracking:
     - **Active Alerts** (`Unresolved active notices` 🚨)
     - **Urgent Notices** (`Active high-priority alerts` ⚠️)
     - **Total Advisories** (`All posted campus items` 📢)
   - Footer: `Medina College Ipil, Incorporated · Ipil, Zamboanga Sibugay · Campus Information & Alert Center`.

Ensure the layout is clean, academic, and mobile-friendly for Android screens, with all code self-contained inside `index.html`.

