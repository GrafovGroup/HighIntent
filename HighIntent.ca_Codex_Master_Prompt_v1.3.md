# HighIntent.ca | Codex master prompt

**Version 1.3 · 21 November 2026 · High Intent Inc.**

## 1. Build the agency website

Build HighIntent.ca for **High Intent Inc., a Canadian demand generation partner for commercial service companies.** High Intent helps contractors reach the businesses that need their services, generate qualified quote requests and site walkthroughs, and track which inquiries become contracts. Position it as a directly engaged marketing partner with a setup fee and ongoing management.

The customer paying High Intent is the service company. Its prospective buyers may be property managers, facility managers, plant operators, multi-site retailers or procurement teams. Distinguish those audiences everywhere. An owner visiting HighIntent.ca should recognise their business, see how High Intent could bring in the type of work they want, and request a consultation. A buyer looking to hire a cleaner, restoration firm or security provider should never mistake High Intent for that contractor.

Build the acquisition service into the homepage, navigation, offers, sector pages, forms, analytics and search metadata. Owner-operated sites may supply first-party experience or a documented pilot. Use those selectively as evidence. A portfolio directory, standalone brand-design studio and shared-lead marketplace are outside this website's positioning.

Read this brief once before making changes. Inspect the supplied repository, its instructions, existing assets, build commands and hosting configuration. Work in that project when supplied. For a fresh build with no existing stack, use a static site generator such as Astro with reusable layouts, local content and minimal client-side JavaScript. Produce static output compatible with WHC Pro shared hosting. Keep the same source suitable for an OpenAI Sites preview. Record the actual build command and output directory.

Complete the phases below in order. Use reversible defaults for open design decisions and continue through implementation when asked to build. A request to run a single phase ends with that phase’s deliverables. This brief does not supply a repository address, live form credentials or a production deployment target. Bind external services to the owner’s actual project when those details are supplied.

## 2. Identity and operating defaults

| Item | Direction |
|---|---|
| Brand and domain | High Intent Inc. is the business name. High Intent is the name in prose. **high intent** is the two-word visual wordmark. The owner has acquired **HighIntent.ca**. |
| Geographic scope | Canada-wide agency coverage. Target campaigns only inside each contractor’s actual service territory, for the services and job sizes it wants. |
| Initial customers | Commercial cleaning, high dusting and facility maintenance are the initial focus. Extend the same offer to restoration, commercial security and industrial service contractors. |
| Buyer and ownership model | High Intent manages the campaigns. Each client owns its ad accounts, inquiry records and customer relationships. Each inquiry goes to the company the buyer contacted. Clients pay media platforms directly. |
| Visual direction | Carry forward the **Say Hi** concept and the latest lowercase treatment. The speech bubble contains **hi**. Set **high intent** to its right. Omit “.ca” and “Inc.” from the logo. |
| Colour | **Working preview only:** palette 03, coral and deep plum on warm ivory. Palette 04, lilac on midnight indigo, is an available comparison. Neither palette has owner approval. Keep colours in shared design tokens. |
| Slogan | Open decision. Use the lowercase logo without a descriptor or slogan in the preview. Use an editable headline to explain the agency’s service. |
| Geography and language | Serve Canada nationally from launch. Deliver complete English and Québec-appropriate French experiences. |
| Contact defaults | **info@highintent.ca** and **(833) 696-9996**. Centralize both. Confirm mailbox delivery and the phone destination during launch handoff. |

## 3. Offer, delivery and commercial terms

| Engagement | What the client receives | Commercial model |
|---|---|---|
| Demand review | Identify the service lines, territories, building types and contract sizes the client wants. Review the current search terms, pages, inbound calls, quote process and known sales outcomes. Deliver a prioritised opportunity brief, qualification criteria, proposed landing page and measurement plan. | Scope and quote separately or include it in setup. Make the distinction clear in the proposal. |
| Campaign setup | Launch search advertising for agreed buying situations; build or improve service and location landing pages; connect call and form tracking, inquiry routing and a simple sales tracker. Agree on who follows up. | One-time setup fee. Quote the scope. Document client access and separate agency fees from media costs. |
| Managed demand generation | Manage campaigns, review search terms, exclude irrelevant traffic, improve organic search content, refine landing pages and reconcile inquiries with quotes and wins. Give the client a monthly report and a short list of actions. | Monthly service fee with an agreed scope. Additional territories, languages or integrations can be priced separately. |

