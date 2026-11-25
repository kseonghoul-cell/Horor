# Roadmap: Business & Systems Analyst (8 weeks)

> Source: TikTok video by [@bistro_v_it](https://www.tiktok.com/@bistro_v_it/video/7694544563930729750), titled “План на 2 месяца чтобы стать бизнес- и системным аналитиком с нуля”.
>
> This document turns the short video outline into a practical beginner plan. The video shows seven stages/weeks; week 8 below is an explicit completion stage added to make the advertised two-month timeline coherent.
>
> Scope: documentation only. This roadmap is stored on a separate branch and does not change the deployed prank page or the GitHub Pages workflow.

## Important distinction

The video's sequence (SQL, Excel, Python, Power BI, statistics, project, interview preparation) leans toward **data analytics**. A business analyst and a systems analyst also need skills that the video does not show:

- Business analysis: understand a business problem, identify stakeholders, map the current and desired process, define measurable outcomes.
- Systems analysis: turn needs into precise functional/non-functional requirements, describe data and integrations, define acceptance criteria, and support testing.
- Data analysis: query, clean, analyse and communicate data using SQL, spreadsheets, statistics and BI tools.

The plan therefore follows the video's subjects but adds requirements analysis, process modelling, data modelling and testing. Eight weeks is an intensive introduction and portfolio sprint, **not a guarantee of job readiness or employment**.

## Study rhythm

Target: 8–10 hours per week, adjustable to available time.

- 5 sessions of 60–75 minutes for learning and small exercises.
- 1 longer session of 2–3 hours for the weekly deliverable.
- Keep one document called **learning-log.md**: record what was learned, what was built, questions and blockers.
- Prefer free learning materials and free tools. Do not buy certificates or subscriptions for this roadmap.

## Eight-week plan

### Week 1 — SQL foundations

**Learn**
- What databases, tables, rows, columns and keys are.
- SELECT, WHERE, ORDER BY, LIMIT.
- COUNT, SUM, AVG, GROUP BY, HAVING.
- Basic data types, NULL and duplicate records.

**Practice**
- Write queries against a sample orders/customers/products dataset.
- Answer 10 plain-language business questions with SQL.

**Deliverable**
- A folder with 10 readable SQL queries and a short explanation of each result.

**Free starting point:** [SQLBolt](https://sqlbolt.com/).

### Week 2 — Excel / Google Sheets

**Learn**
- Clean and validate tabular data.
- Sort, filter, remove duplicates and handle missing values.
- Basic formulas: SUM, COUNTIF, SUMIF, IF, lookups.
- Pivot tables, charts and simple KPI calculations.

**Practice**
- Analyse a sample sales or order export.
- Calculate revenue, order count, average order value and category performance.

**Deliverable**
- A cleaned spreadsheet with a pivot table, 2–3 charts and a short findings note.

**Free option:** [Google Sheets training](https://support.google.com/a/users/answer/9282959).

### Week 3 — Python basics for analysis

**Learn**
- Variables, strings, numbers, lists, dictionaries and conditions.
- Loops and functions.
- Read and write CSV files.
- Basic error reading and debugging.

**Practice**
- Load a small CSV, inspect rows, calculate totals and identify invalid records.
- Reproduce one simple spreadsheet calculation in Python.

**Deliverable**
- One commented Python script or notebook that reads a CSV and produces a small summary.

**Free starting point:** [Official Python tutorial](https://docs.python.org/3/tutorial/).

Python is useful, but do not let it displace SQL, requirements analysis or process modelling if the target is a business/systems analyst role.

### Week 4 — Power BI and communicating metrics

**Learn**
- Why dashboards exist; dimensions vs measures.
- Importing and cleaning data.
- Relationships between tables.
- Basic measures and visual selection.
- KPI definitions, filters and avoiding misleading charts.

**Practice**
- Build a one-page dashboard from the dataset used in weeks 1–2.
- Write down the definition and calculation for every KPI.

**Deliverable**
- A dashboard plus a one-page metric dictionary and three evidence-based observations.

**Free starting point:** [Microsoft Learn — Power BI](https://learn.microsoft.com/en-us/training/powerplatform/power-bi/).

Note: Power BI Desktop is a Windows desktop application. If a Windows computer is not available, postpone Desktop practice rather than paying for a workaround; keep practising the data and dashboard concepts with a free browser-based tool.

### Week 5 — Statistics and analytical reasoning

**Learn**
- Mean, median, mode, range and percent change.
- Percentages, rates and proportions.
- Variance and standard deviation at an intuitive level.
- Correlation vs causation.
- Sampling, bias and the limits of small datasets.
- Basic hypothesis-testing concepts; focus on interpretation, not memorising formulas.

**Practice**
- Compare two periods or two product categories.
- Explain what the data supports and what cannot be concluded.

**Deliverable**
- A short analysis note with 5 findings, supporting calculations and explicit limitations.

### Week 6 — Business and systems analysis fundamentals

**Learn**
- Stakeholders, business goals, scope and constraints.
- As-is / to-be process mapping.
- Functional vs non-functional requirements.
- User stories and acceptance criteria.
- Use cases, basic BPMN flowcharts and simple ER diagrams.
- Prioritisation and traceability.

**Practice**
Use a fictional small online shop as a case study:
1. Describe the current order-to-delivery process.
2. Identify 3 pain points and their business impact.
3. Propose a target process.
4. Write 8–12 clear requirements and acceptance criteria.
5. Draw a simple process diagram and a basic data model.

**Deliverable**
- A compact requirements pack: problem statement, scope, stakeholders, as-is/to-be diagrams, requirements, user stories and acceptance criteria.

**Free diagramming tool:** [diagrams.net](https://www.diagrams.net/).

### Week 7 — End-to-end portfolio project

**Build one coherent case study** using the fictional online shop dataset and process from previous weeks.

Include:
- Business problem and measurable objective.
- Process diagram and requirements.
- Data model / table descriptions.
- SQL queries that answer business questions.
- Spreadsheet analysis and, if available, a BI dashboard.
- Test scenarios and expected results.
- A concise recommendation supported by evidence.

**Deliverable**
- One portfolio project folder with a clear README, diagrams, queries, analysis and test cases.
- Clearly label fictional or synthetic data; do not present it as real client work.

### Week 8 — CV, interview preparation and next steps

**Prepare**
- A one-page CV focused on demonstrated skills and the portfolio project.
- A short explanation of the project: problem → analysis → proposed solution → validation → result/limitations.
- Practice questions on SQL, spreadsheets, requirements, process diagrams, metrics and basic statistics.
- 5 mock interview answers using concrete examples from the project.
- Review 10 real junior vacancies and record repeated requirements.

**Deliverable**
- CV draft, portfolio README, interview question log and a vacancy skills-gap table.

Do not claim professional experience or business results that did not happen. Describe the portfolio project honestly as a self-directed case study.

## Completion criteria

At the end of the eight weeks, the learner should be able to demonstrate:

- Write basic SQL queries, including grouping and simple joins.
- Clean and summarise tabular data in a spreadsheet.
- Explain basic Python code and process a CSV.
- Explain and build a simple KPI dashboard (Power BI practice depends on access to Windows).
- Interpret basic descriptive statistics without overstating conclusions.
- Map a business process and write testable requirements and acceptance criteria.
- Present one coherent portfolio case study and explain the decisions made.

If these criteria are not met, extend the relevant week. Finishing the calendar is less important than being able to demonstrate the skills.

## Suggested priority for a first analyst role

1. SQL + spreadsheets.
2. Requirements, process mapping and clear written communication.
3. One BI tool.
4. Basic statistics.
5. Python as an additional capability.

The exact balance depends on the vacancy: data/BI analyst roles usually need more querying and dashboard work; business analyst roles emphasise requirements and stakeholder/process work; systems analyst roles add more detail around data models, integrations, system behaviour and testing.

## Source and limitations

- TikTok source video: [@bistro_v_it — two-month analyst roadmap](https://www.tiktok.com/@bistro_v_it/video/7694544563930729750).
- The video is approximately 10 seconds and provides only a high-level sequence. It does not teach the topics, specify study hours, establish a detailed eighth week, or demonstrate that completing the plan guarantees employment.
- The expanded sequence and deliverables in this document are a proposed study plan, not claims made by the creator.
- Role titles vary between employers. Always compare the actual responsibilities in job descriptions rather than relying on the title alone.
