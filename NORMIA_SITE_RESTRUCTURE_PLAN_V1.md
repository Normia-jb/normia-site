# NORMIA_SITE_RESTRUCTURE_PLAN_V1

## 1. Current structure assessment

### Site purpose and current focus
- The repository is a public website for NORMIA, largely built as an HTML-based methodology/reference site.
- Current homepage and platform pages already mention NORMIA Platform and the value chain, but the broader site remains dominated by traditional methodology content.
- The site currently mixes product-oriented landing content with normative operations documentation in the same navigation and structure.
- There are two visible content themes:
  - Platform/product messaging: `/`, `/plattform/`, `/plattform/field-worker/`, `/plattform/knowledge-engine/`, `/plattform/supervisor/`
  - Methodology/reference system: `/system/`, `/metodikk/`, `/bruk/`, `/eksempel/`, `/revisjoner/`, `/pdf/`

### Page inventory and categories
- `index.html`: general Platform landing page with module overview and CTAs.
- `/plattform/`: product presentation entry point.
- `/plattform/field-worker/`, `/plattform/knowledge-engine/`, `/plattform/supervisor/`: module pages with product messaging and pilot call-to-action.
- `/system/`: describes system structure, document logic, versioning, and normative rules.
- `/metodikk/`: contains the main methodology landing page and four procedural documents (prosjektering, utførelse, kontroll, fdv).
- `/bruk/`: practical usage guidance and process steps.
- `/eksempel/`: illustrative example project narrative to show workflow.
- `/revisjoner/`: revision log and current published version table.
- `/pdf/`: PDF export templates and generated docs; likely support-only content.
- `/academy/_master.html`: template-like content that appears to be a design/data model example, not currently surfaced in navigation.

### Structural observations
- The product narrative is present but isolated mainly under `/plattform/`.
- Site navigation is inconsistent between pages; each section uses its own local nav.
- The public URL structure is shallow but semantically mixed, with methodology and product content at peer level.
- There is no explicit marketing-oriented “Why NORMIA” or “Who should use it” page.
- The current content framing is internal and operational rather than externally oriented to pilot customers.

## 2. Problems with current structure

### Problem 1: mixed positioning
- Product platform pages exist, but they are not integrated with the main site structure.
- Visitors land on a methodology-heavy site that feels more like a standards repository than a platform solution.
- The platform story is diluted by the presence of normative documentation at the same visual hierarchy.

### Problem 2: unclear customer journey
- There is no clear funnel from homepage to pilot acquisition.
- Calls to action are weak and spread across pages without a dedicated pilot/customer path.
- External visitors cannot easily distinguish between product pages and internal method references.

### Problem 3: inconsistent navigation
- Each section uses its own header and nav scheme, creating cognitive friction.
- The main menu does not reflect NORMIA’s current platform strategy clearly.
- The site lacks a single, product-centric global navigation structure.

### Problem 4: outdated content taxonomy
- `system`, `metodikk`, `bruk`, `eksempel`, `revisjoner` are still styled like an internal documentation set.
- The platform modules are not fully promoted as core business offerings.
- Content like `academy` and PDF templates is not clearly surfaced or categorized.

### Problem 5: poor external visibility for platform modules
- `Field Worker`, `Knowledge Engine`, and `Supervisor` exist, but their connections to common customer pain points are not explicit.
- The platform value chain is mentioned but not presented as a customer workflow.
- The site fails to show how the modules combine into a coherent, pilot-ready platform.

## 3. Recommended information architecture

### Guiding principles
- Position NORMIA as a platform company first, with methodology as supportive evidence.
- Keep documentation as an outcome, not the primary navigation entry point.
- Use simple product-oriented language and clear customer paths.
- Preserve normative content for customers who need trust and compliance details, but separate it from the product landing experience.
- Support pilot customer acquisition with clear messaging, trust signals, and actionable contact points.

### Proposed top-level IA
1. Home
2. Product
   - Overview
   - Field Worker
   - Knowledge Engine
   - Supervisor
   - Value Chain
3. Solutions
   - Task to FDV workflow
   - Use cases
   - Pilot program
4. Resources
   - Methodology
   - System
   - Example
   - Academy / Learning
   - Revisions
   - PDF
5. About
   - About NORMIA
   - Contact / Demo / Pilot

### Rationale
- Separate product messaging (`Product`, `Solutions`, `About`) from supporting reference content (`Resources`).
- Keep customer-facing pages high in the hierarchy.
- Preserve the existing methodology pages in a clearly labeled resource section for partners, auditors, and system users.

## 4. New sitemap

### Recommended sitemap structure
- `/` – Homepage: Platform positioning, value chain, modules, pilot CTA.
- `/product/` – Product overview: what NORMIA Platform does.
- `/product/field-worker/` – Field Worker module.
- `/product/knowledge-engine/` – Knowledge Engine module.
- `/product/supervisor/` – Supervisor module.
- `/product/value-chain/` – Task → Execution → Photo → Control → Documentation → FDV.
- `/solutions/` – How NORMIA solves customer workflows.
   - `/solutions/task-to-fdv/` – end-to-end workflow narrative.
   - `/solutions/pilot/` – pilot customer program, eligibility, contact.
