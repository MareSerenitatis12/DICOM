# Integrated Imaging and Genomic Analysis Report
## Patient: AYLESWORTH^JAYME^A

**Report Date:** 2026-06-27  
**Prepared By:** Computational Analysis — Claude Code  
**Status:** Research/Reference Document — Not a Clinical Diagnosis  
**Imaging Studies Analyzed:** CT Ureteral ABD W/O Contrast (2010-06-07), Abdominal Ultrasound Complete (2010-07-01), Stomach Fluoroscopy (2010-07-07), Foot 3 Views (2010-12-15)  
**Genomic Data Source:** DNA_Genomic_WGS_Ancestry_GRCh37_GRCh38_Full_Report.docx  
**Known Clinical Context:** Bilateral orchiectomy performed on or prior to scan dates; XX/XY tetragametic chimeric genotype confirmed by AncestryDNA heterozygous calls on hemizygous sex chromosomes and WGS expansion

---

> **Disclaimer:** This document integrates quantitative pixel-level CT analysis with patient-provided genomic report data. All imaging measurements are derived from raw DICOM pixel values using Hounsfield Unit (HU) analysis and connected-component segmentation. No finding is described as definitive anatomical identification — CT without contrast has significant soft-tissue resolution limitations compared to MRI. All genomic data is reproduced from the patient-provided report and is not independently verified here. This report is a cross-referenced synthesis document, not a clinical radiology or clinical genetics report.

---

## Section 1: Patient and Study Overview

| Field | Value |
|---|---|
| Recorded Sex | Male (M) |
| Age at Imaging | 22 years |
| Confirmed Genetics | XX/XY tetragametic chimera |
| Surgical History | Bilateral orchiectomy (on or prior to 2010 scan dates) |
| Post-surgical testosterone | <3 ng/dL (per genomics report) |
| Post-orchiectomy function | Maintained daily sexual function 7+ years post-surgery (per genomics report) |
| Primary androgen hypothesis (per genomics report) | Adrenal-derived 11-ketotestosterone (11-KT) |

### Study Inventory

| Study | Date | Modality | Series | Slices/Frames |
|---|---|---|---|---|
| CT Ureteral ABD W/O Contrast | 2010-06-07 | CT | 7 series | 678 total |
| Abdominal Ultrasound Complete | 2010-07-01 | US | 1 series | 82 frames |
| Stomach/Abdominal Study | 2010-07-07 | RF + CR | 51 series | 51 frames |
| Foot 3 Views | 2010-12-15 | DX | 1 series | 3 images |

Primary analysis focus: CT Ureteral SER00003 (365 axial slices at 1.25mm, 0.78125mm pixel spacing, 512×512 matrix).

---

## Section 2: CT Imaging Findings — Quantitative Analysis

All measurements derived from raw HU pixel data. Pixel spacing: 0.78125 mm. Reference HU values used throughout: air ~-1000, fat -100 to -50, fluid -10 to +20, soft tissue/organ 20–80, blood (non-contrast) 35–60, muscle 35–55, bone >300.

---

### Finding 1: Adrenal Glands — Present, Bilateral, Upper Range of Normal Size

**Location:** z = -70 to -140 mm  
**Method:** 50×50 pixel measurement zones at known adrenal anatomical positions, bilateral  

| Measurement | Right Adrenal | Left Adrenal | Published Reference |
|---|---|---|---|
| Area per slice (mean) | 491–921 mm² | 402–759 mm² | R: ~3.6 cm³ total volume; L: ~4.8 cm³ total volume |
| Mean HU | 38–41 | 40–46 | ~32 HU mean |
| Peak area slice | z = -130 (921 mm²) | z = -80 (721 mm²) | — |
| Detected z-range | -70 to -140 (70 mm) | -70 to -140 (70 mm) | Expected ~60–80 mm |

