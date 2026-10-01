# IPL Dashboard Project Architecture

```text
                    ┌─────────────────────────┐
                    │ IPL Dashboard Project   │
                    └────────────┬────────────┘
                                 │
              ┌──────────────────┼──────────────────┐
              │                  │                  │
              ▼                  ▼                  ▼
      ┌───────────────┐  ┌───────────────┐  ┌───────────────┐
      │ Source Excel  │  │ Documentation │  │ Analysis Data │
      │ Workbook      │  │ + Diagrams    │  │ CSV Export    │
      └───────┬───────┘  └───────────────┘  └───────┬───────┘
              │                                      │
              └──────────────────┬───────────────────┘
                                 ▼
                    ┌─────────────────────────┐
                    │ Data Preparation        │
                    │ Cleaning / Validation   │
                    └────────────┬────────────┘
                                 ▼
                    ┌─────────────────────────┐
                    │ Data Model & KPIs       │
                    └────────────┬────────────┘
                                 ▼
                    ┌─────────────────────────┐
                    │ Dashboard Visual Layer  │
                    └────────────┬────────────┘
                                 ▼
                    ┌─────────────────────────┐
                    │ Insights / Reporting    │
                    └─────────────────────────┘
```

The primary source remains the Excel workbook. Documentation and analysis exports support reproducibility and portfolio presentation.
