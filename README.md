# Assessment of the Role of ATP8B1 Gene in Gallstone Disease in the Pakistani Population

**Final Year Thesis Project**  
BS Biosciences, COMSATS University Islamabad  
December 2025

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![DOI](https://img.shields.io/badge/DOI-pending-blue.svg)]()

---

## 📋 Project Overview

Gallstone disease (GSD) is a major gastrointestinal health challenge worldwide. The ATP8B1 gene encodes a P4-ATPase flippase crucial for maintaining lipid asymmetry in hepatocanalicular membranes. While mutations in ATP8B1 are well-established in pediatric liver diseases (PFIC1), their role in adult-onset gallstone disease remains underexplored, particularly in South Asian populations.

This case-control study investigated the association between the ATP8B1 SNP rs766737165 (T>A) and gallstone disease risk in the Pakistani population.

### Key Findings
- **Sample Size:** 104 participants (75 gallstone patients, 29 healthy controls)
- **Primary Result:** rs766737165 (T>A) variant is **monomorphic** in study population
- **Genotype:** All successfully genotyped samples showed wild-type TT genotype
- **Conclusion:** This specific variant does not contribute to gallstone disease risk in this Pakistani cohort
- **Recommendation:** Whole Exome Sequencing (WES) needed to explore other ATP8B1 variants

---

## 🎯 Research Objectives

1. Investigate the potential association between ATP8B1 rs766737165 (T>A) and gallstone disease
2. Determine allelic and genotypic frequencies in Pakistani gallstone patients vs. controls
3. Assess ethnic/regional variation in variant distribution
4. Provide foundation for future comprehensive genetic studies

---

## 🧬 Methodology

### Study Design
- **Type:** Case-control study
- **Location:** COMSATS University Islamabad, Department of Biosciences
- **Duration:** 2024-2025
- **Ethics Approval:** Institutional Review Board, COMSATS University Islamabad

### Sample Collection
- **Cases:** 75 gallstone patients (diagnosed via ultrasound/surgery)
- **Controls:** 29 healthy individuals (no history of gallstone disease)
- **Demographics:** Multiple regions and ethnic backgrounds across Pakistan
- **Sample Type:** Peripheral blood (3-5 mL in EDTA tubes)

### Molecular Methods

#### 1. DNA Extraction
- **Method:** Organic extraction (Phenol-Chloroform-Isoamyl alcohol)
- **Yield:** High-quality genomic DNA
- **Quantification:** Agarose gel electrophoresis, visual estimation

#### 2. Genotyping Strategy
- **Technique:** TETRA-ARMS PCR (Tetra-Primer Amplification Refractory Mutation System)
- **Target:** ATP8B1 rs766737165 (T>A) in exon 19
- **Primers:** Custom-designed tetra-primer set (see `/primers/` folder)

**Primer Design:**
| Primer | Sequence (5' → 3') | Product Size |
|--------|-------------------|--------------|
| Forward Outer | ACTTCCTAGAAAACATTCCTTACC | Control: 486 bp |
| Reverse Outer | ACAATGTGACTCTGAAAGTTAAAA | Control: 486 bp |
| Forward Inner (T allele) | GTTTCTTTCTTCTGGAGATTTCTGACAT | T: 321 bp |
| Reverse Inner (A allele) | CCTGTTGTAAACAGAGGGATTTTTTAAA | A: 237 bp |

**Expected Band Patterns:**
- **TT genotype:** 486 bp (control) + 321 bp (T-specific)
- **TA genotype:** 486 bp + 321 bp + 237 bp
- **AA genotype:** 486 bp + 237 bp (A-specific)

#### 3. PCR Amplification
- **Polymerase:** Taq DNA polymerase
- **Thermal cycling:** 
  - Initial denaturation: 95°C, 5 min
  - 35 cycles: 95°C (30s), 58°C (30s), 72°C (45s)
  - Final extension: 72°C, 7 min
- **Product visualization:** 2% agarose gel electrophoresis, UV transilluminator

---

## 📊 Results

### Demographic Distribution

**Gender Distribution:**
| Group | Male | Female | Total |
|-------|------|--------|-------|
| Cases | 18 (24%) | 57 (76%) | 75 |
| Controls | 12 (41%) | 17 (59%) | 29 |

**Key Observation:** Female predominance in gallstone cases (76%), consistent with known epidemiological patterns.

**Age Distribution:**
- Mean age: 45.3 ± 12.7 years
- Range: 22-68 years
- Peak incidence: 40-55 years

### Genotyping Results

**Primary Finding:**
- **All successfully genotyped samples:** TT genotype (wild-type)
- **Variant allele (A):** Not detected in either cases or controls
- **Interpretation:** rs766737165 is **monomorphic** in this Pakistani population

**Genotypic Frequencies:**
| Genotype | Cases | Controls | Total |
|----------|-------|----------|-------|
| TT | 75 (100%) | 29 (100%) | 104 (100%) |
| TA | 0 (0%) | 0 (0%) | 0 (0%) |
| AA | 0 (0%) | 0 (0%) | 0 (0%) |

**Allelic Frequencies:**
| Allele | Cases | Controls | Combined Frequency |
|--------|-------|----------|-------------------|
| T (wild-type) | 100% | 100% | 1.00 |
| A (variant) | 0% | 0% | 0.00 |

---

## 🔬 Clinical Significance

### What These Results Mean

1. **No Association Detected:** The rs766737165 (T>A) variant does not contribute to gallstone disease risk in this cohort
2. **Population-Specific Finding:** This locus appears monomorphic in the Pakistani population studied
3. **ATP8B1 Not Excluded:** Other variants in ATP8B1 may still play a role
4. **Need for Comprehensive Analysis:** Whole Exome Sequencing (WES) recommended

### Comparison with Global Studies

Limited data exists on this specific SNP (rs766737165) in global populations:
- **This study (Pakistani):** 100% TT genotype
- **Other populations:** Data not readily available in public databases
- **Novel contribution:** First report on this variant in Pakistani gallstone patients

---

## 💡 Discussion

### Why This Variant Was Selected

1. **Gene Function:** ATP8B1 encodes FIC1, essential for bile homeostasis
2. **Known Associations:** Mutations cause PFIC1 (severe pediatric cholestasis)
3. **Biological Rationale:** Impaired bile flow → cholesterol supersaturation → gallstones
4. **Location:** Exon 19, functional coding region

### Limitations

1. **Sample Size:** 104 participants (moderate for SNP study)
2. **Single Variant Focus:** Only one SNP analyzed
3. **Monomorphic Locus:** No variation detected for association testing
4. **Ethnic Homogeneity:** Primarily Punjabi/Potohari backgrounds
5. **No Sequencing Validation:** Relied on PCR-based genotyping

### Future Directions

**Recommended Next Steps:**

1. **Whole Exome Sequencing (WES)**
   - Identify novel ATP8B1 variants
   - Assess all exons simultaneously
   - Discover rare mutations

2. **Larger Cohort Studies**
   - Multi-center recruitment
   - 500+ participants
   - Include diverse ethnic groups

3. **Functional Studies**
   - Validate identified variants
   - Assess impact on protein function
   - Correlate with bile composition

4. **Multi-Gene Panel**
   - ABCB4, ABCB11 (other bile transporters)
   - APOE, LITH genes
   - Comprehensive genetic risk profiling

---

## 📁 Repository Structure

```
ATP8B1-Gallstone-Study/
├── README.md                     # This file
├── LICENSE                       # MIT License
├── docs/
│   ├── thesis_abstract.md       # Thesis abstract
│   ├── methodology.md           # Detailed methods
│   ├── results_summary.md       # Results overview
│   └── references.md            # Bibliography
├── primers/
│   ├── primer_design.md         # Primer design rationale
│   ├── primer_sequences.txt     # All primer sequences
│   └── tetra_arms_protocol.md   # TETRA-ARMS PCR protocol
├── protocols/
│   ├── dna_extraction.md        # DNA extraction protocol
│   ├── pcr_amplification.md     # PCR conditions
│   ├── gel_electrophoresis.md   # Gel running protocol
│   └── sample_collection.md     # Blood sample handling
├── data/
│   ├── demographics.csv         # Anonymized demographic data
│   ├── genotype_results.csv     # Genotyping results (anonymized)
│   └── README.md                # Data dictionary
├── images/
│   ├── gel_images/              # Representative gel electrophoresis images
│   ├── figures/                 # Thesis figures
│   └── workflow_diagram.png     # Visual workflow
└── supplementary/
    ├── ethics_approval.md       # Ethics statement
    ├── informed_consent.md      # Consent form template
    └── abbreviations.md         # List of abbreviations
```

**Note:** Patient identifiable data is NOT included to protect privacy.

---

## 🔐 Data Privacy & Ethics

### Ethical Compliance
- **IRB Approval:** Obtained from COMSATS University Islamabad
- **Informed Consent:** All participants provided written consent
- **Data Anonymization:** No patient identifiers in public repository
- **HEC Guidelines:** Compliant with Higher Education Commission of Pakistan research standards

### Data Sharing Policy
- **Public Data:** Aggregated genotype frequencies, demographics (anonymized)
- **Protected Data:** Individual patient records (NOT shared)
- **Request Policy:** Raw data available to verified researchers upon reasonable request

---

## 🛠️ Tools & Technologies

### Wet-Lab Techniques
- DNA extraction (phenol-chloroform method)
- TETRA-ARMS PCR
- Agarose gel electrophoresis
- UV transillumination

### Equipment Used
- Thermal cycler
- Gel electrophoresis apparatus
- UV transilluminator
- Micropipettes (P10, P20, P200, P1000)
- Centrifuge
- Vortex mixer

### Reagents
- Taq DNA Polymerase
- dNTPs
- MgCl₂
- PCR buffer
- Agarose
- Ethidium bromide (or SYBR Safe)
- DNA ladder (100 bp)

### Analysis Software
- Primer3 (primer design)
- NCBI BLAST (primer specificity)
- Microsoft Excel (data tabulation)
- GraphPad Prism (statistical analysis - if applicable)

---

## 📚 Key References

1. **ATP8B1 and PFIC:**
   - Bull LN, et al. (1998). *Nat Genet.* PFIC1 mapping and ATP8B1 identification
   - Klomp LW, et al. (2004). *Hepatology.* FIC1 function in bile formation

2. **Gallstone Disease Genetics:**
   - Lammert F, et al. (2016). *Nat Rev Gastroenterol Hepatol.* Gallstone genetics
   - Portincasa P, et al. (2006). *Lancet.* Cholesterol gallstone pathophysiology

3. **TETRA-ARMS PCR Methodology:**
   - Ye S, et al. (2001). *Nucleic Acids Res.* TETRA-ARMS PCR development
   - Collins A, et al. (2012). *Methods Mol Biol.* SNP genotyping protocols

4. **Pakistani Population Studies:**
   - Nasir M, et al. (2021). *J Gastroenterol Hepatol.* GSD prevalence in Pakistan
   - Ahmad I, et al. (2019). *Pak J Med Sci.* Genetic epidemiology in Pakistan

**Full bibliography available in:** `/docs/references.md`

---

## 👥 Research Team

### Principal Investigator
**Syed Muhammad Ali Shirazi**  
BS Biosciences Student (2022-2025)  
COMSATS University Islamabad  
📧 shirazi6503@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/syedmuhammadalishirazi) | [GitHub](https://github.com/alishirazi03)

### Supervisors
**Dr. Nasir Masood** (Supervisor)  
Tenured Associate Professor  
Department of Biosciences, COMSATS University Islamabad

**Dr. Muhammad Ajmal** (Co-Supervisor)  
Tenured Assistant Professor  
Department of Biosciences, COMSATS University Islamabad

### Technical Support
**Noshad Ahmed**  
Senior PhD Scholar  
Department of Biosciences, COMSATS University Islamabad

---

## 🙏 Acknowledgments

This research was supported by:
- **Higher Education Commission (HEC) of Pakistan** - Project No. 15349
- **COMSATS University Islamabad** - Laboratory facilities
- **Study participants** - For their voluntary participation
- **Department of Biosciences** - Technical and administrative support

Special thanks to my family for their endless support throughout this research journey.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Note:** While code and protocols are open-source, patient data remains protected under institutional ethics guidelines.

---

## 📞 Contact & Collaboration

Interested in collaboration or have questions about this research?

**Primary Contact:**  
Syed Muhammad Ali Shirazi  
📧 shirazi6503@gmail.com  
🌐 https://alishirazi03.github.io

**For Academic Inquiries:**  
Dr. Muhammad Ajmal
📧 muhammad.ajmal@comsats.edu.pk

Dr. Nasir Masood  
📧 nasirmasood@comsats.edu.pk

---

## 🔄 Citation

If you use this work in your research, please cite:

```
Shirazi, S.M.A. (2025). Assessment of the Role of ATP8B1 Gene in Gallstone 
Disease in the Pakistani Population. Undergraduate Thesis, COMSATS University 
Islamabad, Department of Biosciences.
```

**BibTeX:**
```bibtex
@thesis{shirazi2025atp8b1,
  author = {Shirazi, Syed Muhammad Ali},
  title = {Assessment of the Role of ATP8B1 Gene in Gallstone Disease 
           in the Pakistani Population},
  school = {COMSATS University Islamabad},
  year = {2025},
  type = {Bachelor's Thesis},
  department = {Department of Biosciences}
}
```

---

## 📊 Project Status

- [x] Literature review completed
- [x] Ethics approval obtained  
- [x] Sample collection completed
- [x] DNA extraction completed
- [x] Primer design & optimization
- [x] PCR amplification & genotyping
- [x] Data analysis
- [x] Thesis writing
- [x] Thesis defense
- [ ] Manuscript preparation for publication
- [ ] Follow-up WES study (planned)

**Last Updated:** December 2025

---

## 🌟 Related Projects

Check out my other bioinformatics work:
- [SARS-CoV-2 Genomic Analysis Pipeline](https://github.com/alishirazi03/SARS-CoV-2-Analysis) - Viral genome assembly, annotation, and phylogenetics
- [Bioinformatics Blog](https://alishirazi03.github.io/blog/) - Tutorials and career development

---

**⭐ If you find this project useful, please consider starring this repository!**