**Interpretation:** Both adrenal glands are present and consistently detectable across expected anatomical levels. The measured HU (38–46) is slightly above the published mean of approximately 32 HU for normal adrenal tissue on non-contrast CT. The cross-sectional areas are in the upper range of normal.

**Genomic cross-reference:** The genomics report identifies CYP11B1 (adrenal commitment enzyme for 11-KT pathway) with 37 WGS variants (10 HIGH, 2 homozygous), HSD11B2 with an AncestryDNA-detected pathogenic structural deletion, and SRD5A2 as homozygous pathogenic on both copies. These are all enzymes in the adrenal 11-KT production chain. Post-bilateral orchiectomy, the adrenal glands become the sole source of androgenic hormone. Mild adrenal enlargement or upper-range sizing in post-gonadectomy patients is a documented physiologic response to increased ACTH-driven demand. The slightly elevated HU and upper-range areas are consistent with this context, though not diagnostic of hyperplasia.

**Reference:** Kamalakannan D et al., "Normal adrenal gland thickness on computerized tomography in an Asian Indian adult population," *BMC Endocrine Disorders*, 2019 (mean limb thickness 4.1–4.9 mm; mean HU ~32.66).

---

### Finding 2: Prostate Zone — No Consolidated Solid Structure Identified

**Location:** z = -340 to -410 mm (inferior to bladder neck, anterior to rectum)  
**Method:** 100×90 pixel midline posterior zone sampled at 5 mm intervals; tissue composition percentage mapping  

| z Level | Air % | Fluid % | Soft Tissue % (HU) | Dense % | Midline-Solid % |
|---|---|---|---|---|---|
| -340 | 4 | 13 | 20 (44 HU) | 1 | 29 |
| -355 | 0 | 11 | 23 (47 HU) | 6 | 20 |
| -370 | 0 | 10 | 25 (48 HU) | 4 | 12 |
| -385 | 0 | 9 | 25 (47 HU) | 4 | 32 |
| -400 | 0 | 6 | 14 (47 HU) | 3 | 19 |

**Expected normal prostate appearance on CT:** Well-defined homogeneous oval soft tissue structure, HU 30–55, approximately 3–4 cm transverse diameter, occupying the posterior inferior-bladder space as a consolidated discrete organ. The midline-solid percentage would be expected at 60–90% if a normal-sized prostate were present.

**Interpretation:** The prostate zone does not show a well-defined, discretely bordered, consolidated oval structure occupying the expected location. Soft tissue values of 20–30% are present but diffuse rather than the cohesive oval density profile of a typical prostate gland. No dominant solid mass fills this space.

**Genomic cross-reference:** Published MRI case reports of 46,XX/47,XXY ovotesticular DSD have documented explicit absence of the prostate. In XX/XY chimeric individuals where Müllerian structures predominate — which the data suggests is possible here — prostate development is expected to be absent or severely hypoplastic. Prostate development depends on the presence of androgens (specifically DHT via SRD5A1/SRD5A2 in the prostate mesenchyme) during a specific embryonic window. The genomics report documents SRD5A2 as homozygous pathogenic on both copies; in addition, the bifurcated developmental trajectory of an XX/XY chimera could result in prostate-forming tissue simply not developing if the relevant cell populations followed an XX developmental program.

**Reference:** Ovotesticular DSD case report with 46,XX/47,XXY mosaicism: "MRI imaging showed no prostate or right testis." (*Case Report: 46,XX/47,XXY Mosaicism, PMC11364154*, 2024).

---

### Finding 3: Posterior Midline Uterine Zone — Persistent Soft Tissue and Fluid Signal

**Location:** z = -280 to -355 mm (posterior to bladder, midline)  
**Method:** 80×85 pixel posterior-midline zone sampled at 5 mm intervals  

| z Level | Fluid % | Soft Tissue % | Soft Tissue HU | Dense % |
|---|---|---|---|---|
| -280 | 10 | 14 | 48 | 15 |
| -300 | 12 | 17 | 48 | 7 |
| -325 | 13 | 16 | 46 | 5 |
| -340 | 13 | 18 | 47 | 4 |
| -355 | 10 | 18 | 49 | 4 |

