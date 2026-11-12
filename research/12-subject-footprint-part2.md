# Footprint audit, part 2 — closing the gaps on Dr. Pathuri Avinash / Avinash Pathuri / Avinash Paturi (12 Nov 2026)

**Executive summary**

1. **Credentials are now verified at source.** The NMC Indian Medical Register shows one record: "PATHURI AVINASH", **APMC/FMR/74749**, registered 25 May 2012, Andhra Pradesh Medical Council; MBBS 2012 (Dr. NTR University of Health Sciences), **MD General Medicine 2016 (Manipal Academy of Higher Education)**, **DM Cardiology 2020 (West Bengal University of Health Sciences, Kolkata)**. "West Bengal State University" on Practo and Eka is wrong. No Telangana registration is visible.
2. **He already has one owned channel:** a YouTube channel **"Dr. Avinash Pathuri | Preventive Heart Care" (@dravinashpathuri)** exists, with a bio and **zero videos**. No other social profile, video, interview, news item or Telugu-script mention was found.
3. **Google reviews could not be read from this environment** (Maps/Search need a browser; no review mirror exists). Every other "rating" under his name is a template (Apollo 5/5 with placeholder text, Apollo Clinic 95% and 4.5, Apollo 24|7 boilerplate). His patient voice lives only on Google. A 30-minute manual capture is still needed.
4. **Affiliation picture:** Apollo Hospitals Financial District (primary) plus Apollo Clinic Narsingi (evening OPD) are current. **Citizens has dropped him from its live site**, but a stale Google snippet and Apollo's own "Feb 2024–Present" line still say otherwise. Rajahmundry (Eka, DocIndia, Practo URL), Jubilee Hills (Vaidam) and Manipal (Curofy) are stale.
5. **The 2021 IJSR paper is his** (byline "Dr. Avinash Paturi, MBBS, MD (Gen Med), DM (Cardio)"; Apollo lists it), and **IPGMER & SSKM Kolkata was a PROMINENT trial site**, which supports the NEJM investigator listing. Recommended canonical public name: **"Dr. Avinash Pathuri"** — it matches the register surname, his YouTube handle, his first paper, and all name domains are free.

---

## Findings

### 0. Method and limits

