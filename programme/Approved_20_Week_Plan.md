---
title: Approved 20-Week Plan - Ahamed Basha J
status: APPROVED by the Principal Mentor on 2026-11-23
principal_mentor: Srinivasan Gurukannan
programme_start: 2026-11-23 is week 1, day 1 (the 20-week clock restarts on this day)
audience: Ahamed Basha J (the learner) and the Principal Mentor
---
# Approved 20-Week Plan - Ahamed Basha J
**How to read this document.** It is written plainly so the learner can read it. The Principal Mentor approved the plan on 2026-11-23. Progression through the programme is decided only by the mentor. Items still undecided are collected in section 9 and marked **[OPEN]**. Nothing marked open is a decision.
**Governs:** the Programme Objective document (mentor wording). **Principle:** AI-augmented, human-owned engineering.
**Start and calendar.** The 20-week clock restarts on 2026-11-23, which is week 1, day 1. The mentor sets which calendar date each later learning day falls on. This plan gives no other calendar dates.
## 1. What the plan is
The ten-module order is unchanged: programming, maths and statistics, data engineering, ML fundamentals, classical ML, advanced ML, deep learning, GenAI/LLM, application and MLOps, capstone. Each module takes two weeks. The plan has these features.
- **Size.** 5 learning days a week, 4 hours a day, 100 days, about 400 hours.
- **Target.** A corporate AI/ML engineer role. The capstone is one corporate-style project, a retail sales intelligence platform for a fictional company. It starts in week 1 from the sales project and grows every week. Weeks 19-20 are final integration, hardening and a corporate-style demonstration.
- **Hands-on every day.** Each day ends with working code committed to Git.
- **Early testing and cloud.** Testing, Git and CI start in week 2. Cloud basics start in week 3 on Microsoft Azure. Both are practised again in weeks 5, 6, 9, 10, 17 and 18.
- **Job-readiness track** from week 1, about 68 hours in total, with a "ready to apply" gate (section 7).
- **12 competencies** (section 3).
- **Azure certifications** as extra credentials. They never replace the weekly live no-AI checks (section 8).
- **Restart.** Week 1 is a redo of the earlier Days 1-4 material with new training material, followed by the first live no-AI check on Day 5.
## 2. Time and day pattern
| Item | Value |
|---|---|
| Duration | 20 weeks |
| Week | 5 learning days. A "week" here means 5 learning days, not a calendar week. |
| Day | 4 hours: 60 min concepts, 45 min guided example, 90 min independent implementation, 45 min testing, reflection and evidence |
| Total | 100 days, about 400 hours |
| Job-readiness time (approved) | about 2.5 h/week in weeks 1-8, 3 h in weeks 9-16, 6 h in weeks 17-20: 68 h in total (17%), so about 332 h are technical |
| Start | 2026-11-23 is week 1, day 1. Week 1 holds learning days 1-5, week 2 holds days 6-10, and so on. The mentor maps learning days to dates. |

**Standard week (weeks 2-18).**
| Day | Content | Hands-on output |
|---|---|---|
| 1 | New topic A: concepts, guided example, independent lab | Lab committed with a short written "understand" note before any AI use |
| 2 | New topic B: same pattern | Lab committed |
| 3 | Topic C, plus design of this week's capstone increment (acceptance criteria and tests first) | Design note and failing tests |
| 4 | Capstone build day: implement the increment | Working increment, tests passing, README and AI ledger updated |
| 5 | Assessment day: live no-AI check (about 90 min), evidence pack and mentor hand-off (about 60 min), job-readiness block (about 90 min) | Evidence pack; check result recorded as Pass / Partial / Not demonstrated per Understand-Implement-Defend-Transfer stage |

