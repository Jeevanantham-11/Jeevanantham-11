<div align="center">

<!-- LUXURY HERO BANNER WITH 3D SPINNING COIN, TYPEWRITER ANIMATION & FLOWING GOLDEN SPARKS -->
<img src="banner.svg" width="100%" alt="Jeevanantham C"/>

<br/>

<!-- DYNAMIC TYPING FOCUS LINE (ENGINEERING SPECIALIZATIONS ONLY) -->
<a href="https://github.com/Jeevanantham-11">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=16&duration=3000&pause=1000&color=8A6B3E&center=true&vCenter=true&multiline=false&width=720&height=36&lines=Software+Development+Engineer+(SDE)+%26+Machine+Learning+Engineer;Building+Deterministic+Zero-Trust+Security+for+MCP+AI+Agents;Multi-AGV+Swarm+Model+Predictive+Control+(OSQP+Solver);High-Recall+Graph+Topological+Fraud+Detection+Ensembles;Specializing+in+Applied+NLP%2C+RAG+%26+Distributed+Systems" alt="Focus Line" />
</a>

<!-- REFINED EDITORIAL STATUS CAPSULES -->
<p align="center">
  <img src="https://img.shields.io/badge/Status-Active_for_SDE_&_ML_Roles-ffffff?style=flat-square&logo=statuspage&logoColor=2e7d32&labelColor=faf7f0&color=c5a880" alt="Status"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Location-Chennai,_India-ffffff?style=flat-square&logo=googlemaps&logoColor=8a6b3e&labelColor=faf7f0&color=c5a880" alt="Location"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Discipline-Systems_Architecture_&_AI-ffffff?style=flat-square&logo=codeforces&logoColor=8a6b3e&labelColor=faf7f0&color=c5a880" alt="Discipline"/>
</p>

</div>

<img src="divider.svg" width="100%"/>

### <img src="https://img.shields.io/badge/01-EXECUTIVE_SUMMARY-8a6b3e?style=for-the-badge&logoColor=white&labelColor=faf7f0&color=c5a880" alt="01 // Executive Summary"/>

> *"Software and machine learning engineer focused on intelligent system design, natural language processing, predictive analytics, and mathematical optimization. Dedicated to engineering robust, scalable architectures that bridge machine learning models with performant software systems, backed by a proven track record in national hackathons and competitive problem solving."*

---

### <img src="https://img.shields.io/badge/02-FEATURED_SYSTEMS-8a6b3e?style=for-the-badge&logoColor=white&labelColor=faf7f0&color=c5a880" alt="02 // Featured Systems"/>

<table>
<tr>
<td width="50%" valign="top">

#### Argus — MCP Agent Runtime Security Layer
`[ ZERO-TRUST MCP ]` `[ RUNTIME AST FIREWALL ]`

* **Problem:** Autonomous AI agents connected to Model Context Protocol (MCP) tools face severe risks from silent tool tampering, parameter poisoning, and unauthorized execution-plan deviations.
* **Architecture:** Operates as a transparent middleware performing deterministic tool metadata fingerprinting and data-trust tagging to halt untrusted execution paths before invoking sensitive actions.
* **Tech Stack:** `Python` `MCP Protocol` `AST Analysis` `FastAPI` `Zero-Trust Policy`

<details>
<summary><b>TECHNICAL ARCHITECTURE &amp; SPECS</b></summary>

```
[ LLM Execution Plan ]
          │
          ▼
┌───────────────────────────────┐
│ ARGUS DETERMINISTIC FIREWALL  │
│ ├─ Tool Metadata Fingerprint  │ ──► [ Block Hijack / Tamper ]
│ ├─ Taint & Trust Tagger       │
│ └─ Policy AST Static Enforcer │
└───────────────────────────────┘
          │ (Verified < 1.2ms)
          ▼
   [ Safe Action Dispatch ]
```
* **Performance:** Sub-millisecond policy verification overhead (`< 1.2ms`).
* **Guarantee:** Eliminates probabilistic filter bypasses with strict capability AST boundaries.
</details>

</td>
<td width="50%" valign="top">

#### NeuroSwarm-X — Multi-AGV Digital Twin OS
`[ SWARM MPC ]` `[ ROS2 SIMULATION ]`

* **Problem:** High-density automated guided vehicle (AGV) warehouse fleets face battery thermal throttling, efficiency loss, and trajectory deadlocks during peak continuous operations.
* **Architecture:** Formulates real-time Model Predictive Control (MPC) incorporating thermal dissipation using the OSQP quadratic solver, coordinated over ROS2 DDS with a high-fidelity Digital Twin in Unity3D and Gazebo.
* **Tech Stack:** `ROS2` `Python` `OSQP Solver` `Unity3D` `Gazebo` `C++`

