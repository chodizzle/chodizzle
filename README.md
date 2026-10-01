# John Cho

Data analyst who ships production LLM systems. SQL and Python, with a
statistics foundation (MITx MicroMasters in Statistics and Data Science).
Came up through restaurant operations, then AP and invoice data.

I build things that make messy document data usable, and I write about
where automated systems quietly get it wrong.

### Writing

**[What it cost to put 15 restaurants on real food costing](https://chodizzle.github.io/avt-implementation/)**
A line-item breakdown of a 2017 actual-vs-theoretical implementation,
scored against which lines an AI agent removes today. The two failure
exhibits are about clean text, high confidence, and a wrong number.

### Projects

**[Recipe Flowchart](https://chodizzle.github.io/recipe_flowchart/)** — Dependency
graphs from unstructured recipe text across 6 models and 3 providers, with a
taxonomy-driven eval loop for a task that has no single right answer. Prompt
iteration cut ordering errors 19 to 3; a tested LLM judge was dropped at 0.28 recall.

**[The Peeking Problem](https://chodizzle.github.io/ab-test-peeking-problem/)** — Power
analysis and Monte Carlo on a 90K-user A/B test. Daily peeking with early stopping
inflates the false-positive rate from 5% to ~22%; a Pocock boundary corrects it.

**[Invoice Volume Forecast](https://github.com/chodizzle/invoice-volume-forecast)** — Prophet
model forecasting daily document intake 60 days out, with tuned weekly, quarterly,
and holiday seasonality.

**[Price Tracker](https://github.com/chodizzle/price-tracker)** — Normalizing two
federal data sources with different shapes and reporting cadences onto one weekly grid.

---
[LinkedIn](https://www.linkedin.com/in/john-cho-data) · crunchycho@gmail.com
