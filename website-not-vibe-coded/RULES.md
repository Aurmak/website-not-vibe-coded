# How to build a website that doesn't look vibe-coded

Rules for building any marketing or product website, for a person or an AI. They were learned on one build and apply to all of them. Where a rule has a reason, the reason is given, because the reason is what stops the rule being gamed.

## 1. How to work

1. **Plan first, build when told.** Read the brief, ask the questions, write the plan, agree it. Don't start building until the owner says so. Planning and building are different modes; mixing them produces a site nobody asked for.
2. **One page first.** Build the most important page, get it approved, then do the rest. The first page sets the standard for everything after it.
3. **Wait for the references and the brand assets.** No visual design starts until the owner has supplied the reference sites or screenshots, the logo and any colours they own. The references are the North Star for layout, type, spacing and colour, and they override a brief's palette if the owner says so.
4. **Confirm before reversing a choice.** If an audit suggests undoing something the owner chose, ask about that item on its own. A one-word "ok" to a list of suggestions is not consent to remove their decisions.
5. **A question is not an instruction.** "Do we need X?" is answered, not built.
6. **Commit locally, push only when asked.** Pushing may deploy. Say what is committed and wait for the word.
7. **Audit after building, in order:** QA, design audit, SEO audit, copy pass. Fix everything that doesn't reverse an owner decision; list what does.
8. **Keep internal documents out of the public repository.** Plans, pricing workings, competitor notes, research and audits stay git-ignored.

## 2. Truth rules

A site that overclaims reads as generated, because generated copy overclaims by default.

1. **Only confirmed claims.** Every feature, timing, measure and promise must exist, or be explicitly agreed as a launch commitment.
2. **No invented testimonials, logos, case studies, stats or numbers.** If there are none, the site has none. Fake social proof is the most common tell there is.
3. **No internal numbers:** margins, costs, headcount, counts of customers or units, unless the owner wants them public.
4. **Certifications and audits in progress say so:** "working towards", "we'll update this page when it's issued".
5. **Hedge where the product depends on conditions:** "we can usually", not "we always".
6. **Say what the product does not do.** A short "what we chose not to do" builds more trust than a long feature list.
7. **History is a fact, not a track record.** A founding year appears once, on one page, never as "since", "over N years" or "trusted since".
8. **Never name without permission:** the technology stack, vendors, hosting providers, hardware brands, or any customer or client. Describe instead of naming when you must refer to one.
9. **Locations only if the owner decides.** Many businesses sell everywhere and don't want to look local.
10. **Legal pages are final from the day they're published.** No draft notes, no placeholders in brackets, no "last updated". Every clause must match what the site and product actually do. Remove clauses that can't yet be stated truthfully rather than guessing them.
11. **Third-party facts are attributed.** "Source: <publisher>" with a link; paraphrase, don't quote at length; don't name victims or vendors on the page; claim nothing the linked reporting doesn't support.
12. **Use the product's own words for its features.** Don't substitute a grander term for what the thing actually does.

## 3. Copy voice

Write like a person who has done the reader's job and knows what hurts. Plain, direct, not warm, not salesy.

**Do**
- Talk to the reader as "you". Name their real problems in their words.
- Short sentences. Plain words. Say it once. Cut repetition across pages.
- Specific over clever. A concrete sentence about what happens beats a slogan about how it feels.
- State facts and let the reader decide. One clear call to action where it belongs, no pressure.
- Pick one spelling convention for the audience and keep it.
- Use the words buyers actually search for, in the first sentence under a headline and in page titles, naturally, never stuffed.

**Never**
- Em dashes or en dashes as punctuation. Exclamation marks. Emoji.
- Hype words: seamless, elevate, unlock, empower, robust, cutting-edge, leverage, streamline, revolutionise, harness, delve, journey, game-changer, next-level, effortless, supercharge, transform, holistic, synergy, ecosystem, solution(s), state-of-the-art, best-in-class, world-class.
- AI patterns: "In today's fast-paced world", "Whether you're X or Y", "It's not just X, it's Y", "Say goodbye to", "Imagine a world", three-fragment stacks ("Fast. Simple. Secure."), a rhetorical question opening every section, colon-led headlines, every list in threes.
- Over-explaining, urgency tricks, a demo button on every block.
- Being overly warm. Friendly is fine; gushing is a tell.
- Repeating a message or a call to action on one page. Two buttons to the same destination become one. If a page exists for a topic, other pages link to it instead of restating it.
- Clutter lines that add nothing under a headline (tax notes, disclaimers, a price repeated from elsewhere).

**Check before handover:** an automated scan for the banned words and patterns, then a read-aloud pass. If a sentence sounds like an advert, rewrite it. If a paragraph sounds stupid read aloud, it is.

## 4. Visual design

**Never**
- Default font pairings: one sans at flat weights, the usual system or framework fonts everywhere.
- Out-of-the-box component-library looks: stock dark mode, the same large radius on every card, default grey borders, framework-default backgrounds.
- Icon grids with a coloured box behind every icon.
- Eyebrow labels (small uppercase text above a heading). Headings stand on their own.
- Decorative pills or badges. Pills only for live status data.
- Glowing gradient blobs, radial blurs, neon, glassmorphism, unless the references show them.
- Cards inside cards. Keep the structure flat.
- The whole page stacked down one centred column.
- Captions under photos. Describe a photo in its alt text, never in visible text beneath it.
- Oversized icons. Icons are small, consistent and few.
- Images squeezed into small boxes, or a small hero image. Photos get room.
- Vector animations standing in for real photographs and video. Use real images, or generated images made to a brief, where a scene is needed.
- Backgrounds behind control bars or interactive controls. Controls sit on the page.

