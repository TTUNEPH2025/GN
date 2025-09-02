# **Focal Segmental Glomerulosclerosis (FSGS)** 
## **OverView**
  * Most common cause of Nephrotic syndrome in U.S.
  * 3 types: Idiopathic, Secondary, and Genetic
  * Idiopathic can reoccur in  Transplant patients (typically rapid coures in the first months)
  * Patient's with APOL1 varient: increase incidence of FSGS typical lesions and collapsing lesions 
## **Pathophysiology** 
  * Primary: Circulating Permeability factors yet to identified
     1. Pathology: Focal segmental glomerulosclerosis and foot process effacement (may be duffuse or variable)
     2. Reoccurs in transplant patients
     3. Responds to Plasmapheresis in transplant patient
  * Secondary: has a known cause
     1. Pathology: FSGS lesions, with or without  foot process effacement
     2. Adaptive changes to glomerular hyperfiltration typicallly in the setting of reduced nephron mass (low birth weight, reflux nephropathy, renal dysplasia secondary to other renal disease)
     3. Direct podocyt injury: HIV, Parvo, ect. 
  * Genetic
     1. Mutations in podocyte or glomular basement membrane
     2. Not routinely tested in adults
     3. Should be considered in adults resistent to steroid therapy
     4. Patient's with APOL1 are more susceptible to develop these lesions
  * MCD vs FSGS
     1. Both have foot process effacement
     2. FSGS: presence of segmental sclerosis and early findings demonstrate tubulointerstitial fibrosis and glomerular hypertrophy 
  * Circulating factors currently under investigation for primary FSGS
     1. Anti-Nephrin Ab
     2. SuPAR (not specific  for FSGS)
     3. Cardiotropphine-like cytokine 
## **Clinical Presentation**
  * Proteniuria > 3.5g/d
  * Hypoalbuminemia <30g/L
  * Dyslipidemia
  * Edema/signs of volume overload
## **Primary vs Secondary**
```mermaid
flowchart TD
    A(["FSGS on Biopsy"]) --> C["**Nephrotic Syndrome**
    • Protenuria &gt; 3.5g/d
      and
    • Serum albuming &lt;30g/L (w/or w/out edema)
    • Diffuse foot process effacement"] & n2["**Abscence of Nephrotic syndrome**
    • Proteinuria &gt;3.5g/d and serum albumin &gt;30g/L 
             or
    • Protenuira &lt;3.5g/d w/or w/out hypoalbumina"]
    C --> n3["**Likely Primary FSGS**
    • tx w/immunosuppression
    • If no response, consider genetic testing"]
    n2 --> n4["• Evaluate for underlying cause (exclude secondary FSGS)
    • Do not start immunosupression
    • Supportive therapy
    • Monitor Proteinuria and serum albumin"]
    n4 --> n5["Worsening proteinuira and reduction in serum albumin"]
    n5 --> n3
    style n4 white-space:nowrap
    style C white-space:nowrap
    style n2 white-space:nowrap
    style n3 white-space:nowrap
```
### **Genetic testing consideration**
  * Younger patient's with FSGS
  * Patient's w/family members w/FSGS
  * FSGS patient's resistent to therapy
  * Benefits of Genetic testing: avoid immunosuppressives, guide tx for transplant (who can donate), guide for recurrence
## **Drugs and Disease Associated with FSGS**
  * Infectious
    1. HIV
    2. Parvo B19
    3. CMV
    4. COVID 19
  * Adapative
    1. Low nephron mass (low birth weight, surgical removal)
    2. Obesity 
    3. Remnant kidney
    4. Diabetic Nephropahty
    5. Reflux Nephropathy
    6. Oligomeganephronia
  * Drugs
    1. Interferon
    2. Pamidronate
    3. anabolic steroids
    4. CNI
    5. NSAIDs
    6. Lithium
    7. DAAV (direct acting anti-viral)
    8. mTORs
    9. Heroin
## **Definitions of Treatment Response**
  * Complete remission
     1. Reduction of proteinuria to <0.3g/d or PCR <300mg/d (or 30mg/mmol)
     2. Stable serume Creatinine
     3. Serum albumin >3.5 g/dL (or 35g/L)
  * Partial REmission
     1. Reduction of proteinuria to 0.3-3.5g/d or PCR 300-3500mg/g (or 30-350mg/mmol)
     2. decrease >50% from baseline
  * Relapse
     1. Proteinuria of >3.5g/d or PCR >3500mg/d (or 350mg/mmol) after complete remission achieved
     2. Increase in proteinuria by >50% during partial remission
  * Steroid-resistand FSGS
     1. Persistence of proteinuria >3.5g/d or PCR >3500mg/d (or 350mg/mmol) w/<50% reduction from baseline despite adequate dosing of prednisone for at least 16 wks
  * Steroid-dependent FSGS
    1. Relapse occuring during or w/in 2wk of completing glucocorticoid therapy
  * CNI-resistent FSGS
    1. Persistence of proteinuria >3.5g/d or PCR >3500mg/d (or 350mg/mmol) w/<50% reduction from baseline despite treatment with cyclosporine/tacrolimus with trough levels at goal ranges
  * CNI-dependent FSGS
    1. Relapse occuring during or w/in 2wks of completeing cyclosporine/tacrolimus therapy for >12mo
