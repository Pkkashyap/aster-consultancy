Aster Consultancy Services (ACS) website. Incorporated 2023.

Static site (plain HTML). Deployed on Render as a Static Site: build command empty, publish directory `.`

## Updating details
- **Phone number:** open index.html, find `const PHONE = '';` near the top of the script at the bottom of the file, and add your number, e.g. `const PHONE = '+91 98765 43210';`. That turns on every Call and WhatsApp button. Until then they stay hidden.
- **Email:** info@asterconsultancyservices.com appears in the top bar, contact section, footer and `const EMAIL`. Find and replace all of them.
- **Services:** every service is listed in the "Services directory" section of index.html (one `<li>` per service), grouped by practice area in this order: 01 Recruitment, 02 Environmental & ESG, 03 Education & Accreditation, 04 Healthcare Certification & TPA, 05 Digital Marketing, Tech & AI, 06 Business Registration & Compliance.

## Images
The site uses no photos, only the circular logo and icons.
- `assets/img/thread 3d logo.jpeg` is the original logo.
- `logo.jpg` (large), `logo-160.png` (header/footer), `icon-192.png` and `favicon-64.png` are circular web-sized copies made from it.