**Start with a narrow campaign.** Select one commercial service and a territory the contractor can reliably cover. Document capacity, preferred job type, minimum viable job, exclusions and salesperson responsible for follow-up. Capture active demand with paid search and organic service pages. When justified, develop future demand through buying guides for facility managers, seasonal maintenance planning or follow-up to opted-in inquiries. A full website rebuild is an optional means of improving conversion; lead with outcomes and delivery.

**Illustrative buyer journey.** A warehouse manager needs overhead dust removed during a shutdown. A search for warehouse ceiling cleaning leads to a page covering access, ceiling height, areas served and overnight scheduling. The manager asks for a walkthrough. The contractor receives the details, checks fit, schedules the visit and records whether a quote was issued. This illustrates a workflow. Report actual results only from approved records.

**Offer boundaries.** Keep residential-only searches, job seekers, training requests, supply purchases and do-it-yourself traffic out of a campaign when they fall outside the client’s scope. Treat multi-location buyers, recurring contracts and one-time work differently when they have different economics. Do not promise inquiry counts, sales volume, rankings, close rates or minimum returns.

## 4. Build sequence

1. **Phase 0 · Establish the source.** Inventory the project, brand artwork, locale content, existing forms and deployment settings. Capture confirmed details and preview defaults in one short decision record. Preserve unrelated work.
2. **Phase 1A · Refine the selected identity.** Use the owner's lowercase Say Hi artwork if available. Derive a horizontal wordmark and standalone bubble suitable for the browser tab and social profile. If the source is unavailable, create an editable, flat preview reconstruction from section 5 and label its status in the handoff. The previous logo rounds already satisfy concept exploration.
3. **Phase 1B · Design the homepage.** Preview English and French layouts on desktop and mobile with the working colours, the consultation action, a sector-specific example and the commercial offer. Confirm the agency is recognisable before a visitor scrolls.
4. **Phase 2 · Implement the site.** Build the bilingual service and sector detail pages, engagement process, company, contact and coverage pages. Add a case-study template gated on real evidence. Connect the primary consultation path throughout the site.
5. **Phase 3 · Prepare search, measurement and delivery.** Complete metadata, language routing, discovery files, inquiry handling and the checks below. Hand over the connections the owner must supply.
6. **Phase 4 · Release when commissioned.** Use the provided GitHub repository and chosen hosting destination for approved release work. Keep preview and production settings distinct. Report the actual commit, destination and deployment status when those operations occur.

## 5. Visual identity and art direction

- **The mark.** Place the simple rounded speech bubble with its short lower-left tail beside the bold lowercase name. Put a true lowercase h and dotted i inside. Keep a visible word space in “high intent.” Align the bubble optically with the wordmark. At small sizes, use the bubble alone where the accessible name identifies the brand. Use an SVG or other scalable approved source for the final logo when available. Keep the legal name in the footer and formal documents.
- **Preview colours.** Coral `#F06348`, plum `#361833`, ivory `#FFF4E9`. Use plum text on ivory for reading and plum text inside the coral bubble. Start with a plum button and ivory lettering. Check text, controls and focus states on their actual backgrounds. For a palette comparison use lilac `#C7ABFF` and indigo `#211A43`.
- **Layout.** Build a wide, image-rich site with generous margins, rounded buttons, uppercase navigation and button labels, French accents intact. Keep the mark lowercase in both languages. Put the language switch in the top bar, including on mobile. Suggested typography: bold DM Sans or an equivalent geometric face for headings and a readable sans for body copy.
- **Show the buying situation.** Feature a credible facility walkthrough: for example, a facility manager and contractor reviewing overhead cleaning requirements in a working warehouse. Sector pages should use relevant, distinct commercial imagery. Keep the headline and navigation clearly about marketing services. Label illustrative examples. Use approved evidence for any client attribution, logos, job photography presented as past work, or performance results.