Weeks 1, 19 and 20 differ (see section 6). Every week, coding practice uses two or three 30-minute slots inside Days 1-4.
**Live no-AI check (every week):** the learner explains the week's code, predicts outputs, fixes a defect the mentor or coach introduces, applies one changed requirement, and solves one small related new task. AI is switched off. The mentor or coach can vary the format.
## 3. The 12 competencies
| # | Competency | Source |
|---|---|---|
| C1 | Business understanding | Programme Objective, section 3 |
| C2 | Programming and software engineering | Programme Objective, section 3 |
| C3 | Data engineering | Programme Objective, section 3 |
| C4 | Mathematics and statistics | Programme Objective, section 3 |
| C5 | Machine Learning engineering | Programme Objective, section 3 |
| C6 | Deep Learning and AI | Programme Objective, section 3 |
| C7 | Generative AI engineering | Programme Objective, section 3 |
| C8 | Application and cloud engineering | Programme Objective, section 3 |
| C9 | Quality and operational engineering | Programme Objective, section 3 |
| C10 | Client delivery and independence (in the corporate setting, the "client" is an internal business stakeholder) | Programme Objective, section 3 |
| C11 | Responsible AI and data governance (sits beside C9) | Added for corporate readiness |
| C12 | Cost awareness and working with other roles | Added for corporate readiness |

## 4. Capstone thread
**Capstone: Retail Sales Intelligence Platform** for a fictional retailer, built only on synthetic data. A fictional business manager is the stakeholder (the mentor or coach plays the role). The week 1 sales project becomes version 0.1. The platform grows into: validated data pipeline, SQL store, statistics and A/B analysis, repeat-purchase prediction, demand forecasting, customer segments and anomaly flags, feedback text classification, a document question-answering assistant, a deployed API, and monitoring. The mentor can change the scope. The exact brief and datasets are supplied by the mentor (section 10).
## 5. Azure hands-on work: rules
The cloud provider is Microsoft Azure. The learner may create his own Azure subscription for learning and use it for all hands-on Azure work in this plan. Resources in his own subscription do not need separate approval from the mentor. These rules apply to every step marked **[Azure]**:
1. **He owns and pays for any cost** in his subscription.
2. **He sets a budget alert before creating any resource.** Microsoft Cost Management budgets can send alerts on actual or forecast cost. Microsoft's documentation says a budget sends notifications when a threshold is exceeded and does not stop resources or spending, so he must also stop or remove resources he no longer needs. Microsoft's documentation also says that on a new subscription, budgets and other Cost Management features can take up to 48 hours to become available. Until the budget alert exists, he creates no billable resources. ([Microsoft: create and manage budgets](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/tutorial-acm-create-budgets))
3. **No client or personal data** in the subscription. Synthetic data only.
4. **No secrets in GitHub or in any shared or synced folder** (for example a cloud drive). Secrets are kept in a secrets store such as Azure Key Vault or in environment variables that are not committed.
5. **He never shares his account credentials with the mentor.** If the mentor or coach needs to see something, the learner shows it on screen or exports evidence that contains no secrets.