- **Searches used: 13** (budget was about 12). Everything else came from about 60 direct fetches and public API calls: NMC register search, PubMed E-utilities, ClinicalTrials.gov API, RDAP and DNS-over-HTTPS for domains, YouTube public pages, IJSR PDF.
- **Not readable from this session** (so "not found" below is not "absent"):
  - Google Maps, Google Search and Google Scholar (JavaScript wall or captcha).
  - `apollohospitals.com` profile (HTTP 403). Its content below comes from the search tool's own reading of the page, labelled "(via search tool)".
  - LinkedIn (999/429), Instagram (login wall, 429), X (402), Facebook (login redirect), Justdial (403).
  - `web.archive.org` (blocked; a 11 Oct 2025 snapshot of the Citizens profile exists but could not be opened).
  - `curofy.com` (host not in this session's allowed network list).
  - Telangana Medical Council doctor search (`regonlinetsmc.in`): the council's home page says the portal "is down because of some technical issues".
- No form was submitted, no account created, nobody contacted. The NMC register lookup is a public read-only search.
- The NMC record also displays date of birth, father's name and a partial home address. These are deliberately **not reproduced** here.
- Confidence: High = read on the primary page or database; Medium = search-tool summary, snippet or single aggregator; Low = inference.

### 1. Google Business Profile and patient-review themes

**Result: could not verify.** No rating, review count, number of listings or review text was obtainable.

| Source | What it shows | Is it real patient feedback about him? | Confidence |
|---|---|---|---|
| Google Maps / GBP | Not readable. A domain-restricted search for a `business.google.com` page in his name returned nothing; such pages do exist for peers (see below). | Unknown | — |
| Apollo Hospitals profile | Structured data: rating 5/5, count 10; the three review texts are "Patient review 1…" placeholders (via search tool). | **No — template** | Medium |
| Apollo Clinic profile | "95% patient satisfactory score"; three short excerpts about clinic service (reports on time, "fast services", "supportive" staff). | **No — clinic-level** | High |
| Apollo Clinic Narsingi locator | "4.5 Rating" beside all three cardiologists listed. | **No — template** | High |
| Apollo 24\|7 | "Most patients recommend…" boilerplate; no count. | No | Medium |
| Practo | Claimed profile; **no recommendation %, no patient stories, no feedback tags**. | None exists | High |
| Justdial, Lybrate, Sehat, Credihealth, MediBuddy, Hexahealth, Bajaj Finserv Health, Drlogy, Skedoc | One dedicated search returned **no listing on any of them**. Justdial blocked direct fetch. | — | Medium (absence) |

- **Implication:** outside Google there is no patient-written text about him anywhere on the open web. The claim "strong Google reviews" rests entirely on the brief.
- **Peer benchmark (what a practitioner listing looks like).** Two Hyderabad cardiologists' Google profile pages surfaced by accident: 4.9 from 238 reviews and 5.0 from 116 reviews. Anonymised phrases: "extremely calm, highly patient, and takes the time to listen"; "immediate crisis response… saved my father's life". One critical review complained of no physical examination and queue-jumping. These are the theme families to look for in his own reviews. (High, pages read.)
- **Still to do by hand** — see action 1 below for the capture protocol.

### 2. Social profiles and video

| Platform | Finding | Confidence |
|---|---|---|
| **YouTube (own)** | **Channel exists.** Title "Dr. Avinash Pathuri \| Preventive Heart Care", handle **@dravinashpathuri**, channel ID `UC1fZpfwNZAMOc_tDJC1KdeQ`. Has avatar and banner. Description: "Interventional Cardiologist with over a decade of experience in managing cardiac conditions, currently practicing at Apollo Hospitals, Financial District, Hyderabad. This channel focuses on heart health awareness, preventive cardiology, and simplifying complex cardiac conditions through evidence-based insights…". Home, Videos and Shorts tabs all say "This channel doesn't have any content". No subscriber count shown; RSS feed returns 404 (no uploads). Creation date not visible. | High that it exists and is empty; Medium–High that it is his (matches name, hospital, specialty) |
| YouTube (others' channels) | Exact-name searches ("Pathuri Avinash", "Avinash Pathuri" cardiologist) returned **no video**. Broader queries returned Apollo Hyderabad videos of other doctors only. Telugu-script query returned other cardiologists. | Medium (absence) |
| LinkedIn | No profile surfaced. The only "Avinash Pathuri" LinkedIn result is a **UBS employee in Hyderabad** (namesake). One search summary mentioned "an Apollo Hyderabad LinkedIn post features him explaining heart risk tests"; a follow-up search could not find it. **Unverified — ask him or Apollo marketing.** | Low |
| Instagram, X, Facebook, Threads | Not determinable (login walls). No profile surfaced in any search. | Low (absence) |
| Curofy (doctors' network) | Snippet: "Dr. Avinash Pathuri, Manipal", internal medicine, MBBS Rangaraya; URL slug ends `dravinashpathuri`. A stale profile from his MD/senior-resident years. Page not reachable. | Medium |
| Telugu TV / YouTube interviews | None found. | Medium (absence) |

- **Local contrast:** an Apollo Hyderabad interventional cardiologist peer appears repeatedly on iDream, SumanTV, TV5 and Vanitha TV in Telugu (long-form, 20–40 min, typically 500–3,000 views each). That is the visible Telugu-video norm he is currently absent from. (High; YouTube results page.)

### 3. News, press, conferences

- **English news:** nothing found in three searches (name + news/interview/health camp; name + hospitals; name + cities).
- **Telugu:** "డాక్టర్ పాతూరి అవినాష్ కార్డియాలజిస్ట్", "అవినాష్ పాతూరి" and "పాతూరి అవినాష్" returned **zero** relevant results. The Telugu-script name is an empty field.
- **Conference programmes / abstracts:** none found for CSI, India Live, TCT, EuroPCR, Indian Heart Journal. He is not in the PCR Online physician directory results. The only presentation on record is the one Apollo lists: "Association between subclinical hypothyroidism and diabetic retinopathy in type 2 diabetic patients — RSSDI, Bengaluru 2014" (via search tool; Medium).
- Confidence in absence: Medium. Search coverage of Telugu newspapers and conference PDFs is poor.

### 4. Current affiliations, timings, stale listings

| Site | Evidence | Status | Confidence |
|---|---|---|---|
| **Apollo Hospitals, Financial District** | Apollo profile, Apollo 24\|7, his own YouTube bio ("currently practicing at…"). Mon–Sat 09:00–17:00 (Apollo listing pages, via search tool). Fee ₹1000. | **Current, primary** | High |
| **Apollo Clinic, Narsingi** (1-85/3, Machirevula Village, Gandipet; 040 6906 3398) | Apollo Clinic profile ("Dr. Avinash Pathuri… 6 Years Experience") and clinic locator ("5 years Exp"); Practo: Mon, Tue, Thu, Fri, Sat "05:00–06:00" (no AM/PM; presumably 5–6 PM), ₹850. No Wednesday. | **Current, secondary** | High |
| **Citizens Specialty Hospital, Nallagandla** | Live profile URL (with and without `www`) now serves only the generic "Our Specialists" page. The cardiology list names three other doctors, not him. Google still shows the old snippet ("over 4 years… currently working"). Apollo work history still says "Feb 2024–Present". | **Probably ended; needs his confirmation** | Medium |
| Kokapet clinic | No listing found under any name. (Narsingi clinic is the nearest match.) | No evidence | Medium |
| Apollo Jubilee Hills | Only on Vaidam's header. No Apollo page places him there. | **Stale / wrong** | Medium–High |
| Rajahmundry | Eka Care (city), DocIndia (dental-clinic address), Practo duplicate URL. He left KIMS Rajahmundry in Sep 2021 per Apollo. | **Stale** | High |
| Manipal | Curofy snippet. | **Stale** | Medium |

**New work-history details from the Apollo profile (via search tool, Medium):**
- Junior Consultant, ICU, Basavatarakam Indo-American Cancer Hospital, Hyderabad (2016–2017).
- KIMS Hospital, Rajahmundry: Oct 2020 – Sep 2021.
- Ramesh Hospitals, Vijayawada: Oct 2021 – Feb 2024.
- Citizens: Feb 2024 – "Present".
- Teaching posts at KMC Manipal and Apollo Institute of Medical Sciences (dates not given).
- The JCDR 2018 paper gives "Senior Resident, General Medicine, KMC Manipal". Whether the 2016–17 year was Manipal, Basavatarakam or both needs his answer.

### 5. Credentials — verified against the NMC Indian Medical Register

Public search at `nmc.org.in/information-desk/indian-medical-register`, by registration number and by name. **High confidence.**

| Field | NMC register value |
|---|---|
| Name | PATHURI AVINASH |
| Registration no. | **APMC/FMR/74749** |
| Date of registration | 25 May 2012 |
| Council | Andhra Pradesh Medical Council |
| Qualification | M.B.B.S, 2012, Dr. NTR University of Health Sciences, Vijayawada |
| Additional qualification 1 | MD – General Medicine, 2016, Manipal Academy of Higher Education |
| Additional qualification 2 | DM – Cardiology, 2020, West Bengal University of Health Sciences, Kolkata |
| Removed status | none |

- Name searches for "AVINASH PATHURI", "PATURI AVINASH" and "AVINASH PATURI" return **0 records**. Only the exact register form "PATHURI AVINASH" finds him. Anyone checking a post signed "Avinash Paturi" against the register will find nothing.
- **Both postgraduate degrees are entered as additional qualifications.** This closes Round 1's open question.
- "74749" alone matches 12 doctors across councils. The number must always be written with the council: "APMC/FMR/74749".
- **Telangana registration:** the NMC register shows no Telangana record for him, and the council's own search portal was down. **Could not verify either way.** He should confirm whether he holds, or needs, a Telangana Medical Council registration for practice in Hyderabad (see the regulation file for the rule).
- **Memberships (CSI and others):** none listed on any profile; no public member directory checked. Could not verify.
- **Awards:** Apollo lists only student quiz results (for example "2nd place in quiz – World TB Day 2014, KMC Manipal") (via search tool). Vaidam's "Global Clinical Trial Contributor (2022)" has no other trace.

### 6. Publications

| Item | Finding | Confidence |
|---|---|---|
| **IJSR 2021 — settled: it is his.** | "Hypoalbuminemia Secondary to Strongyloides Hyper Infection – An Often Missed Entity", *Int J Sci Res* 10(2), Feb 2021, DOI 10.21275/SR21122214401. PDF byline: "Dr. Avinash Paturi¹… ¹MBBS, MD (Gen Med), DM (Cardio)". That qualification set fits him and not the St. George's namesake; Apollo's profile lists the same paper. No institution is printed. | High–Medium |
| Caveat on IJSR | IJSR is, to my knowledge, a pay-to-publish journal of low standing that has appeared on predatory-journal watchlists. Not sourced here; verify before featuring it. List it accurately; do not lead with it. | Low–Medium |
| **JCDR 2018** | Unchanged from part 1: first author as "Avinash Pathuri". | High |
| **PROMINENT (NEJM 2022)** | ClinicalTrials.gov (NCT03071692) lists **"IPGMER and SSKM Hospital, Kolkata"** among 31 Indian sites. Combined with his 2017–2020 DM there and the Kolkata names beside his in the PubMed investigator list, the listing is very likely him. `Pathuri A[Investigator]` returns exactly this one record. Correct wording remains "site investigator, listed among the PROMINENT Investigators" — not author. | High that the site took part; Medium–High that the entry is him |
| RSSDI 2014 | Conference presentation on subclinical hypothyroidism and diabetic retinopathy (Apollo profile). Not found in Crossref. | Medium |
| PubMed, all variants | `Avinash Pathuri`, `Pathuri Avinash`, `Avinash Paturi` as full author name: 0. `Avinash P` with IPGMER/SSKM or Manipal affiliation: 0. | High |
| Cardiology conference abstracts | None found. | Medium |
| Google Scholar | Captcha; not audited. No Scholar profile for him appeared in a Google-domain search. | Low |
| DM thesis | Not found. | — |

**New scholarly collisions found:**
- **"Paturi A"** — a US cardiology author (J Invasive Cardiol 2009, late stent thrombosis; J Atr Fibrillation 2011, statins after CABG). Same field, same initials as the "Paturi" spelling. Risk: High for "Paturi A" in PubMed.
- **"Pathuri S / Pathuri SN"** — co-author in a Hyderabad cardiac-surgery group's papers (2008–2026: off-pump CABG, mitral repair, cardioplegia). Same city, same organ, different initial. Risk: Low–Medium. This is the likely origin of the "Star Hospital" confusion noted in part 1.

### 7. Name availability (read-only checks, 12 Nov 2026)

**Domains** (RDAP registry lookup plus DNS):

| Domain | Status |
|---|---|
| dravinashpathuri.com / .in / .org / .co.in | **Unregistered** |
| avinashpathuri.com / .in / .org / .me | **Unregistered** |
| dravinashpaturi.com / .in, avinashpaturi.com / .in | **Unregistered** |
| drpathuriavinash.com / .in, pathuriavinash.com / .in | **Unregistered** |
| drpathuri.com | Registered 20 Feb 2026 (Hostinger), parked |
| drpathuri.in | Registered 22 Dec 2023 (Hostinger), parked |
| dravinash.com | Registered 2011 (GoDaddy), to 2030 |
| dravinash.in | Registered 4 Nov 2025 (GoDaddy) |
| pathuri.in | Registered; pathuri.com unregistered |

- `drpathuri.com` and `drpathuri.in` sit at the same registrar, both parked. Ask him and the friend whether either is theirs; if not, another Dr. Pathuri is preparing a site.

**Handles:**

| Handle | YouTube | Others |
|---|---|---|
| @dravinashpathuri | **Taken — by his own empty channel** | Instagram, X, Facebook, LinkedIn, Threads: not determinable here |
| @avinashpathuri | Taken — unrelated person ("Avinash Chowdari", 1 video, 12 years old) | LinkedIn `avinash-pathuri-901a73129` is the UBS namesake |
| @avinashpaturi | Taken — "Avinash Paturi", no visible content, identity unknown | — |
| @dravinashpaturi, @drpathuriavinash, @pathuriavinash | Free (404) | — |

The friend should check the same six handles on Instagram, X, LinkedIn, Facebook and Threads in a logged-in browser (10 minutes).

---

## Deliverable A — draft fact sheet (he must confirm every row)

"Proposed" is the value the evidence best supports. Nothing here should be published until he ticks it.

| # | Field | Proposed value | Conflicting values found (source) | Basis |
|---|---|---|---|---|
| 1 | Registered name | PATHURI AVINASH | — | NMC register |
| 2 | Public name (English) | **Dr. Avinash Pathuri** | Dr. Pathuri Avinash (Apollo Hospitals, Apollo 24\|7, Practo, Vaidam, Citizens, Eka, DocIndia) · Dr. Avinash Pathuri (Apollo Clinic, own YouTube, Curofy, JCDR 2018) · Dr. Avinash Paturi (IJSR 2021, project brief) | See Deliverable C |
| 3 | Public name (Telugu) | డా. అవినాష్ పాతూరి — *spelling to be given by him* | None found anywhere | — |
| 4 | Registration | **APMC/FMR/74749**, Andhra Pradesh Medical Council, 25 May 2012 | "74749" (Apollo 24\|7) · "APMC74749" (Apollo) · year 2012 (Practo) vs 2020 (Eka) | NMC register |
| 5 | Telangana registration | *He must state: number, or "not held"* | Not shown on any listing; not in NMC register | Unverified |
| 6 | MBBS | Rangaraya Medical College, Kakinada (Dr. NTR University of Health Sciences); course 2006–2011, degree 2012 | "2006–2011" (Apollo 24\|7) vs "2012" (Practo, Eka, Vaidam, NMC) | NMC + Apollo 24\|7 |
| 7 | MD | General Medicine, Kasturba Medical College, Manipal (Manipal Academy of Higher Education), 2013–2016 | "MD Internal Medicine" (Apollo 24\|7) · **missing** (Practo, Eka, DocIndia) | NMC |
| 8 | DM | Cardiology, IPGMER & SSKM Hospital, Kolkata (**West Bengal University of Health Sciences**), 2017–2020 | "West Bengal State University" (Practo, Eka) | NMC |
| 9 | Designation | Consultant Interventional Cardiologist | "Cardiologist" (Apollo 24\|7, Apollo Clinic, Practo, Eka, DocIndia) · "Internal medicine" (Curofy) | Apollo profile |
| 10 | Primary practice | Apollo Hospitals, Financial District, Hyderabad; Mon–Sat 09:00–17:00; ₹1000 | "Apollo Hospitals, Jubilee Hills" (Vaidam) | Apollo, own YouTube |
| 11 | Second practice | Apollo Clinic, Narsingi (Machirevula Village, Gandipet); Mon, Tue, Thu, Fri, Sat 5–6 PM *(confirm PM and days)*; ₹850; 040 6906 3398 | "05:00–06:00" with no AM/PM (Practo) | Practo, Apollo Clinic |
| 12 | Citizens Specialty Hospital | *He must state end date, or "still visiting"* | "currently working… 4 years" (Google snippet) · "Feb 2024–Present" (Apollo) · not on live Citizens site | Unresolved |
| 13 | Experience statement | "In medicine since 2012; cardiologist since 2020 (DM)" | 4 yrs (Citizens) · 5 (Apollo Clinic locator) · 6 (Apollo Clinic profile, Vaidam) · 6+ (Apollo) · 10 (DocIndia) · 12 or 14 (Eka) · 14 with "2 as specialist" (Practo) · "over a decade… managing cardiac conditions" (own YouTube) | Register dates |
| 14 | Work history | Basavatarakam (Jr Consultant ICU, 2016–17) *and/or* KMC Manipal Senior Resident (2016–17) → DM 2017–20 → KIMS Rajahmundry Oct 2020–Sep 2021 → Ramesh Hospitals Vijayawada Oct 2021–Feb 2024 → Citizens Feb 2024–? → Apollo FD from ? | Basavatarakam (Apollo) vs KMC Manipal Senior Resident (JCDR 2018 byline); Apollo start date appears nowhere | Apollo profile |
| 15 | Teaching posts | KMC Manipal; Apollo Institute of Medical Sciences — *dates and titles needed* | — | Apollo profile |
| 16 | Procedure volumes (with "as of" date) | *He supplies from cath-lab logs* | "1500+ angiographies; 300 PCIs" · "800+ angiographies; 400+ PCIs (200+ STEMI)" (both on Apollo, different entries) · "~2,300 angiographies, 150 STEMI PCIs, 80 devices" (brief). Note 1500 + 800 = 2300: the figures look like per-hospital counts that someone summed. | Unresolved |
| 17 | Clinical scope | Complex PCI (left main, CTO, bifurcation, rotablation/calcium), CHIP, pacemaker and ICD implantation, structural interventions | "assisted TAVI" (Apollo) — keep the word "assisted" unless he is an independent operator | Apollo, Vaidam |
| 18 | Publications | (a) Pathuri A et al., JCDR 2018 · (b) Paturi A et al., IJSR 2021 · (c) RSSDI 2014 presentation · (d) Site investigator, PROMINENT trial, IPGMER & SSKM site (NEJM 2022;387:1923–34) | "co-authored… NEJM" (Vaidam) | Primary records |
| 19 | Awards | None to publish, unless he holds documents | "Global Clinical Trial Contributor (2022)" (Vaidam) · student quiz prizes (Apollo) | — |
| 20 | Memberships | *He supplies (CSI life membership number, others)* | None on any listing | — |
| 21 | Languages | Telugu, English, Hindi, Kannada, Bengali | English only (Eka) | Apollo 24\|7 |
| 22 | Owned channels | YouTube @dravinashpathuri *(confirm who holds the login)* | — | YouTube |
| 23 | Google Business Profile(s) | *URL, name on listing, category, rating, count, owner login* | Not readable | — |
| 24 | Public contact | Hospital appointment lines only | No personal phone or email on any page | — |

## Deliverable B — listing-by-listing correction table

Order = suggested sequence. Factual directory listings are permitted under the Oct 2026 NMC guidelines; "best/top" wording and fabricated ratings are not (see `02-regulation-ethics-india.md`).

| # | Listing | What is wrong | How to get it fixed | Effort |
|---|---|---|---|---|
| 1 | **Practo** (claimed) | MD missing; DM university wrong; "2 years as specialist"; timing lacks AM/PM; no services; only Narsingi shown; duplicate `/rajahmundry/` URL and Rajahmundry image text | Self-serve: log in to his Practo doctor account, edit education (degree certificates may be requested), add Apollo FD as a practice, add services. Raise a support ticket for the duplicate URL. | 30–40 min |
| 2 | **Apollo Hospitals profile** | Citizens "Present"; two different volume sets; no Apollo start date; rating markup 5/5 from 10 with placeholder review text | One email to the unit's marketing/digital lead with the fact sheet attached. Ask specifically for the placeholder review markup to be removed. | 30 min + follow-up |
| 3 | **Apollo 24\|7** | No bio; "Cardiologist" label; broken FAQ text; registration shown without council | Same email as row 2 (ask them to forward to the 24\|7 doctor-onboarding team). | — |
| 4 | **Apollo Clinic** profile and Narsingi locator | Page title "Best Cardiologist in Narsingi"; name order differs from Apollo Hospitals; "6 years" on one page and "5 years" on the other; "4.5 Rating" template; no bio, timings or registration | Through the Narsingi clinic manager to Apollo Health & Lifestyle's web team. Ask for the "Best" wording to be dropped from the page that carries his name. | 20 min |
| 5 | **Citizens Hospitals** | Profile body gone but URL and Google snippet persist ("currently working… 4 years") | If he has left: ask Citizens marketing to return a proper 404/redirect, then use Google's public "Refresh outdated content" tool on the URL. If he still visits: ask them to restore and update the page. | 15 min |
| 6 | **Vaidam** | Header hospital Jubilee Hills; "6 years overall"; "co-authored" NEJM; unsupported award; unrelated "case study" | Email Vaidam's listing team, or ask Apollo's international-patient desk, which normally supplies these profiles. Contact route not verified. | 20 min |
| 7 | **Eka Care** | City Rajahmundry; MD missing; DM university wrong; English only; "2020" registration year | Claim the profile through Eka's doctor app and edit, or email support to correct city. Route not verified. | 20 min |
| 8 | **DocIndia** | Rajahmundry dental-clinic address; "10 years"; unverified | Use the site's claim/contact route to update or remove. Route not verified. | 10 min |
| 9 | **Curofy** | Shows him as internal medicine, Manipal | Log in with his old account and update, or delete the profile. Page not reachable from here. | 10 min |
| 10 | **Own YouTube channel** | "over a decade of experience" conflicts with Apollo's "6+ years"; no registration number; no videos | Edit the About text to the fact-sheet wording; add "Reg. No. APMC/FMR/74749"; do not leave it empty for long once other pages link to it. | 10 min |
| 11 | **OpenAlex** (and Semantic Scholar) | IJSR 2021 paper attached to the St. George's University namesake | Create ORCID first, add both papers, then file OpenAlex's author-correction request. | 45 min total |
| 12 | **Google Business Profile(s)** | Unknown | Audit first (action 1). Then align name, category, hours and address to the fact sheet. | 30 min |
| 13 | **NMC register** | Nothing wrong. Displays personal details by design. | No action. Use the exact number format everywhere. | — |

## Deliverable C — canonical public name

**Recommendation: "Dr. Avinash Pathuri"** in English, with "Pathuri Avinash" kept as the registered form and "Avinash Paturi" declared as a former variant.

| Test | Avinash Pathuri | Pathuri Avinash | Avinash Paturi |
|---|---|---|---|
| Matches NMC register surname spelling | Yes (word order differs) | **Exact** | **No — register search returns 0** |
| Existing directory pages | Apollo Clinic | **7 directories incl. Apollo, Practo** | None |
| Existing owned assets | **YouTube @dravinashpathuri**, Curofy slug | None | None |
| Scholarly record | JCDR 2018 byline; PubMed investigator "Pathuri, Avinash" | Same surname index | IJSR 2021 only |
| Collisions | UBS employee on LinkedIn; unrelated YouTube @avinashpathuri | Almost none | ORCID-holding St. George's author; "Paturi A" US cardiology papers; University of Hyderabad kidney researcher |
| Domains free | .com, .in, .org (with and without "dr") | .com, .in | .com, .in |
| Reads naturally in English media, bylines, conference programmes | **Yes (given name first)** | Less so outside Andhra/Telangana | Yes |

Reasoning:
1. **Verifiability.** The NMC guidelines require name and registration number on public posts. A reader who checks will search the register; only the "Pathuri" spelling leads to him.
2. **Searchability.** Google matches both word orders to the same pages, so moving from "Pathuri Avinash" to "Avinash Pathuri" keeps the seven existing listings working for him. Moving to "Paturi" abandons them.
3. **Citations.** His first paper, the NEJM investigator record and every future PubMed entry index under "Pathuri A", which has no cardiology namesake. "Paturi A" already has two cardiology papers by someone else.
4. **What patients type.** Patients find him through hospital pages that say "Pathuri Avinash"; Telugu speakers say the surname first. Keep that order on hospital listings (it is also his registered name) and do not fight it.
5. **He has already chosen it twice** himself: the Curofy profile and the YouTube channel.

Practical rule set:
- Byline, website, social handles, media: **Dr. Avinash Pathuri**.
- Hospital and directory listings: accept "Dr. Pathuri Avinash"; ask Apollo Clinic and Apollo Hospitals to agree on one order.
- Legal, prescriptions, registration line: "Dr. Pathuri Avinash, Reg. No. APMC/FMR/74749".
- Website and ORCID: list "Pathuri Avinash" and "Avinash Paturi" as alternate names so the IJSR paper and old listings resolve to him.
- Telugu: one fixed spelling, used everywhere from day one.
- If he strongly prefers "Paturi" (the brief uses it), the cost is a register mismatch on every post and a permanent namesake problem in PubMed. That decision is his, but it should be made knowingly.

---

## So what for Dr. Avinash

Priority order. One-off unless stated.

1. **Capture the Google review baseline by hand (friend, 30–40 min).** In a normal browser search his name in both word orders on Google Maps. For each listing record: exact name, category, address, whether "Claim this business" appears, rating, count, date of newest and oldest review, owner-reply count. Then read every review and tally themes on a simple grid: listening / explanation / calm manner / availability and follow-up / emergency response / outcome / staff and waiting / cost / negative. Save as an internal note only. Do not publish, quote or repost review text (NMC guidelines).
2. **Confirm the fact sheet (he, 45 min).** Rows 3, 5, 12, 14, 15, 16, 20 and 22–23 need his answer; the rest need a tick.
3. **Decide the name (he, 10 min)** using Deliverable C.
4. **Register the domains (friend, 15 min, about ₹2,000–3,000 for the first year — estimate).** `dravinashpathuri.com` and `.in`; consider `avinashpathuri.com`. All are free today. Ask whether `drpathuri.com/.in` belong to anyone he knows.
5. **Reserve matching handles (friend, 30 min).** @dravinashpathuri on Instagram, X, LinkedIn, Facebook and Threads, if free. Hold them; posting starts only when the plan says so.
6. **Fix the YouTube bio (10 min)** — row 10 of the correction table.
7. **Run the correction table (he + friend, about 4 hours over two weeks).** Practo first (self-serve), then one Apollo email covering rows 2–4.
8. **Resolve Citizens (he, 5 min to decide; 15 min to action).**
9. **Check Telangana registration status (he, 15 min).** If required and not held, start it; it affects what registration line goes on every post.
10. **ORCID + Scholar profile (45 min)** listing both papers and the PROMINENT investigator role, with all three name variants.
11. **Ask Apollo marketing (5 min)** whether any LinkedIn/Instagram/YouTube clip featuring him has ever been published, and get the links.
12. **Monthly (friend, 10 min):** re-check the listings in the correction table and re-run the two name searches.

## Risks & things to avoid

- **Rating templates under his name.** Apollo's 5/5-from-10 markup with placeholder text and Apollo Clinic's "Best Cardiologist" title are the employer's SEO templates, but they carry his name. Under the Oct 2026 guidelines "best" claims and manufactured ratings are the exact things barred. Ask for removal in writing and keep the email.
- **"Over a decade of experience"** on his own channel sits beside "6+ years" on Apollo. On an owned property, an inflated-looking number is his responsibility. Use dated facts instead of a count.
- **Three sets of procedure numbers** are public. Until he supplies logged figures with a date, publish none.
- **Registration line.** "74749" alone is ambiguous across 12 doctors. A Telangana practice with only an AP number shown may invite a query; confirm the position before the first public post.
- **IJSR paper.** Claim it (it is his) but do not headline it; the journal's standing may draw criticism.
- **PROMINENT wording.** "Investigator at a trial site", never "author" or "award".
- **Do not reuse review phrases** in any public material, even anonymised. The capture in action 1 is for internal understanding of what patients value.
- **Empty owned channels.** An empty YouTube channel is harmless now, but once listings link to it, emptiness reads as neglect. Link it only when it has content.
- **Do not create duplicate profiles** on platforms where an old one exists (Curofy, Practo, possibly Google). Recover and correct instead.
- **Privacy.** The NMC register exposes personal details by design; do not link to the record view from his own site — quote the number.

## Open questions / gaps

1. Google Business Profile(s): count, names, rating, review count, themes, owner access. Needs a human with a browser.
2. Instagram, X, LinkedIn, Facebook, Threads: does he hold any account, including dormant personal ones? Are the six handles free?
3. Telangana Medical Council registration: held or not; portal was down.
4. Citizens: has the association ended, and when? Apollo Financial District start date?
5. The reported Apollo Hyderabad LinkedIn post "explaining heart risk tests": does it exist? Any other hospital-channel clips?
6. Full verbatim text of the Apollo profile and the 11 Oct 2025 Citizens snapshot (both blocked here).
7. CSI or other society membership; DM thesis title; any conference posters from Kolkata years.
8. Who created the YouTube channel and who holds the login; who owns `drpathuri.com/.in`.
9. Telugu spelling of his name as he writes it.
10. Google Scholar and ResearchGate: not auditable here.

## Sources

Read directly (pages or public APIs):
- https://nmc.org.in/information-desk/indian-medical-register (search by reg. no. 74749 and by name variants, via the page's public endpoint `https://nmc.org.in/indian-medical-register/search`)
- https://onlinetsmc.in/ (Telangana Medical Council home page; notes that the doctor-search portal is down)
- https://www.youtube.com/@dravinashpathuri (channel `https://www.youtube.com/channel/UC1fZpfwNZAMOc_tDJC1KdeQ`; also `/videos`, `/shorts`)
- https://www.youtube.com/@avinashpathuri and https://www.youtube.com/@avinashpaturi (namesake channels)
- https://www.youtube.com/results?search_query=%22Pathuri+Avinash%22 (and four related queries)
- https://www.apolloclinic.com/find-a-doctor/best-cardiologist-in-hyderabad-telangana/dr-avinash-pathuri
- https://www.apolloclinic.com/clinic-locator/india/telangana/hyderabad/narsingi
- https://www.apolloclinic.com/clinic-locator/hyderabad/narsingi
- https://www.practo.com/hyderabad/doctor/pathuri-avinash-cardiologist
- https://www.citizenshospitals.com/doctor/dr-pathuri-avinash and https://citizenshospitals.com/doctor/dr-pathuri-avinash (generic page only)
- https://www.citizenshospitals.com/doctor/cardiologist
- https://www.ijsr.net/archive/v10i2/SR21122214401.pdf
- https://clinicaltrials.gov/api/v2/studies/NCT03071692 (site list)
- https://eutils.ncbi.nlm.nih.gov/entrez/eutils/esearch.fcgi?db=pubmed&term=Pathuri+A%5BInvestigator%5D&retmode=json (and eight related author/affiliation queries)
- https://eutils.ncbi.nlm.nih.gov/entrez/eutils/esummary.fcgi?db=pubmed&id=42381950,41154837,38125324,19515876,18984757,28496694,19966378&retmode=json
- https://rdap.verisign.com/com/v1/domain/dravinashpathuri.com (and the other .com names in §7)
- https://rdap.nixiregistry.in/rdap/domain/dravinashpathuri.in (and the other .in names in §7)
- https://dns.google/resolve?name=dravinashpathuri.com&type=NS (and the other names in §7)
- https://drpathuri.com/ and https://drpathuri.in/ (parked pages)
- https://archive.org/wayback/available?url=citizenshospitals.com/doctor/dr-pathuri-avinash (snapshot index only)
- https://business.google.com/v/_/016896165858459364897/9317/_/rev/ and https://business.google.com/v/_/012936012808761491676/e2f0/_ (peer cardiologists' profiles, used as benchmark)

Seen only through the search tool's reading or snippets (page blocked to direct fetch):
- https://www.apollohospitals.com/doctors/interventional-cardiologist/hyderabad/dr-pathuri-avinash
- https://curofy.com/doctor/dr-avinash-pathuri-internal-medicine-dravinashpathuri
- https://www.linkedin.com/in/avinash-pathuri-901a73129/ (namesake)
- https://www.apollo247.com/doctors/dr-pathuri-avinash-07916af1-e7a6-4fed-b830-061c4924ffb3
- https://www.eka.care/doctor/dr-pathuri-avinash-cardiologist-rajahmundry
- https://www.docindia.org/doctors/rajahmundry/dr-pathuri-avinash-cardiology
- https://www.vaidam.com/doctor/dr-pathuri-avinash

Attempted, not readable: Google Maps, Google Search, Google Scholar, LinkedIn, Instagram, X, Facebook, Threads, Justdial, web.archive.org, regonlinetsmc.in.

Earlier files relied on: `01-subject-footprint.md`, `02-regulation-ethics-india.md`, `10-seo-reviews-web-presence.md`.