## 6. Pages and language pairing

Use one stable content ID per page and a route map for localised slugs. The following are preferred paths for a new site. If an existing site has valuable indexed routes, preserve them or map deliberate redirects. Give `/` a predictable default destination of `/en/` in a fresh build. Every published route has an English and a French counterpart.

| Page | English route | French route |
|---|---|---|
| Home | /en/ | /fr/ |
| Services | /en/services/ | /fr/services/ |
| Who we help | /en/who-we-help/ | /fr/secteurs/ |
| Engagements and process | /en/how-we-work/ | /fr/notre-approche/ |
| Case studies, once verified examples exist | /en/case-studies/ | /fr/etudes-de-cas/ |
| About | /en/about/ | /fr/a-propos/ |
| Canadian coverage | /en/canada/ | /fr/canada/ |
| Consultation and contact | /en/contact/ | /fr/contact/ |
| Privacy | /en/privacy/ | /fr/confidentialite/ |

**Service detail pages** under each language’s services hub:

| English / French slugs | Specific content |
|---|---|
| paid-search / publicite-sur-les-moteurs-de-recherche | Explain how the client chooses service lines, regions, search terms, exclusions and spend. Use a commercial contractor buying situation. |
| organic-search / referencement-naturel | Show how service pages answer commercial buyer questions, establish coverage and help a buyer assess fit. |
| landing-pages / pages-de-destination | Show how to convert active demand into a call, a walkthrough request or a request for pricing. Offer a sample page outline with a clear action. |
| lead-management / gestion-des-demandes | Describe call tracking, forms, assignment to sales and follow-up in a customer relationship management system or a shared tracker. |
| reporting / rapports-de-rendement | Explain the difference between inquiries, qualified opportunities, quoted work and won contracts. Show the report fields using a clearly marked illustrative example. |

**Sector detail pages** under the Who We Help hub. Each addresses a contractor considering hiring High Intent. Use an illustrative end-buyer example, the type of work sought and what makes that inquiry worth following up.

| English / French slugs | Example of a qualified opportunity for the contractor |
|---|---|
| commercial-cleaning / entretien-menager-commercial | A property manager requests a recurring cleaning quote for three offices in the service area and gives floor areas, service frequency and desired start date. Include specialist high dusting and a walkthrough example within this sector. |
| facility-maintenance / entretien-des-immeubles | A multi-site operator asks for a maintenance proposal for a defined property portfolio, scope and schedule. |
| commercial-restoration / restauration-apres-sinistre | A commercial property manager asks for a site assessment after water damage, provides the location and identifies an on-site contact. The contractor decides whether it can respond. |
| commercial-security / services-de-securite | A facility asks for guard coverage and supplies site type, shifts, location and anticipated start. |
| industrial-services / services-industriels | A plant manager requests a shutdown service quote with a defined scope, planned outage and access constraints. |

**National coverage.** Cover all ten provinces and three territories at the agency level. Prepare reusable province, territory, city and metro templates and release location pages when there is useful, documented local content. Prioritise Toronto/GTA, Montréal, Vancouver, Calgary, Edmonton, Ottawa–Gatineau, Québec City, Winnipeg and Halifax as content supports them. Do not imply that High Intent or its clients have unverified local offices or local crews. Keep unpublished routes out of the sitemap.

## 7. Homepage and preview copy

The hero headline is editable sales copy, separate from the logo.

