<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Amine%20El%20Gardoum&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Data%20Engineering%20Student%20%C2%B7%20AI%20%2F%20RAG%20Systems%20%C2%B7%20Morocco%20%F0%9F%87%B2%F0%9F%87%A6&descAlignY=55&descSize=18"/>

**Building retrieval-augmented systems and the data pipelines that feed them.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amine-el-gardoum-491a82333)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF6B35?style=for-the-badge&logo=vercel&logoColor=white)](https://amine-s-portfolio.netlify.app/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:amine.elgardoum@etu.uae.ac.ma)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/AMINE44467019)

<img src="https://komarev.com/ghpvc/?username=amineelgardoum-rgb&style=for-the-badge&color=6c11ff" alt="profile views"/>
<img src="https://img.shields.io/github/followers/amineelgardoum-rgb?style=for-the-badge&logo=github&logoColor=white" alt="followers"/>

</div>

---

## `whoami`

```python
class Amine:
    role       = "Data Engineering Student & AI Systems Builder"
    school     = "ENSA Al Hoceima — Ingénierie des Données, Class of 2027"
    location   = "Morocco 🇲🇦"
    seeking    = "Internship / entry-level — Data Engineering, Data Science, AI"

    links = {
        "linkedin": "https://www.linkedin.com/in/amine-el-gardoum-491a82333",
        "portfolio": "https://amine-s-portfolio.netlify.app/",
        "email":     "amine.elgardoum@etu.uae.ac.ma",
        "x":         "https://x.com/AMINE44467019",
        "github":    "https://github.com/amineelgardoum-rgb",
    }

    focus = [
        "🤖  RAG pipelines & LLM-powered agents",
        "⚡  Data pipeline orchestration (Airflow)",
        "🔍  Semantic search & vector retrieval",
        "🚀  End-to-end ML deployment (FastAPI)",
    ]

    recent_experience = "AI Engineer Intern @ BCC-BEY Consulting (Jul–Sep 2026)"

    open_to = [
        "💼  Data / AI engineering internships & full-time roles",
        "🔧  Freelance data & automation projects",
        "🌍  Open-source collaboration",
    ]

    currently_exploring = [
        "No-code/low-code automation (Make, n8n, Zapier)",
        "Multi-agent LLM systems",
        "Vector databases & semantic search optimization",
    ]
```

---

## `currently`

```python
currently = [
    "🛠️  Wrapping up my Data Engineering degree at ENSA Al Hoceima",
    "🤖  Building RAG + agent systems end to end",
    "      ↳ ingestion, retrieval, serving",
    "📚  Deepening Airflow orchestration + containerized deploys with Docker",
    "🔎  Looking for an internship or entry-level role",
    "      ↳ where data meets applied AI",
]
```

---

## `experience`

```python
from dataclasses import dataclass, field


@dataclass
class Role:
    company: str
    title: str
    location: str
    period: str
    highlights: list[str] = field(default_factory=list)


EXPERIENCE = [
    Role(
        company="BCC-BEY Consulting & Communication",
        title="AI Engineer Intern",
        location="Oujda, Morocco (Remote)",
        period="Jul 2026 – Sep 2026",
        highlights=[
            "🧩  Built a RAG chatbot for automatic PDF summarization",
            "      ↳ LangChain orchestrating retrieval and generation",
            "📥  Built the document ingestion & indexing pipeline",
            "      ↳ text extraction, chunking, embeddings for semantic search",
            "✍️  Integrated the generation model to produce",
            "      ↳ context-aware summaries from retrieved passages",
        ],
    ),
]
```

---

## `how_i_work`

```python
STAGES = [
    ("📡 Ingest",        ("Kafka", "Airflow")),
    ("🧹 Clean & Model", ("Pandas", "SQL", "dbt")),
    ("🤖 Embed / Train", ("LangChain", "TensorFlow", "Scikit-learn")),
    ("🚀 Serve",         ("FastAPI", "Docker")),
    ("📊 Monitor",       ("Grafana", "Prometheus")),
]

# I like building the full loop — not just a model in a notebook, but the
# pipeline that feeds it and the API/dashboard that serves it.
flow = " → ".join(f"{name} ({', '.join(tools)})" for name, tools in STAGES)
```

---

## `stack`

```python
STACK = {
    "data engineering": [
        "Apache Kafka",
        "Apache Airflow",
        "Apache Spark",
        "dbt",
    ],
    "ai / ml": [
        "LangChain",
        "HuggingFace",
        "Ollama",
        "Google Gemini",
        "TensorFlow",
        "Scikit-learn",
        "Pandas",
        "NumPy",
    ],
    "infrastructure & databases": [
        "Docker",
        "AWS",
        "PostgreSQL",
        "MongoDB",
        "Redis",
        "ElasticSearch",
    ],
    "observability": [
        "Prometheus",
        "Grafana",
    ],
    "languages & frameworks": [
        "Python",
        "Java",
        "SQL",
        "FastAPI",
        "React",
        "TailwindCSS",
    ],
}
```

---

## `projects`

```python
PROJECTS = [
    {
        "name": "RAG AI Chatbot",
        "url": "https://github.com/amineelgardoum-rgb/Rag_amine_chatbot",
        "tagline": "LLM-powered assistant, ingestion to generation.",
        "stack": ["Python", "LangChain", "Docker"],
        "highlights": [
            "🔍  Retrieval-augmented generation (Gemini, HuggingFace)",
            "⚡  FastAPI backend · React frontend",
            "🐳  Fully containerized",
        ],
    },
    {
        "name": "GITA — GitHub Repo AI Agent",
        "url": None,
        "tagline": "Agent on the GitHub API, orchestrating many LLM calls.",
        "stack": ["Python", "LangChain", "FastAPI"],
        "highlights": [
            "🔗  GitHub API integration",
            "🧠  Gemini / Ollama orchestration",
            "⚡  FastAPI service layer",
        ],
    },
    {
        "name": "Jobs Data Warehouse",
        "url": None,
        "tagline": "Orchestrated pipeline with real-time monitoring.",
        "stack": ["Airflow", "PostgreSQL", "Grafana"],
        "highlights": [
            "🔁  Automated pipeline (Apache Airflow)",
            "📈  Real-time monitoring (Prometheus, Grafana)",
            "🗄️  PostgreSQL warehouse · React dashboard",
        ],
    },
    {
        "name": "Bitcoin Stream Pipeline",
        "url": None,
        "tagline": "High-throughput real-time crypto transactions.",
        "stack": ["Kafka", "Docker"],
        "highlights": [
            "📡  Live data ingestion at scale",
            "🔭  Built for observability",
            "🛠️  Microservices architecture",
        ],
    },
    {
        "name": "Car Sales Predictor",
        "url": "https://github.com/amineelgardoum-rgb/Prediction_Sales",
        "tagline": "ML forecasting system for automotive sales.",
        "stack": ["Python", "Scikit-learn"],
        "highlights": [
            "📊  Macroeconomic indicators",
            "🔬  Full EDA & feature engineering",
            "🏭  End-to-end deployment pipeline",
        ],
    },
    {
        "name": "Brain Tumor Classifier",
        "url": "https://github.com/amineelgardoum-rgb/tumor",
        "tagline": "Deep learning MRI scan classifier.",
        "stack": ["TensorFlow", "FastAPI"],
        "highlights": [
            "🖼️  Computer vision pipeline",
            "🎯  Tumor detection & classification",
            "⚡  FastAPI serving layer",
        ],
    },
]
```

---

## `education`

```python
EDUCATION = [
    {
        "school": "ENSA Al Hoceima",
        "degree": "Ingénierie des Données (Data Engineering)",
        "cohort": "Class of 2027",
        "status": "Final year, 2026 → 2027",
    },
]
```

---

## `certs`

```python
CERTS = [
    {
        "name": "MongoDB — SQL to Document Model",
        "issuer": "MongoDB",
        "focus": "NoSQL data modelling & aggregation",
        "url": "https://learn.mongodb.com/courses/relational-to-document-model",
    },
    {
        "name": "Understanding Cloud Computing",
        "issuer": "DataCamp",
        "focus": "Cloud fundamentals & service models",
        "url": "https://www.datacamp.com/courses/understanding-cloud-computing",
    },
    {
        "name": "Understanding Microsoft Azure",
        "issuer": "DataCamp",
        "focus": "Azure services & architecture basics",
        "url": "https://www.datacamp.com/courses/understanding-microsoft-azure",
    },
]
```

---

## `languages`

```python
LANGUAGES = {
    "Arabic":  "Native",
    "French":  "Fluent",
    "English": "Intermediate / Professional",
}
```

---

## `stats`

<div align="center">

<img src="https://raw.githubusercontent.com/amineelgardoum-rgb/amineelgardoum-rgb/main/profile-summary-card-output/radical/3-stats.svg" width="49%" alt="Total stars, repos, forks, issues, commits and pull requests"/>
<img src="https://raw.githubusercontent.com/amineelgardoum-rgb/amineelgardoum-rgb/main/profile-summary-card-output/radical/1-repos-per-language.svg" width="49%" alt="Languages across all public repositories"/>

<br/>

<img src="https://raw.githubusercontent.com/amineelgardoum-rgb/amineelgardoum-rgb/main/profile-summary-card-output/radical/2-most-commit-language.svg" width="24%" alt="Languages I actually commit in"/>
<img src="https://raw.githubusercontent.com/amineelgardoum-rgb/amineelgardoum-rgb/main/profile-summary-card-output/radical/4-productive-time.svg" width="24%" alt="Times of day I code most"/>
<a href="https://github.com/amineelgardoum-rgb">
  <img src="https://streak-stats.demolab.com/?user=amineelgardoum-rgb&theme=radical&hide_border=true" width="49%" alt="Contribution streak"/>
</a>

### `trophies`

<img src="https://raw.githubusercontent.com/amineelgardoum-rgb/amineelgardoum-rgb/main/assets/trophy.svg" width="100%" alt="GitHub trophies"/>

### `snake`

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/amineelgardoum-rgb/amineelgardoum-rgb/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/amineelgardoum-rgb/amineelgardoum-rgb/output/github-contribution-grid-snake.svg"/>
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/amineelgardoum-rgb/amineelgardoum-rgb/output/github-contribution-grid-snake.svg"/>
</picture>

<sub>
Cards and snake are generated and committed daily by
<a href="https://github.com/amineelgardoum-rgb/amineelgardoum-rgb/actions/workflows/snake.yml">workflows</a>
&mdash; no third-party image service involved.
</sub>

</div>

---

## `open_to`

```python
OPEN_TO = [
    "💼  Internships & entry-level roles",
    "🚀  Full-time Data / AI engineering positions",
    "🔧  Freelance data & automation projects",
    "🌍  Open-source collaboration",
]
```

<div align="center">

[![Email](https://img.shields.io/badge/Email-me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:amine.elgardoum@etu.uae.ac.ma)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amine-el-gardoum-491a82333)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF6B35?style=for-the-badge&logo=vercel&logoColor=white)](https://amine-s-portfolio.netlify.app/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/amineelgardoum-rgb)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&animation=twinkling"/>

*"Data is not just numbers — it's the language the world speaks when it doesn't know it's talking."*

</div>
