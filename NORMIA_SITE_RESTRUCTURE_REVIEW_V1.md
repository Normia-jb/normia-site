# NORMIA_SITE_RESTRUCTURE_REVIEW_V1

## Executive assessment

The plan is directionally strong because it recognizes the need to shift NORMIA from a methodology-first site to a platform-first narrative. It correctly isolates product messaging from reference materials and highlights pilot acquisition, but it currently leans toward an overly broad structure and risks adding complexity before the product story is fully consolidated.

Overall recommendation: GO with a phased, product-first implementation; NO-GO on full URL renames and deep content restructuring until the homepage and navigation prove the new platform position.

## What is strong in the plan

- It correctly identifies the main problem: the current site is too much like a standards repository and not enough like a platform offering.
- The proposed separation of `Product`, `Solutions`, and `Resources` is a useful principle for clarity and trust.
- It preserves important existing assets such as `/metodikk/`, `/system/`, `/bruk/`, `/eksempel/`, and `/revisjoner/` rather than discarding them.
- The plan explicitly centers the platform value chain: `Task → Execution → Photo → Control → Documentation → FDV`.
- It makes pilot acquisition visible and calls for a dedicated pilot CTA and pilot program page.
- The recommendation to keep copy practical and customer-focused is aligned with the core product principle.

## What is weak

- The new sitemap is too expansive for this site’s current content and may create navigation clutter.
- The `About` section and many optional future pages add risk of overengineering without clear immediate value.
- `/resources/academy/` is proposed despite there being no real public academy content today.
- The plan assumes redirects are straightforward, but the current static HTML repo may not support easy 301 redirects without extra hosting/config work.
- The migration plan is vague on a real content audit; it says “tag pages” but does not define a concrete cleanup or deprecation process.
- The proposal to move `/bruk/` to `/resources/usage/` or `/resources/how-to/` introduces ambiguity; it should choose one clean label.

## What should be simplified

- Collapse `Solutions` and `About` until the product story is proven. A leaner menu is better.
- Replace the optional `future pages` list with a minimal viable site map: `Home`, `Product`, `Resources`, `Contact`.
- Keep `Product` and `Resources` as the core areas. Avoid separate `/solutions/` and `/about/` if content is limited.
- Fold PDF support into `Resources` without giving it a top-level navigation item if it is not a key audience entry point.
- If `academy/_master.html` is not customer-facing, do not make `/resources/academy/` part of the primary restructure until there is actual content.

## What should be removed

- Remove the proposal to surface `/resources/academy/` unless there is a real learning resource ready.
- Remove the “optional future pages” section from the immediate plan; it is not needed for execution and may distract.
- Remove duplicate or inconsistent navigation rules in favor of a single global nav model.
- Remove the idea of a separate `/about/pilot/` page if the pilot CTA can live on `/contact/` and the homepage.
- Remove any suggestion that PDF templates should be public navigation items if they are only internal/export support.

## What should be implemented first

1. New homepage with strong platform positioning and the value chain front and center.
2. Consistent global navigation across the whole site.
3. Product module landing pages for Field Worker, Knowledge Engine, and Supervisor.
4. A dedicated pilot/customer CTA in the site header and homepage.
5. A simple `Product` section that explains the platform and its value rather than a deep new structure.
6. A lightweight content audit of existing pages to identify outdated content, duplicates, and low-value legacy pages.
7. A mapping of current pages to the new IA without moving files yet.
8. A redirect feasibility check for the deployment environment.
9. A small `Resources` landing page that links to existing methodology and system pages.
10. A soft-launch staging copy of the new nav and homepage while keeping current pages live.

## What should wait

- A full file-system relocation of all pages to `/product/`, `/resources/`, and `/about/`.
- Creating a separate `/solutions/` section until there is enough distinct content to justify it.
- Introducing new public `/resources/academy/` content or navigation.
- Deep URL restructuring and redirect rollout until the redirect plan is validated.
- Formal archiving of content before a final review of what is truly outdated.

## Top 10 implementation priorities

1. Product-first homepage with clear pilot CTA.
2. Unified global navigation on all pages.
3. Product module pages with customer benefits and pilot contact.
4. Value chain page or section that maps to customer workflow.
5. `Resources` hub page that groups methodology and system references.
6. Content audit checklist for each existing page.
7. Redirect feasibility review for hosting environment.
8. Legacy page access plan: keep old pages while linking to the new IA.
9. Remove or archive internal/template-only pages such as `academy/_master.html`.
10. Clear naming decision for `/bruk/` and other resource paths before moving files.

## Clear GO / NO-GO recommendation

- GO: Implement the new plan in a phased, low-risk way by starting with homepage, navigation, and product positioning.
- GO: Keep the current content accessible while introducing the new structure.
- GO: Preserve the methodology and compliance pages as trusted resources, not as the main landing experience.
- NO-GO: A wholesale move of pages and URLs before a content audit and redirect validation.
- NO-GO: Adding a deep `Solutions` or `About` layer before the product story is stable.

## Alignment with evaluation criteria

1. Product clarity
   - The plan is strong here, but it would benefit from an even tighter top-level structure.
2. Pilot customer acquisition
   - Good emphasis, but pilot messaging should be simpler and more urgent.
3. Simplicity
   - The current plan is slightly overcomplicated; simplify to core product and resource areas.
4. Navigation logic
   - The principle is sound, but the actual proposed menu has too many branches.
5. Content hierarchy
   - The split between Product and Resources is good; avoid extra intermediate layers.
6. Technical feasibility
   - The static site can support the changes, but redirect assumptions must be checked.
7. Risk of overengineering
   - High if the plan tries to launch all new sections at once.
8. Risk of keeping outdated legacy content
   - Moderate; the plan preserves too much without enough decisive cleanup.
9. Alignment with NORMIA Platform
   - Good overall alignment; the plan captures the platform value chain and the product shift.
10. Monday 07:00 usability
   - The plan is ready in principle, but the execution path should be narrowed to a minimal launchable version.

## Final verdict

The plan is a solid strategic starting point, but it must be tightened before implementation. Focus on a lean site with a clear product homepage, a small product section, and a single `Resources` area. Delay major URL moves and extra navigation layers until the new platform story has been validated.