| Element | English | Français canadien |
|---|---|---|
| Headline | Attract quote requests for the commercial work you want. | Recevez des demandes de soumission pour les contrats commerciaux que vous recherchez. |
| Supporting copy | High Intent helps commercial service companies reach facility and property managers, turn inquiries into site visits and quotes, and track which campaigns lead to contracts. | High Intent aide les entreprises de services commerciaux à joindre les gestionnaires d’immeubles et d’installations, à convertir les demandes en visites sur place et en soumissions, puis à suivre les campagnes qui mènent à des contrats. |
| Primary action | REQUEST A CONSULTATION | DEMANDER UNE CONSULTATION |
| Secondary action | SEE HOW IT WORKS | VOIR NOTRE APPROCHE |
| Navigation | SERVICES · WHO WE HELP · HOW WE WORK · CONTACT | SERVICES · SECTEURS · NOTRE APPROCHE · CONTACT |

1. **Hero.** Say what the agency does, for whom, and which opportunities it helps pursue. Primary action opens the consultation path.
2. **Show what qualifies.** Compare two useful but different inquiries: a recurring office-cleaning contract and a one-time warehouse walkthrough. Include the field that makes each useful to a salesperson.
3. **How the work happens.** Show service-area targeting, service pages, call/form tracking, sales follow-up and reporting. Link to the five services.
4. **Who we help.** Feature commercial cleaning and facility maintenance first, then the other three sectors. Write each card for the contractor buying marketing services.
5. **Engagement and evidence.** Explain the demand review, setup and monthly management. If there is an approved result, show the market, period, scope and evidence. Until then, show a sample deliverable identified as an example.
6. **Consultation.** Ask which commercial work the visitor wants more of and where they can deliver it. Provide form, email and phone. Keep About, Privacy and Coverage in the footer.

Write French for Québec audiences using “demande de soumission,” “occasion de vente” and “prise de rendez-vous” where appropriate. Keep the mark “hi” in both locales. Translate navigation, labels, metadata, alt text, validation messages, confirmation screens and empty states. Use natural, short copy with a clear verb in each action. Use measured results only when the client approves the evidence and attribution.

## 8. Consultation intake, qualification and reporting

- **Agency intake.** Ask for name, company, email, services offered, and service area. An optional prompt asks “What type of commercial contract would you like more of?” / “Quel type de contrat commercial souhaitez-vous décrocher plus souvent?” Phone and existing website are optional. Discuss media budget, available capacity and current sales process during discovery. Keep building dimensions and job specifications on the contractor's own quote form.
- **Delivery.** Reuse an existing approved form provider where available. Make the endpoint configurable. Validate fields on the receiving side or through the provider, add spam protection, handle duplicate submissions and show a translated success message only after confirmed acceptance. On error, preserve input and offer retry, email and phone. When delivery is unconfigured, show working mail and phone links in place of the submit action. Use a booking CTA only once a working calendar is supplied.
- **Privacy and consent.** Explain how submitted details will be used to respond and link to the matching privacy page. Keep any optional newsletter or promotional opt-in separate and unchecked. Configure optional tracking according to the site's approved consent settings. Draft privacy copy around the vendors and data flows actually in use. Obtain the owner’s privacy contact and review the copy before release.
- **Sales handoff.** Agree with the contractor on what qualifies, who owns each inquiry, the response window and who records outcomes. A qualified inquiry has a real commercial need in an agreed service line and territory, with enough detail for sales to act. Deduplicate repeated calls and forms for the same opportunity. Record reasons such as outside area, residential, unsuitable scope or duplicate. Report unanswered calls so the client can recover missed opportunities.
- **Client reporting.** Track unique inquiries → sales-accepted opportunities → walkthroughs where relevant → quotes → won/lost/pending. Track setup, agency fees and media spend separately. Define media cost per qualified opportunity as attributable media spend divided by unique accepted opportunities for the same campaign and reporting basis. For a zero denominator, show the count and no ratio. Where client records support it, report quoted pipeline value and confirmed contract value separately. Record the reporting date and allow for a longer buying cycle.
- **High Intent’s own analytics.** Distinguish consultation-button click, consultation start, successful submission and accepted agency opportunity. Phone/email clicks indicate contact intent. Keep names, phone numbers, email addresses and free-text form responses out of analytics and URLs.