**Always**
- Asymmetric, left-aligned grid. Offset columns. Everything snaps to grid lines.
- Generous white space, uneven on purpose: more above a heading than below it.
- Colour budget: about 90% neutrals and exactly one accent, used only for primary actions, active states and focal points. Take the accent from the logo, or its contrast. Only the logo shows the full brand palette together.
- Dramatic type scale: large heavy headings, small legible body, several weights. A characterful heading face, a quiet body face, and a monospace for numbers that should feel like real data.
- Buttons that look like buttons, standard form fields, quiet hover states (a darken, a nudge), no glows.
- Dark sections in deep tones, not pure black or saturated blue-black. Alternate dark and light bands for rhythm instead of decoration.
- One signature shape taken from the logo or the brand, used in a few places only (photo crops, feature frames) so it stays special. If the owner likes it, keep it.
- A two-tone headline (the last words in the accent) is allowed once, in the hero.
- Band rhythm that means something: the most serious section gets the darkest band.
- The logo at a size that reads on desktop and phone. Any parent company gets one line in the footer and one link, nothing more.

**Reference handling**
- One reference site is a mood, not a template. Take the feel (one colour family in shades, dark hero and footer, heavy headings, a plain FAQ, a short closing band). Leave out what breaks the rules above.
- No text, images, icons, layout order, illustrations or code from the reference. Different typeface, different accent, different shape language. Stay clear of copyright trouble.

## 5. Page and component specifics

- **Hero:** headline, one sentence, two buttons at most, one large photo or a live demo that can overlap into the next section. No price note, no eyebrow, no stats row.
- **Section headings:** no eyebrows; a smaller subheading only when a term needs clarifying.
- **Feature lists:** typographic (bold line, short sentence) on the grid, not icon cards. An odd last item spans the full width rather than leaving a gap.
- **Interactive demos:** bigger than feels comfortable; controls aligned with their labels; elements side by side at the same angle rather than overlapping; labels above the things they label; the explanation under the section title; no status chips the demo doesn't need; one control changes everything it should.
- **Photos:** real scenes, large, in the signature frame if there is one; descriptive file names (`what-the-photo-shows-1600.jpg`, not `img1.jpg`); multiple sizes with `srcset`; remove stray logos or wrong details from generated images before use; the first image on the page has fetch priority, the rest load lazily.
- **Forms:** full-width fields; radio options in equal columns across the form width; selects with the chevron clear of the edge; the submit button full width; only the fields that are needed; no privacy line under the button if a privacy page exists; error and success messages that say what to do next.
- **Calculators and sliders:** large; a number and its unit must never wrap or separate at any width; no empty space above the result; one call to action.
- **FAQ:** a plain accordion, thin borders, a plus icon, questions people actually ask before buying, one answer each.
- **Footer:** parent-company line if any, a few columns of links, legal links on the base line. Column titles are styled text, not headings, so they don't pollute the page outline.
- **Cookie banner:** honest about what's set; Reject and Accept only; no "cookie settings" re-open; the choice stored once; nothing non-essential loads before Accept.
- **External links:** open in a new tab with `rel="noopener"` and a visually hidden "(opens in a new tab)".
- **Mobile:** every layout rechecked at phone width; never fix a desktop layout with inline styles that then override the phone layout; use classes.

## 6. Technical hygiene that makes it look built, not generated

- Self-hosted fonts in woff2, preloaded; nothing from third-party font or script hosts.
- One stylesheet, hand-edited. Never delete CSS by regex; it breaks selectors silently. The build fails on unbalanced braces.
- Cache-busting on CSS and JS.
- Descriptive page titles (under 60 characters) and unique meta descriptions; one h1 per page; alt text on every image.
- Structured data only where it's true: organisation, product with real prices, FAQ from the real questions, website name.
- One branded social share card for the whole site, rendered at 2x, with width, height and alt tags; a new file name whenever it changes so caches can't serve the old one; author and publish date meta tags.
- Favicon as SVG plus a 48px ICO fallback, and an apple-touch-icon.
- Sitemap and robots.txt generated, noindex pages excluded; a real 404 page with a 404 status.
- Canonical domain decided (with or without www) and the other redirected; http to https at the host.
- Lighthouse above 95 in all four categories before launch; an uptime monitor after.

## 7. Audits, and what they look for

**QA:** every link; the contrast of every text and control colour pair; layout at four widths; forms with empty and bad input; interactive parts in every state; the 404 page; the cookie banner in a fresh browser.

**Design audit:** count sections per page and cut; find duplicate messages and calls to action; find anything on the banned list; check every image size; check that each page has one job.

**SEO audit:** search terms present naturally; titles and descriptions; heading outline; structured data; internal links in body copy, not only menus; image file names; share image; indexing.

**Copy pass:** banned-word scan; read aloud; cut repetition; every sentence talks to the reader, not about the product.

**Alignment check (once the product exists):** every claim on the site matched against the product, with the result in three lists: true, oversold, undersold. Fix the site or the product; never leave the gap.

## 8. The test at the end

Show the site to someone who builds websites for a living and ask one question: "Could you tell this was made with AI?" If they hesitate, find the tell and remove it. The usual tells, in order of frequency: a dash in a sentence, an eyebrow label, a pill, a glow, three fragments in a row, a centred column of cards, a stock sans at one weight, a claim with no source, and copy that sounds pleased with itself.
