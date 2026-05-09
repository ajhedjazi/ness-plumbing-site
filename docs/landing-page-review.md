# Ness Plumbing & Heating — Landing Page Review

## Overall score
8.5 / 10

## Summary
The landing page is visually strong, high-contrast, and conversion-focused. Core messaging is clear, contact routes are prominent, and local trust is supported by service area copy, customer reviews, and FAQ schema. The main opportunities are tactical refinements around mobile UX, SEO polish, trust details, and a few content/link placeholders.

## Top 10 highest-impact improvements
1. Replace placeholder Google review QR/link and Gas Safe number with live business details.
2. Fix or simplify mobile menu toggle behavior so mobile navigation is reliable and does not depend on unused JS.
3. Update footer service links from `#` placeholders to real anchors or remove them to avoid friction and improve internal linking.
4. Add a stronger local signal in the hero with a brief mention of "Hull & East Yorkshire" inside the H1-subline or first paragraph.
5. Improve the contact form UX with clear success/validation messaging and an ARIA role for better accessibility.
6. Use an OG image more service-focused than the logo for better social preview appeal.
7. Add a visible reassurance element near the top CTA that confirms "No call-out fee" or "Gas Safe registered" next to the phone button.
8. Ensure the phone CTA uses `tel:` across all major CTA buttons and the mobile sticky CTA for consistent click-to-call.
9. Add schema enhancements such as `openingHoursSpecification` and `sameAs` or `address` if available.
10. Make the FAQ/FAQ schema content more directly aligned with common Hull plumbing search queries.

## Section-by-section notes

### Header
- Strong brand and phone CTA visibility.
- Good use of anchor navigation and mobile sticky CTA.
- Issue: footer service links are placeholders (`href="#"`) and should point to actual sections.
- Suggestion: add `aria-label` to the mobile menu button is already good; ensure the menu hide/show behavior is functional.

### Trust strip
- Clear service categories and local coverage.
- Good use of bold, simple trust messaging.
- Consider adding one short proof point like "Gas Safe registered" or "100% recommended" in this strip for more credibility.

### Hero
- Headline clearly establishes emergency plumbing and boiler repairs.
- CTA buttons are visible and action-oriented.
- The page should more explicitly name the service area in the hero copy for local relevance, e.g. "Hull & East Yorkshire emergency plumbing".
- The right stats panel is strong; if possible, add a small line about actual review count or years of experience.

### Services
- Cards are well structured and easy to scan.
- The top label "WHAT WE FIX" is strong.
- The last service card includes a CTA button; consider repeating this button pattern for consistency across all service cards or converting the cards into actual anchor links.

### Why Us
- Strong brand messaging and service differentiation.
- Good emphasis on speed, professionalism, reliability, and local coverage.
- The grid of reasons is clear and reinforces trust.
- Potential improvement: add one specific trust proof, like "Gas Safe registered" or "Fast response in HU postcodes" in the left panel.

### Reviews / Popular Call-Outs
- The popular call-outs section is good for surfacing key services.
- Labeling this section as "Reviews" in the ID is slightly confusing; ensure internal section names match visible headings if used for navigation or anchor links.
- Consider adding a single small review snippet or rating badge here to tie the section to trust.

### Recent Work
- The work gallery is a strong visual trust asset.
- Good use of alt text and data attributes for the lightbox.
- Mobile users can benefit from an explicit instruction like "Tap to enlarge" near the grid.
- Verify the image URLs are optimized and the hero image has a descriptive OG preview if shared.

### Customer Reviews
- Customer reviews are prominent and persuasive.
- Good mention of Facebook recommendations and a link to Checkatrade.
- The Google review CTA is currently a placeholder; replacing it with a live review link is high priority.

### Booking CTA
- The call-to-action is strong and repeated well.
- The form is simple and conversion-focused.
- Improvements:
  - add `name` attributes to inputs if the form is functional;
  - use a more explicit button state if submitted;
  - ensure the `select` default option is not valid to avoid accidental submission.
- Keep the strong message that the business will call back within 10 minutes.

### FAQ
- The FAQ section matches the FAQ schema, which is good for search appearance.
- Copy is clear and service-focused.
- Improve SEO by including more exact local phrases such as "Hull emergency plumber" and "East Yorkshire heat pump servicing" in responses.

### Google Review / Footer
- The review CTA is good, but the QR code and review URL are placeholders and must be updated.
- The footer includes useful contact details but lacks an actual physical address or service area structured markup.
- Gas Safe number appears as `000000000`; this should be corrected or removed if not the real number.

## Conversion improvements
- Add a local trust line near the main CTA: "Hull & East Yorkshire emergency plumbing service".
- Ensure the mobile sticky CTA is present on all screens and the action text is clear.
- Replace non-functional `#` footer links with anchors or remove them to reduce dead-click friction.
- Add a quick-win trust badge near CTAs: "No call-out fee" / "Gas Safe registered" / "24-hour response".
- Use clearer confirmation language on the booking form and ensure the default select option cannot be submitted as a real issue.

## SEO improvements
- Title/meta are already strong; refine the title slightly if desired to prioritise local search: "Emergency Plumbing, Boiler Repairs & Heat Pump Service in Hull | Ness Plumbing & Heating".
- Keep the existing H1 and support it with richer local copy in the first paragraph.
- Update OG image to a service or local service photo rather than only the logo.
- Add `openingHoursSpecification` and `sameAs` or local business social links to schema if available.
- Convert footer placeholder links into real internal page anchors.
- Consider adding a small `address` block or microcopy with the business service area and locality to reinforce local SEO.

## Mobile UX improvements
- Verify the mobile menu toggle works as intended; currently the JS toggles a `show` class that is not defined in the CSS.
- The sticky CTA is excellent; keep it and ensure it remains above interactive elements without covering form fields.
- Ensure the hero text and CTA stack cleanly on smaller screens; the current layout appears mobile-ready.
- Keep the form fields large and tappable, and confirm the select dropdown is easy to use on mobile.
- Add a tiny spacing refinement under the mobile review section to prevent cramped text in the bottom sticky area.

## Quick wins
- Replace the placeholder Google review link and QR target with the actual review URL.
- Replace the placeholder Gas Safe number with the real registered number.
- Fix footer `href="#"` links to real anchors or remove the placeholder links.
- Add a short local proof phrase near the hero CTA.
- Fix the mobile menu toggle either by adding the `show` rule or removing the unused JS logic.

## Longer-term improvements
- Add one or two small trust badges/highlights such as actual review count, Gas Safe, and emergency availability badge.
- Expand schema with opening hours, address, and service links.
- Consider a stronger service preview OG image for social sharing.
- Add richer local SEO phrases to review and FAQ copy while preserving the existing tone and layout.
- Monitor performance and conversion after updating the review link and local CTA wording.

## Recommended implementation order
1. Correct placeholders and trust details: Google review link/QR, Gas Safe number, footer links.
2. Fix mobile menu behavior / verify mobile navigation UX.
3. Enhance hero/local messaging with explicit Hull/East Yorkshire wording.
4. Strengthen CTA trust with a short reassurance badge near the main call button.
5. Refine SEO schema and OG image for better search and social previews.
6. Improve footer anchors and internal linking to reduce friction.
7. Polish FAQ and page copy for more exact local search phrases.
8. Add any extra trust badges or credibility signals once the core functional issues are resolved.
