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
