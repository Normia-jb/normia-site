# NORMIA_SITE_IMPLEMENTATION_CHECKLIST_V1

## Objective
Create a practical, launch-ready site restructuring sequence that is product-first, low-risk, and aligned with the current NORMIA Platform strategy. This checklist focuses on V1 only and avoids URL migration, Solutions, Academy, and enterprise-level architecture.

## Target navigation
- Home
- Platform
- Resources
- Contact

---

## 1. Exact files to modify

- `index.html`
- `plattform/index.html`
- `plattform/field-worker/index.html`
- `plattform/knowledge-engine/index.html`
- `plattform/supervisor/index.html`
- `system/index.html`
- `metodikk/index.html`
- `bruk/index.html`
- `eksempel/index.html`
- `revisjoner/index.html`
- `pdf/index.html`
- `README.md` (optional: align repo guidance)
- `ROADMAP.md` (optional: align phase language)

## 2. Exact files to create

- `contact/index.html`
- `resources/index.html`

> Note: No file moves or URL migrations in V1. Existing product pages remain at `/plattform/...`.

## 3. Homepage implementation sequence

1. Update `index.html` so the homepage is clearly product/platform focused.
2. Replace the current menu labels so the product section is presented as `Platform` instead of `Plattform`.
3. Add a hero section with:
   - clear headline about platform operation
   - the value chain: `Task → Execution → Photo → Control → Documentation → FDV`
   - primary CTA: `Contact us` or `Join pilot`
4. Add a short module summary for Field Worker, Knowledge Engine, Supervisor.
5. Add a concise pilot/customer outcome section: less admin, faster quality, FDV-ready delivery.
6. Add a link block to the `Resources` landing page.
7. Add a footer with the final nav and contact CTA.

## 4. Navigation implementation sequence

1. Standardize the global header on all modified pages.
2. Use the new top-level nav labels:
   - Home → `/`
   - Platform → `/plattform/`
   - Resources → `/resources/`
   - Contact → `/contact/`
3. Ensure the same nav appears on:
   - `index.html`
   - `plattform/index.html`
   - `plattform/field-worker/index.html`
   - `plattform/knowledge-engine/index.html`
   - `plattform/supervisor/index.html`
   - all `Resources` entry pages (`system`, `metodikk`, `bruk`, `eksempel`, `revisjoner`, `pdf`)
   - the new `contact/index.html`
4. Keep page-specific sub-navigation minimal and consistent; avoid separate nav patterns for each section.
5. Add a persistent CTA in the header: `Contact` or `Pilot`.

## 5. Platform page implementation sequence

1. Update `plattform/index.html` to become a unified platform overview page.
2. Ensure the page explains how the three modules connect and why the platform exists.
3. Keep `plattform/field-worker/index.html`, `plattform/knowledge-engine/index.html`, `plattform/supervisor/index.html` active and refine each page to:
   - state the module purpose in practical terms
   - explain benefit to customer roles
   - tie the module back to the platform value chain
   - add a clear contact CTA
4. Add a short “How it works together” section on `plattform/index.html`.
5. Avoid adding new product pages beyond the existing module pages in V1.

## 6. Resources page implementation sequence

1. Create `resources/index.html` as a hub page.
2. In `resources/index.html`, link to:
   - `/system/`
   - `/metodikk/`
   - `/bruk/`
   - `/eksempel/`
   - `/revisjoner/`
   - `/pdf/`
3. Update each existing reference page (`system`, `metodikk`, `bruk`, `eksempel`, `revisjoner`, `pdf`) to:
   - include the new global nav
   - add a short context statement: “This is the resource section for NORMIA’s execution and compliance guidance.”
   - add a back link to `Resources`
4. Do not restructure the reference content in V1; keep existing page locations.
5. Do not create a separate Academy section in V1.

## 7. Contact page implementation sequence

1. Create `contact/index.html`.
2. Keep contact content simple and practical:
   - short intro: pilot contact / demo request
   - email link: `info@normia.no`
   - optional phone line or contact form placeholder if supported later.
3. Add a note about pilot interest and a brief “What we are looking for” sentence.
4. Add the new page to the global nav.
5. Add direct links to `Contact` from homepage and all product pages.

## 8. Content archive list

Archive or deprioritize content that is not needed for V1 launch:

- `academy/_master.html` – archive or leave disconnected until there is public academy content.
- `/pdf/templates/` – keep for internal export support, but do not surface in nav.
- Any metadata or template-only content not visible in the new nav.
- Duplicate navigation/ancillary page fragments that do not contribute to the platform story.

## 9. Rollback plan

1. Preserve all existing files and do not delete any content during V1.
2. Use content edits only; keep original pages intact in source control.
3. If the new homepage or nav is not accepted, revert changes in:
   - `index.html`
   - `plattform/index.html`
   - `resources/index.html`
   - `contact/index.html`
   - any updated module or resource pages
4. If `resources/index.html` must be removed, restore the prior nav links from the original pages.
5. Keep the legacy URLs active throughout, with no redirects required in V1.

## 10. Estimated effort

- Homepage refresh: 4–6 hours
- Navigation standardization across pages: 4–6 hours
- Platform page refinements: 6–8 hours
- Resources hub creation: 3–4 hours
- Contact page creation: 1–2 hours
- Review and QA: 3–4 hours

### Total estimated effort
- 18–26 hours (2.5–3.5 working days)

---

## Notes
- This checklist is implementation-ready for V1.
- It keeps the current site structure intact while shifting the public story toward a platform-first presentation.
- It avoids URL migration, Solutions, Academy, and enterprise-level complexity in this first phase.
