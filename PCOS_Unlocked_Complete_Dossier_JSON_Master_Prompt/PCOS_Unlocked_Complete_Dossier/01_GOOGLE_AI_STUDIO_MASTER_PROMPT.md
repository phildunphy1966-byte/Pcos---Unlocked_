# MASTER PROMPT — GOOGLE AI STUDIO
You are a senior UX designer, visual communication designer, health-education content designer and expert frontend engineer.

Build a **complete, responsive, multi-page website** called **PCOS Unlocked** with the tagline **“Understand your body. Question the myths. Find your way forward.”**

The project dossier in `00_COMPLETE_PROJECT_DOSSIER.md` is the source of truth. The JSON files define structured project requirements and routes. The SVG assets in `/assets/` are original visual assets. Read and follow all of them.

## Do not build only a landing page
Implement every route in `02_routes.json`. Populate every page with real, concise educational content based on the dossier and `03_page_content.json`. No lorem ipsum, blank routes or “coming soon” placeholders.

## Required experience
- Multi-page routed website, not one long landing page.
- Shared foundation plus female learning and male ally pathways.
- Optional age bands: Under 18, 18–21, 22–25, 26–30, 31–35, Above 35.
- Age/pathway selection can be skipped, changed or reset at any time.
- Shared information remains accessible to everyone.
- Header, footer, breadcrumbs, search, related links and working browser history.
- All routes load directly and survive refresh.
- Responsive mobile, tablet and desktop layouts.

## Pages and content
Implement all route IDs and page content from the supplied JSON. At minimum include Home, Start, Know Your Body, anatomy, menstrual cycle, hormones, metabolism, Understand PCOS, features, diagnosis, health associations, management, female pathway, male ally pathway, Explore, myths/facts, quiz, FAQs, Find Support, appointment preparation, resources, About, Sources, Accessibility, Privacy and a 404 page.

## Interactions
Implement working:
- mobile navigation;
- route and pathway selection;
- optional age selection;
- search with results and empty state;
- breadcrumbs and related-topic navigation;
- interactive SVG diagram hotspots with accessible text alternatives;
- menstrual cycle stepper;
- accordion and tabs;
- myth/fact choice and explanation;
- educational quiz with per-answer feedback, restart and no diagnostic score;
- print-friendly appointment preparation;
- scroll-to-top where useful.

Every visible button, card and menu item must do what its label says. Do not leave decorative controls that appear interactive.

## Visual direction
Use a contemporary editorial health-education style. Warm cream base, deep plum text, muted coral and sage accents, lilac panels, generous whitespace, clear typography, crisp diagrams, labelled visual explanations and calm motion. Avoid childish cartoons, generic hospital stock photography, pink-only gender coding and clutter.

Use the provided local SVG assets. Do not copy the reference website's assets, text or layout. Any additional image must have verified reuse rights and attribution; otherwise create original SVG/CSS illustrations.

## Medical and privacy safety
This is education, not diagnosis. Display the disclaimer. Do not create symptom checkers, diagnosis tools, medication dose advice, cure promises, health risk scores, cycle tracking or sensitive health data collection. Do not imply that weight, diet, stress or menstrual products cause PCOS. Do not imply all people with PCOS have ovarian cysts. Distinguish adult and adolescent diagnostic guidance. Use PCOS as the primary term; mention emerging terminology only with context and a cited source. Make the male route an ally education path, not a male patient journey.

The supplied CSVs are not male/female awareness surveys. Do not derive gender comparisons from them. Do not present their data as Indian population prevalence or causal evidence.

## Accessibility
Use semantic HTML, logical headings, skip link, keyboard access, visible focus, ARIA semantics, contrast checks, alt text, text alternatives for diagrams, reduced-motion support and responsive touch targets.

## Technical implementation
Use a maintainable component architecture and a proper router. Create reusable header/footer, cards, breadcrumbs, accordions, tabs, diagram hotspots, quiz, source list, disclaimer and search components. Use a route configuration. Keep content data separate from layout. Avoid broken external image dependencies.

## Completion and testing
Before finishing:
1. Enumerate all implemented routes.
2. Test every route directly and after refresh.
3. Test all links, cards, buttons, menus, search, tabs, accordions, hotspots, stepper, quiz and print.
4. Test browser back/forward.
5. Test mobile and desktop layouts.
6. Test keyboard-only navigation and visible focus.
7. Test reduced-motion behaviour and text alternatives.
8. Check no lorem ipsum, dead links, fake sources or diagnostic features.
9. Report honestly any feature not completed.

Build the entire application now. Prioritise clarity, evidence-aware content, accessibility and smooth navigation over decorative effects.
