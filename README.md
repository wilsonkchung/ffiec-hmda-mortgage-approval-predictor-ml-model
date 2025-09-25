# Data Source and Usage
- The dataset used in this project is publicly available under the Home Mortgage Disclosure Act (HMDA), provided through the Federal Financial Institutions Examination Council (FFIEC). It is part of the public data record and is widely used for advanced analysis and research on mortgage lending practices, borrower characteristics, and regulatory compliance.
- https://ffiec.cfpb.gov

# Datasets and  Data Fields (Data Dictionary)
- HMDA Dataset:
    * https://ffiec.cfpb.gov/data-browser
- LAR Data Fields:
    * https://ffiec.cfpb.gov/documentation/publications/loan-level-datasets/lar-data-fields

# Data Selection Rationale
- For this project, I selected HMDA data from 2022 to 2024.
- A larger historical window (before 2020) was avoided because older data may capture outdated lending rules and underwriting practices that no longer reflect the current mortgage environment.
- In addition, data from the peak COVID-19 years (2020–2021) was excluded, as mortgage activity during this period exhibited unusual patterns due to emergency relief programs, historically low interest rates, and forbearance policies, which could bias the model.
- Restricting the dataset to 2022–2024 ensures the analysis reflects recent and relevant lending behavior.

# Acronyms and Abbreviations
- Federal Financial Institutions Examination Council (FFIEC)
- Consumer Financial Protection Bureau (cfpb)
- Home Mortgage Disclosure Act (HMDA)
- Loan/Application Register (LAR)