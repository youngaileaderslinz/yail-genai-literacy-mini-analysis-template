# Data Dictionary

| Variable | Type | Meaning |
|---|---|---|
| `academic_level` | Categorical | Bachelor or Master/MBA or higher |
| `field_of_study` | Categorical | Business/management/law, Computer science/IT, or Other field |
| `institution_type` | Categorical | University or University of Applied Sciences |
| `genai_use_frequency` | Ordered categorical | Daily, Several times a week, or Weekly or less |
| `prior_genai_training` | Binary categorical | Whether the respondent reported prior GenAI-related training |
| `ai_attitude_mean` | Numeric, 1–7 | Mean score across six AI-attitude items; higher values indicate a more positive attitude |
| `digital_competence_mean` | Numeric, 0–4 | Mean score across six digital-competence items; some values are missing |
| `glat_score` | Integer, 0–20 | Total number of correct answers across the 20-item GenAI Literacy Assessment Test |
| `glat_know_understand` | Integer, 0–8 | Correct answers in the Know/Understand dimension |
| `glat_use_apply` | Integer, 0–3 | Correct answers in the Use/Apply dimension |
| `glat_evaluate_create` | Integer, 0–4 | Correct answers in the Evaluate/Create dimension |
| `glat_ethics` | Integer, 0–5 | Correct answers in the Ethics dimension |

The four GLAT dimension scores sum to `glat_score`.
