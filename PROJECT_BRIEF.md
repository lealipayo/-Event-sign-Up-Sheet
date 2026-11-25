# Project Brief: Medina College Ipil — Campus Information & Alert Center

## Elevator Pitch
A fast, zero-setup single-page web application that centralizes official announcements, weather and emergency alerts, class advisories, and student organization notices for **Medina College Ipil, Incorporated**, keeping the entire campus informed in real time.

## Problem Statement
Campus updates at Medina College Ipil are fragmented across informal messaging apps and physical boards. Urgent weather alerts and class advisories get lost in chat noise, and students lack a single dashboard to verify whether an alert is still active or resolved.

## Target Users
* **Students:** Check active class advisories, campus events, and urgent weather/safety alerts filtered by their department or course.
* **Faculty & Department Heads:** Post targeted class or office schedules and track active notices.
* **Campus Administration & Student Council:** Broadcast high-priority emergency alerts, pin critical notices to the top, and mark alerts resolved once situations return to normal.

## Key Features
* **Live Campus Status Banner:** Instantly displays whether campus status is normal or highlights active alerts with one-click **View Active** and **Resolve Active Alerts** controls.
* **Alert & Information Composer:** Structured form supporting 4 categories, 3 priority levels (*Urgent*, *Important*, *General Info*), target department/course, effective/expiry dates, and top-feed pinning.
* **Real-Time Filtering & Search:** Instant category tabs (*All Notices*, *Active Only*, *Emergency / Weather Alert*, *Class / Office Advisory*, *Event / Org Notice*, *Health & Safety*) paired with keyword search.
* **Live Summary Dashboard:** Real-time metric cards tracking **Active Alerts**, **Urgent Notices**, and **Total Advisories**, plus a **Reset Sample Advisories** demo loader.

## System Architecture
* **Frontend:** Single-page responsive HTML5, CSS3, and vanilla JavaScript (`index.html`) designed for desktop and Android mobile viewports.
* **Data Persistence:** Client-side browser `localStorage` storing structured JSON notice objects (`id`, `category`, `priority`, `title`, `details`, `department`, `effectiveDate`, `pinned`, `status`, `timestamp`) with automatic state re-rendering.
* **Hosting & CI/CD:** Static deployment via **GitHub Pages** directly from the `main` branch of `lealipayo/-Event-sign-Up-Sheet`.
* 
