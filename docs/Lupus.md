# **Lupus Nephritis (LN)**
## **Overview**
  * 6 Classes
      1. Minimal Mesangial LN
      2. Mesangial Proliferative LN
      3. Focal LN (< 50% of glomeruli)
      4. Diffuse LN (≥ 50% of glomeruli)
      5. Membranouse Lupus
      6. Advanced Sclerosing LN (≥ 90% global sclerosed glomeruli)
  * Can have mixed classes of LN
  * LN rare disease (20-60% of SLE cases)
  * Females > Males (90% of LN is females)
  * LN typically occurs more often in Black, Asian, and Hispanic Ethnicities
  * Up to 30% of LN patients progres to kidney failure w/in 15 years of diagnosis
  * Patient's SLE are at higher risk of cardiovascular events and mortality when diagnosised with LN
  * Early decrease i nprotenuria predicts improved kidney function outcomes
  * Childhood onset of SLE is a ssociated wtih increased risk of LN and more severe disease
## **Pathophysiology**
  * Pathogenesis
    1. Abnormal B lymphocyte hyperactivity --> mounting an immune response to dying cells
          - Any environment where there is delayed clearance of dying cells (e,g. infections, hormonal responces, drughs) along with genetic mutations that may account for predisposition to hyperactive immune responce may be associated with SLE
    3. Immunity
         - Inate: interferon regulation and production, Nucleic acid sensitivity, Increased TLR (toll-like receptors) signaling (activate immune responce and increase cell recruitment)
         - Adaptive: HLA-DR2, HLA-DR3, Bcell and Tcell activation and signialing
         - Immune Complex: Iincreased phagocytosis, cell adhesion, and compliment activation forming immunce complexes
         - Insitue Immune complex formation or pre-formed immune complex formation causing injury
  * Classes
    1. Class I and II: gnerally normal kidney function. May have low grade protienuria
    2. Class III
         - Active or inactive focal, segmental and/or global endocapillary and/or extracapillary GN involving < 50% glomeruli
         - Typically w/focal subendothelial deposites w/or w/out mesangial alteration
    4. Class IV
         - Active or inactive focal, segmental and/or global endocapillary and/or extracapillary GN involving ≥ 50% glomeruli
         - Typically w/focal subendothelial deposites w/or w/out mesangial alteration
    6. Class V
         - Global or segmental subepithelial immune deposites or their morphologic sequela w/or w/out mesangial alteration
         - May have advanced sclerosis
         - Can be added to class III or IV when subepithelial deposites involve at least 50% of glomerular capillary surface area in at least 50% of glomeruli
         - Patients with immunofluorescent staining positive for Ext 1/2 typically have overall better response to treatment
    8. Class VI
         - 90% or more of global sclerosed glomeruli
         - Classification classification for advanced disease, not likely to benefit from increased immune supression
  * TMA
    1. Causes most revelant to LN: TTP, Antiphospholipid, and compliment medicated diesease
    2. can occure due to shiga-toxin-HUS, Infections, drugs, or malignancies
## **Clinical Presentation**
  * Range of symptoms of SLE (including but not limited to) 
      - fatigue, fever, weight loss, Arthritis/arthralgia, butterfly rash, photosensitivity, alpecia, raynaud, pleurisy, pericarditis, lymphadenopathy, psychosis, etc.
      - LN symptoms: edema, hypoalbuminemia, proteinuria, hyperlipidemia, frothy urine, hematuria
  * Patient's with lupus should be screen yearly for proteinura: progeinuria of 500mg/dL or great should prompt further infestigation  
  * Labs:
      - Auto-ab: Anti-dsDNA, Anti-Smith, Anti-U1 ribonucleoprotein, anti-ro/SSA and anti-La/SSB, Anti-histone, anti-phospholipid
      - General: CBC, CMP, CK, UA, SPEP, ANA, ESR/CRP, Compolement levels
  * Drug induced lupus: anti-dsDNA or Anti-smith positive very rare, Anti-histone very commenly positive
  * In EULAR (European Alliance of Association for Rheumatology)/ACR (American College of Rheumatology) Criteria for diagnosis of lupus, Renal biopsy demonstrating class III or IV is susificiant on it's own to diagnosis SLE with no other clinical or immunologic criteria required. 
