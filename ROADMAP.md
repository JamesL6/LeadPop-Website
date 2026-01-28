# LeadPop Website Roadmap

## Overview
This document tracks future improvements and pages needed for the LeadPop business loan lead generation website.

---

## Pages to Create

### High Priority
- [ ] **Contact Page** — Contact form, phone number, email, business hours
- [x] **About Us Page** — Team photos, company story, mission, why we started this
  - [x] **Add team photos** — James, Isaac, Paola, Dylan headshots added
  - [x] **Update team bios** — Updated bios for all team members
- [ ] **Privacy Policy Page** — Legal requirements
- [ ] **Terms of Service Page** — Legal requirements
- [ ] **Lead Magnet** — Capture leads who aren't ready to book a call yet (email gate)
  - Ideas:
    - "The Business Loan Lead Quality Checklist" (PDF)
    - "7 Questions to Ask Any Lead Provider Before Signing" (PDF)
    - "Lead ROI Calculator" (interactive or spreadsheet)
    - "The Pay-Per-Lead Buyer's Guide" (PDF)
  - Add to homepage as secondary CTA
  - Create simple landing page or modal for email capture

### Medium Priority
- [x] **How It Works Page** — Expanded version with full user journey (dedicated page)
- [ ] **Homepage "How It Works" section** — Add back a concise 3-step version for desktop
- [ ] **FAQ Page** — Comprehensive FAQ beyond what's on the homepage

### Service Pages (Individual Landing Pages)
- [ ] **SBA Loans (7a, 504)** — Dedicated page for SBA lead generation
- [ ] **Merchant Cash Advances (MCA)** — Dedicated page for MCA leads
- [ ] **Equipment Financing** — Dedicated page
- [ ] **Lines of Credit** — Dedicated page
- [ ] **Invoice Factoring** — Dedicated page
- [ ] **Term Loans** — Dedicated page
- [ ] **Working Capital** — Dedicated page
- [ ] **Commercial Real Estate** — Dedicated page
- [ ] **Revenue-Based Financing** — Dedicated page

---

## Content to Create

### Video Content
- [ ] **Hero Video** — You (founder) explaining the service, building trust, humanizing the brand
  - Suggested talking points:
    - Who you are and your background
    - The problem you solve (bad leads, wasted budget)
    - How your model is different (you absorb risk)
    - Quick overview of the process
    - Call to action (book a call)
  - Keep it under 2 minutes
  - Film professionally or use high-quality webcam with good lighting/audio

### Lead Magnet
- *(Moved to High Priority — see Pages to Create section)*

---

## Footer Improvements
- [ ] Add phone number
- [ ] Add email address
- [ ] Add physical business address (or at least city/state)
- [ ] Link to Contact page
- [ ] Link to About Us page
- [ ] Consider adding social media links if applicable

---

## Future Enhancements

### Social Proof (Once Available)
- [ ] Client testimonials from business loan companies
- [ ] Case studies with specific metrics
- [ ] Client logos (with permission)
- [ ] "X leads delivered" or "X funded deals generated" counter

### Technical
- [ ] Analytics setup (GA4, conversion tracking)
- [ ] CRM integration documentation page
- [ ] Calendly/booking integration for "Book a Call" buttons

### SEO
- [ ] Meta descriptions for all pages
- [ ] Schema markup for local business
- [ ] Blog/content section for organic traffic (future consideration)

---

## Notes

### Target Customer Profile
- Minimum spend: $20,000/month
- Roles: VP of Sales, Marketing Directors, Business Owners at lending companies
- Currently using: Shared lead providers, marketing agencies on retainer
- Pain points: Bad leads, wasted ad spend, no guarantees

### Key Differentiators to Emphasize
- We absorb all ad spend risk
- 100% exclusive leads (never resold)
- OTP SMS verification (not just email)
- Custom filters to match their buy box
- Free replacements for unqualified leads
- Real-time CRM delivery (Webhook, Zapier, API, Google Sheets)

### Messaging Considerations
- Be careful not to disparage in-house marketing teams (they may be the decision makers)
- Focus on complementing their efforts, not replacing their team
- Emphasize partnership, not vendor relationship

---

