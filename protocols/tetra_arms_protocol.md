# TETRA-ARMS PCR Protocol
## Tetra-Primer Amplification Refractory Mutation System

---

## Overview

TETRA-ARMS PCR is a single-tube PCR method for SNP genotyping that uses four primers to simultaneously amplify wild-type and mutant alleles in a single reaction.

**Target SNP:** ATP8B1 rs766737165 (T>A) in exon 19

---

## Primer Design

### Primer Sequences

| Primer Name | Sequence (5' → 3') | Tm (°C) | Product |
|-------------|-------------------|---------|---------|
| FO (Forward Outer) | ACTTCCTAGAAAACATTCCTTACC | 56.2 | 486 bp (control) |
| RO (Reverse Outer) | ACAATGTGACTCTGAAAGTTAAAA | 54.8 | 486 bp (control) |
| FI (Forward Inner, T-allele) | GTTTCTTTCTTCTGGAGATTTCTGACAT | 58.1 | 321 bp (T-specific) |
| RI (Reverse Inner, A-allele) | CCTGTTGTAAACAGAGGGATTTTTTAAA | 57.9 | 237 bp (A-specific) |

### Design Criteria

✅ **Outer primers:** Amplify control fragment (both alleles)  
✅ **Inner primers:** Allele-specific (3' end matches SNP)  
✅ **Tm difference:** < 3°C between all primers  
✅ **No primer-primer interactions:** Checked for dimers/hairpins  
✅ **Specificity:** BLAST validated against human genome  

---

## Expected Genotype Patterns

| Genotype | Bands Visible | Band Sizes |
|----------|---------------|------------|
| **TT (wild-type)** | 2 bands | 486 bp (control) + 321 bp (T-allele) |
| **TA (heterozygous)** | 3 bands | 486 bp + 321 bp + 237 bp |
| **AA (variant)** | 2 bands | 486 bp (control) + 237 bp (A-allele) |

**Control band (486 bp)** = Internal positive control (present in all genotypes)

---

## PCR Reaction Setup

### Master Mix Composition (Per 25 μL Reaction)

| Component | Volume (μL) | Final Concentration |
|-----------|-------------|---------------------|
| 10X PCR Buffer | 2.5 | 1X |
| MgCl₂ (25 mM) | 2.0 | 2.0 mM |
| dNTP mix (10 mM each) | 0.5 | 200 μM each |
| FO primer (10 μM) | 0.5 | 0.2 μM |
| RO primer (10 μM) | 0.5 | 0.2 μM |
| FI primer (10 μM) | 1.0 | 0.4 μM |
| RI primer (10 μM) | 1.0 | 0.4 μM |
| Taq polymerase (5 U/μL) | 0.2 | 1 U |
| Template DNA (50 ng/μL) | 2.0 | 100 ng |
| Nuclease-free water | 14.8 | — |
| **Total** | **25.0** | |

**Notes:**
- Inner primers (FI, RI) at 2X concentration of outer primers
- Optimize DNA template concentration if poor amplification
- Prepare master mix on ice

---

## Thermal Cycling Conditions

| Step | Temperature | Time | Cycles |
|------|-------------|------|--------|
| **Initial Denaturation** | 95°C | 5 min | 1× |
| **Denaturation** | 95°C | 30 sec | |
| **Annealing** | 58°C | 30 sec | 35× |
| **Extension** | 72°C | 45 sec | |
| **Final Extension** | 72°C | 7 min | 1× |
| **Hold** | 4°C | ∞ | |

**Total runtime:** ~2 hours 30 minutes

---

## Gel Electrophoresis

### Gel Preparation

**Agarose Concentration:** 2% (w/v)

1. Weigh 2 g agarose powder
2. Add 100 mL 1X TBE buffer
3. Microwave until fully dissolved (~2 min)
4. Cool to ~60°C
5. Add 5 μL ethidium bromide (10 mg/mL) OR SYBR Safe
6. Pour into gel tray with comb
7. Allow to solidify (30-40 min)

### Loading Samples

**Per Well:**
- 5 μL PCR product
- 1 μL 6X loading dye
- Mix gently, load immediately

**Ladder:** 5 μL of 100 bp DNA ladder in lane 1

### Running Conditions

- **Voltage:** 100V
- **Time:** 45-60 minutes
- **Buffer:** 1X TBE
- **Stop when:** Dye front reaches 2/3 of gel

### Visualization

- **Method:** UV transilluminator (302 nm)
- **Documentation:** Gel documentation system
- **Band Analysis:** Visual inspection + ImageJ (optional)

---

## Troubleshooting Guide

### Problem: No Bands Visible

**Possible Causes:**
- ❌ No DNA template → Re-extract DNA
- ❌ Taq polymerase inactive → Check enzyme, use fresh aliquot
- ❌ Primers degraded → Order new primers
- ❌ Wrong PCR conditions → Verify temperatures

**Solutions:**
- Positive control: Use DNA known to amplify
- Negative control: No template (should show no bands)

### Problem: Weak Bands

**Possible Causes:**
- Low DNA concentration → Use 100-200 ng template
- Insufficient cycles → Increase to 40 cycles
- Low primer concentration → Increase inner primers to 0.6 μM

**Solutions:**
- Optimize MgCl₂ (try 1.5-3.0 mM range)
- Increase template DNA amount
- Extend annealing time to 45 sec

### Problem: Non-Specific Bands

**Possible Causes:**
- Annealing temperature too low → Increase to 60-62°C
- Primer dimers forming → Check primer design
- DNA contamination → Use fresh reagents

**Solutions:**
- Gradient PCR to optimize annealing temperature
- Redesign primers if persistent
- Include negative controls

### Problem: Only Control Band Visible (No Allele-Specific Bands)

**Possible Causes:**
- Inner primers not working → Check primer stocks
- SNP site not in sample → Verify SNP location
- Mismatch at 3' end blocking extension → Redesign inner primers

**Solutions:**
- Test primers on positive control sample
- Sequence PCR product to confirm SNP presence
- Adjust inner primer concentration ratio

---

## Quality Control

### Positive Controls
- **TT genotype control:** Known homozygous wild-type sample
- **TA genotype control:** Known heterozygous sample (if available)
- **AA genotype control:** Known homozygous variant sample (if available)

### Negative Controls
- **No template control (NTC):** PCR reaction without DNA
- **Should show:** No bands OR only primer dimers (<100 bp)

### Internal Controls
- **486 bp control band:** Must be present in ALL samples
- **If absent:** PCR failure, repeat sample

---

## Data Recording

### Genotyping Results Table

| Sample ID | Control (486 bp) | T-band (321 bp) | A-band (237 bp) | Genotype | Notes |
|-----------|------------------|-----------------|-----------------|----------|-------|
| Patient01 | + | + | - | TT | Clear bands |
| Patient02 | + | + | + | TA | All bands visible |
| Patient03 | + | - | + | AA | Weak A-band |
| NTC | - | - | - | — | Clean |

**Scoring:**
- **+** = Band present
- **-** = Band absent
- **±** = Faint/ambiguous (repeat sample)

---

## Safety Precautions

⚠️ **Hazards:**
- **Ethidium bromide:** Mutagenic, use gloves, dispose properly
- **UV light:** Eye/skin damage, use face shield
- **TBE buffer:** Corrosive, avoid contact

✅ **Safety Measures:**
- Wear lab coat, gloves, safety glasses
- Work in designated PCR area (avoid contamination)
- Dispose of ethidium bromide waste in designated container
- Follow institutional biosafety guidelines

---

## References

1. Ye S, et al. (2001). *Nucleic Acids Res.* 29(17):e88 - TETRA-ARMS PCR method
2. Collins A, et al. (2012). *Methods Mol Biol.* 578:309-318 - PCR-based SNP genotyping
3. Medrano RF, et al. (2005). *Biotechniques* 39(6):919-925 - TETRA-ARMS optimization

---

**Last Updated:** Feb 2026 
**Prepared by:** Syed Muhammad Ali Shirazi  
**Validated by:** Dr. Nasir Masood, Dr. Muhammad Ajmal