<details>
<summary><b>CONTROL LOOP &amp; SIMULATION SPECS</b></summary>

```
[ AGV Thermal Sensors ] ◄──► [ ROS2 DDS Bus ] ◄──► [ Unity3D / Gazebo Twin ]
                                     │
                                     ▼
                     ┌──────────────────────────────┐
                     │   OSQP Quadratic Solver      │
                     │ ├─ Thermal Heat Penalty      │
                     │ └─ Non-Linear Trajectory MPC │
                     └──────────────────────────────┘
```
* **Solver Horizon:** `< 4.8ms` solve cycle via OSQP quadratic optimization.
* **Result:** Zero multi-robot collision deadlocks across continuous benchmark runs.
</details>

</td>
</tr>

<tr>
<td width="50%" valign="top">

#### Mule Shield AI — Mule Account Detection
`[ GRAPH FORENSICS ]` `[ ENSEMBLE CLUSTERING ]`

* **Problem:** Organized cyber syndicates exploit multi-hop mule account transactions that evade traditional single-account heuristic fraud checks.
* **Architecture:** Employs Louvain graph community detection to uncover hidden transactional rings, combined with a high-recall ensemble of XGBoost, LightGBM, and CatBoost with SHAP explainability.
* **Tech Stack:** `XGBoost` `LightGBM` `Graph Networks` `SHAP` `SMOTE-Tomek`

<details>
<summary><b>FORENSIC PIPELINE SPECS</b></summary>

* **Topological Clustering:** Identifies coordinated syndicate cycles over transaction graph adjacencies.
* **Ensemble Recall:** Balanced with SMOTE-Tomek to achieve `99.2%` recall on rare fraud vectors with full tree-attribution SHAP transparency.
</details>

</td>
<td width="50%" valign="top">

#### PRAANA — Predictive Business Health
`[ 90-DAY FORECASTING ]` `[ GROQ LPU INFERENCE ]`

* **Problem:** Small and medium businesses often face sudden operational insolvency due to lack of real-time financial trajectory forecasting and early intervention.
* **Architecture:** 10-metric dynamic financial scoring engine generating 90-day trajectory forecasts paired with automated mitigation recommendations powered by Llama 3.3 70B on Groq LPUs.
* **Tech Stack:** `FastAPI` `Next.js 14` `Supabase` `Groq / Llama 3.3`

<details>
<summary><b>HEALTH INDEX &amp; FORECASTING SPECS</b></summary>

* **Forecasting Horizon:** 90-day cashflow liquidity and operational stability indices.
* **Intervention Engine:** Autonomous operational recovery plans synthesized in `< 450ms` via Groq LPU acceleration.
</details>

</td>
</tr>
</table>

<img src="divider.svg" width="100%"/>

### <img src="https://img.shields.io/badge/03-SYSTEM_BENCHMARKS-8a6b3e?style=for-the-badge&logoColor=white&labelColor=faf7f0&color=c5a880" alt="03 // System Benchmarks"/>

| Flagship System | Core Innovation | Key Benchmark / Metric | Primary Stack |
| :--- | :--- | :--- | :--- |
| **Argus** | Deterministic Tool Policy Firewall | **< 1.2ms** Verification Latency | `MCP Protocol` · `Python` · `FastAPI` |
| **NeuroSwarm-X** | Thermal-Aware Swarm MPC | **< 4.8ms** OSQP Solve Cycle | `ROS2 Humble` · `OSQP` · `Unity3D` |
| **Mule Shield AI** | Louvain Graph & Ensemble Forensics | **99.2%** Fraud Ring Recall | `XGBoost` · `CatBoost` · `SHAP` |
| **PRAANA AI** | 90-Day Cashflow Forecasting | **< 450ms** Strategy Synthesis | `Llama 3.3 70B` · `Groq LPU` · `Next.js` |

<img src="divider.svg" width="100%"/>

### <img src="https://img.shields.io/badge/04-TECHNICAL_ARSENAL-8a6b3e?style=for-the-badge&logoColor=white&labelColor=faf7f0&color=c5a880" alt="04 // Technical Arsenal"/>

#### 1. Programming Languages
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/PostgreSQL_/_SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"/>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C"/>
</p>

#### 2. Natural Language Processing & LLMs (NLP)
<p>
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/RAG_Architecture-8a6b3e?style=flat-square&logo=databricks&logoColor=white" alt="RAG"/>
  <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/LlamaIndex-4353FF?style=flat-square&logo=meta&logoColor=white" alt="LlamaIndex"/>
  <img src="https://img.shields.io/badge/SpaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white" alt="SpaCy"/>
  <img src="https://img.shields.io/badge/Groq_LPU-F55036?style=flat-square&logo=speedtest&logoColor=white" alt="Groq"/>