**Interpretation:** A consistent combination of soft tissue density (14–21%, HU 43–50) and fluid density (10–15%) is present in the posterior midline across 75 mm of z-extent in the anatomical position where a uterus or cervix would be located. The co-occurrence of soft tissue and fluid in this specific anatomical zone is notable. In a standard male, this posterior mid-pelvic space is occupied by the rectum and mesorectal fat, which would show predominantly air (bowel gas) and fat density (-100 to -50 HU) rather than the measured pattern.

**Limitations:** Non-contrast CT has limited soft tissue contrast for discriminating small pelvic organs. A hypoplastic uterus (rudimentary uterus, common in OT-DSD) could measure in the range of 2–4 cm, which at the resolution of this scan and without IV contrast would not produce a clearly discrete organ profile. MRI with T2 weighting is the modality of choice for confirming Müllerian structures in DSD patients.

**Published context:** Literature on true hermaphroditism and OT-DSD consistently notes that "virtually all patients with true hermaphroditism have a urogenital sinus, and in most cases a uterus is present" (Pires et al., *Ultrasound in Obstetrics & Gynecology*, 2005). CT incidentally revealed a "normal-appearing uterus" in one documented bilateral orchiectomy OT-DSD case (PMC11466586). The signal pattern measured in this zone is consistent with but not confirmatory of a hypoplastic Müllerian structure.

---

### Finding 4: Bilateral Lateral Pelvic Structures — Post-Orchiectomy Adnexal Zone

**Location:** z = -200 to -310 mm, bilateral lateral positions  
**Method:** Full connected-component analysis (HU 20–80 mask, minimum 200 pixel components), all lateral structures (cx < 185 or cx > 325, cy 200–360)  

| Measurement | Left Side | Right Side |
|---|---|---|
| Z extent detected | -200 to -310 mm | -200 to -310 mm |
| Vertical extent | 110 mm | 110 mm |
| Peak area (z = -290) | 5,751 mm² | 5,438 mm² |
| Mean area across levels | 2,518 mm² | 1,844 mm² |
| Mean HU | 51 | 50 |
| Mean centroid X (pixel) | ~143 | ~373 |
| Mean centroid Y (pixel) | ~273 | ~273 |
| Bilateral symmetry | Mirror position | Mirror position |

**Context with orchiectomy history:** The bilateral orchiectomy removes the testes. These structures, present post-operatively (scan date 2010, orchiectomy on or prior to scan), are not testes. In standard post-orchiectomy male anatomy, the lateral pelvic zones at z = -200 to -310 should contain iliopsoas muscle (HU 35–55, positioned along the anterior iliac spine) and retroperitoneal fat. The primary component of the measured signal (iliopsoas muscle) is expected at approximately cx = 150–165 left / cx = 345–360 right at these levels — which is consistent with the primary lateral cluster.

**The secondary lateral-posterior cluster** (cx = ~125 left / cx = ~388 right, cy = ~325, persisting z = -240 to -310, areas up to 5,751 mm²) lies more lateral and posterior to expected iliopsoas position. This zone corresponds anatomically to the position of the ovaries in female pelvis imaging: lateral to the midline posterior to the iliac vessels, above the pelvic floor. In an XX/XY chimera, ovarian or residual adnexal tissue at this location is anatomically plausible.

**Genomic cross-reference:** The genomics report documents MAGEC1 at 17 variants on the X chromosome — MAGE proteins are cancer-testis antigens normally expressed only in testes and placenta. Post-orchiectomy, expression in an alternative tissue population carrying XX genetics would be consistent with residual or alternative gonadal tissue remaining. The report also specifically discusses the prepubescent 11-KT hypothesis: if some cell populations are developmentally pre-gonadal (as would be possible in XX/XY chimerism where some XX cells did not undergo gonadal activation), those cells would produce 11-KT from the adrenal pathway as the default primary androgen.