## 9. Search, accessibility and release criteria

**Editorial standard · Google E-E-A-T**

Start with the decision the reader came to make. Where first-hand experience helps, use work the publisher can document and share. Identify who produced or reviewed technical guidance where readers would expect it, and explain the method when it affects interpretation. Support consequential claims with the most relevant original source. Claim outside recognition or credentials only when readers can verify them.

For a HighDusting.ca pilot, publish a measured result only after documenting the service area, reporting period, definition of a qualified walkthrough, source records and permission to attribute the result. Describe High Intent’s campaign work separately from the contractor’s field experience. Keep sample sales records and illustrative walkthrough photos labelled in English and Québec French.

At content review, trace a material claim on a representative page back to its source. Correct, qualify or omit an unsupported claim, including in translated copy and structured data where present. [Google Search Central](https://developers.google.com/search/docs/fundamentals/creating-helpful-content) · [Universal master prompt](https://github.com/GrafovGroup/MasterPrompt/blob/main/MASTER_PROMPT.md).

Generate unique English and French titles, descriptions and social previews. Use one clear H1 per page, descriptive internal links, self-referencing production canonicals, reciprocal en-CA/fr-CA hreflang links and an x-default route consistent with the selected default. Build the sitemap and robots file from real published routes. Include factual Organization, Service and Breadcrumb structured data where appropriate. Give preview deployments a noindex setting and check the production setting separately. Keep location claims, reviews and schema aligned with visible evidence.

Serve responsive, compressed images with explicit dimensions. Prioritize the hero, lazy-load secondary imagery, respect reduced-motion preferences, and keep the mobile menu, forms and language switch keyboard-operable. Give the bubble-only home link an accessible name. Build narrow layouts for longer French labels. The language switch must open the corresponding page at any depth.

**Definition of done for the site build**

- The documented command produces a static output directory. A direct visit or refresh on an English or French nested page works on the target host. Missing pages return a useful 404.
- Both languages include the homepage, services, five commercial service sectors, approach, contact, coverage, about and privacy content. Each published route opens its corresponding translation. Every sector page makes clear that High Intent provides marketing for companies in that trade. Case-study routes only go live with approved evidence.
- On a small phone, the logo, CTA, French menu and language switch are legible. At desktop width, content has a generous measure and the imagery supports the copy. Confirm focus order, form labels, text contrast and reduced-motion behaviour.
- A valid request produces either verified delivery to the intended recipient in the configured environment or an explicit owner action in the handoff with contact fallback in place. Check invalid input, provider errors, repeat taps and successful confirmation. Report which path was actually exercised.
- Published claims have a source or owner approval. No invented client logos, rankings, guarantees, employee counts, addresses, reviews, certifications, screenshots of results or revenue claims appear in pages or metadata.
- Deliver the source files, reusable brand assets, locale and route configuration, sample environment variable names without secrets, build/deploy instructions and a short owner handoff. List what was implemented, what was verified, where the editable content lives, and what still needs a real account, destination or decision.
- For an authorized launch, confirm HTTPS, apex/www routing, canonical host, form receipt and production indexing settings on the real domain. Submit the sitemap to Google Search Console and Bing Webmaster Tools when the owner has provided access. Report submissions separately from observed indexing.

## 10. Owner handoff

Close with a short decision table for the owner covering the final palette, optional slogan, artwork approval, destination repository/host, live contact routing, provider configuration and verified proof of work. Distinguish preview-ready work from items connected and checked on the public domain.

**Suggested first pilot:** use HighDusting.ca for one commercial high-dusting service in one metro the operator can cover. Agree on a qualifying walkthrough request, record a baseline and record calls, unique requests, sales acceptance, visits, quotes and wins. Only publish verified results with the operator’s approval. The pilot is a proposal, not a case study or an assertion of existing campaign performance.