## **Treatment**
### **Initial treatment**
```mermaid
flowchart TD
    A(["FSGS"]) --> B(["Primary"]) & n1(["Secondary/Undetermined Cause"])
    n1 --> n2["• RAS blockade
     • BP control
     • Low Salt Diet
     • Diuretics/SGLT2i"] & n3["Find/tx Secondary cause"]
    B --> n26["• RAS blockade
     • BP control
     • Low Salt Diet
     • Diuretics/SGLT2i"]
    n4["•Predinsone 1mg/kg Daily (max 80mg/day)
    or
    • Prednisone 2mg/kg EOD (max 120mg/day)"] --> n5["•Continue for at least 4wk & complete remission 
    or 
    • max of 16wk"]
    n24(["Steroids Contraindicated"]) --> n25["• Cyclosporin 3-5mg/kg/day divided into two doses (trough 100-175ng/mL; 83-146nmol/L)
     • Tacrolimus 0.05-0.1mg/kg/day divided into two doses (trough 5-10ng/mL; 6-12mmol/L)"]
    n26 --> n24 & n27(["No Contraindications Steroids"])
    n27 --> n4
     A:::Peach
     B:::Peach
     n1:::Peach
     n24:::Peach
     n27:::Peach
    classDef Peach stroke-width:1px, stroke-dasharray:none, stroke:#FBB35A, fill:#FFEFDB, color:#8F632D
    classDef Class_01 fill:#FFCDD2
    style n2 fill:#FFCDD2,stroke:#000000
    style n3 fill:#FFCDD2,stroke:#000000
    style n26 fill:#FFCDD2,stroke:#000000
    style n4 fill:#FFCDD2,stroke:#000000
    style n5 stroke:#000000,fill:#FFCDD2
    style n25 fill:#FFCDD2,stroke:#000000
```
### **Treatment response**
```mermaid
flowchart TD
    n6["Continue hig dose for 2wks after remission"] --> n7["taper prednisone by 5mg every 1-2wks for 6 months"]
    n7 --> n8(["Relapse"]) & n9(["Monitor for Relapse"])
    n8 --> n10["**Approached like MCD**
     • Prednisone 1mg/kg dailys (max of 80mg/day) for 4wks or until remission"]
    n10 --> n11["Wean by 5mg every 3-5 days till DC w/ing 1-2 months
    *low Quality of evidence"]
    n12(["Partial Remission at 8-12wk continue to 16 wks"]) --> n13(["Remission"]) & n14(["No Remission"])
    n13 --> n7
    n14 --> n21(["CNI Contraindicated"]) & n28(["No Contraindications to CNI"])
    n15["• Cyclosporin 3-5mg/kg/day divided into two doses (trough 100-175ng/mL; 83-146nmol/L)
     • Tacrolimus 0.05-0.1mg/kg/day divided into two doses (trough 5-10ng/mL; 6-12mmol/L)"] --> n16["Continued at target trough level for 4-6months (before considered CNI resistent)"]
    n16 --> n17(["Partial or coplete remission"])
    n17 --> n18["Continued for 12months and taper over 6-12months"]
    n18 --> n19(["No remission"])
    n19 --> n20["• Re-biopsy
     • Refer to Specialiazed Centers
     • Enroll in trials
     • MMF, high dose dexamethasone, Rituximab, and ACTH"]
    n21 --> n20
    n22(["Persistent/unremiting"]) --> n30["Do not need to complete 16wk tx"] & n23["Genetic testing"]
    n28 --> n15
    n29(["Remission"]) --> n6
     n8:::Peach
     n9:::Peach
     n12:::Peach
     n13:::Peach
     n14:::Peach
     n21:::Peach
     n28:::Peach
     n17:::Peach
     n19:::Peach
     n22:::Peach
     n23:::Class_01
     n29:::Peach
    classDef Peach stroke-width:1px, stroke-dasharray:none, stroke:#FBB35A, fill:#FFEFDB, color:#8F632D
    classDef Class_01 fill:#FFCDD2
    style n6 fill:#FFCDD2
    style n7 fill:#FFCDD2
    style n10 fill:#FFCDD2
    style n11 fill:#FFCDD2
    style n15 fill:#FFCDD2
    style n16 fill:#FFCDD2
    style n18 fill:#FFCDD2
    style n20 fill:#FFCDD2
    style n30 fill:#FFCDD2
```
### Other considerations
  * Rituximab
     1. Emerging as a secondline therapy
     2. Consider in patient's with multiple Treatment failures
     3. Consider using Rituximab +/- CNI
  * Endotheline Blockade: Sparsent vs Irbesartan pending FDA approval 
## **Sources** 
* [KDIGO GN Guidlines](https://kdigo.org/guidelines/gd/)
* [CNI w/Reduced-dose steroids as firstline therpay for FSGS](https://pubmed.ncbi.nlm.nih.gov/30596167/)
* [Long-Term Outcoms of Rituxiimab-treated Adul Patients w/Podocytopathies](https://pubmed.ncbi.nlm.nih.gov/39431468/)

---
*Last updated: 9/2025 by Ashley Kinder, D.O.*
*Next review: 9/2026*
