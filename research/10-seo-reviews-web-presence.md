# Owned presence, search and reputation infrastructure for Dr. Avinash Paturi / Pathuri (India, Nov 2026)

**Executive summary**

1. **The regulatory ground moved five weeks ago.** On 6 Oct 2026 the NMC issued binding *Guidelines on Ethical Advertising and Public Communication* (No. R-13014/01/2024-Ethics, read in full for this report). They treat websites, search, platforms and AI content as "advertisement" when promotional; bar requesting or sharing patient reviews/testimonials for promotion; bar "engag[ing] any third party for marketing medical services"; and require name, qualifications and registration number on every electronic post. The whole system must be built as **public education + factual identity**, not marketing.
2. **Google permits asking for reviews; the NMC text does not safely permit it.** Recommended rule: no solicitation, no QR-to-Google, no reposting of reviews. Keep the profile factual, reply neutrally, collect private feedback. He already has strong reviews, so the cost of compliance is low.
3. **His web identity is fragmented.** Live listings disagree on spelling order, location (Financial District vs Jubilee Hills vs Rajahmundry), experience (4 / 6 / 13+ / 14 years) and MBBS year. Fixing one canonical record and propagating it is the highest-value first job.
4. **An owned, bilingual "entity home" website is the anchor** for Google, AI assistants and impersonation defence. Cost is small (roughly ₹1,500–35,000/year depending on stack); the constraint is doctor review time, not money. FAQ rich results were retired by Google in May 2026, so FAQ content now earns AI/voice answers, not SERP decoration.
5. **Deepfake doctor-endorsement ads are a documented Indian problem** (Trehan, V. Mohan, Devi Shetty). Pre-emptive handle/domain registration, a public "official channels" page, monthly monitoring and a pre-written takedown kit are cheap insurance.

> **Research-method caveat (read this).** The shared web-search budget for this run was exhausted after six searches. Everything after that was done by fetching known primary-source URLs directly (Google help/developer docs, the NMC PDF, WhatsApp policy, pricing pages, Medical Dialogues, MediaNama, Whitespark, BrightLocal, Ahrefs, SE Ranking). Claims I could not re-verify online in this session are marked **[prior knowledge – not re-verified]** with lower confidence. No search-volume data could be pulled. A second round with search access is warranted for the gaps listed at the end.

---

## Findings

### 0. The governing constraint: NMC Guidelines of 6 Oct 2026 (primary source read page by page)

Source: NMC public notice PDF, https://nmc.org.in/whats-new/download/1874 (13-page scanned PDF; read as images). **Confidence: High** on the text; **Medium** on how State Medical Councils will apply it (no enforcement history yet).

