# Vitor Yuske Watanabe

**Analytics Engineer · Data Engineer · Data Analyst**<br>
Campo Grande, Brazil · [LinkedIn](https://www.linkedin.com/in/vitor-yuske/)

Analytics Engineer and Data Analyst with a Computer Engineering background. I work across ingestion, transformation, orchestration, and BI, mainly with Python, SQL, dbt, Airflow, Qlik, and cloud data platforms. I care about data quality, reproducibility, and making data useful for decisions.

Currently working with analytics engineering, data analysis, and BI at Aderência.

## Stack

| Area | Stack |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/python-%233670A0.svg?style=flat-square&logo=python&logoColor=ffdd54) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square) ![PL/SQL](https://img.shields.io/badge/PL%2FSQL-F80000?style=flat-square) |
| **Data engineering** | ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square) ![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-%23017CEE.svg?style=flat-square&logo=Apache%20Airflow&logoColor=white) ![ClickHouse](https://img.shields.io/badge/ClickHouse-%23FFCC01.svg?style=flat-square&logo=clickhouse&logoColor=black) ![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white) ![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=flat-square) ![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square&logo=apache&logoColor=white) ![API REST](https://img.shields.io/badge/API%20REST-005571?style=flat-square) |
| **Analytics & BI** | ![Qlik](https://img.shields.io/badge/Qlik-009848?style=flat-square&logo=qlik&logoColor=white) ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square) ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square) ![Alteryx](https://img.shields.io/badge/Alteryx-0078C0?style=flat-square) ![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=flat-square&logo=streamlit&logoColor=white) |
| **Data & ML** | ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat-square&logo=numpy&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat-square&logo=scikit-learn&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Jupyter](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=flat-square&logo=jupyter&logoColor=white) |
| **AI & automation** | ![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=claude&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white) ![LLMs/RAG](https://img.shields.io/badge/LLMs%20%2F%20RAG-6B7280?style=flat-square) ![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=flat-square) ![Power Apps](https://img.shields.io/badge/Power%20Apps-742774?style=flat-square) |
| **Platform & engineering** | ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat-square&logo=github&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=flat-square&logo=githubactions&logoColor=white) ![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) |

## How I work

I build data products in layers: land the raw data, transform it into tested models, and ship it to the people who use it. I aim for each layer to have a clear purpose, a test, and a consumer.

```mermaid
flowchart LR
  subgraph Sources
    A1[APIs]
    A2[Files]
    A3[Databases]
  end
  subgraph Ingestion
    B[Airflow + Python]
  end
  subgraph Storage
    C[S3 / BigQuery / ClickHouse]
  end
  subgraph Transformation
    D[dbt + SQL tests]
  end
  subgraph Serving
    E[Qlik / Power BI / Streamlit]
  end
  A1 --> B
  A2 --> B
  A3 --> B
  B --> C
  C --> D
  D --> E
```

<div align="center">

<table align="center">
  <thead>
    <tr>
      <th align="center">Principle</th>
      <th align="center">In practice</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">Correctness</td>
      <td align="center">Tests, contracts, reconciliation</td>
    </tr>
    <tr>
      <td align="center">Reproducibility</td>
      <td align="center">Versioned SQL, dbt, containerized jobs</td>
    </tr>
    <tr>
      <td align="center">Usability</td>
      <td align="center">Documented marts, clear metrics, BI handoff</td>
    </tr>
  </tbody>
</table>

</div>

## Focus

- Build and maintain batch/ELT pipelines with clear ownership and tests.
- Model analytics data with dbt and document assumptions.
- Turn data into BI products that people actually use.
- Automate manual data work and improve data quality.

## GitHub activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=vyuske&theme=github_dark">
    <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=vyuske&theme=github">
    <img alt="GitHub stats for vyuske" height="150" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=vyuske&theme=github">
  </picture>
</p>

## Contact

<a href="https://www.linkedin.com/in/vitor-yuske/">
  <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white">
</a>
