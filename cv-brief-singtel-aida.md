# CV Generation Brief — Singtel AIDA "Data & AI Platform Engineer" (Req 168065 / successor)

**For:** employment agent preparing Sylvester Koh's application · **Prepared:** July 2026
**Companion doc:** `singapore-relocation-budget.md` (salary floors, pass thresholds, timeline)

---

## 1. Objective and constraints

- **Target role:** Data & AI Platform Engineer, AIDA business unit, Singtel Singapore (grade P2, 1–3 yrs, "fresh graduates encouraged"). If Req 168065 is filled, this brief targets any AIDA data-platform requisition — the spec is stable.
- **Channel:** internal mobility (candidate is a current Optus employee; Singtel wholly owns Optus). Named contacts on the req: Hiring Manager Jian Beng, TA Manager Ching Yap. The CV must survive three readers in order: ATS keyword parse → TA skim (~30 seconds) → hiring-manager technical read.
- **Salary anchor the CV must justify:** ≥ S$6,000 fixed monthly (top half of Singtel's S$5–7k data-engineer band; also the Dependant's Pass threshold). Every content decision should ladder up to "top-of-band P2 with unusual operational maturity."
- **Timing:** application window ~Sep 2026 (12-month Optus tenure reached; UNSW Master of Analytics two months from completion). The CV is built now, finalized against whatever gap-closure work is done by then.

## 2. Positioning strategy

**Reposition from** "senior support specialist who also does data" **to** "data/AI platform engineer with production telco operations experience."

Narrative spine (the story every section must reinforce):
1. Three years operating enterprise SaaS and telco platforms to SLA (RCS, Optus) — this person understands production reliability, incident response, and stakeholder communication, which pure fresh-grad competitors do not.
2. Independently designed, shipped, and **operates** a production Azure data pipeline with an integrated, security-hardened LLM assistant — a working miniature of what AIDA builds.
3. Master of Analytics (UNSW, Nov 2026) formalizing the ML/statistics layer.

Positioning rules:
- Badge the employer as **"Optus (Singtel Group)"** — the internal-transfer signal must be visible in a 5-second skim.
- Headline under the name: `Data & AI Platform Engineer | Azure data pipelines · LLM/RAG integration · 3+ yrs telco & SaaS platform operations (Singtel Group)`.
- The support career is reframed as *platform operations*, never hidden — it is the differentiator, not the liability. Verbs shift from "resolved/supported" to "operated/administered/automated/root-caused."
- P2 is a junior-professional grade: do not oversell into senior-engineer register; sell *trajectory + reliability*.

## 3. JD keyword map (ATS + content targeting)

The agent must ensure every left-column term appears verbatim somewhere defensible. Right column states the evidence source and honesty status.

| JD term | Evidence | Status |
|---|---|---|
| Python, SQL | RCS/Optus scripting, SGN project, UNSW | ✅ solid — feature prominently |
| Azure (hybrid cloud) | Azure Functions, Azure SQL Serverless in project | ✅ solid |
| ETL/ELT, data ingestion pipelines, batch | SGN warehouse (~1,500 rows/day, monitoring, auto-replay) | ✅ solid |
| Data transformation & validation (SQL) | Project + SQL Server admin at RCS | ✅ solid |
| CI/CD, version control | GitHub workflow on project | ✅ solid — name Git/GitHub Actions explicitly |
| RAG, knowledge base, embeddings | Claude assistant (guardrailed, no direct DB access) is adjacent; **build the RAG extension (§5) before claiming RAG/embeddings** | 🟡 close the gap, then claim |
| Document parsing, PyMuPDF | Not yet held; §5 demo is cheap (JD names PyMuPDF) | 🟡 build first |
| Spark / PySpark, large-scale processing | UNSW big-data coursework if taken + §5 micro-conversion | 🟡 claim as coursework/portfolio only |
| Kafka / streaming | Gap; do not claim. Mitigate with "batch today, streaming roadmap" framing in interview, not CV | 🔴 omit |
| PyTorch, PEFT, LoRA, OCR, VLM, TTS | Gap; XGBoost/scikit-learn is the honest ML evidence. List JD-matching items only under "currently developing (UNSW)" if actually in coursework | 🔴 omit unless §5 done |
| Microsoft Fabric, Databricks, Delta Lake | Gap; Databricks Community Edition exercise in §5 → "familiar" tier at most | 🟡 optional |
| Data governance, access control, PII | Security-hardened assistant (input validation, rate limiting, least-privilege DB access) + Monash cybersecurity cert | ✅ genuine — under-used in current CV, elevate |
| Documentation, metadata, traceability | 65+ KB articles renewal at Optus; pipeline monitoring docs | ✅ reframe existing bullet |
| Independent + collaborative, stakeholder comms | SME/onboarding work at RCS; 28-person queue project at Optus | ✅ solid |

Coverage target: ≥ 80% of JD nouns present after §5 work; 100% of claims interview-defensible.

## 4. Section-by-section instructions

**Header.** Name; headline (above); Singapore-facing contact block: keep +61 mobile, add "Relocating to Singapore — [month] 2026 · Singtel Group employee (Optus)". Links: kohstack.au (must show the live project), linkedin.com/in/sylvester-koh, GitHub. No photo, no address.

**Summary (3 lines max).** Rewrite around the narrative spine. Draft direction: *"Data & AI platform engineer with 3+ years operating enterprise telco/SaaS platforms (Optus — Singtel Group). Built and operate a production Azure ETL pipeline with automated monitoring and a security-hardened LLM assistant. Completing UNSW Master of Analytics (Nov 2026); seeking internal transfer into Singtel AIDA."* Kill "creative problem solver" phrasing — P2 platform readers screen for nouns, not adjectives.

