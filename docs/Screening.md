  ```mermaid
    A(["Serum albumin
        &lt;25 g/l or 2.5g/dl"]) --> B["High Risk Thrombus"] & n1["Serum albumin
    &lt;32g/l or 3.2g/dl"]
    B --> C["GN tool/risk calculator"]
    n1 --> n2["Estimate arterial thrombus risk"] & n7["No Aspirin"]
    n2 --> n3["Framingam risk score, eGFR, diabetes, hx of arterial embolism"]
    C --> n4["Warfarin"] & n5["No Warfarin"]
    n3 --> n6["Aspirn"] & n7
    n5 --> n6
    n16["Risk > 20/1000 patient-year"]
    n9["Yes"]
    n10["No"]
    n11["Yes"]
    n12["No"]
    n13["High bleeding risk"]
    n14["Low bleeding risk"]
    n15["Risk &lt; 20/1000 patient-year"]
    B@{ shape: rect}
    n16@{ shape: text}
    n9@{ shape: text}
    n10@{ shape: text}
    n11@{ shape: text}
    n12@{ shape: text}
    n13@{ shape: text}
    n14@{ shape: text}
    n15@{ shape: text}
```