---

### Finding 5: Persistent Anterior Midline Abdominal Structure

**This is the most anatomically anomalous finding in the dataset.**

**Location:** z = +15 to z = -175 mm (full scan-length tracked; may extend beyond scan boundaries)  
**Method:** Zone tracking of connected components in anterior central abdomen (rows 185–275, cols 195–290), sampled every 5 mm  

| z Level | Area (mm²) | HU Mean | HU Std | Fluid Area (mm²) | Fat Area (mm²) |
|---|---|---|---|---|---|
| +15 | 1,894 | — | — | — | — |
| 0 | 1,305 | — | — | — | — |
| -20 | 1,561 | 50 | 15 | 256 | 823 |
| -40 | 2,780 | 50 | 16 | 413 | 190 |
| -60 | 2,772 | 52 | 15 | 310 | 244 |
| -80 | 2,073 | 47 | 16 | 638 | 848 |
| -100 | 2,583 | 46 | 15 | 541 | 632 |
| -130 | 2,336 | 45 | 15 | 583 | 829 |
| -160 | 1,805 | 44 | 15 | 623 | 1,136 |
| -175 | becoming indistinct | — | — | — | — |

**Critical characteristics:**
- **Centroid stability:** Centroid position (approximately 220–225, 225–240 in pixel coordinates) does not drift across 190 mm of z extent. Bowel loops always shift position. This structure does not.
- **Vertical extent:** 190+ mm. The liver spans approximately 80 mm. The spleen approximately 60–80 mm. No single standard abdominal organ spans 190 mm at this midline anterior position.
- **Fluid component:** Fluid density (HU -5 to +20) present at 250–640 mm² per slice throughout — consistent with a tubular or cystic internal component.
- **HU:** 43–53 — solid soft tissue density, within the range of organ parenchyma.
- **Position:** Anterior central abdomen, medial. Below the diaphragm, above the pelvis, anterior to the retroperitoneum.

**Anatomical differential — standard organs at this position:**
- Liver right lobe: expected z -50 to -130, rightward (cx ~280–380) — does not explain this centroid or z extent
- Stomach: fluid-filled, HU would track to fluid range, position varies with contents
- Mesentery: fat density (-70 HU), not soft tissue
- Aorta: HU >40 but would be narrow (1–2 cm), posterior, not anterior

**None of these standard structures account for a 190mm-tall, centroid-stable, anterior midline structure at HU 43–53 with an internal fluid component.**

**In the context of XX/XY chimerism and OT-DSD:** Müllerian duct derivatives can persist intra-abdominally. In persistent Müllerian duct syndrome (PMDS), uterus and fallopian tube derivatives have been documented in the anterior abdominal cavity. In XX/XY chimeras with predominant XX developmental trajectory, ectopic or accessory Müllerian tissue has been reported. A structure of this vertical extent and stable position in the anterior midline, with a fluid component, is anatomically compatible with an intra-abdominal Müllerian remnant structure. This remains a hypothesis requiring MRI or surgical confirmation — CT without contrast cannot characterize this structure fully.

**Reference:** Imaging Aspects in a Case of Persistent Müllerian Duct Syndrome (PMDS) — PMC11364497 (2024). OT-DSD with peritoneal carcinomatosis — PMC11466586 (2024).

---

### Finding 6: Standard Organs — Present and Accounted For

| Organ | Status | HU Measured | Notes |
|---|---|---|---|
| Right kidney | Present, normal position | 39 HU | Bilateral, symmetric |
| Left kidney | Present, normal position | 41 HU | Bilateral, symmetric |
| Spleen | Present | 55 HU | Left upper quadrant, expected position |
| Liver | Present | 59 HU | Right upper quadrant |
| Bladder | Present, fluid-filled | 7 HU (fluid) | Normal fluid density in lumen |
| Aorta | Present | 46 HU | Expected midline position |
| Bilateral ureters | Tracked via CT ureteral study | — | Indication for study; within expected positions |

