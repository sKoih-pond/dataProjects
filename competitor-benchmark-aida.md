# Benchmark Analysis — Incumbent Hire, Singtel AIDA

**Subject:** Brian Tham — AI Platform Engineer, Singtel AIDA (hired ~Feb 2026)
**Prepared:** July 2026 · **Purpose:** calibrate the AIDA hiring bar for `cv-brief-singtel-aida.md`
**Sourcing note:** LinkedIn and tham.ai return 403 to automated fetching; this is compiled from publicly indexed sources (search results, [GitHub/Nightey3s](https://github.com/Nightey3s), [dev.to post](https://dev.to/nightey3s/launching-my-ai-portfolio-brian-tham-49db), Singtel careers portal). Treat as directional, not verified line-by-line.

---

## 1. Two corrections to the premise

1. **Name:** Brian Tham (not Bryan).
2. **Different requisition.** They hold **"AI Platform Engineer — #AIDA"**. The target role is **"Data & AI Platform Engineer — #AIDA"** — a separate, concurrently-listed req. Adjacent sibling role, not the same seat.

## 2. Headline finding — AIDA is hiring at scale, and the target req appears live

The Singtel careers portal currently lists at least four distinct AIDA platform reqs:

| Req | Relevance |
|---|---|
| [**Data & AI Platform Engineer — #AIDA**](https://groupcareers.singtel.com/job/Data-&-AI-Platform-Engineer-AIDA-Sing/1327769266/) | **The target role — appears live on the portal** |
| [AI Platform Engineer — #AIDA](https://groupcareers.singtel.com/job/AI-Platform-Engineer-AIDA-Sing/1327770266/) | Incumbent's role; also graduate-marketed via [gradsingapore](https://gradsingapore.com/graduate-employers/singtel/jobs-internships/ai-platform-engineer-aida) |
| [AI Platform Operations Engineer — #AIDA](https://groupcareers.singtel.com/job/AI-Platform-Operations-Engineer-AIDA-Sing/1327828466/) | **Strong secondary target** — "operations" framing suits 3+ yrs production ops |
| [Senior AI Platform Engineer](https://groupcareers.singtel.com/job/Senior-AI-Platform-Engineer-Sing/1212026866/) | Above current level; track for later |

**Implication:** this is not a single-seat contest. AIDA is standing up a unit and hiring across several profiles — the earlier concern that Req 168065 (Sep 2025) had gone stale is resolved; verify exact status on the internal portal.

## 3. Incumbent profile

- **Education:** BSc (Hons) Applied Artificial Intelligence, Singapore Institute of Technology (expected 2026); Diploma in IT, Singapore Polytechnic (2021). Hired at/near fresh-graduate stage.
- **Research:** A*STAR I2R internship — foundation models for medical imaging; A*STAR Research Internship Award (ARIA).
- **Certifications:** Google Cloud Professional Machine Learning Engineer; Microsoft Azure certified.
- **Stack:** Azure, GCP, RHEL, OpenShift, Kubernetes, Docker, Infrastructure-as-Code, Python, PyTorch, TensorFlow, LLMs.
- **Work at AIDA:** enterprise GenAI platform on on-prem Kubernetes/OpenShift — model deployment, OpenAI-compatible inference APIs, benchmarking, observability, authentication, production troubleshooting across LLM and multimodal workloads.
- **Public portfolio:** `tham.ai` (dedicated domain), FoodVision (YOLOv8, 55 classes), multimodal profanity detection, emotion analysis; DEV article, DataCamp portfolio, archived prior site.

## 4. What this reveals about the hiring bar

AIDA hires for **hands-on GenAI infrastructure capability demonstrated publicly**, and is comfortable hiring junior when that evidence exists. Three signals:
1. **Certifications carry weight** — cloud/ML certs on a fresh-grad profile.
2. **Public portfolio is expected**, with a real domain and shipped, documented projects.
3. **Container/orchestration fluency** (Kubernetes, OpenShift, Docker, IaC) is core, not optional.

## 5. Competitive read — where the candidate wins and loses

**Losing ground (vs this profile, on the pure *AI Platform* req):**
- No Kubernetes/OpenShift/Docker/IaC exposure.
- No cloud or ML certification.
- No deep-learning framework depth (PyTorch/TensorFlow) — XGBoost/scikit-learn is the honest ceiling.
- Local fresh graduate = no EP required, lower cost, no COMPASS friction. **A local junior is structurally cheaper to hire than a foreign one at the same level** — this is the core competitive disadvantage, and the argument against competing head-on for a junior AI-platform seat.

**Winning ground (and why the *Data & AI Platform* / *Platform Operations* reqs are the right targets):**
- **3+ years production operations** — SLA discipline, incident management, root-cause analysis. The incumbent profile shows no production operations history; this is the clearest non-overlapping asset.
- **Data engineering weighting** — the target req is pipeline-shaped (document parsing, ingestion, ETL, Fabric/Databricks, RAG). The SGN Flight Warehouse maps to that far better than to model-serving infra.
- **Telco domain + Singtel Group insider** — Optus tenure, internal-mobility channel, understands the operating environment.
- **Postgraduate qualification** — UNSW Master of Analytics carries COMPASS C2 (20 pts); a local SIT bachelor's is irrelevant to that calculus but the master's is the stronger credential on paper.
- **Governance/security angle** — Monash cyber cert + the security-hardened Claude assistant; AIDA's JD explicitly asks for data governance, PII handling, access control.

## 6. The EP justification threshold (recruitment's view)

**Hard gates — binary, fail any and there is no EP:**
| Gate | Requirement |
|---|---|
| Fixed monthly salary | **≥ S$5,600** (Singtel = non-financial-services). Not negotiable downward |
| COMPASS | **≥ 40 points** |
| Credentials | Recognised degree + experience commensurate with the role |
| **Fair Consideration Framework** | Role advertised on MyCareersFuture and locals fairly considered **before** the EP is lodged ([MOM FCF guide 2026](https://rafflescorporateservices.com/mom-fair-consideration-framework-fcf-mycareersfuture-singapore-2026/)). Minimum duration reported as 14 days, with sources indicating an increase to 28 — **verify current duration**. Exemptions exist for internal transferees; whether an Australia→Singapore Group transfer qualifies must be confirmed with Singtel HR |

**The commercial threshold — the actual judgment.** Clearing the gates only makes an EP *possible*. Recruitment's real question is: *is this candidate enough better than the best local applicant to justify the cost?* That cost is concrete — a 14–28 day advertising window before filing, EP processing time on top, application fees, rejection risk, and renewal risk (COMPASS applies to EP renewals from 1 Jul 2026). A local hire carries none of it.

**Quantified position:**
- **Salary ask: S$6,000–6,500.** Below S$5,600 disqualifies outright; S$6,000 clears the Dependant's Pass threshold and scores C1; above ~S$7,000 invites comparison against senior local candidates.
- **COMPASS: target 50+, not 40.** C1 (10) + C2 (20) = 30 locked *provided* the UNSW master's is conferred and salary meets benchmark; Singtel's firm-level C3/C4 likely adds strongly; C5 SOL bonus if the role qualifies. Do not rely on the SOL bonus alone.
- **Differentiation: must name a capability the local applicant pool structurally lacks** — here, 3+ years production telco operations at SLA, plus existing Singtel Group tenure.

**The decisive reframe.** At *junior* level the threshold is effectively unclearable: local fresh graduates are cheaper, faster and frictionless, and AIDA has already demonstrated it will hire exactly that (§3). At *experienced* level the comparison set changes to experienced local data engineers who already cost S$6,000+ — EP friction becomes normal, and 3 years of production operations counts as the differentiator rather than a consolation.

**So the threshold is not a score, it is a category: be evaluated as an experienced hire, not a junior one.** Everything else — salary ask, req selection, CV positioning — follows from that.

## 7. Actions arising

1. **Reprioritise reqs:** target **Data & AI Platform Engineer** (primary) and **AI Platform Operations Engineer** (strong secondary — operations framing is the candidate's home turf). Do not compete head-on for the junior AI Platform Engineer seat.
2. **Close the certification gap** — cheapest, highest-signal fix. Azure Data Engineer Associate (DP-203) or Azure AI Engineer (AI-102) fits the existing Azure stack; target before September.
3. **Add container fluency** — Dockerise the SGN pipeline; basic Kubernetes literacy. Elevates the portfolio to the bar this hire set.
4. **Upgrade kohstack.au** to portfolio-grade — the incumbent's `tham.ai` is the standard being met; a live, documented project page with JD vocabulary is now table stakes, not optional polish.
5. **Lead the pitch with the non-overlapping asset:** production reliability and data-pipeline operations, not ML modelling depth — do not fight on the axis where a specialist AI graduate is stronger.
