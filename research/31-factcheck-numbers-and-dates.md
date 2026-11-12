# 31 — Fact-check: numbers, dates and factual claims the plan will quote

**Role:** fact-checker, not researcher. Every item below was re-opened at the best source reachable on **12 November 2026**; the earlier research files were used only to find out what was claimed and where. Verdicts: **Confirmed** / **Corrected** / **Could not verify**. "Confirmed (caveat)" means the number is right but the wording around it needs care.

**Method.** One web search was used (for Dr Sudhir Kumar's X following). Everything else was a direct fetch: Europe PMC REST API (abstracts and open full text), ClinicalTrials.gov API, NLM Catalog and PubMed E-utilities, the NMC register's public search endpoint, YouTube channel "About" pages, Google/YouTube help and application pages, conference and society sites, and primary PDFs (NFHS-5 Telangana state report, GSMA Mobile Gender Gap Report 2025, TGMC fee schedule and CPD notice, CSI fellowship and membership forms, Elsevier APC price list, MCC DrNB seat matrix, arXiv 2608.08235). **Not reachable:** x.com (HTTP 402), Edelman's own PDF (403), rchiips.org (TLS failure), socialblade (403).

**Headline.** Of about 70 separate claims, none is materially wrong. Four need rewording, one contradiction is settled (YouTube Health), and two could not be verified at source (Dr Sudhir Kumar's current X following; the Edelman figure, confirmed only through a secondary report).

---

## Executive verdict table

### 1. Health statistics

| # | Claim as stated | File(s) | Verdict | Corrected / exact figure |
|---|---|---|---|---|
| 1.1 | Bystander CPR in India "1.3–9.8%" | 09 | Confirmed (caveat) | Review's words: "only 1.3%–9.8%". Its own table also lists 0% (two registry arms) and 27.8% (WACAR, any CPR, 139 of 500 with data) |
| 1.2 | Warangal registry, 814 out-of-hospital arrests, zero survivors | 09, 14 | Confirmed (caveat) | 814 subjects, 2018. Paper: "no survivors of OHCA were reported"; authors say resuscitation data were "inadequate". Print "no survivors were reported" |
| 1.3 | 12.6% of Indian hypertensives controlled | 19, 22 | Confirmed (caveat) | 379 of 3,017 (12.6%, 95% CI 11.0–14.3). Survey data are from **2017–18** |
| 1.4 | "21% BP control" | 14 | Confirmed | 21.2% of 7,324 people with hypertension, nine IHCI districts, 2023–24 (up 6.7 points from 2018) |
| 1.5 | 27% of treated coronary patients at LDL goal | 14, 19, 24 | Confirmed | 27.0% (2,603 of 9,658) at ≤50 mg/dL; uptitration in 37.3% of those above goal |
| 1.6 | Statins fall 99.7% to 70% six months after PCI | 19, 22, 24 | Confirmed (caveat) | 99.7% at discharge to 70.0% at 6 months; high-intensity 92.0% to 45.7%. One registry, 716 patients, 20.5% lost to follow-up |
| 1.7 | Symptom-to-hospital delay 5–6 hours in Indian STEMI | 14 | Confirmed (caveat) | 300 min (174 STEMI, one South Indian centre, 2023–24) and 360 min (CREATE, **all ACS, 2001–05**). Not a national STEMI figure |
| 1.8 | "84% fatty liver" in 345 Hyderabad IT employees | 14, 19 | Confirmed (caveat) | 290 of 345 (84.06%). Bhargava et al., *Scientific Reports* 2025. MAFLD by FibroScan (CAP ≥238 dB/m). **Volunteers**, age 30–60 |
| 1.9 | Risk calculators missed about 80% of Indian first-MI patients | 19 | Confirmed | 4,975 first-AMI patients; PREVENT flagged 19.8% and Framingham 20.2% as high risk (≥20%); authors: "80% of patients were still not identified as high risk" |
| 1.10 | PROLIFIC (Kerala) 64% vs 46% at target | 19, 22, 24 | Confirmed | 514/803 (64%) vs 379/819 (46%) met at least 3 of 4 targets at 2 years; OR 2.2 (1.7–2.7) |
| 1.11 | INDIA-WORKS 36% dropout | 24 | Confirmed | 750 of 2,108 did not complete (35.6%); 509 lost to follow-up. Registry results only; no journal paper |
| 1.12 | NAILED-ACS LDL difference | 24 | Confirmed | LDL-C 0.28 mmol/L lower (95% CI 0.135–0.42) at 36 months; systolic BP 4.1 mm Hg lower; 962 randomised, 797 analysed |
| 1.13 | Grampian nurse-led clinics, mortality HR 0.75 | 24 | Confirmed | Deaths 14.5% vs 18.9% at 4.7 years; adjusted HR 0.75 (0.58–0.98); 19 practices, 1,343 patients |
| 1.14 | Himachal STEMI: thrombolysis 27.6% to 65.5% | 15 | Confirmed (caveat) | Table: 8/29 (27.6%) to 167/255 (65.5%). The paper's abstract prints 27.5% and its discussion 26.5%. Baseline is **29 patients** |
| 1.15 | Lp(a)HORIZON (pelacarsen) negative at AHA Nov 2026 | 14 | Confirmed | Presented 7 Nov 2026, AHA, Chicago; 8,350 patients; MACE 12.3% vs 12.1%, HR 1.02 (0.90–1.15); Lp(a) −77.7%; NEJM, with NEJM Evidence companion |
| 1.16 | Yoga-CaRe HF result | 14 | Confirmed (caveat) | 3,492 patients, 16 centres. Quality-of-life co-primary met (8.1 points at 3 months); **clinical co-primary not met** (21% vs 22.8%, HR 0.90, NS). Presentation only |
| 1.17 | TRICORDER (Lancet 2026) negative | 18 | Confirmed | Lancet 2026;407 (epub 28 Jan 2026). 205 practices; heart-failure detection IRR 0.94 (0.86–1.02) |
| 1.18 | FAVOR III Europe negative | 18 | Confirmed | Lancet 2024. 6.7% vs 4.2%, HR 1.63 (1.11–2.41); difference 2.5% (90% CI 0.9–4.2), margin 3.4% not met |
| 1.19 | EAGLE positive | 18 | Confirmed | Nat Med 2021. New low-EF diagnosis 2.1% vs 1.6%, OR 1.32 (1.01–1.61) |
| 1.20 | Edelman: "my doctor" most trusted, 80% | 06, 22 | Confirmed via secondary source only | 2026 Edelman Trust Barometer Special Report: Trust and Health (16 countries). CIDRAP: "80% of survey respondents said their doctor was a trusted source". Edelman PDF returned 403 |
| 1.21 | Misinformation in doctors' cholesterol videos 29% | 22 | Confirmed | 105 YouTube videos; independent doctors published 55.2% and had the highest misinformation rate (29%); overall 21% |
| 1.22 | ChatGPT fabricated 47–55% of references | 22 | Confirmed (caveat) | 47% (115 references, GPT-3.5) and 55% (GPT-3.5; **18% for GPT-4**). Both studies are from **2023** |
| 1.23 | Lower ratings for doctors who mention AI (effect size) | 22 | **Corrected (wording)** | The study did not test doctors mentioning AI. It tested identical advice **labelled** "AI" or "human + AI" vs "human physician": less reliable (d 0.28, 0.29) and less empathetic (d 0.27, 0.26); n = 2,280 |
| 1.24 | NFHS-5 Telangana: 26.5% of women ever used internet (rural 15.8%) | 27 | Confirmed | Urban 43.9, rural 15.8, total 26.5 (men 57.4) |
| 1.25 | GSMA 2025: smartphone ownership 36% women vs 58% men | 27 | Confirmed | India, survey year 2024: mobile 71% / 84%; smartphone 36% / 58%; mobile internet 39% / 58% |
| 1.26 | Weekly radio listening 2% / 6% | 27 | Confirmed | Telangana, age 15–49: women 2.1%, men 6.1% (TV 75.1% / 75.2%) |
| 1.27 | About 1,080 cardiology trainees a year (592 DM; ~485 DrNB) | 19 | Confirmed (caveat) | 592 + 485 = 1,077. Different years and sources: NMC matrix 2026–27 (news report) and MCC counselling matrix 2025 (my recount: 236 entries, 485 seats) |
| 1.28 | Telangana 32 DM + 55 DrNB | 19 | Confirmed | DM 32 (Medical Dialogues table); DrNB 55 seats in 24 hospital entries (my recount) |

### 2. Channels and platforms

| # | Claim as stated | File(s) | Verdict | Corrected / exact figure (12 Nov 2026) |
|---|---|---|---|---|
| 2.1 | Dr M S S Mukharjee / Pulse Heart ~495K, ~170M views | 13, 20 | Confirmed | 495K subscribers; 171,684,784 views; 734 videos; joined 19 Nov 2017 |
| 2.2 | Dr Movva Srinivas 318K, created 6 Feb 2023 | 20 | Confirmed | 318K; 72,429,125 views; 1,421 videos; joined 6 Feb 2023 |
| 2.3 | Dr C Raghu 16.9K | 04, 13 | Confirmed | 16.9K; 2,034,004 views; 326 videos; joined 14 Apr 2015 |
| 2.4 | Dr. Manthena Official 37.9 lakh | 14, 20 | Confirmed | 3.79M; 1.53 billion views; 6,613 videos |
| 2.5 | CARE / Apollo / Yashoda channels ~1.1–1.2M | 04 | Confirmed | CARE 1.2M; Apollo 1.12M; Yashoda 1.11M |
| 2.6 | Dr Sudhir Kumar YouTube 11.4K | 13, 20 | Confirmed | 11.4K; 3,613,821 views; 434 videos; joined 20 Feb 2018 |
| 2.7 | Dr Sudhir Kumar X following ~100K+ | 03, 13 | **Could not verify** | x.com returned 402. Only dated source opened: ThePrint, 20 Jan 2025, "81,200 followers on X". Print "about one lakh (not verified)" or drop the number |
| 2.8 | YouTube Health: can an individual Indian doctor apply? (file 05 yes, file 22 no) | 05, 22 | **Settled: file 05 is right in practice; file 22 quoted the help page correctly but drew the wrong conclusion** | A live India form exists and accepts individuals. The Help Center article omits India from its individual-application country list. See detail 2.8 |
| 2.9 | Thresholds 1,500 public watch hours / 1.5M Shorts views; LegitScript licence check | 05, 22 | Confirmed | Same wording on the Help page and on the India form |
| 2.10 | DataReportal Oct 2026 India: YouTube 573M, Instagram 515M, Facebook 400M, LinkedIn 210M, X 22.9M | 05 | Confirmed (caveat) | Report is **"Digital 2027: India"**, published 4 Nov 2026. Figures are **advertising reach**; LinkedIn's is registered "members" |
| 2.11 | Telugu ASR word error rate 25–29% (IISc 2026) | 23 | Confirmed | arXiv 2608.08235 (8 Aug 2026), Table 3, Telugu, 6 data sets, 17.77 h: Gemini 3 Flash 28.9, Sarvam Saaras v3 28.7, IndicConformer 26.4, SraVaani-1.0 25.1 |
| 2.12 | Descript does not support Telugu | 05, 23 | Confirmed (precise) | Transcription in 25 languages, Telugu not among them. Telugu appears only in the caption-translation list |
| 2.13 | WhatsApp Channels allow 16 admins | 23 | Confirmed (precise) | "You can invite up to 16 **additional** channel admins" |
| 2.14 | LinkedIn forbids account sharing | 23 | Confirmed | User Agreement s. 2.2 (quoted in detail 2.14) |
| 2.15 | Google retired FAQ rich results in May 2026 | 10 | Confirmed | "will no longer appear in Google Search starting May 7, 2026"; documentation removed 15 June 2026 |
| 2.16 | Cureus delisted from Web of Science, Oct 2025 | 07 | Confirmed | Retraction Watch, 27 Oct 2025 |
| 2.17 | Only 3 of 20 top cardiology YouTube channels above 100K (Sept 2024) | 03 | Confirmed | Paubox blog, 27 Sept 2024: York Cardiology 462K, PrevMedHealth 179K, DeBakey CV Education 103K; the other 17 below 34K. A vendor blog list, not a ranking study |

### 3. Dates, criteria and prices

| # | Claim as stated | File(s) | Verdict | Corrected / exact figure |
|---|---|---|---|---|
| 3.1 | TCTAP 2027 case submission 20 Nov 2026 | 16 | Confirmed | "Submission Deadline Extended: Friday, November 20, 2026, 11:59 PM KST". Meeting 20–23 Apr 2027, COEX, Seoul |
| 3.2 | CRT cases 4 Dec 2026 | 16 | Confirmed | "Interesting Cases Deadline: Friday, December 4, 2026". CRT 2027: 6–9 Mar 2027, Washington Hilton |
| 3.3 | EuroPCR 11 Jan 2027 | 16 | Confirmed | Clinical cases and images: "Deadline: 11 January 2027 23:59 CET". EuroPCR 18–21 May 2027 |
| 3.4 | ESC Congress 2027 clinical cases 8 Mar 2027 | 16 | Confirmed | Abstracts 1 Mar 2027; clinical cases 8 Mar 2027; late-breaking 1 Jun. Congress 27–30 Aug 2027, Milan |
| 3.5 | India Live 19–21 Mar 2027, New Delhi, with CHIP-CTO India | 16 | Confirmed | "16th INDIA LIVE 2027, 19th (Fri) – 21st (Sun) March, 2027, Taj Palace, New Delhi", "in partnership with CHIP-CTO India" |
| 3.6 | CSI 2026 annual conference dates and venue | 16 | Confirmed | CSICON 2026 (78th), 3–6 Dec 2026, Palace Grounds, Bengaluru |
| 3.7 | FSCAI criteria: 5 years post-fellowship, 2,000 procedures as primary operator, sponsor | 07, 16 | Confirmed | Exact wording in detail 3.7 |
| 3.8 | FSCAI deadline 28 Feb 2027; induction 2–4 May 2027 | 07, 16 | Confirmed (caveat) | Page says "by February 28" with no year; SCAI 2027 is 2–4 May 2027, Fort Lauderdale. The year is an inference |
| 3.9 | FCSI: 10 years' membership + 2 first-author indexed papers; Rs 30,000; 31 July | 07, 16 | Confirmed | Criterion 4 of 5 alternatives; fee includes the fellowship dinner; last date 31 July each year |
| 3.10 | CSI life membership Rs 20,000 | 07, 16 | Confirmed | "Life Membership Fee Rs. 20,000/-" (foreign US$ 600); proposer and seconder must be CSI members |
| 3.11 | Elsevier APC: Indian Heart Journal USD 360 | 16 | Confirmed | Price list "as of 05-Oct-2026", excluding taxes |
| 3.12 | Elsevier APC: JACC: Case Reports USD 850 | 16 | Confirmed | Same list |
| 3.13 | Is IHJ Cardiovascular Case Reports PubMed-indexed? | 07, 16 | Confirmed: **not indexed** | NLM: "PubMed: Selected citations only"; 9 PubMed records in total. Title ceased 2023; successor "IHJ Cardiovascular Reports" (APC USD 400) has no NLM record |
| 3.14 | TGMC renewal fee Rs 1,000 | 21 | Confirmed | Fee schedule dated 9 Feb 2024, effective 15 Feb 2024. PG degree entry Rs 3,000; super-speciality Rs 5,000 |
| 3.15 | CPD hours (18 for 2026; 24 from 1 Jan 2027) | 21 | Confirmed | Notice of 29 Nov 2023: 6 (2024), 12 (2025), 18 (2026), 24 (2027), 30 (from 1 Jan 2028) |
| 3.16 | Citizens Specialty Hospital is an AHA International Training Centre; BLS Rs 3,500 | 15 | Confirmed (caveat) | Hospital's own page says so; price is for the **Aug 2025** batch. AHA's own directory not checked |
| 3.17 | IIIT-H "AI for Medical Professionals", Rs 30,000 | 18 | Confirmed | iHub-Data, IIIT Hyderabad; 2026 cohort started 1 June 2026; Rs 30,000 working professionals, Rs 25,000 bulk, Rs 15,000 PG students |
| 3.18 | National register: PATHURI AVINASH, APMC/FMR/74749, 25 May 2012; MD General Medicine 2016 (MAHE); DM Cardiology 2020 (WBUHS) | 12, 21 | Confirmed | Re-queried on the NMC register on 12 Nov 2026; one record; all fields match |

---

## Detail by section

All sources below were fetched on 12 November 2026.

### Section 1 — Health statistics

**1.1 Bystander CPR "1.3–9.8%"** (file 09).
Source: Patel et al., "Outcomes of out of hospital sudden cardiac arrest in India: A review and proposed reforms", *Indian Heart Journal* 2023;75 (PMID 37657626; full text PMC10568059).
Found: "the bystander CPR rate in India is reported to be only 1.3%–9.8%, as per previous studies… far below the target goal of 62% set by the American Heart Association". Table 1 lists CARO (Delhi) 1.3%, Pandian 7.4%, Bhat (Manipal) 9.8%, DA-CPR 0% (2,775 patients, Telangana), PAROS 0% (2,006, Telangana), and WACAR 27.8% (139 of 500 with data).
Verdict: **Confirmed.** Print as "1.3% to 9.8% in the studies a 2023 review relied on". Do not call it a national rate.

**1.2 Warangal registry, 814 arrests, zero survivors** (files 09, 14).
Source: Ramaka et al., WACAR, *Indian Heart Journal* 2020;72(6):517–523 (PMID 33357639; PMC7772591).
Found: "The study included 814 subjects of OHCA of presumed cardiac etiology brought to the Mahatma Gandhi Memorial Hospital during January 1, 2018, and December 31, 2018." "Though performance of CPR was reported in 139 subjects, no survivors of OHCA were reported in this study." Abstract: "Data on resuscitation characteristics were inadequate."
Verdict: **Confirmed, with wording.** Say "no survivors were reported".

**1.3 "12.6% of hypertensives controlled"** (files 19, 22).
Source: Amarchand et al., *Journal of Human Hypertension* 2023 (PMID 35513442), National NCD Monitoring Survey 2017–18.
Found: of 10,593 adults, 3,017 (28.5%) hypertensive; "840 (27.9%) were aware, 438 (14.5%) were under treatment and, 379 (12.6%; 95% CI: 11.0-14.3) were controlled."
Verdict: **Confirmed.** State the survey years.

**1.4 "21% BP control"** (file 14).
Source: Ganeshkumar et al., "Change in cascade of care among individuals with hypertension - India hypertension control initiative, 2018-2024", *American Journal of Preventive Cardiology* 2026 (PMID 42827825).
Found: "In 2023-24, 7324 individuals had hypertension; 58.5% were aware of their condition, 44.7% were under treatment, and 21.2% had it under control… absolute improvement of 6.1%, 3.9%, and 6.7%". Separately, Kaur et al., *BMJ Open* 2025 (PMID 41314840): 1,046,512 under IHCI care, "44% BP control" (among those in care).
Verdict: **Confirmed.** 21.2% is population-level in nine districts; 44% is among patients under programme care. Do not mix them.

**1.5 "27% of treated coronary patients at LDL goal"** (files 14, 19, 24).
Source: Puri et al., *JACC: Asia* 2026;6 (PMID 42376721).
Found: 122 cardiologists, 9,658 analysed; median LDL-C 66.1 mg/dL; "only 27.0% (2,603 of 9,658…) having values ≤50 mg/dL"; high-intensity statin 73.3%; combination therapy 11.9%; uptitration "in only 37.3% (2,552 of 6,833)".
Verdict: **Confirmed.** The goal is the Lipid Association of India's ≤50 mg/dL.

**1.6 Statins "99.7% to 70%"** (files 19, 22, 24).
Source: Bana et al., *Indian Heart Journal* 2025;77 (PMID 40020999).
Found: 716 patients, PCI in 714 (99.7%). Discharge: aspirin 97.3%, dual antiplatelets 99.7%, statins 99.7%. Six months: aspirin 83.9%, dual antiplatelets 70.2%, statins 70.0%; "high-intensity statins declined from 92.0 % to 45.7 %"; good adherence 42.7%; 147 (20.5%) lost to follow-up.
Verdict: **Confirmed.** Single registry; say so.

**1.7 Delays "5–6 hours"** (file 14).
Sources: (a) Rao et al., *J Emerg Trauma Shock* 2026 (PMID 41924462): 174 STEMI patients given fibrinolysis, one centre in South India, May 2023–Jan 2024; "median prehospital delay of 300 min (IQR: 195-464)"; door-to-needle 15 min. (b) CREATE, Xavier et al., *Lancet* 2008 (PMID 18440425): 20,468 ACS patients; "median time from symptoms to hospital was 360 (IQR 123-1317) min". (c) Himachal paper (1.14): symptom to first medical contact 300 min before, 173 min after the programme.
Verdict: **Confirmed, with caveat.** CREATE is all ACS and 20 years old; the 300-minute figure is one centre. An Ahmedabad series in file 14 found 90 minutes. Print "often five hours or more".

**1.8 "84% fatty liver"** (files 14, 19).
Source: Bhargava et al., "Prevalence of metabolic dysfunction-associated fatty liver disease among information technology employees in India", *Scientific Reports* 2025;15 (PMID 40128210; PMC11933284). University of Hyderabad with AIG Hospitals; recruitment July 2023–July 2024.
Found: 345 analysed (363 enrolled "through a voluntary recruitment process", age 30–60, secondary causes excluded); "290 (84.06%) employees had increased liver fat accumulation indicating MAFLD"; FibroScan CAP grades S1 238–259, S2 260–289, S3 >290 dB/m; 76.52% high LDL-C; 34.20% metabolic syndrome; median age 38.
Verdict: **Confirmed.** It is a volunteer sample; print "84% of 345 IT employees who came forward for testing".

**1.9 Risk calculators "missed about 80%"** (file 19).
Source: Gupta et al., "Comparison of ASCVD Risk Prediction Models in STEMI: Insights From a South Asian Cohort", *JACC: Asia* 2026 (PMID 42470426).
Found: 4,975 consecutive first-AMI patients aged 40–79; high risk (≥20%) by PREVENT 19.8%, Framingham 20.2%, WHO 15.0%, JBS-3 11.7%, ASCVD-2013 12.3%; "80% of patients were still not identified as high risk before their event".
Verdict: **Confirmed.**

**1.10 PROLIFIC** (files 19, 22, 24). Jeemon et al., *Lancet Global Health* 2021 (PMID 34534488). 750 families, 1,671 participants, mean age 40.8; primary outcome "514 (64%) of 803… and 379 (46%) of 819"; OR 2.2 (1.7–2.7). **Confirmed.**

**1.11 INDIA-WORKS "36% dropout"** (file 24). ClinicalTrials.gov NCT02813668 (API; results first posted 8 Sep 2023). Started 2,108; completed 1,358; not completed 750 (death 4, lost to follow-up 509, withdrawal 148, no longer at worksite 85, medical 4). 750/2,108 = 35.6%. **Confirmed.** Single-group study; registry figures only.

**1.12 NAILED-ACS** (file 24). Henriksson et al., *Scientific Reports* 2021 (PMID 34489516). 962 randomised, 797 analysed at 36 months; "mean LDL-C 0.28 mmol/L lower (95% CI 0.135-0.42)"; SBP 4.1 mm Hg lower. **Confirmed.**

**1.13 Grampian nurse-led clinics** (file 24). Murchie et al., *BMJ* 2003;326:84 (PMID 12521974). 19 practices, 1,343 patients; deaths 14.5% vs 18.9%; "proportional hazard ratios were 0.75 for all deaths (95% confidence intervals 0.58 to 0.98; P=0.036)". **Confirmed.** File 24 marked the counts "[BK]"; they are now verified.

**1.14 Himachal STEMI programme** (file 15). Negi et al., *Indian Heart Journal* 2024;76 (PMID 38885880; PMC11329047). Table 1: thrombolysis 8 of 29 (27.6%) before, 167 of 255 (65.5%) after; symptom-to-thrombolysis 542 to 230 min. The abstract prints "27.5 %" and the discussion "26.5 %". **Confirmed** (27.6% is the table value). Always give the baseline of 29.

**1.15 Lp(a)HORIZON** (file 14). TCTMD, 7 Nov 2026 (fetched); Nissen et al., *NEJM Evidence*, epub 7 Nov 2026 (PMID 42998055): "pelacarsen did not reduce the risk of major adverse cardiovascular events compared to placebo". TCTMD: 8,350 patients, Lp(a) ≥70 mg/dL, median 4.7 years, MACE "12.3% with pelacarsen and 12.1% with placebo (HR 1.02; 95% CI 0.90-1.15)", Lp(a) down 77.7%. Top-line was announced in September 2026 (PMID 42880684). **Confirmed.**

**1.16 Yoga-CaRe HF** (file 14). TCTMD, 8 Nov 2026 (fetched): AHA 2026 late-breaker; 3,492 patients (1,737 vs 1,755), 16 Indian centres; Minnesota questionnaire 8.1 points better at 3 months; 6-minute walk +25.5 m; clinical composite 21% vs 22.8%, HR 0.90, "not statistically significant". No journal paper found in Europe PMC. **Confirmed.** Print as "improved quality of life and walking distance; did not reduce deaths or admissions".

**1.17–1.19 TRICORDER, FAVOR III Europe, EAGLE** (file 18). PMIDs 41619752, 39488224, 33958795. All three results match the abstracts (figures in the table above). **Confirmed.**

**1.20 Edelman "my doctor" 80%** (files 06, 22). Edelman's PDF returned 403. CIDRAP report (fetched): the 2026 Edelman Trust Barometer special report on trust and health, 16 countries; "80% of survey respondents said their doctor was a trusted source of health information, while 73% said the same of medical scientists". **Confirmed through a secondary source only.** "Most trusted in all 16 markets" rests on Fortune (not re-opened).

**1.21 Cholesterol videos "29%"** (file 22). Baydar and Gördük, *European Journal of Cardiovascular Nursing* 2026;25 (PMID 41612669). 105 videos, 32,565,336 views; "Independent doctors were the most frequent publishers (55.2%), but their videos exhibited the highest rate of misinformation (29%)". **Confirmed.** English-language searches; not Indian or Telugu content.

**1.22 ChatGPT references "47–55%"** (file 22). Bhattacharyya et al., *Cureus* 2023 (PMID 37337480): 115 references, "47% were fabricated, 46% were authentic but inaccurate". Walters and Wilder, *Scientific Reports* 2023 (PMID 37679503): "55% of the GPT-3.5 citations but just 18% of the GPT-4 citations are fabricated". **Confirmed.** Always attach "GPT-3.5, 2023".

**1.23 AI and ratings** (file 22). Reis et al., *Nature Medicine* 2024 (PMID 39054373; PMC11564086). Two preregistered studies, n = 2,280; identical advice with the source label manipulated. Study 1: human vs AI, empathy d = 0.27, reliability d = 0.28; human vs human + AI, empathy d = 0.26, reliability d = 0.29. **Corrected wording.** The effect size (about 0.26–0.29) is right. The study is about advice labelled as involving AI, not about a doctor who discloses using AI for drafting.

**1.24 and 1.26 NFHS-5 Telangana** (file 27). NFHS-5 Telangana state report (dhsprogram.com FR374) and fact sheet (OF43.TG). "Women who have ever used the internet (%)": urban 43.9, rural 15.8, total 26.5; men 72.3 / 46.7 / 57.4. Media exposure, age 15–49: radio weekly women 2.1%, men 6.1%; television 75.1% / 75.2%; newspaper 17.1% / 41.6%; no regular media 20.1% / 11.8%; women with no schooling 32.6%. **Confirmed.** Fieldwork 2019–21.

**1.25 GSMA** (file 27). *The Mobile Gender Gap Report 2025* (PDF). India: mobile ownership men 84%, women 71%; smartphone 58% / 36%; mobile internet 58% / 39%. Text: India's smartphone gender gap widened "from 32% in 2023 to 39% in 2024". **Confirmed.**

**1.27–1.28 Trainee numbers** (file 19). DM: Medical Dialogues, 10 Oct 2026 (fetched), NMC seat matrix 2026–27, table total 592; Telangana 32, Andhra Pradesh 31. DrNB: MCC "Final seats matrix for SS counselling 2025, DrDNB SS" (PDF, 92 pages); my independent count of "DNBSS Cardiology (DCRD)" rows gives 236 entries and 485 seats; Telangana 55 seats in 24 entries; Andhra Pradesh 28 in 15. **Confirmed.** Print "roughly 1,000–1,100 a year". File 19 notes an Indian Heart Journal paper giving 202 DrNB seats; not re-checked.

### Section 2 — Channels and platforms

**2.1–2.6 YouTube channels.** Read from each channel's own "About" data on youtube.com:

| Channel (handle) | Subscribers | Views | Videos | Joined |
|---|---|---|---|---|
| Dr M S S Mukharjee \| Pulse Heart (@DrMukharjeeOfficial) | 495K | 171,684,784 | 734 | 19 Nov 2017 |
| Dr. Movva Srinivas (@Dr.MovvaSrinivas) | 318K | 72,429,125 | 1,421 | 6 Feb 2023 |
| Dr Movva srinivas Official (@DrMovvasrinivasOfficial) | 11.8K | 5,572,580 | 218 | 30 Mar 2026 |
| Dr C Raghu \| Interventional Cardiologist (@Drraghucardio) | 16.9K | 2,034,004 | 326 | 14 Apr 2015 |
| Dr. Manthena Official (@dr.manthenaofficial3931) | 3.79M | 1,528,657,520 | 6,613 | 25 Feb 2020 |
| CARE Hospitals (@carehospitalsindia) | 1.2M | 186,401,848 | 4,126 | 1 Jun 2016 |
| Apollo Hospitals (@apollohospitalsindia) | 1.12M | 182,799,422 | 4,325 | 28 Oct 2008 |
| Yashoda Hospitals (@yashodahospitals) | 1.11M | 101,350,507 | 8,561 | 31 Dec 2013 |
| Dr Sudhir Kumar (@HyderabadNeurologist) | 11.4K | 3,613,821 | 434 | 20 Feb 2018 |

All **Confirmed.** Side finding: his own channel "Dr. Avinash Pathuri | Preventive Heart Care" (@dravinashpathuri) shows "Joined Apr 6, 2026" and no subscriber or video counts.

**2.7 Dr Sudhir Kumar on X** (files 03, 13). x.com 402; Nitter mirrors and Social Blade blocked. ThePrint, 20 Jan 2025 (fetched): "Dr Kumar has a reach of 81,200 followers on X… known by his username @hyderabaddoctor". Earlier files hold undated cached snapshots of 95.1K, 102.8K and 111.6K. **Could not verify** the current figure. "100K+" is plausible given 81K in January 2025, but no dated source confirms it.

**2.8 YouTube Health: can an individual Indian doctor apply?** (file 05 vs file 22).
What the official pages say:
- **Help Center article** (support.google.com/youtube/answer/12796915; read in en, en-IN and en-GB; identical): "The criteria and process outlined in this article applies only to health providers based in the US, UK, DE, BR, ID, JP, FR, KR, CA, and MX." "Individuals, companies, and nonprofits with health-focused YouTube channels in the US, Germany, Mexico, Brazil, Indonesia, Japan, France, South Korea, Canada, and the UK can apply". India appears only in the note that accredited hospitals, academic institutions and government bodies "do not need to apply". Outside the listed countries, "organizations… can submit a request via the feedback tool" with "#healthinfo".
- **YouTube Health application hub** (health.youtube/features-application/): the country picker lists Brazil, France, Germany, Indonesia, Japan, Mexico, United Kingdom, United States, Australia, Canada, **India (English)**, Canada (French), Korea. Banner: "We are currently updating our Health Features Program."
- **The India form itself** (services.google.com/fb/forms/youtubehealthapp-in-en/; opened, not submitted; HTTP 200): "YouTube Health features Expansion Application [IN]". "Individuals and organizations who meet the below requirements can apply". Requirements: "You are a licensed professional in one of the eligible professions below in India"; "minimum of 1,500 public watch hours on the channel in the last 12 months or 1.5 million valid public Shorts views in the past 90 days"; channel "primarily focused on health topics"; "no active Community Guidelines strikes"; attest to "CMSS/NAM/WHO information sharing standards". Eligible professions: "Licensed Doctor (eligible to practice medicine in India)", nurse, psychologist. The form offers "Individual" or "Organization" ("Select 'individual' only if the same health professional features in the majority of the channel's videos and is the channel owner"), a state list that includes Andhra Pradesh and Telangana, licence images, "Licensing Authority", "License Number". Data are "shared with LegitScript".

**The truth for an individual Indian doctor in November 2026:** YouTube runs a live India application form that accepts individual licensed doctors, with the 1,500-hour / 1.5-million-Shorts threshold and LegitScript licence verification. File 05 is right. File 22 read the Help Center article correctly, but that article's country list is out of step with YouTube's own application hub, so "individuals in India cannot apply" is wrong. Two cautions remain: the programme is flagged as "currently updating", and whether India applications are being processed and approved now cannot be checked without applying. Plan wording: "apply through the India form once the threshold is met; approval is not assured". The December 2024 Google India announcement cited in file 05 was not re-opened.

**2.10 DataReportal** (file 05). datareportal.com/reports/digital-2027-india, published 4 Nov 2026. "YouTube had 573 million users in India in late 2026" (55.3% of internet users in October 2026; +14.6% year on year); Instagram 515 million; Facebook 400 million; LinkedIn 210 million "members" (+23.5%); X 22.9 million (1.5% of population); Threads 40.4 million; Reddit 170 million. **Confirmed.** These are advertising-reach figures from each platform's ad tools, which the report itself says are not monthly active users.

**2.11 Telugu ASR** (file 23). arXiv 2608.08235, "SraVaani 1.0: Scaling Inclusive Speech Recognition for Indic Languages", submitted 8 Aug 2026. Table 3 values as in the verdict table. **Confirmed.** SraVaani's 25.1% is the authors' own model.

**2.12 Descript** (files 05, 23). descript.com/pricing: "Automatically transcribe your recordings into text in 25 languages, including Catalan, Croatian, Czech, Danish, Dutch, English (US), Finnish, French (FR), German, Greek, Hindi, Hungarian, Italian, Latvian, Lithuanian, Malay, Norwegian, Polish, Portuguese (BR), Romanian, Slovak, Slovenian, Spanish (US), Swedish, and Turkish." Telugu appears only in the translation list. **Confirmed.**

**2.13 WhatsApp Channels** (file 23). WhatsApp Help, "How to create a WhatsApp Channel": "You can invite up to 16 additional channel admins to help you manage your channel." **Confirmed.**

**2.14 LinkedIn** (file 23). LinkedIn User Agreement, "Effective on November 3, 2025", section 2.2 "Your Account": "You will keep your password a secret. You will not share your account with anyone else and will follow our policies and the law." "You agree to: (1) protect against wrongful access to your account (e.g., use a strong password and keep it confidential); (2) not share or transfer your account or any part of it (e.g., sell or transfer the personal data of others by transferring your connections); and (3) follow the law, our list of Dos and Don'ts (below), and our Professional Community Policies." **Confirmed.**

**2.15 Google FAQ rich results** (file 10). Google Search Central documentation changelog: "May 8: Deprecating the FAQ rich result feature… This feature will no longer appear in Google Search starting May 7, 2026." June 15: "Removed documentation for the FAQ rich result feature… The FAQ rich result feature is no longer shown in Google Search results". **Confirmed.**

**2.16 Cureus** (file 07). Retraction Watch, 27 Oct 2025: "Embattled journal Cureus delisted from Web of Science, loses impact factor" (earlier: on hold, 30 Sept 2024). Wikipedia: still in PubMed Central. **Confirmed.**

**2.17 "3 of 20"** (file 03). Paubox, "Top cardiology influencers on Youtube", Farah Amod, 27 Sept 2024. Twenty channels listed with subscriber counts; three above 100K. **Confirmed.** Counts are as of September 2024 (York Cardiology has since grown).

### Section 3 — Dates, criteria and prices

**3.1 TCTAP 2027.** summit-tctap.com/2027/submission_science.html: "Submission Deadline Extended: Friday, November 20, 2026, 11:59 PM KST (UTC +9). Accepted presenters will be notified at the end of January 2027." Site news, 9 Nov 2026: "Deadline Extended! 2 MORE WEEKS". 32nd TCTAP, 20–23 April 2027, COEX, Seoul. **Confirmed.** That is 20:29 IST on 20 November: eight days from today.

**3.2 CRT 2027.** crtmeeting.org: "Abstracts Deadline: Friday, November 20, 2026; Interesting Cases Deadline: Friday, December 4, 2026; Cardiovascular Innovations Deadline: Friday, January 8, 2027; Late-Breaking Trials Deadline: Friday, January 15, 2027"; scholarships 18 Dec 2026; "March 6 – March 9, 2027 | Washington Hilton". **Confirmed.**

**3.3 EuroPCR 2027.** pcronline.com Call for Cases: "Call for Clinical Cases and Images is open! Deadline: 11 January 2027 23:59 CET. Results: end of February"; EuroPCR "18-21 May". **Confirmed.**

**3.4 ESC Congress 2027.** escardio.org ESC Congress page, key-dates cards: "01 Mar 2027 Abstract submission"; "08 Mar 2027 Clinical Case submission"; "01 Jun 2027 Late-Breaking Science submission"; early fee to 31 May, late fee to 31 Jul; 27–30 August 2027, Milan. **Confirmed.**

**3.5 India Live 2027.** chipctoindia.com (IFACI): "MARK YOUR DATES: CHIP-CTO India PARTNERS 16th INDIA LIVE 2027 || 19th (Fri) – 21st (Sun) March, 2027 || Taj Palace, New Delhi"; event listing "16th INDIALIVE 2027 in partnership with CHIP-CTO India". indialive.in returned 403. **Confirmed.**

**3.6 CSICON 2026.** csicon78.com: "CSICON 2026, the 78th Annual Conference of the Cardiological Society of India… 3rd–6th December 2026 at Palace Grounds, Bangalore, Karnataka." csi.org.in home page: "CSICON 2026, 3rd Dec to 6th Dec, 2026, Palace Ground Bangalore". **Confirmed.** (The site header still carries stale "77th… New Delhi" text from 2025; ignore it.)

**3.7–3.8 FSCAI.** scai.org/membership/apply/fellow-scai-fscai: "All FSCAI applicants must be sponsored by an active FSCAI or MSCAI. Sponsors can write a letter of recommendation or complete the online attestation form." "Applications must be completed by February 28 if you would like to be inducted at the upcoming Scientific Sessions." Sub-pathway for those certified outside the USA/Canada: "Certified in cardiovascular or endovascular medicine by the appropriate board in country of certification. Minimum 5 years in practice post-fellowship training and performed a combined total of 2,000 diagnostic and interventional procedures as primary operator. All candidates must have unrestricted privileges in the… catheterization lab and be in good standing as a primary operator." SCAI 2027 Scientific Sessions: "May 2 - 4, 2027… Broward County Convention Center… Ft. Lauderdale". **Confirmed.** The page gives no year for 28 February.

**3.9 FCSI.** CSI Fellowship Form 2026 (PDF; circular dated 09.06.2026; page 3 read as an image). "Following criteria will apply (any one): 1. All past Presidents of CSI, 2. All past Secretaries of CSI, 3. Those who have served for more than 5 years in the Executive committee of CSI, 4. Members of CSI for more than 10 years who have 2 or more publications in Cardiology as first author in indexed journals. + His / her work should be 100% in Cardiology and must have active involvement in cardiac catheterization and / or Echocardiography, treadmill and CCU management. 5. Any member of CSI who has been Professor of Cardiology for 5 years or more in an Institution where DM/DNB Cardiology training is going on." "Every year the last date for applying for fellowship of CSI will be 31st July." "The charges for fellowship will be Rs. 30000/- which will include the fellowship dinner." Intimation by 31 October. **Confirmed.**

**3.10 CSI life membership.** CSI "Application for Membership" form (PDF created 18 Dec 2025): "Life Membership Fee Rs. 20,000/-"; "Life Membership Fee (Foreign Applicant) US$. 600/-"; "letters from the proposer and seconder (Must be CSI Member)". **Confirmed.**

**3.11–3.12 Elsevier APCs.** Elsevier "Article Publishing Charge (APC) price list… Prices as of date: 05-Oct-2026", excluding taxes: Indian Heart Journal (0019-4832) USD 360; JACC: Case Reports (2666-0849) USD 850; IHJ Cardiovascular Reports (2950-4678) USD 400; Indian Pacing and Electrophysiology Journal USD 550; CRM: Interesting Cases USD 920; JACC: Asia USD 4,207. **Confirmed.**

**3.13 IHJ Cardiovascular Case Reports and PubMed.** NLM Catalog record 389880 (E-utilities): title "IHJ cardiovascular case reports"; "Began with Volume 1, issue 1 (January/April 2017); ceased with Volume 7, issue 3/4 (July/December 2023)"; succeeding title "IHJ cardiovascular reports" (ISSN 2950-4678); indexing source "PubMed", coverage "Selected citations only". PubMed search `"IHJ Cardiovasc Case Rep"[Journal]` returns 9 records (JACC: Case Reports returns 6,654). No NLM record for the successor title. **Confirmed: not PubMed-indexed** in any useful sense. A case published there will not be found on PubMed.

**3.14–3.15 TGMC.** Fee schedule, TSMC/GB-2/2024 dated 09.02.2024, "w.e.f. 15.02.2024": "Renewal of Registration: Rs 2000 → Rs 1000"; PG Degree Registration Rs 3000; Super Speciality Registration Rs 5000; NOC Rs 3000. CPD notice dated 29.11.2023 (image read): 6 credit hours from 1 Jan 2024, 12 from 2025, 18 from 2026, 24 from 1 Jan 2027, 30 from 1 Jan 2028. **Confirmed.**

**3.16 Citizens Specialty Hospital.** citizenshospitals.com course page (August 2025 batch): "Citizens Specialty Hospitals (ARTMED Healthcare Private Limited) is an American Heart Association (AHA) certified and Authorized International Training Centre (ITC) Providing; Basic Life Support (BLS) and Advance Cardiac Life Support (ACLS) both Provider and Instructor Courses." "Basic Life Support (BLS): Rs. 3,500/-; Advance Cardiac Life Support (ACLS): Rs. 7,500/-; BOTH BLS and ACLS: Rs. 10,000/-". **Confirmed** as the hospital's own statement and a 2025 price. Ask the hospital for the current fee and ITC number before printing.

**3.17 IIIT-H course.** ihub-data.ai course page (via fetch summary): "AI for Medical Professionals – 2026", "Starts June 1st 2026"; online, about 3 hours a week, four modules; working professionals "Rs 30,000", bulk (20+) "Rs 25,000", PG students "Rs 15,000"; certificate jointly from IIIT-H, iHub-Data and NAMS. **Confirmed.** The next cohort date is not published.

**3.18 National Medical Register.** NMC Indian Medical Register public search (nmc.org.in/indian-medical-register/search, name query), one record: name "PATHURI AVINASH"; registration "APMC/FMR/74749"; registration date "25-05-2012"; "Andhra Pradesh Medical Council"; M.B.B.S 2012, Dr. NTR University of Health Sciences, Vijayawada; "MD -GENERAL MEDICINE", 2016, Manipal Academy of Higher Education; "DM - CARDIOLOGY", 2020, West Bengal University of Health Sciences, Kolkata. **Confirmed.** (The public record also displays personal details; they are deliberately not copied here.) His Telangana (TGMC) renewal status still cannot be seen from outside.

---

## Figures the synthesis should stop using (or must reword)

1. **"People rate a doctor who mentions AI lower (d 0.2–0.3)."** Reword: "identical medical advice was rated less reliable and less empathetic when labelled as AI or human + AI (d about 0.26–0.29; Nature Medicine 2024)". The study did not test a doctor disclosing AI help with drafting.
2. **"Individuals in India cannot apply to YouTube Health" (file 22).** Wrong. Use: "an India application form for individual licensed doctors is live; threshold 1,500 public watch hours in 12 months or 1.5 million Shorts views in 90 days; programme marked as being updated; approval not assured".
3. **"Dr Sudhir Kumar has 100K+ X followers"** as a stated fact. Not verifiable today; the last dated figure opened is 81,200 (January 2025).
4. **"Zero survivors" as a measured survival rate.** Use "no survivors were reported among 814 arrests brought to one Warangal hospital in 2018".
5. **"Indian STEMI patients take 5–6 hours"** as a national fact. Use "five hours in a 2023–24 South Indian series; six hours in the 2001–05 national ACS registry".
6. **"84% of Hyderabad IT employees have fatty liver"** without the sample. Use "84% of 345 IT employees who volunteered for testing".
7. **"ChatGPT fabricates half its references"** in the present tense. The studies are 2023, GPT-3.5 (GPT-4: 18%).
8. **"Yoga-CaRe HF was positive"** without the second half. It improved quality of life; it did not reduce events; not yet published.
9. **"DataReportal Oct 2026 users".** These are ad-reach figures from "Digital 2027: India"; LinkedIn's 210M is registered members.
10. **"Himachal thrombolysis rose from 27.6%"** without "8 of 29 patients".
11. **"About 1,080 trainees a year"** as a precise count. Use "roughly 1,000–1,100" (592 DM, 2026–27 matrix; 485 DrNB, 2025 counselling matrix).
12. **"IHJ Cardiovascular Case Reports"** as a current journal name. It ceased in 2023; the current title is IHJ Cardiovascular Reports, not PubMed-indexed, APC USD 400.
13. **"BLS at Rs 3,500"** as a current price. It is the August 2025 batch price.
14. **"My doctor is the most trusted, 80% (Edelman)"** with an Edelman link. Cite the CIDRAP report unless someone opens the Edelman PDF by hand.

## Figures safe to print (verified at source, 12 Nov 2026)

**Health**
- 12.6% of Indian adults with hypertension had it controlled (national survey 2017–18; n = 3,017 hypertensives).
- 21.2% controlled in nine IHCI districts, 2023–24; 44% among 1.05 million patients under IHCI care.
- 27.0% of 9,658 treated Indian coronary patients had LDL-C ≤50 mg/dL; treatment stepped up in 37.3% of the rest (JACC: Asia 2026).
- Statin use 99.7% at discharge, 70.0% at six months; high-intensity statin 92.0% to 45.7% (716 patients, Indian Heart Journal 2025).
- Risk calculators classed only about 20% of 4,975 Indian first-heart-attack patients as high risk beforehand (JACC: Asia 2026).
- PROLIFIC: 64% vs 46% met three of four targets at two years (OR 2.2).
- NAILED-ACS: LDL-C 0.28 mmol/L lower at 36 months. Grampian clinics: deaths 14.5% vs 18.9%, HR 0.75 (0.58–0.98).
- INDIA-WORKS: 750 of 2,108 (35.6%) did not complete.
- Lp(a)HORIZON: 12.3% vs 12.1%, HR 1.02 (0.90–1.15); AHA, 7 Nov 2026; NEJM.
- TRICORDER IRR 0.94 (0.86–1.02); FAVOR III Europe 6.7% vs 4.2%, non-inferiority not met; EAGLE 2.1% vs 1.6%, OR 1.32.
- Bystander CPR 1.3–9.8% in Indian studies (2023 review); AHA target 62%.
- Independent doctors' cholesterol videos: 29% contained misinformation (105 videos, 32.6 million views).
- NFHS-5 Telangana: 26.5% of women had ever used the internet (rural 15.8%, urban 43.9%); weekly radio 2.1% of women, 6.1% of men; weekly television 75%.
- GSMA 2025 (India): smartphone ownership 36% of women, 58% of men.
- DM Cardiology seats 592 (2026–27), Telangana 32; DrNB Cardiology 485 seats in 236 hospitals (2025 counselling), Telangana 55 in 24.

**Channels and platforms**
- All nine YouTube channel figures in the table in section 2.1–2.6.
- YouTube Health thresholds: more than 1,500 public watch hours in 12 months, or 1.5 million public Shorts views in 90 days; LegitScript verifies the licence.
- India ad reach, late 2026: YouTube 573M, Instagram 515M, Facebook 400M, X 22.9M; LinkedIn 210M members.
- Telugu speech-recognition word error 25.1–28.9% across four systems (IISc, August 2026).
- Descript transcribes 25 languages, not Telugu. WhatsApp Channels: up to 16 additional admins. LinkedIn User Agreement s. 2.2: "You will not share your account with anyone else".
- Google FAQ rich results ended 7 May 2026. Cureus delisted from Web of Science, October 2025.

**Dates, criteria, prices**
- TCTAP 2027 abstracts and cases: Fri 20 Nov 2026, 23:59 KST. CRT 2027 interesting cases: Fri 4 Dec 2026. EuroPCR 2027 cases and images: 11 Jan 2027, 23:59 CET. ESC Congress 2027: abstracts 1 Mar, clinical cases 8 Mar 2027.
- CSICON 2026: 3–6 Dec 2026, Palace Grounds, Bengaluru. India Live 2027: 19–21 Mar 2027, Taj Palace, New Delhi, with CHIP-CTO India. SCAI 2027: 2–4 May 2027, Fort Lauderdale.
- FSCAI (certified outside USA/Canada): 5 years post-fellowship practice, 2,000 diagnostic and interventional procedures as primary operator, sponsor who is an active FSCAI or MSCAI; apply by 28 February.
- FCSI: more than 10 years' CSI membership plus 2 first-author papers in indexed journals; Rs 30,000; 31 July each year. CSI life membership Rs 20,000.
- Elsevier list APCs (5 Oct 2026): Indian Heart Journal USD 360; JACC: Case Reports USD 850; IHJ Cardiovascular Reports USD 400.
- TGMC: renewal Rs 1,000; MD entry Rs 3,000; DM entry Rs 5,000; CPD 18 hours for a 2026 renewal, 24 from 1 Jan 2027, 30 from 1 Jan 2028.
- IIIT-H iHub-Data "AI for Medical Professionals": Rs 30,000 for working professionals.
- Register: PATHURI AVINASH, APMC/FMR/74749, 25 May 2012; MD General Medicine 2016 (MAHE); DM Cardiology 2020 (WBUHS).

## Open items for a human

1. Dr Sudhir Kumar's current X follower count: open x.com/hyderabaddoctor in a browser.
2. Edelman 2026 Trust and Health PDF: open by hand to confirm "80%" and the "most trusted in all 16 markets" wording.
3. YouTube Health: whether India applications are being processed during the "updating" period (ask a Telugu doctor-creator who holds the panel, or apply when eligible).
4. Citizens Specialty Hospital: current BLS fee and AHA ITC identifier.
5. FSCAI: confirm with SCAI that 28 February 2027 is the cut-off for the May 2027 induction, and the dues tier for India.
6. TGMC status of 74749 (needs his login).

## Sources

All fetched 12 November 2026.

**Papers (Europe PMC API, abstracts or full text)**
- https://europepmc.org/article/MED/37657626 (PMC10568059) — OHCA in India review
- https://europepmc.org/article/MED/33357639 (PMC7772591) — WACAR
- https://europepmc.org/article/MED/35513442 — hypertension cascade, NNMS 2017–18
- https://europepmc.org/article/MED/42827825 — IHCI cascade 2018–2024
- https://europepmc.org/article/MED/41314840 — IHCI 15 states
- https://europepmc.org/article/MED/42376721 — LDL-C goal attainment
- https://europepmc.org/article/MED/40020999 — adherence after ACS/PCI
- https://europepmc.org/article/MED/41924462 — time to fibrinolysis
- https://europepmc.org/article/MED/18440425 — CREATE
- https://europepmc.org/article/MED/40128210 (PMC11933284) — MAFLD in IT employees
- https://europepmc.org/article/MED/42470426 — risk models in first AMI
- https://europepmc.org/article/MED/34534488 — PROLIFIC
- https://europepmc.org/article/MED/34489516 — NAILED-ACS
- https://europepmc.org/article/MED/12521974 — Grampian clinics
- https://europepmc.org/article/MED/38885880 (PMC11329047) — Himachal STEMI
- https://europepmc.org/article/MED/42998055 ; https://europepmc.org/article/MED/42880684 — pelacarsen
- https://europepmc.org/article/MED/41619752 — TRICORDER
- https://europepmc.org/article/MED/39488224 — FAVOR III Europe
- https://europepmc.org/article/MED/33958795 — EAGLE
- https://europepmc.org/article/MED/41612669 — cholesterol videos
- https://europepmc.org/article/MED/37337480 ; https://europepmc.org/article/MED/37679503 — ChatGPT references
- https://europepmc.org/article/MED/39054373 (PMC11564086) — believed AI involvement
- https://clinicaltrials.gov/study/NCT02813668 — INDIA-WORKS (API v2)

**News and reports**
- https://www.tctmd.com/news/full-lpahorizon-results-affirm-lack-pelacarsen-benefit-secondary-prevention
- https://tctmd.com/news/yoga-care-qol-and-functional-gains-seen-hfref-patients
- https://www.cidrap.umn.edu/public-health/new-global-health-misinformation-survey-reveals-deep-divides
- https://dhsprogram.com/pubs/pdf/FR374/FR374_Telangana.pdf ; https://dhsprogram.com/pubs/pdf/OF43/OF43.TG.pdf
- https://www.gsma.com/wp-content/uploads/2025/12/The-Mobile-Gender-Gap-Report-2025.pdf
- https://medicaldialogues.in/news/education/nmc-pg-matrix-2026-27-592-dm-cardiology-seats-listed-74-in-tamil-nadu-180939
- https://medicaldialogues.in/pdf_upload/2026/03/12/mcc-neet-ss-final-seats-matrix-for-ss-counelling-2025-drdnb-ss-332346.pdf
- https://theprint.in/health/the-age-of-health-fluencers-blending-humour-expertise-to-bust-myths-promote-health-literacy/2452599
- https://retractionwatch.com/?s=Cureus+Web+of+Science ; https://en.wikipedia.org/wiki/Cureus
- https://www.paubox.com/blog/top-cardiology-influencers-on-youtube

**Platforms**
- https://www.youtube.com/@DrMukharjeeOfficial/about ; /@Dr.MovvaSrinivas ; /@DrMovvasrinivasOfficial ; /@Drraghucardio ; /@dr.manthenaofficial3931 ; /@carehospitalsindia ; /@apollohospitalsindia ; /@yashodahospitals ; /@HyderabadNeurologist ; /@dravinashpathuri
- https://support.google.com/youtube/answer/12796915?hl=en (also hl=en-IN, hl=en-GB)
- https://health.youtube/features-application/
- https://services.google.com/fb/forms/youtubehealthapp-in-en/
- https://datareportal.com/reports/digital-2027-india
- https://arxiv.org/abs/2608.08235 ; https://arxiv.org/html/2608.08235
- https://www.descript.com/pricing
- https://faq.whatsapp.com/794229125227200
- https://www.linkedin.com/legal/user-agreement
- https://developers.google.com/search/docs/appearance/structured-data/faqpage (redirects to the documentation changelog)
- https://x.com/hyderabaddoctor (402, not readable)

**Conferences, societies, fees**
- https://www.summit-tctap.com/2027/ ; https://www.summit-tctap.com/2027/submission_science.html
- https://crtmeeting.org/
- https://www.pcronline.com/Courses/EuroPCR/call-for-submissions/Call-for-Cases
- https://www.escardio.org/events/congresses/esc-congress/
- https://www.chipctoindia.com/
- https://csicon78.com/ ; https://www.csi.org.in/
- https://www.scai.org/membership/apply/fellow-scai-fscai ; https://www.scai.org/education-and-events/events-schedule/scai-2027-scientific-sessions
- https://csi.org.in/frontend/cdn/notices/Fellowship%20Form%202026.pdf
- https://www.csi.org.in/frontend/cdn/notices/1852002086338970.pdf
- https://legacyfileshare.elsevier.com/els_com_pricing/article-publishing-charge.xlsx
- https://eutils.ncbi.nlm.nih.gov/entrez/eutils/efetch.fcgi?db=nlmcatalog&id=389880 (NLM Catalog) ; PubMed E-utilities journal counts
- https://onlinetsmc.in/wp-content/uploads/2024/02/TSMC-Revised-Fee-structure-Feb2024.pdf
- https://onlinetsmc.in/wp-content/uploads/2023/12/CreditPoints.jpg
- https://www.citizenshospitals.com/coursedetail/aha-bls-and-clscourse
- https://ihub-data.ai/archives/courses/ai-for-medical-professionals-2026/
- https://nmc.org.in/information-desk/indian-medical-register (public search endpoint https://nmc.org.in/indian-medical-register/search)