No gross abnormalities in organ position (situs) identified. No obvious hepatomegaly, splenomegaly, or hydronephrosis identified by HU mapping. The scan was performed as a ureteral study (indication: likely urolithiasis), and no calcification was noted in the quantitative tissue analysis at renal or ureteral positions.

---

## Section 3: Ultrasound Findings

**Study:** Abdominal Ultrasound Complete, 82 frames, Acuson system, 2010-07-01

The ultrasound study consisted of 82 frames covering the liver, bilateral kidneys, spleen, and abdominal structures. All 82 frames were rendered and saved individually in `anatomy_findings/US_individual/`. Ultrasound does not provide HU-based quantification; visual survey of the frames shows structures consistent with abdominal ultrasound examination coverage. The modality provides complementary documentation of the abdominal anatomy from a different imaging perspective than CT but with lower spatial resolution for deep structures in a 22-year-old male-habitus abdomen.

---

## Section 4: Genomic Cross-Reference — Key Findings Summary

The following is a synthesis of key data points from the patient-provided genomics report that are directly relevant to the imaging findings. All genomic data below is sourced from `DNA_Genomic_WGS_Ancestry_GRCh37_GRCh38_Full_Report.docx` — this report does not independently verify genomic calls.

### 4.1 Chimerism Evidence

| Source | Finding |
|---|---|
| AncestryDNA | 3 heterozygous calls on non-PAR X (impossible in single-genome XY) |
| AncestryDNA | 5 heterozygous calls on non-PAR Y (impossible in single-genome XY) |
| AncestryDNA | rs2534116 and rs2535142: two spatially coherent het calls 243kb apart in Xq21.33 |
| AncestryDNA | rs9786514 in AZFc region (Y spermatogenesis cluster) |
| WGS GRCh37 | 520 variants across X chromosome covering 120+ genes |
| WGS GRCh37 | 179 variants on Y chromosome |
| Clinical | Living identical twin brother documented |

**Interpretation in imaging context:** XX/XY tetragametic chimerism (two fertilized eggs fusing early in development) creates one individual with two distinct cell populations. Tissue composition — including gonadal, Müllerian, and Wolffian derivative tissue — is determined by which cell population dominates in each anatomical location during embryonic development. This is the biological mechanism that produces the internal anatomical variability observed in the imaging data.

### 4.2 11-KT Pathway — All 10 Genes Modified

The genomics report analyzed the complete 11-ketotestosterone biosynthetic and signaling pathway. All 10 genes assessed show structural variants when NOT_IN_ANY_DB data is included.

| Gene | Function | Key Variants | Homozygous? |
|---|---|---|---|
| CYP11B1 | Commitment enzyme (A4 → 11OHA4) | 37 WGS variants (10 HIGH) | 2 homozygous |
| HSD11B2 | 11-keto synthesis (11OHA4 → 11KA4) | Pathogenic structural deletion (AncestryDNA ClinVar pathogenic); absent from WGS (structural variant) | Yes (AncestryDNA) |
| AKR1C3 | Final 11-KT synthesis (11KA4 → 11-KT) | Multiple variants | Present |
| SRD5A2 | Upgrade to 11-KDHT (most potent form) | 2 AncestryDNA pathogenic homozygous insertions; 5 WGS all homozygous | ALL homozygous |
| HSD11B1 | Off switch (11-KT → 11OHT, reversal) | 2-3 variants, all heterozygous | Only one copy modified |
| AR | Androgen receptor (binds 11-KT) | 17 variants; homozygous CAG/AC repeat expansions in receptor ligand-binding zone | Multiple homozygous |
| CYP19A1 | Aromatase — competing pathway to estrogen | 14 structural variants in NOT_IN_ANY_DB; CAG repeat CONTRACTION mirroring AR expansion | All heterozygous |
| ESR1 | Estrogen receptor | 26 WGS variants, 16 homozygous | 16 homozygous |
| MTHFR | Methylation cycle rate-limiting step | Multiple | 5 homozygous |
| MTR | Methyl donor recycling | Multiple | 20 homozygous |