</p>

#### 3. Machine Learning, Deep Learning & Analytics
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="Scikit-Learn"/>
  <img src="https://img.shields.io/badge/XGBoost-006ACC?style=flat-square&logo=xgboost&logoColor=white" alt="XGBoost"/>
  <img src="https://img.shields.io/badge/LightGBM-4C8CBF?style=flat-square&logo=chartdotjs&logoColor=white" alt="LightGBM"/>
  <img src="https://img.shields.io/badge/SHAP-c5a880?style=flat-square&logo=circleci&logoColor=black" alt="SHAP"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
</p>

#### 4. Web & Backend Architecture
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Next.js_14-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=black" alt="Supabase"/>
</p>

#### 5. Robotics, Simulation & Optimization
<p>
  <img src="https://img.shields.io/badge/ROS2_Humble-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS2"/>
  <img src="https://img.shields.io/badge/Gazebo_Sim-FF6F00?style=flat-square&logo=gazebo&logoColor=white" alt="Gazebo"/>
  <img src="https://img.shields.io/badge/Unity3D_Twin-222C37?style=flat-square&logo=unity&logoColor=white" alt="Unity3D"/>
  <img src="https://img.shields.io/badge/OSQP_Solver-00B4D8?style=flat-square&logo=mathworks&logoColor=white" alt="OSQP"/>
</p>

#### 6. Cloud, DevOps & Infrastructure
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="GCP"/>
  <img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure"/>
</p>

<img src="divider.svg" width="100%"/>

### <img src="https://img.shields.io/badge/05-NATIONAL_ACCOLADES-8a6b3e?style=for-the-badge&logoColor=white&labelColor=faf7f0&color=c5a880" alt="05 // National Accolades"/>

| Standing | Competition / Track | Institution / Host |
| :--- | :--- | :--- |
| **Finalist** | Quantathon & Programming Contest | **IIT Madras Shaastra 2026** |
| **Top 42 / 2000+ Teams** | Intelligent Systems & Hardware Co-Design | **SmartMotion Hackathon 2.0 (CIT)** |
| **Top 25 / 500+ Teams** | Full-Stack AI & Distributed Systems | **HACK IT 2.0 (Anna University)** |
| **Top 10 Finalist** | Predictive Conversion Analytics | **AI-Driven Marketing Hackathon (Linkenite)** |

**Professional Certifications:**
* DeepLearning.AI NLP Specialization
* AWS ML Foundations & Cloud 101
* Microsoft Learn (AI, Generative AI & Cloud Security)

<img src="divider.svg" width="100%"/>

### <img src="https://img.shields.io/badge/06-CONNECT_HUB-8a6b3e?style=for-the-badge&logoColor=white&labelColor=faf7f0&color=c5a880" alt="06 // Connect Hub"/>

<div align="center">

<p>
  Feel free to reach out for software engineering roles, machine learning initiatives, or research discussions:
</p>

<a href="https://www.linkedin.com/in/jeevananthamchandrasekaran" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-Jeevanantham_C-ffffff?style=for-the-badge&logo=linkedin&logoColor=0A66C2&labelColor=faf7f0&color=c5a880" alt="LinkedIn"/>
</a>
&nbsp;
<a href="mailto:jeevajeeva71196@gmail.com">
  <img src="https://img.shields.io/badge/Email-Direct_Dispatch-ffffff?style=for-the-badge&logo=gmail&logoColor=EA4335&labelColor=faf7f0&color=c5a880" alt="Email"/>
</a>
&nbsp;
<a href="https://leetcode.com/u/Jeevanantham_Chandrasekaran/" target="_blank">
  <img src="https://img.shields.io/badge/LeetCode-Jeevanantham_Chandrasekaran-ffffff?style=for-the-badge&logo=leetcode&logoColor=FFA116&labelColor=faf7f0&color=c5a880" alt="LeetCode"/>
</a>
&nbsp;
<a href="https://github.com/Jeevanantham-11" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-Jeevanantham--11-ffffff?style=for-the-badge&logo=github&logoColor=181717&labelColor=faf7f0&color=c5a880" alt="GitHub"/>
</a>

<br/><br/>

```sql
-- Candidate Query
SELECT candidate, role_focus, readiness 
FROM engineering_talent 
WHERE candidate = 'Jeevanantham C' 
  AND discipline IN ('SDE', 'Machine Learning', 'NLP');
-- Status: 200 OK | Ready to Ship High-Impact Systems
```

<sub>Curated with precision for <b>Jeevanantham C</b> · Built with modern engineering discipline</sub>

</div>
