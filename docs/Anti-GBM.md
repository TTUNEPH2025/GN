# **Anti-Glomerular Basement Membrane (Anti-GBM)**
## **Overview**
  * Rapidly progressive Crescent GN
    1. 95% of patients present with crescents
  * One wave of acute injury
  * Incidence of 0.5-1 per million
  * Equal Male:Female ratio
  * Most common in Caucasians and older Asians 
  * Occurs as isolated kidney disease or Pulm-renal syndrome (Goodpasture's)
    1. 40-60% of patient have alveolar invovlement --> predomintly young males with pulm and renal involvement
    2. Alveolar involvement more likely with smokers 
  * Biphasic distribution: 20-30's and 60-70
  * Typically do no flair after treatment from disease
     1. If flair occurs should conisder ANCA associated disease
  * Timming of treatment matters --> early treament the better
  * Prior to immunosupression therapy had a 96 mortality rate which has dropped to 47 with immunosupression therapy
    1. This mortality rate drops further for those patient's with pulmonary hemorrhage who recieve Plasmaphoresis and immunotherapy to 8.5% mortality 
  * Disease can re-occur in transplant if ant-gbm titer still detectable
    1. Typically recommend 6 months or more of undetectable anti-gbm levels prior to transplant
## **Pathophysiology**
 * Autoantibody against the non-collagenous domain of the alpha3 chain of type IV collagen which can be found in the glomerlous and the alveoli 
   1. With alveolar hemorrhage: Goodpasture Syndrome
   2. W/out alveolar hemorrhage: Anti-GBM GN
 * Pathology: Linear staining for IgG or rarely IgA on IM
 * Alloimune ANti-GBM: patients w/type 4 collagen mutation recieve a kidney transplant from done w/out mutation: Antibodies form against GBM of transplanted kidney (typically occurs in some genetic variation of Alport syndrome)
### Cresentic GN
 * Cresents are etiologically and pathogenically a nonspecific response to glomerular capilary rupture that is typically caused by inflammmatory injury
 * Types: Cellular, fibrocellular, fibrous, and pseudocrescent
   1. Higher number of fibrous cresents present on biopsy--> less likely to have recovery
 * Cresentic lesions can be found on wide range of GN with varying percentages of glomerulus
 * Anti-GBM and ANCA vasculitis are considered "rapidly progressive cresentic gn". Both of which are typically severe and agressive with greater than 50% Crescents found on light microscopy
## **Clinical Presentation**
 * Hematuria/Proteinuria 
 * W/ or w/out alveolar hemorrhage: dignosed clinical or with high resolution CT
 * Rapidly rising Cr/Dropping eGFR: rapidly crescent GN
## **Treatment**
```mermaid
---
config:
  theme: redux
---
flowchart TD
    A(["Rapidly Progressive GN"]) --> n2["Alveolar Hemorrhage"]
    n2 -- Present --> n3["Begin Treatment w/in first 24hr of presentation
    • PLEX, Steroids, and Cyclophosphamide"]
    n2 -- Abscent --> n4["**Test**
    • Anti-GMB 
    • ANCA
    • ANA
    • Exclude infection
    • Kidney biopsy"]
    n3 --> n5["Plasma Exchange"] & n6["Glucocorticoids"] & n7["Cyclophosphamide"] & n4
    n5 --> n8@{ label: "• 40-50 ml/kg of Ideal body weight Daily against 5% albumin\n    •Add FFP at end of treatment in patient's w/alveolar hemmorrhage or after kidney bx" }
    n6 --> n9["• Methylprednisone 1000mg/day for 3 consecutive days followed by
    • Prednisone 1mg/kg daily reduced down to
    • Prednisone 20mg Daily by week 6"]
    n7 --> n10["• 2-3mg/kg daily (reduce dose for pt >55 to 2mg/kg)
    • Data with IV cyclophosphamide limited, but can be used"]
    n8 --> n11["To be continue to be continue until anti-GBM titers are negative
    • typically after 14 days of treatment"]
    n9 --> n12["Continue for a duration of 6 months"]
    n10 --> n13["Continue for a duration of 3 months"] & n14["If patient not able to tolerate or not responding to cyclophosphamide consider
    • Rituximab or Mycophenolate Mofetil"]
    n13 --> n15["Persistent Anti-GBM titers after 3 months
    • Treat with either Azothioprine or mycophenolate in combo w/steroids
    • Consider treatment with Rituximab"]
    n4 --> n16["Positive for Anti-GBM"] & n17["Positive for ANCA and Ant-GBM"]
    n16 --> n3
    n17 --> n18["Treat as ANCA associated Vasculitis w/mainance therapy"]
    n2@{ shape: rounded}
    n3@{ shape: rounded}
    n4@{ shape: rounded}
    n8@{ shape: rect}
    n11@{ shape: rounded}
    n12@{ shape: rounded}
    n13@{ shape: rounded}
    n14@{ shape: rounded}
    n16@{ shape: rounded}
    n17@{ shape: rounded}
    n18@{ shape: rounded}
    style A fill:#FFF9C4
    style n2 fill:#FFF9C4
    style n3 fill:#FFF9C4,text-align:left
    style n4 fill:#FFF9C4,text-align:left
    style n5 fill:#FFE0B2
    style n6 fill:#FFE0B2
    style n7 fill:#FFE0B2
    style n8 fill:#FFE0B2,text-align:left
    style n9 fill:#FFE0B2,text-align:left
    style n10 fill:#FFE0B2,text-align:left
    style n11 fill:#FFF9C4,text-align:left
    style n12 fill:#FFF9C4
    style n13 fill:#FFF9C4,text-align:left
    style n14 fill:#FFF9C4,text-align:left
    style n15 fill:#FFE0B2,text-align:left
    style n16 fill:#FFF9C4
    style n17 fill:#FFF9C4
    style n18 fill:#FFF9C4
```


 * Most Anti-GBM is cleared in the first 8 weeks of treatment after PLEX and Immunsupression initiated
 * Relapses uncommon --> may occure in patient who smoke or are exposed to lun irritants
 * If serious infection during treatment can add IVIG post PLEX treatment with abx
 * [Prophylaxis](Prophylaxis.md)
## **Sources**
* [KDIGO GN Guidlines](https://kdigo.org/guidelines/gd/)
