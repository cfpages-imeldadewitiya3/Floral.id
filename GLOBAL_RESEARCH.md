# Global Research — floral.id

Status: **project-wide evidence foundation complete; article-level gates remain explicit**

Last verified: **2026-07-25 (Asia/Jakarta)**

Research family: **F13 Flowers, floristry, arrangements, and delivery**

Catalog covered: **16 topic families / 96 planned articles** in [`ARTICLE_CATALOG.md`](ARTICLE_CATALOG.md)

Authority boundary: [`TOPICAL_AUTHORITY.md`](TOPICAL_AUTHORITY.md)

## Purpose

This file is the reusable ground-truth layer for the whole `floral.id` article catalog. It consolidates source discovery once, maps it to every parent topic, and states where a fresh supplier record, expert review, legal check, or project-specific fact is still required.

It is not an article, a stock feed, a medical or veterinary service, a religious ruling, a venue approval, or proof that a product, florist partner, certification, delivery area, price, or sustainability claim is currently available. Writers must open and cite the original source.

## How writers must use this file

1. Start with the relevant row in the coverage matrix.
2. Reopen every source before using a technical, legal, health, safety, availability, or performance claim.
3. Keep common names separate from accepted botanical names and cultivar or trade names.
4. Keep general postharvest principles separate from species-, cultivar-, temperature-, and treatment-specific instructions.
5. Never turn cultural symbolism into a universal rule or a guarantee that a recipient will interpret a flower in one way.
6. Treat prices, stock, seasonality, delivery time, partner coverage, substitutions, and product photographs as volatile operational facts.
7. Preserve all jurisdiction, scope, and professional-review limits.
8. Recheck volatile sources during outlining or six months after the date above, whichever comes first.

## Evidence scale

| Grade | Meaning | Permitted use |
| --- | --- | --- |
| A | Current Indonesian law, official Indonesian statistics, or official primary record | Establish legal status, defined scope, and dated public facts |
| B | Government, university, botanical institution, or standards/certification owner guidance | Explain evidence-backed concepts with attribution and scope limits |
| C | Foreign regulator or professional guidance relevant by analogy | Explain risk or practice; never present as Indonesian law |
| Gate | Supplier-, product-, venue-, person-, case-, or professional-specific evidence is unresolved | Do not publish the definitive claim until resolved |

## Research register

### KR-01 — Project corpus and editorial boundary

- **Sources:** [`TOPICAL_AUTHORITY.md`](TOPICAL_AUTHORITY.md), [`ARTICLE_CATALOG.md`](ARTICLE_CATALOG.md), and [`README.md`](README.md).
- **Grade:** A for project scope; not independent real-world evidence.
- **Purpose:** Freeze the verified local topic map so shared family research cannot overwrite the actual `floral.id` boundary.
- **Summary:** The repository defines a buyer-facing flower and florist knowledge system spanning identification, sourcing, care, formats, safety, craft, photography, and order operations.
- **Grounded facts:** The catalog has 16 parent topics and 96 distinct briefs. Geographic doorway pages, unsupported company claims, prices, current stock, and service coverage remain outside the evidence provided by the catalog.
- **Incorporation:** Use as the scope check for all topics. Every outline must remain inside its parent topic's boundary and keep transactional claims on verified commercial routes.
- **Limits/recheck:** Repository planning documents establish editorial intent, not product availability, competence, performance, or legal compliance.

### KR-02 — Accepted botanical names and synonym control

