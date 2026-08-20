# Frequently Asked Questions

If your question is not answered here, email **office@youngaileaderslinz.at**.

## The data

**Where is the dataset? The `data/` folder is empty.**
That is intentional. The dataset is confidential and is never stored in this repository.
You receive a restricted download link in your invitation email. Save the file as
`data/genai_literacy_candidate_data.csv` — the templates assume that exact path.

**I did not receive a link, or the link does not work.**
Email **office@youngaileaderslinz.at** and we will sort it out. Do not ask another
candidate to send you their copy.

**Can I put the data in my own repository?**
Only if that repository is **private**, and it must stay private. Never commit it to a
public repository or a fork of this one. The `.gitignore` here already excludes
`data/*.csv` as a safety net, but the responsibility is yours.

**Can I share my analysis with a friend for feedback?**
No — not while the review is ongoing. Your analysis, figures, and findings are
confidential until we give explicit written permission. See [DATA_USE.md](DATA_USE.md).

## Tools and approach

**Do I have to use Python?**
No. Python is recommended because the templates are written for it, but R, Julia, or
anything else is fine. Whatever you use, submit your code and make sure someone else could
run it.

**Do I have to use the Jupyter notebook?**
No. `analysis.py`, an R script, or an `.Rmd` are all fine. The notebook is a convenience,
not a requirement.

**Can I use ChatGPT, Claude, Copilot, or similar?**
Yes, and it is not a disadvantage. Just fill in the AI-use note in `report.md`: which
tools, what for, and what you personally checked, changed, or decided. Do not paste raw
data rows into a public or shared AI session, and keep any conversation links private.

**Do I need inferential statistics — t-tests, regression, p-values?**
No. They are welcome if they fit your question, but a well-chosen descriptive analysis
with clear reasoning scores better than a test applied without justification.

**How advanced should the analysis be?**
Less advanced than you probably think. We are reading for your analytical choices, your
honesty about limitations, and how clearly you explain yourself — not for technique.

## The task

**How long should the report be?**
There is no word count. Most good submissions land around two to four pages of prose plus
figures. `report.md` should make sense on its own, without running the code.

**How many figures?**
Two to four in total, each with a clear title, readable labels, and one sentence on why
that chart suited the question.

**Do I have to take the survey first?**
No, it is optional. It takes about 15 minutes and usually makes the recommendations
section much easier to write, but skipping it carries no disadvantage. If you do take it,
your answers and score are never reviewed — do not include them in your submission.

**What if my results are inconclusive or boring?**
Report them as they are. An honest "the relationship I expected is not visible in this
sample, and here is why that might be" is a strong answer. A dressed-up result the data
does not support is not.

**Can I bring in outside data to enrich the analysis?**
No, please do not actually combine this dataset with external sources — see
[DATA_USE.md](DATA_USE.md). If a specific external dataset or source comes to mind that
you think could meaningfully enrich this kind of analysis, though, we would like to hear
about it — mention the idea in your report rather than acting on it.

## Submitting

**How do I submit?**
Complete the `submission/` folder, compress it into a single ZIP, and upload the ZIP in
the application form. Please do not fork this repository, open a pull request, share your
repository, or invite anyone to it.

**Do I include the CSV in my ZIP?**
No. We already have the data. Send only your report, code, and figures.

**When is it due?**
The deadline is stated in your invitation email.

**I cannot finish everything in time. What should I do?**
Submit what you have and say plainly what you left out and why. A partial submission with
an honest note is far better than a missed deadline or a rushed, overstated one. If
something came up, tell us before the deadline — we are reasonable.

**Roughly how long should this take?**
About four to six focused hours. If you find yourself well past that, you are likely going
deeper than we are asking for.

**What happens after I submit?**
The Software & Research team reviews submissions and follows up by email. If you are not
selected, delete your local copies of the dataset once the process concludes — see
[DATA_USE.md](DATA_USE.md).
