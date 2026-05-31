# Repository Structure

```
synthetic-analytics-dataset-generator-prompts/
│
├── README.md
├── Project Structure.md
│
├── Retention Cohort Analysis/
│   ├── README.md
│   ├── Dataset Prompt.md
│   ├── Prompt Explanation.md
│   ├── Python Script.py
│   └── saas_retention_events_raw.csv
│
└── SaaS Funnel Analysis/
    ├── README.md
    ├── Dataset Prompt.md
    ├── Prompt Explanation.md
    ├── generate_saas_funnel_dataset.py
    └── saas_funnel_dataset.csv
```

The repository is organized by dataset case study:

- `README.md`  
  Main overview of this repository.

- `Project Structure.md`  
  Explanation of the repository structure and file organization.

- `01_SaaS_Funnel_Analysis/`  
  Folder for the SaaS funnel analysis dataset.

  - `README.md`  
    Dataset-specific overview.

  - `Dataset Prompt.md`  
    Full prompt used to generate the SaaS funnel dataset.

  - `Prompt Explanation.md`  
    Explanation of the prompt logic and design decisions.

  - `generate_saas_funnel_dataset.py`  
    Python script used to generate the SaaS funnel dataset.

  - `saas_funnel_dataset.csv`  
    Generated synthetic SaaS funnel dataset.

- `02_SaaS_Retention_Cohort_Analysis/`  
  Folder for the SaaS retention and cohort analysis dataset.

  - `README.md`  
    Dataset-specific overview.

  - `Dataset Prompt.md`  
    Full prompt used to generate the SaaS retention dataset.

  - `Prompt Explanation.md`  
    Explanation of the prompt logic and design decisions.

  - `generate_saas_retention_dataset.py`  
    Python script used to generate the SaaS retention dataset.

  - `saas_retention_events_raw.csv`  
    Generated synthetic SaaS retention event dataset.
