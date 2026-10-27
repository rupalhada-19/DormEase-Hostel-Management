# DormEase — Hostel Laundry & Cleaning Coordination

DormEase is a student project prototype for making two everyday hostel services easier to coordinate: laundry return verification and room-cleaning schedule requests. It follows the problem scope and wireframe concepts in Design Thinking Assignments 1 and 2.

## Problem addressed
Students may receive missing, exchanged, damaged or mixed-up laundry items, while cleaning timings can conflict with classes or other commitments. Records and requests can be hard to track when spread across informal channels.

## Features in this prototype
- Responsive dashboard with laundry, cleaning and open-issue summaries.
- Create laundry batches with a unique batch ID, submission date and submitted-item count.
- Record returned-item counts; flag a count mismatch and create an issue record.
- Cleaning schedule view and reschedule/skip requests.
- Demo request status changes (Pending / Approved / Declined).
- Service issue reporting for laundry and cleaning.
- Data saved in the current browser using `localStorage`.
- Basic field validation and success/error toast messages.

## Technology
- HTML5: semantic page structure and forms.
- CSS3: responsive layout and visual design.
- Vanilla JavaScript: rendering, form validation, prototype workflows and local persistence.
- Browser `localStorage`: demo-only data storage. No backend or account authentication is connected.

## Run locally
1. Download or clone this repository.
2. Open `DormEase-Website/index.html` in a modern browser.
3. Use the sidebar to visit Dashboard, Laundry tracking, Cleaning schedule and Report an issue.
4. Try creating a batch, opening it with **View**, entering the returned count, submitting a cleaning request and reporting an issue.

No package installation or build step is needed for the static prototype.

## Demo data and limitations
- The initial dashboard contains clearly illustrative sample records.
- Data is stored only in the browser profile where the site is opened. Clearing browser storage clears the demo data.
- This is not a production service: there is no real login, server-side database, multi-user sync, role-based access control, staff notifications or backend photo upload.
- Optional file selection is shown as a UI concept only; the photo is not uploaded or persisted.
- Item-by-item photo matching is not implemented.
- Schedule data is illustrative. Requests do not actually reach hostel staff.
- Do not enter real student information or sensitive photos.

## Team contributions
**Please verify and edit this section so it matches the work actually completed by each team member before submission.** Suggested division based on the team's stated four-member structure:
- **Rupal Hada** — problem research continuity, requirements/report integration, feature validation and final presentation coordination.
- **Prarthna** — UI/UX review against the Figma design and Assignment 2 wireframes.
- **Aditi** — front-end implementation review, forms and interaction checks.
- **Reva** — demo flow, test execution, feedback collection and video preparation.

These are suggested allocations for the report and should not be presented as completed work unless each person confirms their contribution.

## Testing
The project includes a proposed test checklist in the Assignment 3 report. Record actual outcomes after running each test in the browser; do not report peer feedback until it has genuinely been collected.

## Links
- Figma design reference: https://www.figma.com/design/82tTqjsouniMj6fLdoOlo6/DormEase-Mobile-App-UI?node-id=0-1
- Deployment URL: **Add after publishing** (e.g. GitHub Pages or Netlify).
- GitHub repository URL: **Add after creating the repository**.
- YouTube demo URL: **Add after recording and publishing the video as Public or Unlisted**.

## GitHub publishing (quick steps)
1. Create a new GitHub repository named `DormEase`.
2. Upload the contents of this folder (including `index.html`, `styles.css`, `app.js`, and this README).
3. In repository **Settings → Pages**, choose the default branch and root folder if GitHub Pages is available for the repository.
4. Wait for the published URL, open it in a private/incognito window, and test the key journeys.
5. Add the actual repository and deployment URLs above. Never commit passwords, API keys, access tokens, real student data or laundry photos.

## Acknowledgements and assets
- Project problem and requirements: Assignment 1 and Assignment 2 materials supplied by the team.
- Figma: DormEase Mobile App UI design reference.
- Icons in the interface are simple text glyphs/Unicode symbols; no external icon library is bundled.
- Fonts: DM Sans and Manrope are requested from Google Fonts when internet access is available; fallback sans-serif fonts are defined.
- ChatGPT was used to help draft code, organise the report and refine wording. Review and disclose this assistance according to the instructor's requirements.
