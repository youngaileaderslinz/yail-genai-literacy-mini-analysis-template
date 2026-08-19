# Candidate Dataset

**The dataset is intentionally not included in this repository.**

You receive a restricted download link in your invitation email. Save the file here, at the exact path:

```text
data/genai_literacy_candidate_data.csv
```

The templates in `submission/` assume that path. The repository `.gitignore` excludes `data/*.csv`, so the file will not be committed by accident — but it remains your responsibility never to commit, upload, or share it.

## About the file

- Unit of observation: one survey response
- Rows: 218
- Missing values are preserved intentionally
- Internal survey identifiers are removed
- Individual demographic variables, exact age, and exact weekly working hours are excluded
- Rare categories are combined to reduce disclosure risk
- Individual questionnaire-item responses are excluded to keep the task focused

See [data_dictionary.md](data_dictionary.md) for variable definitions, and [../DATA_USE.md](../DATA_USE.md) for the conditions under which this data may be used.
