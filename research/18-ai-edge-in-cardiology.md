# 18 — The AI edge: what it would genuinely mean, in late 2026, for one Indian cardiologist to be visibly ahead of his peers in using AI, safely and lawfully

**Research date:** 12 November 2026. **Scope:** Dr. Avinash Paturi ("Dr. Pathuri Avinash"), interventional cardiologist, Hyderabad; currently at Apollo, planning for independence.

## Executive summary

1. **Buying AI tools is not an edge.** Almost every clinical AI product is either sold to anyone (AI-ECG devices, scribes, smartwatches), owned by a hospital chain (Apollo's AICVD risk score, Narayana's AI-ECG), or not available in India at all (HeartFlow FFR-CT, Anumana's low-EF ECG-AI, Cleerly). Hyderabad hospitals already advertise "AI-powered" equipment; an individual cannot out-buy them.
2. **The evidence is mixed, and knowing that is itself the edge.** AI-ECG for low ejection fraction has a positive randomised trial (EAGLE, 2021) and a strong 2026 validation in Kenya, but the 2026 TRICORDER trial of AI stethoscopes in 205 UK practices found no increase in heart-failure detection, and FAVOR III Europe (2024) showed software-derived QFR failed non-inferiority against wire-based FFR. A cardiologist who can explain these results plainly is rarer than one who owns the device.
3. **The rules are now explicit.** CDSCO finalised its Medical Device Software guidance on 21 July 2026 (AI/ML covered; "hallucination" named as a risk). ICMR (2023) puts responsibility on the clinician who uses the tool. The Telemedicine Guidelines bar AI from counselling or prescribing. NMC clause 7.2 bars synthetic representations of a doctor and requires disclosure. DPDP consent duties bite from 13 May 2027. No Indian court ruling on AI malpractice was found, so ordinary negligence law applies: the doctor stays liable.
4. **Peers are mostly not doing this.** In the only Indian survey found (2025, n=250, mostly students) 82.9% had no AI training and 8% used AI daily. No Hyderabad cardiologist was found publicly positioned as a responsible-AI voice. IIIT Hyderabad (Gachibowli, next to the Financial District) runs an online "AI for Medical Professionals" certificate for Rs 30,000.
5. **The durable edge is workflow plus trust, not hardware:** (i) every patient leaves with a doctor-verified plain-Telugu explanation, (ii) an audited personal outcomes registry, (iii) a published "responsible AI in my practice" charter, (iv) teaching peers how to judge AI tools, (v) a Telugu heart-health library with a carefully staged Q&A assistant, (vi) a Telugu medical-AI evaluation study with IIIT-H. All six travel with him when he leaves Apollo.

> **Method note and limits.** I used 13 web searches (one over the 12-search budget) and about 70 direct fetches, plus PubMed E-utilities for trial abstracts. Primary texts read this session: ICMR AI guidelines 2023 (PDF), ASCI synthetic-content guideline (PDF, 17 Sept 2026), a Shardul Amarchand Mangaldas AI-liability report (PDF, Feb 2026), PubMed abstracts of all trials cited. **Not reachable from this environment:** mohfw.gov.in (Telemedicine Guidelines PDF, 403), ai.telangana.gov.in and hai.iiit.ac.in (do not resolve; they need to be allowed in the session's network settings), csi.org.in (406), bmj.com (403), malaymail.com (403), acc.org innovation page (503). Items tagged **[BK]** come from my background knowledge and were **not re-verified this session**; treat them as leads. Confidence is marked High / Medium / Low. Vendor claims are labelled as vendor claims. This is research, not legal or regulatory advice.

---

## Findings

### 1. Clinical AI that is real and available in India now

#### 1.1 The regulatory frame (applies to every product below)

- **CDSCO Guidance Document on Medical Device Software, Doc No. CDSCO/MD/GD/MDSW/01/2026, issued 21 July 2026** under the Medical Devices Rules, 2017. It takes a function-based approach: software with a medical purpose is a medical device whether standalone or embedded. It expressly covers AI/ML, asks applicants to state whether algorithms are fixed or adaptive and their "degree of autonomy", and names the risks: bias, lack of explainability, model drift, poor generalisability and hallucination. An Algorithm Change Protocol may be required. "Where models have been trained or validated outside India, manufacturers may be required to justify" applicability to Indian settings. Classes A–D follow the existing rules; software that drives hardware takes the hardware's class. (National Law Review, 3 Aug 2026; Emergo by UL, 30 July 2026.) Confidence: High on existence and date; Medium on detail, because I read two law/regulatory summaries and not the CDSCO PDF itself.
- **Excluded from the guidance:** software "intended solely for general wellness, fitness, education, or training without a medical purpose", and software limited to data transfer, storage, formatting or communication, including certain hospital information systems. The exclusion is function-specific. Practical reading: a documentation scribe and an education library sit outside; software that analyses an ECG or image to aid diagnosis sits inside. Confidence: Medium (my interpretation of a summary).
- **The obligations in the guidance fall on manufacturers and importers, not on the doctor who uses the product.** The doctor's duty comes from ICMR 2023 and negligence law (section 3). His practical check is simple: ask each vendor for the CDSCO licence number and the intended-use statement, and keep a copy.

#### 1.2 Product-by-product table

Legend for the last column: **A** = anyone can buy it, no edge from ownership; **H** = hospital-owned, edge belongs to the institution; **N** = not available in India; **R** = research-stage.

| Category | What exists | Best evidence | Regulatory status | Cost / who uses it in India | Differentiator for an independent cardiologist? |
|---|---|---|---|---|---|
| **AI-ECG: low ejection fraction** | Anumana ECG-AI LEF (Mayo/nference) | **EAGLE** cluster RCT, 22,641 adults, 120 primary-care teams: new low-EF diagnosis 2.1% vs 1.6% (OR 1.32) (Nat Med 2021). Kenya, 8 clinics, n=1,444, a different algorithm (AiTiALVSD): sensitivity 95.6%, specificity 79.4%, PPV 43.2%, NPV 99.1% (JAMA Cardiol, June 2026) | FDA-cleared (K250652). Vendor says "available for clinical use in the US and EU"; no India mention | Not found in India | **N.** Knowing the evidence is useful; the product is not obtainable. Confidence: Medium |
| **AI-ECG: Indian in-house** | Narayana Health "Medha AI" ECG-image model | Eur Heart J Digit Health, June 2026: 51,055 patients; AUROC 0.87 internal, 0.84 external (n=20,053); sensitivity 0.80, specificity 0.80, PPV 0.46, NPV 0.95 for major echo abnormalities. Press (Aug 2025) claims 97% detection of EF ≤35% across 14 centres and 57,000 patients | No regulatory approval mentioned in the coverage | Narayana Health only | **H.** Shows Indian chains are building their own. Confidence: High on paper, Medium on press claims |
| **AI-ECG: tele-reporting** | Tricog InstaECG (also InstaEcho) | Vendor claims "42 million+ patients diagnosed"; AI plus cardiologist validation. No independent RCT found | Website shows CE and CDSCO logos | Pricing not public. Clinics, diagnostic centres, state governments | **A**, and it is designed for the spoke, not the cardiologist. He could be a reader/hub, not a customer. Confidence: Medium |
| **Handheld ECG** | AliveCor KardiaMobile, 6L, Card, Kardia 12L | Large validation literature for AF detection [BK] | India site: "US FDA-cleared and CDSCO-approved" | Price not shown on the pages fetched | **A.** Useful for palpitations work-up; not an edge |
| **Handheld ECG (Indian)** | SunFox Spandan 4.0 / Neo / Pro / Ultra 12L | Cardiol Res 2025: n=184, Meerut, ST-elevation sensitivity 94%, PPV 94% vs standard 12-lead. Small, single centre. The site's "99.7% accuracy" has no cited study | "CDSCO Approved" (vendor claim; no number shown) | App plans: free, Rs 249/month, Clinical from Rs 999/month; device price not shown. Vendor claims 5,000+ clinics | **A.** Possible tool for community teaching; evidence thin. Confidence: Medium |
| **AI stethoscope** | Eko-type ECG + phonocardiogram | **TRICORDER** cluster RCT, 205 UK practices, 12,725 recordings: heart-failure detection **no different** (IRR 0.94, 95% CI 0.86–1.02) on intention-to-treat; detection was higher only where the device was actually used (Lancet, Feb 2026) | Algorithms had regulatory approval in the UK trial. India availability: could not verify | — | **No.** The lesson is that accuracy does not equal impact; use falls away. Confidence: High on trial |
| **Smartwatch AF / BP** | Apple Watch; Samsung Galaxy Watch | Apple Heart Study (NEJM 2019) | Apple's India feature page (read 12 Nov 2026) lists **ECG, irregular rhythm notification, AFib History, hypertension notifications and sleep apnoea notifications as available in India** (hypertension may not work on Series 12/Ultra 4 pending clearances). Samsung lists ECG, blood pressure and irregular-rhythm notification for India on Watch4 and later | Patient-owned | **A**, but his IT-corridor audience already wears these. Knowing how to triage a watch alert is a real, teachable skill. Confidence: High |
| **Long-term ECG patch/strap** | Kardi Ai (Czech), launched in Hyderabad 26 Sept 2026 via Eurasia Medical Technologies LLP | No trial data in coverage | Indian MD-15 licence and EU MDR Class IIa (per Telangana Today) | Price not stated | **A.** Confidence: Medium |
| **Contactless monitoring** | Dozee (ballistocardiography under-mattress sensor; "Shravan" home product) | No studies shown on the site | FDA and CDSCO badges (vendor) | Vendor claims 200+ hospitals, 15,500+ beds | **H** for wards. Home heart-failure use is unproven. Confidence: Medium |
| **AI for occlusion MI (STEMI triage)** | PMcardio "Queen of Hearts" | US registry, 1,032 cath-lab activations: sensitivity 92.0% vs 71.0% for standard triage; false-positive activations 7.9% vs 41.8% (JACC Cardiovasc Interv, Jan 2026). Retrospective | India status: could not verify | — | **R.** Directly relevant to teaching first-contact doctors (see file 15, "First ECG"). Confidence: High on paper |
| **AI echo** | Us2.ai; Ultromics EchoGo; GE/Caption guidance | Us2.ai: multicohort validation (Lancet Digit Health 2022); vendor cites a 2026 JAHA randomised trial, +2 exams per sonographer per day | Us2.ai: FDA 510(k), CE Class IIb, "34 markets". No CDSCO clearance mentioned on its site; one Indian hospital testimonial. Ultromics and Caption in India: could not verify | Pricing not public | **H / A.** Echo AI is a throughput tool. Only matters if he runs his own echo service. Confidence: Medium |
| **Coronary CT-AI** | HeartFlow FFR-CT; Cleerly; Caristo | **PRECISE** RCT (n=2,103): composite endpoint 4.2% vs 11.3% (HR 0.35), driven by fewer caths without obstructive disease; death/MI not different, non-fatal MI numerically higher (1.2% vs 0.5%) (JAMA Cardiol 2023). AI plaque quantification has registry data, not outcome trials | A 2025 status review of CT-FFR in Asia covers Korea, Japan, Hong Kong, Singapore, Taiwan, Thailand and Vietnam and does not mention India. My search found no Indian launch of HeartFlow or Cleerly | — | **N.** Confidence: Medium (absence of evidence) |
| **Cath-lab physiology from angiography (QFR)** | Medis QFR and similar | FAVOR III China (Lancet 2021): QFR guidance beat angiography guidance. **FAVOR III Europe (Lancet 2024): QFR did not meet non-inferiority to FFR** (event difference 2.5%, 90% CI 0.9–4.2, margin 3.4%); authors: results "do not support the use of QFR if FFR is available" | India availability: could not verify | — | **No.** A model case for teaching "software ≠ wire". Confidence: High on trials |
| **AI-OCT / IVUS** | Abbott Ultreon (automated calcium and vessel sizing) | ILUMIEN IV (NEJM 2023) tested OCT guidance, not the AI: larger stent area, no difference in target-vessel failure [BK for results] | Ultreon was launched in India around 2021–22 [BK]; not re-verified. A search for Indian "AI cath lab" launches returned only imaging-chain features (Fortis Noida 2023; Wipro GE Optima IGS 320, 2022, automatic dose/image optimisation) | Bundled with the OCT console; hospital-owned | **H.** He should use it well and teach it; it is not his to own. Confidence: Low–Medium |
| **Cardiac MRI AI** | Automated contouring in vendor software [BK] | — | — | Imaging departments | Not relevant to his lane |
| **Retinal image → CV risk** | Reti-CVD (Mediwhale, Korea); Indian academic models | Reti-CVD validated in UK Biobank (BMC Med 2023) and a Korean pivotal study (JAMIA 2023). Indian papers 2024–26 are model-development studies | No validated, regulator-cleared Indian product found. One Hyderabad hospital (Sindhu) announced an AI screening tool for diabetic complications (headline only, not read) | — | **R.** Not ready for his practice. Confidence: Medium |
| **AI risk score built on Indians** | Apollo **AICVD** | 31,599 participants from six Apollo hospitals, 2009–2018; AUC 0.853; validation AUCs 0.84–0.92; outperformed Framingham and QRISK3 in that dataset (Fam Med Community Health, Jan 2024). Authors are at Apollo Hospitals, Hyderabad. Retrospective; health-check population; no prospective impact study found | In-house software, not a marketed device. Apollo announced a "Cardiovascular Disease Risk tool" built on about 4 lakh individuals in Sept 2021 (probably the same programme; not confirmed) | Apollo-proprietary; availability to outside doctors not stated | **H.** It stays with Apollo when he leaves. Confidence: High on paper |
| **Polygenic risk scores** | South Asian CAD genome-wide score | JACC 2020: top 5% of score had OR 3.22 for CAD in the Indian validation set (MedGenome collaboration). 2024 study in 13,974 Asian Indians: ancestry-specific models predicted 18–22% better than European-derived ones | Laboratory test, not SaMD. Commercial availability and price in India: could not verify | — | **R.** No trial shows that knowing the score changes outcomes. Suitable for research, not routine care. Confidence: Medium |
| **Heart-failure telemonitoring** | Apps and nurse-led follow-up | Indian work is feasibility-stage: Suhriday app pilot (BMJ Open 2022); a task-sharing plus mHealth RCT (Am Heart J Plus 2023); file 15 cites TIME-HF (India, 2026; nurse-coordinated care, mortality HR 0.78). mWellcare (Circulation 2019), a large Indian cluster RCT of app-based decision support, showed no advantage over enhanced usual care [BK for result] | — | Low tech cost; staff time is the cost | **Yes, as a workflow** (class b below): the benefit comes from the nurse and the protocol, not the algorithm. Confidence: Medium |
| **Digital cardiac rehab** | App-based home programmes | 2025 JACC Asia review: digital CR can be an effective alternative, limited by literacy, connectivity and adherence. Indian studies are usability/prototype stage (TaCT for women, 2025; SRCardioCare, 2026) | — | — | **Yes, as a programme** he designs. No Indian hard-outcome trial found. Confidence: Medium |
| **CGM for non-diabetics** | Consumer wellness programmes | No outcome evidence found in people without diabetes; trials are in diabetes | Wellness positioning | — | **No.** Recommending it without evidence would cost credibility. Confidence: Medium [BK] |

**What this table says.** Of roughly twenty categories, none gives an independent cardiologist a lasting advantage through ownership. The few with strong evidence are either unavailable in India or sit inside hospital systems. The realistic clinical uses for him are: triaging wearable alerts well, using intracoronary imaging software competently, using AI-ECG within teaching and research, and running nurse-and-protocol programmes where software is the minor ingredient.

### 2. AI for the practice itself

#### 2.1 Ambient scribes and documentation

- **International evidence is modest but real.** A UCLA randomised trial of 238 physicians (NEJM AI, Dec 2025) found Nabla cut time-in-note by 9.5%; Microsoft DAX showed no significant change. Scribes were used in only about 30% of visits. Clinicians reported clinically significant inaccuracies "occasionally". A second trial (66 practitioners, same issue) found less work exhaustion and 0.36 fewer hours per day on notes. Confidence: High.
- **Safety signal.** ECRI's August 2026 survey of 124 safety leaders: 31% had seen an incorrect or misleading AI output in the past year, 9% said an AI error reached a patient or affected a decision, and ambient scribes were the most commonly encountered tool (37%). Confidence: High.
- **India: Eka Care's EkaScribe is the most concrete option.** The product page lists 20+ languages including Telugu; the developer documentation for the Parrotlet-a 2.5 Pro speech model (released 10 Aug 2026) lists Indian English, Hindi, Marathi, Kannada and Telugu "including code-mixed speech". Eka's own February 2026 benchmark reported about 93% medical-keyword accuracy in Indian English and about 85% in Hindi; **no Telugu figure was published**. Price: free for 5 consultations a day; **Pro Rs 1,499 per doctor per month**. Vendor statements: data encrypted, hosted on servers in India, ISO 27001, staff have no access to patient data. Whether audio is used for model training is not stated. User counts are inconsistent (1,400+ active users on the product page; "more than three thousand doctors" in February press). Confidence: High on price and language list; Medium on everything self-reported.
- **Augnito** (Omni ambient product, Spectra dictation) claims "37+ languages" and shows an Apollo logo; specific languages, Telugu performance and prices are not published. **HealthPlix** lists an AI product called H.A.L.O and an ABDM badge; details were not retrievable. **Nabla, Abridge and Microsoft DAX**: I found no evidence of Telugu support or of sales to independent Indian clinics. Could not verify.
- **How good is machine Telugu, independently measured?** The only independent benchmark found is "Voice of India" (Josh Talks, August 2026, draft v2): 536 hours of unscripted telephone speech in 15 languages, scored with a metric that forgives code-mixing and spelling variants. **Telugu error rates for the best systems were 13.5% (Saaras v3), 14.1% (Amazon), 18.3% (Gemini 3 Pro) and 19.6% (ElevenLabs Scribe v2), against 3.8–5.9% for Hindi.** This is conversational, not clinical, speech. A research paper surfaced in search states there is no large public benchmark for ambient clinical scribes in India (seen in search summary only). Confidence: Medium.
- **Reading:** a Telugu-English scribe will produce a usable draft and roughly three times the error rate of Hindi. Word error rate does not capture the dangerous errors (a dropped "no", a wrong dose). Every note needs his eyes.

#### 2.2 Discharge summaries and plain-Telugu explanations

- **Evidence:** in a study of 50 discharge summaries rewritten by an LLM into patient-friendly language (JAMA Netw Open, March 2024), readability improved markedly, but only 56 of 100 reviews rated the output entirely complete and **18 reviews flagged safety concerns**, mostly omissions plus some hallucinated statements. The authors concluded physician review is needed. Confidence: High.
- **Telugu:** I found no published evaluation of LLM-generated Telugu medical explanations for accuracy or comprehension. Could not verify. This is a gap he could fill with a small study (play 6 in section 5).

#### 2.3 Appointment, follow-up and adherence on WhatsApp

- **Platform rule:** from 15 January 2026 the WhatsApp Business API bars general-purpose AI assistants where the AI is the main function; Meta confirmed that businesses using AI to serve their own customers remain allowed (TechCrunch, 18 Oct 2025, updated). A clinic reminder and follow-up bot is on the permitted side; an open "ask the AI doctor anything" bot on WhatsApp is at Meta's discretion and should be avoided. Confidence: High.
- **Clinical evidence** for text-message support after a cardiac event is mixed: TEXT ME (JAMA 2015) improved risk factors; the larger TEXTMEDS trial did not improve medication adherence [BK, not re-verified]. Treat reminders as a convenience, not a proven therapy.
- **Legal:** follow-up messages to his own patients are care, not advertising. Broadcasts to non-patients fall under the NMC Guidelines (file 11). DPDP notice and consent for messaging apply from 13 May 2027.

#### 2.4 Doctors offering "an AI version of themselves" — what happened

| Example | What it is | What is known about results |
|---|---|---|
| **Dr Duan Tao**, Shanghai obstetrician, on Ant Group's AQ app | AI clone trained on textbooks, cases and his social-media content (10 million+ followers). Reported to have "served 160,000 patients in six months"; AQ reported 100 million+ users and 1,000+ expert doubles (AFP reporting, March 2026, read via a secondary site; Malay Mail headline matches) | No accuracy or outcome data published. Duan himself: "At the beginning, I did have concerns"; "Humans must retain the ultimate decision-making and choice." Confidence: Medium |
| **Dr Mansoor Anwar Habib**, UAE, 9verse AI (live July 2025) | Voice-cloned twin for general wellness and prevention, 30+ languages including Hindi; blocked from diagnosis, prescriptions and treatment plans | No usage or outcome data reported. Confidence: Medium |
| **UCHealth "Livi"** (US, institutional assistant, not a doctor clone) | Scheduling and FAQ assistant with a "virtual assistant" disclaimer | In a patient survey, one in three people were unsure what Livi was and a small share thought it was a human typing (CU Anschutz, Aug 2025). Confidence: Medium |
| **Commentary** | Medical Economics (2 Oct 2026) on a hypothetical "Dr Jones" clone | Lists the failure modes: patients assume the doctor is watching; scope creep from intake to advice; a smooth non-urgent reply to chest pressure; no staffed escalation after hours; likeness ownership. Cites the AMA position that AI content should not be produced on a physician's behalf without consent and final review |

- **No published safety or outcome evaluation of any physician clone was found.** No Indian doctor with a public AI twin was found (could not verify either way).
- **The strongest relevant evidence is negative.** In a preregistered randomised study of 1,298 members of the public (Nature Medicine, Feb 2026), LLMs working alone identified the right condition in 94.9% of scenarios, but people using the same LLMs identified relevant conditions in fewer than 34.5% of cases and the right course of action in fewer than 44.2%, no better than controls. The authors recommend human user testing before any public deployment. ECRI named **misuse of AI chatbots the number one health technology hazard for 2026** (21 Jan 2026), citing wrong diagnoses, invented anatomy and unsafe device advice. Confidence: High.
- **Indian constraint:** NMC clause 7.2(b) bars AI used "to create a synthetic endorsement or representation purporting to be that of an actual patient, RMP or other person". A talking avatar or cloned voice "of Dr Avinash" answering patients sits squarely in the risk zone. A text assistant that is clearly labelled as software, answers only from his reviewed library and refuses personal medical questions is a different object. File 11 lists the voice-clone question as unsettled.

#### 2.5 Literature surveillance, guideline summaries, research writing, registry extraction

- General-purpose LLMs and literature tools can draft summaries of new trials and guidelines. The risk is fabricated or mis-attributed citations; every reference must be opened and read. No India-specific product evidence was gathered; this is a workflow, not a purchase. Confidence: Medium (judgement).
- **Registry extraction:** Narayana's AI-ECG paper built its labels by extracting echo findings from structured reports with keyword rules, which shows the method is publishable. LLM-based extraction from free-text reports is feasible but has to be validated against manual abstraction on a sample (for example 100 records, double-checked) before the numbers are trusted or published. Confidence: Medium.
- **Journals:** ICMJE-following journals require disclosure of AI use in writing and do not accept AI as an author [BK]. File 07 covers publishing strategy.

#### 2.6 Voice cloning and dubbing for Telugu-English education

- **YouTube automatic dubbing supports English → Telugu and Telugu → English.** Dubs are marked "auto-dubbed" in the description, cannot be edited, and YouTube warns of errors with proper nouns, idioms and jargon. Confidence: High (YouTube Help, read 12 Nov 2026).
- **YouTube's disclosure policy** treats cloning one's own voice for voice-overs or dubs as not requiring disclosure, while realistic content that makes a real person appear to say something they did not say must be disclosed. Confidence: High.
- **Indian rules are stricter than YouTube's.** (i) The IT (Intermediary Guidelines) Amendment Rules 2026, in force 20 February 2026, define "synthetically generated information", require platforms to label it with visible marks and metadata, and require large platforms to obtain a user declaration; good-faith educational uses and accessibility improvements are excluded (Legal500/Mondaq analysis). (ii) ASCI's guideline of 17 September 2026 (effective three months after publication, so about 17 December 2026) makes a label mandatory when "replicating a real person's likeness or voice even with their consent, for personalised messaging", and requires no label for "subtitles, close captions, translations" made for accessibility. (iii) NMC 7.2(c) requires disclosure where the artificial nature "may reasonably be material to the audience's understanding". Confidence: High on texts (ASCI read in full); Medium on how they apply to a doctor's own dubbed voice.
- **Reading:** he is a native Telugu speaker. The cleanest route is to record Telugu and English himself and use AI only for subtitles and translation drafts that he checks. If an AI dub is ever used, label it on screen and in the description.

### 3. Rules and risk

#### 3.1 The rule set at a glance

| Instrument | What it says that matters here | Status | Confidence |
|---|---|---|---|
| **ICMR Ethical Guidelines for Application of AI in Biomedical Research and Healthcare (2023)** | Ten principles: autonomy; safety and risk minimisation; trustworthiness; data privacy; accountability and liability; optimisation of data quality; accessibility, equity and inclusiveness; collaboration; non-discrimination and fairness; validity. "Humans should have complete control of the AI based healthcare system and medical decision-making." Patients "must have complete autonomy to choose or reject AI technologies." "AI for health should always be appropriately supervised." "Like other diagnostic and decision-making tools used in clinical practice the responsibility of optimal utilization of the technology is on the health professional using AI-based solutions." Flawed functionality points to the developer; "defective implementation" points to the end-user or organisation | Guidance, not statute; a "living document". Applies to clinicians as well as developers | High (primary PDF read) |
| **Telemedicine Practice Guidelines 2020** | "Artificial intelligence/machine learning are not allowed to counsel the patients or prescribe any medicines" (as quoted in a 2020 PMC article). The official text adds that AI may assist the RMP but the final prescription or counselling must be delivered directly by the RMP [BK; MoHFW PDF blocked] | In force (appended to the 2002 Regulations) | High on the rule; wording Medium |
| **CDSCO Medical Device Software guidance (21 July 2026)** | See 1.1 | Guidance under MDR 2017 | High / Medium |
| **SAHI and BODH (MoHFW, 17 Feb 2026)** | SAHI = Strategy for Artificial Intelligence in Healthcare for India, a national governance framework. BODH = Benchmarking Open Data Platform for Health AI, built by IIT Kanpur with the National Health Authority to test models on Indian data before deployment. No direct obligations on individual clinicians found | Policy framework | Medium |
| **DPDP Act 2023 and Rules 2025** | Phases: Board and definitions from 13 Nov 2025; **consent-manager registration from 13 Nov 2026**; **notice, consent, fiduciary duties, rights and cross-border rules from 13 May 2027**. Cross-border transfer is allowed except to countries the government restricts; significant data fiduciaries may face localisation. Security safeguards include encryption, access control, logs kept one year; processor contracts must carry security duties; breach notice to the Board within 72 hours. Penalties up to Rs 250 crore for security failures (file 02) | Phased | High (AZB summary; file 02) |
| **NMC Guidelines, 6 Oct 2026, clause 7.2** | AI-generated promotional campaigns prohibited; no AI manipulation of a patient's image, testimonial, voice or outcome; no synthetic representation of an actual patient or RMP; disclosure where artificial nature is material; "Any use of patient information as input for an AI system shall comply with applicable privacy, confidentiality, data-protection and professional-ethics requirements" (7.2(d)) | In force | High (files 02, 11) |
| **IT Rules amendment (20 Feb 2026) and ASCI guideline (17 Sept 2026)** | See 2.6 | In force / effective about 17 Dec 2026 | High |
| **WHO guidance on large multi-modal models in health** | "Ethics and governance of artificial intelligence for health: Guidance on large multi-modal models" (98 pages; WHO page dated 25 March 2025; first issued January 2024 [BK]) | Reference | Medium (title and date verified; contents not re-read) |
| **US FDA and EU AI Act** | FDA publishes a list of authorised AI-enabled devices and has lifecycle guidance; the EU AI Act treats AI in regulated medical devices as high-risk [BK] | Reference only | Low (not re-verified) |

**Two pipelines, two rules.** Earlier files set the rule "no patient data ever enters an AI tool" for the publishing system. That rule stands for content. Clause 7.2(d) does not ban clinical AI; it requires that patient data given to an AI tool meets privacy and ethics law. So the plan needs two separate pipelines:

- **Content pipeline** (posts, videos, articles, the public library): zero patient data, always.
- **Clinical pipeline** (scribe, patient explanations, registry): patient data only in tools with an India-hosted, contract-bound vendor (or offline), with patient notice and consent, minimum data, and his review of every output.

**At Apollo the hospital is the data fiduciary and decides which tools touch patient records.** He should not run a personal scribe on Apollo patients without written permission. In his own clinic he is the fiduciary and carries the DPDP duties himself.

#### 3.2 Liability when AI is wrong

- **No Indian judgment on AI-related medical negligence was found.** A September 2026 legal commentary and a February 2026 Shardul Amarchand Mangaldas report both treat the area as governed by ordinary negligence law. The SAM report says its research "did not find any evidence of a structured understanding of how responsibility should be allocated among various stakeholders in an AI based system" in the statutes analysed. Confidence: Medium (absence of evidence; a lawyer should check NCDRC and Supreme Court databases).
- **Position by default:** the Bolam standard as adopted in *Jacob Mathew v State of Punjab* (2005) 6 SCC 1; paid medical services are "services" under the Consumer Protection Act (*IMA v V.P. Shantha*, 1995). A doctor who relies on an AI output a competent practitioner would have questioned is exposed; using AI is not in itself negligent if he applies independent judgement. Whether AI software counts as a "product" for strict product liability under the Consumer Protection Act 2019 is unsettled (SAM report). Confidence: Medium.
- **Practical consequence:** the doctor is the last line and the first defendant. Records should show that he reviewed the AI output and made the decision himself.

#### 3.3 Informed consent wording (draft for his lawyer to review)

For clinic use (to be written in Telugu and English by him, not machine-translated without checking):

> "In this clinic some tasks are assisted by computer software that uses artificial intelligence (AI). Examples: writing up the notes of our conversation, preparing a simple-language explanation of your condition, and helping to read some tests. The software does not make decisions about your care. I personally check everything it produces before it is used, and I am responsible for your diagnosis and treatment. Your information is kept confidential and is shared with the software provider only as needed for these tasks, under a written agreement. You may say no to the use of AI in your care at any time, and your care will not be affected. If you have questions, please ask me or my staff."

Record the patient's choice (yes / no) in the notes. This follows ICMR 1.1 (right to refuse, no coercion) and anticipates DPDP notice requirements. Confidence: Medium (drafting judgement, not legal advice).

#### 3.4 Documented failures and harms worth knowing by heart

| Failure | Source | Lesson |
|---|---|---|
| AI stethoscope accurate in studies, no gain in heart-failure detection in routine practice | TRICORDER, Lancet 2026 | Implementation, not accuracy, decides benefit |
| Software QFR failed non-inferiority to wire FFR | FAVOR III Europe, Lancet 2024 | A computed surrogate can be worse than the measurement it replaces |
| Endoscopists' adenoma detection without AI fell from 28.4% to 22.4% after months of AI exposure | Lancet Gastroenterol Hepatol, Oct 2025 | Deskilling is measurable |
| 43 of 903 FDA-authorised AI devices (4.8%) recalled; missing clinical-study information associated with higher recall hazard | JAMA Netw Open, June 2026; JAMA Health Forum, Aug 2025 | "Cleared" is not "validated" |
| Public users with an LLM did no better than controls | Nature Medicine, Feb 2026 | The human–chatbot interaction is the weak point |
| Chatbot misuse ranked top hazard; invented anatomy, unsafe advice | ECRI, Jan 2026 | Unsupervised health chatbots are a recognised hazard |
| LLM patient-friendly discharge summaries: 18 of 100 reviews flagged safety issues | JAMA Netw Open, 2024 | Verify every patient-facing document |
| Deepfake videos of well-known Indian doctors used to sell remedies (2024 reports) [BK, not re-verified] | — | A doctor with a public voice needs a provenance habit: "if it is not on my channel, it is not me" |

### 4. What peers are (and are not) doing

#### 4.1 Adoption data

- **India (weak data):** a 2025 questionnaire of 250 IMA-register respondents (49% undergraduates, mean age 23, 64.7% from the south): **82.9% had never taken an AI course**; 35% never used AI tools, 8% used them daily; only 6.9% knew a model should be tested on a different dataset (Bioinformation, May 2025). The paper has internal inconsistencies. Confidence: Low–Medium.
- **Global:** Elsevier's Clinician of the Future 2025 reports 48% of clinicians using AI tools for work, up from 26% in 2024; most use general tools such as ChatGPT; only 30% say their institution gives enough AI training. An India-specific split (a blog cited 12% rising to 41%) could not be verified because the page returned 404. Confidence: Medium.
- **Cardiologists in India specifically:** no survey found. Could not verify.
- **Curriculum signal:** on 6 October 2026 a cardiologist-editor (Dr Prem Aggarwal, Medical Dialogues) published a "vision statement for an AI-ready Indian medical system" calling for minimum AI competencies, faculty training and attention to automation bias. The profession is talking about readiness and has little of it.

#### 4.2 Hyderabad hospitals that advertise AI

| Hospital | What is advertised | Cardiology-specific? |
|---|---|---|
| **Apollo** | AICVD risk score (authors at Apollo Hyderabad); the Financial District 400-bed "smart hospital" (April 2026) with AI-based appointment scheduling and AI MRI workflows; an 11-bed AI-enabled "ICU of the Future" with Medtronic at Jubilee Hills (16 July 2026) | AICVD only |
| **AIG Hospitals** | Center for Artificial Intelligence & Innovation; PRISM polyp-detection AI; sepsis prediction system; twin hybrid cath labs | No AI named in the cath labs |
| **Star Hospitals** | Blog (Oct 2025) on "AI-aided cardiac diagnostics"; no products named | Generic |
| **Medicover (Financial District, 2026)** | Cardiac scan "in five seconds" | Scanner speed, not decision AI |
| **Others** | Kardi Ai long-term ECG launched in Hyderabad (Sept 2026). No KIMS or Yashoda cardiology AI launch surfaced in one search | — |

Pattern: institutions advertise AI as equipment. No Hyderabad cardiologist was found who publicly explains AI evidence or publishes how he uses AI. Confidence: Medium–Low (one search plus fetches; absence of evidence).

#### 4.3 Indian cardiology and AI: named people

Verified in sources read this session: **Dr Deepak Padmanabhan** (electrophysiology, Narayana Health, Bengaluru; last author, listed as "Padmanabhan D", of the 2026 AI-ECG paper; first name from background knowledge), **Dr Pradeep Narayan** (Narayana Health, Chief Scientific Officer; lead researcher on the ECG model), **Dr Sujoy Kar** (Apollo Hospitals, Hyderabad; corresponding author on AICVD), **Dr Prem Aggarwal** (cardiologist; Medical Dialogues chairman; AI-readiness advocate). Internationally, **Dr Partho Sengupta** (US-based, Indian-origin, echo and AI) is a long-standing voice [BK]. A fuller list of CSI-level AI figures could not be verified because csi.org.in was unreachable.

#### 4.4 Societies and working groups

- **CSI Digital Technology Council** exists among the 16 subspecialty councils for 2026–27 (file 07). The joining mechanism is not published; the route is a direct approach to the convener with a concrete offer.
- **ESC:** the **e-Cardiology Working Group** covers AI, signal processing and e-health; membership applications are open and joining is free. The ESC also has a Digital Cardiology and AI Committee, an "AI Gateway" (chair Prof Folkert Asselbergs) and the journal *European Heart Journal – Digital Health* (editor Nico Bruining). The **ESC Digital & AI Summit 2026 is on 12–13 November 2026 in Basel**, which is today and tomorrow; its 2025 presentations are on ESC 365. Confidence: High.
- **ACC:** the **Health Care Innovation Member Section** (requires ACC membership) covers AI and digital health. Dated items: **JACC: Advances focus issue on AI, digital health, wearables and remote monitoring, submissions due 4 January 2027**; an ACC.27 pre-conference, "The Future of Cardiology: Harnessing Artificial Intelligence Across the Cardiovascular Ecosystem", on **9 April 2027** in Houston. Confidence: High.

#### 4.5 Courses and certificates

| Course | Facts | Verdict |
|---|---|---|
| **IIIT Hyderabad iHub-Data, "AI for Medical Professionals"** | Third iteration began 1 June 2026 (earlier cohorts June and December 2025). Online; four modules (AI in healthcare, ML basics, clinical applications including ECG, ethics and regulation of AI as a medical device); about 3 hours a week; **Rs 30,000 for working professionals**; certificate issued jointly by IIIT-H, iHub-Data and NAMS. Contact: programs@ihub-data.iiit.ac.in | **First choice.** Local, credible, cheap, and it puts him in a room with the IIIT-H faculty he would later collaborate with. Confidence: High |
| **Stanford "AI in Healthcare" specialization (Coursera)** | Five courses, beginner level, CME-accredited; fee not shown | Good self-paced supplement. Confidence: High |
| **Stanford HAILS (Healthcare AI Leadership & Strategy)** | 7 May–4 June 2027, two days on campus; USD 8,000–8,800 plus travel | Not needed now |
| **NPTEL, IISc, IIT-H programmes** | Could not verify this session | — |

#### 4.6 Hyderabad's AI-health ecosystem

- **IIIT-H iHub-Data** (Gachibowli) has a healthcare vertical, runs the course above, hosts IoT-AI for healthcare workshops and internships, and partners with start-ups on deployment. Confidence: High.
- **Telangana AI Mission (T-AIM), T-Hub, IIT Hyderabad, AIG's AI centre:** not verified this session (state and IIIT sub-sites did not resolve). File 09 identifies the Society for Cyberabad Security Council (250+ IT-corridor companies) as the employer-side route.
- **National:** BODH (IIT Kanpur and NHA) is the official benchmarking platform; Eka Care's speech and document models are published openly on Hugging Face and AIKosh, which makes independent evaluation possible.

### 5. Where the edge is durable

#### 5.1 Three classes

| Class | Examples | Who can copy it | Durability |
|---|---|---|---|
| **(a) Tools anyone can buy** | Scribe subscription, handheld ECG, smartwatch features, AI echo software | Any doctor with a credit card; any hospital faster | None. Use them, do not build identity on them |
| **(b) Workflows that need his judgement and his data** | Verified patient explanations; an audited outcomes registry; a nurse-and-protocol follow-up programme; a reviewed Telugu content library | Only someone willing to do the review work every week for years | High. The asset is the accumulated, checked material and the habit |
| **(c) Public positioning: "the cardiologist who explains and uses AI responsibly"** | A published charter; teaching peers to appraise AI; honest public explanations of what AI can and cannot do for the heart; a peer-reviewed evaluation | Requires (b) to be true first, otherwise it is hype and a regulatory risk | High if backed by (b); fragile if not |

The NMC Guidelines forbid claims of superiority, so "ahead of peers" can never be stated. It has to be visible through published method, published results and teaching.

#### 5.2 Seven plays

**Play 1 — "Every patient leaves understanding": a plain-Telugu (and English) explanation, AI-drafted, doctor-verified.**
- *What:* after each consultation or procedure the patient receives one page: what was found, what was done, what each medicine is for, warning signs, next visit. Drafted from a structured template by an LLM, corrected and signed by him.
- *Evidence:* LLM rewrites improve readability but 18% of reviews found safety problems (JAMA Netw Open 2024); verification is the product.
- *Cost:* an LLM subscription (order of Rs 2,000 a month, estimate) plus 2–3 minutes per patient once templates are mature; about 10 hours one-off to build 15–20 condition templates.
- *Legal conditions:* build drafts from non-identifying inputs (diagnosis, procedure, drug list) and add the name locally; India-hosted or contract-bound tool; consent wording in 3.3; at Apollo, hospital permission. Footer: "Prepared with AI assistance and checked by Dr …, TGMC Reg. No. …".
- *Hard to copy because:* it needs a personally reviewed Telugu template library and the discipline to check each one. Hospitals optimise for throughput, not for this.
- *What could go wrong:* a wrong dose or omitted warning in a document carrying his name; mistranslated Telugu terms; drift into unchecked bulk generation. Mitigation: he reads every page; audit 20 documents a month.

**Play 2 — An audited personal outcomes registry, maintained with AI-assisted extraction.**
- *What:* a prospective log of his own procedures and outcomes (file 07 already recommends this), with LLM or rule-based extraction from reports to cut the clerical load, validated against manual abstraction.
- *Evidence:* extraction from structured echo reports underpinned a 51,000-patient Indian paper (EHJ-DH 2026).
- *Cost:* 6–10 hours to design fields; 30–60 minutes a week; optional data assistant.
- *Legal conditions:* the records belong to the hospital where the procedure is done, so he needs institutional permission and ethics-committee approval for research use; de-identify before any cloud processing or run extraction offline; DPDP from May 2027.
- *Hard to copy because:* it takes years of consistent entry; it cannot be bought. It is also the base for fellowships and papers.
- *What could go wrong:* extraction errors inflating results; publishing outcomes in a way that reads as a superiority claim (NMC); losing access to data when he leaves Apollo. Mitigation: start now, keep a lawful personal copy of his own de-identified procedural log with permission, and report through journals and society registries, not social media.

**Play 3 — A public Telugu heart-health library first, then a tightly limited Q&A assistant.**
- *What:* stage 1, a library of 100–150 reviewed questions and answers in Telugu and English (each with sources and a review date). Stage 2, a search assistant that answers only by retrieving from that library, shows the source passage, and declines personal medical questions. Stage 3, user-test it with 30–50 ordinary people before any public launch.
- *Evidence:* the caution is strong (Nature Medicine 2026; ECRI 2026). There is no outcome evidence for doctor clones anywhere.
- *Cost:* stage 1 is mostly his time (about 2 hours a week for a year). Stage 2 build cost was not researched; a retrieval-only assistant is a modest software project.
- *Legal conditions:* education only, no counselling or prescribing (Telemedicine Guidelines); labelled as software; **not** named, voiced or pictured as him (NMC 7.2(b)); no collection of health data from users without DPDP-grade notice; not on the WhatsApp Business API as a general chatbot; a fixed emergency message for chest pain or collapse ("call 108, go to the nearest hospital") [108 is the Telangana ambulance number, BK].
- *Hard to copy because:* the reviewed bilingual library is the moat. File 04 found Telugu heart content dominated by non-cardiologist aggregator channels.
- *What could go wrong:* a wrong or reassuring answer to someone with real symptoms; users treating it as a consultation; a council reading it as a promotional device. Mitigation: retrieval-only, visible sources, weekly log review, a kill switch, lawyer sign-off before launch. If in doubt, stop at stage 1; the library alone is valuable.

**Play 4 — Teach peers "AI for the practising cardiologist".**
- *What:* a 45-minute case-based talk and a short written series on how to read an AI paper and question a vendor: EAGLE vs TRICORDER, FAVOR III China vs Europe, the Kenya AI-ECG numbers (PPV 43%), deskilling, CDSCO's 2026 guidance.
- *Evidence:* 82.9% of surveyed Indian doctors and students had no AI training; a national "AI readiness" call was published in October 2026.
- *Cost:* about 12 hours to build the first talk; 2 hours a month to keep it current.
- *Legal conditions:* peer education is squarely permitted; declare no vendor ties and accept no vendor fees for it.
- *Hard to copy because:* it needs someone who has actually read the trials and has no product to sell. Venues: CSI Telangana chapter, CSI Digital Technology Council, IIIT-H's course (as clinical guest faculty), DM trainee teaching.
- *What could go wrong:* being seen as anti-technology or as a vendor proxy; errors of fact in front of peers. Mitigation: cite primary papers on every slide.

**Play 5 — An AI-assisted prevention programme for IT-corridor employees.**
- *What:* employer-hosted education plus a structured risk review: validated risk estimation, guideline-based testing, a clear protocol for smartwatch alerts (ECG, irregular rhythm and hypertension notifications are live in India), and plain-language reports drafted with AI and verified by him.
- *Evidence:* local need is documented in file 04 (84% fatty liver, 76.5% high LDL among 345 Hyderabad IT employees). There is no trial evidence that AI risk tools improve outcomes; the AI here supports communication and triage, not diagnosis.
- *Cost:* 3–4 hours per session including preparation; software cost small.
- *Legal conditions:* education in his own name is allowed; no soliciting, no free procedures as inducement, no employer payment tied to referrals (file 15, clauses 8.1(ii) and 8.1(x)); employee data never goes to the employer; consent per person.
- *Hard to copy because:* hospitals run packages; an independent, non-selling cardiologist who also explains the employees' own wearable data is a different offer.
- *What could go wrong:* over-testing the worried well; false-positive watch alerts flooding his clinic; the programme being read as patient acquisition. Mitigation: publish the protocol and the referral thresholds.

**Play 6 — A research collaboration with IIIT-H on Telugu medical AI.**
- *What:* a small, publishable evaluation that nobody has done: (i) accuracy of speech recognition on simulated Telugu-English cardiology consultations, or (ii) accuracy and comprehension of LLM-generated Telugu explanations of common cardiac conditions, rated by cardiologists and tested with lay readers.
- *Evidence of the gap:* no clinical Telugu benchmark exists; the general benchmark shows Telugu error rates of 13.5–19.6% against 3.8–5.9% for Hindi; no published Telugu patient-education evaluation was found.
- *Cost:* the iHub-Data course (Rs 30,000) as the entry point; then about 2 hours a week for 6 months; simulated or consented data only.
- *Legal conditions:* ethics-committee approval; ICMR 2023; no real patient audio without consent.
- *Hard to copy because:* it needs a Telugu-speaking cardiologist and an AI lab together. A paper in a digital-health journal such as EHJ-Digital Health gives peer-reviewed standing in exactly this niche. (The JACC: Advances focus-issue deadline of 4 January 2027 is too soon for this study.)
- *What could go wrong:* no faculty partner; the study stalls. Mitigation: start with the smallest version (50 questions, three raters).

**Play 7 — AI-ECG and chest-pain triage inside teaching and community programmes, as a studied pilot.**
- *What:* add an AI-ECG component to the "First ECG" teaching series for first-contact doctors (file 15) and, later, a protocol-driven screening pilot with a government or NGO partner.
- *Evidence:* EAGLE positive; Kenya validation strong on sensitivity and NPV with PPV of 43%, meaning more than half of positives are false; TRICORDER negative on real-world impact; Spandan evidence small.
- *Cost:* depends on partner; devices in the low tens of thousands of rupees each (not verified).
- *Legal conditions:* CDSCO-licensed device; ethics approval if data are analysed; confirmatory echo pathway arranged before screening starts; not a branded camp (file 15 rates camps the riskiest activity under the NMC Guidelines).
- *Hard to copy because:* it requires a referral pathway and a published protocol, not just a gadget.
- *What could go wrong:* false positives without follow-up echo capacity; false reassurance; device-vendor entanglement. Mitigation: run it as research with counted results.

**Ranking.** Start with plays 1, 2 and 4 plus the charter (section 6): they are cheap, lawful today and build the base. Add play 6 after the IIIT-H course. Treat plays 3, 5 and 7 as second-year programmes that need legal review and partners.

### 6. Guardrails: a "Responsible AI in my practice" charter he could publish

Draft, about one page, for his own site once he has one (factual statement of practice, not a claim of superiority; have the lawyer check it against the NMC Guidelines):

> **How I use artificial intelligence (AI) in my practice**
>
> 1. **I decide; software assists.** No diagnosis, prescription or advice is given to you by AI. I examine you, I decide, and I am responsible.
> 2. **I check everything.** Any note, letter or explanation drafted with AI help is read and corrected by me before it reaches you.
> 3. **I tell you.** When AI has helped to prepare something for you, it says so. You can ask me how it was used.
> 4. **You can say no.** If you prefer that AI is not used in your care, tell me. Your care will not change.
> 5. **Your information is protected.** I share only the minimum information needed, only with tools that keep data secure under a written agreement, and never for advertising. I do not put patient information into public AI chat tools.
> 6. **I use tested tools.** For any AI that reads a test, I use only products licensed for that purpose in India, and I look at the evidence behind them.
> 7. **No artificial me.** I do not use an AI copy of my face or voice. If you see a video of me selling a product or a cure, it is not me.
> 8. **Education is not consultation.** My articles and videos are for general understanding. Any AI help in making them is disclosed where it matters, and I review every word.
> 9. **I keep score.** I keep a log of AI errors I catch, review it regularly, and change or stop a tool that is not safe.
> 10. **I will keep this updated.** Last reviewed: [date]. Dr [name], [degrees], TGMC Reg. No. [number].

Why this builds trust: it converts ICMR's principles (human in the loop, autonomy, accountability), NMC 7.2 and DPDP duties into promises a patient can check. Point 9 commits him to an internal audit, which is also his best protection if something goes wrong.

---

## So what for Dr. Avinash

Prioritised. Effort is his own time unless stated.

| # | Action | When | Effort |
|---|---|---|---|
| 1 | **Adopt the two-pipeline rule** (content: zero patient data; clinical: governed tools only) and write it into the plan's Rules | Now | 30 minutes |
| 2 | **Enrol in IIIT-H iHub-Data "AI for Medical Professionals"** (next cohort; email programs@ihub-data.iiit.ac.in for dates). Rs 30,000 | Next intake | About 3 hours a week for the course duration |
| 3 | **Draft the charter and the consent wording** (sections 6 and 3.3) in English and Telugu; send both to the healthcare lawyer already recommended in file 02 | Within 4 weeks | 3 hours one-off, plus lawyer review |
| 4 | **Build the patient-explanation template library** (15–20 conditions and procedures, Telugu and English), tested first on invented cases | Months 1–3 | 10 hours one-off, then 2–3 minutes per patient |
| 5 | **Trial a scribe on simulated consultations only** (EkaScribe free tier, 5 a day): 20 mock Telugu-English consultations with a colleague; count errors that would matter clinically. Use on real patients only in his own clinic, or at Apollo with written permission | Months 1–2 | 4 hours one-off |
| 6 | **Start the outcomes registry** with institutional permission; validate any automated extraction on 100 records | Start now; ongoing | 6–10 hours set-up; 30–60 minutes a week |
| 7 | **Build the peer talk "How to judge an AI tool in cardiology"** and offer it to the CSI Telangana chapter and the CSI Digital Technology Council convener | Months 2–4 | 12 hours one-off; 2 hours a month |
| 8 | **Join the ESC e-Cardiology Working Group** (free) and watch the ESC Digital & AI Summit 2026 sessions on ESC 365; consider the ACC Health Care Innovation Section once he holds ACC membership | Month 1 | 1 hour to join; 1 hour a month |
| 9 | **Write one plain-language public piece per quarter on AI and the heart** (for example "Your watch says irregular rhythm: what to do", "Can AI read your ECG?"), in Telugu and English, in the teach-don't-sell lane | From month 3 | 3 hours a quarter |
| 10 | **Start the Telugu Q&A library** (stage 1 of play 3): 3 reviewed questions a week | From month 3 | 2 hours a week |
| 11 | **Propose the Telugu medical-AI evaluation to an IIIT-H faculty member** met through the course | Months 6–9 | 2 hours a week for 6 months |
| 12 | **Vendor due-diligence checklist** for any clinical AI: CDSCO licence number, intended use, Indian validation data, where data is stored, whether data trains the model, processor contract, exit and deletion terms | Before any purchase | 1 hour per product |
| 13 | **Keep a one-page "AI error log"** from the first day of use | Ongoing | 5 minutes a week |

What not to spend on now: HeartFlow-style tools (not available), polygenic or retinal risk tests (research-stage), a talking avatar, Stanford HAILS.

## Risks & things to avoid

- **Hype claims.** "AI-powered cardiologist", "first in Hyderabad", "more accurate than doctors" are superiority and promotional claims under the NMC Guidelines and are not supported by evidence. Say what is done and how it is checked.
- **Patient data in consumer AI chat tools.** A breach of confidentiality today, and of DPDP from 13 May 2027 (penalties up to Rs 250 crore for security failures). Never paste identifiable notes, images or recordings into a public chatbot.
- **Running personal AI tools on Apollo's patients without permission.** The hospital is the data fiduciary; doing so could also sour the exit.
- **An AI avatar or cloned voice of himself.** NMC 7.2(b) risk, deepfake confusion, and no evidence of benefit. Record in his own voice.
- **A public chatbot before the library and user testing exist.** The best evidence (Nature Medicine 2026; ECRI 2026) says this is where harm happens.
- **Automation bias and deskilling.** Read the ECG before looking at the AI output; keep doing unaided reads. The colonoscopy study shows skill loss is real.
- **Unverified scribe notes.** Telugu speech recognition is roughly three times less accurate than Hindi; an unchecked note is a liability document.
- **Vendor entanglement.** Endorsing a product is prohibited (file 02). Paid advisory roles with AI vendors would undermine play 4. If he ever takes one, disclose it and stop teaching on that product.
- **Screening without a pathway.** With a PPV near 43% (Kenya study), most AI-ECG positives are false; screening without confirmatory echo capacity causes anxiety and cost.
- **Treating AI as the message.** His reputation should rest on care, teaching and prevention. AI is a method he is transparent about, not the headline.
- **Volume.** AI makes it easy to publish more than he can read. File 11 notes that frequency can change the regulatory character of content. Keep output at a level he personally reviews.
- **Dated facts.** Several items here will move within months (DPDP phases, CDSCO practice, product availability). Re-check before acting.

## Open questions / gaps

1. **CDSCO guidance primary text** was not read; only two professional summaries. The classification matrix and any transition timeline need the PDF.
2. **India availability and price** of Ultreon/AI-OCT, QFR, Eko, Us2.ai, PMcardio, KardiaMobile and Spandan devices, and any commercial polygenic test, could not be verified. Vendor quotes are needed.
3. **Telugu clinical performance of scribes** (EkaScribe, Augnito, HealthPlix H.A.L.O) is unpublished; whether consultation audio is used for model training is unstated. Needs a hands-on test and written vendor answers.
4. **Indian cardiologists' AI adoption**: no survey found. CSI Digital Technology Council convener, activities and joining route could not be confirmed (csi.org.in unreachable).
5. **Hyderabad ecosystem detail** (T-AIM programmes, T-Hub health cohorts, IIT-H, AIG's AI centre, named IIIT-H faculty working on cardiology signals) was not verified because state and IIIT sub-sites did not resolve.
6. **Legal questions for the lawyer:** whether a retrieval-only education assistant is outside both CDSCO scope and the Telemedicine "counselling" bar; whether an AI-dubbed version of his own voice with a label is acceptable under NMC 7.2(b); DPDP roles and contract terms for a solo clinic; whether any NCDRC order touches AI.
7. **Doctor-clone outcomes:** no safety or outcome data exist for Duan Tao's AQ clone or the 9verse twin; original AFP text was not accessible.
8. **Build cost and architecture** for the retrieval-only Telugu assistant were not researched.
9. **Deepfake incidents involving Indian doctors** and the Telemedicine Guidelines' exact AI wording were recalled from background knowledge and need re-verification.
10. **Dates of the next IIIT-H "AI for Medical Professionals" cohort** and whether clinicians can serve as guest faculty: ask iHub-Data.

## Sources

**Regulation, policy and law**
- ICMR, Ethical Guidelines for Application of AI in Biomedical Research and Healthcare (2023), landing page: https://www.icmr.gov.in/ethical-guidelines-for-application-of-artificial-intelligence-in-biomedical-research-and-healthcare ; PDF: https://www.icmr.gov.in/icmrobject/custom_data/pdf/Ethical-guidelines/Ethical_Guidelines_AI_Healthcare_2023.pdf
- National Law Review, "Code and compliance: decoding India's medical device software guidance" (3 Aug 2026): https://natlawreview.com/article/code-compliance-decoding-indias-medical-device-software-guidance
- Emergo by UL, "India CDSCO finalizes guidance for medical device software" (30 July 2026): https://www.emergobyul.com/news/india-cdsco-finalizes-guidance-medical-device-software
- Telemedicine Practice Guidelines 2020, official PDF (blocked this session): https://www.mohfw.gov.in/pdf/Telemedicine.pdf ; quotation taken from: https://pmc.ncbi.nlm.nih.gov/articles/PMC7398026/
- AZB & Partners, DPDP framework comes into effect: https://www.azbpartners.com/bank/update-indias-digital-personal-data-protection-framework-comes-into-effect/
- NMC Guidelines on Ethical Advertising and Public Communication (6 Oct 2026): https://medicaldialogues.in/pdf_upload/2026/10/07/nmc-guidelines-on-ethical-advertising-and-public-communication-478642.pdf (analysed in files 02 and 11 of this folder)
- Medical Dialogues, SAHI and BODH launch (18 Feb 2026): https://medicaldialogues.in/amp/news/health/sahi-bodh-initiatives-launched-to-promote-safe-transparent-and-accountable-ai-in-healthcare-164936
- ASCI, Guidelines for Responsible Labelling of Synthetically Generated Content in Advertising (17 Sept 2026): https://www.ascionline.in/wp-content/uploads/2026/09/Guidelines-for-Responsible-Labelling-of-Synthetically-Generated-Content-in-Advertising.pdf
- Legal500 (via Mondaq), IT intermediary rules amended, AI synthetic content: https://www.legal500.com/intelligence/india/technology/india-it-intermediary-rules-amended-%E2%80%93-new-obligations-for-ai-synthetic-content
- Shardul Amarchand Mangaldas, "Reforming India's AI Liability Regime: A Comparative Perspective" (Feb 2026): https://www.amsshardul.com/wp-content/uploads/2026/02/Reforming-Indias-Ai-Liability-Regime_-A-Comparative-Perspective.pdf
- Jus Corpus, "Medical AI and the standard of care: should Indian negligence law evolve?" (9 Sept 2026): https://www.juscorpus.com/medical-ai-and-the-standard-of-care-should-indian-negligence-law-evolve/
- WHO, Ethics and governance of AI for health: guidance on large multi-modal models: https://www.who.int/publications/i/item/9789240084759
- TechCrunch, WhatsApp bars general-purpose chatbots (18 Oct 2025): https://techcrunch.com/2025/10/18/whatssapp-changes-its-terms-to-bar-general-purpose-chatbots-from-its-platform/
- YouTube Help, automatic dubbing: https://support.google.com/youtube/answer/15569972?hl=en ; altered or synthetic content disclosure: https://support.google.com/youtube/answer/14328491?hl=en

**Trials and studies (PubMed)**
- EAGLE, AI-ECG for low EF (Nat Med 2021): https://pubmed.ncbi.nlm.nih.gov/33958795/
- AI-ECG and LVSD in Kenya (JAMA Cardiol 2026): https://pubmed.ncbi.nlm.nih.gov/42090146/
- Narayana Health AI-ECG pre-echo triage (Eur Heart J Digit Health 2026): https://pubmed.ncbi.nlm.nih.gov/42305247/
- TRICORDER AI stethoscope trial (Lancet 2026): https://pubmed.ncbi.nlm.nih.gov/41619752/
- PMcardio Queen of Hearts registry (JACC Cardiovasc Interv 2026): https://pubmed.ncbi.nlm.nih.gov/41158088/
- Spandan validation (Cardiol Res 2025): https://pubmed.ncbi.nlm.nih.gov/40370630/ ; Spandan Ultra 12L (2026): https://pubmed.ncbi.nlm.nih.gov/41916329/
- Apple Heart Study (NEJM 2019): https://pubmed.ncbi.nlm.nih.gov/31722151/
- Us2.ai multicohort validation (Lancet Digit Health 2022): https://pubmed.ncbi.nlm.nih.gov/34863649/
- PRECISE (JAMA Cardiol 2023): https://pubmed.ncbi.nlm.nih.gov/37610731/
- CT-FFR in Asia and the US, 2025 status (Korean J Radiol 2026): https://pubmed.ncbi.nlm.nih.gov/41494674/
- FAVOR III Europe (Lancet 2024): https://pubmed.ncbi.nlm.nih.gov/39488224/ ; FAVOR III China (Lancet 2021): https://pubmed.ncbi.nlm.nih.gov/34742368/
- ILUMIEN IV (NEJM 2023): https://pubmed.ncbi.nlm.nih.gov/37634188/
- AICVD (Fam Med Community Health 2024): https://pubmed.ncbi.nlm.nih.gov/38238156/
- South Asian CAD polygenic score (JACC 2020): https://pubmed.ncbi.nlm.nih.gov/32762905/ ; PRS in Asian Indians (2024): https://pubmed.ncbi.nlm.nih.gov/38658478/
- Reti-CVD validation (BMC Med 2023): https://pubmed.ncbi.nlm.nih.gov/36691041/ ; pivotal study (JAMIA 2023): https://pubmed.ncbi.nlm.nih.gov/37847669/
- mWellcare (Circulation 2019): https://pubmed.ncbi.nlm.nih.gov/30586732/
- Suhriday heart-failure app pilot (BMJ Open 2022): https://pubmed.ncbi.nlm.nih.gov/36002201/ ; task-sharing mHealth RCT (2023): https://pubmed.ncbi.nlm.nih.gov/38510948/
- Digital cardiac rehabilitation review (JACC Asia 2025): https://pubmed.ncbi.nlm.nih.gov/41067820/ ; TaCT (2025): https://pubmed.ncbi.nlm.nih.gov/40917970/ ; SRCardioCare (2026): https://pubmed.ncbi.nlm.nih.gov/41730181/
- Ambient scribe RCTs (NEJM AI, Dec 2025): https://pubmed.ncbi.nlm.nih.gov/41497288/ and https://pubmed.ncbi.nlm.nih.gov/41625485/
- LLM patient-friendly discharge summaries (JAMA Netw Open 2024): https://pubmed.ncbi.nlm.nih.gov/38466307/
- LLMs as medical assistants for the public (Nat Med 2026): https://pubmed.ncbi.nlm.nih.gov/41663592/
- Endoscopist deskilling after AI exposure (Lancet Gastroenterol Hepatol 2025): https://pubmed.ncbi.nlm.nih.gov/40816301/
- AI device recalls (JAMA Netw Open 2026): https://pubmed.ncbi.nlm.nih.gov/42275062/ ; (JAMA Health Forum 2025): https://pubmed.ncbi.nlm.nih.gov/40844774/
- Indian doctors' AI knowledge survey (Bioinformation 2025): https://pmc.ncbi.nlm.nih.gov/articles/PMC12357720/

**Products and vendors (vendor claims unless stated)**
- Tricog: https://www.tricog.com/
- Anumana: https://anumana.ai/
- AliveCor India: https://alivecor.com/in ; https://alivecor.com/in/products/kardiamobile
- SunFox Spandan: https://sunfox.in/ ; https://sunfox.in/products/spandan
- Apple Watch feature availability (India): https://www.apple.com/in/watchos/feature-availability/
- Samsung Health Monitor (India): https://www.samsung.com/in/apps/samsung-health-monitor/
- Dozee: https://dozeehealth.ai/
- Us2.ai: https://us2.ai/
- EkaScribe: https://ekascribe.ai/ ; Eka developer models: https://developer.eka.care/eka-medai/models ; Parrotlet v2 launch (17 Feb 2026): https://indiamedtoday.com/eka-care-launches-parrotlet-a-v2-for-real-time-indian-medical-transcription/ ; Parrotlet-a 2.5 Pro commentary (15 Oct 2026): https://www.iatrox.com/blog/ekascribe-parrotlet-a-2-5-pro-multilingual-medical-scribing
- Augnito: https://augnito.ai/ ; HealthPlix: https://healthplix.com/
- Voice of India ASR benchmark (Josh Talks, Aug 2026): https://elevenlabsreport.ai.joshtalks.com/

**Hyderabad and India news**
- Narayana Health AI-ECG (Telangana Today, 7 Aug 2025): https://telanganatoday.com/narayana-healths-ai-becomes-indias-first-to-detect-heart-failure-in-a-flash
- Kardi Ai launch in Hyderabad (Telangana Today, Sept 2026): https://telanganatoday.com/ai-powered-cardiac-monitoring-technology-to-launch-in-india-on-september-26
- Apollo cardiovascular risk tool (Telangana Today, 30 Sept 2021): https://telanganatoday.com/apollo-hospitals-launches-ai-tool-that-can-predict-risk-of-heart-ailments
- Apollo Financial District smart hospital (29 Apr 2026): https://indiamedtoday.com/apollo-hospitals-launches-76th-facility-400-bed-smart-hospital-in-hyderabad-financial-district/
- Apollo–Medtronic AI-enabled ICU, Jubilee Hills (16 July 2026): https://www.indianpharmapost.com/hospitals/apollo-hospitals-medtronic-launch-ai-enabled-futuristic-icu-in-hyderabad-20948
- AIG Banjara Hills facility: https://www.digitalhealthnews.com/aig-hospital-unveils-new-ai-powered-multispecialty-facility-in-banjara-hills
- Star Hospitals blog (Oct 2025): https://starhospitals.in/blogs/artificial-intelligence-in-cardiology
- Fortis Noida "AI-powered" cath lab (2023): https://www.biospectrumindia.com/news/110/23975/uttar-pradeshs-first-ai-powered-advanced-state-of-the-art-cath-lab-launches-at-fortis-noida.html
- Medical Dialogues, vision statement for an AI-ready Indian medical system (6 Oct 2026): https://medicaldialogues.in/ai-medical-innovation/vision-statement-for-an-ai-ready-indian-medical-system-180628

**Doctor "digital twins", chatbots and safety**
- Medical Economics, "Should we be worried when Dr. Jones hires the AI version of himself?" (2 Oct 2026): https://www.medicaleconomics.com/view/should-we-be-worried-when-dr-jones-hires-the-ai-version-of-himself-
- Duan Tao / AQ (secondary summary, 5 Mar 2026): https://rudevulture.com/?p=7780 ; Malay Mail (AFP, 4 Mar 2026; 403 this session): https://www.malaymail.com/news/life/2026/03/04/this-shanghai-doctor-has-160000-patients-and-he-has-never-met-any-of-them/211133 ; background: https://ucstrategies.com/news/china-is-rolling-out-ai-doctor-clones-and-millions-are-already-using-them/
- 9verse AI digital twin of Dr Mansoor Anwar Habib (28 Aug 2025): https://www.rtinsights.com/first-digital-twins-of-patients-now-a-digital-twin-of-a-doctor/
- CU Anschutz, "Just because we can do something with AI, does it mean we should?" (15 Aug 2025): https://news.cuanschutz.edu/news-stories/just-because-we-can-do-something-with-ai-does-it-mean-we-should
- ECRI, misuse of AI chatbots tops 2026 hazards (21 Jan 2026): https://home.ecri.org/blogs/ecri-news/misuse-of-ai-chatbots-tops-annual-list-of-health-technology-hazards
- ECRI, AI error reporting and survey (25 Aug 2026): https://home.ecri.org/blogs/ecri-news/ecri-expands-problem-reporting-network-and-calls-for-more-data-on-ai-errors-in-patient-care
- Elsevier, Clinician of the Future 2025: https://www.elsevier.com/insights/clinician-of-the-future/2025

**Societies, courses, ecosystem**
- IIIT-H iHub-Data: https://ihub-data.ai/ ; AI for Medical Professionals 2026: https://ihub-data.ai/archives/courses/ai-for-medical-professionals-2026/
- ESC digital health and AI: https://www.escardio.org/topics/digital-health-ai/ ; ESC Digital & AI Summit: https://www.escardio.org/events/congresses/digital-ai-summit/
- ACC Health Care Innovation Member Section: https://www.acc.org/Membership/Sections-and-Councils/Health-Care-Innovation-Section
- Stanford AIMI education: https://aimi.stanford.edu/education ; HAILS: https://aimi.stanford.edu/hails ; Coursera AI in Healthcare specialization: https://www.coursera.org/specializations/ai-healthcare

**Internal cross-references:** `02-regulation-ethics-india.md`, `04-hyderabad-landscape-telugu-media.md`, `07-academic-professional-standing.md`, `09-community-impact.md`, `11-nmc-guidelines-operating-manual.md`, `15-community-programmes-executable.md`.
