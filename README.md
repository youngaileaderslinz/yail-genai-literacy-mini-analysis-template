# YAIL GenAI Literacy — Mini Data Exploration

A short, practical data-exploration task for people interested in joining the Young AI Leaders Software & Research team.

## About

This repository is the assignment template for a mini data exploration built around a real Generative AI literacy survey. You will work with a privacy-reduced extract of the study data, explore two questions of your own framing, and write up what you found.

This is **not a formal hiring test**. We want to understand how you approach a real dataset, make analytical choices, communicate findings, and reflect on survey design. There is no single correct analysis, and we are not looking for the most advanced statistical method — clear reasoning beats clever technique.

## Repository structure

```text
.
├── README.md                 # This guide: task, expectations, submission process
├── DATA_USE.md               # Data-use agreement — read before you begin
├── FAQ.md                    # Common questions from candidates
├── SECURITY.md               # How to report an accidental data exposure
├── CODE_OF_CONDUCT.md        # How we expect people to treat each other
├── CONTRIBUTING.md           # What this repository is and is not
├── LICENSE.md                # Copyright and permitted reuse
├── requirements.txt          # Python packages used by the notebook template
├── data/
│   ├── README.md             # Notes on the dataset and where to place it
│   └── data_dictionary.md    # Variable definitions
└── submission/
    ├── analysis.ipynb        # Analysis template (or write analysis.py instead)
    ├── report.md             # Report template — the main written deliverable
    └── figures/              # Save your charts here
```

Stuck on something? Check the [FAQ](FAQ.md) first.

## The dataset

The data comes from a Generative AI literacy survey conducted with higher-education students. Respondents completed a 20-item Generative AI Literacy Assessment Test (GLAT) together with questions about their background, experience with GenAI, attitudes toward AI, and digital competence.

The candidate dataset is a privacy-reduced selection of variables from **218 responses**. Direct identifiers were never collected. The internal survey ID, individual demographic variables, exact age and working hours, detailed rare categories, and item-level answers have all been removed for this exercise.

> [!IMPORTANT]
> **The data file is not in this repository.** You receive a restricted download link in your invitation email. Save the file as `data/genai_literacy_candidate_data.csv` — the templates assume that exact path. The `.gitignore` in this repository excludes it, and it must never be committed, uploaded, or shared anywhere public.

See [data/data_dictionary.md](data/data_dictionary.md) for variable definitions, and read [DATA_USE.md](DATA_USE.md) before you begin.

## Before you start (optional, recommended)

Before opening the dataset, we recommend completing the [GenAI Literacy Survey](https://www.soscisurvey.de/gen-ai-literacy/) from a participant's perspective. It takes about 15 minutes and helps you understand the questions, concepts, structure, and participant experience behind the data.

Participation is voluntary. Whether you complete it, what you answer, and the score you receive are **not** part of our review. Do not include your personal answers or final GLAT score in your submission.

If you complete it, record brief notes on:

- One element that was clear or worked well
- One question, term, or response option that could be clearer
- One observation about the survey's length, flow, or level of difficulty

If you prefer not to take the survey, begin with the dataset directly — this carries no disadvantage.

## Your task

### Part 1 — Understand the data

Load `data/genai_literacy_candidate_data.csv` and briefly document:

- Number of rows and columns
- Variable types
- Missing values and any other data-quality observations
- Any transformation you perform, and why

Do not automatically remove or impute missing values. First investigate where they occur, then explain your choice.

### Part 2 — Explore two questions

Answer both of the following:

1. **What does the distribution of GLAT scores suggest about this sample?**
2. **Choose one factor that may be associated with GLAT score** and explore the relationship. You might consider prior GenAI training, frequency of GenAI use, field of study, academic level, institution type, AI attitude, or digital competence.

Use descriptive analysis that fits the variables. Inferential statistics are welcome but **not required**.

Create **2–4 useful visualizations** in total. Each should have a clear title, readable labels, and one sentence explaining why that chart was suitable.

### Part 3 — Findings and recommendations

Summarize:

- **Two to three findings** supported by your analysis
- **One to two limitations** that affect how the findings should be interpreted
- **Two to three concrete recommendations** for the next version of the survey

For each recommendation, state whether it is based on:

- Your experience completing or reviewing the survey
- Evidence visible in the dataset
- Both

Recommendations may address question wording, response options, survey flow, sampling, missing data, or future analysis.

## Effort and deadline

- Approximately **4–6 focused hours**
- The submission deadline is stated in your invitation email
- Python is recommended, but thoughtful reasoning matters more than advanced code

## Use of AI tools

You may use tools such as ChatGPT, Claude, Gemini, GitHub Copilot, or similar assistants. Using them is not a disadvantage.

Briefly state in your report:

- Which tools you used
- What you used them for
- What you personally checked, changed, or decided

Using AI does not change your confidentiality obligations. Raw data rows must not be pasted into public or shared AI sessions, and any conversation link containing project data or findings stays private. See [DATA_USE.md](DATA_USE.md).

## How to submit

1. **Complete the `submission/` folder** — `report.md`, `analysis.ipynb` (or `analysis.py`), and your charts in `figures/`. The provided files are templates; replace the prompts with your own work. The notebook format is a suggestion, not a requirement.
2. **Verify the pre-submission checklist:**
   - Your analysis runs from beginning to end
   - File paths are relative rather than specific to your computer
   - Your figures are saved in `submission/figures/` and referenced from `report.md` with relative paths
   - `report.md` reads and makes sense on its own, without running the code
   - Your claims match the analysis you performed
   - You have completed the AI-use note in `report.md`
3. **Compress the `submission/` folder** into a single ZIP archive.
4. **Upload the ZIP** in the application form.

Please do not fork this repository, share it, or invite anyone to it. Working in your own **private** repository is fine — it stays private.

## Data use and confidentiality

The dataset is confidential research data provided solely for completing this assignment. It may not be published, redistributed, or shared in any form, and no attempt may be made to identify respondents. Your analysis, findings, and figures likewise remain confidential until YAIL gives explicit written permission to share them.

The full terms are in **[DATA_USE.md](DATA_USE.md)** — please read it before you begin.

If the data is ever exposed by accident — a public push, a shared link, a lost device —
tell us immediately. [SECURITY.md](SECURITY.md) explains how. Reporting quickly is treated
as responsible handling, not as a failure.

## About Young AI Leaders Linz

Young AI Leaders is a community hub in Austria building practical AI capability through hands-on projects, events, and collaboration. The Software & Research team works data-first on real projects, applied research, and publications — turning survey and product data into evidence people can act on.

We expect everyone involved with this repository to follow our [Code of Conduct](CODE_OF_CONDUCT.md). The materials here are © Young AI Leaders Linz — see [LICENSE.md](LICENSE.md).

Questions about this task: **office@youngaileaderslinz.at**
