# UX Project Proposal & Design Strategy Handoff — ParkUB Tracker

## 1. Project Overview & Theme
* **Project Name:** ParkUB Tracker (University of Baguio Parking & Bike System)
* **Chosen Theme:** University Campus Logistics, Transit, and Infrastructure Accessibility
* **Core Concept:** A mobile-responsive web application that provides real-time slot availability, live zone occupancy heatmaps, pass reservations, Monday–Friday vehicle coding checks, and downloadable offline parking pass receipts across campus parking lots, motorcycle hubs, and bicycle racks.

## 2. Target Audience & User Personas
* **Primary Users:** University students, faculty, staff, and campus visitors commuting via cars, motorcycles, or bicycles who need quick pre-arrival slot visibility and clear pass/coding information.
* **Pain Points Addressed:** Uncertainty over open slots before arriving, morning gate congestion and idling, high pre-class stress, forgetting number-coding restrictions, and needing proof of reservation when mobile signal is weak.

## 3. Explicit Interface Goals & Design Strategy
* **Accessibility:** High-contrast typography and borders, clear text/icon status indicators alongside color cues (avoiding color-only signaling), and responsive layouts that adapt to mobile screens.
* **Sustainability:** Surfaces motorcycle hubs and bicycle racks alongside car parking zones to encourage lower-emission commuting and reduce gate idling.
* **Timely UX:** Surfaces top-level free-slot counts immediately, previews pass durations/coding rules before confirmation, and lets users download offline receipts for instant gate verification.

## 4. Key Functional & UI Components
* **Authentication & Profile:** Log in / sign up flow with ID and password validation, vehicle type/plate setup, and user profile/contact support view.
* **Slot & Zone Selection:** Vehicle category filters (Motorcycle, Car, Bicycle), interactive slot/zone cards, and zone status panels.
* **Reservations & Digital Pass:** Pass rate/duration options (including multi-month/semester passes), date selection, Mon–Fri coding warnings, and clickable digital passes for offline receipt download.
* **Live Heatmap & Sync Tracker:** Full-width occupancy bars and manual/live sync status across campus zones.

## 5. Current Status & Next Steps for Handoff
* **Current State:** Front-end prototype implemented in HTML, CSS, and JavaScript with responsive mobile styles and client-side state.
* **Next Steps:** Connect to a persistent database/backend for real-time multi-user slot updates, add QR code generation on digital passes, and run mobile usability testing with students and security personnel.
