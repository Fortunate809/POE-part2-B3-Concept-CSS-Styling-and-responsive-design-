[README.md](https://github.com/user-attachments/files/32379202/README.md)
# B3 Concept Website Project

## Student Information
- Student Name: Phokela Ramokone Fortunate
- Student Number: ST10529266
- Module: Web Development (Introduction)
- Module Code: WEDE5020
- Assessment: Part 1 — Building the Foundation
- Organisation: B3 Concept

## Project Overview
This Part 1 project establishes a five-page HTML foundation for B3 Concept, a South African interior and graphic design practice. The website is organised around the organisation's services, history, project enquiry process and service areas.

Part 1 is intentionally HTML-only. CSS and JavaScript are reserved for later POE stages.

## Website Goals and Objectives
1. Present B3 Concept's services clearly.
2. Explain the organisation's background, mission and approach.
3. Help prospective clients identify an appropriate service.
4. Provide a dedicated project enquiry route.
5. Provide a separate general contact route.
6. Present more than one service location.
7. Create a semantic HTML foundation for later CSS and JavaScript.

## Target Audience
Residential clients, commercial and retail clients, businesses requiring corporate identity or website design, property development clients, and clients requiring project management, consulting or 3D visualisation.

## Key Features and Functionality
- Five linked HTML pages.
- Semantic HTML5 structure: header, nav, main, section, article, address, form, fieldset and footer.
- Consistent navigation.
- Detailed service content and three-stage design process.
- Licensed Pexels photographs used through HTML <img> elements; no CSS or JavaScript.
- Project enquiry form with HTML5 validation.
- Separate general contact form.
- Three service areas with map links.
- Accessible labels and descriptive links.
- Comments explaining major code sections.

## Image Assets
The website uses three Pexels photographs as illustrative visuals. They are not presented as photographs of B3 Concept projects and are not used to imply endorsement by B3 Concept. Pexels identifies these images as free to use; the exact source pages and photographers are recorded below for transparent academic sourcing.

## Part 1 Details
The implementation follows the POE requirements for a minimum of five pages, semantic HTML structure, researched content, working navigation, comments, organised files, and README/changelog documentation. CSS and JavaScript are not included in Part 1.

## Sitemap
Home (index.html)
├── About Us (about.html)
├── Services (services.html)
├── Enquiry (enquiry.html)
└── Contact (contact.html)
    ├── Cape Town
    ├── Johannesburg
    └── Durban

## File and Folder Structure
```text
b3-concept/
├── index.html
├── about.html
├── services.html
├── enquiry.html
├── contact.html
├── README.md
├── content-research.md
└── images/
    ├── interior-design.jpg
    ├── design-process.jpg
    └── services-interior.jpg
```

## Timeline and Milestones
| Stage | Activity | Evidence |
|---|---|---|
| 1 | Research and audience analysis | Research notes |
| 2 | Proposal and lecturer approval | Two proposals |
| 3 | HTML structure | Five HTML pages |
| 4 | Navigation and forms | Tested links/forms |
| 5 | Quality assurance | Browser and HTML checks |
| 6 | Submission preparation | README, references and commits |

## Changelog
| Date | Version | Development record |
|---|---|---|
| 11 August 2026 | 0.1 | Created the five-page project structure. |
| 11 August 2026 | 0.2 | Added semantic HTML5 structure and consistent navigation. |
| 11 August 2026 | 0.3 | Added researched organisation content and service areas. |
| 11 August 2026 | 0.4 | Added separate project enquiry and general contact forms. |
| 11 August 2026 | 0.5 | Added comments, labels, validation attributes and internal links. |
| 11 August 2026 | 0.6 | Added content research notes and Part 1 documentation. |

## References
B3 Concept (2026) *B3 Concept*. Available at: https://www.b3concept.co.za/ (Accessed: 11 August 2026).

The Independent Institute of Education (2026) *Web Development (Introduction) WEDE5020: Assessment Type POE*. Johannesburg: The Independent Institute of Education (Pty) Ltd.

xneelo (2026) *Domain Name Search and Registration*. Available at: https://xneelo.co.za/domains/ (Accessed: 11 August 2026).

xneelo (2026) *Web Hosting*. Available at: https://xneelo.co.za/web-hosting/ (Accessed: 11 August 2026).

Pexels (2026) *Modern Living Room Design* by Paul Seling. Available at: https://www.pexels.com/photo/modern-living-room-design-20390765/ (Accessed: 11 August 2026).

Pexels (2026) *Architect working on Floor Plans* by AI25.Studio Studio. Available at: https://www.pexels.com/photo/architect-working-on-floor-plans-5292244/ (Accessed: 11 August 2026).

Pexels (2026) *Modern Living Room Interior* by Curtis Adams. Available at: https://www.pexels.com/photo/modern-living-room-interior-15824912/ (Accessed: 11 August 2026).

## Testing Record
Images should be checked for correct display and meaningful alt text. Record the actual browsers, dates, link results and form results after testing. Do not claim tests that were not performed.

## GitHub Commit Plan
1. Initial Part 1 project structure.
2. Add semantic HTML page structure.
3. Add researched organisation content.
4. Add navigation and internal links.
5. Add enquiry and contact forms.
6. Add comments and accessibility improvements.
7. Final Part 1 testing and documentation.

## AI Disclosure
Complete the official IIE AI disclosure annexure required for this assessment, including the required screenshots/evidence and an accurate explanation of how AI assistance was used.

## Part 2: CSS and Responsive Design Work

### Corrections implemented from Part 1 feedback
- Added a second website proposal and supporting research documents to address the missing proposal/research feedback.
- Added a clearer B3 Concept design aesthetic and visual direction.
- Expanded the website structure and implementation detail while retaining the existing five-page sitemap.
- Added an external stylesheet and linked it to all HTML pages.
- Added responsive desktop, tablet and mobile layouts.
- Added relative CSS units including `%`, `rem` and `em`.
- Added responsive image handling with `srcset` and `sizes`.

### Part 2 changelog
- **16 September 2026 — v1.0:** Created and linked `style.css` to `index.html`, `about.html`, `services.html`, `enquiry.html` and `contact.html`.
- **16 September 2026 — v1.1:** Added base page styling, typography, spacing, colours and responsive image defaults.
- **16 September 2026 — v1.2:** Added Flexbox and CSS Grid layouts for navigation, content sections, service cards, forms and footer.
- **16 September 2026 — v1.3:** Added visual styling, borders, shadows, rounded corners, hover states, focus states, active button state and text-selection styling.
- **16 September 2026 — v1.4:** Added tablet breakpoint at `900px` and mobile breakpoint at `600px`, including changes to navigation, content grids, typography, forms and footer layout.
- **16 September 2026 — v1.5:** Added responsive image attributes using `srcset` and `sizes` to the main visual images.
- **16 September 2026 — v1.6:** Restored the original three local image assets and added 600px and 1200px responsive variants so the Part 2 project no longer depends on external image URLs for its main visuals.

### Responsive image sources
The three original project image assets are stored locally in the `images/` folder. Responsive 600px and 1200px variants are provided and referenced through `srcset` and `sizes`. The original Pexels sources are documented in the references below.
- `images/interior-design.jpg` with `interior-design-600.jpg` and `interior-design-1200.jpg`.
- `images/design-process.jpg` with `design-process-600.jpg` and `design-process-960.jpg`.
- `images/services-interior.jpg` with `services-interior-600.jpg` and `services-interior-1200.jpg`.

### Part 2 testing record

The website was tested at desktop, tablet and mobile viewport sizes using the browser's responsive device toolbar. The testing checked the layout, navigation, typography, images and overall responsiveness

| Device | Viewport Size | Result |
|---|---|---|
| Desktop | 1920 × 1080 | Passed |
| Tablet | 768 × 1024 | Passed |
| Mobile | 375 × 667 | Passed |

### Testing Evidence

- `testing-evidence/desktop-1920px.png` — Desktop responsive test.
- `testing-evidence/tablet-768px.png` — Tablet responsive test.
- `testing-evidence/mobile-375px.png` — Mobile responsive test.

The tests confirmed that the website layout remains usable at different screen sizes, the navigation adapts appropriately, and the images resize correctly without causing horizontal overflow.