Legal position:
- The 2023 RMP (Professional Conduct) Regulations remain in abeyance since 23 Aug 2023; the IMC (Professional Conduct, Etiquette and Ethics) Regulations, 2002 are operative (https://medicaldialogues.in/health-news/nmc/breaking-news-nmc-puts-its-controversial-registered-medical-practitioner-professional-conduct-regulations-2023-put-on-hold-116314; https://gauravphogat.com/glossary/nmc-professional-conduct-regulations/). High.
- The 2026 Guidelines are "read with" the 2002 Regulations (cl. 4.2), framed "in view of" Supreme Court W.P.(C) 1160/2023, and came "into force with immediate effect".

Clauses that directly shape this workstream (quoted or closely paraphrased from the PDF):

| Clause | Text / effect | Consequence for web, search and reviews |
|---|---|---|
| 3.2 | "Advertisement" = any communication that "directly or indirectly solicits, promotes or is intended to promote the professional services, reputation, skills, qualifications, achievements…". Digital, "search-engine, platform-based… AI-generated or AI-assisted promotional communications shall be treated as advertising where their content or manner of dissemination has a promotional character." | Reputation-building itself is inside the definition when promotional. Tone and intent matter. |
| 3.2 Expl. I | Information "in the normal course of discharge of information to the public at large, without same being promotional and without any intent for commercial benefit" is exempt. | The safe harbour: public education. |
| 3.2 Expl. III | "RMP while publishing any Electronic media posts should transparently disclose their name, qualifications, registration status and SMR/NMR Registration number." | Site footer, every article byline, every social bio/post, YouTube descriptions. |
| 3.2 Expl. V | No RMP shall "solicit, purchase, procure, manipulate or cause to be published fake, paid or misleading patient reviews, ratings, testimonials…". "An RMP shall not request or share patient testimonials, recommendations, endorsements or reviews for professional promotion on social media." | See §2.6 on Google reviews. |
| 3.5 | "Medium of advertisement" includes "websites and blogs", messaging platforms (WhatsApp, Telegram), podcasts, "public interviews, news articles intended for promotion, online healthcare platforms". | Website, WhatsApp, Practo-type listings and PR interviews are all in scope. |
| 4.4 | Publishing through a platform, agency, influencer or intermediary does not absolve the RMP for content "authorized, commissioned, sponsored, adopted or knowingly permitted". | He is answerable for what the friend, an AI system, or a hospital marketing team publishes with his knowledge. |
| 5.1 | RMPs "may participate in health awareness programmers, public health campaigns, academic discussions, educational content, provided that such activities do not promote personal practice, do not solicit patients and are not monetized through promotional marketing." | The permitted lane. |
| 6.2 | Patient consent "shall not, by itself, make permissible any testimonial, endorsement, promotional patient story, before-and-after depiction, success claim". | No patient stories as promotion, even with consent. |
| 7.2 | "AI Generated promotional campaign for furtherance of commercial interest is prohibited." Compliant AI content must "carry the source mark"; AI must not create synthetic patient/RMP endorsements; patient data into AI systems must meet privacy rules. | Governs the planned Claude-based system (see Risks). |
| 8.1(ii) | Shall not "solicit patients directly or indirectly, promote his/her professional services through self-promotion, engage any third party for marketing medical services, permit the use of their name, image, voice, testimonial or endorsement for promotion of services or any products". | The friend's role must be framed and documented as education/communications support, not service marketing. |
| 8.1(iii) | Shall not advertise "personal achievements or professional success rates or number of patients treated" with assertions such as "Best doctors", "No.1 Specialist", "100% success". | Procedure-count boasts ("2,300 angiographies") are risky as promotion; see §1.9. |
| 8.1(ix) | No "best", "No.1", "leading", "top" claims unless objectively verifiable with transparent methodology. | Never self-describe as "best cardiologist in…"; do not target that phrase in titles. |
| 8.1(xii) | Shall not "procure, manipulate… fake followers, likes, reviews, ratings… or manipulate search rankings, visibility or algorithms to create a misleading impression of professional standing." | Honest technical SEO is fine; link buying, fake engagement and paid rank are not. |
| 8.2 | Permitted: published case studies; formal announcements (starting practice, change of address/type, absence, resumption, "public declaration of charge"); lectures/talks "in their own name and designation, without promoting their employer organization"; patient education pamphlets; greetings. | Education in his own name is explicitly allowed; do not turn it into Apollo promotion. |
| 9.1 | A hospital website's doctor directory with "names, recognised qualifications, specialties, registration details and availability" is a patient-information function, not advertising. | The model for his own site's factual "About / Where I consult" page. |
| 9.2 | Use of the RMP's photograph is not permitted "where such use constitutes self-advertisement"; self-photo on letterhead/signboard is unethical. | A plain professional headshot on an About page is defensible; hero-style glamour imagery and photo ads are not. Interpretation – Medium. |
| 9.4 | "All healthcare platforms hosting RMP shall ensure… prohibition of paid ranking of doctors". | Factual listings acceptable; never buy placement. |
| 10.1 | Graded action by the State Medical Council: warning + ethics training → censure + fine → 3–6 month suspension → 6–12 months for "digital mass solicitation" etc. → removal 1–3 years. | Real licence risk. |

Secondary readings agree on the core (https://medicaldialogues.in/health-news/nmc/nmc-issues-ethical-advertising-public-communication-guidelines-for-doctors-hospitals-details-180731; https://thesouthfirst.com/health/doctors-on-instagram-nmc-says-no-to-patient-testimonials-paid-ads-ai-promotions-and-guaranteed-claims/; https://www.policyedge.in/p/nmc-restricts-misleading-medical-ads-paid-rankings-and-ai-generated-testimonials; https://www.doctopath.com/blog/nmc-advertising-guidelines-2026-for-doctors).

Older context: a 2019 Maharashtra Medical Council RTI reply answered "NO" to whether allopaths may list on JustDial/Sulekha/Practo (https://medicaldialogues.in/doctors-cannot-list-with-online-platforms-like-justdial-or-practo-medical-council-gives-rti-response) – state-specific and **stale (2019)**; clause 9.4 of the 2026 Guidelines now presupposes that platforms host RMPs. Medium.

---

### 1. Personal website

**1.1 Why have one at all.** Google's knowledge panels are "automatically generated" from web information and cannot be requested (https://support.google.com/knowledgepanel/answer/9163198). The practical lever is a single authoritative page about the person that every other profile points to and agrees with (the "entity home" idea popularised by Kalicube – **[prior knowledge – not re-verified]**, Medium). A site he controls is also the only place where his name spelling, registration number and "official channels" list are guaranteed correct, which matters for impersonation defence (§6). High.

**1.2 Must-have pages (ordered by value)**

| Page | Content | NMC-safe framing |
|---|---|---|
| Home | One-paragraph who/what/where; latest articles; links to official profiles | Informational, no superlatives |
| About / Credentials (entity home) | Full name + alternate spellings, MBBS/MD/DM with institutions and years, registration council and number, current affiliations, training, publications, languages, professional headshot | Mirrors cl. 9.1 directory fields |
| Where I consult | Hospital name(s), address, OPD days/times, hospital appointment desk number and official hospital booking link, consultation fee if he chooses (permitted as "public declaration of charge") | Factual availability, no "Book now" urgency, no offers |
| Heart health library (EN) | Condition and procedure explainers, FAQ library | Education (cl. 5.1) |
| గుండె ఆరోగ్యం (TE) | Telugu originals, not machine translations | Same |
| Research & teaching | Publications (PubMed/ORCID links), talks, CME, trial participation | Factual; cl. 8.2(i) |
| Media & talks | Links to interviews/lectures | Avoid "as seen on" badge walls |
| Official channels & verification | List of every genuine handle; "I do not endorse any product, supplement or medicine; any video saying so is fake"; how to report | Anti-impersonation |
| Editorial policy | Who writes, how reviewed, date-reviewed policy, how AI assistance is used and disclosed, sources policy | Meets Google "Who/How/Why" + NMC 7.2(c) |
| Medical disclaimer, Privacy notice, Terms, Contact | See 1.8 | DPDP |

Do **not** include: testimonials page, Google-review widgets or screenshots, before/after or patient stories, procedure-count banners, "best/top/leading" language, discount or package offers, pop-up appointment CTAs.

**1.3 E-E-A-T / YMYL.** Google: "E-E-A-T itself isn't a specific ranking factor"; "Of these aspects, trust is most important"; extra weight for health ("Your Money or Your Life") topics; authorship should be "self-evident"; AI use should be disclosed where readers would wonder (https://developers.google.com/search/docs/fundamentals/creating-helpful-content). High. Practical signals: named physician author on every page, "medically reviewed / last reviewed on" dates, references to guidelines (ESC/ACC/CSI) and trials, consistent credentials sitewide, real About and Contact pages.

**1.4 Schema markup (what still matters in Nov 2026)**

- `Physician` exists in schema.org with subtypes `IndividualPhysician` and `PhysiciansOffice`; properties include `medicalSpecialty`, `hospitalAffiliation`, `availableService`, `occupationalCategory` (https://schema.org/Physician, V30.1 dated 2026-09-16). High.
- Google's `ProfilePage` markup is meant for pages about one person, explicitly including "An 'About Me' page on a blog"; `mainEntity` → `Person` with `name`, `alternateName`, `description`, `identifier`, `image`, `sameAs` (https://developers.google.com/search/docs/appearance/structured-data/profile-page). High.
- **FAQ rich results are gone.** Google's FAQPage documentation carries a notice that the feature "will no longer appear in Google Search starting May 7, 2026" and the page was removed on 15 June 2026 (https://developers.google.com/search/docs/appearance/structured-data/faqpage). High. FAQ *content* remains valuable for AI answers and long-tail queries; FAQPage markup is optional and yields no SERP feature.
- There is no Google rich result specific to doctors; the value of markup is entity disambiguation, not decoration. Structured data must match visible text (https://developers.google.com/search/docs/appearance/ai-features). High.

Recommended JSON-LD set:
1. About page: `ProfilePage` → `mainEntity: Person` (`name`, `alternateName` for all four spelling/order variants incl. Telugu script, `honorificPrefix`, `jobTitle`, `knowsAbout`, `alumniOf`, `hasCredential`, `identifier` = registration number + council, `worksFor`/`affiliation` → `Hospital`, `knowsLanguage`, `sameAs` → Apollo profile, Apollo 24|7, ORCID, Google Scholar, PubMed, LinkedIn, YouTube, X, Practo, Wikidata when it exists).
2. Where-I-consult page: one `IndividualPhysician` per location (`address`, `geo`, `openingHoursSpecification` = his OPD hours, `hospitalAffiliation`, `medicalSpecialty`, `telephone` = hospital desk), each linked to the Person by `@id`.
3. Articles: `MedicalWebPage` or `Article` with `author` → the Person `@id`, `datePublished`, `dateModified`, `inLanguage`, `citation`.
4. Sitewide: `WebSite`, `BreadcrumbList`.

**1.5 Bilingual SEO and hreflang.** Google supports hreflang via HTML tags, HTTP headers or sitemap; every version must list itself and all others ("If two pages don't both point to each other, the tags will be ignored"); codes are ISO 639-1 language + optional ISO 3166-1 region (`te`, `te-IN`, `en-IN`); `x-default` for fallback; and Google does **not** use hreflang or the `lang` attribute to detect language – it reads the content (https://developers.google.com/search/docs/specialty/international/localized-versions). High.
- Structure: `/` (English) and `/te/` (Telugu) on one domain; pair pages only where a true equivalent exists; `hreflang="en-IN"`, `"te-IN"`, `x-default` → English.
- Write Telugu natively in Telugu script; add common transliterated ("Tenglish") phrasings in sub-headings/FAQ where natural, because many Telugu speakers type in Latin script (**practitioner observation, not verified with data** – Low/Medium).
- Telugu pages need their own titles, meta descriptions, slugs (Latin-transliterated slugs are easier to share than percent-encoded Telugu), and Telugu alt text.

**1.6 Domain naming with two spellings.** Observed today: every third-party listing found uses **"Dr. Pathuri Avinash"** (Apollo, Apollo 24|7, Citizens, Vaidam, Eka Care – see §3). The brief's preferred form is "Avinash Paturi".
- Decision rule: the canonical spelling should be the one on his **medical registration certificate**, because NMC Expl. III requires name + registration number on every post and patients/regulators verify against the register. Word order (Avinash Pathuri vs Pathuri Avinash) is handled well by search engines; the missing "h" is the real mismatch for a rare surname (Medium – reasoning, not tested).
- If the registered spelling is "Pathuri": use "Dr. Avinash Pathuri" (or keep "Pathuri Avinash") as display name, declare "Paturi" variants in `alternateName`, and state both once in visible text on the About page ("also written as…").
- If he insists on "Paturi": every listing in §3 and the hospital profiles must be changed first, and the registered-name form must still appear next to the registration number.
- Register both spellings in `.com` and `.in` (four domains, roughly ₹3,000–5,000/year total – **[prior knowledge – not re-verified]**), 301-redirect three to the canonical. Avoid specialty-plus-city keyword domains (reads as solicitation; brittle if he moves hospitals).
- Availability of `dravinashpaturi.com` / `drpathuriavinash.com` **could not be verified** (hosts did not resolve from this sandbox, which may be a network allow-list effect, not proof of availability).

**1.7 Core Web Vitals.** "Good" = LCP ≤ 2.5 s, INP < 200 ms, CLS < 0.1; Google "highly recommend[s]" achieving them but gives no weight (https://developers.google.com/search/docs/appearance/core-web-vitals). High. For a mostly-text site on Indian mobile networks: static or cached pages, system or one web font with Telugu subset (Telugu fonts are large – subset or use system fonts), compressed WebP/AVIF images, no review/chat/social-feed widgets, YouTube embeds as click-to-load facades.

**1.8 Compliance text.**
- Footer on every page: full name, qualifications, registration number + council, "registration status: active" (NMC Expl. III).
- Medical disclaimer: educational information only; not a substitute for consultation; no doctor–patient relationship via the site; emergencies → call 108 / go to the nearest emergency department.
- No-endorsement statement (see §6).
- Independence statement: views are his own; site is not an official site of any hospital; hospital names used only to state where he consults (aligns with cl. 8.2(iii) "without promoting their employer organization").
- Privacy notice per DPDP (§7): what is collected (newsletter email, contact form), purpose, how to withdraw consent, grievance contact. Do **not** accept symptoms, reports or records through site forms.
- AI disclosure in the editorial policy; label any AI-generated illustration.

**1.9 Procedure counts and "achievements".** Apollo's profile reportedly lists ~2,300 angiographies, 150 STEMI PCIs, 80 device implants (per brief; the Apollo page returned HTTP 403 to my fetcher so I could not re-read it). Under cl. 8.1(iii) ("number of patients treated") and cl. 8.3(ii) ("promotional portrayal of an individual RMP" by hospitals), volume claims are exposed if stale, unverifiable or presented as a selling point. Recommendation: do not repeat counts on his own site; describe scope of practice factually; ask Apollo to either refresh from audited cath-lab data or drop them. Interpretation – Medium.

**1.10 Cost and no-code options (India, Nov 2026)**

| Option | Verified price | Bilingual / schema / blog | Verdict |
|---|---|---|---|
| Carrd Pro Standard | US$19/year, custom domain, forms (https://carrd.com/pro) | One-page sites; no real blog or hreflang pairs | Good 1-day placeholder / "official channels" page only |
| Framer | Basic US$10/mo (30 pages, 2 CMS collections); Pro US$30/mo; extra locale US$20/mo each (https://www.framer.com/pricing) | Polished; Telugu locale adds cost → ~US$30–50/mo; schema via custom code | Best-looking, highest running cost; content locked to vendor |
| Webflow | Pricing page could not be fetched (parse error) | Localization is a paid add-on (**[prior knowledge]**) | Not recommended for a one-person site |
| WordPress self-hosted | Hostinger India Premium ₹139/mo on 48-month prepay (₹6,672 upfront), renews ₹449/mo, domain free year 1 (https://www.hostinger.com/in/pricing) | Polylang-type plugin for /te/; SEO plugin for schema (**[prior knowledge]**); huge freelancer pool in Hyderabad | Best fit if a human operator edits in a dashboard; needs update/security hygiene |
| Static site (Markdown in a Git repo, generated and maintained with Claude Code, hosted on a free static host) | Hosting typically free; domain only (**[prior knowledge – not re-verified]**) | Full control of hreflang/JSON-LD; fastest CWV; nothing to hack | Best fit *if* the friend's Claude-based system will run content; needs someone comfortable with that workflow |

One-off build if outsourced: a competent freelancer build of a 10–15 page bilingual WordPress site in Hyderabad is plausibly ₹20,000–60,000 (**my estimate, not sourced** – Low). Professional headshots and Telugu editing are separate small costs.

**1.11 Being hospital-employed (Apollo).** I **could not find or verify** Apollo's consultant agreement terms or a published social-media/personal-website policy for consultants. What is known:
- NMC cl. 8.2(iii) expects public talks "in their own name and designation, without promoting their employer organization"; cl. 4.4/11.5 make him personally answerable for hospital communications he "authorized, participated in, endorsed".
- Standard practice in corporate hospitals (**general knowledge, Low/Medium**): brand name/logo use needs written permission; appointment and fee collection must route through the hospital; some contracts restrict outside practice or media statements.
- Safe pattern: text-only mention of the hospital as place of practice; link out to the hospital's own doctor page for booking; no hospital logo, no cath-lab footage, no patient-area photography without written clearance; inform the unit head / marketing head in writing before launch and keep the reply.

---

### 2. Google Business Profile (GBP) for a practitioner inside a hospital

**2.1 Policy (primary source).** Google's guidelines (https://support.google.com/business/answer/3038177): High.
- "An individual practitioner is a public-facing professional, typically with their own customer base." Eligible if public-facing and directly contactable at the verified location during stated hours.
- Multiple practitioners at one location: "The organization should create a Business Profile for this location, separate from that of the practitioner." "The title of the Business Profile for the practitioner should include only the name of the practitioner" (titles/degrees such as Dr., MD allowed).
- "A practitioner shouldn't have multiple Business Profiles to cover all of their specializations."
- Names: no taglines, location or service keywords.
- Categories: "as few categories as possible"; describe what the business *is*.

**2.2 Duplicates, multi-location, ownership.**
- One practitioner listing per physical location where he actually holds OPD hours; third-party guidance says each needs that location's address and preferably a distinct phone, and that practitioner listings should point to the practitioner's own page (https://www.vdigitalservices.com/best-practices-for-managing-gbp-practitioner-listings – agency source, 2018 updated June 2026; Medium).
- Reviews stay with the listing they were left on and practitioner reviews follow the practitioner when he moves (same source; Medium).
- Action: search Maps for both spellings + each hospital; list every profile found; report true duplicates via "Suggest an edit → Close or remove → Duplicate"; request ownership or manager access of any practitioner listing created by the hospital rather than creating a second. He (not the hospital, not the friend) should be **primary owner** on his own Google account; the friend can be a manager.
- Whether his current "strong Google reviews" sit on a practitioner listing, the Apollo Financial District listing, or Citizens' listing **was not verified** (no Maps access in this session). This determines everything else here.

**2.3 Categories, services, links, posts, Q&A.**
- Primary category is the single strongest local-pack factor (Whitespark 2026, score 227, rank 1) – choose "Cardiologist" (exact category list should be checked in the GBP editor – **not verified**). Hours matter: "Business is Open at Time of Search" ranks 5th (https://whitespark.ca/local-search-ranking-factors/). High for the survey; it is expert opinion, not Google disclosure.
- Hours must be his real OPD hours at that location, not the hospital's 24×7 hours (policy: contactable during stated hours).
- Booking links: up to 10 appointment links can be added; third-party provider links can only be removed via the provider (https://support.google.com/business/answer/6218037). Use the hospital's official booking URL as preferred link. High.
- Website link: his own site's "Where I consult" page (or the Apollo doctor page until the site exists).
- Services list: factual procedure names only.
- Posts: use for education and factual announcements (absence, changed OPD timings). The API now supports recurring scheduled posts (https://developers.google.com/my-business/content/change-log, 2026-04-07). No offers, no claims.
- Photos: exterior/entrance/OPD signage for way-finding and a professional headshot; no patient images (cl. 7.4), no cath-lab glamour shots.
- Q&A: whether the classic Q&A feature is still shown on Indian profiles **could not be verified**; the change log shows nothing on it. Check in the live profile.

**2.4 Local pack ranking factors 2025–26.** Whitespark's 2026 report (published 6 Nov 2025, 47 experts) top local-pack factors: primary category (227), proximity of searcher (225), keywords in business title (223), address in city of search (213), open at time of search (189), high numerical rating (181), quantity of native reviews with text (170), recency of reviews (164, rank 11), "Sustained Influx of Reviews Over Time (rather than bursts)" (154, rank 14), HTML NAP matching GBP NAP (153). The report notes "an increased importance of review signals and behavioural signals" (https://whitespark.ca/local-search-ranking-factors/). High as a survey.
- Implication: proximity is uncontrollable; "keywords in title" must not be gamed (policy + NMC); what he can legitimately control is correct category, real hours, accurate pin, matching NAP on his website, and a natural trickle of genuine reviews.
- Consumer behaviour (BrightLocal 2026, US-centric): 74% only care about reviews from the last three months; 68% require ≥4 stars; 89% expect owners to respond; use of ChatGPT-type tools for local recommendations rose from 6% to 45% (https://www.brightlocal.com/research/local-consumer-review-survey/). Medium for India applicability.

**2.5 Google's own review rules.** Google allows asking: businesses can "ask customers to visit a Google link or scan a QR code" (https://support.google.com/business/answer/3474122). Google prohibits: incentives; "Discourage or prohibit negative reviews, or selectively solicit positive reviews from customers" (review gating); requesting specific content; pressuring on premises; staff review quotas; conflict-of-interest reviews (staff, family) (https://support.google.com/contributionpolicy/answer/7400114). High.

**2.6 Reconciling with the NMC.** The two regimes conflict in practice:

| Practice | Google | NMC 6 Oct 2026 | Recommended rule |
|---|---|---|---|
| Asking every patient for a Google review (verbal, card, QR, WhatsApp) | Allowed | "shall not request or share patient… reviews for professional promotion on social media" (Expl. V); "social media" is defined broadly (cl. 3.6) | **Do not do it.** At least one compliance vendor reads it the same way (https://medhive.in/blog/ethical-patient-feedback-nmc-guidelines – vendor, Medium) |
| Review gating (happy → Google, unhappy → private) | Prohibited | Prohibited (misleading impression, Expl. V, 8.1(xii)) | Never |
| Incentives, staff/family reviews, bought reviews | Prohibited | Prohibited | Never |
| Embedding/reposting reviews on website or social | Allowed | "request or share" barred | Do not |
| Replying to reviews | Encouraged | Not addressed | Yes, neutral and confidentiality-safe |
| Private feedback form (QR to a private form, not Google) | n/a | Not promotion | Yes, ideally run by the hospital |
| Organic, unsolicited reviews | Fine | Not prohibited | Let them come |

Residual ambiguity: Expl. V's second sentence is qualified by "for professional promotion on social media"; a lawyer could argue a neutral "feedback welcome on any platform" notice is not a request for promotion. I would not build a programme on that argument. Hospital-run review drives are the hospital's exposure, but cl. 11.5 reaches an RMP who "personally authorized, participated in" them. Confidence in the conservative reading: Medium-High.

**2.7 Responding without breaching confidentiality.** Duties of secrecy sit in the IMC 2002 Regulations (regs 2.2 and 7.14 – **[prior knowledge; the DMC PDF returned HTTP 503]**), NMC cl. 7.4 (no identifiable patient data) and the DPDP Act. Rules:
- Never confirm the reviewer is or was a patient; never mention diagnosis, dates, procedures, relatives or billing.
- Positive: "Thank you for taking the time to share this." Nothing more.
- Negative: "Thank you for the feedback. I can't discuss any individual's care in a public forum. Please contact [hospital patient-relations number/email] so this can be looked into properly." One reply, no argument.
- Reply within about a week (BrightLocal: 81% expect a reply within a week). Replies are now moderated by Google and can be rejected (ReviewReply PolicyViolation field, 2026-07-01 change log).

**2.8 Fake / negative reviews.** Google removes only policy-violating reviews; "Do not report a review just because you disagree with it". Route: report from the profile or the Reviews Management Tool → evaluation "typically takes several days" → one-time appeal (up to 10 reviews) → separate route for review-extortion scams (https://support.google.com/business/answer/4596773). High. Legal removal (defamation) is a separate, slower path through Google's legal request forms and Indian courts – use only for clearly false, damaging statements, with the hospital's legal team. A genuine unhappy patient is handled offline through hospital patient relations, never by flagging.

---

### 3. Third-party profiles in India

**3.1 What was actually found for him (fetched 12 Nov 2026)**

| Source | Name shown | Location | Experience | Other data | Issue |
|---|---|---|---|---|---|
| Apollo Hospitals doctor page (via search snippet; page itself 403) https://www.apollohospitals.com/doctors/interventional-cardiologist/hyderabad/dr-pathuri-avinash | Dr. Pathuri Avinash | Apollo Hospitals, Financial District | 6+ years | MBBS, MD, DM; reg. no. 74749; interests CTO, rotablation | Most authoritative; verify counts and hours |
| Apollo 24\|7 https://www.apollo247.com/doctors/dr-pathuri-avinash-07916af1-e7a6-4fed-b830-061c4924ffb3 | Dr. Pathuri Avinash | Apollo Financial District | 6+ years | Fee ₹1000; English, Hindi, Telugu, Bengali, Kannada; reg. 74749; MBBS dates "Mar 2006–Mar 2011"; no online consults | MBBS year differs from others (2012) |
| Citizens Specialty Hospital https://www.citizenshospitals.com/doctor/dr-pathuri-avinash | Dr Pathuri Avinash | Nallagandla | 4 years (search snippet) | – | Stale experience; is the affiliation current? |
| Vaidam https://www.vaidam.com/doctor/dr-pathuri-avinash | Dr. Pathuri Avinash | **Apollo Jubilee Hills** (wrong) plus Financial District, Narsingi clinic, Citizens, Ramesh Hospitals Vijayawada (2024), KIMS Rajahmundry (2021) | 6 years; other language versions say 13+ | Mentions NEJM pemafibrate trial contribution; uses "highly skilled", "expert" | Wrong primary hospital; promotional adjectives he did not write; contact hello@vaidam.com |
| Eka Care https://www.eka.care/doctor/dr-pathuri-avinash-cardiologist-rajahmundry | Dr. Pathuri Avinash | **Rajahmundry** | 14 years | DM 2020; MBBS Rangaraya 2012; reg. 74749, Andhra Pradesh Medical Council; **unclaimed** ("Claim this profile") | Wrong city; claim and correct |

Not verified (search budget exhausted): presence/state on Practo, Justdial, Lybrate, Credihealth, MediBuddy, Bajaj Finserv Health, Sehat, HexaHealth, Skedoc, Docplexus, Google Scholar, ORCID, LinkedIn, PubMed author record.

**3.2 Which matter (judgement; Medium)**

| Tier | Platform | Why | Action |
|---|---|---|---|
| 1 | Google Business Profile | Where "near me" and name searches resolve; feeds Gemini/AI Overviews local answers | Own, complete, keep current |
| 1 | Apollo doctor page + Apollo 24\|7 | Highest-authority page about him; likely top result for his name | Send corrected bio via Apollo marketing; ask for consistent name, years, hours |
| 1 | Citizens page | Second affiliation | Update or remove if no longer current |
| 2 | Practo | The Healthgrades-equivalent in India; free profile, 3 steps: find/register → add registration, fees, timings → online verification (https://www.practo.com/providers/doctors/profile) | Claim; factual only; decline paid visibility products (cl. 9.4, 8.1(vii)) |
| 2 | Justdial | Auto-generates listings that rank for "cardiologist in [area]" (**prior knowledge**) | Claim free listing; correct NAP; refuse paid packages/lead fees |
| 2 | Eka Care | Unclaimed profile with wrong city already ranks | Claim and correct |
| 2 | Vaidam, Credihealth, MediBuddy, Bajaj Finserv Health, HexaHealth, Lybrate | Aggregators; some feed AI answers and medical-tourism queries | Email correction requests; do not pay |
| 3 | Sehat, Sulekha, smaller directories | Low traffic | Fix only if wrong data ranks on page 1 for his name |
| Professional (not patient-facing) | ORCID, Google Scholar, PubMed, ResearchGate, LinkedIn, Docplexus, CSI/SCAI member directories | Entity corroboration and peer reputation | Create/claim with canonical name; these are the best `sameAs` targets |
| Government | State medical council register, National Medical Register / ABDM Healthcare Professionals Registry | The verifiable identity that NMC wants cited; HPR page returned 403 here | Confirm details are correct and current (**[prior knowledge]** that NMR/HPR exist) |

A correction email to a platform is also evidence that he did not "knowingly permit" promotional adjectives written by the platform (cl. 4.4) – keep a log.

**3.3 NAP consistency audit method (one-off 3–4 hours, then 30 minutes/quarter)**
1. Write the **canonical record** first (single source of truth, approved by him): display name; registered name; alternate spellings; degrees with institution + year; registration number + council; years since DM (state as "practising cardiology since 2020", which never goes stale); each location's exact name, address, PIN, phone, OPD hours; languages; bio in 50 / 150 / 400 words (EN + TE); headshot file; canonical URLs.
2. Discovery: search Google, Bing and Maps for each of `"Pathuri Avinash"`, `"Avinash Pathuri"`, `"Avinash Paturi"`, `"Paturi Avinash"`, each + `cardiologist`, + `Hyderabad`, + `Rajahmundry`, + `Vijayawada`, and the registration number `74749`. Also ask ChatGPT, Gemini and Perplexity "Who is Dr Pathuri Avinash, cardiologist?" and note what they cite.
3. Log every URL in a sheet: platform, URL, claimed? (Y/N), name, location, experience, qualifications, phone, hours, errors, owner/contact, date requested, date fixed.
4. Fix in order: GBP → Apollo/Apollo 24|7 → Citizens → Practo → Eka → Justdial → Vaidam → rest.
5. Re-check 30 days later; then quarterly. Old-city listings (Rajahmundry, Vijayawada) need explicit closure or relocation.

---

### 4. Entity SEO and AI search

**4.1 Knowledge Panel.** Google: panels are automatic; you cannot apply; once one exists you claim it by signing in to an official profile Google associates with the entity – YouTube, Search Console, Twitter/X or Facebook (https://support.google.com/knowledgepanel/answer/7534902). High. For a doctor the *Business Profile* panel on name searches is the realistic near-term "panel"; a person Knowledge Panel typically follows consistent corroboration across independent authoritative sources and may take many months or never appear for a non-celebrity clinician (**estimate**, Low/Medium).

Sequence that gives the best odds (**practitioner method; Medium**):
1. Entity home = About page with ProfilePage/Person JSON-LD and outbound `sameAs`.
2. Every controlled profile uses the same name string, same one-line description, and links back to the entity home.
3. Identifiers: ORCID iD, Google Scholar profile, PubMed-linked name, LinkedIn, YouTube channel verified against the site in Search Console.
4. Independent mentions: hospital pages, society faculty pages (CSI, conference programmes), newspaper health columns, journal author pages.
5. Wikidata item once references exist (below).
6. Verify the site in Google Search Console early – it is one of the four accepted verification routes.

**4.2 Wikidata vs Wikipedia.**
- Wikidata accepts an item if it has a valid sitelink, **or** "refers to an instance of a clearly identifiable conceptual or material entity" describable with "serious and publicly available references", **or** fills a structural need; the bar is "intentionally left a bit vague" (https://www.wikidata.org/wiki/Wikidata:Notability). High. A cardiologist with an ORCID, PubMed-indexed papers (e.g., listed contributor to a NEJM trial – per Vaidam, **must be verified on PubMed**) and a hospital faculty page can plausibly qualify. Best created by someone other than the subject, with references on every statement, after the publications/ORCID exist. Self-promotional items do get deleted (**prior knowledge**).
- Wikipedia: academics need one of eight criteria (major research impact, prestigious award, selective fellowship, named chair, etc.), and the realistic route for a clinician is criterion 7 – substantial impact outside academia, e.g. frequent expert quotation – or general notability (https://en.wikipedia.org/wiki/Wikipedia:Notability_(academics)). High. He does not meet this today. **Do not create or commission a Wikipedia article**; it would likely be deleted and can leave a visible deletion record. Revisit only after sustained independent coverage, and then never self-write.

**4.3 Generative Engine Optimisation (AI-answer visibility), 2026**

What the platforms say:
- Google: "There are no additional requirements to appear in AI Overviews or AI Mode, nor other special optimizations necessary"; a page must be indexed and snippet-eligible; no new machine-readable or AI text files are needed; AI features use "query fan-out… issuing multiple related searches across subtopics and data sources"; keep Business Profile info current; AI-feature traffic is reported inside the Search Console Performance report (https://developers.google.com/search/docs/appearance/ai-features). High.
- OpenAI: allow `OAI-SearchBot` to appear in ChatGPT search; `GPTBot` is training-only and can be blocked separately; `ChatGPT-User` is user-triggered (https://developers.openai.com/api/docs/bots). High.
- Perplexity: allow `PerplexityBot`; `Perplexity-User` is user-triggered; Cloudflare bot-fight settings can block them (https://docs.perplexity.ai/guides/bots). High.
- Anthropic: `Claude-SearchBot` (search index), `Claude-User` (user-triggered fetch), `ClaudeBot` (training) (https://support.claude.com/en/articles/8896518-does-anthropic-crawl-data-from-the-web-and-how-can-site-owners-block-the-crawler). High.

What the data says:
- 76.1% of pages cited in Google AI Overviews rank in Google's top 10 (Ahrefs, 1.9M citations, July 2025) – classic SEO is the main lever for AI Overviews (https://ahrefs.com/blog/search-rankings-ai-citations/). High.
- For ChatGPT, Gemini, Copilot and Perplexity only ~12% of cited URLs rank in Google's top 10 for the same prompt (Perplexity 28.6%, others ~8%) – assistants draw on a wider, different set of sources (Ahrefs, 15,000 prompts, Aug 2025) (https://ahrefs.com/blog/ai-search-overlap/). High.
- In health AI Overviews, YouTube was the single most-cited domain (4.43% of 465,823 citations; 24 of the 25 most-cited videos were from medical channels); government and academic sources were ~1%; over 82% of health searches in the sample triggered an AI Overview (SE Ranking, Germany, Dec 2025 data) (https://seranking.com/blog/health-ai-overviews-youtube-vs-medical-sites/). Medium for India (German dataset).
- Local AI visibility (Whitespark 2026 expert survey), top factors: presence on expert-curated "best of" lists (179); a dedicated page for each service (170); prominence on key industry-relevant domains (167); quality of unstructured citations – news, government, associations (160); authority of third-party sites holding reviews (156) (https://whitespark.ca/local-search-ranking-factors/). High as a survey.
- 45% of (US) consumers used generative AI tools for local business recommendations in 2026, up from 6% (BrightLocal). Medium for India.

How assistants "pick doctors" (synthesis; Medium): for "best cardiologist in Gachibowli"-type prompts they lean on Maps/GBP data (Gemini, AI Overviews), aggregator and hospital pages, and third-party lists and news; for "what does left-sided chest pain mean" they cite explainer pages and YouTube. A doctor is named when multiple independent sources agree on who he is, where he is and what he does. So: consistent entity data (§3), one page per condition/procedure, physician-authored video with transcripts, and mentions on authoritative third-party domains.

What raises citation likelihood (practical):
- Answer-first writing: question as H2, a 40–60 word direct answer, then detail; tables for costs/steps/comparisons; clear "when to go to emergency" boxes.
- Visible authorship, review date, references.
- Text, not images of text; transcripts for every video; Telugu text for Telugu answers (few competitors).
- Crawlable: do not block Googlebot, OAI-SearchBot, PerplexityBot, Claude-SearchBot in robots.txt or at the CDN.
- Third-party corroboration: society pages, newspaper columns, hospital blog bylines, podcast show notes.

**llms.txt.** A proposal (Jeremy Howard, 3 Sep 2024) for a Markdown file at `/llms.txt`; the spec site does not claim any provider consumes it for answers (https://llmstxt.org/), and Google states no AI text files are needed. Verdict: optional, ten minutes, no evidence of benefit; do it last or skip. Medium-High.

**4.4 Name disambiguation.**
- Two spellings × two orders = four strings; plus old cities (Rajahmundry, Vijayawada) still attached to the name.
- Fixes: `alternateName` + one visible "also written as" line; registration number as a unique identifier on the site and in schema; ORCID iD on all papers going forward; one consistent author name for future publications (journals index "Pathuri A" and "Paturi A" as different authors); same headshot across profiles (assistants and people match faces/thumbnails).
- Whether other professionals share the name (namesake collisions) **was not checked** – do this in the audit.

---

### 5. Search demand

No keyword volumes could be pulled in this session. Method and working lists follow; treat the lists as hypotheses to validate.

**5.1 Research method (2–3 hours one-off; 30 minutes/month)**

| Tool | How to use | Output |
|---|---|---|
| Google Search Console (after site launch) | Performance → Queries; filter by page, country India; regex filter for brand terms | Real impressions; the only reliable Telugu data source |
| Google Keyword Planner (free with an Ads account, no spend needed) | Location = Hyderabad / Telangana; run language = English and = Telugu separately; enter seed terms in Telugu script and transliteration | Volume ranges, related terms |
| Google Trends | Region = Telangana (and Andhra Pradesh); compare ≤5 terms; use "Topics" not just strings; check "Related queries → Rising" | Seasonality (winter cardiac events, festival/fasting periods), relative demand |
| Google autosuggest + "People also ask" | Type seeds in English, Telugu script, and transliterated Telugu, in an incognito window with location Hyderabad | Question phrasing in real words |
| AlsoAsked / AnswerThePublic (free tiers) | One seed per day | Question trees for FAQ clusters |
| YouTube autosuggest | Telugu script and transliteration | Video topics; Telugu health search is heavily video-led (observation) |
| GBP Performance → "Searches" | Monthly export | The queries that already trigger his profile |
| His own OPD | Ask the team to note the 5 commonest patient questions each week (no patient identifiers) | The best FAQ source there is |

**5.2 Query families**

Local, high-intent (served mainly by GBP + hospital pages; his site supports with a factual "Where I consult" page – **do not** write "best cardiologist" pages, cl. 8.1(ix)):
- cardiologist in Financial District / Gachibowli / Nanakramguda / Kokapet / Narsingi / Nallagandla / Lingampally / Tellapur / Gopanpally / Manikonda
- heart specialist near me; cardiologist near me open now; 24 hour cardiac emergency Gachibowli
- interventional cardiologist Hyderabad; angioplasty doctor Hyderabad; pacemaker implantation Hyderabad

Cost / decision (high intent, low-quality competition from aggregators):
- angiogram cost Hyderabad; angioplasty cost Hyderabad; stent price India (NPPA ceiling prices are a factual hook); pacemaker cost; TMT / echo / CT calcium score cost; "Aarogyasri heart surgery" eligibility; insurance cashless angioplasty
- Handle as transparent explainers of what drives cost and what the government caps, not as price offers.

Symptom / worry (highest volume, YMYL, strongest AI-answer exposure):
- chest pain left side; chest pain gas or heart; heart attack symptoms in women; heart attack at young age / gym; breathlessness on stairs; palpitations at night; BP 150/100; high LDL; ECG abnormal meaning; troponin positive meaning

Telugu (script; needs native-speaker editing before use):
- గుండె నొప్పి లక్షణాలు (heart pain symptoms); గుండెపోటు లక్షణాలు (heart attack symptoms); ఎడమ వైపు ఛాతీ నొప్పి (left-side chest pain); గ్యాస్ నొప్పి లేదా గుండె నొప్పి (gas pain or heart pain); యాంజియోగ్రామ్ అంటే ఏమిటి (what is an angiogram); స్టెంట్ వేసిన తర్వాత జాగ్రత్తలు (care after a stent); బీపీ తగ్గడానికి ఏమి చేయాలి (how to lower BP); కొలెస్ట్రాల్ తగ్గించే ఆహారం (cholesterol-lowering diet)
- Transliterated variants: "gunde noppi lakshanalu", "heart attack lakshanalu telugu", "chest pain left side telugu"

Post-procedure / chronic care (low volume, very high trust value, few good Indian sources):
- after angioplasty diet (South Indian), driving/flying/sex after stent, blood thinner missed dose, pacemaker and mobile phones/airport security, cardiac rehab at home

**5.3 Content cluster design.** Hub-and-spoke, each hub with an English and a Telugu version:

| Hub (pillar page) | Example spokes | Video pair |
|---|---|---|
| Chest pain: when to worry | gas vs heart; left-side pain; women; young adults; what to do in the first 10 minutes | 3-minute Telugu explainer |
| Heart attack & emergency care | STEMI and the golden hour; why "door-to-balloon" time matters; aspirin at home? | Yes |
| Angiogram, angioplasty & stents | what happens; wrist vs groin; stent types; cost drivers; life after a stent | Yes |
| Blood pressure | home BP technique; targets; salt in Telugu diets | Yes |
| Cholesterol & prevention | LDL targets for Indians; statin myths; Lp(a); calcium score | Yes |
| Heart rhythm & devices | palpitations; AF; pacemaker/ICD living guide | Optional |
| Heart failure | fluid/salt; medicines; warning signs | Optional |
| Heart tests explained | ECG, echo, TMT, CT angio, troponin | Short clips |
| Young hearts & lifestyle | gym deaths; smoking/vaping; sleep; stress in IT workers (Financial District audience) | Yes |

**5.4 Patient FAQ library.** Target 100 questions in year 1 (about 2 per week), each: question (EN + TE), 50-word answer, 200–400 word explanation, "see a doctor urgently if…", references, reviewed-on date. Source questions from OPD, autosuggest, YouTube comments. Each FAQ is reusable as a short video script, a WhatsApp Channel post, a newsletter item and an AI-citable passage. Never answer individual cases in comments.

---

### 6. Online reputation management

**6.1 Monitoring on a small budget**

| Tool | Cost | Use |
|---|---|---|
| Google Alerts | Free | Alerts for all four name variants in quotes, plus name + "cardiologist", plus registration number |
| GBP notifications | Free | New reviews, edits suggested by the public |
| Search Console | Free | Branded query impressions; new sites linking to him |
| Manual monthly sweep (20 min) | Free | Google/Bing/YouTube/Instagram/Facebook search of name variants; Meta Ad Library search for his name; reverse image search of headshot; ask ChatGPT/Gemini/Perplexity who he is and log changes |
| Brand24 | From US$199/mo billed annually, 3 keywords (https://brand24.com/prices/) | Not justified at this stage |
| Mention | No public self-serve pricing; "request a demo" (https://mention.com/en/pricing/) | Not justified |

Paid social listening only becomes sensible if he reaches regular media presence or a crisis occurs (a 14-day Brand24 trial can cover a crisis window).

**6.2 Name-squatting protection (one-off 2–3 hours).** Register, even if left dormant with a bio link to the website: domains (both spellings, .com and .in); YouTube handle; Instagram; Facebook Page; X; LinkedIn (personal profile + custom URL); Threads; WhatsApp Channel; Telegram channel; Substack/newsletter subdomain; Google Scholar; ORCID; ResearchGate; Practo. Same handle pattern everywhere (e.g., `@dravinashpathuri` or the canonical equivalent), same headshot, same one-line bio with registration number. Store credentials in a password manager with 2FA on his own phone/email – he must be the legal owner of every account.

**6.3 Impersonation and deepfake risk – documented Indian cases**

| Case | What happened | Action / outcome | Source |
|---|---|---|---|
| Dr. V. Mohan (diabetologist, Chennai) | Video of a lookalike promoting a drug claimed to cure diabetes in under 48 hours; he noted it was in Hindi, which he does not speak | Complaint to Tamil Nadu police cyber cell, Nov 2023; removed, then reappeared ~Feb 2024 | https://medicaldialogues.in/news/health/doctors/menace-of-medical-deepfakes-attacking-indias-top-doctors-dr-naresh-trehan-becomes-the-latest-victim-126080 |
| Dr. Devi Shetty (cardiac surgeon) | Fake news-anchor style video promoting a joint-pain remedy "within three days", Feb 2024 | No complaint reported in the article | same |
| Dr. Naresh Trehan (Medanta) – 2024 | 35-second Facebook deepfake endorsing a weight-loss drug | Medanta's marketing AVP filed a complaint; FIR at Cyber East PS Gurgaon under IPC 419/420; link deactivated | same |
| Dr. Naresh Trehan – 2024–25 | Deepfakes pushing "natural remedies" for prostatitis/erectile dysfunction with Medanta branding; one posted 16 Nov 2024 reached ~1.1 million views | Delhi High Court (Justice Mini Pushkarna): poster to remove within 24 hours, platforms within 36 hours, future fakes blockable on notice within 36 hours, disclosure of uploader details; grounds: personality/publicity rights, trademark, passing off | https://medicaldialogues.in/news/health/doctors/remove-deepfake-videos-featuring-medanta-chief-dr-naresh-trehan-delhi-hc-141329 |
| Two women doctors, Karad (Maharashtra) | Obscene AI-generated video, June 2025 | Reported | https://medicaldialogues.in/news/health/doctors/2-karad-women-doctors-targeted-in-ai-generated-obscene-video-149923 |

All High confidence as reported by Medical Dialogues. Pattern: cardiology/diabetes/urology "miracle cure" ads on Meta platforms, targeting trusted senior doctors; the fake reappears after takedown. Hyderabad-specific cases were **not found** in this session (search budget) – likely exist; worth a follow-up. Courts are actively granting personality-rights relief against deepfakes in Oct–Nov 2026 (Bombay HC – Samantha Ruth Prabhu, Ananya Panday; Delhi HC – Kangana Ranaut, Arjun Kapoor) (https://www.medianama.com/tag/deepfakes/). High.

**Legal and platform levers (Nov 2026)**
- IT Rules amendment notified 10 Feb 2026 (G.S.R. 120(E)), effective 20 Feb 2026: platforms must act against synthetic content that "falsely depicts or portrays a natural person"; other synthetic content must be prominently labelled with embedded metadata; general takedown window cut to **three hours** (two for non-consensual intimate imagery); large platforms must obtain user declarations; non-compliance risks loss of safe harbour (https://www.medianama.com/2026/08/223-x-compliance-reports-synthetic-media-rules/). Medium-High (secondary source; gazette text not read; the three-hour window's exact trigger should be confirmed).
- NMC cl. 7.2(b): AI must not create "a synthetic endorsement or representation purporting to be that of an actual patient, RMP or other person" – useful to cite, and a reason to tell his State Medical Council promptly so he is on record as the victim.
- Grievance Appellate Committee: online appeal within 30 days if a platform's Grievance Officer rejects or ignores a complaint; covers Facebook, Instagram, WhatsApp, X, LinkedIn etc.; fraud goes to 1930 / cybercrime.gov.in (https://gac.gov.in/). High.

**Takedown route (pre-write this kit now; 2 hours)**
1. Evidence: screen-record the ad/video, URL, advertiser page name, Ad Library ID, date/time, any payment link. Do not engage or comment.
2. Platform report as impersonation/fraud via in-app tools and the platform's India Grievance Officer email, citing the Feb 2026 synthetic-media rules.
3. Same day: complaint on cybercrime.gov.in (and 1930 if money is being collected); written complaint to the jurisdictional cyber-crime police station; ask for an FIR (BNS cheating/personation provisions, IT Act s.66C/66D – **[prior knowledge]**).
4. Inform Apollo's legal/corporate communications team – in the Trehan matters the hospital was complainant/co-plaintiff, which brought trademark grounds and resources.
5. Public notice within hours: pinned post + website banner – "A fake video using my face/voice is circulating. I do not endorse any product. Official channels: …".
6. If it recurs or spreads: civil suit for a John Doe injunction (Trehan order as template) through the hospital's lawyers; GAC appeal for non-responsive platforms.
7. Log everything; re-search weekly for a month (fakes reappear).

**6.4 Crisis playbook for a viral complaint (patient allegation, video of an angry family, hostile news item)**

| Time | Action | Owner |
|---|---|---|
| 0–2 h | Do not reply publicly. Capture evidence. Inform hospital medical superintendent, patient relations, legal and corp-comms. Friend freezes all scheduled posts. | Doctor + friend |
| 2–24 h | Establish facts from records with the hospital. Decide spokesperson (normally the hospital, not him). If a response is needed: one holding statement – concern for the patient/family, confidentiality prevents discussing details, matter being reviewed, contact channel. No clinical details, no blame, no deleting comments except abuse/doxxing. | Hospital comms + doctor |
| Day 1–3 | Direct, private outreach to the family through patient relations. Inform professional indemnity insurer. Prepare a factual chronology in case of council/consumer complaint. | Hospital + doctor |
| Day 3–14 | Correct factual errors with journalists in writing, on record. Report policy-violating posts (doxxing, threats). Do not seed counter-reviews or ask colleagues/patients to post support (cl. 8.1(xi), (xii)). | Friend supports |
| After | Post-incident review; update FAQ/education content if a genuine information gap caused the grievance; resume normal posting quietly. | All |

Rules: confidentiality survives even when the patient goes public; never litigate in comment threads; speed of private contact matters more than the public statement; anything he posts is discoverable.

---

### 7. Email / CRM basics

**7.1 DPDP Act and Rules.** Commencement is phased: provisions establishing the Data Protection Board took effect 13 Nov 2025; consent-manager provisions 13 Nov 2026; "all remaining provisions" (notice, consent, security, rights) **13 May 2027** (https://en.wikipedia.org/wiki/Digital_Personal_Data_Protection_Act,_2023 – tertiary source; official MeitY/PIB pages returned 403). Medium-High. NMC cl. 7.6 already ties medical advertising data use to the DPDP Act and "Rules made thereunder in 2025". Build to the 2027 standard now:
- Separate, unbundled, opt-in consent with a plain notice: what data (email, name, language preference), purpose (heart-health newsletter), how to withdraw, grievance contact. Offer the notice in Telugu too.
- Double opt-in; store timestamp and form version; one-click unsubscribe; delete on withdrawal.
- Collect the minimum: email + language. No age, condition, phone, or "what is your health concern" fields.
- **Never** load hospital patient contact data into a personal newsletter or WhatsApp list: the hospital is the data fiduciary, the purpose is different, and it would also look like solicitation (cl. 8.1(ii)).
- Penalties under the Act run to ₹250 crore (**[prior knowledge]**).

**7.2 Newsletter mechanics.** Sign-up on website and in video descriptions only (not at the OPD desk). Fortnightly, bilingual or two lists. Content: one question answered, one myth, one study explained, upcoming public talks. Footer: name, qualifications, registration number, disclaimer, unsubscribe. Tool: any mainstream newsletter service with double opt-in and export; free tiers suffice below ~1,000 subscribers (**[prior knowledge – not re-verified]**).

**7.3 WhatsApp.**
- Policy (last updated 23 Sep 2026): contact only with "opt-in permission from the recipient"; honour all opt-outs; "Don't use WhatsApp for telemedicine or to send or request any health related information" where regulations bar sharing such data with systems lacking heightened safeguards; drugs and "Medical and healthcare products" are prohibited commerce categories (https://whatsappbusiness.com/policy/). High.
- Pricing: per delivered template message since 1 Jul 2025 (marketing / utility / authentication); India marketing rate rose 1 Jan 2026; from 1 Oct 2026 service messages beyond 1,000 free per number per month are charged and utility messages inside the service window are no longer free; India billing moving to INR by 31 Dec 2026 (https://developers.facebook.com/docs/whatsapp/pricing). High.
- NMC lists WhatsApp/Telegram as advertising media (cl. 3.5).
- Recommendation: **do not build a WhatsApp Business API programme.** Use a one-way **WhatsApp Channel** for public education (followers' numbers are not exposed to the admin; no patient data; no per-message cost – **[prior knowledge – not re-verified]**). Appointment reminders, reports and tele-consults stay on the hospital's systems. He should not give clinical advice over personal WhatsApp to the public.

**7.4 Patient-education drip.** Topic-based, self-selected sequences (e.g., "8 weeks after a stent", "BP at home in 6 emails"), triggered by the subscriber choosing a topic – not by the hospital's knowledge of their procedure. General education only; each mail ends with "this is not personal medical advice".

**7.5 Referral-doctor relationship tracking.** A simple sheet or Airtable/Notion base: doctor, specialty, clinic/area, how met, last contact, last case discussed (no patient identifiers), feedback letter sent (Y/N), CME invitations, notes. Habits that build referrals ethically: same-day call for emergencies, a discharge/feedback letter back to the referring doctor for every patient, quarterly small-group CME/ECG teaching for GPs in Nallagandla–Lingampally–Kokapet–Narsingi. Absolute bar on commissions, gifts or "lead-generation fee" (cl. 8.1(vii)); the CRM tracks relationships and teaching, not payments.

---

### 8. Measurement

**8.1 KPI tree**

North star: **people reached with accurate heart-health education, and trust earned** (not patient volume – which is the hospital's metric and an NMC-sensitive one).

| Branch | Leading indicators (weekly/monthly) | Lagging indicators (quarterly) | Source |
|---|---|---|---|
| Findability (identity) | Listings audited/corrected (% of canonical record matched); GBP completeness; pages indexed; schema valid | Branded search impressions and CTR; name query shows correct panel/profile; AI assistants describe him correctly (monthly prompt test, score 0–3 per assistant) | Audit sheet; Search Console; GBP |
| Education reach | Articles/FAQs published (EN/TE); videos published; newsletter issues sent | Non-branded impressions/clicks; Telugu vs English split; video watch-hours; newsletter subscribers and open rate; AI citations observed | Search Console; YouTube Studio; ESP |
| Local presence | GBP profile views, "searches" terms | GBP calls, direction requests, website clicks, booking-link clicks | GBP Performance |
| Reputation (observed, not driven) | Review response time; % reviews answered | Review count, average rating, recency of latest review – **monitor only, no targets, no solicitation** | GBP |
| Authority (peers/media) | Abstracts/papers submitted; talks proposed; journalist responses | Publications, citations, h-index; invited talks; media mentions; society roles; guideline/committee work | Scholar/ORCID; log |
| Referral network | GP contacts made; feedback letters sent; CMEs held | Number of distinct referring doctors (count kept by him/hospital; no identifiers in the PR system) | CRM sheet |
| Community impact | Camps/CPR sessions/school or corporate talks scheduled | People trained in CPR; people screened; attendees | Event log |
| Risk & compliance | Monthly monitoring sweep done; content pieces doctor-approved (100%); posts carrying registration number (100%) | Impersonation incidents and time-to-takedown; complaints; zero regulator notices | Log |

Dashboard: one Google Sheet (or Looker Studio fed by Search Console + GBP + YouTube), one tab per branch, updated monthly by the friend in ~45 minutes; a one-page quarterly review with the doctor (30 minutes).

**8.2 Year-1 quarterly targets (start-from-near-zero; my estimates – Low/Medium confidence, to be recalibrated after the first 60 days of data)**

| Metric | Q1 (foundation) | Q2 | Q3 | Q4 |
|---|---|---|---|---|
| Canonical record + listings corrected | 100% of Tier 1, 60% of Tier 2 | 100% Tier 1–2 | maintain | maintain |
| Website | Live: About, Consult, Official channels, policies, 10 FAQs EN + 5 TE | 30 EN / 15 TE pieces | 55 EN / 30 TE | 80–100 EN / 45–50 TE |
| Handles/domains secured | 100% | – | – | – |
| Branded impressions (Search Console, monthly) | baseline | +25% vs baseline | +50% | +100% |
| Non-branded impressions (monthly) | <1,000 | 3,000–8,000 | 10,000–25,000 | 25,000–60,000 |
| GBP interactions (calls + directions + clicks) | baseline | track | +15–25% vs baseline | +30–50% |
| Reviews | monitor; 100% replied within 7 days | same | same | same |
| YouTube (if run) | 6 videos | 18 | 30 | 45; first Telugu video past 10,000 views is a reasonable hope, not a plan |
| Newsletter subscribers | 50 | 200 | 400 | 750–1,000 |
| AI-assistant accuracy test (3 assistants × 3 points) | baseline (expect errors: city, experience) | ≥6/9 | ≥7/9 | ≥8/9 |
| Media mentions / bylined pieces | 0–1 | 2 | 3–4 | 4–6 |
| Public talks / CMEs | 1 | 2 | 3 | 3–4 |
| Scholarly output | ORCID + Scholar live; 1 submission in progress | 1 submitted | 1 accepted or presented | 2 cumulative |
| Community (people CPR-trained/screened) | plan | 100 | 300 | 500+ |
| Compliance | 100% posts with reg. no.; 0 testimonials | same | same | same |

Leading vs lagging: output and hygiene metrics (pieces published, listings fixed, sweeps done) should be judged monthly; impressions and subscribers lag by 2–4 months; authority metrics (citations, invitations, knowledge panel) lag by 6–18 months. Do not judge the programme on lagging metrics before month 6.

---

## So what for Dr. Avinash

Prioritised. Effort shown as doctor time (D) and friend/operator time (F).

**Week 1–2: decisions and hygiene (cannot be delegated)**
1. **Decide the canonical name** from his registration certificate; confirm registration council/number and that registration is current for practice in Telangana. D: 30 min.
2. **Approve the canonical record** (bio 50/150/400 words EN + TE, degrees/years, locations, hours, headshot). F: 3 h draft; D: 45 min review.
3. **Adopt the house rules in writing**: education not marketing; no review solicitation or sharing; no superlatives; no patient stories; registration number on everything; doctor approves every piece; AI assistance disclosed. D: 20 min.
4. **Written heads-up to Apollo** (unit head + marketing/corp-comms) about a personal educational website and channels; ask for their consultant communication policy and for profile corrections. D: 30 min.

**Week 2–4: secure and correct**
5. **Register domains and handles** on accounts he owns, with 2FA. F: 3 h; cost ~₹3,000–5,000/yr.
6. **GBP audit**: find all listings, get primary ownership, fix category/hours/pin/links, remove duplicates. F: 3 h + D: 15 min for verification.
7. **Listings clean-up** in order: Apollo/Apollo 24|7 → Citizens → Practo → Eka (wrong city) → Justdial → Vaidam (wrong hospital, promotional adjectives) → others. F: 4–6 h spread over a month; keep the request log.
8. **ORCID + Google Scholar + LinkedIn** with canonical name; verify the NEJM trial contribution on PubMed and list it accurately. F: 2 h; D: 20 min.
9. **Carrd-style one-page placeholder** on the canonical domain: who he is, registration number, where he consults, official channels, no-endorsement statement. F: 2 h; US$19/yr.

**Month 2–3: build the entity home**
10. **Launch the bilingual site** (pages in §1.2, schema in §1.4, hreflang, Search Console verified). F: 20–30 h or freelancer; D: 3 h total review. Running cost ₹1,500–35,000/yr by stack.
11. **Private feedback loop** with the hospital's patient-relations team instead of review asks. D: one conversation.
12. **Deepfake takedown kit** and "official channels" page. F: 2 h.

**Ongoing (steady state)**
13. **Content cadence**: 2 FAQs/week (one EN, one TE), each reusable as a short video script. D: 45–60 min/week (voice-note answers + approval); F: 3–4 h/week.
14. **Review replies**: neutral template, within 7 days. F drafts, D approves: 10 min/week.
15. **Monthly sweep + dashboard**: monitoring, AI-assistant test, metrics. F: 60–75 min/month.
16. **Quarterly**: NAP re-audit (30 min), targets review with the doctor (30 min), compliance re-read of the NMC guidelines against the last quarter's output (30 min).

**Later (month 6+)**
17. Wikidata item (by someone other than him, fully referenced) once ORCID/publications/third-party mentions exist.
18. Reassess paid monitoring only if media presence or incidents justify it.
19. Wikipedia: not before sustained independent coverage; never self-authored.

---

## Risks & things to avoid

| Risk | Why it matters | Mitigation |
|---|---|---|
| The programme itself is read as "self-promotion" or "engaging a third party for marketing" (cl. 8.1(ii)) | Licence exposure; graded penalties up to removal | Frame, document and run it as public education and factual identity; friend unpaid or paid a flat fee unrelated to patients; no patient-acquisition KPIs anywhere; doctor signs off everything |
| Soliciting or reposting Google reviews | Expl. V; vendors and hospitals will keep suggesting it | Written rule: none. Tell hospital marketing not to run review asks in his name |
| "Best cardiologist in…" pages, titles, GBP name stuffing | cl. 8.1(ix), 8.1(xii); Google name policy; suspension risk | Never. Rank via factual pages and education |
| Procedure counts, success rates, awards walls | cl. 8.1(iii), proviso to 8.1(ix) | Omit or state only verifiable, dated facts |
| Patient stories, photos, angiogram clips, WhatsApp screenshots | cl. 6.2, 7.4; confidentiality; DPDP | Never for public channels; anonymised cases only in journals/CME |
| AI-generated content at scale | cl. 7.2; Google spam policy on automation used to manipulate rankings; hallucinated medical facts under his name | AI drafts from his own voice notes; he reviews every line; references checked; disclose assistance; no AI avatars/voice clones of him (also trains the public to trust fakes) |
| Paid rank on Practo/Justdial, lead-gen fees, "per appointment" agency deals | cl. 8.1(vii), (viii), 9.4 | Free factual listings only |
| Google Ads for his name/services | Sponsored, search-engine promotion is advertising (cl. 3.2) | Do not run ads; if ever considered for public-health campaigns, get written legal advice first |
| Accounts owned by the friend, an agency or the hospital | Loss of control on dispute or job change | He is primary owner everywhere; others are managers |
| Hospital contract breach (brand use, exclusivity, media statements) | Employment risk | Read the agreement; get written no-objection; no logos/footage |
| Duplicate GBP listings / wrong hours | Suspension; filtered listings; patients arriving when he is absent | Audit; one listing per real location; real OPD hours |
| Wikipedia self-creation | Deletion, permanent public record, reputational cost | Do not |
| Collecting health data via forms/WhatsApp | DPDP, WhatsApp policy, confidentiality | Email + language only; clinical communication stays in hospital systems |
| Engaging publicly with a complaint | Confidentiality breach; amplification | Playbook in §6.4 |
| Monetised content (sponsored posts, affiliate links, supplement tie-ups) | cl. 5.1 "not monetized through promotional marketing"; 8.1(iv) | None. Whether platform ad-revenue (YouTube AdSense) counts is unclear – keep monetisation off until clarified |
| Over-reliance on vendor interpretations of the new NMC text | Many current explainers are written by companies selling listings/compliance | Use the primary PDF; get one written opinion from a medico-legal lawyer on reviews, website and third-party support |

---

## Open questions / gaps

1. **Live state of his Google presence**: which listing(s) hold his reviews, who owns them, name/category/hours, duplicates. Not checkable without Maps access. This is the first thing to verify.
2. **Apollo's consultant policy** on personal websites, media, social accounts and brand use; and whether Citizens (Nallagandla) and the Narsingi clinic are current affiliations. Could not verify.
3. **How State Medical Councils (Telangana in particular) will read Expl. V and cl. 8.1(ii)** – especially passive review signage, personal websites with a headshot, YouTube ad revenue, and unpaid help from a friend. No enforcement record yet; a medico-legal opinion is warranted. Also confirm his registration position (Eka shows Andhra Pradesh Medical Council no. 74749; Telangana requirements not verified).
4. **Search demand data**: no volumes for English or Telugu heart-health queries in Hyderabad; no SERP/competitor review (who ranks for "cardiologist Gachibowli/Financial District", which doctors appear in AI answers); no check for namesakes. Needs Keyword Planner/Trends/Search Console work and live SERP sampling.
5. **Hyderabad/Telugu-specific deepfake and fake-doctor-ad cases**, Telangana cyber-crime reporting specifics, and the gazette text of the Feb 2026 IT Rules amendment (three-hour trigger conditions). Only national cases were documented here.
6. Not verified this session: presence on Practo/Justdial/Lybrate/Credihealth/MediBuddy/Bajaj Finserv Health; domain availability; Webflow pricing; current GBP Q&A status in India; DPDP Rules text (Rule 3 notice contents); IMC 2002 reg 2.2/7.14 wording (server error); WhatsApp Channels admin-privacy behaviour; static-host free-tier terms; India-specific AI-citation studies (the SE Ranking dataset is German).
7. Sites that failed to load and would need allow-listing or manual checking: apollohospitals.com doctor page (403), pib.gov.in and meity.gov.in (403), hpr.abdm.gov.in (403), delhimedicalcouncil.org (503), cybercrime.gov.in (503), bmj.com (403), sterlingsky.ca (empty), multiplierai.co (bot wall); `dravinashpaturi.com`, `drpathuriavinash.com` did not resolve.

---

## Sources

**Regulatory – India**
- NMC, Public Notice No. R-13014/01/2024-Ethics, 6 Oct 2026, Guidelines on Ethical Advertising and Public Communication (primary PDF): https://nmc.org.in/whats-new/download/1874
- Medical Dialogues, NMC issues ethical advertising guidelines (7 Oct 2026): https://medicaldialogues.in/health-news/nmc/nmc-issues-ethical-advertising-public-communication-guidelines-for-doctors-hospitals-details-180731
- The South First (7 Oct 2026): https://thesouthfirst.com/health/doctors-on-instagram-nmc-says-no-to-patient-testimonials-paid-ads-ai-promotions-and-guaranteed-claims/
- The Policy Edge (10 Oct 2026): https://www.policyedge.in/p/nmc-restricts-misleading-medical-ads-paid-rankings-and-ai-generated-testimonials
- Doctopath explainer (13 Oct 2026, vendor): https://www.doctopath.com/blog/nmc-advertising-guidelines-2026-for-doctors
- MedHive on patient feedback under the guidelines (27 Oct 2026, vendor): https://medhive.in/blog/ethical-patient-feedback-nmc-guidelines
- Asian Pain Academy commentary (Oct 2026): https://www.asianpainacademy.com/post/nmc-medical-advertising-guidelines-2026-what-pain-physicians-need-to-know
- Status of 2023/2002 regulations: https://gauravphogat.com/glossary/nmc-professional-conduct-regulations/
- NMC puts 2023 regulations on hold (Aug 2023): https://medicaldialogues.in/health-news/nmc/breaking-news-nmc-puts-its-controversial-registered-medical-practitioner-professional-conduct-regulations-2023-put-on-hold-116314
- NMC 2023 social-media points (part of the regulations now in abeyance; older): https://medicaldialogues.in/health-news/nmc/how-to-behave-on-social-media-nmc-releases-11-commandments-for-doctors-115773
- Maharashtra Medical Council RTI on Justdial/Practo listings (2019; stale): https://medicaldialogues.in/doctors-cannot-list-with-online-platforms-like-justdial-or-practo-medical-council-gives-rti-response
- IMC Regulations 2002 (not retrievable this session): https://www.delhimedicalcouncil.org/pdf/EthicsRegulations-2002.pdf ; https://www.nmc.org.in/rules-regulations/code-of-medical-ethics-regulations-2002/
- DPDP Act commencement dates (tertiary): https://en.wikipedia.org/wiki/Digital_Personal_Data_Protection_Act,_2023
- IT Rules synthetic-media amendment, Feb 2026 (secondary): https://www.medianama.com/2026/08/223-x-compliance-reports-synthetic-media-rules/
- Personality-rights/deepfake orders index: https://www.medianama.com/tag/deepfakes/
- Grievance Appellate Committee: https://gac.gov.in/

**Deepfake cases**
- https://medicaldialogues.in/news/health/doctors/menace-of-medical-deepfakes-attacking-indias-top-doctors-dr-naresh-trehan-becomes-the-latest-victim-126080
- https://medicaldialogues.in/news/health/doctors/remove-deepfake-videos-featuring-medanta-chief-dr-naresh-trehan-delhi-hc-141329
- https://medicaldialogues.in/mdtv/healthshorts/delhi-hc-orders-removal-of-deepfake-videos-featuring-medanta-chief-dr-naresh-trehan-141380
- https://medicaldialogues.in/news/health/doctors/2-karad-women-doctors-targeted-in-ai-generated-obscene-video-149923
- Index page used: https://medicaldialogues.in/tags/deepfake-video

**Google – policies and documentation**
- Business Profile guidelines (practitioners, names, categories): https://support.google.com/business/answer/3038177
- Maps user-contributed content policy (fake engagement, gating, incentives): https://support.google.com/contributionpolicy/answer/7400114
- Tips to get more reviews (link/QR): https://support.google.com/business/answer/3474122
- Report/remove reviews, appeals: https://support.google.com/business/answer/4596773
- Local business links (booking): https://support.google.com/business/answer/6218037
- Business Profile API change log: https://developers.google.com/my-business/content/change-log
- Knowledge panels – about: https://support.google.com/knowledgepanel/answer/9163198
- Knowledge panels – get verified: https://support.google.com/knowledgepanel/answer/7534902
- AI features and your website: https://developers.google.com/search/docs/appearance/ai-features
- FAQPage structured data (deprecation notice): https://developers.google.com/search/docs/appearance/structured-data/faqpage
- ProfilePage structured data: https://developers.google.com/search/docs/appearance/structured-data/profile-page
- Localized versions / hreflang: https://developers.google.com/search/docs/specialty/international/localized-versions
- Creating helpful content (E-E-A-T, YMYL): https://developers.google.com/search/docs/fundamentals/creating-helpful-content
- Core Web Vitals: https://developers.google.com/search/docs/appearance/core-web-vitals

**Schema, entity, AI crawlers**
- https://schema.org/Physician
- https://www.wikidata.org/wiki/Wikidata:Notability
- https://en.wikipedia.org/wiki/Wikipedia:Notability_(academics)
- https://llmstxt.org/
- https://developers.openai.com/api/docs/bots
- https://docs.perplexity.ai/guides/bots
- https://support.claude.com/en/articles/8896518-does-anthropic-crawl-data-from-the-web-and-how-can-site-owners-block-the-crawler

**Local SEO / AI visibility studies**
- Whitespark 2026 Local Search Ranking Factors (6 Nov 2025): https://whitespark.ca/local-search-ranking-factors/
- BrightLocal Local Consumer Review Survey 2026: https://www.brightlocal.com/research/local-consumer-review-survey/
- Ahrefs, 76% of AI Overview citations from top 10 (Jul 2025): https://ahrefs.com/blog/search-rankings-ai-citations/
- Ahrefs, 12% overlap for AI assistants (Aug 2025): https://ahrefs.com/blog/ai-search-overlap/
- SE Ranking, health AI Overviews and YouTube (Jan 2026): https://seranking.com/blog/health-ai-overviews-youtube-vs-medical-sites/
- V Digital Services, practitioner listings (2018, updated 2026): https://www.vdigitalservices.com/best-practices-for-managing-gbp-practitioner-listings

**Dr. Avinash's existing listings**
- https://www.apollohospitals.com/doctors/interventional-cardiologist/hyderabad/dr-pathuri-avinash (403 to fetcher; details from search snippet)
- https://www.apollo247.com/doctors/dr-pathuri-avinash-07916af1-e7a6-4fed-b830-061c4924ffb3
- https://www.citizenshospitals.com/doctor/dr-pathuri-avinash
- https://www.vaidam.com/doctor/dr-pathuri-avinash
- https://www.eka.care/doctor/dr-pathuri-avinash-cardiologist-rajahmundry

**Platforms, messaging, tools, pricing**
- Practo profile for doctors: https://www.practo.com/providers/doctors/profile
- WhatsApp Business Messaging Policy (updated 23 Sep 2026): https://whatsappbusiness.com/policy/
- WhatsApp Business Platform pricing: https://developers.facebook.com/docs/whatsapp/pricing
- Framer pricing: https://www.framer.com/pricing
- Carrd Pro: https://carrd.com/pro
- Hostinger India pricing: https://www.hostinger.com/in/pricing
- Brand24 pricing: https://brand24.com/prices/
- Mention pricing: https://mention.com/en/pricing/