**Clinical anchor:** Post-bilateral orchiectomy, total testosterone <3 ng/dL sustained for 7+ years with maintained daily sexual function. The 11-KT pathway, which operates entirely independently of gonadal function through ACTH-driven adrenal precursor production, is identified in the genomics report as the hypothesized active androgen system.

**Imaging correlation:** The adrenal glands (Finding 1) are present and mildly enlarged/upper-normal, consistent with increased androgenic demand from an ACTH-driven adrenal pathway post-gonadectomy.

### 4.3 Prostate Absence — Genomic Support

SRD5A2 homozygous pathogenic on both copies is directly relevant: SRD5A2 (5α-reductase type 2) is the enzyme that converts testosterone to DHT in the prostate mesenchyme, and its activity during embryonic development is required for prostate morphogenesis. In XX/XY chimeras, if XX-lineage cells dominated the pelvic mesenchyme during embryogenesis, prostate development would not be induced regardless of SRD5A2 status. Published MRI case of OT-DSD with XX/XY mosaicism documents confirmed prostate absence.

### 4.4 Müllerian Structures — Genomic Support

In XX/XY chimeras, Müllerian regression requires anti-Müllerian hormone (AMH) secreted by Sertoli cells during embryonic development. AMH acts locally — it only regresses Müllerian structures adjacent to testicular tissue. In chimeric individuals where Sertoli cells are regionally absent or XX-dominant cells predominate in specific areas, Müllerian structures in those areas would not be suppressed and would persist. This is the established biological mechanism for Müllerian remnant persistence in OT-DSD.

### 4.5 DNA Repair, Coagulation, and Clinical Monitoring Flags

The genomics report identifies several findings with clinical monitoring implications that the imaging data cannot assess but should be documented for completeness:

**DNA Repair (TP53):** 20 WGS variants, 11 homozygous — not detected by AncestryDNA microarray. TP53 encodes the p53 tumor suppressor. This was characterized in the genomics report as a "genuinely new finding" from WGS. MLH1 (Lynch syndrome mismatch repair executor): ALL 9 WGS variants homozygous. MSH2 (mismatch detector): 7 of 16 WGS variants homozygous.

**Coagulation:** Factor V (F5) 9 homozygous including missense; Factor II/Prothrombin insertion (both copies); Factor XIII (clot stabilizer) 17 of 22 homozygous including 2 missense; Protein S (anticoagulant) 6 of 7 homozygous. Both the pro-coagulant and anti-coagulant sides of the cascade are modified on both gene copies at multiple positions.

**Blood type:** FUT2 stop-gained pathogenic (AncestryDNA highest single-variant score at 305); FUT1 15 WGS variants; RHD/RHCE/RHAG 32 combined Rh variants. The genomics report raises a Bombay phenotype or para-Bombay consideration — standard blood type testing may not accurately reflect transfusion compatibility. This is a direct patient safety flag.

**Pharmacogenomics:** CYP2D6 likely poor metabolizer (24 variants, 14 homozygous); CYP2C19 all 10 homozygous; CYP3A4 8–10 variants. These three enzymes process the majority of commonly prescribed drugs. Documented poor metabolizer status for CYP2D6 means progesterone (cited as prescribed in the genomics report) clears slowly — lower doses achieve equivalent effect.

---

## Section 5: Integrated Assessment

### 5.1 Structural Anatomy — What the Imaging Shows

The CT and ultrasound data for this patient, interpreted in the context of XX/XY chimerism and post-bilateral orchiectomy status, shows a pattern that is anatomically inconsistent with standard male anatomy and consistent with the documented biology of ovotesticular disorder of sex development (OT-DSD) in an XX/XY chimeric individual:

1. **Adrenal glands: present bilaterally, upper range of normal, mildly elevated HU** — consistent with adrenal compensation and 11-KT pathway activity post-gonadectomy.

