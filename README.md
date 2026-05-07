# cognitive_offloading_cogsci

# official repository for the cogsci paper "Cognitive offloading and the speedup illusion in human-AI interaction" (2026)

**Sunny Yu, Myra Cheng, Ahmad Jabbar, Ilia Sucholutsky, Katherine M. Collins, Dan Jurafsky, Robert D. Hawkins**

Presented at the 48th Annual Meeting of the Cognitive Science Society (2026; Brazil).

[Link to experiment (prediction sample)](https://stanforduniversity.qualtrics.com/jfe/form/SV_bmfJCc51HLv9EJ8)
[Link to experiment (completion sample)](https://stanforduniversity.qualtrics.com/jfe/form/SV_bkdLHgFHblApVn8)

```
@inproceedings{yu2026cognitiveoffloading,
  title = {Cognitive offloading and the speedup illusion in human-AI interaction},
  booktitle = {Proceedings of the 48th {Annual} {Conference} of the {Cognitive} {Science} {Society}},
  author = {Yu, Sunny and Cheng, Myra and Jabbar, Ahmad and Sucholutsky, Ilia and Collins, Katherine and Jurafsky, Dan and Hawkins, Robert},
  year = {2026},
}
```

**Contents:**

- [Overview](#overview)
- [Repository structure](#repository-structure)
- [CRediT author statement](#credit-author-statement)

## Overview

Large language models (LLMs) have the potential to boost human productivity by speeding up task completion---provided users know when to offload cognitive work to them. But we do not know if users are well-calibrated in estimating these potential time savings. We conducted a preregistered large-scale behavioral study (N = 1237) to characterize mismatches between expectations and reality, with a focus on simple cognitive tasks. While actual completion times between independent completion and AI-assisted completion did not differ, participants predicted AI to be significantly faster. The same bias was not observed when imagining help from another human participant. We identify a speedup illusion where people have accurate forecasts of independent completion times but significantly underestimate AI-assisted times. Additionally, time and effort dissociate: participants reported lower subjective effort with AI despite equivalent completion times. This suggests that completion time itself is not sufficient to characterize efficiency gains.

## Repository structure

```
project_root/
├── data/
│   ├── prediction_sample.csv
│   ├── completion_sample1.csv
│ study1_analysis_cogsci.Rmd
├── figures/

```

- `/data`: raw data used (with demographic data removed -- please contact us directly if you are interested in using the full data)
  - `prediction_sample.csv`: the csv file for the prediction sample data (N=401).
  - `completion_sample1.csv`: the csv file for the completion sample data (N=836). The data includes annotations for the correctness of each response.
- `study1_analysis_cogsci.Rmd`: analysis code used for the study, including preprocessing, main analysis, exploratory analysis, and plotting code.

## Set up

R should be installed and added to the PATH.

## CRediT author statement

_What is a [CRediT author statement](https://www.elsevier.com/authors/policies-and-guidelines/credit-author-statement)?_

- **Sunny Yu:** Conceptualization, Methodology, Software, Validation, Formal analysis, Investigation, Data Curation, Writing - Original Draft, Writing - Review & Editing, Visualization, Supervision, Project administration
- **Myra Cheng:** Conceptualization, Methodology, Investigation, Writing - Original Draft, Writing - Review & Editing, Supervision, Project administration
- **Ahmad Jabbar:** Conceptualization, Methodology, Investigation, Writing - Review & Editing, Supervision, Project administration
- **Ilia Sucholutsky:** Conceptualization, Writing - Review & Editing, Supervision, Project administration
- **Katherine Collins:** Conceptualization, Writing - Review & Editing, Supervision, Project administration
- **Dan Jurafsky:** Conceptualization, Writing - Review & Editing, Supervision, Project administration
- **Robert Hawkins:** Conceptualization, Methodology, Resources, Writing - Review & Editing, Supervision, Project administration
