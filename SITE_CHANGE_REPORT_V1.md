# SITE_CHANGE_REPORT_V1

## Files changed
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
- `resources/index.html`
- `contact/index.html`

## Summary of changes
- Updated the homepage to a platform-first message with the core NORMIA principle: documentation is a result of work.
- Created a new `Resources` hub page to centralize system, methodology, use, example and revision content.
- Created a new `Contact` page with a pilot/customer inquiry call to action.
- Standardized navigation across main site pages to the target structure: Home / Platform / Resources / Contact.
- Improved the Platform overview page to explain the value chain and module connections.
- Improved the Field Worker page to emphasize field execution, photo capture and auto-generated documentation.
- Improved the Knowledge Engine page to emphasize metadata, register value and platform connection.
- Improved the Supervisor page with updated messaging, consistent branding, and the new contact call to action.

## Screens affected
- Home page (`/`)
- Platform overview (`/plattform/`)
- Field Worker module (`/plattform/field-worker/`)
- Knowledge Engine module (`/plattform/knowledge-engine/`)
- Supervisor module (`/plattform/supervisor/`)
- System page (`/system/`)
- Metodikk page (`/metodikk/`)
- Bruk page (`/bruk/`)
- Eksempel page (`/eksempel/`)
- Revisjoner page (`/revisjoner/`)
- Resources hub (`/resources/`)
- Contact page (`/contact/`)

## Outstanding issues
- `academy/_master.html` remains unchanged and is not surfaced by the new navigation; it is outside V1 scope.
- `pdf/` content remains in place but is not directly linked from the new global navigation; it is accessible from the Resources hub paragraph.
- Resource subpages such as `/metodikk/prosjektering/`, `/metodikk/utforelse/`, `/metodikk/kontroll/`, and `/metodikk/fdv/` still use legacy internal navigation patterns. A follow-up pass may be needed if broader resource nav standardization is required.
- No URL migration or redirects were implemented in this phase, per scope.
- There is no contact form; the Contact page currently uses `mailto:` only.

## Recommended next steps
1. Review the updated pages in a browser to confirm nav links and visual consistency across sections.
2. Update resource subpage headers and navigation if the next phase includes deeper resource standardization.
3. Optionally add a lightweight contact form or tracking mechanism for pilot inquiries.
4. Consider surfacing the `pdf/` page or a direct link from the Resources hub for easier access.
5. Validate that the updated copy is aligned with the product story, especially in the platform and module pages.
