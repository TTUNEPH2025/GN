## **Anticoagulation**
### **General Information**
* Risk of thrombosis is higher with patients with Nephrotic Syndrome than the general population
* DVT and Renal Vein thrombosis are the most commen, with Pulmonary embolus common as well
* Thrombotic events are most common with Membranous Nephropathy, but can occur with other Nephrotic diseases
* Degree of Proteinuria and serum albumin are best predictors of thrombotic risk
* Additional risk factors: prior thrombosis, gentic predisposition, antiphospholipid antibodies, Immobility, obesity, Maligangcy, pregnancy, or surgery
* Heparin and Warfarin are medications or choice for prophylaxis and/or treatment of thrombosis
    1. No studies currently avaible comparing DOAC or LMW Heparin
    2. DOAC are heavily albumin-bound and dosing in low albumin states has not been studied
### **Anticoagulation in Nephrotic syndrome**
* For thromboembolic events Full dose anticoagulation is required for 6-12 months and/or the duration of the nephrotic syndrome
    1. Venous thrombosis
    2. Arterial throbosis
    3. PE
    4. Nonvalvular atrial Fibrillation
* Prophylactic full dose anticoagulation should be consider if
    1. Serum albumin < 20-25g/l
    2. BMI > 35 kg/m2
    3. Genetic disposition for thrombosis
    4. Heart Failure NYHA class III or IV
    5. Recent orthopedic or abdominal surgery
    6. prolonged immobilization
* Relative or absolute contraindications to prophylactic anticoagulation
    1. Patient preference/abilit to adhere to medications
    2. Hx of bleeding
    3. CNS lesion prone to hemorrhage
    4. Genetic mutations influencing warfarin metabolism
    5. Frailty
 ```mermaid
flowchart TD
    A(["Serum albumin
        &lt;25 g/l or 2.5g/dl"]) --> n17["Yes"] & n18["No"]
    B["High Risk Thrombus"] --> C["GN tool/risk calculator"]
    n1["Serum albumin
    &lt;32g/l or 3.2g/dl"] --> n21["Yes"] & n22["No"]
    n2["Estimate arterial thrombus risk"] --> n3["Framingam risk score, eGFR, diabetes, hx of arterial embolism"]
    C --> n19["Low bleeding risk"] & n20["High bleeding risk"]
    n3 --> n23["Risk > 20/1000 patient-year"] & n24["Risk &lt; 20/1000 patient-year"]
    n5["No Warfarin"] --> n6["Aspirn"]
    n17 --> B
    n18 --> n1
    n19 --> n4["Warfarin"]
    n20 --> n5
    n21 --> n2
    n22 --> n7["No Aspirin"]
    n24 --> n7
    n23 --> n6
    B@{ shape: rounded}
    C@{ shape: rounded}
    n1@{ shape: rounded}
    n2@{ shape: rounded}
    n3@{ shape: rounded}
    n5@{ shape: rounded}
    n6@{ shape: rounded}
    n4@{ shape: rounded}
    n7@{ shape: rounded}
     A:::Pine
     n17:::Aqua
     n18:::Aqua
     B:::Pine
     C:::Pine
     n1:::Pine
     n21:::Aqua
     n22:::Aqua
     n2:::Pine
     n3:::Pine
     n19:::Aqua
     n20:::Aqua
     n23:::Aqua
     n24:::Aqua
     n5:::Pine
     n6:::Pine
     n4:::Pine
     n7:::Pine
    classDef Aqua stroke-width:1px, stroke-dasharray:none, stroke:#46EDC8, fill:#DEFFF8, color:#378E7A
    classDef Pine stroke-width:1px, stroke-dasharray:none, stroke:#254336, fill:#27654A, color:#FFFFFF
```
*[GN tool/Risk Calculator](https://www.med.unc.edu/gntools/bleedrisk.html)
## **Vaccinations**
 * Pneumococcal Vaccinatation
   * Patient and entire house hold should recieve both 7vPCV and 23vPPV
* Anual Influenza
* Avoid all live Vaccinations (MMR, Varicella, rotavirus, yellow fever) should be deferred until prednisone dose is < 20mg/d or immunosuppressive agents have been stopped for at least 1-3months
* Patient recieving complement antagonists should have
   * Menigococcal Conjugate Vacine
       1. depending the brand and age of patient may require 2,3, or 4 doses
       2. Booster dose every 5 years for the duration of complement inhibitor therapy
   * Serogroup B menigococcal Vaccine
       1. Requires 3 doses
       2. Booster doses one year after completion of series and every 2-3 years therafter for duration of complement inhibitor therapy
 * Shingrix vaccine is safe should be given to patient, but immunosuppression may reduce its efficacy
## **Antibiotics in setting of Immunosupression**
 * Bactrim (TMP-SMX)
   * While patient on high dose prednisone or other immunosuppressive agents (rituximab, cyclophosphamide)
   * Atovaquone or pentamidine may be substituted for patient's with sulfa-allergy --> recommendation based on immunosuppressed patient w/out glomerular disease
## **Other**
 * H2 blockers or PPI while on steroids --> prevention of Peptic ulcer disease
 * Limit UV exposure and appropiate use of Broad spectrum sunscreent
 * Effective contraception [Patient Counseling](Counseling.md)
## **Sources**
* [KDIGO GN Guidlines](https://kdigo.org/guidelines/gd/)
* [CDC Menigococcal Vaccination](https://www.cdc.gov/meningococcal/hcp/clinical-guidance/complement-inhibitor.html?CDC_AAref_Val=https://www.cdc.gov/meningococcal/clinical/eculizumab.html)