## **Drugs and Diseases Associated with Lupus**
  * Kidney disease in drug-induced lupus is rare
  * Some drugs commenly associated with drug-induced lupus are as follows: 
    - Minocycline
    - Hydralazine
    - Isoniazid
    - Procainamide
    - TNF therapies
## **Deffinitions of Treatment Response**
|Criteria|Definition|
|--------|----------|
|Complete Response| • Reduction in proteinuria < 0.5g/g measured as PCR from 24hr urine; • Stabilization or improvement in kidney function (± 10-15% of baseline);• W/in 6-12mo of starting therapy, but could take more than 12mo|
|Primary Efficacy Renal Response| • PCR ≤ 0.7 g/g; • eGFR that was no worse than 20% below the pre-flare value or ≥ 60mL/min per 1.73m²; • No use of rescue therapy for treatment failure|
|Partial response| • Reduction in progeinuria by at least 50% and < 3g/g measured as teh PCR from 24hr urine; • Stabilization or improvement in kidney function (± 10-15% of baseline); • W/in 6-12mo of starting therapy|
|No Kidney response| Failure to achieve a partial or complete response w/in 6-12mo of starting therapy|

  * Goals of tx
      - 25% reduction of protienuria at 3mo
      - 50% reduction of protienuria at 6mo
      - UPCR below 0.5-0.7mg/mg at 12mo

## **Treatment**
### All Lupus Nephritis patients
  * Hydroxychloroquine: 200-400mg as a single daily dose or divided into two doses
  * Anti-Proteinuria: RASS blockade (ACE/ARB) and SGLT2i
  * Life style changes: smoking cessation, exercise, body weight management, ect.
