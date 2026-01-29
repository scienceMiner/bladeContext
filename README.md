# bladeContext
Context Engineering Repository

Overview
This repository provides standardized metadata templates for financial context engineering - a systematic approach to structuring investment information for analysis, comparison, and decision-making.

Purpose
Financial context engineering establishes consistent frameworks for:

Structured financial reporting across different asset classes

Comparable analysis between securities using standardized metrics

Automated data processing through consistent schema definitions

Context-aware investment decisions with comprehensive risk/return frameworks

Repository Structure
text
├── templates/                    # Core template definitions

│   ├── finance-report.md        # Main financial report specification

│   ├── equity-context.md        # Equity-specific context templates
│   ├── fixed-income-context.md  # Bond and fixed income templates
│   └── portfolio-context.md     # Portfolio-level analysis templates
│
├── examples/                    # Example implementations
│   ├── VAPX-analysis.md        # Example ETF analysis using templates
│   ├── AAPL-context.md         # Example equity context
│   └── portfolio-example.md    # Sample portfolio context
│
├── specifications/              # Detailed specifications
│   ├── data-requirements.md    # Data sourcing and validation rules
│   ├── metric-definitions.md   # Calculation methodologies
│   └── scoring-models.md       # Comparative scoring frameworks
│
└── tools/                      # Utility tools and scripts
    ├── context-validator.py    # Template validation script
    └── data-mapper.js          # Data to template mapping utility
