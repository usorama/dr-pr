# 22 — Does it work, what can go wrong, and how will we know? The evidence base, risk register and measurement system for a doctor's public teaching

**Research date:** 12 November 2026. **Method:** about 45 direct queries to the Europe PMC and PubMed APIs (abstracts and, where open, full text), about 30 direct page fetches, and 16 web searches (four over the 12-search budget; the extra ones were spent on the named court cases). Pages that refused access (HTTP 403): the GMC guidance page and PDF, COPE, bmj.com, Stan Ventures. Where a primary page was blocked the claim rests on a secondary source and says so. **Tags:** confidence High / Medium / Low; **[PK]** = stated from prior knowledge, not re-verified this session; "file NN" = an earlier report in this folder.

## Executive summary

1. **Public teaching works for some things and not others.** It reliably buys attention and modest gains in knowledge and belief accuracy (corrections on social media: d = 0.40 across 24 studies, stronger when an expert corrects). It changes behaviour or a biomarker only when it is interactive and tied to measurement and follow-up. For academic standing the randomised evidence is split: two trials show a citation gain (ESC journals 1.12 times; thoracic surgery +3.1 vs +0.7 citations at one year), four show no gain in page views, downloads or citations. Plan for teaching and scholarship to do the work; treat posting as distribution.
2. **Doctors are part of the misinformation problem, and AI makes it easier to join it.** In 105 YouTube videos on cholesterol treatment (32.6 million views), independent doctors were the commonest publishers and had the highest misinformation rate (29%). ChatGPT-3.5 fabricated 47–55% of the references it supplied in two studies. The quality system in section 4 is therefore the core of the plan, not an appendix.
3. **Every norm on ghost-writing and AI says the same three things:** a named human is accountable, help is disclosed, a machine is never the author. Disclosure has a small measurable cost (people rate a doctor who mentions AI slightly lower, d about 0.2–0.3) and concealment has a large tail risk. The workable line is "written by me, edited with help", clinical claims and opinions his own, and no clone of his face or voice.
4. **The five risks that matter most** are an over-specific "composite" case that someone recognises, an error (his own or an AI's) reaching the public, conflict with Apollo before he leaves, a legal threat from a company or alternative-medicine promoter (the TheLiverDoc matter cost an account suspension, nine hidden posts, a gag still reported in July 2024 and a withdrawn paper; no final outcome found), and burnout. A regulator complaint is unlikely for a quiet educational channel but costly. Deepfake remedies have improved: a two-hour takedown duty for impersonation since February 2026 and a permanent decree for Dr Devi Shetty in October 2026.
5. **Measurement:** a KPI tree of about 30 measures across the three lighthouse rings, plus foundations and guardrails, with denominators shown, no patient-acquisition metric anywhere, a one-page quarterly review, a five-person advisory circle, written decision rights, thirteen stop rules and an annual public "impact and corrections" note.

---

## Findings

### 1. Evidence that physician public communication achieves anything

#### 1.0 Verdict table

| Outcome | What the evidence supports | Strength |
|---|---|---|
| Attention, reach | Yes. Professional content is watched; professionals' videos score higher on quality scales in most audits | High |
| Knowledge, belief accuracy | Yes, modestly; effects fade and need repetition | High |
| Behaviour, biomarkers | Only for interactive programmes with measurement and human follow-up; passive content alone, rarely | High (file 19 and Cochrane) |
| Trust and choice of doctor | Online presence and educational output are associated with more consultations in platform studies; survey evidence in India is thin; unprofessional posts reduce trust | Medium |
| Referrals, practice growth | No trial. Word of mouth and referring doctors still dominate | Low–Medium |
| Citations | Contested: 2 positive trials, 4 null | Medium |
| Countering misinformation | Corrections work on average; "backfire" is rare; decay is the real problem | High |
| The doctor's own wellbeing | Meaningful work protects against burnout; a quarter to two-thirds of visible doctors report online attacks, women and minorities far more | Medium–High (US data; no Indian data found) |

#### 1.1 Patient knowledge and behaviour

- **Cochrane review of interactive social media (2021):** 88 studies, 871,378 participants, 86% from high-income countries. Interactive social-media interventions "may increase physical activity and medical screening tests" but showed "little to no effect" on diet or tobacco; small positive effects on weight and resting heart rate; wellbeing improved (SMD 0.46, low certainty). No included study reported adverse effects such as privacy problems, which means they were not looked for. PMID 34057201. **High.**
- **Low- and middle-income countries:** a systematic review found 33 eligible social-media behaviour-change studies; 22 concluded the intervention worked, but only 13 quantified engagement and few used a behaviour-change model. PMID 35436220. **Medium** (weak primary studies).
- **Mass media:** the Lancet review by Wakefield and colleagues concluded that campaigns "can produce positive changes or prevent negative changes in health-related behaviours across large populations", in competition with marketing, norms and habit. PMID 20933263. **High**, old (2010).
- **Indian and cardiovascular trials:** file 19 sets nine negative or neutral education-only trials (DISHA, SMARThealth West Godavari, mWellcare, TEXTMEDS and others) against the ones that worked (PROLIFIC in Kerala: 64% vs 46% reaching three of four targets at two years; IHCI: 44% control among those under care). The difference was a measurement the person owns, a route to treatment, repeated human contact and a family or peer unit. Not repeated here.
- **Exposure to misinformation moves beliefs by about the same amount that correction does.** Two meta-analyses of randomised trials: g = 0.24 (14 studies, N = 18,115; longer messages g = 0.41) and d = 0.28 (28 studies, n = 8,752). PMID 40708117; 39104361. **High.** Implication: the opposition's long videos are more persuasive than its one-liners, and a doctor's short, accurate, repeated messages are fighting on equal terms, not losing.

#### 1.2 Trust and choice of doctor

- **Platform data from China (haodf.com and similar):** physicians' free and paid educational articles were associated with more patient visits and consultations (PMID 36419984); in 1,295 doctors, topic focus, readability and variety of form in their "popular science" articles were each positively associated with performance on the platform (PMID 36553956); in 2,676 physicians, how widely read and well received their articles were predicted consultations (PMID 39494068). **Medium:** observational, one country, a marketplace in which articles and bookings sit on the same page. They show association, not that writing causes bookings.
- **Unprofessional posts cost trust.** In a survey of 491 patients in three US cities, most said they would trust their physician less after racist comments, a disrespectful patient narrative, a photograph appearing intoxicated, or profanity. PMID 31663810. **Medium–High.**
- **Orthopaedic patients, US (n = 329):** how they reached the surgeon: primary-care physician 45.0%, insurer 14.3%, friend 12.8%, emergency room 8.8%, internet search or website 8.5%; 39.5% searched online before the first visit. PMID 35044319. **High** for that setting.
- File 06 already records the Edelman figures ("my doctor" trusted by 80% in 2026) and the rater8 vendor survey (35% of US adults say they have chosen a physician on social-media presence). Not repeated.

#### 1.3 Referrals and practice growth

- **No controlled study was found** that links a physician's public education to referral volume or practice growth. The literature is opinion pieces and marketing surveys (for example PMID 25111280, a 2014 commentary). **Could not verify any causal estimate.**
- The honest reading for an interventional cardiologist: emergency work arrives through emergency rooms and referring doctors, elective work through word of mouth (see the EY-FICCI figures in 1.7). Public teaching mainly changes who has heard of him among "hidden buyers" (file 06): referring doctors, journalists, programme committees. That is why this plan sets no patient-volume KPI.

#### 1.4 Academic impact: tweets, altmetrics and citations

| Trial | Design | Result | Source |
|---|---|---|---|
| ESC Journals Randomized Study, final | 694 papers in ESC journals (Mar 2018–May 2019) randomised to promotion from ESC Twitter channels or none; median follow-up 994 days | Citation rate ratio **1.12** (95% CI 1.08–1.15). The preliminary analysis of 536 papers had reported 1.43 (1.29–1.58), so the effect shrank with follow-up. An extended-follow-up note appeared in Eur Heart J on 9 Feb 2026 (no abstract; not read) | PMID 35567549; 32306033; 40981751 |
| Thoracic Surgery Social Media Network (TSSMN) | 112 articles, 1:1, tweeted by TSSMN delegates or not; 1 year | Altmetric 9.4 vs 1.0; change in citations **+3.1 vs +0.7** (P < .001); randomisation to tweeting OR 9.50 for citation | PMID 32504611 |
| Circulation (first trial) | 243 articles, journal Facebook and Twitter posts vs none | 30-day page views 409 vs 392, P = 0.80 | PMID 25406308 |
| Circulation (higher intensity) | 152 articles; posts in triplicate, boosted, larger follower base | Stopped for futility; 499.5 vs 450.5 page views, P = 0.38 | PMID 27121850 |
| International Journal of Public Health | 130 papers, blog + Twitter + Facebook vs none; follow-up extended to 24 months | No difference in downloads (P = 0.72) or citations (P = 0.30) | PMID 27193574; 33159529 |
| Branch et al. (life sciences) | 110 articles tweeted by prominent science communicators, four matched controls each, three years | Downloads 2.6–3.9 times higher at first; Altmetric +81%; citations +7% (Web of Science) and +12% (Scholar), **not significant** (p > 0.15) | PMID 38507397 |

Reading: promotion reliably raises attention metrics. Citation gains appear when many specialists amplify within a specialty network (ESC, TSSMN) and are small once follow-up is long. Journal brand accounts posting alone, and individual scientists tweeting papers, showed nothing. For him: join the specialty conversation around his own papers and others', expect a modest lift at best, and never count on it. Among cardiologists, follower counts track posting activity rather than citations (file 05). **High** that this is the state of the trials.

#### 1.5 Countering misinformation

- **Corrections work on average.** Meta-analysis of attempts to correct health misinformation on social media: k = 24, N = 6,086, d = 0.40 (0.25–0.55); stronger when people care about the topic, when the misinformation came from news organisations rather than peers, and when **experts** rather than non-experts did the debunking; publication bias could not be excluded. PMID 32762260. **High.**
- **Debunking is partial.** Meta-analysis of 52 studies (N = 6,878): debunking effects d = 1.14–1.33, but misinformation persisted after debunking (d = 0.75–1.06); persistence was stronger when audiences had generated reasons supporting the myth. PMID 28895452. **High.**
- **The backfire effect as it now stands.** Nyhan's 2021 review: the original finding was over-generalised; "an emerging research consensus finds that corrective information is typically at least somewhat effective"; the problem is that effects "often do not last or accumulate" and are overwhelmed by cues from elites and media. PMID 33837144. File 14 records the Debunking Handbook 2020 and Swire-Thompson 2020 to the same effect. **High.**
- **Decay, measured.** Preregistered experiments in the US, Great Britain and Canada: fact-checks reduced COVID-19 misperceptions, most among the most vulnerable groups, but the reductions "do not persist over time in panel data even after repeated exposure". PMID 35115678. **High.** Implication: one myth-busting video is not a result; a standing weekly format is.
- **Peer correction works too.** In a simulated feed, corrections by other users were as effective as algorithmic ones (PMID 28622038). **High.**
- **WHO infodemic review (Bulletin of the WHO, 2022):** 31 systematic reviews; the share of health posts that were misinformation ranged from 0.2% to 28.8% by topic and platform; consequences include vaccine hesitancy and delayed care. PMID 36062247. **High.**
- **Prebunking:** covered in file 14 (Roozenbeek 2022). No new cardiology-specific prebunking trial found.

**Quality of cardiovascular content on video platforms**

| Topic, platform | Finding | Source |
|---|---|---|
| Cholesterol treatment, YouTube (105 videos, 32.6 million views, over 50,000 comments) | 18% rejected cholesterol-lowering drugs; 21% contained misinformation; alternative-therapy videos carried marketing in 70% and misinformation in 43%. **Independent doctors published 55.2% of videos and had the highest misinformation rate (29%)** | Eur J Cardiovasc Nurs 2026, PMID 41612669 |
| Myocardial infarction, YouTube (Indian authors, English search) | 33.3% uploaded by doctors, 7.8% by health organisations; 15.7% promotional; authors rate quality as high on GQS | PMID 37692661 (Cureus; weak design) |
| Angiography and angioplasty, YouTube (57 videos, Indian authors) | Most uploaded by hospitals and non-doctors; higher quality and reliability from doctors and organisations | PMID 37885539 (Cureus) |
| Hypertension, YouTube | 33.3% by physicians; median GQS 4; "usually accurate" but not comprehensive, possibly biased | PMID 40050348 |
| Coronary heart disease, TikTok (145 videos) | 88.3% by health professionals, yet median DISCERN 27, JAMA 2, GQS 2: low | PMID 39226540 |
| CPR, YouTube / Bilibili / TikTok (239 videos) | YouTube highest quality, especially professionals' videos; videos by professional individuals drew the most interactions | PMID 41030356 |
| Hindi YouTube, COVID-19 vaccine (top 50) | 48% by professionals, 46% by news organisations; judged a valid source | PMID 40124832 |
| Hindi YouTube, breast cancer (top 50) | Professionals' videos scored higher than consumers' on all scales, "limited in numbers" | PMID 36861697 |

- **Telugu or any Indian-language audit of heart content: none found** in Europe PMC (searched Telugu, Tamil, Hindi, "regional language" with YouTube and cardiac terms). File 13's observation that Telugu heart content is dominated by naturopathy channels has no peer-reviewed counterpart. This is a publishable gap he could fill (see "So what", item 14). **High** that nothing is indexed.
- Two lessons: being a doctor does not guarantee accuracy (the cholesterol study), and short video compresses content below the quality threshold even when professionals make it (the TikTok study). Both argue for the editorial standard in section 4.

#### 1.6 Physician wellbeing, meaning and harassment

- **Meaning protects.** In 465 academic internists, those spending under 20% of their time on the activity they found most meaningful had burnout rates of 53.8% vs 29.9%; it was the strongest predictor (OR 2.75). Education was the most meaningful activity for 9%. PMID 19468093. **High**, US, 2007. For a doctor who finds teaching meaningful, protected teaching time is protective; for one who finds it a chore, it is a load. His weekly energy rating (guardrail G5) is how the plan finds out which it is.
- **Burnout in Indian health professionals:** 15 studies, 3,845 people; pooled prevalence 24% emotional exhaustion, 27% depersonalisation, 23% low personal accomplishment. PMID 32346250. **High.**
- **Harassment, pre-pandemic (JAMA Internal Medicine 2021):** 464 US physicians; 23.3% reported being personally attacked on social media, with no sex difference (24.2% women, 21.9% men); online sexual harassment 16.4% of women vs 1.5% of men. Attacks followed advocacy (vaccines 10 of 21 advocacy comments, guns, abortion, smoking); forms included death threats, contacting employers and certifying boards, fake negative reviews and doxxing. PMID 33393965. **High.**
- **Harassment, pandemic (JAMA Network Open 2023):** 359 physicians, scientists and trainees; 66% reported harassment, 88% of those because of advocacy; 64% over COVID-19 comments; sexual harassment 31% overall, 41% of women vs 14% of men; harassment on the basis of race or ethnicity reported by 82% of harassed Black respondents, 52% of Asian, 15% of White. PMID 37314808. **High**; the sample was recruited among people who had experienced harassment, so 66% is not a population rate.
- **Indian data on online harassment of doctors: none found.** The nearest evidence is workplace violence (1.7). **Could not verify.**

#### 1.7 India-specific data

| Question | Finding | Source, confidence |
|---|---|---|
| How patients choose | FICCI–EY-Parthenon report (9 Oct 2025; over 1,000 patient surveys): 83% seek objective information to guide choices, only about one-third can easily get it; they rely on **word of mouth (79%)** and **brand or doctor reputation (60%)**; nearly 90% would pay more for certified quality | EY press release; Medium (denominators not stated) |
| Social media and doctor selection | Bengaluru tertiary-hospital outpatients' caregivers (n = 130, purposive sample, 2026): used for health information WhatsApp 82%, YouTube 76%, Facebook 68%; **58% said social media influenced doctor selection**; 64% lifestyle changes; 49% had met misleading health information | IJCMPH 2026; Low–Medium (small, single site) |
| Trust in doctors | Chennai tertiary centre (n = 359, 2021): high trust in doctors in more than 80%; trust rose with age and **fell with education** (β = −0.42); communication difficulty reduced trust (β = −0.63) | PMID 34161383; Medium |
| Trust, system level | Kane and Calnan (2017): "a massive erosion of trust" in the profession from stewardship failures; argue for nurturing interpersonal trust alongside regulation | PMID 28005537; opinion |
| Violence, 12-month | 47.0% of 151 doctors in a Delhi tertiary hospital (87.3% verbal, 8.6% physical); 34.5% of 394 health workers at another tertiary hospital, with only 23.5% of incidents reported | PMID 28050406; 31065192; Medium |
| Violence, ever | 77.3% of 617 doctors in a nationwide online survey (Nov 2019–Apr 2020); triggers: perceived non-improvement (40.0%) and perceived wrong treatment (37.3%); relatives were perpetrators in 82.2%; doctors afterwards did fewer surgical and emergency cases and ordered more investigations and referrals | PMID 32946495; Medium (self-selected) |
| Safety at night | IMA survey after the RG Kar case (2024): 3,885 doctors from 22 states; 35.5% felt unsafe or very unsafe on night duty; about 45% had no duty room | ThePrint, Business Standard; Medium (open online form) |
| The often-quoted "75% of doctors have faced violence" (IMA) | Primary source **could not be verified** | — |
| National, representative data on where Indians get health information (WhatsApp, YouTube) | **Not found.** Only small single-site studies | — |
| Telangana law | A state Act of 2008 on violence against medicare service persons and institutions applies **[PK, not re-verified]** | Low |

Reading for him: trust in one's own doctor remains high but is lower among the educated, urban audience his English content will reach; choice still runs on word of mouth; violence is triggered by perceived non-improvement and perceived wrong treatment, which is exactly what honest expectation-setting ("After the stent") addresses.

---

### 2. Ghost-writing, editing and AI assistance

#### 2.1 Norms and positions

| Body | Position | Source, confidence |
|---|---|---|
| **ICMJE** (page © 2026) | Authorship needs all four: substantial contribution; drafting or critical review; final approval; accountability for all aspects. "Writing assistance, technical editing, language editing, and proofreading" alone do not qualify and should be acknowledged. Journals "should require authors to disclose whether they used artificial intelligence (AI)-assisted technologies"; chatbots "should not be listed as authors because they cannot be responsible for the accuracy, integrity, and originality of the work"; "humans are responsible for any submitted material that included the use of AI-assisted technologies"; AI "can generate authoritative-sounding output that can be incorrect, incomplete, or biased" | icmje.org (fetched); High |
| **WAME** (revised 31 May 2023) | "Chatbots cannot be authors." "Authors should be transparent when chatbots are used and provide information about how they were used." "Authors are responsible for material provided by a chatbot in their paper." WAME also has a separate statement on ghost writing initiated by commercial companies (title seen; text not read) | wame.org (fetched); High |
| **COPE** (position statement, Feb 2023) | AI tools cannot be authors; use must be disclosed; authors remain fully responsible | Page returned 403; **[PK]**, Medium |
| **AMA Code, Opinion 2.3.2** | Physicians "cannot realistically separate their personal and professional personas entirely online"; must not publish patient information without appropriate consent; "Publicly disclose any financial interests related to their social media content"; "ensure that such information is useful and accurate based on professional medical judgment" | code-medical-ethics.ama-assn.org (fetched); High |
| **AMA deepfake framework** (spring 2026) | Seven principles: physician identity as a protected right; prohibition of deceptive medical impersonation; informed, opt-in, revocable consent; mandatory transparency and labelling; shared responsibility; enforcement and practical remedies; minimal administrative burden. Advisory, not law | Secondary coverage and JMIR news item (PMID 42361790); Medium |
| **GMC, "Using social media as a medical professional"** (in effect 30 Jan 2024) | As quoted by a secondary guide: para 11, "take reasonable steps to make sure that the information you communicate on social media as a medical professional is not false or misleading" and do not "misrepresent your experience and qualifications"; para 12, be "open and honest about any interests you have that may influence (or could be seen to influence) the recommendations you make"; para 14, do not use social media "to abuse, discriminate against, bully, harass or deliberately target any individual or group"; para 20, "maintain patient confidentiality" and do not "disclose identifiable information about patients, unless you have explicit consent"; good practice to identify yourself "if you're using social media to comment on health or healthcare issues" | GMC page and PDF returned 403; wording from Bridgehead Communications guide (Aug 2026) and search snippets; **Medium**, paragraph numbers to be re-checked |
| **BMA** (updated 28 Aug 2024) | "Your privacy (and confidentiality) can never be guaranteed - even in closed groups or forums"; "You could run into legal issues like defamation or contempt of court" | bma.org.uk (fetched); High |
| **NHS England / RCP** guidance specific to ghost-writing or AI-drafted public content | **Could not find or verify** | — |
| **NMC Guidelines, 6 Oct 2026** | cl. 4.4: publishing through "a digital platform, third party, advertising agency, influencer or other intermediary shall not, by itself, absolve an RMP" from responsibility for content "authorized, commissioned, sponsored, adopted or knowingly permitted"; cl. 7.2: AI-generated promotional content must carry a source mark; 7.2(b): no synthetic "representation purporting to be that of an actual patient, RMP or other person"; 7.2(c): disclose AI where its artificial nature "may reasonably be material to the audience's understanding"; 7.2(d): no patient data into AI | File 11 (primary text read there); High |
| **Other Indian positions** on ghost-writing of a doctor's public content | None found beyond the NMC text. ICMR's research-integrity policy addresses ghost authorship in research **[PK, not re-verified]** | Low |

No body bans editorial help. All of them place responsibility on the named person and treat hidden authorship, not assistance, as the wrong.

#### 2.2 Public expectations about authenticity

- **A label of AI involvement lowers ratings even when a doctor supervises.** Two preregistered studies (n = 2,280): identical medical advice labelled "AI" or "human + AI" was rated less reliable and less empathetic than advice labelled "human", and people were less willing to follow it. Nature Medicine 2024, PMID 39054373. **High.**
- **Doctors who mention AI are rated lower.** 1,276 US adults saw a physician's advertisement with or without a line about AI use: competence 3.85 (control) vs 3.71 / 3.66 / 3.58 (administrative / diagnostic / therapeutic AI); trustworthiness 3.88 vs 3.66 / 3.62 / 3.61; willingness to book 3.61 vs 3.32 / 3.16 / 3.15; effect sizes d = 0.16–0.34. JAMA Network Open 2025, PMID 40674054. **High.** Even administrative AI carried the penalty.
- **Ghost-writing damages trust when discovered.** The documented cases are from journals: litigation documents showed medical-writing companies producing ghost-written manuscripts to promote hormone therapy (PLoS Medicine 2010, PMID 20838656); a 2016 review described the erosion of public trust in physicians (PMID 27354171); Naomi Oreskes argued in Science in 2025 that rebuilding trust "requires confronting the harms of ghostwriting" (PMID 41166476; title only). **Medium–High.**
- **No peer-reviewed study of ghost-written social-media content by doctors was found.** **Could not verify** how Indian audiences react to "edited with help" disclosures.

What follows from this: (a) do not lead with AI in public messaging about himself; the "AI edge" (file 18) should be shown through verified outputs and a published charter, not through an "AI-powered doctor" label; (b) disclose assistance once, plainly, in a standing place, and per piece only where the artificial nature is material (an AI image, AI dubbing); (c) make the human accountability visible, because that is what the penalty is about.

#### 2.3 A disclosure practice that preserves trust

**Standing page, "How this is made"** (English and Telugu), linked from every profile:

> I am Dr Avinash Pathuri (Andhra Pradesh Medical Council reg. no. 74749). Everything published here under my name is my own view and I have checked every medical statement in it against the source cited. A colleague, [name], edits my drafts for clarity and manages publishing. We use software, including AI tools, for transcription, translation drafts, subtitles and first drafts of some explanations. No patient information is ever put into these tools. Nothing is published until I have read and approved it. If you find an error, write to [address]; corrections are listed with dates at [link].

**Per-piece line:** "Written by Dr Avinash Pathuri. Edited by [name]. Medically checked on [date]; next review due [date]." Add "Illustration generated with AI" or "Subtitles machine-translated and checked by [Telugu editor]" where true.

**What must be his own, without exception**

| His alone | May be drafted or handled by the friend or AI, then approved by him | Never |
|---|---|---|
| Every clinical claim, number and recommendation | Structure, headline, shortening, plain-language rewrite | The friend replying as him to a clinical question, a peer or a journalist |
| Every opinion, and any criticism of a practice, product or person | Transcription, subtitles, translation drafts (Telugu editor checks) | An AI persona, avatar or cloned voice (NMC 7.2(b); file 18) |
| First-person experience ("in my practice I see…") | Graphics, thumbnails (no fear imagery), scheduling | Invented or "typical" patient quotes |
| Apologies, corrections, replies in a controversy | Literature search and a first list of sources (each opened and read by a human) | Any citation supplied by AI and not opened |
| Journal manuscripts (ICMJE: all four criteria; assistance acknowledged) | Reference formatting, language polish, with acknowledgement | Guest or gift authorship in either direction |
| The final "publish" approval, logged with date | Moderation of comments to a written script | Deleting critical comments that are civil |

The friend's role should be named publicly. A named editor is ordinary; an anonymous one is what people mean by a ghost.

#### 2.4 Where ghost-written or AI-generated health content backfired

| Case | What happened | Lesson | Source |
|---|---|---|---|
| Men's Journal, Feb 2023 | Its first AI-generated article, on low testosterone, credited to "Men's Fitness Editors" and marked "reviewed and fact-checked by our editorial team"; an endocrinologist (chief of medicine, University of Washington Medical Center) found 18 errors; the piece was substantially rewritten with a partial note | "Reviewed by" is worthless unless a named clinician checked claim by claim | Futurism (fetched); High |
| "Make America Healthy Again" report, May 2025 | A 73-page US government report with over 500 citations; seven cited papers did not exist and dozens more had errors; listed authors told reporters they had not written them; the references were removed and the errors called "formatting issues". The article fetched does not itself attribute this to AI | A fabricated citation is found by the first person who e-mails the author. Open every source | NOTUS via Washington Sun (fetched); High |
| ChatGPT-generated medical references | 30 short medical papers by ChatGPT-3.5: of 115 references, 47% fabricated, 46% authentic but inaccurate, 7% authentic and accurate. Separate study: 55% of GPT-3.5 and 18% of GPT-4 citations fabricated | Newer models fabricate less, not never. The citation of record must come from the database, not the model | PMID 37337480; 37679503; High |
| Cholesterol videos by independent doctors | 29% contained misinformation | A medical degree on the thumbnail does not protect the viewer or the doctor | PMID 41612669; High |
| Dr Ed Hope (UK), 2026 | A doctor with about 500,000 followers reported that Google's AI Overview falsely stated he had been suspended by the GMC | AI systems now write a doctor's reputation; the monthly AI-assistant accuracy test in file 10 is a defence, not vanity | Search summary only (page 403); Low–Medium |
| "Deepfake doctor" chatbot | BMJ news, May 2026: a chatbot presented as a doctor "hit with lawsuit in US" (title only; text not read) | Do not launch a public chatbot under his name (file 18 agrees) | PMID 42114916; Medium |
| Doctors' "AI twins" | See file 18, section 2.4 | — | — |

A clean, documented case of an individual doctor publicly exposed for ghost-written or AI-written social posts was **not found** in one targeted search.

#### 2.5 Deepfakes and impersonation: scale and remedies in India

**Scale.** CBS News (Aug 2025) found over 100 videos from dozens of accounts using fictitious doctors, some with real physicians' identities, mostly on TikTok and Instagram; a named physician-educator found his face with another voice selling a product; YouTube told CBS the flagged videos did not breach its guidelines but that people can request removal of AI content simulating them. BMJ reported in July 2024 on deepfaked doctors in social-media scams (PMID 39019557; text not read). Indian cases (Dr V. Mohan, Dr Devi Shetty, Dr Naresh Trehan, two doctors in Karad) are in file 10, section 6.3. **High.**

**The law as of November 2026**

| Instrument | What it gives him | Source, confidence |
|---|---|---|
| IT (Intermediary Guidelines and Digital Media Ethics Code) Amendment Rules, notified 10 Feb 2026, in force 20 Feb 2026 | Defines "synthetically generated information" (audio, visual or audio-visual content artificially created or altered so as to appear real; **AI text is outside the definition**; routine good-faith editing, translation and accessibility changes are excluded). Platforms must label it prominently and embed non-removable metadata where feasible; large platforms must obtain a user declaration and verify it. **Timelines: 3 hours** to act on a court order or government notice (was 36); **2 hours** for complaints in high-risk categories, which include **impersonation** and artificially morphed images (was 24); **36 hours** for complaints about content concerning an individual (was 72); grievances resolved in **7 days** (was 15). Failure risks loss of safe harbour | Freshfields analysis (fetched), Bar & Bench; gazette not read; Medium–High. This corrects file 10, which recorded the three-hour window as general |
| Grievance Appellate Committee; cybercrime.gov.in; 1930 | Appeal within 30 days of a platform's refusal; fraud reporting | File 10; High |
| Criminal law | Cheating by personation and identity-theft provisions (BNS; IT Act ss. 66C, 66D) **[PK]** | Medium |
| Personality-rights case law (judge-made; no statute **[PK]**) | *Anil Kapoor* (Delhi HC, 2023): 16 defendants restrained from using his name, likeness and image, including through AI and face-morphing. *Jaikishan Kakubhai Saraf (Jackie Shroff) v Peppy Store* (Delhi HC, May 2024): name, nicknames, voice and image protected. *Arijit Singh v Codible Ventures LLP* (Bombay HC, 26 July 2024, Chagla J; 2024 SCC OnLine Bom 2445): ex parte interim order against AI voice-cloning tools; interim only, later status not found. In 2026 the Delhi HC granted similar relief to several public figures | ThePrint; Columbia Global Freedom of Expression; Wikipedia; Medium–High |
| ***Dr Devi Prasad Shetty & Anr v Medicine Me & Ors***, CS(COMM) 1053/2024, Delhi HC | Interim order 28 Nov 2024 (Pushkarna J): unidentified operators of Facebook pages restrained from misusing his persona; Meta and Google directed to take down content and disclose account-holder details. **Final decree reported 9 Oct 2026** (Kaurav J): interim order made absolute; permanent injunction; **a continuing right to seek takedown of similar content**, because it "can be re-uploaded easily under new identities". The court said the misuse "is not confined to the commercial appropriation of the persona of a well-known individual"; it attributes "claims of cures for diabetes, hypertension and other cardiac ailments which he never made" and the harm "extends to members of the public who may act upon such content" | LiveLaw Biz (fetched), ThePrint; High |
| *Dr Naresh Trehan* orders | 24-hour and 36-hour removal directions; see file 10 | File 10 |

**What this means for a doctor who is not yet famous.** The celebrity cases rest on being "well known". The Shetty decree adds a public-health ground that does not depend on fame, and the 2026 rules give a two-hour impersonation route that needs no court. The practical sequence is unchanged from file 10's takedown kit, with one amendment: cite the impersonation category and the two-hour duty in the first complaint. His exposure rises with visibility; the cheapest protections are the "official channels" page, the same handle everywhere, the monthly sweep, and never publishing studio-quality voice samples in a second language he does not normally speak on camera.

**YouTube's health features are not a shield he can apply for.** YouTube's eligibility page lists individual applications from licensed professionals in the US, UK, Germany, Brazil, Indonesia, Japan, France, South Korea, Canada and Mexico. **India is not on the individual list**; Indian channels with "standardized vetting", such as accredited hospitals and government bodies, are treated as eligible. The threshold elsewhere is 1,500 public watch hours in 12 months or 1.5 million Shorts views in 90 days, with attestation to the CMSS principles. support.google.com/youtube/answer/12796915 (fetched). **High.** If earlier files assume he can obtain the health-source panel as an individual, that needs correcting; the only route today is the feedback request tagged "#healthinfo".

---

### 3. Risk register for this plan

#### 3.1 Legal notes that sit behind the register

**Does a duty of care arise online?**

- **No Indian statute or reported judgment was found that makes a doctor liable for general public education or for a reply in a comment thread.** Absence of evidence after one targeted search; a lawyer should check the NCDRC and High Court databases. **Medium.**
- Courts have treated **advice to a specific patient without examination** as capable of being negligence. NCDRC (reported Dec 2023): treating a patient on a consultant's telephone advice "constitutes another instance of negligence in treatment"; Rs 10 lakh with 9% interest. Supreme Court (12 Feb 2025, Vikram Nath and Sandeep Mehta JJ): culpable-homicide charge quashed for an injection ordered by phone, but the negligence charge (s. 304A IPC) was left to proceed, applying *Jacob Mathew*. Kerala HC (May 2025): prescribing by phone is not criminal negligence if it matches what other practitioners would do (search summary only). **Medium–High.**
- **Consumer law.** Paid medical services are a "service" (*IMA v V.P. Shantha*, 1995). A three-judge bench in November 2024 declined to reconsider that; review and curative petitions were dismissed; a fresh plea by the Association of Healthcare Providers (India) drew notice to the Union and NMC in February 2026. Services rendered free of charge are outside the Act's definition **[PK]**, so an unpaid public reply is unlikely to support a consumer complaint, but ordinary negligence and a council complaint remain open, and if the commenter is already his patient the paid relationship exists. **Medium.**
- **Professional conduct.** The 2023 NMC regulations (in abeyance, still the best statement of the regulator's mind) say: avoid discussing patients' treatment or prescribing on public social media and "guide the patient toward a telemedicine consultation or in-person consultation" (file 02). The Telemedicine Practice Guidelines bar soliciting patients for teleconsultation.
- **Working rule:** teach the condition, never the person. No dose for an individual, no reading of a posted ECG or report, no "you should stop/start". Scripted replies only (section 4.6).

**Defamation and legal threats**

- Defamation is both a civil wrong and a crime in India (BNS s. 356; criminal defamation upheld in *Subramanian Swamy*, 2016) **[PK]**. Truth is a complete defence in a civil suit; the criminal exception needs truth and public good; fair comment on a matter of public interest is protected **[PK]**. A lawyer must confirm how these apply to him.
- **TheLiverDoc (Dr Cyriac Abby Philips).** Himalaya Wellness sued in Bengaluru over his posts on its products, alleging he maligned it to promote rivals. An ex parte injunction issued on 23 Sept 2023; X withheld the whole account on 28 Sept; the Karnataka High Court allowed restoration in October 2023 on condition that he hide nine posts until the case is decided. Retraction Watch reported in July 2024 that an injunction still barred him from speaking about Himalaya or its products, and that Frontiers in Pharmacology, having accepted his paper on liver injury linked to Liv.52 in January 2024, put it on hold in June 2024 and withdrew it "temporarily" pending the Indian proceedings, after also querying a past advisory role with Cipla that he said ended in 2020. His account was active as of May 2025. **Final outcome of the suit: not found** in two searches. Other proceedings (council complaints by AYUSH bodies, charges dropped Oct 2022; a police summons from Uttar Pradesh in 2024; an apology for calling an actor "health and science illiterate") are in file 03. **High** for the events to mid-2024.
- **Dr Chandra Gulhati and Lundbeck.** A 2009 article in a drug index noted that Deanxit was sold in India though not approved in Denmark; a criminal defamation case followed in Bengaluru (dated 2011); the health ministry banned the drug in 2013; the case ended only when the company closed its Indian operations in 2021, after about ten years and 15 trips to Bengaluru. He "won" by attrition. Scroll (fetched). **High.**
- **Revant Himatsingka ("FoodPharmer").** After a legal notice from Mondelez in April 2023 he took down the Bournvita video and apologised; a Delhi High Court interim order (reported 23 Oct 2024) lets him make factual statements but not "disparaging" videos about the company's products. Wikipedia (fetched). **Medium.**
- **The courts' stated caution.** *Bloomberg v Zee Entertainment* (Supreme Court, 22 Mar 2024, three judges): ex parte pre-trial injunctions in defamation suits against media should be granted cautiously; the Bonnard standard applies; courts should consider "the possibility of using protracted litigation to inhibit free speech and public participation" (SLAPP). India has no anti-SLAPP statute **[PK]**. The LiverDoc order shows that trial courts still grant ex parte relief. **High.**

**Lessons, in order of value**

1. Criticise the claim, never the company's or the person's motive or character. "This product has not been shown to lower LDL in a randomised trial" is defensible; "they are cheating patients" is a lawsuit.
2. The process is the punishment: years, travel to a distant court, a withheld account, and a journal that gets cold feet. Winning on the merits does not return the time.
3. An industry advisory role, even an old one, becomes the plaintiff's story ("promoting rivals"). Keep the conflict-of-interest register clean and public.
4. Put original criticism into peer-reviewed form first, and cite that.
5. No brand names in public content unless the lawyer has read the piece. Name the class or the claim.
6. One rude adjective cost Dr Philips a public apology. Tone is a legal and a reputational control.

#### 3.2 The register

Scales: Likelihood over three years (L low, M medium, H high); Impact (L, M, H, VH). Priority = judgement from both. Owners: **A** = Dr Avinash, **F** = friend/editor, **Law** = retained health lawyer, **2R** = clinician second reader, **TE** = Telugu editor, **AC** = advisory circle.

| # | Risk | L | I | Early warning | Mitigation | Owner |
|---|---|---|---|---|---|---|
| 1 | **Over-specific "composite" case** breaches confidentiality: a patient, family or colleague recognises a real person | M | VH | A comment or message saying "is this about…"; a draft containing age + occupation + date + locality; a story told within weeks of the event | File 11 protocol; three-patient rule (every scenario blends at least three, with age, sex, place, timing and one clinical detail changed); nothing from the last 6 months; label "illustrative scenario, not a real patient"; 2R asks "could anyone identify this?"; real cases go only to journals and conferences with consent | A, 2R |
| 2 | **Error in his own content** (wrong number, outdated guidance) | H | M–H | Reader or peer flags; guideline update; review date passed | Claims ledger; second-reader rule; date stamps and review cadence; corrections policy with severity tiers (section 4.4) | A, F |
| 3 | **AI error reaches the public**: a hallucinated statistic or citation, a mistranslated Telugu instruction | M | H | A source that will not open; a number with no PMID; TE flags a phrase that reverses meaning | "No source, no sentence"; every source opened by a human; AI never supplies the citation of record; Telugu back-translation of every instruction involving a medicine or an emergency; log of AI use (section 4.5) | F, A, TE |
| 4 | **Employer conflict before exit**: Apollo objects to the own practice, to content, to "not promoting the employer", or to media contact | M | H | A message from marketing or HR; a request to add branding; a contract clause on exclusivity or media | Read the contract with Law first (file 17); written understanding that public-health education is in his own name (NMC cl. 5.1 supports this); no Apollo facility, logo or patient in any content; no comment on Apollo; sequence per file 17 | A, Law |
| 5 | **Legal threat** from a company or alternative-medicine promoter (notice, suit, FIR) | M (H if he names products) | H | A lawyer's letter; a tag from a brand account; a coordinated complaint | Rules in 3.1; pre-publication legal read for anything naming a product, practitioner or system of medicine; evidence file for every critical claim; never reply to a notice himself; indemnity cover that includes media and defamation defence if obtainable | A, Law |
| 6 | **Regulator complaint** under the 6 Oct 2026 Guidelines (likely from a peer or competitor) | L–M | H | TGMC letter; a peer's public remark that he is "advertising"; a hospital reel with his face | File 11 checklist before every post; registration number on every post; no testimonials, superiority words, paid reach or calls to book; decline hospital promotion in writing; resolve the AP-only registration (TGMC registration) before launch; keep an approvals log to show education intent | A, F |
| 7 | **Burnout and abandonment** | H | H | Energy rating 2 or lower for two weeks; missed sign-offs; hours above cap; irritation at comments | Hours cap; content buffer of 6 weeks; "never miss twice"; a minimum viable cadence (one piece a fortnight) that he can hold when busy; quarterly pruning; the friend, not he, reads comments | A, F |
| 8 | **Medical advice in comments or messages** creating a duty or a complaint | M | M–H | Comments with reports, doses, "what should I do"; DMs | Scripted replies; comments moderated by F to script; no DM consultations; pinned boundary note; emergency line (108) in the script | F, A |
| 9 | **Peer hostility** for speaking about over-treatment or appropriateness | M | M–H | Cold shoulders at meetings; anonymous complaints; referral drop; remarks in doctor groups | Speak about evidence and decisions, never about colleagues or hospitals; present the same material to peers first (case conference) before the public; use guideline language; mentor's read; share credit | A, mentor |
| 10 | **Misquotation by media** | M | M | A headline that overstates; a quote cut from context; a request for comment on a celebrity's death | Written answers preferred; a 100-word quotable summary supplied with every interview; ask to see quotes (not copy); never speculate on an individual's cause of death; correction request within 24 hours, in writing (file 08) | A, F |
| 11 | **Deepfake or impersonation** using his face or voice to sell a product | M (rises with reach) | H | Monthly sweep; a patient asks "is this you?"; Meta Ad Library hit | Official-channels page; takedown kit (file 10) citing the two-hour impersonation duty; police and cybercrime complaint; inform council; John Doe suit if it recurs (Shetty decree as template) | F, Law |
| 12 | **Trolling and harassment**, including of family | M | M–H | Sudden spike in hostile replies; employer or council contacted; home address or family named | Avoid the three high-harassment topics unless essential (vaccines, AYUSH as a system, politics); no-reply rule; F filters; document, block, report; police complaint for threats and doxxing; pause rule | F, A |
| 13 | **Political or communal landmine** | L–M | VH | A draft touching a party, a government scheme's merits, a religious practice (fasting, diet), a community's food, a caste or regional stereotype | Subject rule: health facts only; describe practices respectfully and without ranking communities; no comment on parties, leaders or court cases; TE and patient representative read festival and food pieces; pause scheduled posts during unrest | A, TE |
| 14 | **Account takeover** | L–M | H | Login alerts; unknown sessions; posts he did not approve | He owns every account; password manager; hardware key or app-based two-factor, not SMS; F has delegated roles, not passwords, where the platform allows; recovery codes printed and stored; quarterly access review | A, F |
| 15 | **Data breach** (newsletter list, cohort data, registry) | L–M | H–VH | Unexpected exports; a lost laptop or phone; a tool vendor's breach notice | Collect the minimum (file 10); keep cohort and registry data out of the content pipeline entirely (file 18's two pipelines); encrypted storage; named custodian; breach procedure (3.3); DPDP duties to notify the Board and affected people **[PK; main provisions in force 13 May 2027 per file 10]** | A, F, Law |
| 16 | **Over-dependence on one platform** | M | M | More than 60% of reach on one platform; a policy or algorithm change; a strike | Website as the archive of record; owned e-mail list; every video also exists as text; two platforms minimum | F |
| 17 | **Over-dependence on one helper** | M | H | F unavailable; undocumented steps; only F knows how something works | Written runbook; a named backup (even at minimum cadence); all assets in A's name; quarterly "could someone else run this?" test | A, F |
| 18 | **Family privacy** | L–M | H | Family in photographs; home, school or car visible; relatives tagged | No family, home or routine in content; separate private accounts locked down; clinic address only as the public address; ask relatives not to tag | A |
| 19 | **Outcome figures read as "success claims"** when he publishes his audit | L–M | M–H | A draft that says "my patients do better"; a rate shown without denominators or source | Publish outcomes through journals and conferences first; in public, describe the audit and link the paper; no comparison with other doctors; Law reads the annual note (NMC cl. 6.2; 2002 Reg. 6.1.1) | A, Law |
| 20 | **Community programme harm or allegation** (injury at a CPR session; a screening result mishandled; a consent lapse) | L | H | An incident at a session; a participant complaint | File 15 safeguards; partner organisations hold the event; written consent and data notice; referral pathway for abnormal results; incident log | A, partner |
| 21 | **Conflict of interest surfaces late** (a device-company workshop, a sponsored trip) | L–M | M–H | An invitation with travel paid; a logo on a slide | Public COI register updated yearly; no sponsor in public or trainee teaching (file 19); declare at the start of any talk | A |
| 22 | **A viral patient complaint or adverse-outcome allegation** unrelated to content | L–M | VH | A family's video; a hostile review cluster; a journalist's call | File 10, section 6.4 playbook: silence in public, facts with the hospital, insurer informed, private contact first | A, hospital, Law |
| 23 | **Rule change** (TGMC circular, NMC amendment, platform policy) makes current practice non-compliant | M | M | Council or NMC notice; platform policy e-mail | F checks NMC and TGMC notices monthly; pause-and-review stop rule; Law on call | F, Law |

**Top priorities by judgement:** 1, 3, 2, 4, 7, 5. All but 5 are within his own control.

#### 3.3 Crisis playbook

File 10, section 6.4, already covers the viral patient complaint, and section 6.3 the deepfake. This playbook covers the rest and sets the common rules.

**Common rules**

- **Who speaks.** He speaks only about his own educational content and his own errors. The hospital speaks about anything involving a patient treated there. The lawyer speaks to lawyers, courts and the council. The friend never speaks as him; the friend may post a holding statement he has approved. No one answers a journalist's phone question on the spot; ask for it in writing.
- **First move in every case:** stop the schedule, save the evidence (screenshots with URL, date and time; the original file; the approvals log), tell the people on the list, write nothing in public for one hour.
- **Nothing is deleted** except content that is itself the harm (a confidentiality breach, a dangerous error), and then only after a copy is saved and the removal is logged.

| | First hour | First day | First week |
|---|---|---|---|
| **A. Error in his content** | F pauses schedule; A judges severity. S1 (could cause harm: a dose, "stop your medicine", a missed emergency sign): take the piece down or correct it at once | Corrected version live with a dated note at the top; pinned correction on the platform where it spread; entry in corrections log; e-mail to subscribers if S1 | Root cause written in five lines (which check failed); checklist changed; AC told in the quarterly note; S1 goes in the annual note |
| **B. Confidentiality concern** (someone recognises a scenario) | Remove the piece everywhere; save copies; do not confirm or deny identity in public | Tell Law; if the person is identifiable to others, A contacts the patient or family privately and apologises; tell the hospital if their patient; record the incident | Review every published scenario against the three-patient rule; pause all scenario content until done; consider notifying the insurer |
| **C. Legal notice, suit or police call** | Do not reply, post, delete or phone the sender. Send the paper to Law. F freezes all content on that subject | Law acknowledges if needed; evidence file assembled; indemnity insurer told; decide with Law whether the posts stay up | Public statement only if Law drafts it; once anything is before a court, say nothing on that subject; keep publishing on unrelated topics after Law agrees |
| **D. Council or regulator notice** | Stop all publishing. Send to Law | Assemble the approvals log, the registration details and the content in question; reply only through Law within the time given | Fix whatever is fixable; resume only on Law's written advice |
| **E. Employer objection** | Stop anything that touches the employer; no public comment | A meets the right person with the contract and NMC cl. 5.1 in hand; Law advises | Written understanding, or an earlier exit decision (file 17) |
| **F. Harassment pile-on** | F takes over the accounts' notifications; A stops reading; no replies | Document, block, report; if a factual error triggered it, handle as A; if threats or doxxing, police and cybercrime complaint | Decide whether the topic is worth it; resume quietly; A's energy rating decides the date |
| **G. Account takeover** | Platform recovery from a clean device; revoke sessions; change e-mail password first; tell F and close family | Notice on the website and other channels: "Our [platform] account was accessed without permission between [times]; ignore messages from it"; report impersonation category | Review access; rotate all credentials; hardware keys; note in the log |
| **H. Data breach** | Contain (revoke links, lock the account, wipe the device remotely); tell Law | Establish what data, whose and how many; Law advises on notification to the Data Protection Board and affected people and on whether CERT-In reporting applies **[PK: CERT-In's 2022 directions set a six-hour reporting window for covered entities; applicability to a solo clinic to be confirmed]** | Notify as advised, in plain language; fix the cause; record in the annual note |
| **I. Deepfake** | File 10 kit; first complaint cites impersonation and the two-hour duty | Public notice; police and cybercrime complaint; inform TGMC/APMC so he is on record as the victim | Weekly re-search for a month; suit if it recurs |

**Holding statements (pre-approved; adapt, do not improvise)**

1. *Error:* "On [date] I published [title]. It said [X]. That was wrong: the correct information is [Y] (source: [link]). I have corrected it and I am sorry. If you acted on the earlier version, please speak to your own doctor. — Dr Avinash Pathuri, [reg. no.]"
2. *Patient-related allegation:* "I cannot discuss any patient's care in public; that duty continues even when others speak. The matter is being reviewed through the proper channel, and I have asked that the family be contacted directly."
3. *Legal matter:* "This matter is before a court, so I will not comment on it. My educational work on other subjects continues."
4. *Impersonation:* "A video/advertisement using my face or voice is circulating. It is fake. I do not endorse any product or treatment. My only official channels are listed at [link]. Please report the video and do not buy from it."
5. *Pause:* "I am taking a short break from posting. The existing material stays available at [link]. In an emergency call 108."

**When to stay silent:** anything before a court; anything about a patient; a pile-on with no factual error; political or communal bait; a myth with no traction (file 14: answering it spreads it); criticism of him that is merely rude. Silence in public still means documenting and reporting.

**When to call the lawyer (same hour):** any legal notice, court paper, police call or council letter; a journalist asking about a named patient; a platform message about a court order; a deepfake that is collecting money; an employer's written objection; a data breach; and **before** publishing anything that names a company, product, hospital, practitioner or system of medicine critically.

---

### 4. Quality system

Why a system and not good intentions: the GMC requires "reasonable steps" that information is "not false or misleading"; the AMA requires that it be "accurate based on professional medical judgment"; the NMC holds him responsible for whatever he authorises through others; and the audits in 1.5 show doctors failing this routinely. The UK's PIF TICK scheme gives a tested skeleton of ten criteria: a documented process; trained people; a genuine need; reliable, current evidence clearly communicated; users involved; health-literacy and language needs met; legal compliance; a feedback route; dissemination; impact measured (pifonline.org.uk, fetched). The standard below maps to those ten.

#### 4.1 Source hierarchy

| Tier | Source | Use |
|---|---|---|
| 1 | Current guidelines and consensus statements: CSI, LAI, IRC and other Indian bodies first where they exist; ESC, ACC/AHA; WHO; ICMR and MoHFW documents | The default basis for any recommendation. State the year |
| 2 | Cochrane and other systematic reviews and meta-analyses | For effect sizes |
| 3 | Large randomised trials (name the trial) | For specific claims; say who was studied |
| 4 | Indian registries and cohorts | For "how common is this here"; say the place and years |
| 5 | Observational studies | Only with the word "associated" |
| 6 | His own experience or opinion | Allowed, labelled as such ("in my view", "in my practice") |
| Not sources | Press releases, company material, preprints unless labelled, news reports of studies, WhatsApp forwards, another doctor's video, **any AI output** | Never the basis of a claim |

Where an Indian and a Western guideline differ, say so and say which he follows and why.

#### 4.2 Citation and dating rules

- **Claims ledger.** One spreadsheet row per factual claim in every piece: the claim as worded; source (PMID or DOI or official URL); the exact figure or sentence in the source; population; year; who opened the source and when. A piece cannot be approved with an empty row.
- **Public citation.** Every piece carries at least its main source in the description or footer ("Sources: …"), and any number carries its own. Spoken video: sources in the description and on the website transcript.
- **Numbers.** Absolute before relative ("3 fewer heart attacks per 100 people over 5 years"), the population named, no "up to".
- **Date stamps.** "Medically checked: [date]. Next review due: [date]."
- **Review cadence.** Evergreen prevention content: 12 months. Anything naming a drug class, device, target or threshold: 6 months. Immediate review on a trigger: a new or revised guideline, a safety alert, a retraction of a cited paper, a reader's substantiated challenge. F keeps the review calendar; an overdue piece is unlisted until checked.

#### 4.3 Conflict-of-interest statement

A public page, updated each January: employer and hospitals where he holds privileges; his own practice; any payment, travel, hospitality, research support, advisory role or equity from any pharmaceutical, device, diagnostics, food, insurance or health-technology company in the past 36 months (or "none"); society posts; the friend's relevant interests; who pays for the content work ("self-funded; no sponsor"). A per-piece line when a piece touches anything on the register. This follows AMA 2.3.2 and GMC para 12, and it is the defence the LiverDoc case shows he will need.

#### 4.4 Corrections policy and log

| Severity | Definition | Action | Time limit |
|---|---|---|---|
| S1 | Could lead someone to harm (dose, stopping or starting a medicine, emergency advice, a contraindication) | Remove or correct at once; dated note at the top; pinned correction where it spread; e-mail subscribers; root-cause note; reported to AC | 24 hours from discovery |
| S2 | A wrong fact or number that does not change what a person should do | Correct; dated note; log | 72 hours |
| S3 | Typo, broken link, formatting | Fix; log without a public note | 7 days |

The log is public (date published, date corrected, what was wrong, what is right, how it was found). Nothing is silently edited at S1 or S2. A correction made well is the cheapest trust he will ever buy; file 19's ninth principle already commits to it.

#### 4.5 Verifying AI drafts (claim by claim)

1. **Inputs.** No patient information, ever (NMC 7.2(d)). Give the AI the source documents; do not ask it to recall facts.
2. **Extract.** List every factual claim, number, comparison and causal statement in the draft as ledger rows. A second AI pass may help to list them; it does not verify them.
3. **Open.** A human opens each source at the publisher or PubMed page. If it does not open, the reference is treated as fabricated and the sentence is deleted. The AI never supplies the citation of record.
4. **Match.** Find the figure or sentence in the source and paste it into the ledger. Check units, denominators, time frame, relative versus absolute, and the direction of effect.
5. **Applicability.** Who was studied (age, sex, country, primary or secondary prevention)? If not Indian or South Asian, say so in the piece.
6. **Currency.** Is there a newer guideline or a retraction? Search the title on PubMed for errata.
7. **Opinion check.** Any sentence expressing a judgement must be one he actually holds; he rewrites it in his own words.
8. **Telugu.** TE edits the Telugu; every instruction involving a medicine, a symptom that needs action, or an emergency is back-translated into English by someone who has not seen the original, and compared.
9. **Record.** The ledger notes which tool was used and for what. This is the audit trail if a claim is ever challenged.
10. **Rule of thumb:** no source, no sentence; no ledger, no publish.

The numbers behind the rule: 47% and 55% fabricated references from GPT-3.5, 18% from GPT-4 (PMID 37337480; 37679503); 18 of 100 reviews of LLM-rewritten discharge summaries flagged safety issues (file 18).

#### 4.6 The boundary wording: honest, not ritual

Ritual disclaimers ("consult your doctor") are ignored and protect no one. An honest one says what the content cannot do and what the reader should do next.

> **English:** "I have not examined you and I do not know your reports, so I cannot tell you what you should do. This is general information to help you understand the condition and ask better questions. Do not start, stop or change any medicine because of this. If you have chest pain, breathlessness or fainting now, call 108."
>
> **Telugu (draft for the Telugu editor to correct):** "నేను మిమ్మల్ని పరీక్షించలేదు, మీ రిపోర్టులు నాకు తెలియవు. అందుకే మీరు ఏమి చేయాలో నేను ఇక్కడ చెప్పలేను. ఇది జబ్బును అర్థం చేసుకోవడానికి, మీ డాక్టర్‌ను సరైన ప్రశ్నలు అడగడానికి ఉపయోగపడే సాధారణ సమాచారం మాత్రమే. దీన్ని చూసి ఏ మందూ మొదలుపెట్టవద్దు, ఆపవద్దు, మార్చవద్దు. ఇప్పుడు ఛాతీ నొప్పి, ఆయాసం లేదా స్పృహ తప్పడం ఉంటే వెంటనే 108కి కాల్ చేయండి."

**Scripted replies** (F posts; nothing else is said):

- To a personal question: "I can't advise on an individual's case here because I haven't examined you. Please take this question to your own doctor. If it is urgent, call 108."
- To a posted report or ECG: the same, and the image is hidden.
- To "which doctor/hospital?": "I can't recommend doctors or hospitals here."
- To a civil disagreement: the source, once, without adjectives.
- To abuse: no reply; hide or block; log.

#### 4.7 Accessibility and Telugu readability

- **No validated readability formula for Telugu was found** (file 14; two further Europe PMC searches this session returned nothing). English formulas do not transfer. Use people instead.
- **Listener test, every Tier A and every flagship piece:** three to five lay listeners, including one aged over 60 and one with schooling to Class 8 or less, hear or read it once. Each answers: what was the main message; what should you do; what should you not do; was any word unclear. Pass = at least four of five give the main message and the action correctly. Record failures and rewrite. Cost: about 20 minutes per piece for TE or F.
- **Teach-back question** at the end of each lesson (file 14).
- **Language rules:** spoken Telangana Telugu, not textbook Telugu; keep the English words people actually use (BP, sugar, stent, cholesterol) and explain them once; Indian numerals and units people recognise; no English-only slides in a Telugu video.
- **PEMAT.** The Patient Education Materials Assessment Tool scores understandability and actionability of print and audiovisual material (PMID 24973195); it has been validated in Japanese, Chinese and Arabic (PMID 36497836; 37200085; 40471382) but **no Telugu or Hindi validation was found**. Use the audiovisual form as an internal checklist; a 70% score is the commonly used pass mark **[PK]**. A Telugu validation is a small publishable project.
- **Access:** captions on every video (checked, not auto-generated only); a text transcript on the website; alt text on images; high contrast and large type on slides; audio-only versions for low-literacy and low-data users; nothing that requires reading small English text.

#### 4.8 Second-reader rule

| Tier | Content | Before publishing |
|---|---|---|
| **A** | Medicines (starting, stopping, doses, interactions); emergency actions; procedures he performs (angioplasty, pacemakers); criticism of any practice, product or system; anything touching over-treatment; decision aids; all scenario-based pieces | Claims ledger complete; **a clinician second reader** (a cardiologist or physician, not the friend) signs; TE and back-translation for Telugu; **Law** if a product, company, practitioner or system is named; then his sign-off |
| **B** | Standard prevention education (know your numbers, salt, exercise, tobacco), CPR awareness, explainers of a guideline | Claims ledger complete; F's checklist (file 11 compliance list); listener test for flagship pieces; his sign-off |
| **C** | Announcements of talks, logistics, thanks | F's compliance check; his sign-off |

If no second reader is available, Tier A waits. Two clinicians who read for each other (he reads theirs) make this sustainable; the senior mentor is not the routine second reader.

---

### 5. Measurement without vanity

#### 5.1 Principles

1. **No patient-acquisition metric anywhere in this system** (file 10; NMC cl. 8.1(ii)). Clinic volume is a private business number, kept elsewhere.
2. **Inputs and guardrails are judged monthly; reach quarterly; outcomes at 12 months and after.** Nothing lagging is judged before month 6 (file 06, file 10).
3. **Every outcome carries its denominator** ("112 of 160"), and people lost to follow-up are counted as not at goal.
4. **Targets below are planning figures.** Where a benchmark exists it is cited; where none exists the target is "establish a baseline", not an invented number. Year 1 ends November 2027; year 3, November 2029.
5. **Vanity test:** if a number can rise while no one is better informed, measured, treated or taught, it is not a KPI. Followers, likes and impressions are recorded for diagnosis only.

#### 5.2 KPI tree

**Ring 1 — the public who never become patients**

| ID | Measure and definition | Source, cadence | Year 1 | Year 3 | Benchmark or evidence | Lead / lag |
|---|---|---|---|---|---|---|
| P1 | **Reach in Telugu and English:** public watch hours and unique viewers per quarter, split by language | YouTube Studio, website analytics; quarterly | At least 1,500 public watch hours in 12 months; Telugu at least 60% of watch time; subscribers 10,000 (lower end of file 13's range) | 15,000–20,000 watch hours a year; 50,000–1,00,000 subscribers | File 05 arithmetic (1,500 hours is about 25,700 views at 3.5 minutes); file 13 (10,000–25,000 at 12 months with 3–4 Shorts a week); 1,500 hours is also YouTube's health-feature threshold in countries where individuals can apply | Lagging, 2–4 months |
| P2 | **Completion and saves:** median percentage viewed (long form); "viewed vs swiped away" (Shorts); saves plus sends per 1,000 reach | Platform analytics; monthly per piece | Baseline from the first 90 days; then median up 20% relative | Held or better | No reliable public benchmark found; platform heads name watch time and sends per reach as the main signals (file 05) | Leading |
| P3 | **Cohort enrolment and completion:** people enrolled in a Heart School cohort with baseline numbers recorded; share re-measured at day 100 | Cohort sheet; per cohort | 150–200 enrolled in 2 cohorts; at least 60% re-measured at day 100 | 5,000 with logged numbers; 12-month follow-up on early cohorts | File 19 milestones. No benchmark for completion of a doctor-led Telugu cohort exists; cohort 1 sets it | Leading (enrolment), lagging (completion) |
| P4 | **Numbers known:** share of participants who can state their own BP, LDL, fasting glucose or HbA1c, waist or BMI, and tobacco status, day 0 vs day 100 | Two-minute form; per cohort | At least 80% know all five at day 100 | Same, sustained at 12 months in at least 60% | Nationally only 27.9% of people with hypertension are aware of it (NNMS 2017–18, PMID 35513442) | Lagging |
| P5 | **Numbers controlled:** of participants with raised BP at baseline, share below 140/90 at day 100 and at 12 months; same for LDL above target and for tobacco use (quit) | Cohort sheet, measured not self-reported; per cohort | Report with denominators; no numeric promise before cohort 1 | At least 40% BP control at 12 months among those hypertensive at baseline | National control 12.6% (PMID 35513442); IHCI 44% among those under care (PMID 41314840); PROLIFIC 64% vs 46% reaching three of four targets at two years (PMID 34534488) | Lagging, 4–12 months |
| P6 | **CPR-trained:** people who completed two rounds of compressions and an AED-trainer drill with a signed tick-list | Event log; monthly | 1,000 | 4,000 cumulative; 30 sites with a named AED contact | File 15, Programme A | Leading |
| P7 | **CPR retention:** share of a re-tested sample passing the tick-list at 6 months | Feedback manikin re-test of at least 30 people; twice a year | Measured; target at least 50% | At least 60% with the refresher loop running | Adequate performance fell from 60% to 44% within 2 months after self-training and from 42% to 30% after a standard course (Einspruch 2007, via file 15) | Lagging |
| P8 | **Belief accuracy:** three true/false items on the cohort's topic, day 0, day 100 and month 12 | Cohort form | Run in every cohort | 12-month recheck reported | Corrections d = 0.40 (PMID 32762260) but fade (PMID 35115678): the 12-month figure is the honest one | Lagging |

**Ring 2 — patients** (his own audited registry; needs ethics approval, consent and, while at Apollo, the hospital's agreement on data: files 17 and 19)

| ID | Measure and definition | Source, cadence | Year 1 | Year 3 | Benchmark or evidence | Lead / lag |
|---|---|---|---|---|---|---|
| T1 | **Understanding:** share of ACS/PCI patients or carers answering three teach-back questions correctly at first follow-up (which medicines must not be stopped without asking; their LDL target; when to call 108) | Clinic form; monthly | Asked in at least 80% of eligible patients; pass at least 70% | Pass at least 85% | Teach-back evidence in files 14 and 19 | Leading |
| T2 | **Persistence:** on statin and on antiplatelet therapy at 6 and 12 months | Registry; quarterly | Measured for the first 6 months' patients | Above 85% at 12 months | Indian registry: statins 99.7% to 70.0% at 6 months, high-intensity 92.0% to 45.7% (PMID 40020999) | Lagging |
| T3 | **LDL at goal:** share with LDL-C below 55 mg/dL at 12 months, and share with any LDL measured | Registry; quarterly | Baseline rate; at least 80% measured | Over 50% at goal | 27% of treated Indian coronary patients at 50 mg/dL or below (file 19) | Lagging |
| T4 | **BP at goal** among his patients with hypertension | Registry; quarterly | Baseline | Set after baseline; reference point IHCI 44% | PMID 41314840 | Lagging |
| T5 | **Rehabilitation:** share referred; share starting; share completing a structured programme (centre, hybrid or home) | Registry; quarterly | Referral documented in 100%; uptake measured | At least 30% completing | India had about one rehabilitation place per 360 eligible patients (PMID 32489801, data about 2017) | Leading (referral), lagging (completion) |
| T6 | **Loss to follow-up** at 12 months | Registry | Measured | Below 15% | 20.5% lost by 6 months in the Indian registry (PMID 40020999) | Lagging |

**Ring 3 — peers and trainees**

| ID | Measure and definition | Source, cadence | Year 1 | Year 3 | Benchmark or evidence | Lead / lag |
|---|---|---|---|---|---|---|
| E1 | **Attendance:** registered trainees; "regular" = attended at least half the sessions in a quarter | Webinar log; quarterly | 300 registered; 80–120 regular; 40 sessions held | 1,000 registered; 250–300 regular | File 19; India admits about 1,080 cardiology trainees a year | Leading |
| E2 | **CPD hours delivered:** attendee-hours; and accredited credit hours through an accredited association | Log; TGMC CPD portal; quarterly | About 4,000 attendee-hours; 2 accredited programmes | 12,000 a year; 6 accredited programmes | TGMC: online CPD earns half a credit hour per 2 hours; 24 credit hours needed for renewal from 2027, 30 from 2028 (file 16) | Leading |
| E3 | **Scholarly output and citations:** papers accepted (with trainee co-authors counted separately); citations | ORCID, Google Scholar; half-yearly | 2 cumulative submissions, 1 accepted (file 10) | 10 or more trainee-co-authored papers; one audit published | Promotion adds at most about 1.12 times to citations (ESC trial); the paper is the lever | Lagging, 12–36 months |
| E4 | **Invitations:** unsolicited invitations as faculty | Log | 1 at a state or fellows' meeting | 4–6 a year, at least 1 national | File 19 | Lagging |
| E5 | **Fellowships and roles:** FSCAI/FESC/FACC applications and awards; committee roles | Log | 1 application filed | 2 held; 1 society committee role | Sponsor rules in file 16 | Lagging |
| E6 | **Case submissions accepted:** cases and abstracts accepted at TCTAP, CRT, EuroPCR, CSI, India Live (his and mentees') | Log | 3 submitted, 1–2 accepted | 6 accepted a year | Deadlines in file 16 | Lagging |
| E7 | **Atlas and reuse:** open teaching cases published; use by others (citations, course adoption) | Website; yearly | 40 cases | 120 cases; used by at least one programme he does not run | File 19 | Leading then lagging |

**Foundations**

| ID | Measure | Source, cadence | Year 1 | Year 3 | Lead / lag |
|---|---|---|---|---|---|
| F1 | **Entity presence under "Dr. Avinash Pathuri":** canonical record matched across Tier 1–2 listings; AI-assistant accuracy score (3 assistants × 3 points); branded search impressions | Audit sheet, Search Console; monthly | 100% matched; score at least 8/9; branded impressions double the baseline (file 10) | 9/9; correct panel or profile for the name query | Leading (hygiene), lagging (panel) |
| F2 | **Owned list:** double-opt-in e-mail subscribers; WhatsApp Channel followers | ESP; quarterly | 750–1,000 e-mail (file 10) | 5,000 | Lagging |
| F3 | **Portability:** share of accounts, domains, lists and content legally in his name | Access review; quarterly | 100% | 100% | Leading |

**Guardrails** (a breach of any red line outranks every other number)

| ID | Measure | Target | Cadence |
|---|---|---|---|
| G1 | Complaints: council or regulator notices; legal notices; platform strikes; substantive complaints about content from patients or peers | 0; 0; 0; each answered within 7 days | Monthly |
| G2 | Corrections: count by severity; median hours to correct | S1 = 0; any S1 corrected within 24 h; 100% logged publicly | Monthly |
| G3 | Process compliance: pieces with a complete claims ledger; Tier A pieces with a clinician second reader; posts carrying name, qualification and registration number | 100% each | Monthly |
| G4 | Hours: his weekly hours on all of this; the friend's | His at most 5–6 a week in total (file 06's 60–90 minutes for content plus file 19's 4 hours of teaching and audit); four weeks over the cap triggers pruning | Weekly |
| G5 | His energy: one self-rating, 1–5, each Sunday | Two consecutive weeks at 2 or below pauses publishing | Weekly |
| G6 | Safety: harassment incidents; impersonation incidents; hours to takedown | Logged; takedown requested the same day | Monthly |
| G7 | Confidentiality incidents | 0 | Monthly |
| G8 | Dependence: share of reach on the largest platform; runbook current; backup person named | Below 60%; yes; yes | Quarterly |

#### 5.3 Attributing modestly

- **Claim contribution, not causation.** "Of 160 people who enrolled, 112 were re-measured at day 100 and 48 of the 70 with raised BP at baseline were below 140/90" is a fact. "The programme lowered BP" needs a comparison group.
- **Build the comparison in.** A wait-list design (the next cohort measured at its own day 0 and day 100 before starting) costs nothing and is what file 19 proposes with an evaluation partner.
- **The ladder:** exposure (views) → engagement (completion, saves) → enrolment → measurement → control → events. Report each rung separately and never multiply down the ladder to claim events prevented. If a modelled figure is ever shown, label it "modelled" with the method.
- **Regression to the mean and drop-out** inflate before-after results; show the baseline of completers and non-completers, and count the lost as not at goal.
- **Ask "how did you hear of this?" once**, at cohort or CPR enrolment, to learn which channel recruits. Do not ask it at the clinic desk for the purposes of this system.
- **Publish nulls.** If cohort 1 shows nothing, say so and change the design.
- **Academic attribution:** do not credit posting for citations; the trials do not support it.

#### 5.4 The one-page quarterly review

Thirty minutes, he and the friend; circulated to the advisory circle afterwards. One page, same layout every time.

```
QUARTERLY REVIEW — Q_ 20__                     Prepared by: ______  Date: ______

1. RED LINES (any "yes" is discussed first)
   Council/legal notice?  N   S1 correction?  N   Confidentiality incident?  N
   Stop rule invoked?  N (which, how long)       Impersonation incident?  N

2. HIS LOAD                 This qtr    Last qtr    Cap
   Avg hours/week              __          __       5–6
   Energy (avg 1–5)            __          __       >=3
   Weeks missed                __          __       <=1

3. RING 1 — PUBLIC                              This qtr   Cumulative   Year target
   Watch hours (Telugu % )                        __ (__%)    __          1,500
   Median % viewed / saves+sends per 1,000        __ / __     baseline __
   Cohort: enrolled / re-measured at day 100      __ / __     __          150–200
   Raised BP at baseline now <140/90 (n of N)     __ of __
   CPR: trained / 6-month pass (n of N)           __ / __ of __   __      1,000

4. RING 2 — PATIENTS (registry, denominators shown)
   Teach-back pass  __ of __    Statin at 6 mo  __ of __    LDL <55 at 12 mo  __ of __
   Rehab: referred / started / completed  __ / __ / __      Lost to follow-up  __ of __

5. RING 3 — PEERS AND TRAINEES
   Sessions held __   Regular attendees __   CPD attendee-hours __
   Submitted / accepted (papers, cases) __ / __   Invitations __   Atlas cases __

6. FOUNDATIONS
   Listings matched __%   AI-assistant score __/9   E-mail list __   Assets in his name 100%? __

7. QUALITY
   Pieces published __   Claims ledger complete __%   Tier A second-read __%
   Corrections S1/S2/S3  __/__/__   Median hours to correct __   Reviews overdue __

8. THREE DECISIONS
   Stop: ____________   Start: ____________   Change: ____________

9. ONE THING WE LEARNED THAT SURPRISED US: ______________________________
```

---

### 6. Governance

#### 6.1 Advisory circle

Five people, two-year terms, two 60-minute meetings a year plus the quarterly page, on call for stop-rule events. No employee of a pharmaceutical, device or diagnostics company. Each declares interests. Unpaid or a token honorarium, except the lawyer and the language editor, who are paid for work done.

| Seat | Who to look for | What they do |
|---|---|---|
| Senior cardiologist mentor | A respected senior outside his reporting line: a DM teacher, or a CSI Telangana office-bearer | Reads anything touching appropriateness or over-treatment before the public sees it; warns of peer reaction; opens doors for teaching roles |
| Health lawyer | Hyderabad-based, with medical-council and media or defamation experience; on a small retainer | Contract and exit (file 17); the NMC questions in file 11; pre-publication read where a name appears; first call in any crisis |
| Public-health or evaluation person | Faculty at IIPH Hyderabad, ICMR-NIN or a community-medicine department (file 19 names these as candidates; none approached) | Designs the cohort evaluation and the registry audit; keeps the denominators honest; co-authors |
| Patient representative | A former patient or carer, not under his active treatment, comfortable in Telugu | Reads flagship pieces as a lay reader; sits in on listener tests; tells him when something frightens or confuses. **Never appears in content and gives no testimonial** (NMC cl. 6.2) |
| Telugu language editor | A Telugu journalist, teacher or translator; paid per piece | Edits every Telugu piece; runs back-translation; flags regional, religious or caste sensitivities |

#### 6.2 Decision rights between him and the friend

| Decision | He | Friend | Others |
|---|---|---|---|
| Any clinical claim, number or recommendation | **Decides** | May question, cannot change | 2R for Tier A |
| Opinions and positions | **Decides** | Advises on framing | Mentor consulted on peer-sensitive items |
| Topic calendar | Approves quarterly | **Proposes and runs** | — |
| Wording, length, format, thumbnail | Approves | **Decides within the standard** | TE for Telugu |
| Publish | **Final sign-off, logged** | Schedules only after sign-off | — |
| Anything naming a company, product, practitioner, hospital or system | Decides after legal read | Flags | **Law must read** |
| Comment moderation | Sets the script | **Runs to script** | — |
| Replies to journalists and peers | **His own words** | Logistics only | Law if a patient or dispute is involved |
| Accounts, domains, lists, data | **Owner of everything** | Delegated roles | — |
| Tools, including AI tools | Approves | **Proposes, operates, logs** | — |
| Spending | Approves a yearly envelope | Spends within it | — |
| Invoking a stop rule | **Either may invoke** | **Either may invoke** | AC informed |
| Lifting a stop rule | **Only he**, after the checklist | Confirms checklist | Law where the trigger was legal |
| Friend's own posts about him | Must approve | No promotional posts about him (NMC 8.1(ii), (xi)) | — |
| Crisis statements | Approves or delegates to Law | Posts approved text only | Law drafts where legal |

The friend's arrangement should be written down in one page: unpaid, or a flat fee unrelated to patients or reach (file 10); no access to patient data; confidentiality; what happens if either wants to stop.

#### 6.3 Stop rules: things that pause publishing

Publishing pauses automatically, scheduled items included, when any of these happens. Only he lifts the pause, in writing, after the stated condition.

1. An S1 error is found. *Lift:* corrected, root cause logged.
2. Any notice or complaint from a medical council or regulator. *Lift:* lawyer's written advice.
3. A legal notice, court order or police contact. *Lift:* lawyer's written advice (other subjects may resume earlier).
4. A written objection from the employer. *Lift:* written understanding.
5. A confidentiality incident or credible "is this about me?" message. *Lift:* all scenario content re-checked.
6. Account compromise, or an impersonation in circulation. *Lift:* accounts secured; only the notice is published meanwhile.
7. A data breach. *Lift:* contained and notified as advised.
8. His energy rating at 2 or below for two consecutive weeks, or hours over the cap for four weeks. *Lift:* his own decision after a week off and a pruned calendar.
9. No clinician second reader available. *Scope:* Tier A only.
10. A claims ledger incomplete or a verification step skipped. *Scope:* that piece.
11. A rule change (NMC, TGMC, platform) not yet reviewed. *Lift:* F's note and, if needed, Law's.
12. A public tragedy, communal tension, or the death of a public figure from a cardiac cause before facts are known. *Scope:* 24–72 hours; no commentary on the individual.
13. The friend unavailable for more than two weeks with no backup. *Scope:* drop to the minimum cadence.

A pause is logged with date, trigger, who invoked it and when it was lifted. The number of pauses is reported, not hidden.

#### 6.4 The annual public "impact and corrections" note

Published each January on his website, in English and Telugu, two pages. Read by the lawyer before release because of risk 19.

1. **What was published and taught:** counts of pieces by language; sessions for the public and for trainees; CPR sessions.
2. **What was measured, with denominators:** people enrolled, re-measured and at target in the cohorts; CPR trained and the retention figure. Patient-registry results appear here only as a link to the published or presented audit, described neutrally, with no comparison to others.
3. **What did not work:** null results, abandoned formats, targets missed.
4. **Corrections:** every S1 and S2 correction of the year, what was wrong, how it was found.
5. **Complaints and pauses:** number and type, without identifying anyone.
6. **Money and interests:** who paid for the work; the conflict-of-interest register; "no sponsor, no advertising, no paid reach".
7. **How it is made:** who edits; what AI tools were used for; confirmation that no patient data entered them.
8. **Impersonation:** any fake accounts or videos found and what was done; the list of official channels.
9. **Advisory circle:** names (with consent) and interests.
10. **Next year:** three commitments.

It carries no praise, no testimonials, no ranking and no invitation to book.

---

## So what for Dr. Avinash

Prioritised. Effort is his time unless marked F (friend).

**Before the first public piece (weeks 1–4)**

1. **Retain a health lawyer** and take three things to the first meeting: the Apollo contract (file 17), the friend's role and the "third party" question (file 11), and the criticism rules in 3.1. One-off 2–3 hours; then on call.
2. **Adopt the editorial standard (section 4) as a two-page document** and sign it with the friend. One-off 2 hours. F builds the claims ledger, corrections log and review calendar: 4 hours.
3. **Recruit a clinician second reader** on a reciprocal basis (he reads theirs). One conversation; then about 20 minutes a week.
4. **Engage a Telugu editor**, paid per piece, and run the first listener test on three draft pieces. F: 3 hours.
5. **Publish three standing pages**: "How this is made", conflict-of-interest statement, corrections page (empty but live), alongside file 10's "official channels" page. F drafts in 3 hours; he approves in 30 minutes.
6. **Security hour:** every account in his name, password manager, app or hardware two-factor, recovery codes printed, delegated roles for F. One-off 60–90 minutes together.
7. **Write the one-page agreement with the friend** (decision rights 6.2, no payment linked to patients or reach, no patient data, exit terms). One-off 1 hour; lawyer glances at it.

**In the first quarter**

8. **Start the two weekly guardrails:** hours and a 1–5 energy rating. 1 minute a week.
9. **Pre-approve the five holding statements** and the scripted replies; F keeps them with the takedown kit. 30 minutes.
10. **Seat the advisory circle** (mentor, lawyer, evaluator, patient representative, Telugu editor). Five conversations over 6–8 weeks; first meeting 60 minutes.
11. **Set up the quarterly one-page review** and hold the first one at day 90 with baselines only. F: 45 minutes a month; he: 30 minutes a quarter.
12. **Decide the subject boundaries in writing:** no brand names without legal read; no commentary on AYUSH as a system, on politics, or on any individual's death; evidence and decisions, never colleagues. 20 minutes.

**In the first year**

13. **Ethics approval and consent design for the registry and the cohort evaluation**, with the evaluation adviser, including a wait-list comparison. 6–8 hours one-off (file 19 item 9).
14. **Fill a literature gap as his first public-facing paper:** an audit of the 50 most-viewed Telugu YouTube videos on heart attack, cholesterol or stents using DISCERN, GQS and PEMAT-AV, on the model of the Hindi studies (PMID 36861697; 40124832) and the cholesterol study (PMID 41612669). No Telugu audit is indexed. It gives him the evidence base for "why I teach", a citable paper with trainee co-authors, and a neutral way to describe the naturopathy problem without naming anyone. About 20–30 hours across a small team.
15. **Publish the first annual impact and corrections note** in January 2028 (covering 2027). F drafts in 4 hours; he edits in 1; lawyer reads.
16. **Ask his indemnity insurer** whether cover extends to media activity and defamation defence, and to community events. One e-mail.

**Standing weekly load created by this report:** about 25–35 minutes for him (second-read exchange, sign-offs against the ledger, the two ratings) inside the existing 5–6 hour envelope, and about 2 hours for the friend (ledger, checks, logs).

---

## Risks & things to avoid

- **Do not treat a medical degree as a quality control.** Independent doctors had the worst misinformation rate in the cholesterol audit.
- **Do not let AI supply a citation.** Open every source.
- **Do not lead with "AI" in public descriptions of himself.** The two experiments show a penalty for the label even for administrative use. Show the charter and the verified work instead.
- **Do not name products, companies, practitioners or systems of medicine in criticism without a legal read.** Criticise claims.
- **Do not answer individuals' clinical questions in comments or messages**, however kind the impulse.
- **Do not publish a composite built from one recent patient.** Three patients, six months, changed details, labelled.
- **Do not publish his outcome rates as public claims.** Journal first, link after, lawyer reads.
- **Do not set or report a patient-acquisition number** in this system.
- **Do not rely on YouTube's health-source features**; individuals in India cannot yet apply.
- **Do not let the friend speak as him**, and do not let the friend post praise of him.
- **Do not reply to a legal notice, a council letter or a pile-on himself.**
- **Do not judge the programme on followers, or on anything lagging, before month 6.**
- **Do not keep going when the energy rating says stop.** A paused channel recovers; a resentful doctor does not teach well.
- **Do not promise that posting will raise citations.** Four of six trials say it will not.

---

## Open questions / gaps

1. **Final outcome of *Himalaya Wellness v Philips*** (Bengaluru civil court, Karnataka HC) and of the other proceedings against Dr Philips after mid-2024. Two searches found nothing later than July 2024; needs a court-record search (e-Courts, LiveLaw, Bar & Bench).
2. **Any Indian decision on liability for public online health content or comment replies**, and whether his indemnity policy covers media work and defamation defence. Needs the lawyer and the insurer.
3. **Primary texts not read:** the gazette text of the February 2026 IT Rules amendment (timelines rest on Freshfields and Bar & Bench); the GMC 2024 guidance (403; paragraph numbers from a secondary guide); COPE; the BMJ deepfake articles; the full Shetty decree.
4. **Indian data that do not seem to exist:** a representative survey of where Indians (or Telugu speakers) get health information and how they choose a doctor; any survey of online harassment of Indian doctors; any quality audit of Telugu cardiac video content; a Telugu readability measure or PEMAT validation. The last two are research he could do.
5. **Benchmarks still missing for the KPI tree:** completion and save rates for health video in Telugu; completion rates for doctor-led cohorts in India; his own baselines (LDL at goal, persistence, loss to follow-up, rehab access), which file 19 also lists. Year-3 targets marked "planning" should be reset after two quarters of data.
6. **Whether publishing his own audited outcomes in an annual note is compatible with NMC cl. 6.2 and Reg. 6.1.1**, and where "public health education" ends for procedures he performs (file 11's open question 5). Needs written legal advice.
7. **NHS England and RCP guidance** on doctors' public content and AI assistance was not found; the extended-follow-up result of the ESC Journals trial (Feb 2026) has no abstract and was not read.

---

## Sources

**Academic impact trials**
- ESC Journals Randomized Study, final: https://pubmed.ncbi.nlm.nih.gov/35567549/ ; preliminary: https://pubmed.ncbi.nlm.nih.gov/32306033/ ; extended follow-up (2026): https://pubmed.ncbi.nlm.nih.gov/40981751/
- TSSMN trial, one-year results: https://pubmed.ncbi.nlm.nih.gov/32504611/
- Circulation trials: https://pubmed.ncbi.nlm.nih.gov/25406308/ ; https://pubmed.ncbi.nlm.nih.gov/27121850/
- Int J Public Health: https://pubmed.ncbi.nlm.nih.gov/27193574/ ; https://pubmed.ncbi.nlm.nih.gov/33159529/
- Branch et al., PLoS One 2024: https://pubmed.ncbi.nlm.nih.gov/38507397/

**Behaviour, trust, choice**
- Cochrane, interactive social media: https://pubmed.ncbi.nlm.nih.gov/34057201/
- LMIC social-media review: https://pubmed.ncbi.nlm.nih.gov/35436220/
- Wakefield, mass media campaigns: https://pubmed.ncbi.nlm.nih.gov/20933263/
- Exposure to health misinformation, meta-analyses: https://pubmed.ncbi.nlm.nih.gov/40708117/ ; https://pubmed.ncbi.nlm.nih.gov/39104361/
- Online health community studies: https://pubmed.ncbi.nlm.nih.gov/36419984/ ; https://pubmed.ncbi.nlm.nih.gov/36553956/ ; https://pubmed.ncbi.nlm.nih.gov/39494068/
- Physician social-media behaviour and patient trust: https://pubmed.ncbi.nlm.nih.gov/31663810/
- Orthopaedic surgeon selection: https://pubmed.ncbi.nlm.nih.gov/35044319/
- Commentary on social media and new patients: https://pubmed.ncbi.nlm.nih.gov/25111280/

**Misinformation**
- Walter et al., correction meta-analysis: https://pubmed.ncbi.nlm.nih.gov/32762260/
- Chan et al., debunking meta-analysis: https://pubmed.ncbi.nlm.nih.gov/28895452/
- Nyhan, backfire effect: https://pubmed.ncbi.nlm.nih.gov/33837144/
- Carey et al., ephemeral effects of fact-checks: https://pubmed.ncbi.nlm.nih.gov/35115678/
- Bode and Vraga: https://pubmed.ncbi.nlm.nih.gov/28622038/
- WHO Bulletin review of reviews: https://pubmed.ncbi.nlm.nih.gov/36062247/

**Content-quality audits**
- Cholesterol, YouTube: https://pubmed.ncbi.nlm.nih.gov/41612669/
- Myocardial infarction, YouTube: https://pubmed.ncbi.nlm.nih.gov/37692661/
- Angiography and angioplasty, YouTube: https://pubmed.ncbi.nlm.nih.gov/37885539/
- Hypertension, YouTube: https://pubmed.ncbi.nlm.nih.gov/40050348/
- Coronary heart disease, TikTok: https://pubmed.ncbi.nlm.nih.gov/39226540/
- CPR videos across platforms: https://pubmed.ncbi.nlm.nih.gov/41030356/
- Hindi YouTube: https://pubmed.ncbi.nlm.nih.gov/40124832/ ; https://pubmed.ncbi.nlm.nih.gov/36861697/

**Wellbeing, harassment, violence, India**
- Career fit and burnout: https://pubmed.ncbi.nlm.nih.gov/19468093/
- Burnout in Indian health professionals: https://pubmed.ncbi.nlm.nih.gov/32346250/
- Pendergrast et al., JAMA Intern Med 2021: https://pubmed.ncbi.nlm.nih.gov/33393965/ (full text https://pmc.ncbi.nlm.nih.gov/articles/PMC7783586/)
- Royan et al., JAMA Netw Open 2023: https://pubmed.ncbi.nlm.nih.gov/37314808/
- Workplace violence, India: https://pubmed.ncbi.nlm.nih.gov/28050406/ ; https://pubmed.ncbi.nlm.nih.gov/32946495/ ; https://pubmed.ncbi.nlm.nih.gov/31065192/
- IMA night-duty survey: https://theprint.in/health/no-duty-room-for-45-doctors-on-night-shifts-safety-measures-worse-in-govt-hospitals-says-ima-survey/2244530 ; https://business-standard.com/india-news/35-of-doctors-mostly-women-feel-unsafe-at-night-shifts-says-ima-survey-124083000644_1.html
- Trust: https://pubmed.ncbi.nlm.nih.gov/34161383/ ; https://pubmed.ncbi.nlm.nih.gov/28005537/
- FICCI–EY-Parthenon report (press release): https://ey.com/en_in/newsroom/2025/10/transparency-drives-patient-choice-9-in-10-indians-willing-to-pay-more-for-certified-healthcare-ficci-ey-parthenon-report
- Bengaluru caregivers and social media: https://www.ijcmph.com/index.php/ijcmph/article/view/16204

**Authorship, AI, disclosure**
- ICMJE: https://www.icmje.org/recommendations/browse/roles-and-responsibilities/defining-the-role-of-authors-and-contributors.html
- WAME: https://wame.org/page3.php?id=106
- COPE (403, not read): https://publicationethics.org/guidance/cope-position/authorship-and-ai-tools
- AMA Opinion 2.3.2: https://code-medical-ethics.ama-assn.org/ethics-opinions/professionalism-use-social-media
- GMC (403, not read): https://www.gmc-uk.org/professional-standards/the-professional-standards/using-social-media-as-a-medical-professional/using-social-media-as-a-medical-professional ; secondary guide used: https://www.bridgeheadcommunications.com/insights/2026/08/18/gmc-social-media-guidance-doctors-practical-guide
- BMA: https://www.bma.org.uk/advice-and-support/ethics/personal-ethics/ethics-of-social-media-use
- NMC Guidelines, 6 Oct 2026 (via file 11): https://medicaldialogues.in/pdf_upload/2026/10/07/nmc-guidelines-on-ethical-advertising-and-public-communication-478642.pdf
- Reis et al., Nat Med 2024: https://pubmed.ncbi.nlm.nih.gov/39054373/ ; JAMA Netw Open 2025: https://pubmed.ncbi.nlm.nih.gov/40674054/
- Ghost-writing: https://pubmed.ncbi.nlm.nih.gov/20838656/ ; https://pubmed.ncbi.nlm.nih.gov/27354171/ ; https://pubmed.ncbi.nlm.nih.gov/41166476/
- Fabricated references: https://pubmed.ncbi.nlm.nih.gov/37337480/ ; https://pubmed.ncbi.nlm.nih.gov/37679503/
- Men's Journal: https://futurism.com/neoscope/magazine-mens-journal-errors-ai-health-article
- MAHA report citations: https://washingtonsun.com/health-science/make-america-healthy-again-report-citation-errors?redirected=notus_org
- Dr Ed Hope and Google AI Overview (403; search summary only): https://www.stanventures.com/news/?p=6278

**Deepfakes and personality rights**
- CBS News investigation: https://www.cbsnews.com/news/deepfake-videos-impersonating-real-doctors-push-false-medical-advice-treatments
- BMJ: https://pubmed.ncbi.nlm.nih.gov/39019557/ ; https://pubmed.ncbi.nlm.nih.gov/42114916/
- AMA framework: https://hlth.com/insights/news/ama-introduces-framework-to-shield-doctors-from-ai-deepfakes ; https://www.ama-assn.org/system/files/ai-generated-deepfakes.pdf ; https://pubmed.ncbi.nlm.nih.gov/42361790/
- IT Rules amendment 2026: https://www.freshfields.com/en/our-thinking/blogs/technology-quotient/india-targets-deepfakes-and-ai-generated-content-key-changes-under-meitys-2026-102mjwn ; https://www.barandbench.com/amp/story/news/law-policy/centre-amends-it-rules-to-regulate-ai-generated-content-takedown-timelines-reduced
- Dr Devi Shetty: https://www.livelawbiz.com/personality-rights/delhi-high-court-bars-fake-medical-videos-using-dr-devi-shettys-name-flags-public-health-risk-553873 ; https://theprint.in/judiciary/after-amitabh-bachchan-jackie-shroff-why-delhi-hc-protected-surgeon-dr-shettys-personality-rights/2386506 ; https://www.barandbench.com/news/litigation/delhi-high-court-protects-personality-rights-dr-devi-shetty-narayana-health-trademark
- Arijit Singh: https://globalfreedomofexpression.columbia.edu/cases/singh-v-codible-ventures/ ; https://spicyip.com/2024/08/synthetic-singers-and-voice-theft-bomhc-protects-arijit-singhs-personality-rights-part-i.html
- 2025–26 Delhi HC matters: https://en.wikipedia.org/wiki/Personality_rights
- YouTube health features eligibility: https://support.google.com/youtube/answer/12796915?hl=en

**Defamation, duty of care, consumer law**
- TheLiverDoc: https://retractionwatch.com/2024/07/18/supplement-maker-sues-critic-for-defamation-spurring-removal-of-accepted-abstract/ ; https://scroll.in/article/1056818/why-a-bangalore-court-suspending-liverdoc-x-account-is-legally-unprecedented ; https://www.newslaundry.com/2023/10/10/the-liver-docs-x-account-to-be-restored-if-he-hides-defamatory-tweets-against-himalaya ; https://www.thenewsminute.com/karnataka/karnataka-hc-allows-the-liver-doctor-account-to-be-restored ; https://en.wikipedia.org/wiki/Cyriac_Abby_Philips
- Gulhati and Lundbeck: https://scroll.in/article/1057317/long-before-liver-doc-this-doctor-fought-defamation-by-a-pharma-company-and-won
- Revant Himatsingka: https://en.wikipedia.org/wiki/Revant_Himatsingka
- Bloomberg v Zee: https://main.sci.gov.in/supremecourt/2024/12343/12343_2024_1_19_51717_Judgement_22-Mar-2024.pdf ; https://globalfreedomofexpression.columbia.edu/cases/bloomberg-v-zee-entertainment/ ; https://www.scconline.com/blog/post/2024/03/26/sc-set-aside-order-directing-bloomberg-to-remove-article-on-zee-entertainment-legal-news
- NCDRC on telephone advice: https://medicaldialogues.in/news/health/medico-legal/treatment-of-patient-based-on-telephonic-advice-from-doctor-constitutes-negligence-ncdrc-122320
- Supreme Court, Feb 2025: https://medicaldialogues.in/news/health/medico-legal/sc-quashes-culpable-homicide-charges-against-doctor-for-prescribing-injection-over-phone-143653
- Kerala HC, 2025: https://www.livelaw.in/high-court/kerala-high-court/kerala-high-court-prescribing-medicine-telephone-criminal-negligence-same-course-action-followed-other-medical-professionals-292793
- V.P. Shantha not reconsidered: https://www.livelaw.in/amp/top-stories/supreme-court-refuses-to-reconsider-judgment-which-brought-doctors-under-consumer-protection-act-says-reference-was-unnecessary-274529 ; review dismissed: https://www.livelaw.in/top-stories/supreme-court-doctors-consumer-protection-act-review-petition-against-order-refusing-reconsideration-of-vp-shantha-judgment-dismissed-284299 ; 2026 plea: https://medicaldialogues.in/amp/news/health/doctors/doctors-exclusion-from-consumer-protection-act-supreme-court-issues-notice-to-centre-nmc-164415

**Quality tools and benchmarks**
- PIF TICK criteria: https://pifonline.org.uk/pif-tick/
- PEMAT: https://pubmed.ncbi.nlm.nih.gov/24973195/ ; translations: https://pubmed.ncbi.nlm.nih.gov/36497836/ ; https://pubmed.ncbi.nlm.nih.gov/37200085/ ; https://pubmed.ncbi.nlm.nih.gov/40471382/
- Hypertension cascade (NNMS): https://pubmed.ncbi.nlm.nih.gov/35513442/ ; IHCI: https://pubmed.ncbi.nlm.nih.gov/41314840/ ; PROLIFIC: https://pubmed.ncbi.nlm.nih.gov/34534488/
- Post-ACS adherence registry: https://pubmed.ncbi.nlm.nih.gov/40020999/ ; cardiac rehabilitation capacity in India: https://pubmed.ncbi.nlm.nih.gov/32489801/
- Earlier reports in this folder relied on for benchmarks and rules: 02, 03, 05, 06, 10, 11, 13, 14, 15, 16, 17, 18, 19.
