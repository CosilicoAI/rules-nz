# rules-nz

New Zealand tax and benefit legislation in Akoma Ntoso XML format.

## Structure

```
rules-nz/
├── acts/                    # Primary legislation
│   ├── income-tax-act-2007/
│   ├── tax-administration-act-1994/
│   └── social-security-act-2018/
└── regulations/             # Secondary legislation
    └── (statutory regulations)
```

## Data Source

All legislation is sourced from [legislation.govt.nz](https://www.legislation.govt.nz/), the official New Zealand legislation website maintained by the Parliamentary Counsel Office (PCO).

New Zealand legislation is published in Akoma Ntoso XML format, an international standard for legal documents.

## Key Acts

### Income Tax Act 2007
The principal Act governing income tax in New Zealand, covering:
- Income definitions and calculation
- Deductions and allowances
- Tax credits (Working for Families, Independent Earner)
- Business income and losses

### Tax Administration Act 1994
Governs the administration of tax, including:
- Filing requirements
- Assessment and disputes
- Penalties and interest

### Social Security Act 2018
Covers welfare benefits including:
- Jobseeker Support
- Sole Parent Support
- Supported Living Payment
- Accommodation Supplement
- Best Start tax credit

## Usage

This repository provides the raw XML source files for encoding into the Cosilico DSL. The Akoma Ntoso format preserves:
- Hierarchical structure (Parts, Subparts, Sections, Subsections)
- Cross-references between provisions
- Amendment history
- Official citations

## License

New Zealand legislation is Crown copyright but freely available for reuse under the [New Zealand Government Open Access and Licensing framework (NZGOAL)](https://www.data.govt.nz/toolkit/policies/nzgoal/).