Free-tier terms, student offers and prices change. This plan states none. The learner reads the current terms on Microsoft's own pages before creating the subscription.
The Azure services named in this plan were each checked on learn.microsoft.com (section 12).
## 6. Week-by-week table
Tags: **[Azure]** Azure hands-on work (rules in section 5 apply), **[Test]** testing, Git or CI. "Labs" are the small daily exercises. "Cap" is the week's capstone increment.
| Wk | Module and focus | Hands-on: labs and capstone increment | Evidence at end of week (live no-AI check included) | Competencies |
|---|---|---|---|---|
| 1 | M1 Programming. **Restart week.** Days 1-4: redo the Day 1 to Day 4 material with the new training material (Python, VS Code workflow, terminal, Git basics, and the sales project). Day 5: live no-AI check, evidence pack and mentor hand-off. | Labs: redo the Day 1-2 exercises. Cap v0.1: the retail sales project in VS Code (`src/`, `data/`, `output/`), redone with the new material. | `python src/main.py` runs from a clean clone; metrics match the mentor-confirmed expected values; test log; README; AI ledger. Live check (Day 5, the first one): explain the data flow, predict the output for a changed CSV, add one validation rule. | C2, C3, C1 |
| 2 | M1. Functions, errors, files, modules, venv. **[Test]** pytest, Git branches and pull requests, first CI run. | Labs: refactor exercises with tests. Cap v0.2: package layout, config, logging, automated tests for the nine sales-project cases, CI green. | Tests and CI link. Live check: fix an injected bug and write one new test; solve a small new file-processing task. **Gate M1.** | C2, C9, C3 |
| 3 | M2 Maths and stats 1. Descriptive stats, probability, distributions (NumPy, pandas). **[Azure]** Account and cost basics: create his own Azure subscription, set the budget alert, learn subscriptions, resource groups, access control (Microsoft Entra ID and Azure RBAC) and the cost-management basics. AZ-900 study starts. | Labs: stats from first principles. Cap: stats module over the sales data, tested against hand calculation; a one-page Azure and cost sketch of where the platform will run. No billable resource is created until the budget alert exists. | Tests pass; hand-calculation sheet; cost sketch; screenshot of the budget alert with no personal details. Live check: compute mean, variance and a probability by hand and in code. | C4, C2, C8, C12 |
| 4 | M2. Sampling, confidence intervals, hypothesis tests, correlation, vectors and matrices, gradient descent. | Labs: gradient descent and linear regression in NumPy. Cap: promotion A/B analysis written as a business memo to the stakeholder. | Memo; regression matches a reference library within a stated tolerance. Live check: choose and justify a test for a new scenario; do one gradient step by hand. **Gate M2.** | C4, C1, C5, C12 |
| 5 | M3 Data engineering 1. SQL (joins, windows, CTEs), schema design, pandas cleaning. **[Azure]** Azure Blob Storage (object storage) and Azure SQL Database basics. | Labs: SQL drills on a given schema. Cap: transactions loaded into a relational database (local, and optionally in Azure SQL Database); ten business queries with checked expected results. | Query results verified against independent calculation. Live check: write three SQL queries on an unseen schema. | C3, C9, C8 |
| 6 | M3. APIs, ETL scripts, logging, data-quality checks, Docker intro. **[Test]** data tests in CI. Data handling rules. | Labs: API ingestion, container build. Cap: containerised ETL pipeline with data-quality tests, a data dictionary and a note on data handling and personal data (synthetic only). | A clean-clone `docker run` reproduces the outputs; CI green. Live check: add a new quality rule and a new column; explain failure behaviour. **Gate M3.** | C3, C8, C9, C11 |
| 7 | M4 ML fundamentals 1. Lifecycle, problem framing, baselines, splits, leakage, metrics (scikit-learn). | Labs: baseline models on practice datasets. Cap: repeat-purchase prediction, framing note and baseline with a reproducible split. | Split test; baseline versus model table. Live check: find leakage in a given snippet; justify the metric. | C5, C1, C2 |
| 8 | M4. Cross-validation, pipelines, over/underfitting, feature basics. | Labs: pipelines and CV. Cap: end-to-end repeat-purchase pipeline with requirements note and a saved model that reloads and predicts the same. | Reload test; CV results. Live check: change the business constraint (metric or threshold) and re-evaluate; repeat the workflow on a new dataset. **Gate M4.** | C5, C1, C2 |
| 9 | M5 Classical ML 1. Regression, regularisation, trees, ensembles, tuning. **[Azure]** One training run on Azure Machine Learning, with the budget alert in place. | Labs: model comparison drills. Cap: product demand regression with tuning and error analysis; one Azure Machine Learning run, with the cost read from Microsoft Cost Management and noted. | Comparison table on CV; run log and cost note. Live check: explain why one model beat another; predict the effect of a hyperparameter change. | C5, C8, C12 |
| 10 | M5. Classification, thresholds, gradient boosting, experiment tracking, serving. **[Test]** API tests. | Labs: threshold and calibration drills. Cap: tuned repeat-purchase classifier behind a `/predict` API with tests and an experiment log. | Tests green in CI. Live check: change the threshold to meet a precision target; add one input validation rule. **Gate M5.** | C5, C8, C9 |
| 11 | M6 Advanced ML 1. Clustering, dimensionality reduction, anomaly detection. | Labs: clustering drills. Cap: customer segments and transaction anomaly flags, with business descriptions of each segment. | Segment stability check; named segments. Live check: justify the number of clusters; rerun after a changed feature. | C5, C1, C3 |
| 12 | M6. Time series, imbalanced data, explainability, error analysis. Bias and privacy review. | Labs: forecasting and SHAP-style or permutation importance drills. Cap: demand forecast with time-based validation; explanation report for a non-technical reader; bias and privacy checklist. | Time-split test (no leakage); report. Live check: explain one prediction; spot a leak in a time-split snippet. **Gate M6.** | C5, C9, C1, C11 |
| 13 | M7 Deep learning 1. Neural networks, backpropagation, PyTorch basics, training loops. | Labs: NumPy network with gradient check. Cap: neural model on the repeat-purchase data, compared honestly with the best classical model. | Gradient check passes; curves; comparison. Live check: predict tensor shapes; read training curves; change learning rate and explain the effect. | C6, C4, C5 |
| 14 | M7. Transfer learning, text models, training hygiene. | Labs: pretrained model fine-tuning drills. Cap: customer-feedback text classifier added to the platform, with a model card. | Evaluation and error analysis; model card. Live check: diagnose a failing training run; reproduce one evaluation. **Gate M7.** | C6, C5, C9 |
| 15 | M8 GenAI 1. LLM APIs, prompting, structured output, embeddings, vector search, secrets and token cost. **[Azure]** Model access through an Azure service named in the training material (for example Microsoft Foundry); any paid model use is at his own cost and inside his budget alert. | Labs: prompt and parser drills. Cap: semantic search over product and policy documents, with mocked-LLM tests (the tests make no paid calls) and a cost log. | Tests; cost log; no keys in the repository. Live check: write a prompt and parser for a new extraction task. | C7, C9, C12, C11 |
| 16 | M8. RAG, evaluation, tool use and agents, guardrails. | Labs: retrieval tuning. Cap: store-staff question-answering assistant with an evaluation set the learner writes, and guardrails. | Evaluation results with failures analysed. Live check: debug a retrieval failure; change chunking and predict the effect; explain prompt-injection risk. **Gate M8.** | C7, C8, C9, C11 |
| 17 | M9 Application and MLOps 1. Service hardening, Docker, CI/CD, config and secrets. **[Azure]** Deploy the service to Azure Container Apps, with the image in Azure Container Registry and secrets in Azure Key Vault. | Labs: pipeline stage drills. Cap: platform modules behind one service API, deployed by a CI/CD pipeline. | Reachable deployment; pipeline run; rollback shown. Live check: change a config value and redeploy; explain each pipeline stage. | C8, C9, C12 |
| 18 | M9. Monitoring, logging, drift checks, security and cost review, runbook, fault drill. **[Azure]** Azure Monitor (Application Insights and Log Analytics) for the deployed service. | Labs: monitoring drills. Cap: monitoring, runbook, security and cost review of the deployed platform, including a Microsoft Cost Management check of what the learner's own subscription spent. | Runbook; monitoring output. Live check: find an injected fault from logs alone. **Gate M9.** | C9, C8, C5, C11, C12 |
| 19 | M10 Capstone: integration and hardening. | Daily: end-to-end tests, performance and security hardening, data-governance review, requirement traceability, effort estimate against actual, documentation. Mentor checkpoint on Day 5. | Hardening report; traceability table; estimate-versus-actual note. Live check: defend design and estimate to the stakeholder role, no AI. | C10, C1, C9, C11, C12 |
| 20 | M10 Capstone: corporate-style demonstration. | Daily: fix remaining defects, handover pack, runbook, stakeholder presentation (Day 3), final unfamiliar-problem check (Day 4), mock panel and mentor review (Day 5). **[Azure]** Remove Azure resources that are no longer needed. | Deployed, tested, documented platform; demonstration; handover pack. Live check (Programme Objective, section 11): an unfamiliar, scoped problem with a changed requirement, no AI. **Gate M10** and graduation decision. | C10, all |

