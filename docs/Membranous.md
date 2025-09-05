# **Membranous Nephropathy (MN)**
## **Overview**
* Occurs in all ages, but most common in ages 30-60 years old
* Male:Female ratio 2:1
* Risk factors for progression: Male, >60 years of age, high levels of proteinuria, and elevated Cr levels
* Two types: Primary and Secondary
* Primary MN about 70% of cases, Secondaary about 30%
* PLA2R antigen is most comming antigen in Primary MN
* Secondary MN: Autoimmune/CVD, Drug associated, Infection related, Malignancy
    1. Children < 16 years of age commonly: SLE, HBV, congenital syphilis
    2. Adults > 60 years of age commonly: Drug associated and Malignancy
* Biopsy not required for diagnosis PLA2R positive Primary MN
* Spontaneous Remission Relatively common (about 30% of Cases)
* Transplant
    1. occurs most frequently ~2 years post transplant
    2. Is most commonly sub nephrotic 
## **Pathophysiology**
 * Pathology: Subepithelial deposits
    1. Immuncomplex formation in situ of the subepitheial layers of the basement membrane
    2. IgG granulated pattern on IF
    3. Well seen in EM and IF
    4. Spike formation and thickened Basement membrane 
 * Rarely Crescents --> if present should test instigate further testing: ANCA, ANA, Anti-GMB
 * Primary MN Antigen association
    1. PLA2R: Most commen antigen/anti-body in Primary MN, anti-body testing excellent correleatio w/5-10 excess compaired to tissue staining
    2. THSD7A: No antibody testing available at this time, also found in secondary and should invoke age approiate cancer screenings
 * Secondary MN Antigen association
    1. Exostosin 1/Exostosin 2 (EXT1/EXT2): ofent associated with Autimmune disease
    2. NELL 1: most heterogenous of all antigens, associated in many disease states (drugs, malignancy, autoiummune, infection), should invoke age approiate cancer screenings
    3. THSD7A: can be associated with malignancy
    4. NDNF: associaged with syphylsis
    5. PCSK6: NSAID
    6. Protocadherin 7: primary older patients, minimal complement activation and high rates of spontaneous remission
    7. FAT1: associated with stemcell transplant patients, progressive and can re-occur in allograft
    8. Semaphorin 3b: pediatric patients w/onset <2 years old
 * Most common Secondary MN found in SLE patients
## **Clinical Presentation**
 * Proteniuria --> 75% of cases fully nephrotic
 * Normotensive
 * Normal/perserved renal function
 * 50% of cases with microscopic hematuria
## **Drugs and Diseases Associated with Membranous**
 * Drugs
    1. Gold salts
    2. Mercury (can occasionaly be found in creams meant to lighten skin)
    3. Penicillamine
    4. Bucillamin
    5. Catopril (sulfhydryl group)
    6. Lipoic Acid (found in supplaments)
    7. NSAID (assoicated with PCSK6 antigen)
    8. Tiopronin
    9. Trimethadione
 * Malignancy
    1. Mainly Carcinomas
    2. MC lung (highly associated with older patients who have a smoking history)
    3. GI 
    4. Prostate 
    5. Breast
 * Infections
    1. HBV
    2. Syphilis
    3. Filariasis
    4. HCV
    5. Hydatid disease (parasitic infection caused by the larval stage of a tapeworm)
 * Autiommune
    1. SLE
    2. RA
    3. Sjogren
    4. Mixed connective tissues
    5. Graves
    6. Hashimoto's
 * Other
    1. Allogenic hematopoietic SCT
    2. IgG4RD
    3. Guillain Barre
    4. Chronic inflammatory Demyelinatio polyneuropathy (CIDP)
    5. Sarcoidosis
    6. Renal Vein Thrombosis 
## **Deffinitions of Treatment Response**
 * No formal definition of Resistent Disease currently accepted. Current guidelines put forth that patient's with persistent/increasing levles PLA2R ab after 1st round of immunotherapy be treated as Resistent
 * Resistance Disease in PLA2R negative patient's with primary MN is difficult to define
    1. Persistent Nephrotic Syndrome
    2. Or increased, but still reduced serum albumin levels as markers for resistent disease
  * Best Model for predicitive of response to treatment is PLA2R ab titer w/serum Albumin at 3months of treatment 
