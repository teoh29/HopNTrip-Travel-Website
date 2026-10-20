<p align="center">
  <img src="image/HopNTrip-logo.png" alt="HopNTrip logo" width="180">
</p>

<h1 align="center">HopNTrip</h1>

<p align="center">
  <strong>Your Journey Begins Here</strong><br>
  A Sabah tourism website built with HTML, CSS, and JavaScript.
</p>

---

## Overview

HopNTrip is a group web development project for a fictional travel agency focused on Sabah, Malaysia. It brings destination discovery, tour packages, accommodation, flights, and travel insurance together in a multi-page interface.

The project demonstrates website design and browser-based interactions using plain HTML, CSS, and JavaScript, with no framework or build process.

> **Project status:** Front-end demonstration. Bookings, account access, contact submissions, and chat responses are simulated. There is no backend, database, payment processing, or live travel inventory.

## Contents

- [Features](#features)
- [Technology](#technology)
- [Pages](#pages)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Exploring the Demo](#exploring-the-demo)
- [Development Notes](#development-notes)
- [Current Limitations](#current-limitations)
- [Future Improvements](#future-improvements)
- [Team](#team)
- [Assets and Licensing](#assets-and-licensing)

## Features

- **Destination discovery:** Sabah travel highlights, destination cards, and detail modals.
- **Travel services:** Dedicated pages for flights, hotels, tours, and travel insurance.
- **Booking interfaces:** Search fields, filter controls, and demonstration booking actions.
- **Account forms:** Login, registration, password visibility controls, and a password-reset modal with client-side validation.
- **Contact page:** Validated enquiry form, embedded Google Map, and location information.
- **Company showcase:** About page, team profiles, and travel portfolio.
- **Media:** Local destination photography, video backgrounds, and video galleries.
- **Navigation and interaction:** Mobile menu controls, scroll-to-top buttons, modal windows, and a simulated chat widget.

## Technology

| Technology | Purpose |
| --- | --- |
| HTML5 | Page structure, links, forms, and media |
| CSS3 | Layout, styling, and responsive rules |
| Vanilla JavaScript | Menus, modals, validation, and demo interactions |
| Font Awesome 6.5.0 | Icons on the contact and login pages, loaded from a CDN |
| Google Maps Embed | Map on the contact page |

CSS and JavaScript are embedded in the individual HTML files. No package installation, API keys, or environment variables are required to preview the project.

## Pages

| Page | File | Description |
| --- | --- | --- |
| Home | [`index.html`](index.html) | Travel highlights, promotions, and destination discovery |
| About Us | [`about-us.html`](about-us.html) | Agency introduction and team profiles |
| Services | [`services.html`](services.html) | Travel services and media showcase |
| Tours | [`tours.html`](tours.html) | Tour packages and demonstration booking controls |
| Flights | [`flighbooking.html`](flighbooking.html) | Flight search fields, filters, and sample bookings |
| Hotels | [`hotels.html`](hotels.html) | Hotel listings, filters, and sample bookings |
| Insurance | [`insurance.html`](insurance.html) | Plan selection and traveller application form |
| Portfolio | [`portfolio.html`](portfolio.html) | Travel and project showcase |
| Contact Us | [`contact-us.html`](contact-us.html) | Enquiry form and location map |
| Login / Register | [`login.html`](login.html) | Account form demonstrations |

**Filename note:** `flighbooking.html` is the existing filename. Keep this spelling unless you also update every link that references it.

## Project Structure

```text
HopNTrip-main/
├── README.md
├── index.html
├── about-us.html
├── contact-us.html
├── flighbooking.html
├── hotels.html
├── insurance.html
├── login.html
├── portfolio.html
├── services.html
├── tours.html
├── image/                 # Logos, destination photos, icons, and team images
└── video/                 # Background videos and travel clips
```

The project archive includes both media folders. Keep them beside the HTML files so relative asset paths work.

## Getting Started

### Option 1: Open directly

1. Download and extract the project ZIP.
2. Open the extracted folder containing `index.html`.
3. Double-click `index.html` to open it in your browser.

This is the quickest way to preview the pages.

### Option 2: Run a local server

If Python 3 is installed, open a terminal in the folder containing `index.html` and run:

```bash
python -m http.server 8000
```

On Windows, you can also use:

```powershell
py -m http.server 8000
```

Open **[http://localhost:8000](http://localhost:8000)** in your browser. Press **Ctrl+C** in the terminal to stop the server.

An internet connection is needed for the embedded map, CDN icons, and externally hosted images. Local images and videos are included in the project.

## Exploring the Demo

1. Start on the homepage and explore the destination cards.
2. Use the navigation menu to visit services, tours, flights, and hotels.
3. Try the booking controls to see their demonstration messages.
4. Select an insurance plan and explore the application form.
5. Try the login, registration, and contact forms to see validation feedback.
6. Open the chat widget to see its predefined response.

Use sample information when trying forms. Success messages demonstrate the interface; they do not create accounts, send emails, or confirm reservations.

## Development Notes

- Edit the relevant `.html` file to change its content, styles, or interactions.
- Shared navigation, footers, and chat code are repeated across pages. Apply shared changes consistently.
- Preserve the `image/` and `video/` paths when moving or uploading the project.
- Match filename capitalization exactly when referencing assets, especially when deploying to a case-sensitive host.
- Keep `index.html` at the repository root when uploading the extracted project contents.

### Suggested Manual Checks

- Open all ten pages and follow the navigation links.
- Check images and videos for missing assets.
- Try the menu at desktop and mobile widths.
- Open and close modals and the chat widget.
- Submit empty, invalid, and valid sample form values.
- Check the browser console for JavaScript errors.

These are suggested checks for future changes, not a claim that the project has passed a full browser or accessibility audit.

## Current Limitations

| Area | Current behaviour |
| --- | --- |
| Search and filters | Several controls display demo alerts instead of querying or filtering live inventory |
| Bookings and insurance | Actions show sample feedback; no reservation or policy is created |
| Accounts | Validation and success messages are simulated; no authentication or account storage |
| Password reset | Displays simulated feedback; no reset email is sent |
| Contact form | Validates inputs and displays success feedback; no message delivery |
| Chat | Adds messages locally and returns a predefined reply |
| Travel information | Prices, offers, dates, and listings are sample content |
| External resources | Maps, CDN icons, and some images depend on external services |
| Maintainability | Repeated inline styles and scripts require updates across multiple files |

## Future Improvements

- [ ] Extract shared styles and scripts into reusable files.
- [ ] Consolidate common navigation, footer, and chat components.
- [ ] Implement working search, sorting, filtering, and pagination.
- [ ] Connect enquiry and booking forms to a backend.
- [ ] Add secure authentication and persistent account storage.
- [ ] Replace sample travel data with an appropriate data source.
- [ ] Optimize images and videos for faster loading.
- [ ] Audit keyboard navigation, form labels, contrast, and mobile layouts.
- [ ] Add automated checks for links and core interactions.

## Team

| Member | Role |
| --- | --- |
| Tiffany Fam | Team Leader |
| Tan Wei Ting | Team Member |
| Teoh En Yi | Team Member |
| Tan Wen Xi | Team Member |
| Sian Yi Xuan | Team Member |

## Assets and Licensing

The project includes local images and videos and references third-party resources, including Pexels imagery, Font Awesome icons, and Google Maps.

No project license file is included in the supplied archive. Reuse permissions for the source code and media are not established by this README. Third-party assets remain subject to their respective terms.
