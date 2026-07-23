# Topical Authority — floral.id

## Role and boundary

`floral.id` is an Indonesian flower-commerce and floral-craft property. Repository evidence shows a product catalog, nationwide ordering proposition, event-florist service, and local-florist partner model. Its editorial role is to help buyers identify flowers, choose an appropriate arrangement, judge quality, brief an order, receive it safely, and care for it; it can also teach bounded floral craft where the instructions are safe and testable.

The site is not a general gardening, landscape, medicinal-plant, or academic-botany encyclopedia. Botanical identity is covered only as far as it improves naming, substitution, safety, sourcing, design, handling, or care. Product availability, delivery coverage, lead times, prices, partner counts, certifications, and case results must come from current operational evidence, never from an editorial assumption or a location-name swap.

Commercial routes such as `/shop`, `/produk/*`, `/produk-kategori/*`, `/handbouquet`, `/bunga-meja`, `/standing-flower`, `/bunga-papan`, `/salib`, `/paper-flower`, `/mobil-pengantin`, `/perangkai`, and `/partnership` own transactions and service claims. Planned articles educate and link to those routes only when the reader's decision makes the link useful.

## Evidence audited

- Canonical local repository: `C:\tmp\portfolio-authority\floral.id`; remote `cfpages-imeldadewitiya3/Floral.id`; branch `main`; audited at commit `ec839746`.
- Ownership and scope: `floral.id` is marked owned in `PROJECTS_CATEGORIES.md` and eligible in `PORTFOLIO_AUTHORITY_ROLLOUT.md`. `florist.co.id` is a separate owned domain and may independently cover overlapping queries.
- Technology/content shape: static WordPress export with 2,620 tracked files, including 2,077 HTML files, 14 XML files, and copied WordPress assets. No repository-local `AGENTS.md` was present.
- Sitemap index: 11 children (`post-sitemap1.xml` through `post-sitemap10.xml` plus `page-sitemap.xml`). Child files contain 1,957 post locators and 17 page locators. `sitemap-complete.xml` contains 2,077 distinct locators.
- Dominant editorial footprint: 1,952 geographic commercial posts—488 each for `handbouquet-*`, `standing-flower-*`, `bunga-papan-*`, and `bunga-salib-*`.
- Other complete-sitemap coverage: 36 product URLs, 15 product-category URLs, 20 category/archive URLs, 17 author archive/pagination URLs, 17 news archive/pagination URLs, and 20 homepage/static/service entries.
- Commercial evidence: the homepage and About page describe online ordering, local/imported flowers, several major-city representatives, product sales, delivery, and custom arrangements. `/partnership` recruits florist partners; `/perangkai` sells event arrangement/decorating.
- Quality risks observed: the homepage says the business is centered in Jakarta while `/tentang` says Surabaya; `/layanan` is an unrelated accounting/tax lorem-ipsum template; several strong customer, partner, speed, freshness, and nationwide-delivery claims are present without supporting records in the repository.
- Existing sitemap/routes were normalized and compared with all proposed slugs. No proposed article slug exactly collides with an existing sitemap path.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/` | Main store proposition, product cards, broad service claims; Jakarta/Surabaya inconsistency across pages | expand | Homepage remains brand and transaction gateway | Confirm legal business identity, actual base, fulfillment model, current service area, and every numeric/superlative claim |
| `/produk/*` | 36 SKU-like product pages with snapshot prices and images | keep | Each product page owns exact offer, composition, price, and availability | Current inventory, image rights, stem/material specification, substitution policy, and price freshness |
| `/produk-kategori/*` | 15 transactional collection pages | keep | Category routes own shopping intent | Remove empty/thin collections; verify taxonomy and canonical behavior |
| `/handbouquet`, `/bunga-meja`, `/standing-flower`, `/bunga-papan`, `/salib`, `/paper-flower`, `/mobil-pengantin` | Core commercial format/service landing pages | expand | These routes own quote/order intent for their named formats | Current capability, original photography, dimensions, materials, delivery constraints, and route-specific FAQs |
| `/perangkai` | Event-florist/decorator service | expand | Service route owns consultation and booking | Team competence, portfolio rights, service boundary, installation process, and real project evidence |
| `/partnership` | Florist-partner recruitment and network proposition | expand | Partner route owns applications and commercial terms | Current partner count, selection criteria, payment terms, geographic coverage, and governance |
| `/faq` | Ordering, routing to partners, delivery, placement, damage, and documentation claims | expand | FAQ owns concise current policies; long educational questions link to catalog articles | Operations sign-off, exceptions, escalation path, timestamp, and policy consistency |
| `/layanan` | Unrelated accounting/tax placeholder and lorem ipsum | remove | Navigation should point to verified flower services or `/perangkai` | Confirm it has no traffic/backlinks or contractual need before removal/redirect |
| `/berita`, `/berita/page/*` | Archive containing geographic sales posts rather than a useful editorial hub | manual review | A future knowledge index should own article discovery | GSC traffic/backlinks, archive templates, pagination canonical/noindex behavior |
| `/author/syamsul-alam/page/*` | Author pagination, largely duplicating archive discovery | noindex | Verified author profile may remain indexable; pagination is discovery-only | Author bio accuracy, canonical/noindex implementation, GSC value |
| `/category/*` and pagination | Four product-stem archives repeated across pagination | manual review | Commercial categories or a curated knowledge taxonomy | Indexation, uniqueness, internal links, and whether archives serve users |
| `/{handbouquet,standing-flower,bunga-papan,bunga-salib}-<place>` | 1,952 location-swapped commercial pages; no evidence audit found unique local stock, partner, climate, service, or case content | manual review | Consolidate only after page-level evidence; core format pages own generic intent | GSC clicks/backlinks, real partner/service coverage, unique NAP/process/case evidence, local availability, and redirect mapping |
| `/bunga-papan.html`, `/bunga-salib.html`, `/standing-flower.html`, `/handbouquet.html` | Post-form variants competing with clean commercial routes | canonicalize | Clean routes without `.html` own format-level commercial intent | Response status, canonical tags, internal links, backlinks, and redirect feasibility |
| Homepage/About/footer company statements | Conflicting base city and unsupported “thousands”, “100+”, nationwide, 24-hour, speed, and quality claims | manual review | Verified About, FAQ, and partnership routes | Documentary evidence and named operations owner approval |

No new city-, province-, or region-swapped briefs belong in the catalog. Existing geographic pages require evidence-led consolidation, not automatic deletion or blind redirection.

## Coverage matrix

| Completeness lens | Topic owners | Coverage decision |
|---|---|---|
| Definition, vocabulary, taxonomy, anatomy, materials | FLR-01, FLR-04, FLR-08, FLR-09, FLR-10, FLR-14 | Cover commercial/common versus accepted botanical names, floral roles, arrangement parts, and mechanics; exclude cultivation encyclopedias |
| Mechanisms and science | FLR-05, FLR-07, FLR-13 | Explain water uptake, senescence, ethylene, hygiene, pollen/contact exposure, and toxicity only from expert sources |
| History and evolution | FLR-03, FLR-10 | Include the context of floral messages and Indonesian formats where sources exist; never invent a universal meaning or origin story |
| Measurement and terminology | FLR-04, FLR-06, FLR-08, FLR-09, FLR-10, FLR-11 | Dimensions, scale, stem count, opening stage, viewing distance, sightlines, mechanics, and order specifications |
| Need recognition and occasion | FLR-03, FLR-08, FLR-09, FLR-10, FLR-11, FLR-16 | Give readers a path from recipient/occasion/venue to a suitable format |
| Survey, brief, requirements, and design | FLR-04, FLR-11, FLR-16 | Translate recipient, message, venue, climate, handling, deadline, and budget constraints into a brief |
| Comparison and selection | FLR-01, FLR-03, FLR-06, FLR-08, FLR-09, FLR-10 | Compare real alternatives by function, quality, care burden, symbolism, scale, and logistics |
| Budget and procurement | FLR-02, FLR-06, FLR-16 | Explain cost components and quote comparison without publishing fabricated prices or availability |
| Preparation, assembly, installation | FLR-05, FLR-11, FLR-14 | Safe conditioning, mechanics, venue setup, transport, and stop conditions |
| Handover, use, maintenance, troubleshooting, end of life | FLR-07, FLR-12, FLR-16 | Receiving checklist, care, symptom diagnosis, reuse/compost/waste separation, complaint evidence |
| Stakeholders | FLR-06, FLR-11, FLR-13, FLR-16 | Buyer, recipient, florist, partner florist, venue, event planner, photographer, pet owner, allergy-sensitive household |
| Site, climate, and scale | FLR-02, FLR-07, FLR-09, FLR-11 | Indonesia's heat/humidity, indoor/outdoor venue conditions, arrangement size, transport duration; no city swaps |
| New installation versus occupied venue | FLR-11, FLR-13, FLR-14 | Event setup around guests, food, pets, children, and venue rules; generic construction framing is N/A |
| DIY versus professional | FLR-05, FLR-08, FLR-09, FLR-10, FLR-11, FLR-14 | Safe home techniques plus stop conditions for unstable structures, ladders, vehicles, chemicals, and large installations |
| Quality levels and failure modes | FLR-05, FLR-06, FLR-07, FLR-14, FLR-16 | Quality markers, dehydration, microbial blockage, bruising, substitution mismatch, transport damage, service recovery |
| Safety, health, standards, and regulation | FLR-02, FLR-12, FLR-13, FLR-14 | Veterinary/toxicology review, allergy/occupational sources, chemical labels, CITES/current import rules, certification verification |
| Environmental impact | FLR-02, FLR-12 | Origin, transport, farm practices, foam/plastic, reuse, compostability, contamination, and evidence-based claims |
| Evidence quality, myths, unsafe advice | All topics; strongest in FLR-05, FLR-07, FLR-12, FLR-13 | Name source type and review owner; reject folk vase recipes, universal meanings, “hypoallergenic” absolutes, and unsupported sustainability claims |
| Search formats | All topics | Fundamentals, comparisons, decision tables, checklists, diagrams, original photos, troubleshooting, calculators/worksheets, and verified case studies |
| News/trends | FLR-02, FLR-12 only when maintainable | Use dated BPS/Ministry production data or standards changes; no trend filler |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| FLR-01 | Flower identity and commercial vocabulary | Identify commonly sold flowers and communicate substitutions accurately | Common versus botanical names; accepted names/synonyms; cut flower versus foliage/filler/potted plant; focal/form/line/mass/filler roles; rose, chrysanthemum, orchid, lily and tropical stems; look-alikes; cultivar/color limits | Kew POWO references, Ministry catalogs, labeled original macro photos, comparison tables | Identification for buying/design only; cultivation belongs to a gardening property, toxicity to FLR-13, availability to current product routes | 6 |
| FLR-02 | Seasonality, origin, and supply | Set realistic sourcing expectations without assuming year-round stock | Indonesian production context; local versus imported; harvest/opening stage; natural season versus controlled production; substitution planning; farm/wholesaler/partner traceability; cold-chain questions | Current BPS/Ministry data, supplier records, harvest-stage diagrams, provenance checklist | Does not promise stock, city coverage, delivery time, or price; current offers stay on `/produk/*` and quote routes | 6 |
| FLR-03 | Meanings, occasions, and etiquette | Choose a respectful flower, palette, message, and format for the recipient | Meanings as culture-dependent conventions; romance; congratulations/openings; sympathy/condolence; weddings/anniversaries; gratitude/recovery; faith/cultural sensitivity; message-card etiquette | Sourced cultural explanation, recipient/occasion decision table, expert sensitivity review | No universal symbolism claims or religious rulings; format construction is FLR-08–FLR-11 and exact wording is confirmed by recipient context | 6 |
| FLR-04 | Color and floral-design principles | Turn a mood and venue into a coherent visual brief | Hue/value/saturation; monochrome/analogous/complementary palettes; balance; proportion/scale; dominance/focal point; rhythm/movement; texture/form/negative space; lighting/background effects | Color diagrams, annotated original arrangements, design critique rubric | Principles rather than product sale; format mechanics belong to FLR-08–FLR-11 and photography color accuracy to FLR-15 | 6 |
| FLR-05 | Conditioning and postharvest handling | Condition stems safely and diagnose early quality loss | Clean tools/containers; recutting and leaf removal; hydration; species/opening stage; temperature/humidity; ethylene sensitivity; preservative roles; transport; microbial blockage; bent neck and bruising | UC Davis/extension research, process diagrams, controlled comparison, florist expert review | Professional handling, not pesticide recipes or unsupported chemistry; household display care is FLR-07 and workplace hazards FLR-13 | 6 |
| FLR-06 | Buying, quality, and substitutions | Compare offers and accept or reject a delivered arrangement using observable criteria | Freshness markers; stem/flower opening; dimensions/stem counts; grade versus aesthetics; seasonal substitution; reference-photo limits; quote components; receiving inspection; seller/partner evidence | Original inspection photos, acceptance checklist, quote matrix, measurement sheet | No universal price table, fabricated grade, or guaranteed inventory; exact offers and claims belong to commercial routes | 6 |
| FLR-07 | Home care and vase life | Maintain an arrangement and respond to common deterioration safely | Clean vase; water/preservative; recut; placement in tropical interiors; species differences; cloudy water/odor; drooping/bent stems; pet/child placement; disposal timing | Extension guidance, species matrix, symptom decision tree, time-stamped care test | No guaranteed number of days; conditioning before assembly is FLR-05, toxicology/emergency advice FLR-13 | 6 |
| FLR-08 | Hand bouquets and bloom boxes | Select, brief, carry, present, and care for personal arrangements | Bouquet silhouettes; hand size/weight; focal/filler/foliage; wrapping; card/presentation; bridal versus gift bouquet; bloom-box water/mechanics; transport and handoff | Shape diagrams, scale photos, brief template, carrying checklist | `/handbouquet` and product routes own sales; general design theory is FLR-04, stem conditioning FLR-05 | 6 |
| FLR-09 | Table and standing arrangements | Match arrangement scale and mechanics to room, table, viewing angle, and occasion | Dining sightlines; vase/container; one-sided versus all-around; entry/lobby scale; standing frame stability; congratulations versus condolence; indoor/outdoor exposure; care/handoff | Dimension diagrams, venue checklist, original 360° photos, stability review | `/bunga-meja` and `/standing-flower` own transactions; boards/crosses are FLR-10 and large event installations FLR-11 | 6 |
| FLR-10 | Flower boards, paper boards, and condolence crosses | Specify a readable, respectful, structurally appropriate ceremonial display | Bunga papan anatomy; paper-flower board; fresh versus artificial components; message hierarchy/spelling; dimensions/viewing distance; congratulatory versus condolence use; flower cross etiquette; placement and retrieval | Annotated photos, message-proof checklist, dimension/readability test, cultural review | `/bunga-papan`, `/paper-flower`, and `/salib` own orders; no denomination-wide claims, city pages, or invented local customs | 6 |
| FLR-11 | Weddings, events, and vehicle florals | Build a floral brief and installation plan that survives the venue and schedule | Ceremony/reception zones; bridal personal flowers; table plan; backdrop/aisle; vehicle attachment; venue rules; weather/heat; install/strike schedule; rentals; sample/mock-up; contingency | Brief worksheet, venue survey, install timeline, risk checklist, verified case study only | `/perangkai` and `/mobil-pengantin` own bookings; no fabricated case studies, venue permissions, or load/attachment assurances | 6 |
| FLR-12 | Sustainable sourcing and floral waste | Ask better sourcing questions and reduce avoidable material waste | Local/import trade-offs; farm practices; water/energy/pesticides; labor/traceability; certification verification; floral foam and plastics; packaging; reuse/donation; compostability/contamination; waste audit | GLOBALG.A.P./Fairtrade criteria, supplier documents, material flow diagram, waste audit | No blanket “local is greener”, “biodegradable”, or certification claim; protected-species/import compliance requires current expert verification under FLR-02 | 6 |
| FLR-13 | Allergies, pets, toxicity, and safe handling | Recognize exposure risks, choose lower-risk options, and know when to seek expert help | Pollen versus fragrance; contact dermatitis; occupational asthma; thorns/sap/tools; children/food/healthcare settings; lilies and cats; other pet-toxic plants; common-name confusion; emergency escalation; chemical residues/PPE | FDA/ASPCA/CDC/AAAAI and veterinary review, botanical-name table, hazard checklist | Not diagnosis, treatment, or a guarantee of “pet-safe/hypoallergenic”; individual emergencies go to a veterinarian/clinician, not the article | 6 |
| FLR-14 | Floral craft, tools, and mechanics | Choose a safe construction method and understand when a professional is needed | Tool selection/care; spiral hand-tied technique; grids/frogs/wire/tape/foam; stem reinforcement; container balance; mechanics concealment; repair; reusable mechanics; large-structure stop conditions | Step diagrams, original process photos, tool safety checklist, load/stability expert review | Small craft only; elevated, vehicle-mounted, public, electrical, or heavy installations belong to FLR-11/professional service | 6 |
| FLR-15 | Floral photography and presentation | Produce honest, useful images that preserve color, scale, detail, and delivery evidence | Natural/artificial light; white balance/color reference; background; composition; scale; front/side/detail set; phone workflow; product consistency; proof-of-delivery privacy; alt text/file handling | Shot list, lighting diagrams, color-card workflow, consent/privacy checklist | Does not replace the physical QC in FLR-06 or fabricate portfolio/case evidence; commercial images require rights and current-product accuracy | 6 |
| FLR-16 | Ordering, delivery, and florist-partner operations | Place and fulfill a well-specified order with clear approvals, evidence, and recovery paths | Occasion/recipient brief; deadline/venue access; card proofing; substitution approval; remote order verification; partner selection; work order; QC photos; packaging/handoff; delivery exception; complaint evidence; service recovery | Order worksheet, partner scorecard, RACI/process map, QC checklist, policy review | `/shop`, `/faq`, `/kontak-kami`, `/partnership`, and service routes own terms, price, payment, coverage, and conversion | 6 |

## Related-domain opportunities

`florist.co.id` is an independent editorial and commercial property. It may cover the same flower, arrangement, care, or buying queries without creating cannibalization on `floral.id`. If the businesses later share verified data, each site may present it from its own role—for example, `floral.id` as a buyer-facing marketplace/order network and `florist.co.id` as a florist craft or provider-facing property. Cross-domain links should exist only when they help users, not to manufacture ownership signals.

`taman.co.id` may independently cover living garden plants and landscape cultivation. `weddingevent.co.id` may independently cover whole-event planning. On `floral.id`, cultivation remains out of scope and weddings stay focused on floral choices, logistics, and installation.

## Consolidation plan

1. Preserve commercial URLs with real inventory, demand, links, or transactions; update their evidence before changing slugs.
2. Remove `/layanan` only after analytics/backlink review, then redirect it to the closest verified flower-service route if a clear replacement exists.
3. Reconcile `/bunga-papan.html`, `/bunga-salib.html`, `/standing-flower.html`, and `/handbouquet.html` with the corresponding clean commercial routes. Canonicals, internal links, sitemap entries, and redirects must agree.
4. Export GSC and analytics for all 1,952 geographic pages. Classify each as: proven local service page with unique operational evidence; useful page to rebuild; duplicate to consolidate; or unresolved. Do not preserve or remove pages merely because a place name exists.
5. Stop generating new place-name permutations. A local page is eligible only with verifiable local stock/partner/service details, substantive local constraints, and accountable maintenance.
6. Replace broad author/news/category pagination indexation with curated discovery. Keep a verified author entity; noindex thin pagination when implementation and GSC evidence support it.
7. Correct the Jakarta/Surabaya contradiction and audit every numeric, speed, “best”, nationwide, partner, quality, and customer claim before it remains live.
8. Build the first knowledge hub at a route selected by the implementation owner, then add catalog articles in bounded waves. Proposed slugs are path segments, not permission to deploy at the root without a routing decision.

## Internal-link architecture

- A central flower-selection hub links to FLR-01, FLR-02, FLR-03, FLR-04, FLR-06, and the format hubs FLR-08–FLR-11.
- Identity pages link to safety when a common-name confusion changes toxicity, and to handling/care when a species has materially different postharvest behavior.
- Occasion pages link to the relevant format guide first, then to commercial routes only when a reader is ready to order.
- Quality pages link forward to receiving care and backward to sourcing/conditioning; diagnostic care pages link to prevention and safe disposal.
- Format hubs link to their six children and laterally to design, quality, care, sustainability, safety, and ordering pages based on the specific decision.
- Event pages form a lifecycle: brief → venue survey → mechanics/installation → climate contingency → handoff/strike → verified case-study method.
- Sustainability pages link to sourcing, reusable mechanics, care/longevity, and waste sorting. They do not inject generic green claims into every commercial page.
- Ordering pages link to current FAQ/policy and partner routes; policy routes link back only to educational pages that reduce ordering error.
- Every article links upward to its topic hub; each topic hub links to all children. Related IDs in `ARTICLE_CATALOG.md` define the initial lateral graph.

## Evidence and editorial standards

- Botanical identity: use accepted names and synonyms from [Kew Plants of the World Online](https://powo.science.kew.org/about), Indonesian Ministry catalogs, or another maintained taxonomic authority. Label cultivar-level uncertainty.
- Indonesia supply context: use dated [BPS floriculture tables](https://www.bps.go.id/id/statistics-table/2/NjQjMg%3D%3D/produksi-tanaman-florikultura-hias-html) and [Directorate General of Horticulture](https://hortikultura.pertanian.go.id/ajang-pemasyarakatan-produk-florikultura-florikultura-indonesia-dan-tomohon-international-flower-festival/) sources. Statistics describe a dated market, not current Floral.id inventory.
- Handling and care: ground claims in crop-specific research or sources such as the [UC Davis/UC ANR cut-flower handling bulletin](https://ucanr.edu/sites/Postharvest_Technology_Center_/files/231308.pdf). Test household instructions and avoid universal vase-life promises.
- Pet toxicity: veterinary review is mandatory. The [FDA lily guidance](https://www.fda.gov/animal-veterinary/animal-health-literacy/lovely-lilies-and-curious-cats-dangerous-combination) and [ASPCA plant database](https://www.aspca.org/pet-care/aspca-poison-control/toxic-and-non-toxic-plants) are starting references; common names alone are insufficient.
- Allergy and worker health: use expert sources such as [AAAAI outdoor-allergen guidance](https://www.aaaai.org/tools-for-the-public/conditions-library/allergies/outdoor-allergens-ttr) and [CDC/NIOSH occupational evidence](https://stacks.cdc.gov/view/cdc/189146). Avoid diagnosis and “allergy-free” promises.
- Responsible sourcing: distinguish farm assurance, social criteria, and environmental metrics. Verify any claimed certificate in its registry; useful frameworks include [GLOBALG.A.P. Flowers and Ornamentals](https://globalgap.org/what-we-offer/solutions/ifa-flowers-and-ornamentals/) and the [Fairtrade Flowers and Plants Standard](https://www.fairtrade.net/content/dam/fairtrade/fairtrade-international/standards/flowers-and-plants-/Flowers-and-Plants-Standard_EN.pdf).
- Protected species and cross-border sourcing: verify current Indonesian rules and CITES status before naming a compliance path. Never imply that all orchids or all artificial propagation share one rule.
- Meanings and etiquette: state whose convention is being described, where, and when. Treat recipient preference and faith/community practice as more authoritative than generic “flower language”.
- Photography and cases: use owned/licensed images, disclose styled examples, preserve color honestly, secure consent, remove personal delivery data, and never invent a customer, test, result, or project.
- Commercial facts: price, stock, delivery time, city coverage, partner counts, service levels, substitutions, refunds, and payment terms require a named operations owner and “last verified” date.
- Medical/veterinary red flags and chemical handling receive expert review and visible stop/escalation language before publication.

## First bounded publication cluster

The first wave is 12 connected assets:

1. `FLR-01-01` — commercial versus botanical flower names.
2. `FLR-02-01` — Indonesian flower supply/season planning.
3. `FLR-03-01` — meaning and etiquette without universal claims.
4. `FLR-04-01` — palette-building fundamentals.
5. `FLR-05-01` — receiving and conditioning stems.
6. `FLR-06-01` — cut-flower freshness inspection.
7. `FLR-06-04` — substitution approval.
8. `FLR-07-01` — first-hour vase setup.
9. `FLR-07-04` — drooping-flower diagnosis.
10. `FLR-13-03` — lilies and cats.
11. `FLR-15-03` — honest scale/detail photography.
12. `FLR-16-01` — complete order brief.

This cluster connects identity, sourcing, meaning, design, quality, care, safety, honest presentation, and ordering—the full buyer journey without requiring fabricated inventory or case studies. The central selection hub links to all 12; quality and order pages provide contextual links to verified commercial routes.

Measure indexation; impressions and clicks by distinct intent; scroll/checklist completion; use of order-brief or care assets; qualified inquiries that include usable specifications; order correction/substitution rate where operations can measure it; and same-domain query overlap. Do not scale the next wave until content is reviewed, indexed, differentiated, and operationally useful.

## Definition of done

- All 16 parent topics have six distinct briefs and exact matching counts in `ARTICLE_CATALOG.md`.
- Every brief has a unique ID, title, slug, primary intent, coverage promise, explicit owner boundary, evidence format, related links, priority, and bounded wave.
- No proposed slug collides exactly with the 2,077 audited sitemap locators.
- Same-domain overlap groups have one named intent owner; `florist.co.id` overlap is not treated as cannibalization.
- High-risk toxicity, allergy, handling, sustainability, protected-species, and commercial claims pass their stated expert or operational review.
- No city-swap article, invented availability/price/service area, fabricated case, universal flower meaning, or unsupported safety claim is published.
- First-wave assets receive editorial, legal/claims, image-rights, and operations review; hubs and children link bidirectionally; no article is orphaned.
- GSC/analytics baselines and geographic-page decisions are recorded before consolidation or further scaled publishing.