- **Sources:** [Kew Plants of the World Online](https://powo.science.kew.org/), [Kew explanation of the WCVP names backbone](https://powo.science.kew.org/about-wcvp).
- **Grade:** B.
- **Purpose:** Prevent common-name ambiguity from becoming unsafe buying, substitution, allergy, toxicity, or protected-species advice.
- **Summary:** POWO uses the expert-reviewed World Checklist of Vascular Plants as its names backbone and exposes accepted names, synonyms, distribution, and supporting references.
- **Grounded facts:** A common flower name can refer to more than one taxon, while an accepted botanical name can have older or trade synonyms. Identification should therefore record botanical name, common/trade name, cultivar when known, and the date checked.
- **Incorporation:** Use in `FLR-01`, `FLR-02`, `FLR-06`, `FLR-12`, `FLR-13`. Add a botanical-name field to comparison, substitution, toxicity, and sourcing checklists.
- **Limits/recheck:** POWO is a taxonomy source, not proof of a delivered stem's identity, safety, cultivation method, certification, legal trade status, or current availability.

### KR-03 — Indonesian floriculture production context

- **Sources:** [BPS floriculture production table](https://www.bps.go.id/id/statistics-table/2/NjQjMg%3D%3D/produksi-tanaman-florikultura-hias-html), [Ministry of Agriculture 2024 horticulture final figures](https://repository.pertanian.go.id/items/03825fa9-5541-4b80-8c67-95e2d8588aa9), [Ministry horticulture data portal](https://data.hortikultura.pertanian.go.id/horti/).
- **Grade:** A.
- **Purpose:** Ground supply and seasonality articles in dated Indonesian production evidence instead of assumed nationwide stock.
- **Summary:** BPS and the Ministry publish official statistics for defined ornamental-plant commodities using national collection systems and dated reporting periods.
- **Grounded facts:** Production statistics describe recorded output by commodity, unit, geography, and period; they do not prove that one florist has stock or that a particular cultivar is available for a deadline.
- **Incorporation:** Use in `FLR-01`, `FLR-02`, `FLR-06`, `FLR-16`. State the dataset year, commodity definition, unit, and geography; pair any ordering conclusion with a current supplier check and substitution plan.
- **Limits/recheck:** Do not infer retail price, quality, delivery coverage, farm practice, cold-chain condition, or day-specific inventory from aggregate production data.

### KR-04 — Cut-flower postharvest control system

- **Sources:** [UC Davis cut-flower research collection](https://postharvest.ucdavis.edu/publication-category/cut-flowers), [UC Davis Three C's checklist record](https://postharvest.ucdavis.edu/fr/node/5477).
- **Grade:** B.
- **Purpose:** Provide a defensible foundation for conditioning, sanitation, temperature, handling, and transport explanations.
- **Summary:** UC Davis organizes cut-flower guidance around cooling, cleanliness, and careful handling, with species-specific publications for temperature, hydration, ethylene, sanitation, and storage.
- **Grounded facts:** Temperature management, clean water and containers, prompt hydration, damage prevention, and species-specific sensitivity are separate control points. One generic vase-life promise is not supported.
- **Incorporation:** Use in `FLR-05`, `FLR-06`, `FLR-07`, `FLR-08`, `FLR-09`, `FLR-10`, `FLR-11`, `FLR-16`. Build process/checklist articles around control points, records, symptoms, and escalation rather than miracle recipes.
- **Limits/recheck:** Some collection documents are older and may mention treatments unsuitable for household use or local regulation. Recheck the species, current label, worker safety, and Indonesian context before giving a procedure.

### KR-05 — Species and cultivar differences in storage and care

- **Sources:** [UC Davis anthurium fact sheet](https://postharvest.ucdavis.edu/produce-facts-sheets/anthurium), [UC Davis chrysanthemum fact sheet](https://postharvest.ucdavis.edu/produce-facts-sheets/chrysanthemum).
- **Grade:** B.
- **Purpose:** Stop writers from applying one temperature, ethylene, harvest-stage, or vase-life rule to all flowers.
- **Summary:** UC Davis fact sheets show materially different handling profiles: tropical anthuriums have chilling considerations and limited ethylene response, while chrysanthemums have their own maturity and storage behavior.
- **Grounded facts:** Botanical identity, cultivar, opening stage, prior storage, temperature, water quality, treatment, and damage history can change the result. Visual freshness alone cannot reconstruct the full cold chain.
- **Incorporation:** Use in `FLR-02`, `FLR-05`, `FLR-06`, `FLR-07`. Use species tables only when each row has a direct species source and state observable stop conditions.
- **Limits/recheck:** Do not generalize the numeric storage conditions or chemical treatments from these examples to other taxa, household care, or an undocumented product.

### KR-06 — Floral symbolism is contextual, not universal

- **Sources:** [Smithsonian Gardens: Language of Flowers](https://gardens.si.edu/learn/blog/language-of-flowers/), [Smithsonian historical learning resource](https://www.si.edu/object/language-flowers%3ASCLDA_4757).
- **Grade:** B for historical context.
- **Purpose:** Ground etiquette and meaning articles while preventing invented universal symbolism or religious claims.
- **Summary:** Smithsonian records show that Victorian flower-language guides assigned meanings but often contradicted one another; flower symbolism also varies across culture, event, relationship, and personal history.
- **Grounded facts:** A meaning table is a historical or cultural convention, not a deterministic communication system. The sender's message, recipient context, language, faith, and local custom need confirmation.
- **Incorporation:** Use in `FLR-03`, `FLR-08`, `FLR-09`, `FLR-10`, `FLR-11`. Frame meanings as sourced examples and provide a recipient/message confirmation checklist.
- **Limits/recheck:** These sources document largely Western/Victorian examples and cannot establish Indonesian, regional, ethnic, or religious etiquette. Obtain a qualified local cultural or faith review before specific claims.

### KR-07 — Design principles and scale

- **Sources:** [Penn State Extension design principles](https://extension.psu.edu/principles-of-garden-design), [University of Missouri Extension design principles](https://extension.missouri.edu/publications/mg11).
- **Grade:** B; principles transfer by analogy, not as a florist credential.
- **Purpose:** Give color, balance, rhythm, unity, proportion, and scale articles a disciplined visual vocabulary.
- **Summary:** University extension guidance treats scale, balance, rhythm, unity, focal relationships, and context as interacting design principles rather than fixed formulas.
- **Grounded facts:** Visual weight can be balanced symmetrically or asymmetrically; scale is relative to the whole setting; repetition can create rhythm and unity. A successful design still depends on viewing angle, container, venue, lighting, material, and intended function.
- **Incorporation:** Use in `FLR-04`, `FLR-08`, `FLR-09`, `FLR-10`, `FLR-11`, `FLR-15`. Translate principles into annotated original examples and critique questions, not prescriptive taste rules.
- **Limits/recheck:** The sources concern garden/landscape composition. Floral-specific mechanics, cultural symbolism, stability, and venue safety need separate evidence and practitioner review.

### KR-08 — Indonesian consumer-information duties

- **Sources:** [UU No. 8 Tahun 1999 — BPK legal record](https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999), [official law PDF](https://peraturan.bpk.go.id/Home/Download/33784/UU%20Nomor%208%20Tahun%201999.pdf).
- **Grade:** A.
- **Purpose:** Ground quote comparison, substitutions, reference photos, complaints, and recovery content in Indonesian consumer-protection context.
- **Summary:** Indonesia's Consumer Protection Law establishes a national framework for consumer rights and business obligations, including truthful and clear information about goods or services.
- **Grounded facts:** An order workflow should make the offered item, price components, material substitutions, approvals, delivery terms, evidence, and complaint path understandable and retrievable.
- **Incorporation:** Use in `FLR-06`, `FLR-08`, `FLR-09`, `FLR-10`, `FLR-11`, `FLR-15`, `FLR-16`. Build quote, proofing, substitution-approval, receiving, and complaint checklists around documented facts.
- **Limits/recheck:** This file does not interpret liability, remedies, or contract validity for a specific transaction. Legal review is required before definitive legal advice or policy copy.

### KR-09 — Electronic ordering, confirmation, delivery, and disputes

- **Sources:** [PP No. 80 Tahun 2019 — official Kemendag PDF](https://jdih.kemendag.go.id/pdf/Regulasi/2019/PP%20Nomor%2080%20Tahun%202019.pdf), [Kemendag consumer/e-commerce coordination record](https://jdih.kemendag.go.id/nota/detail/203).
- **Grade:** A.
- **Purpose:** Ground remote-order and florist-partner workflows in the Indonesian electronic-commerce framework.
- **Summary:** PP 80/2019 addresses electronic offers, acceptance and confirmation, contracts, payments, delivery, cancellation/exchange, personal data, evidence, and dispute handling for electronic commerce.
- **Grounded facts:** A chat or online flower order can involve multiple evidence points: specification, card text, recipient/location data, substitution consent, payment, confirmation, dispatch, handoff, exception, and resolution.
- **Incorporation:** Use in `FLR-06`, `FLR-15`, `FLR-16`. Create a timestamped order record and distinguish requested, approved, produced, dispatched, delivered, refused, and resolved states.
- **Limits/recheck:** Open the current consolidated regulation and obtain legal review before describing mandatory wording, retention periods, refunds, jurisdiction, or a specific platform's compliance.

### KR-10 — Personal data and delivery-proof privacy

- **Sources:** [UU No. 27 Tahun 2022 — Komdigi JDIH](https://jdih.komdigi.go.id/produk_hukum/view/id/832/t/undangundang%2Bnomor%2B27%2Btahun%2B2022), [official law download](https://jdih.komdigi.go.id/produk_hukum/unduh/id/832/t/undangundang%2Bnomor%2B27%2Btahun%2B2022).
- **Grade:** A.
- **Purpose:** Prevent order, delivery, photography, and case-study articles from encouraging unnecessary disclosure of recipient data.
- **Summary:** Indonesia's Personal Data Protection Law governs processing of identifiable personal data and provides a general protection framework for electronic and non-electronic processing.
- **Grounded facts:** Recipient names, phone numbers, addresses, messages, faces, vehicle plates, workplace details, and geolocation can identify a person alone or in combination.
- **Incorporation:** Use in `FLR-11`, `FLR-15`, `FLR-16`. Minimize data in screenshots and delivery photos; separate operational proof from public portfolio use; obtain and record an appropriate lawful basis or consent review.
- **Limits/recheck:** This is not a lawful-basis determination, privacy notice, retention schedule, or incident-response plan. Obtain current Indonesian privacy/legal review for implementation.

### KR-11 — Pet toxicity and emergency escalation

- **Sources:** [ASPCA lily toxicology record](https://www.aspca.org/pet-care/aspca-poison-control/toxic-and-non-toxic-plants/lily), [ASPCA cat plant list](https://www.aspca.org/pet-care/animal-poison-control/cats-plant-list).
- **Grade:** B/C; recognized veterinary toxicology guidance, US service context.
- **Purpose:** Ground pet-risk warnings and show why botanical identity matters.
- **Summary:** ASPCA identifies `Lilium` species as toxic to cats and provides plant lists using common and scientific names with species-specific toxicity records.
- **Grounded facts:** “Lily” is an unsafe level of precision because common-name groups differ. A mixed bouquet can hide a hazardous stem; suspected exposure belongs with a veterinarian, not a home-remedy article.
- **Incorporation:** Use in `FLR-01`, `FLR-07`, `FLR-08`, `FLR-13`, `FLR-16`. Require botanical-name confirmation, disclose unresolved identity, keep hazardous stems away from pets, and include immediate local veterinary escalation.
- **Limits/recheck:** Do not label an arrangement universally “pet safe,” diagnose poisoning, copy a foreign hotline as local advice, or infer safety from omission from one list.

### KR-12 — Allergy and occupational respiratory risk

- **Sources:** [CDC/NIOSH work-related asthma guidance](https://www.cdc.gov/niosh/bulletin/2026/asthma.html), [CDC archived florist study](https://stacks.cdc.gov/view/cdc/196645/cdc_196645_DS1.pdf).
- **Grade:** B/C; occupational evidence, not individual diagnosis or Indonesian regulation.
- **Purpose:** Ground allergy, fragrance, pollen, cleaning-product, mold, and florist-workplace discussions.
- **Summary:** NIOSH explains that workplace irritants and allergens can cause or worsen asthma, sometimes after repeated exposure; a florist study found associations between flower sensitization and asthma-like symptoms.
- **Grounded facts:** Pollen, fragrance, plant sap, mold, dust, cleaning products, and repeated handling are different exposure pathways. Symptoms and triggers need clinical and workplace evaluation rather than a “hypoallergenic flower” guarantee.
- **Incorporation:** Use in `FLR-05`, `FLR-07`, `FLR-11`, `FLR-13`, `FLR-14`. Explain exposure reduction, ventilation, hygiene, substitution questions, symptom records, and stop/escalation conditions.
- **Limits/recheck:** Do not diagnose, prescribe PPE from this summary, claim zero-allergen arrangements, or import US occupational rules as Indonesian law.

### KR-13 — Responsible production and certification verification

- **Sources:** [GLOBALG.A.P. IFA for flowers and ornamentals](https://globalgap.org/what-we-offer/solutions/ifa-flowers-and-ornamentals/), [GLOBALG.A.P. product-category definition](https://documents.globalgap.org/documents/GLOBALGAP_product_list_April2025_en.pdf).
- **Grade:** B.
- **Purpose:** Replace vague “eco-friendly flower” claims with verifiable production, worker, environment, and traceability questions.
- **Summary:** GLOBALG.A.P. describes a flowers-and-ornamentals assurance standard covering responsible production topics, with published principles, criteria, and certification scope.
- **Grounded facts:** A standard's existence does not prove that a farm, supplier, species, site, or shipment is certified. Certification claims need the scheme, holder, scope, validity, and traceable product link.
- **Incorporation:** Use in `FLR-02`, `FLR-06`, `FLR-12`, `FLR-16`. Create a supplier-evidence checklist that records certificate identity/scope separately from broader sustainability questions.
- **Limits/recheck:** Do not imply endorsement or certification without a current certificate and scope verification. Compare schemes only from current owner documents and local legal context.

### KR-14 — Protected species and international trade

- **Sources:** [CITES orchid trade decision record](https://cites.org/eng/node/134831), [CITES appendices](https://cites.org/eng/app/appendices.php).
- **Grade:** A/B for treaty-listing context.
- **Purpose:** Prevent sourcing and sustainability articles from treating all ornamental plant material as unrestricted commerce.
- **Summary:** CITES regulates international trade in listed species, including extensive orchid coverage, through appendices, annotations, permits, exemptions, and party implementation.
- **Grounded facts:** Botanical identity, wild/artificial propagation, specimen type, source country, destination, annotation, and current appendix can affect trade treatment.
- **Incorporation:** Use in `FLR-01`, `FLR-02`, `FLR-12`, `FLR-16`. Add a protected-species/import gate before discussing imported or unusual flowers and link to current Indonesian competent-authority procedures.
- **Limits/recheck:** A CITES page does not prove a particular shipment is legal or illegal. Recheck current appendices, annotations, permits, Indonesian quarantine/customs rules, and competent-authority advice.

### KR-15 — Floral waste, separation, and compost claims

- **Sources:** [US EPA composting overview](https://www.epa.gov/sustainable-management-food/composting), [US EPA home-compost feedstock limits](https://www.epa.gov/recycle/composting-home).
- **Grade:** C; technical concept, not Indonesian waste regulation.
- **Purpose:** Ground end-of-life articles and prevent “biodegradable” from becoming an automatic disposal instruction.
- **Summary:** EPA describes composting as managed aerobic decomposition and emphasizes feedstock separation, contamination control, moisture, oxygen, and process conditions.
- **Grounded facts:** Plant matter, wire, tape, foam, plastics, treated material, ribbons, cards, coatings, and packaging are different waste streams. Compostability depends on material and the receiving process.
- **Incorporation:** Use in `FLR-07`, `FLR-08`, `FLR-09`, `FLR-10`, `FLR-11`, `FLR-12`, `FLR-14`. Show disassembly and separation first; direct readers to actual local facility rules.
- **Limits/recheck:** Do not claim compostability, biodegradation time, emissions savings, or local acceptance without product evidence and local waste-operator confirmation.

### KR-16 — Transport compatibility and delivery condition

- **Sources:** [UC Davis mixed-load transport guidance](https://postharvest.ucdavis.edu/ask-produce-docs/can-you-help-me-container-consolidation-mixed-load-shipments), [UC Davis cut-flower collection](https://postharvest.ucdavis.edu/publication-category/cut-flowers).
- **Grade:** B.
- **Purpose:** Ground transport and handoff articles in temperature, ethylene, packing, and species compatibility rather than generic “fast delivery.”
- **Summary:** UC Davis advises treating many cut flowers as ethylene-sensitive in mixed loads while recognizing that tropical flowers may be injured by low temperatures suitable for other commodities.
- **Grounded facts:** Compatibility depends on species, treatment, temperature range, ethylene exposure, duration, packaging, air flow, physical support, and opening stage.
- **Incorporation:** Use in `FLR-02`, `FLR-05`, `FLR-06`, `FLR-08`, `FLR-09`, `FLR-10`, `FLR-11`, `FLR-16`. Build packing, dispatch, receiving, and exception checklists around recorded conditions and observable damage.
- **Limits/recheck:** Container guidance does not establish a last-mile delivery promise or one temperature for a mixed bouquet. Validate product-specific and route-specific conditions.

### KR-17 — Hand tools, blades, and craft stop conditions

- **Sources:** [US OSHA hand and power tools overview](https://www.osha.gov/hand-power-tools), [OSHA sharp-tool interpretation](https://www.osha.gov/laws-regs/standardinterpretations/1976-09-15).
- **Grade:** C; hazard principles, not Indonesian legal requirements.
- **Purpose:** Keep floral-craft tutorials from normalizing damaged tools, uncontrolled blades, unsafe cutting paths, or public structural work.
- **Summary:** OSHA identifies hand tools as injury hazards when improperly used or maintained and emphasizes suitable condition, guarding where applicable, and protection from cuts or flying particles.
- **Grounded facts:** Secateurs, knives, wire cutters, pins, thorns, wire ends, hot tools, ladders, and heavy/elevated frames present distinct hazards. A small tabletop craft tutorial does not qualify a reader for vehicle-mounted, elevated, electrical, or public installations.
- **Incorporation:** Use in `FLR-05`, `FLR-11`, `FLR-13`, `FLR-14`. Include tool inspection, stable work area, cutting-path control, storage, cleanup, and professional stop conditions.
- **Limits/recheck:** Obtain Indonesian K3 requirements, manufacturer instructions, task risk assessment, and competent supervision before workplace or installation procedures.

### KR-18 — Honest photography, scale, and proof

- **Sources:** [UU No. 8 Tahun 1999 — BPK](https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999), [UU No. 27 Tahun 2022 — Komdigi JDIH](https://jdih.komdigi.go.id/produk_hukum/view/id/832/t/undangundang%2Bnomor%2B27%2Btahun%2B2022).
- **Grade:** A for legal context; Gate for visual methodology.
- **Purpose:** Tie product and delivery imagery to truthful representation and privacy instead of aesthetic polish alone.
- **Summary:** Consumer-information and personal-data duties create two separate checks: an image should not mislead about the offered or delivered item, and it should not expose unnecessary identifiable data.
- **Grounded facts:** Lens choice, crop, lighting, white balance, editing, missing scale, staged context, old stock images, faces, addresses, messages, and location metadata can change what an image communicates or discloses.
- **Incorporation:** Use in `FLR-06`, `FLR-15`, `FLR-16`. Require a current shot list, color/scale reference, view set, edit disclosure where material, rights record, and privacy-safe proof workflow.
- **Limits/recheck:** The laws do not prescribe a floral shot list. Obtain legal/privacy review for publication and use original controlled tests before giving color-accuracy instructions.

## Topic coverage matrix

| Topic family | Primary records | Coverage purpose | Mandatory article-level gate |
| --- | --- | --- | --- |
| `FLR-01` | KR-02, KR-03, KR-11, KR-14 | Names, commercial identity, substitutions, risk, and trade status | Verify botanical/cultivar identity for every product-specific statement |
| `FLR-02` | KR-03, KR-05, KR-13, KR-14, KR-16 | Production context, seasonality, provenance, certification, and logistics | Obtain current supplier stock/provenance and import/quarantine evidence |
| `FLR-03` | KR-06 | Meaning, occasion, message, and etiquette | Local cultural/faith/recipient-context review before prescriptive advice |
| `FLR-04` | KR-07 | Color, balance, rhythm, proportion, and visual brief | Use original annotated floral examples and practitioner review |
| `FLR-05` | KR-04, KR-05, KR-12, KR-16, KR-17 | Conditioning, sanitation, temperature, exposure, and tool safety | Species/product label and Indonesian K3 check before procedures |
| `FLR-06` | KR-02, KR-03, KR-04, KR-08, KR-09, KR-18 | Quality, quotes, substitutions, receiving, and truthful evidence | Current offer, measurement method, approval, and receiving record |
| `FLR-07` | KR-04, KR-05, KR-11, KR-12, KR-15 | Household care, deterioration, exposure, and disposal | Species-specific care source and veterinary/clinical escalation wording |
| `FLR-08` | KR-04, KR-06, KR-07, KR-08, KR-11, KR-15 | Bouquet/box selection, presentation, care, and claims | Current product mechanics, dimensions, identity, and recipient-risk check |
| `FLR-09` | KR-04, KR-06, KR-07, KR-08, KR-15 | Table/standing scale, viewing, stability, care, and end of life | Original dimension/stability review for the exact arrangement and venue |
| `FLR-10` | KR-04, KR-06, KR-07, KR-08, KR-15 | Boards/crosses, readability, respect, mechanics, and retrieval | Local cultural review, message proof, structural check, and venue approval |
| `FLR-11` | KR-04, KR-07, KR-08, KR-09, KR-10, KR-12, KR-16, KR-17 | Event brief, installation, transport, safety, privacy, and contingency | Venue/vehicle permission, risk assessment, competent installation evidence |
| `FLR-12` | KR-02, KR-03, KR-13, KR-14, KR-15 | Sourcing, certification, materials, reuse, and waste | Current certificate/scope plus product/facility-specific disposal evidence |
| `FLR-13` | KR-02, KR-10, KR-11, KR-12, KR-17 | Botanical identity, pets, allergy, privacy, and handling | Veterinary/clinical/K3 review; no “safe” or “hypoallergenic” absolute |
| `FLR-14` | KR-04, KR-12, KR-15, KR-17 | Tools, mechanics, small craft, reuse, and stop conditions | Manufacturer instructions and professional handoff for unstable/public work |
| `FLR-15` | KR-07, KR-08, KR-09, KR-10, KR-18 | Visual accuracy, scale, rights, delivery evidence, and privacy | Original controlled photo test, rights record, and privacy review |
| `FLR-16` | KR-03, KR-08, KR-09, KR-10, KR-13, KR-14, KR-16, KR-18 | Ordering, partner control, QC, handoff, exceptions, and recovery | Current policy/legal review and traceable order/partner/delivery evidence |

## Evidence gates

| Gate | Applies to | Resolve before an outline may assert | Required proof |
| --- | --- | --- | --- |
| `EG-01` | All product and substitution topics | Identity, availability, season, grade, dimensions, color, or stem count | Current supplier/product record with botanical/trade identity and date |
| `EG-02` | FLR-03, FLR-08–FLR-11 | Universal meaning, etiquette, condolence, faith, or ceremony rule | Named local cultural/faith reviewer and scoped source |
| `EG-03` | FLR-05, FLR-07 | Exact temperature, chemical, preservative, dose, or vase-life number | Current species/cultivar source, product label, and use-context review |
| `EG-04` | FLR-06, FLR-08–FLR-11, FLR-16 | Price, discount, stock, delivery time, coverage, warranty, or substitution policy | Dated approved commercial record from the responsible operator |
| `EG-05` | FLR-09–FLR-11, FLR-14 | Stability, load, elevated work, vehicle attachment, or public installation safety | Venue/vehicle approval, competent design, risk assessment, and method statement |
| `EG-06` | FLR-11, FLR-15, FLR-16 | Permission to publish recipient, venue, address, message, face, plate, or delivery proof | Data-minimization and lawful-basis/consent record reviewed for Indonesia |
| `EG-07` | FLR-12 | “Certified,” “sustainable,” “local is greener,” “plastic-free,” or “compostable” | Current certificate/scope, comparative method, product declaration, and receiving-facility acceptance |
| `EG-08` | FLR-02, FLR-12, FLR-16 | Imported/protected-species legality or unrestricted trade | Botanical identity, current CITES annotation, permits, and Indonesian authority check |
| `EG-09` | FLR-07, FLR-13 | “Pet safe,” “hypoallergenic,” diagnosis, treatment, or emergency instruction | Qualified veterinary/clinical review and local escalation route |
| `EG-10` | FLR-05, FLR-13, FLR-14 | Workplace PPE, chemical handling, blade, ladder, or machinery procedure | Indonesian K3 review, manufacturer instructions, and task risk assessment |
| `EG-11` | FLR-06, FLR-15, FLR-16 | Image accurately represents a current product or delivered order | Original dated image set, scale/color controls, edit record, rights, and order linkage |
| `EG-12` | FLR-06, FLR-16 | Legal entitlement, mandatory refund, liability, or dispute outcome | Current consolidated Indonesian law and qualified legal review |

## Refresh triggers

- Recheck BPS and Ministry production data when a newer annual/final dataset is published.
- Recheck Indonesian consumer, PMSE, privacy, quarantine, CITES-implementation, and K3 rules before legal or compliance outlines.
- Recheck POWO and CITES whenever botanical identity or protected-species trade matters.
- Recheck UC Davis species records and every chemical/product label before procedural or numeric advice.
- Recheck certificates, stock, product photos, prices, delivery areas, service policies, florist partners, and venue permissions at outline approval and again before publication.
- Revalidate this file whenever `TOPICAL_AUTHORITY.md` changes.

## Explicit exclusions

This research does not authorize article outlines, article drafting, HTML hydration, publication dates, article sitemap changes, deployment, GSC submission, geographic doorway expansion, fabricated case studies, unsupported company claims, or operational promises.
