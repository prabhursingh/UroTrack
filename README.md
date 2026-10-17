# 🩺 UroTrack — Clinical Decision Support for Urinary Tract Infections

![Status](https://img.shields.io/badge/status-in%20development-orange)
![Domain](https://img.shields.io/badge/domain-clinical%20decision%20support-0B5394)
![Standards](https://img.shields.io/badge/standards-HL7%20FHIR%20%7C%20SNOMED%20CT-E5402A)

**UroTrack** is a clinical research and health-informatics project to improve the diagnosis and management of **urinary tract infections (UTIs)** and related urological conditions through data analysis and decision support.

> 🚧 **Status:** design and research phase. Code will be published here as it is developed.

---

## 📌 The Problem

UTIs are among the most common infections seen in emergency and outpatient care. Diagnosis often relies on symptoms and urine dipstick results before culture results are available, which leads to:

- over- and under-treatment,
- unnecessary broad-spectrum antibiotic use, contributing to **antimicrobial resistance**,
- variation from evidence-based guidelines between clinicians.

## 💡 Proposed Solution

A clinical decision support system (CDSS) that brings together the data a clinician needs at the point of care:

| Data source | Used for |
|---|---|
| Electronic health records | Symptoms, history, risk factors, previous UTIs |
| Laboratory results | Urinalysis, urine culture, antibiotic susceptibility |
| Imaging | Complicated / upper-tract infections |
| Clinical guidelines | Evidence-based diagnosis and antibiotic choice |

## 🎯 Objectives

1. **Risk stratification** — estimate the likelihood of a UTI and of a complicated infection.
2. **Guideline-based recommendations** — suggest diagnostic steps and empirical antibiotic therapy aligned with local resistance patterns.
3. **Antimicrobial stewardship** — flag unnecessary or overly broad antibiotic prescriptions.
4. **Interoperability** — exchange data using **HL7 FHIR** and code findings with **SNOMED CT**.

## 🗺️ Roadmap

- [x] Define clinical problem and scope
- [ ] Map required data elements to FHIR resources and SNOMED CT codes
- [ ] Encode guideline rules (diagnosis and empirical treatment)
- [ ] Build a prediction model on de-identified / public data
- [ ] Prototype clinician-facing dashboard
- [ ] Evaluate with clinical users

## 👤 Author

**Dr. Prabhu Raj Singh** — Specialist Dentist & Health Informatician · [LinkedIn](https://www.linkedin.com/in/prabhu-raj-singh-9a926a20)