## **Treatment**
### General Information
 * It is reasonable to wait 6 months, while patient is on maximal anti-proteinuric therapy, before starting immunosupressive therapy due to high rates of spontaneous remission.
 * PLA2R-ab testing with ELIZA and/or IFA is cleared by FDA for aid in diagnosis only. Use for PLA2R-ab testing in monitoring is off lable use, though used extensively in guidline recomendations
 * Proteinuria can persist for 12-24 months after start of treatment
 * High rates of thrombosis; [Prophylaxis page](Prophylaxis.md)
 * When to Biopsy
    1. Unusual clinical course; rapid decrease in eGFR
    2. Serological abnormalities (positive ANA, ect.)
    3. Unresponsive to immunosuppressive therapy and progressive kidney injury
    4. Persistent nephrotic syndrome despite disappearance of PLA2Rab
### Initial Investigation and Management
```mermaid
---
config:
  theme: redux
---
flowchart TD
    A(["Nephrotic Range Proteinuria"]) --> B["Screen appropiate antibodies"]
    B --> C["PLA2R ab Negative"] & D["PLA2R ab Positive"]
    C --> n1["Renal Bx"]
    n1 --> n2["MN on Bx"]
    n2 --> n3["PLA2R ag Positive"] & n4["PLA2R ag Negative"]
    n4 --> n5["Screen for contitions associated with MN"]
    n3 --> n6["• RAS Blockade (ACEi/ARB)
    • BP Control (SBP&lt;120)
    • Low Salt Diet
    • Diuretics/SGLT2i
    • Statin"] & n5
    D --> n7["• RAS Blockade (ACEi/ARB)
    • BP Control (SBP&lt;120)
    • Low Salt Diet
    • Diuretics/SGLT2i
    • Statin"] & n8["Screen for contitions associated with MN"]
    n7 --> n9["Monitor PLA2R ab every 3months for 6 months
    [High ab titers may (>150RU/mL) may require short testing internvals]"]
    n8 --> n9
    n9 --> n10["Stratify Risk Category: Low, Moderate, high, high risk"] & n11["• Life-threatening nephrotic syndrome
    or
    • Rapid Deterioration of kidney function not otherwise explain"]
    n11 --> n12[" • Can skip 3-6month waiting period and initate treatemnt with Cyclophosphamide + glucocortidcoids 
    • Consider Kidney biopsy"]
    B@{ shape: rounded}
    C@{ shape: rounded}
    D@{ shape: rounded}
    n1@{ shape: rounded}
    n3@{ shape: rounded}
    n4@{ shape: rounded}
    n5@{ shape: rounded}
    n8@{ shape: rounded}
    n9@{ shape: rounded}
    style A fill:#FFCDD2
    style B fill:#E1BEE7
    style C fill:#E1BEE7
    style D fill:#E1BEE7
    style n1 fill:#E1BEE7
    style n2 fill:#BBDEFB
    style n3 fill:#E1BEE7
    style n4 fill:#E1BEE7
    style n5 fill:#E1BEE7
    style n6 fill:#BBDEFB,text-align:left,white-space:nowrap
    style n7 fill:#BBDEFB,text-align:left,white-space:nowrap
    style n8 fill:#E1BEE7
    style n9 fill:#E1BEE7,white-space:nowrap
    style n10 fill:#BBDEFB
    style n11 fill:#BBDEFB,text-align:left
    style n12 fill:#BBDEFB,text-align:left
```
### Risk Categories
```mermaid
---
config:
  kanban:
    ticketBaseUrl: 'https://github.com/mermaid-js/mermaid/issues/#TICKET#'
  theme: forest
---
kanban
  Low risk
    docs[ • Normal eGFR, proteinuria <3.5g/d and serume albumin >30g/last
    or
    • Normal eGFR, or a decrease >50% after 6 months of conserative therapy with ACEi/ARB]
  [Moderate Risk]
    id6[• Normal eGFR, proteinuria, and no decrease >50% after 6 months of conserative therapy with ACEi/ARB
    and
    • Not fulfilling high-risk criteria ]
  [High risk]
    id4[• eGFR < 60ml/min/1.73m² and/or Proteinuria > 8g/d for >6months
    or
    • Normal eGFR, Proteinuria >3.5g/d and no decrease >50% after 6months of conservative therapy with ACEi/ARB 
    and at least one of the following:
    • Serum albumin <25 g/l
    • PLA2Rab >50 RU/ml 
    • Urinary α₁-microglobulin >40 µg/min
    • Urinary IgG >1 µg/min
    • Urinary β₂-microglobulin >250 mg/d
    • Selectivity index > 0.2]
  [Very High Risk]
    id5[• Life-threatening Nephrotic Syndrome 
    or
    • Rapid deterioration of kidney function not otherwise explained]
```
### Treatment Regimens 
 * Cyclophosphamid (cyclical)(Modified ponticell)
    1. Methylprednisolone 1g IV for 3 consecutive days at start of Month 1, 3, and 5
    2. Prednisone 0.5mg/kg/day in months 1, 3, 5, after finishing doses of methylprednisolone
    3. Cyclophosphamide 2.5mg/kg day in months 2, 4, and 6
 * Cyclophosphamide (continuous)
    1. Methylprednisolone 1g IV for 3 consecutive days at start of Month 1, 3, and 5
    2. Prednisone 0.5mg/kg/day every other day in months 1-6
    3. Cyclophophosphamide 1.5mg/kg/day in months 1-6
 * Rituximab
    1. Rituximab 1g IV administered twice w/in 2 weeks or
    2. Rituximab 375mg/m2 given 1-4 times at weekly intervals 
 * Tacrolimus
    1. Tacrolimus 0.05-0.1mg/kg/day
    2. Target trough 3-8ng/mL(3.7-9.9nmol/l)
    3. Duration of 12 months
 * Cyclosporine
    1. Cyclosporine 3.5mg/kg/day
    2. Target trough level 125-225 ng/ml (104-187nmol/l)