**Coverage check.** M1 weeks 1-2, M2 weeks 3-4, M3 weeks 5-6, M4 weeks 7-8, M5 weeks 9-10, M6 weeks 11-12, M7 weeks 13-14, M8 weeks 15-16, M9 weeks 17-18, M10 weeks 19-20. That is 10 modules, 20 weeks, 100 days. C1 to C12 each appear at least twice.
## 7. Job-readiness track
**Starts in week 1.** About 68 hours in total. The weekly rhythm is a Day 5 block plus short coding-practice slots. **"Ready to apply" gate:** the learner applies for jobs only after the mentor records a "ready to apply" decision. The earliest planned point is week 17.
| Wk | Job-readiness activity |
|---|---|
| 1 | GitHub profile tidy-up; sales-project repository with README and commit history; mentor picks the coding-practice platform; current CV and LinkedIn saved as the baseline (LinkedIn is the agreed source) |
| 2 | Python practice: strings, lists, dictionaries (easy level); sales project pinned with CI badge |
| 3 | Python practice: arrays and hash maps; CV draft v1 uses only facts the learner can defend |
| 4 | SQL practice starts (select, join, group); LinkedIn headline and summary rewritten for the AI/ML engineer target; ten statistics questions answered in his own words |
| 5 | SQL window functions practice; portfolio project 2 (SQL store) published |
| 6 | First timed Python and SQL practice (45 min, no AI); CV v2 with project results from his own evidence |
| 7 | ML interview basics (metrics, leakage) in his own words; informal 30-minute mock interview |
| 8 | **Mock interview 1:** technical screen (Python, SQL, ML basics). Behavioural stories (STAR format) drafted from his own experience |
| 9 | Timed practice weekly; one-page project write-up (problem, approach, result) |
| 10 | **Mock interview 2:** ML concepts and one project walkthrough; portfolio README review |
| 11 | Behavioural stories refined; data-structure problems |
| 12 | System-design basics 1: draw the components of the week-10 service (data, features, training, serving, monitoring) |
| 13 | Practice; deep-learning interview questions; CV v3 |
| 14 | **Mock interview 3:** 60 minutes, coding plus ML plus behavioural; gaps become next-week tasks |
| 15 | System-design basics 2: design an LLM feature on a whiteboard; GenAI interview questions |
| 16 | **Mock interview 4:** system-design basics and project deep dive; portfolio frozen to the best projects; read about ten real job postings and list the skills they ask for (no statistics claimed) |
| 17 | Mentor "ready to apply" decision; first small batch of tailored applications; Azure deployment added to portfolio |
| 18 | Applications continue; **mock interview 5:** cloud, MLOps and troubleshooting; networking messages |
| 19 | Capstone case study written for the portfolio; **mock interview 6:** behavioural and stakeholder communication |
| 20 | CV, LinkedIn and portfolio final review by the mentor; mock panel on the capstone; job-search plan for after week 20; certification exam dates, if set |