### Class I and II LN
```mermaid
---
config:
  theme: redux
  layout: dagre
---
flowchart TB
    A(["Class I or II on Bx"]) --> n1["Evaluate level of Proteinuria"]
    n1 --> n2["Low level Proteinuria"] & n3["Nephrotic Range Proteinuria"]
    n2 --> n4["• Lupus treatment guided by extra-renal symptoms
    • Hydroxychloroquine, RAAS blockade, SGLT2
    • Monitor proteinuria"]
    n3 --> n5["• Tx as MCD 
    • Hydroxychloroquine, RAAS blockade, SGLT2"]
    n5 --> n6["• Remission typically seen in 4wk
    • Optimal duation of therapy unknown"]
    n6 --> n7["Relapse"]
    n7 --> n8["Condisder Steroid therapy + MMF or Azathioprine, CNI"]
    n4 --> n9["Nephrotic Range prteinuria"]
    n9 --> n5

    n4@{ shape: rounded}
    n5@{ shape: rounded}
    n8@{ shape: rounded}
    style A fill:#C8E6C9
    style n1 fill:#C8E6C9
    style n2 fill:#C8E6C9
    style n3 fill:#C8E6C9,white-space:nowrap
    style n4 fill:#FFF9C4,text-align:left,white-space:nowrap
    style n5 fill:#FFF9C4,text-align:left,white-space:nowrap
    style n6 fill:#C8E6C9,text-align:left,white-space:nowrap
    style n7 fill:#C8E6C9
    style n8 fill:#FFF9C4,text-align:left,white-space:nowrap
    style n9 fill:#C8E6C9,white-space:nowrap
    click n5 "https://ttuneph2025.github.io/GN/MCD/"
```
### Class III and IV ± V
```mermaid
---
config:
  theme: redux
---
flowchart TB
    A(["Class III/IV ± V on Bx"]) --> n1["TMA present on Bx?"]
    n1 -- Positive --> n2["See treatment plan below"]
    n1 -- Negative --> n3["Assess Chronicity"]
    n3 --> n4["Active Disease"] & n5["Chronic Disease w/out Activity"]
    n4 --> n6["Pulse dose steroids + one of the following"]
    n5 --> n7["• Supportive therapy 
    • Hydroxychloroquine, RAAS blockade, SGLT2
    • Monitor proteinuriaUntitled Node"] & n8["If Class V present on Bx, treat as Class V"]
    n6 --> n9["CNI + MPAA"] & n10["MPA"] & n11["Cyclosphosphamide"] & n12["Belimumab + MPAA or/reduced-dose cyclophosphamide"]
    n9 --> n13["• Voclosporin 23.7mg BID and MPAA in pt w/eGFR &gt;45
    • Tacrolimus goal trough 5.5ng/mL 
    • Cyclosporine when volcosorin or tacrolimus no available
    • For duration of 3 years"]
    n10 --> n14["• For at least 6months
    • MMF 1-1.5g BID or Mycophenolic Acid 720-1080mg BID"]
    n11 --> n15["• tx for up to 6mo
    • IV 500mg q2wk for 6mo or 0.5-1g/m² for 6mo
    • PO 1-1.5mg/kg/d for 3mo (max 150mg/d) for 2-6mo"]
    n12 --> n16["• Belimumab: 10mg/kg q2wk for 3 doses, then q4wks
    • MPAA: MMF or MPA
    • Cyclophosphamide 500mg q2wk for 3mo"]
    n13 --> n17["• Preferred in patient w/nephrotic syndrome and relatively preserved renal function
    • If pt can not tolerate full dose of MPAA or unfit for cyclophosphamide"]
    n16 --> n18@{ label: "• May be preferred in patient's with repeat flairs or high risk kidney failure\n    • Not as effective in patients with severely elevated proteniura<br/>• Belimumab duration up to 2.5 years" }
    n17 --> n19["Assess Response to Therapy"]
    n14 --> n19
    n15 --> n19
    n18 --> n19
    n19 -- Adequate --> n20["Complete Therapy (≥36mo)"]
    n19 -- Inadequate --> n21["Consider Rituximab, Ocrelizumab, abatacep, enrol in trials"]
    n20 --> n22["Transition to Maintance Therapy"]
    n22 --> n23["• Taper steroids quickly and may be able to DC after > 12mo
    • Hydroxychloroquine and MPAA
    • CNI and Belimumab may be used as maintance therapy"]
    n9@{ shape: rounded}
    n10@{ shape: rounded}
    n11@{ shape: rounded}
    n12@{ shape: rounded}
    n13@{ shape: rounded}
    n14@{ shape: rounded}
    n15@{ shape: rounded}
    n16@{ shape: rounded}
    n21@{ shape: rounded}
    n23@{ shape: rounded}
    style A fill:#C8E6C9
    style n1 fill:#C8E6C9
    style n2 fill:#C8E6C9
    style n3 fill:#C8E6C9
    style n4 fill:#C8E6C9
    style n5 fill:#C8E6C9
    style n6 fill:#C8E6C9,white-space:nowrap
    style n7 fill:#C8E6C9,text-align:left
    style n8 fill:#C8E6C9,text-align:left
    style n9 fill:#FFF9C4,text-align:left
    style n10 fill:#FFF9C4,text-align:left
    style n11 fill:#FFF9C4,text-align:left
    style n12 fill:#FFF9C4,text-align:left
    style n13 fill:#FFF9C4,text-align:left
    style n14 fill:#FFF9C4,text-align:left
    style n15 fill:#FFF9C4,text-align:left
    style n16 fill:#FFF9C4,text-align:left
    style n17 fill:#C8E6C9,text-align:left
    style n18 fill:#C8E6C9
    style n19 fill:#C8E6C9
    style n20 fill:#C8E6C9
    style n21 fill:#FFF9C4
    style n22 fill:#C8E6C9,text-align:left,white-space:nowrap
    style n23 fill:#FFF9C4,text-align:left,white-space:nowrap
```
### TMA and LN
```mermaid
---
config:
  theme: redux
---
flowchart TB
    A(["LN + LN on Bx"]) --> n1["Obtain the following
    • ADAMTS13 activity
    • Antibody to ADAMTS13
    • Antiphospholipid Antibody
    • Heme/Onc consult if available"]
    n1 --> n2["Risk stratify while waiting on labs with PLASMIC Score"]
    n2 --> n3["Moderate/High risk (>5)"] & n4["Low Risk (0-4)"]
    n3 --> n5["Start PLEX and Glucocorticoid while awaiting lab results"]
    n4 --> n6["Wait for lab results"]
    n5 --> n7["Evaluate labs"]
    n6 --> n7
    n7 --> n8["Low ADAMTS 13 Activity (&lt;10%)"] & n9["• Normal ADAMTS13
    • Negative Antiphospholipids"] & n10["• Normal ADAMTS13 activit
    • Positive Antiphospholipids"]
    n8 --> n11["SLE associated TTP"]
    n9 --> n12["Eval for other TMA etiologies"]
    n10 --> n13["Antiphospholipid syndrome Nephropathy"]
    n11 --> n14["PLEX + Glucocorticoid + Rituximab ± Caplacizumab"]
    n12 --> n15["Primary or Secondary Complement-mediated TMA"] & n16["Treat other etiology"]
    n13 --> n17["Anticoagulation (Wafarin) ± PLEX"]
    n15 --> n18["Consider Eclizumab"]
    n18 --> n19["• Optimal dose and duration controversial
    • Typically does not respond well with PLEX, steroids, or cyclophosphamide"]
    n17 --> n20["PLEX and high-dose Glucocorticoids often used in catastropic APS and is associated with iproved patient survival"]

    n5@{ shape: rounded}
    n14@{ shape: rounded}
    n17@{ shape: rounded}
    n18@{ shape: rounded}
    n20@{ shape: rounded}
    style A fill:#C8E6C9
    style n1 fill:#C8E6C9
    style n2 fill:#C8E6C9
    style n3 fill:#C8E6C9
    style n4 fill:#C8E6C9
    style n5 fill:#FFF9C4
    style n6 fill:#C8E6C9
    style n7 fill:#C8E6C9
    style n8 fill:#C8E6C9
    style n9 fill:#C8E6C9
    style n10 fill:#C8E6C9
    style n11 fill:#C8E6C9
    style n12 fill:#C8E6C9
    style n13 fill:#C8E6C9
    style n14 fill:#C8E6C9
    style n15 fill:#C8E6C9
    style n16 fill:#C8E6C9
    style n17 fill:#FFF9C4
    style n18 fill:#FFF9C4
    style n19 fill:#C8E6C9
    style n20 fill:#FFF9C4
    click n2 "https://www.mdcalc.com/calc/10200/plasmic-score-ttp"
```
### Class V
## **Sources**
  * [KDIGO 2024 Lupus Guidelines](https://www.kidney-international.org/action/showPdf?pii=S0085-2538%2823%2900627-0)
  * [Risk of CV events and mortality in LN](https://pubmed.ncbi.nlm.nih.gov/28053276/)
  * [UPToDate Drug induced lupus](https://www-uptodate-com.ezproxy.ttuhsc.edu/contents/drug-induced-lupus?search=drug%20indued%20lupus&source=search_result&selectedTitle=4~150&usage_type=default&display_rank=4#H16)
  * [UpToDate diagnosis of SLE](https://www-uptodate-com.ezproxy.ttuhsc.edu/contents/systemic-lupus-erythematosus-in-adults-clinical-manifestations-and-diagnosis?search=symptoms%20of%20lupus&source=search_result&selectedTitle=1~150&usage_type=default&display_rank=1#H914180)
---
*Last updated: 12/2025 by Ashley Kinder, D.O.*
*Next review: 12/2026*
