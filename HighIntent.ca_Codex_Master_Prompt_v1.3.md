# HighIntent.ca | Codex master prompt

**Version 1.7 · 27 November 2026 · High Intent Inc.**

## 1. Build the High Intent website

Build HighIntent.ca for **High Intent Inc.** High Intent helps companies across Canada get in front of buyers who already want what they sell. A B2B buyer may be comparing suppliers, checking specifications or preparing a request for a quote. Help that buyer discover the client’s brand, verify what the company can deliver and explain to colleagues why it belongs on their shortlist. High Intent serves businesses in every industry.

Write primarily for companies selling to other businesses, across industries. Address the person building a supplier shortlist, the colleagues weighing the offer and the sales team answering their questions. Companies serving both business and consumer buyers can use the same services. Tailor each engagement to the client’s offer, audience, market and buying process. Use this positioning in page copy, footers, intake, metadata and social previews in both languages. Remove any public self-description using “agency” or “agence” during copy review. Claims of past work in a particular industry require evidence.

Read this brief before making changes. Inspect the supplied project, its instructions, assets, build commands and hosting configuration. If the site source is present, reuse its Node static generator, shared layouts, locale content and paired routes. For a fresh build, keep client-side JavaScript minimal and produce static output compatible with WHC Pro shared hosting and a Sites preview. Record the actual build command and output directory.