A weekly written status update (done, blocked, next) from week 1 trains working with other roles (C12). Code review: from week 6 the mentor or coach reviews pull requests, and the learner reviews one supplied pull request.
## 8. Azure certifications
Two Azure certifications are planned as extra credentials: **Azure Fundamentals** and **an Azure AI/ML certification**. They do not replace the live no-AI checks. Exam codes below were read on Microsoft Learn pages. Cost, availability for the learner, and exam dates are **not verified** (section 9).
| Certification | Exam code | Status of the code | What Microsoft says it covers | Timeline slot |
|---|---|---|---|---|
| Microsoft Certified: Azure Fundamentals ([page](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/)) | AZ-900 | Shown on Microsoft's page as the exam for this certification. Mentor confirmation pending. | Cloud concepts; Azure architecture and services; Azure management and governance. The page gives 45 minutes and says the exam is proctored. | Study starts in week 3 and builds on weeks 3, 5 and 6. Earliest sensible attempt: after Gate M3 (week 6). The mentor sets the date. |
| Azure AI/ML certification (which one is **[OPEN]**) | **TBC** | Three candidate exams exist; the mentor has not chosen one. | See the candidates below. | After week 18, because it builds on the weeks 9 and 15-18 Azure work. The mentor sets the date. |

**Candidates for the Azure AI/ML certification (all read on Microsoft Learn):**
| Exam code | Certification | Microsoft's description | Notes from the Microsoft page |
|---|---|---|---|
| AI-300 | [Microsoft Certified: Machine Learning Operations Engineer Associate](https://learn.microsoft.com/en-us/credentials/certifications/operationalizing-machine-learning-and-generative-ai-solutions/) | Setting up infrastructure for MLOps and generative AI operations on Azure. Assessed on: MLOps infrastructure, model lifecycle and operations, GenAIOps infrastructure, generative AI quality assurance and observability, optimising generative AI systems. | 120 minutes, proctored, offered in English. Expects experience training, deploying and maintaining models with Azure Machine Learning. This plan gives limited Azure Machine Learning time (weeks 9 and 17-18). |
| AI-103 | [Microsoft Certified: Azure AI Apps and Agents Developer Associate](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-apps-and-agents-developer-associate/) | Designing, developing and deploying Azure AI solutions with Python and Microsoft Foundry. Assessed on: planning and managing Azure AI solutions, generative AI and agentic solutions, computer vision, text analysis, information extraction. | 120 minutes, proctored. Fits weeks 15-16 (GenAI) more than the classical ML weeks. |
| AI-901 | [Microsoft Certified: Azure AI Fundamentals](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-fundamentals/) ([exam page](https://learn.microsoft.com/en-us/credentials/certifications/exams/ai-901/)) | Foundational AI concepts and implementing AI solutions with Microsoft Foundry. | Entry level. Microsoft's exam page lists no retirement date. |

**Retired exams (per Microsoft Learn study guides):** [AI-102](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-102) and [DP-100](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/dp-100) show a retirement warning, so they are not used in this plan.
**Suggestion for the mentor (not a decision).** AI-300 is closest to an ML engineer target and to the weeks 9 and 17-18 Azure work. It is also the hardest of the three given the limited Azure Machine Learning practice in the plan. AI-103 fits the GenAI weeks. AI-901 is the lightest. The mentor decides which one, if any.
## 9. Open points
Everything else in this plan is decided. These are not decided, and nobody should treat them as decided.
| # | **[OPEN]** point | Notes |
|---|---|---|
| 1 | Which Azure AI/ML certification, and its exam code | Candidates AI-300, AI-103, AI-901 (section 8). The mentor chooses. |
| 2 | Cost in India and exam availability for the learner, for AZ-900 and the chosen AI/ML exam | Price not verified. Check Microsoft's scheduling page for the learner's country or region before booking. |
| 3 | Exam dates, and whether exam study sits inside the job-readiness hours or after week 20 | The plan has no spare time. Study for an exam competes with the capstone. |
| 4 | Calendar date for each learning day after week 1, day 1 | The mentor sets the mapping. This plan gives none. |
| 5 | Expected values and submission format for the week 1 sales project (notebook or `.py` modules) | Set by the mentor in the new training material. |
| 6 | Whether the freelance and client-delivery wording in the Programme Objective (capstone in weeks 19-20) is fully replaced by the corporate-style capstone | This plan uses the corporate-style capstone. |
| 7 | Support for the job search after week 20 | Not covered by the 400 hours. |

Not open: the plan stays at 20 weeks, restarting on 2026-11-23. If a live check is not passed, it is repeated with a different variant on the next Day 5 (section 11). Whether to hold the learner at a gate is decided by the mentor from the evidence.
## 10. Training material still needed (mentor will supply)
| Material | Needed by |
|---|---|
| New Day 1 to Day 4 training material for the week 1 redo, a Day 5 live-check question set, and corrections to the sales project handbook (expected totals, summary report line breaks) | Week 1, day 1 |
| Git branches, pull requests, pytest and GitHub Actions handbook | Week 2 start |
| Azure basics handbook: creating his own subscription, the budget-alert steps, the section 5 rules, and AZ-900 study pointers | Week 3 start |
| Capstone brief: fictional retailer, stakeholder, acceptance criteria, synthetic datasets | Week 3 (v0.1 uses the sales project data) |
| Step-by-step handbook, lab set and live-check question bank for each of weeks 3-20, with Azure steps for weeks 5, 9, 15, 17 and 18 | One week ahead of each week |
| Job-readiness templates: coding-practice list, CV and LinkedIn guide, STAR template, mock-interview rubric, system-design primer | Weeks 1, 4, 7 and 12 |
| Certification study plan for the chosen exams | After the open point 1 is decided |

## 11. Evidence and gate rules per module
**Evidence classes:** E1 artefact exists; E2 it ran; E3 result was checked; E4 learner explains it; E5 learner adapts it without AI. Three streams are kept: engineering evidence, AI interaction evidence, competency evidence.
**"Ready for mentor decision" means all of the following** (the agent or coach recommends; only the mentor decides):
1. The work runs from a clean clone using the documented command (E1, E2).
2. Tests pass locally and, from week 2, in CI (E3).
3. README and Git history exist. The AI ledger is complete: attempt before AI, what was accepted or changed, how it was tested.
4. The learner explains the work in his own words (E4).
5. The live no-AI check is passed, including the change request and transfer task (E5). A percentage cannot offset a failed independent check.
6. No secrets in the repository, synthetic data only, and no open critical security or data issue.

A check that is not passed is repeated with a different variant on the next Day 5, and the mentor decides on holding or remediation.
| Gate | Module-specific evidence |
|---|---|
| M1 (wk 2) | Sales project runs from terminal; automated tests for the nine sales-project cases; CI green; meaningful commits; live: fix an injected bug |
| M2 (wk 4) | Statistics functions tested against hand calculation; gradient descent matches a reference; A/B memo; live: justify a test |
| M3 (wk 6) | Pipeline reproducible in a container; data-quality tests; data dictionary; live: add a rule and a column |
| M4 (wk 8) | Leakage-free split; baseline compared; metric justified in business terms; saved model reloads; live: change threshold |
| M5 (wk 10) | More than one model family compared on CV with settings recorded; experiment log; API tests in CI; live: meet a precision target |
| M6 (wk 12) | Time-based validation; report a non-technical reader can follow; bias and privacy checklist; live: explain a prediction |
| M7 (wk 14) | Gradient check; training curves; comparison with a non-deep baseline; model card; live: diagnose a failing run |
| M8 (wk 16) | Learner-written evaluation set; retrieval and answer quality measured, failures analysed; mocked-LLM tests; no keys in repo; live: debug retrieval |
| M9 (wk 18) | Deployed through a pipeline; monitoring and runbook; fault found from logs; security and cost review; live: fault drill |
| M10 (wk 20) | Integrated, hardened platform; end-to-end tests; traceability to requirements; handover pack; stakeholder demonstration; unfamiliar-problem check passed |

## 12. References checked
| Source | What was checked |
|---|---|
| [SFIA 9 machine learning](https://sfia-online.org/en/sfia-9/skills/machine-learning) | Level 3 "Apply" includes deploying models, monitoring them and communicating limits to stakeholders. Level 4 adds assessing suitability, designing solutions and collaborating across teams. Guidance notes cover data preparation, MLOps, evaluation for fairness and bias, ethics, privacy and traceability. **Benchmark:** level 3 by week 20; level 4 is not expected in 20 weeks (mentor-side judgement). This supports C11 and C12. |
| Microsoft certification pages | Section 8 links. Exam codes AZ-900, AI-300, AI-103 and AI-901 and the retirement warnings on AI-102 and DP-100 were read on learn.microsoft.com. |
| Microsoft Learn: [Cost Management budgets](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/tutorial-acm-create-budgets) | Budget alerts on actual or forecast cost; alerts do not stop resources; new subscriptions can take up to 48 hours before budgets are available. |
| Microsoft Learn Azure service pages | [Azure Machine Learning](https://learn.microsoft.com/en-us/azure/machine-learning/overview-what-is-azure-machine-learning), [Azure Container Apps](https://learn.microsoft.com/en-us/azure/container-apps/overview) (mentions Azure Container Registry), [Azure Blob Storage](https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-introduction), [Azure SQL Database](https://learn.microsoft.com/en-us/azure/azure-sql/database/sql-database-paas-overview), [Azure Key Vault](https://learn.microsoft.com/en-us/azure/key-vault/general/overview) (mentions Microsoft Entra ID and Azure RBAC), [Azure Monitor](https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/overview) (Application Insights, Log Analytics workspaces). Microsoft Foundry is named on the AI-103 and AI-901 pages. |

## 13. Risks and what is not verified
| Item | Detail |
|---|---|
| Job outcome | Being hired within or after 20 weeks is **not verified**. No hiring-rate, salary or time-to-hire figures were gathered. The plan builds interview readiness; it cannot promise a job. |
| Scope against hours | Ten modules in about 332 technical hours means limited depth per topic. Deep learning and GenAI get two weeks each. |
| No spare time | The plan has no buffer. Exam study for AZ-900 and the AI/ML certification competes with the capstone (open point 3). |
| Azure cost | The learner pays for his own usage. Prices, free offers and credits are **not stated or verified** here. A budget alert does not stop spending, so stopping unused resources is the learner's job. |
| Certifications | Exam cost in India, tax and availability are **not verified**. The AI/ML exam code is not chosen. |
| Capstone size | A platform with many modules in 20 weeks is a stretch. The mentor can reduce scope. |
| Mentor and coach time | Weekly live checks need mentor or coach time each Day 5. The effort is not estimated. |
| Restart | The redo in week 1 uses new training material that the mentor supplies. If it is late, week 1 cannot start as planned. |
