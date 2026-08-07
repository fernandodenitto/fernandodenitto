<h1 align="center">Fernando Denitto</h1>

<p align="center">
  Data platforms by day. Governance for AI agents by night.
</p>

<p align="center">
  <a href="https://www.fernandodenitto.me"><img src="https://img.shields.io/badge/website-fernandodenitto.me-0A0A0A?style=flat-square&logo=safari&logoColor=white" alt="Website"></a>
  <a href="https://linkedin.com/in/fernandodenitto"><img src="https://img.shields.io/badge/LinkedIn-fernandodenitto-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://docs.ontologiq.org"><img src="https://img.shields.io/badge/docs-ontologiq.org-4B32C3?style=flat-square&logo=readthedocs&logoColor=white" alt="Ontologiq docs"></a>
</p>

---

## 🛠 Building

### [Ontologiq](https://github.com/ontologiq/ontologiq) — governed actions for AI agents

An open-source compiler that turns business objects declared in YAML — identity, computed state, relations, governed actions — into **SQL views, a catalog, and MCP tools**.

Built on one guarantee: **an agent can propose an action, but can never approve or execute it on its own.** Preconditions re-evaluated at execution time, approvals signed by humans in a separate process, every step in an append-only audit log. It never writes to your database — effects are webhooks into your own systems.

```yaml
actions:
  cancel:
    requires: state == 'open'
    roles: [support]
    approval: required        # the agent only ever sees propose_order_cancel
```

`Apache 2.0` · `PyPI` · DuckDB / Postgres / MySQL / Databricks · `ontologiq import dbt`

---

## 👋 About

Global Data Engineer at **Prada Group** — I lead delivery of the Group's data platform on Databricks Lakehouse, serving Sales, Stock, Production and E-Commerce domains worldwide. Before that: observability lakehouses, multi-cloud metadata governance and financial-services data platforms at **Data Reply**.

The common thread: systems that don't fail silently — pipelines with observability built in, governance that's enforced rather than declared, and data products that move real decisions.

## ⚙️ Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Scala-DC322F?style=flat-square&logo=scala&logoColor=white" alt="Scala">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Spark">
  <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka">
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" alt="dbt">
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" alt="Databricks">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white" alt="OpenTelemetry">
  <img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black" alt="ClickHouse">
</p>

## 📍 Now

- 🏗 Growing **Ontologiq** toward real-world use cases — feedback and attempts to break the governance guarantees are welcome
- 🏢 Scaling a global lakehouse and the team behind it at Prada Group
- 📐 Thinking about the layer between "agents can read" and "agents can act"

---

<p align="center">
  <i>Optimizing a pipeline is satisfying — but the real value is in the ones that don't fail silently.</i>
</p>