## Completed Items
- [x] Initial homepage build (index-v2.html)
- [x] Remove trust bar (redundant)
- [x] Remove hero badge ("Now Accepting...")
- [x] Remove "In-House Marketing Team" from comparison table
- [x] Fix comparison table for mobile
- [x] Combine "Aged Lead Lists" and "Unqualified Prospects" problem cards
- [x] Fix section padding/spacing
- [x] Improve FAQ with industry-specific questions
- [x] Fix mobile responsiveness issues
- [x] **About Us Page** — Team photos, company story, mission, why we started this
  - [x] **Add team photos** — James, Isaac, Paola, Dylan headshots added
  - [x] **Update team bios** — Updated bios for James, Isaac, Paola, and Dylan
  - [x] **Added Dylan Purcell** — Sales Director added to team section
  - [x] **Fixed team grid layout** — Changed to 2x2 grid on desktop
  - [x] **Updated story section** — Changed "What If Moment" to "Chose a Better Model" to clarify pay-per-lead is an existing model
- [x] **How It Works Page** — Expanded version with full user journey (dedicated page)
  - [x] **Fixed timeline visual** — Line now connects through numbered circles properly
  - [x] **Condensed to 5 steps** — Combined first two steps and added pricing discussion
  - [x] **Updated CRM section** — Added real company logos (Salesforce, HubSpot, Zoho, etc.)
- [x] **Updated CTAs** — Changed "Book a Call" to "Get Your Lead Projection" across all pages
- [x] **Navigation** — Added working navigation links to Homepage, About, and How It Works pages

---

## Currently Working On
- [x] **Call Booking Page** — Dedicated page for scheduling lead projection calls
  - [x] Created `book-call.html` with booking form
  - [x] What to expect on the call section
  - [x] FAQ about the call
  - [x] Trust badges
  - [x] Updated all CTAs across pages to link to book-call.html
  - [x] Updated footers with booking page link
- [x] **Alternative Booking Pages** — Created variations for A/B testing
  - [x] ~~Created `get-projection.html` (v2) with Heyflow form embed~~ (removed from nav)
  - [x] ~~Created `book-call-v3.html` (v3) with high-converting design~~ (removed)
  - [x] ~~Added "Lead Projection v2" to navigation for internal testing~~ (removed)
  - [x] Integrated LeadConnector calendar embed into `book-call.html`
  - [x] Fixed FAQ expansion behavior (independent opening)
  - [x] Updated FAQ content to mention "Trial Lead Tests"
  - [x] Updated ad spend estimates to "$150M+ in 5 years" across all pages

---

---

## Recent Updates (January 2026)

### Content & Branding Updates
- [x] **Updated ad spend messaging** — Changed from "$20M" to "$150M+ in 5 years" across all pages
- [x] **Added quote attribution on About page** — "James LaRosa, Owner @ LeadPop" with custom styling
- [x] **Refined About page quote styling** — Multiple iterations to match desired horizontal layout

### Navigation & Page Management
- [x] **Unified header navigation** — Standardized navigation across all pages (Home, About, How It Works, Get Your Lead Projection)
- [x] **Removed book-call-v3.html** — Deleted older booking page version
- [x] **Removed "Lead Projection v2" link** — Cleaned up navigation (get-projection.html remains but not in nav)
- [x] **Fixed navigation active states** — Proper highlighting of current page across all pages

### Booking Page Improvements (book-call.html)
- [x] **Removed call details section** — Cleaned up redundant information (15-30 minutes, Video/phone, No obligation)
- [x] **Updated FAQ** — Clarified call length to "Plan for 30 minutes" and specified Zoom as preferred method
- [x] **GoHighLevel calendar customization** — Researched and provided custom CSS for vertical layout and branding

### Assets & Images
- [x] **Generated LeadPop logo (180x180)** — Created square version for GoHighLevel calendar
- [x] **Generated headshot (180x180)** — Properly cropped and resized James's headshot without distortion
- [x] **Generated LeadPop icon (180x180)** — Extracted icon from full logo for calendar use

### Deployment
- [x] **GitHub repository setup** — Initialized git, created repository, configured remote
- [x] **Pushed to GitHub** — All website files committed and pushed to https://github.com/JamesL6/LeadPop-Website
- [x] **GitHub Pages enabled** — Live site at https://jamesl6.github.io/LeadPop-Website/

---

## Currently Working On
- [ ] **Contact Page** — General contact form (distinct from booking flow)
- [ ] **Select Final Booking Page** — Decide between v1, v2, and v3 designs
- [ ] **Emphasize $30M lead revenue stat** — Make this more prominent across the website