Complete the phases below in order. Use reversible defaults for open design decisions and continue through implementation when asked to build. A request to run a single phase ends with that phase’s deliverables. The master prompt lives in [GrafovGroup/HighIntent](https://github.com/GrafovGroup/HighIntent). Connect form delivery and production hosting when the owner supplies the destinations and commissions release.

## 2. Identity and operating defaults

| Item | Direction |
|---|---|
| Brand and domain | Use **High Intent** in prose and **High Intent Inc.** for the legal name and footer copyright. The owner has acquired **HighIntent.ca**. |
| Geographic scope | High Intent serves businesses across Canada. For each campaign, agree on the audience and markets the client can actually serve. |
| Who can hire High Intent | Businesses in every industry, including those selling to consumers, to other businesses or to both. Organise services into brand development and demand capture. Lead with examples that B2B owners, marketing leaders and sales teams recognize. |
| Buyer and ownership model | High Intent manages the campaigns. Each client owns its ad accounts, inquiry records and customer relationships. Each inquiry goes to the company the buyer contacted. Clients pay media platforms directly. |
| Visual direction | The approved emblem is the standalone white speech bubble containing a dark lowercase **hi**. Use it on its own at every size in English and French. The company name, domain and tagline are never attached to the bubble. |
| Colour | Use the redesigned site’s near-black, graphite and platinum palette. Keep colours in shared design tokens and use the values in section 5. |
| Slogan | A slogan remains optional editorial copy. Set the introductory line and editable headline as live text in the page layout, separate from the emblem. |
| Geography and language | Serve Canada nationally from launch. Deliver complete English and Québec-appropriate French experiences. |
| Contact defaults | Use **info@highintent.ca** as the sole public contact address on the site and in structured data. Centralize the email address and confirm mailbox delivery during launch handoff. |

## 3. Offer, delivery and commercial terms

| Engagement | What the client receives | Commercial model |
|---|---|---|
| Brand or website project | Agree on a concrete handoff such as a messaging guide, a domain shortlist or buyer-facing website pages. For an acquisition the client approves outreach, spending and purchase terms and controls the registrar account. | Scope deliverables and fees with the client. |
| Demand review | Identify the offer, intended customers, markets and sales goal. Review search demand, existing pages, inquiries and known sales outcomes. Deliver a prioritised opportunity brief, an agreed definition of a useful conversion, a proposed landing page and a measurement plan. | Scope and quote separately or include it in setup. Make the distinction clear in the proposal. |
| Campaign setup | Set up search campaigns for the agreed audience, build or improve landing pages, connect measurement and route inquiries to the person responsible. | One-time setup fee. Quote the scope. Document client access and separate service fees from media costs. |
| Managed demand generation | Manage search terms and exclusions, improve organic content and landing pages, and reconcile campaign activity with sales outcomes. Give the client a monthly report and a short list of actions. | Monthly service fee with an agreed scope. Additional markets, languages or integrations can be priced separately. |

**Start with one offer and one audience.** Agree on the buyer’s next step and how the client will recognise success. A demo request may matter to a software company, a booking to an appointment-based business, and a completed purchase to a retailer. These illustrate how the same services adapt. Use an example on a service page only when it helps explain a decision.

**Campaign scope.** Choose search terms, exclusions, geography and follow-up based on what that client sells and whom it can serve. Treat repeat purchases, one-time sales and long buying cycles according to their economics. Avoid guarantees about inquiry counts, sales, rankings, close rates or returns.

## 4. Build sequence

1. **Phase 0 · Establish the source.** Inventory the project, brand artwork, locale content, existing forms and deployment settings. Capture confirmed details and preview defaults in one short decision record. Preserve unrelated work.
2. **Phase 1A · Apply the approved emblem.** Use the supplied [standalone “hi” SVG](public/brand/bubble.svg) as the source for the header, footer, favicon, social profile and share cards. Preserve its proportions when resizing or exporting. Check it at phone-header and favicon sizes.
3. **Phase 1B · Design the homepage.** Preview the homepage in English and French on desktop and mobile. Use the monochrome identity, original abstract hero and both actions from section 7. A first-time visitor should understand how High Intent helps their company reach buyers who are ready to act.
4. **Phase 2 · Implement the site.** Build the bilingual page pairs in section 6, including the eight service details. Preserve the former industry URLs as redirects. Keep the case-study template gated on real evidence. Connect the primary consultation path throughout the site.
5. **Phase 3 · Prepare search, measurement and delivery.** Complete metadata, language routing, discovery files, inquiry handling and the checks below. Hand over the connections the owner must supply.
6. **Phase 4 · Release when commissioned.** Use the provided GitHub repository and chosen hosting destination for approved release work. Keep preview and production settings distinct. Report the actual commit, destination and deployment status when those operations occur.

## 5. Visual identity and art direction

- **The emblem.** Keep the supplied rounded white-to-platinum bubble, its short lower-left tail, and the dark lowercase h and dotted i. The SVG contains the letter outlines and can be rendered directly without loading a font. Use the emblem alone in every brand placement, including the 404 page and the Organization logo in structured data. Keep clear space around it.
- **Palette.** Use near-black `#08090A` for the page, graphite `#141517` for surfaces, platinum `#F5F5F3` for primary text, muted silver `#B0B1B5` for secondary text and `#35363A` for fine dividers. The primary action is a light pill with dark text. Check text, controls and focus states against their actual backgrounds.
- **Typography and layout.** Aim for a minimal, futuristic and elegant site. Use DM Sans, generous margins, large live headlines, short paragraphs and fine rules between service rows. Use text-only labels for links on service rows and website tiles. Keep button labels in sentence case. Give the primary action visual priority and keep EN / FR accessible on desktop and mobile. The owner’s reference for spacing, typography and restraint is [Portfolite](https://www.framer.com/marketplace/templates/portfolite/).
- **Artwork.** Use the Low light horizon in `public/images/low-light-horizon.webp` across the English and French site. Centre live headings over the near-black upper field, with softly lit grayscale ridges below. Set the homepage’s second headline line and each service’s buyer benefit in italic serif. Set project names in DM Sans inside compact matte charcoal circles. Use charcoal sections with fine dividers for detailed content and shorter headers above the consultation and domain-offer forms. Pair the horizon, the “hi” emblem and the localised title on share cards.

## 6. Pages and language pairing

Use one stable content ID per page and a route map for localised slugs. The following are preferred paths for a new site. If an existing site has valuable indexed routes, preserve them or map deliberate redirects. Give `/` a predictable default destination of `/en/` in a fresh build. Every published route has an English and a French counterpart.

| Page | English route | French route |
|---|---|---|
| Home | /en/ | /fr/ |
| Services | /en/services/ | /fr/services/ |
| Domains for sale | /domains/ | /fr/domaines/ |
| Engagements and process | /en/how-we-work/ | /fr/notre-approche/ |
| About | /en/about/ | /fr/a-propos/ |
| Canadian coverage | /en/canada/ | /fr/canada/ |
| Consultation and contact | /en/contact/ | /fr/contact/ |
| Privacy | /en/privacy/ | /fr/confidentialite/ |

**Service detail pages.** Link to all eight services from both the homepage and the Services hub. On the homepage, group the first three under “Build your brand” / “Développer votre marque” and the other five under “Capture demand” / “Capter la demande”. Each detail page uses its localised service name as the H1, followed by a buyer benefit and a link to request a consultation.

| English service | Québec French service | English / French slugs | What to explain |
|---|---|---|---|
| Brand strategy and positioning | Stratégie et positionnement de marque | brand-positioning / strategie-de-marque | Trace a buying decision and deliver a positioning statement and messaging guide the sales team can use. |
| Domain acquisition | Acquisition de noms de domaine | domain-acquisition / acquisition-de-noms-de-domaine | Compare names, agree on budget and outreach, and coordinate an approved transfer to the client’s registrar account. Link buyers looking for a listed domain to the separate Domains directory. |
| Website and digital presence | Site Web et présence en ligne | digital-presence / presence-en-ligne | Review what buyers find, build pages that demonstrate capabilities with approved examples, and align the company profiles the client controls. |
| Paid search | Publicité sur les moteurs de recherche | paid-search / publicite-sur-les-moteurs-de-recherche | Explain how the client chooses an offer, audience, market, search terms, exclusions and spend. |
| Organic search | Référencement naturel | organic-search / referencement-naturel | Show how pages answer the questions people ask before choosing an offer and help them assess fit. |
| Landing pages | Pages de destination | landing-pages / pages-de-destination | Pair one visitor intent with an appropriate action, such as requesting a demo, booking, asking for a quote or purchasing. |
| Inquiry management | Gestion des demandes | lead-management / gestion-des-demandes | Describe call tracking, forms, assignment to sales and follow-up in a customer relationship management system or a shared tracker. |
| Campaign reporting | Rapports de rendement | reporting / rapports-de-rendement | Connect spend to the client’s agreed conversions and sales. Where sales reviews inquiries, distinguish acceptance, proposal and outcome. Keep the labelled sample sales record on this page. |

**Former industry pages.** Permanently redirect the former English industry hub (`/en/who-we-help/`) and its five former detail URLs to `/en/services/`. Redirect the former French hub (`/fr/secteurs/`) and its five former detail URLs to `/fr/services/`. Keep these retired addresses out of navigation and the sitemap. The legacy detail slugs below are used only to resolve existing links.

| Under `/en/who-we-help/` | Under `/fr/secteurs/` |
|---|---|
| `commercial-cleaning/` | `entretien-menager-commercial/` |
| `facility-maintenance/` | `entretien-des-immeubles/` |
| `commercial-restoration/` | `restauration-apres-sinistre/` |
| `commercial-security/` | `services-de-securite/` |
| `industrial-services/` | `services-industriels/` |

**Case studies.** For a future case-study collection, reserve `/en/case-studies/` and `/fr/etudes-de-cas/` until there is approved, attributable material in both languages.

**National coverage.** Cover all ten provinces and three territories when describing High Intent’s coverage. Prepare reusable province, territory, city and metro templates and release location pages when there is useful, documented local content. Prioritise Toronto/GTA, Montréal, Vancouver, Calgary, Edmonton, Ottawa–Gatineau, Québec City, Winnipeg and Halifax as content supports them. Do not imply that High Intent or its clients have unverified local offices or staff. Keep unpublished routes out of the sitemap.

## 7. Approved homepage copy

Use the headline and supporting line below verbatim in each language. Set the H1 as live text. Begin its italic second clause after “buy,” in English and “acheter,” in French. Let each clause wrap naturally on phones. Use the same headline on the corresponding homepage share image.

| Element | English | Français québécois |
|---|---|---|
| Line above the headline | CAPTURING HIGH INTENT | CAPTER L’INTENTION D’ACHAT |
| Headline | When buyers are ready to buy, be the brand they find. | Quand vos clients sont prêts à acheter, soyez la marque qu’ils trouvent. |
| Supporting copy | We help you capture demand from buyers already searching for what you sell | Nous vous aidons à capter la demande des acheteurs qui cherchent déjà ce que vous vendez |
| Primary action | Request a consultation | Demander une consultation |
| Secondary action | Explore B2B services | Voir nos services B2B |
| Navigation | Services · Approach · Domains · Contact | Services · Notre approche · Domaines · Contact |
| Services heading | Get on the buyer’s shortlist. | Faites partie des fournisseurs à consulter. |
| Consultation invitation | Which buyers do you want to reach? | Quels acheteurs souhaitez-vous joindre? |

Use four homepage sections in this order.

1. **Hero.** Show the introductory line, headline and supporting copy over the abstract artwork. The primary action opens Contact in the current language. The secondary action jumps to the services on the same page.
2. **Projects.** Present the approved website names as links in the compact circles, with the daily lead-generation line above them. Each link opens the project in a new tab.
3. **Services.** Group the eight services under brand building and demand capture. Give each service one linked row with its buyer benefit. Link to Approach for the engagement process and commercial model.
4. **Consultation invitation.** Close with the question above and one consultation action. Keep intake on Contact, the sample report on Reporting, and About, Coverage and Privacy in the footer.

Write natural, concise French for Québec. Translate navigation, labels, metadata, alt text where meaningful, validation messages, confirmation screens and empty states. Use the same “hi” emblem in both locales.

## 8. Consultation intake, qualification and reporting

- **Consultation intake.** Ask for name, company, email, what the business offers and which markets it serves. The optional goals prompt is “What would you like this project to achieve?” / “Que souhaitez-vous accomplir avec ce projet?” The visitor’s own phone number and website are optional form fields. During discovery, discuss intended customers, budget, capacity and how sales are recorded.
- **Delivery.** Reuse an existing approved form provider where available. Make the endpoint configurable. Validate fields on the receiving side or through the provider, add spam protection, handle duplicate submissions and show a translated success message only after confirmed acceptance. On error, preserve input and offer a retry or direct email. When delivery is unconfigured, show a working email link in place of the submit action. Use a booking CTA only once a working calendar is supplied.
- **Privacy and consent.** Explain how submitted details will be used to respond and link to the matching privacy page. Keep any optional newsletter or promotional opt-in separate and unchecked. Configure optional tracking according to the site's approved consent settings. Draft privacy copy around the vendors and data flows actually in use. Obtain the owner’s privacy contact and review the copy before release.
- **Sales handoff.** For an inquiry-led campaign, agree with the client on qualification, ownership, response time and who records outcomes. Define fit using the buyer’s need, the offer, market and timing. Merge repeat contacts about the same opportunity. Record missed calls and reasons for disqualification so the client can act on them.
- **Client reporting.** Measure the buying process the client actually uses. For an inquiry-led sale, follow unique inquiries through sales acceptance, the relevant next step and the won, lost or pending outcome. For a direct sale, use confirmed purchases and attributable revenue where records support them. Track setup fees, ongoing service fees and media spend separately. Media cost per qualified opportunity is attributable media spend divided by unique accepted opportunities for the same campaign and period. With zero accepted opportunities, show the count and leave the ratio blank. Distinguish proposed value from confirmed revenue. Record the reporting date and account for the length of the buying cycle.
- **High Intent’s own analytics.** Distinguish consultation-button click, consultation start, successful submission and sales acceptance of the consultation request. Email clicks indicate contact intent. Keep names, phone numbers, email addresses and free-text form responses out of analytics and URLs.

## 9. Search, accessibility and release criteria

**Editorial standard · Google E-E-A-T**

Start with the decision the reader came to make. Where first-hand experience helps, use work the publisher can document and share. Identify who produced or reviewed technical guidance where readers would expect it, and explain the method when it affects interpretation. Support consequential claims with the most relevant original source. Claim outside recognition or credentials only when readers can verify them.

For a pilot in any industry, document the client’s offer and market, reporting period, conversion definition, method, source records and permission to publish the outcome and attribution. Credit the work High Intent performed and identify the outcomes the client verified. Label hypothetical sales records or example journeys in both languages. A statement that the services apply across industries describes availability. Claims about work performed or results achieved require supporting records.

At content review, trace a material claim on a representative page back to its source. Correct, qualify or omit an unsupported claim, including in translated copy and structured data where present. [Google Search Central](https://developers.google.com/search/docs/fundamentals/creating-helpful-content) · [Universal master prompt](https://github.com/GrafovGroup/MasterPrompt/blob/main/MASTER_PROMPT.md).

Generate unique English and French titles, descriptions and social previews. Use one clear H1 per page, descriptive internal links, self-referencing production canonicals, reciprocal en-CA/fr-CA hreflang links and an x-default route consistent with the selected default. Build the sitemap and robots file from real published routes. Include factual Organization, Service and Breadcrumb structured data where appropriate. Give preview deployments a noindex setting and check the production setting separately. Keep location claims, reviews and schema aligned with visible evidence.

Serve responsive, compressed images with explicit dimensions. Prioritize the hero, lazy-load secondary imagery, respect reduced-motion preferences, and keep the mobile menu, forms and language switch keyboard-operable. Label the header and footer home links “High Intent · Home” in English and “High Intent · Accueil” in French. Use an empty alt attribute on the emblem inside these labelled links. Build narrow layouts for longer French labels. The language switch must open the corresponding page at any depth.

**Definition of done for the site build**

- The documented command produces a static output directory. A direct visit or refresh on an English or French nested page works on the target host. Missing pages return a useful 404.
- Both languages include Home, Services, the eight service details, Approach, Contact, Coverage, About and Privacy. Each published route opens its translation. Check that a visitor selling products or services can identify what High Intent offers and complete the consultation path without choosing an industry. All 12 former sector URLs return a permanent redirect to Services in the matching language. Case-study routes only go live with approved evidence.
- On a small phone, the “hi” emblem, CTA, French menu and language switch are legible. Check the homepage at desktop and mobile widths. The live headline stays legible over the abstract artwork in both languages. Verify that the header, footer, favicon and localised share cards use the same standalone bubble. Confirm focus order, form labels, text contrast and reduced-motion behaviour.
- A valid request produces either verified delivery to the intended recipient in the configured environment or an explicit owner action in the handoff with contact fallback in place. Check invalid input, provider errors, repeat taps and successful confirmation. Report which path was actually exercised.
- Published claims have a source or owner approval. No invented client logos, rankings, guarantees, employee counts, addresses, reviews, certifications, screenshots of results or revenue claims appear in pages or metadata.
- Deliver the source files, reusable brand assets, locale and route configuration, sample environment variable names without secrets, build/deploy instructions and a short owner handoff. List what was implemented, what was verified, where the editable content lives, and what still needs a real account, destination or decision.
- For an authorized launch, confirm HTTPS, apex/www routing, canonical host, form receipt and production indexing settings on the real domain. Submit the sitemap to Google Search Console and Bing Webmaster Tools when the owner has provided access. Report submissions separately from observed indexing.

## 10. Owner handoff

Close with a short decision table for the owner recording the standalone “hi” emblem as approved on 24 November 2026. List the monochrome palette, optional slogan, destination repository/host, live contact routing, provider configuration and verified proof of work with their current status. Distinguish preview-ready work from items connected and checked on the public domain.

**Suggested first pilot.** Select one willing client in any industry. Agree on one offer, one audience, a measurable buying action and a source for confirming the outcome. Record the baseline, period and results. Obtain the client’s permission before publishing a case study.
