
# Purpose
The ```commons-foundations``` repository contains the canonical semantic assets of the Heliophysics Knowledge Commons. These artifacts define shared meaning and structure and are stewarded with heightened care.

Foundations exist to stabilize meaning while enabling scientific and technological innovation.


Changes here have downstream impact and therefore require explicit review.

# Proposed Structure
```
commons-foundations/
├── README.md
├── glossary/
│ ├── source-vocabularies/
│ ├── harmonized-glossary/
│ └── governance.md
├── ontologies/
│ ├── phenomena/
│ ├── regions/
│ ├── instruments/
│ ├── coordinates/
│ └── governance.md
├── data-models/
│ ├── helio-know/
│ ├── spase-extensions/
│ └── governance.md
└── artifact-governance/
└── foundations-governance.md
```

# Foundations Governance
```artifact-governance/foundations-governance.md``` defines:
- shared principles across all foundations
- criteria for accepting new foundational artifacts
- expectations for citation and reuse

# Promotion Path (Project -> Foundation)
Artifacts may be promoted into ```commons-foundations``` when they:
- demonstrate sustained use
- have clear scope and documentation
- have identified maintainers
- provide value beyond a single project

Promotion decisions are made jointly by stewards and documented in ```commons-governance/decision-records```.

# Relationship to Projects

Projects:
- may depend on foundations
- may propose extensions
- may incubate candidate foundational assets

Foundations:
- remain stable
- provide shared semantic ground
- enable interoperability across projects


