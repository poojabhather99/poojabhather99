# Hi, I'm Pooja Bhather

Data engineer at Khushi Baby, building data pipelines, analytics and GenAI / agentic AI systems. B.Tech in CSE, currently pursuing M.Tech in Generative AI at IIT Jammu.

## What I do

I turn messy operational data into reliable analytical datasets and KPIs for program teams, and I build LLM-powered applications on top of Python, FastAPI, Docker and PostgreSQL.

## Tech stack

**Languages:** Python, SQL, JavaScript, Java

**Backend and data:** FastAPI, PostgreSQL, Docker, data pipelines (ETL / CDC), analytics dashboards

**GenAI:** LLM APIs, RAG, Streamlit, agent workflows

**Practices:** unit testing with pytest, CI with GitHub Actions, containerised deployment

## Flagship project

**[insight-agent](https://github.com/poojabhather99/insight-agent)**: a deployable data analyst agent. Upload a CSV, ask in plain English, and it runs sandboxed read-only SQL (single SELECT, read-only database, no file access, time limit), draws a chart and shows every step. FastAPI backend, web UI with live step streaming, API-key auth, rate limiting, JSON logs, Prometheus metrics, SQLite run history, Docker and CI with an evaluation gate. 86 tests. Works offline and with Groq or Hugging Face models; not yet evaluated with a live model.

## Featured projects

**[bot-gpt](https://github.com/poojabhather99/bot-gpt)**: conversational AI platform with general chat and document-grounded RAG over PDFs. FastAPI, Groq LLaMA 3.3, Streamlit, Docker, CI.

**[Workhour-prediction](https://github.com/poojabhather99/Workhour-prediction)**: ML model that predicts project effort, served through a web app.

**[aimouse](https://github.com/poojabhather99/aimouse)**: computer-vision hand tracking to control the mouse.

**[agent-eval-lab](https://github.com/poojabhather99/agent-eval-lab)**: tool-using LLM agent (ReAct loop) with an evaluation harness measuring success rate, tool-selection accuracy, steps and invalid-JSON rate. Baseline and real-model (Groq) backends, 14 tests, CI. [Live demo](https://poojabhather99.github.io/agent-eval-lab/)

**[cdc-quality-pipeline](https://github.com/poojabhather99/cdc-quality-pipeline)**: CDC ingestion demo with validation, quarantine, duplicate and out-of-order handling, silver and gold KPI layers (DuckDB), and a reconciliation check proving no event is lost. 20 tests, CI. [Live demo](https://poojabhather99.github.io/cdc-quality-pipeline/)

**[mcp-kpi-server](https://github.com/poojabhather99/mcp-kpi-server)**: Model Context Protocol server giving any LLM client safe, read-only SQL and KPI tools over DuckDB, with a SQL guard and 19 tests. [Live demo](https://poojabhather99.github.io/mcp-kpi-server/)

**[data-quality-agent](https://github.com/poojabhather99/data-quality-agent)**: agent that profiles a table and proposes validation rules as JSON specs that are schema-checked before they run, never executable code. 20 tests, CI. [Live demo](https://poojabhather99.github.io/data-quality-agent/)

**[rag-eval-harness](https://github.com/poojabhather99/rag-eval-harness)**: offline harness that measures a RAG pipeline on retrieval hit rate and MRR, answer accuracy, faithfulness to cited sources, and abstention on unanswerable questions. 12 tests, CI. [Live demo](https://poojabhather99.github.io/rag-eval-harness/)

**[multi-agent-workflow](https://github.com/poojabhather99/multi-agent-workflow)**: planner, researcher and critic agents with schema-validated plans, a safe calculator tool, an event trace and a retry loop that catches injected faults. 31 tests, CI. [Live demo](https://poojabhather99.github.io/multi-agent-workflow/)

**[ai-interviewer](https://github.com/poojabhather99/ai-interviewer)**: FastAPI service that runs an adaptive technical interview, with SQLite-backed sessions, resumes referenced by id instead of file path, prompt-injection mitigation, a transparent scoring rubric and reports. 11 tests, CI. [Live demo](https://poojabhather99.github.io/ai-interviewer/)

**[meal-nutrition-agent](https://github.com/poojabhather99/meal-nutrition-agent)**: protein-aware weekly meal planner that learns a profile from free text, plans seasonal meals for veg, egg and non-veg diets, and sends day-ahead reminders through a bot-ready command router. 21 tests, CI. [Live demo](https://poojabhather99.github.io/meal-nutrition-agent/)

## Live demos

Every demo below runs the real project code in your browser (Python via Pyodide), with no sign-up and no server:

[Agent eval lab](https://poojabhather99.github.io/agent-eval-lab/) | [CDC quality pipeline](https://poojabhather99.github.io/cdc-quality-pipeline/) | [MCP KPI server tools](https://poojabhather99.github.io/mcp-kpi-server/) | [Data quality agent](https://poojabhather99.github.io/data-quality-agent/) | [RAG evaluation harness](https://poojabhather99.github.io/rag-eval-harness/) | [Multi-agent workflow](https://poojabhather99.github.io/multi-agent-workflow/) | [AI interviewer](https://poojabhather99.github.io/ai-interviewer/) | [Meal planning bot](https://poojabhather99.github.io/meal-nutrition-agent/)