### Initial immunosupressive therapy
```mermaid
---
config:
  theme: redux
---
flowchart TD
    n9["Monitor PLA2R ab q3months for 6 months
    [High ab titers may (>150RU/mL) may require short testing internvals]"] --> n10["Low Risk"] & n11["Moderate Risk"] & n12["High Risk"] & n13["Very High Risk"]
    n11 --> n15["PLA2R ab negative/ Decreasing or low levles of ab"] & n16["Persistent PLA2R ab after 3-6months"] & n17["Increasing levels of PLA2R"]
    n12 --> n18["• Consider kidney Bx
    • Rituximab 
    or 
    • Cyclophosphamide + glucocorticoids
    or
    •CNI + glucocorticoids"]
    n13 --> n19["• Consider kidney Bx
    • Cyclophosphamide + glucocorticoids"]
    n17 --> n20["• Consider kidney Bx
    • Rituximab 
    or
    •CNI + glucocorticoids"]
    n15 --> n21(["Remission"])
    n16 --> n22["• Persistent Disease activity Re-consider therapy
    • Consider kidney Bx"]
    n21 --> n23["• Continue supportive therapy
    • Continue to monitor"]
    n18 --> n24["Measure PLA2R ab at 3 or 6 months
    (Most patient start responding at 3 months of therapy)"]
    n19 --> n24
    n22 --> n24
    n20 --> n24
    n24 --> n26["PLA2R ab Present, but low or decreasing"] & n27["PLA2R ab Persistent"] & n28["**PLA2R ab negative**
    • supportive therapy
    • Rituximab --> no additional tx
    • Cyclophosphamide + glucocorticoids --> DC cyclophosphamide taper glucocorticoids
    •CNI --> Taper CNI and glucocorticoids"]
    n26 --> n29["Evaluate PLA2R at 3 or 6 month intervals"]
    n29 --> n30["**PLA2R ab negative**
    • supportive therapy
    • Rituximab --> no additional tx
    • Cyclophosphamide + glucocorticoids --> DC cyclophosphamide taper glucocorticoids
    •CNI --> Taper CNI and glucocorticoids"] & n31["PLA2R ab Persistent"]
    n31 --> n32(["Resistent Disease"])
    n27 --> n32 & n73["• Rituximab --> continue with Rituximab 2g (see treatment tabel)
    • Cyclophosphamide + glucocorticoids --> Stop cyclophosphamide and taper glucocorticoids and start Rituximab
    •CNI --> Taper CNI and glucocorticoids and re-evaluate at 6 months"]
    n73 --> n74["Persistent PLA2R ab at 3 or 6 months"]
    n74 --> n32
    n10 --> n75["• Continue supportive therapy
    • Continue to monitor"]
    n9@{ shape: rounded}
    n10@{ shape: hex}
    n11@{ shape: hex}
    n12@{ shape: hex}
    n13@{ shape: hex}
    n15@{ shape: rounded}
    n16@{ shape: rounded}
    n17@{ shape: rounded}
    n24@{ shape: rounded}
    n26@{ shape: rounded}
    n27@{ shape: rounded}
    n29@{ shape: rounded}
    n31@{ shape: rounded}
    style n9 fill:#E1BEE7,text-align:left,white-space:nowrap
    style n10 fill:#FFF9C4
    style n11 fill:#FFF9C4
    style n12 fill:#FFF9C4
    style n13 fill:#FFF9C4
    style n15 fill:#E1BEE7
    style n16 fill:#E1BEE7
    style n17 fill:#E1BEE7
    style n18 fill:#BBDEFB,text-align:left,white-space:nowrap
    style n19 fill:#BBDEFB,text-align:left,white-space:nowrap
    style n20 fill:#BBDEFB
    style n21 fill:#FFCDD2
    style n22 fill:#BBDEFB,text-align:left,white-space:nowrap
    style n23 fill:#BBDEFB,text-align:left,white-space:nowrap
    style n24 fill:#E1BEE7
    style n26 fill:#E1BEE7,text-align:left,white-space:nowrap
    style n27 fill:#E1BEE7
    style n28 fill:#BBDEFB
    style n29 fill:#E1BEE7
    style n30 fill:#BBDEFB
    style n31 fill:#E1BEE7
    style n32 color:#000000,fill:#FFCDD2,text-align:left,white-space:nowrap
    style n73 fill:#BBDEFB,text-align:left,white-space:nowrap
    style n74 fill:#BBDEFB
    style n75 fill:#BBDEFB
```
### Resistent disease
```mermaid
---
config:
  theme: redux
---
flowchart TD
    n32(["Resistent Disease"]) --> n54["eGFR stable"] & n55["eGFR decreasing"]
    n54 --> n57["Initial tx 
    Rituximab"] & n58["Initial tx
    CNI"] & n59["Initial tx
    Cyclosphosphamide + glucocorticoids"]
    n55 --> n60["Initial tx
    Rituximab"] & n61["Initial tx
    CNI"] & n62["Initial tx
    Cyclosphosphamide + glucocorticoids"]
    n57 --> n63["Rituximab + CNI"]
    n58 --> n64["Rituximab"]
    n59 --> n65["Rituximab"]
    n60 --> n66["Cyclosphosphamide + glucocorticoids"]
    n61 --> n66
    n62 --> n66
    n63 --> n67["PLA2R ab at 3 months"]
    n64 --> n67
    n65 --> n67
    n67 --> n70["**PLA2R ab negative**
    • supportive therapy
    • Rituximab --> no additional tx
    • Cyclophosphamide + glucocorticoids --> DC cyclophosphamide taper glucocorticoids
    •CNI --> Taper CNI and glucocorticoids"] & n71["Persistent PLA2R ab"]
    n66 --> n68["Persistent PLA2R ab"] & n72["**PLA2R ab negative**
    • supportive therapy
    • Rituximab --> no additional tx
    • Cyclophosphamide + glucocorticoids --> DC cyclophosphamide taper glucocorticoids
    •CNI --> Taper CNI and glucocorticoids"]
    n68 --> n69["Consult Expert Center"]
    n71 --> n66
    n54@{ shape: rounded}
    n55@{ shape: rounded}
    n67@{ shape: rounded}
    n71@{ shape: rounded}
    n68@{ shape: rounded}
    style n32 color:#000000,fill:#FFCDD2
    style n54 fill:#E1BEE7
    style n55 fill:#E1BEE7
    style n57 fill:#BBDEFB
    style n58 fill:#BBDEFB
    style n59 fill:#BBDEFB
    style n60 fill:#BBDEFB
    style n61 fill:#BBDEFB
    style n62 fill:#BBDEFB
    style n63 fill:#BBDEFB
    style n64 fill:#BBDEFB
    style n65 fill:#BBDEFB
    style n66 fill:#BBDEFB
    style n67 fill:#E1BEE7
    style n70 fill:#BBDEFB
    style n71 fill:#E1BEE7
    style n68 fill:#E1BEE7
    style n72 fill:#BBDEFB
    style n69 fill:#BBDEFB
```
### Comming Therapies
  * Obinutuzumab vs tac in Majesty trial --> Primary partial complet date December 2025, Expected completion Date December 2027
  * Combo therapy with short course cyclosporin and glucocorticoids with Rituximab 
## **Sources**
* [KDIGO GN Guidlines](https://kdigo.org/guidelines/gd/)
* [Serology based approach](https://pubmed.ncbi.nlm.nih.gov/27777266/)
* [SGLT2 in primary and secondary glomerulonephritis](https://pubmed.ncbi.nlm.nih.gov/37550217/)
* [Rituximab for Severe Membranous Nephropathy](https://pubmed.ncbi.nlm.nih.gov/27352623/)
* [Rituximab or Cyclosporine in Treatment of Membranous Nephropathy](https://pubmed.ncbi.nlm.nih.gov/31269364/)
* [Alternating treatment with corticosteroids and cyclophosphamide superior to tx with tacrolimus and rituximab](https://pubmed.ncbi.nlm.nih.gov/33166580/)
* [Comparison of Obinutuzumab and Rituximab for Treating Primary MN](https://pubmed.ncbi.nlm.nih.gov/39207845/)
* [Combination Rituximab, and low dose cyclophosphamide and prednisone for Primary Membrandous](https://pubmed.ncbi.nlm.nih.gov/34174365/)
---
*Last updated: 9/2025 by Ashley Kinder, D.O.*
*Next review: 9/2026*