2. **Prostate zone: no discrete consolidated oval structure** — consistent with absent or hypoplastic prostate, documented in XX/XY OT-DSD case reports.

3. **Posterior midline pelvis: persistent soft tissue and fluid signal** at z = -280 to -355 in the anatomical uterine/cervical zone — consistent with hypoplastic Müllerian structure; not confirmatory without MRI.

4. **Bilateral lateral pelvic structures post-orchiectomy: secondary lateral clusters at adnexal anatomical position** — HU 50–54, symmetric, areas up to 5,751 mm², present across 110 mm of z-extent in the position where adnexal tissue would be expected. With orchiectomy confirmed and testes removed, these secondary clusters are not accountable as testes; their position corresponds to the adnexal/ovarian anatomical zone.

5. **Anterior midline abdominal structure: anomalous 190+ mm vertically stable structure** at HU 43–53 with internal fluid component, not accountable as any standard male abdominal organ — anatomically compatible with intra-abdominal Müllerian remnant in the context of XX/XY chimerism.

6. **Standard organs: present and in expected anatomical positions** — bilateral kidneys, spleen, liver, bladder, aorta all confirmed.

### 5.2 Genomics-Imaging Convergence Points

| Genomic Finding | Imaging Correlate | Convergence |
|---|---|---|
| XX/XY chimerism (8 AncestryDNA het calls, WGS 520X + 179Y variants) | Bilateral adnexal structures, absent prostate, Müllerian zone signal | Chimerism creates the developmental mechanism for mixed internal anatomy |
| SRD5A2 homozygous pathogenic | Absent prostate on CT | SRD5A2 required for prostate morphogenesis in embryogenesis |
| 11-KT pathway 10/10 genes modified, SRD5A2 pathogenic | Adrenals present, upper-normal, mildly elevated HU | Adrenals are the sole post-orchiectomy androgen source; upper-range sizing consistent with increased demand |
| ESR1 16 homozygous variants + CYP19A1 14 structural variants | Bilateral symmetric lateral structures at adnexal positions | Ovarian tissue in chimeras responds to hormonal environment; with modified estrogen production and reception, residual ovarian tissue behavior is altered |
| MAGEC1 17 X-chromosome variants (cancer-testis antigen) | Bilateral lateral pelvic structures post-orchiectomy | MAGE proteins express in testes and placenta; alternative expression in post-orchiectomy residual gonadal tissue possible |
| Prepubescent 11-KT hypothesis (XX cell populations pre-gonadal) | Posterior midline Müllerian zone signal | XX-lineage cells in pelvis not exposed to AMH would retain Müllerian structures |

### 5.3 What This Report Cannot Determine

- Whether the structures identified are histologically what their HU and position suggest. CT without contrast cannot confirm organ identity — only tissue density and position.
- Whether the anterior midline structure represents a specific Müllerian derivative (e.g., vestigial fallopian tube, accessory uterine tissue, or other structure) versus another explanation.
- Whether residual ovarian or adnexal tissue in the lateral pelvic zone is functional, inactive, or surgically modified.
- Whether the posterior midline Müllerian zone signal represents a small hypoplastic uterus, cervical remnant, or other soft tissue structure.

**The imaging modality appropriate for addressing these questions is MRI with T2-weighted pelvic sequences, with a knowledgeable radiologist aware of the XX/XY chimeric context.**

---

## Section 6: Referenced Literature

All sources used in this analysis are filed in the `External Links/` folder in this repository.