- `/resources/` – Resources hub.
   - `/resources/methodology/` – Methodology landing.
   - `/resources/system/` – System structure and document logic.
   - `/resources/example/` – Example project.
   - `/resources/academy/` – Learning resources and templates.
   - `/resources/revisions/` – Revision log.
   - `/resources/pdf/` – PDF export and template explanation.
- `/about/` – Company and contact.
   - `/about/contact/` – contact and demo request form or mailto.
   - `/about/pilot/` – pilot invitation and next steps.

### Optional future pages
- `/product/integration/` – integrations and ecosystem.
- `/resources/terms/` – terms and conditions for pilots.
- `/about/team/` – leadership and credibility.

## 5. Homepage redesign proposal

### Homepage focus
- Audience: pilot customers, decision-makers, early adopters.
- Messages:
  - NORMIA is an operational platform, not just a methodology.
  - Documentation is created as a natural result of work.
  - The platform connects Field Worker, Knowledge Engine, Supervisor.
  - The value chain is the product story.
  - The pilot program is front and center.

### Recommended homepage sections
1. Header
   - Logo / brand
   - Primary nav: Product / Solutions / Resources / About
   - Pilot CTA button: `Become a pilot` or `Book demo`
2. Hero
   - Short headline: “Operativ plattform for byggeprosjekter hvor dokumentasjon oppstår som et resultat av arbeidet.”
   - Subtext: “Task → Execution → Photo → Control → Documentation → FDV.”
   - Primary CTA: `Join pilot program` / `Contact us`
   - Secondary CTA: `See platform modules`
3. Value chain section
   - Visual list of the six platform stages.
   - One-line benefit for each stage.
4. Product module summary
   - Three cards: Field Worker, Knowledge Engine, Supervisor.
   - Each card: what it does, customer benefit, link to module page.
5. Customer outcomes
   - Simple bullets or short statements: fewer handoffs, faster compliance, higher quality, ready-for-FDV.
6. Pilot program section
   - Clear invitation, who should participate, what they get.
   - Contact path / email.
7. Resource preview
   - Link to methodology, system, example, revisions for trust.
8. Footer
   - Links to all major sections, contact info, copyright.

### Design and copy principles
- Keep copy practical, not marketing-heavy.
- Use customer language: “contractors”, “project managers”, “site teams”, “quality teams”.
- Emphasize the platform outcome: less admin, more control, better handover.
- Avoid internal labels as navigation items; keep product labels external-facing.

## 6. Navigation redesign proposal

### Global navigation structure
- Home
- Product
- Solutions
- Resources
- About
- CTA button: `Pilot / Contact`

### Product submenu
- Overview
- Field Worker
- Knowledge Engine
- Supervisor
- Value Chain

### Solutions submenu
- Task to FDV workflow
- Pilot customers
- Use cases (optional)

### Resources submenu
- Methodology
- System
- Example
- Academy
- Revisions
- PDF

### About submenu
- About NORMIA
- Contact
- Pilot program

### Navigation principles
- Keep the top-level menu lean and product-oriented.
- Move deep operational documentation into `Resources`.
- Ensure every page includes the same global nav and the same footer links.
- Include a persistent CTA button in the header for pilot/demo requests.
- Avoid page-specific, inconsistent nav bars across sections.

## 7. Content migration plan

### Phase A: structure and navigation
1. Create new product and solutions page scaffolding in a staging area.
2. Map existing pages to the new sitemap.
3. Keep current pages live while staging new IA content offline.

### Phase B: content classification
- Tag each current page as one of:
  - product messaging
  - workflow/use case
  - trusted reference
  - support/template
- Identify pages that should remain as-is, move, or be archived.

### Phase C: page migration
- Move `/plattform/` pages into `/product/`.
- Copy `/system/`, `/metodikk/`, `/bruk/`, `/eksempel/`, `/revisjoner/`, `/pdf/` under `/resources/` namespace or leave them accessible with redirects.
- Create a new homepage and revise links to point to the new IA.
- Maintain existing URLs during transition with redirects from legacy paths to preserve SEO and bookmarks.

### Phase D: content rationalization
- Consolidate duplicate or overlapping content before publishing.
- Reframe methodology pages as “Resources for project execution and compliance.”
- Add clear signposts on resource pages back to the product story.

### Phase E: launch and validation
- Validate navigation, external links, and CTA paths.
- Review page titles and descriptions for product positioning.
- Ensure pilot contact/email is available on at least three key pages.

## 8. What content should stay

### Keep in place
- Current main homepage messaging, with stronger product focus.
- `/plattform/field-worker/`, `/plattform/knowledge-engine/`, `/plattform/supervisor/`: keep content and reframe into product pages.
- `/metodikk/` and its core methodology documents: essential trust-building reference.
- `/system/`: valuable explanation of structure, versioning and trust.
- `/bruk/`: practical guidance that supports platform adoption.
- `/eksempel/`: useful example for customers and partners.
- `/revisjoner/`: important audit and trust page.
- `/pdf/`: keep as support documentation for exports and templates.
- Roadmap guidance in `README.md` and `ROADMAP.md` to maintain strategic continuity.