**Skills (re-categorized to mirror the JD).** Four groups, honest tiers:
- *Data engineering:* Python, SQL, ETL/ELT, star-schema modeling, data validation, automation, PowerShell/Bash
- *Cloud & platform:* Azure Functions, Azure SQL, AD/Entra, M365, AWS (basic), Git/GitHub CI/CD, Linux
- *AI/ML:* XGBoost, scikit-learn, pandas, Anthropic Claude API, prompt/guardrail design; (+RAG/LlamaIndex, PyMuPDF after §5)
- *Operations & governance:* ITIL/ServiceNow, SLA management, incident response, monitoring/alerting, access control, PII handling (Monash cybersecurity cert)
Drop from this CV: telephony/desktop-support noise (branded apps, Zoom, Notion) — they dilute the parse.

**Experience.** Same employers/dates (never alter), rewritten emphasis:
- *Optus (Singtel Group) — Senior Service Centre Client Specialist.* Lead bullet becomes the ITSM queue-management project, quantified as a data project (28-person team, aged cases →~10 in a month, SLA breaches made outliers — describe the analysis/automation used). Keep incident-management bullet (platform reliability signal). KB renewal bullet reframed as documentation/knowledge-pipeline work. Cut or compress pure contact-volume bullets to one line.
- *RCS Australia — Senior Traffic Support.* Lead with Windows Server / SQL Server / AD administration and proactive maintenance; then API/cloud/integration root-cause analysis with dev teams; then requirements-to-product translation. This is the "operated production systems" proof.

**Projects (the centerpiece — give it room).** SGN Flight Warehouse, restructured in platform language, one bullet per JD theme: ingestion (unattended Azure pipeline, 15k+ records, ~1,500/day) → reliability (built-in monitoring, failure flagging, automatic replay of missed runs) → modeling (star-schema warehouse) → ML (XGBoost classifier, ROC-AUC ≈ 0.80, backtesting + bias correction) → **AI + governance** (Claude assistant with input validation, rate limiting, no direct database access). Append §5 extensions *only once built*, each with its own bullet. Repo/portfolio link mandatory. The airline-satisfaction analysis (this repo) is the secondary project if space allows.

**Education.** UNSW Master of Analytics — "expected Nov 2026", list 2–3 JD-relevant modules (ML, big-data processing, statistics). Monash cybersecurity cert stays (feeds governance). Swinburne BIS last.

## 5. Gap-closure workstream (prerequisite, Jul–Sep 2026)

The CV's ceiling is set by what exists by September. Priority order, each ~1–2 weekends, each yielding one honest CV bullet + public repo evidence:
1. **RAG extension** on the SGN warehouse: LlamaIndex (or LangChain) knowledge base over flight/ops documents, embeddings + retrieval feeding the existing Claude assistant. Unlocks the JD's core nouns: RAG, knowledge base, embeddings, indexing/retrieval.
2. **PyMuPDF document-parsing demo:** parse the project's own PDF reports (layout-aware extraction into the warehouse). The JD names PyMuPDF explicitly — cheap, high-signal.
3. **PySpark conversion** of one pipeline stage (Databricks Community Edition) → "familiar with PySpark/Databricks" becomes true.
Skip (not worth pre-offer effort): Kafka, TTS, VLM fine-tuning, PEFT/LoRA — acknowledge as growth areas in interview.

## 6. Variants and collateral

1. **Master CV** (2 pages) — full detail, source of truth.
2. **Tailored 1-page PDF** for this req — the version submitted; cuts secondary project and RCS to 3 bullets.
3. **Internal expression-of-interest note** (short email to TA Ching Yap, cc'able to hiring manager): current Optus role + tenure, one-paragraph fit, CV attached, asks about req status and the internal-transfer process. This is the actual first contact — the CV rides on it.
4. **LinkedIn sync:** headline/summary/skills mirrored before any outreach (TA will cross-check within hours).
5. **Portfolio page** on kohstack.au for the SGN project using JD vocabulary (ingestion, RAG, governance).

## 7. Formatting and ATS rules

Single column; standard headings (Summary/Skills/Experience/Projects/Education); no tables, text boxes, icons, or graphics; 10.5–11pt system font; PDF with a real text layer — **verify by running `pdftotext` on the final file and checking every keyword survives** (the current "offwhite" template must be re-tested). Filename: `Sylvester_Koh_DataAI_Platform_Singtel.pdf`. Dates in `MMM YYYY`. No model-ID/AI-generation footers.

## 8. Honesty guardrails

- Nothing on the CV the candidate cannot whiteboard for 10 minutes.
- Coursework/portfolio skills labelled as such ("portfolio", "UNSW coursework"), never implied as employment experience.
- No claiming streaming, OCR/VLM, or fine-tuning until §5 (or coursework) makes them real.
- Employers, titles, dates, metrics exactly as per the existing verified CVs.

## 9. QA checklist before submission

- [ ] Req 168065 status confirmed on Singtel internal careers portal (or successor req identified)
- [ ] ≥80% JD keyword coverage (map in §3), zero unsupported claims
- [ ] Every experience bullet quantified or outcome-stated
- [ ] `pdftotext` render test passed; 1-page variant ≤ 1 page
- [ ] "Optus (Singtel Group)" and relocation line visible in top third
- [ ] LinkedIn synced; portfolio link live and loading
- [ ] EOI note drafted; salary expectation ready if asked: "S$6,000+ fixed monthly" (never volunteered in the CV)