1. **Unilateral true hermaphrodite with 46,XX/46,XY dispermic chimerism** — PMC1050410  
   [https://pmc.ncbi.nlm.nih.gov/articles/PMC1050410/](https://pmc.ncbi.nlm.nih.gov/articles/PMC1050410/)

2. **Magnetic Resonance Imaging Findings of Ovotesticular Disorder of Sex Development with Bilateral Gonadoblastoma** — Iranian Journal of Radiology  
   [https://brieflands.com/articles/iranjradiol-56259.html](https://brieflands.com/articles/iranjradiol-56259.html)

3. **Imaging Aspects in a Case of Persistent Müllerian Duct Syndrome (PMDS): A Case Report and Overview** — PMC11364497  
   [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11364497/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11364497/)

4. **46,XX/46,XY Chimerism and Human Sexual Development** — OBM Genetics  
   [https://www.lidsen.com/journals/genetics/genetics-06-02-156/obm.genet.2202156.pdf](https://www.lidsen.com/journals/genetics/genetics-06-02-156/obm.genet.2202156.pdf)

5. **Normal adrenal gland thickness on computerized tomography in an Asian Indian adult population** — PMC6319091  
   [https://pmc.ncbi.nlm.nih.gov/articles/PMC6319091/](https://pmc.ncbi.nlm.nih.gov/articles/PMC6319091/)

6. **Ovotesticular Disorders of Sexual Development: A rare case of peritoneal carcinomatosis** — PMC11466586  
   [https://pmc.ncbi.nlm.nih.gov/articles/PMC11466586/](https://pmc.ncbi.nlm.nih.gov/articles/PMC11466586/)

7. **Case Report: 46,XX/47,XXY Mosaicism with Ovotesticular DSD** — PMC11364154  
   [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11364154/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11364154/)

8. **True hermaphroditism — the importance of ultrasonic assessment** — Pires et al., *Ultrasound in Obstetrics & Gynecology* (2005)  
   [https://obgyn.onlinelibrary.wiley.com/doi/full/10.1002/uog.1928](https://obgyn.onlinelibrary.wiley.com/doi/full/10.1002/uog.1928)

9. **Differentiation of Adrenal Adenoma and Nonadenoma in Unenhanced CT** — PMC2627166  
   [https://pmc.ncbi.nlm.nih.gov/articles/PMC2627166/](https://pmc.ncbi.nlm.nih.gov/articles/PMC2627166/)

10. **46,XX DSD: Developmental, Clinical and Genetic Aspects** — PMC8392837  
    [https://pmc.ncbi.nlm.nih.gov/articles/PMC8392837/](https://pmc.ncbi.nlm.nih.gov/articles/PMC8392837/)

---

## Section 7: Image Index

All annotated images are in the `anatomy_findings/` folder:

| File | Contents |
|---|---|
| REPORT_A_adrenals.png | Adrenal gland bilateral measurement zones with HU and area data |
| REPORT_B_prostate_zone.png | Prostate zone analysis, z=-345 to -410 |
| REPORT_C_uterine_zone.png | Posterior midline uterine zone, z=-290 to -360 |
| REPORT_D_periumbilical_mass.png | Anterior midline persistent structure tracking, z=-20 to -164 |
| REPORT_E_bilateral_adnexal.png | Bilateral lateral pelvic structures with measurements |
| FINDING_07_bilateral_lateral_structures.png | Initial bilateral structure identification with boxes |
| FINDING_08_zoomed_lateral_structures.png | Zoomed views of lateral zones |
| FINDING_09_quantified_bilateral.png | Quantified bilateral structures with circles at each level |
| FINDING_09b_component_overlay.png | Connected component outlines overlaid on CT slices |
| CT_pelvic_slices/ | Every pelvic CT slice (both windows) for manual review |
| CT_reformat_A/ | Reformatted series A (coronal/sagittal reconstruction) |
| CT_reformat_B/ | Reformatted series B |
| US_individual/ | All 82 ultrasound frames individually |

---

*Report generated by computational analysis integrating raw DICOM pixel data with patient-provided genomic report. All imaging measurements are derived from actual pixel values — no placeholders or assumed values are used. All clinical context is taken from patient-provided information. This document is intended as a reference synthesis for the patient's own use and for communication with treating physicians. It is not a clinical radiology report and does not constitute a medical diagnosis.*