### Keep but relocate/relabel
- The platform entry page should become `/product/overview/` or `/product/`.
- `academy/_master.html` should either become a surfaced learning resource under `/resources/academy/` or remain as an internal staging template if not currently user-facing.

## 9. What content should move

### Move to product section
- `/plattform/` pages → `/product/`.
- Platform module content should live under a unified `product` namespace.
- Module overview should become a product landing page or a `product/overview` page.

### Move to resources section
- `/system/` → `/resources/system/`
- `/metodikk/` → `/resources/methodology/`
- `/bruk/` → `/resources/usage/` or `/resources/how-to/`
- `/eksempel/` → `/resources/example/`
- `/revisjoner/` → `/resources/revisions/`
- `/pdf/` → `/resources/pdf/`

### Move content into workflow story
- Extract the platform value chain content from home and product pages into `/product/value-chain/` or `/solutions/task-to-fdv/`.
- Use the `Document Once, Reuse Many` principle as a narrative thread across product and solution pages.

## 10. What content should be archived

### Archive or deprioritize
- Internal or template-only pages that are not customer-facing and do not contribute to platform positioning.
- `academy/_master.html` unless it is intentionally surfaced to customers; archive as source material or reorganize into a real learning page.
- Any duplicate navigation or content fragments in the current site that only exist to support internal structure.
- PDF export templates under `/pdf/templates/` may remain but should not be first-class navigation items; archive them behind the Resources hub.

### Archive candidate content
- Any stale content inside `/academy/` that is not polished for public use.
- Technical page sections with no external audience, such as specific editorial metadata examples.

## 11. Recommended page hierarchy

### Top-level
- Home
- Product
- Solutions
- Resources
- About

### Product section
- Product Overview
- Field Worker
- Knowledge Engine
- Supervisor
- Value Chain

### Solutions section
- End-to-end workflow
- Pilot program
- Use cases / customer outcomes

### Resources section
- Methodology
- System
- Example
- Academy
- Revisions
- PDF

### About section
- About NORMIA
- Contact / Demo
- Pilot details

### Example hierarchy diagram
- Home
  - Product
    - Overview
    - Field Worker
    - Knowledge Engine
    - Supervisor
    - Value Chain
  - Solutions
    - Task to FDV
    - Pilot program
  - Resources
    - Methodology
      - Prosjektering
      - Utførelse
      - Kontroll
      - FDV
    - System
    - Example
    - Academy
    - Revisions
    - PDF
  - About
    - Contact
    - Pilot

## 12. Recommended URL structure

### Product URLs
- `/product/`
- `/product/field-worker/`
- `/product/knowledge-engine/`
- `/product/supervisor/`
- `/product/value-chain/`

### Solutions URLs
- `/solutions/`
- `/solutions/task-to-fdv/`
- `/solutions/pilot/`
- `/solutions/use-cases/` (optional)

### Resources URLs
- `/resources/`
- `/resources/methodology/`
- `/resources/methodology/prosjektering/`
- `/resources/methodology/utforelse/`
- `/resources/methodology/kontroll/`
- `/resources/methodology/fdv/`
- `/resources/system/`
- `/resources/example/`
- `/resources/academy/`
- `/resources/revisions/`
- `/resources/pdf/`

### About URLs
- `/about/`
- `/about/contact/`
- `/about/pilot/`

### Redirect strategy
- Preserve legacy URLs during migration with 301 redirects:
  - `/plattform/` → `/product/`
  - `/plattform/field-worker/` → `/product/field-worker/`
  - `/plattform/knowledge-engine/` → `/product/knowledge-engine/`
  - `/plattform/supervisor/` → `/product/supervisor/`
  - `/system/` → `/resources/system/`
  - `/metodikk/` → `/resources/methodology/`
  - `/bruk/` → `/resources/usage/` or `/resources/how-to/`
  - `/eksempel/` → `/resources/example/`
  - `/revisjoner/` → `/resources/revisions/`

## Practical pilot acquisition recommendations

- Make pilot contact immediate on the homepage and every product module page.
- Add a short pilot eligibility section on `/solutions/pilot/`:
  - Who should join
  - What they get
  - What commitments are required
- Use simple copy: “We are looking for a few pilot projects in renovation and new build where digital execution, photo-based control and FDV handover matter.”

## Final recommendation summary

- Rebase the website around the platform narrative and separate product pages from methodology resources.
- Keep current methodology content, but move it into a clear `Resources` area.
- Create a consistent global navigation and a single pilot/demo CTA.
- Treat the homepage as a product landing page first, not a standards index.
- Preserve trust via `System`, `Methodology`, `Example`, `Revisions`, and `PDF`, but do not let these pages dominate the public-facing hierarchy.
- Implement the new architecture in a pilot-phase transition, preserving legacy URLs with redirects.

> Monday 07:00 Rule: this plan is ready for execution at the start of the next working week. The focus is on clarity, platform communication, and enabling pilot customer acquisition with a simple, usable site structure.
