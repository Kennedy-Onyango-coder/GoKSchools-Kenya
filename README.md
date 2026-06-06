# GovSchools Kenya

This is a frontend prototype I built for the Kenyan Ministry of Education school admissions process. The goal is to show how a more modern, user-friendly interface could simplify the transition from Primary to Secondary school compared to the current NEMIS workflow.

## Project Overview
I built this to help parents and students navigate through thousands of government schools more easily. It features a mobile-first design and a color palette inspired by the Kenyan flag.

## Main Features

*   School Search: Users can filter schools by county, category (National, Extra-County, etc.), and KCPE cutoff marks.
*   M-Pesa Simulation: A mockup of the Daraja API STK push for handling application fees.
*   Application Wizard: A 4-step process to guide users through registration, document simulation, and payment.
*   User Dashboard: A simple area to track whether applications are under review, accepted, or rejected.
*   Dark Mode: Built-in support for a dark theme that keeps the green and red brand colors.

## Tech Stack

I kept this as a "Vanilla" project to show what's possible with just clean, standard web tech.

- HTML5 and CSS3 (using CSS variables for theme handling)
- Vanilla JavaScript (handles state and localStorage)
- Font Awesome for icons
- Google Fonts (Plus Jakarta Sans and DM Sans)

## Project Structure

```text
govschools-kenya/
├── css/
│   ├── base.css      # Resets and global utility styles
│   └── style.css     # Main UI and theme components
├── js/
│   ├── auth.js       # Login and session management
│   ├── apply.js      # Logic for the application wizard
│   ├── school-data.js# Helper for managing the school list
│   ├── payment.js    # M-Pesa payment simulation
│   └── search.js     # Search and filtering logic
├── index.html        # Home page
├── search.html       # School discovery page
└── apply.html        # Application form
```

## Quick Start

1.  **Clone the Repo**:
    ```bash
    git clone https://github.com/yourusername/govschools-kenya.git
    ```
2.  **Run it**: No npm install needed. Just open `index.html` in your browser.
3.  **Demo Credentials**: 
    *   **Phone**: `0712345678`
    *   **Password**: `demo1234` (or just register a new account—it's all stored in your browser!)

## Persistence (The "Mock" DB)

Since this is a frontend prototype, I'm using `localStorage` to keep your data alive. 
- User sessions, school modifications, and submitted applications will survive a page refresh. 
- You can clear your "database" at any time by clearing your browser's site data.

## Disclaimer

This is a **portfolio project** and is not affiliated with the Kenyan Ministry of Education (MoE) or the ICT Authority. It is intended for demonstration purposes only to showcase UI/UX and frontend architectural patterns.

---
**Created by Kennedy Onyango**
University of the People

© 2027 Republic of Kenya - Concept Design
