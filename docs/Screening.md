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
