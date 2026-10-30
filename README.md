<p align="center">
  <img src="assets/banner.svg" alt="Jesús Salmerón — Data Engineer moving into DevOps & Cloud" width="100%"/>
</p>

<p align="center">
  <a href="https://salmerondevzone.github.io"><img src="https://img.shields.io/badge/Portfolio-salmerondevzone.github.io-161b22?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmZmZmIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iMTAiLz48cGF0aCBkPSJNMiAxMmgyME0xMiAyYTE1IDE1IDAgMCAxIDAgMjBNMTIgMmExNSAxNSAwIDAgMCAwIDIwIi8%2BPC9zdmc%2B" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/jesussalmeronarmario/"><img src="https://img.shields.io/badge/LinkedIn-jesussalmeronarmario-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTQuOTggMy41QzQuOTggNC44OCAzLjg3IDYgMi41IDZTMCA0Ljg4IDAgMy41IDEuMTIgMSAyLjUgMXMyLjQ4IDEuMTIgMi40OCAyLjV6TS41IDhoNHYxNmgtNFY4em03LjUgMGgzLjh2Mi4yaC4wNWMuNTMtMSAxLjg0LTIuMiAzLjgtMi4yIDQuMDYgMCA0LjggMi42NyA0LjggNi4xNVYyNGgtNHYtNy44YzAtMS44Ni0uMDMtNC4yNi0yLjYtNC4yNi0yLjYgMC0zIDIuMDMtMyA0LjEyVjI0aC00Vjh6Ii8%2BPC9zdmc%2B" alt="LinkedIn"/></a>
  <a href="mailto:jsalmedev@gmail.com"><img src="https://img.shields.io/badge/Email-jsalmedev%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

## 👋 About me

I'm a **Data Engineer at T-Systems Iberia**. I build the pipelines that turn raw, messy data into tables people can trust: ingestion, cleansing, data quality, dimensional models and the SQL on top, on **Microsoft Fabric**, **Spark** and **SQL Server / Oracle**.

Now I'm taking that into **DevOps & Platform Engineering**: the same mindset (automate it, test it, observe it) applied to infrastructure on **Azure**.

```yaml
# whoami.yaml
name: Jesús Salmerón
role: Data Engineer @ T-Systems Iberia
next: DevOps / Platform Engineering
data: [PySpark, Microsoft Fabric, SQL, Python, SSIS]
devops: [Azure, Terraform, Docker, Kubernetes, CI/CD]
motto: "If it isn't tested and automated, it isn't done."
```

## 🧪 What I do as a Data Engineer, with proof

Every claim links to code you can run.

| Skill | See it in action |
| --- | --- |
| **Medallion pipelines**: bronze → silver → gold, idempotent and incremental, with late-arriving corrections | [Insight_Horizon · pipeline](https://github.com/SalmeronDevZone/Insight_Horizon/tree/main/pipeline) |
| **Data quality**: validation rules, quarantine with every reason, quality reports | [Insight_Horizon](https://github.com/SalmeronDevZone/Insight_Horizon/tree/main/pipeline) · [Go data-quality CLI](https://github.com/SalmeronDevZone/PythonProjects/tree/main/Go/Proyecto%20Final) |
| **Advanced SQL**: window functions, gaps & islands, sessionization, upserts, SCD type 2, recursive CTEs | [snake-data-lair · 13 auto-graded exercises](https://github.com/SalmeronDevZone/snake-data-lair/tree/main/ejercicios) |
| **SQL across engines**: T-SQL, PL/SQL, MySQL, SQLite and a star schema for a Fabric warehouse | [snake-data-lair · SQL](https://github.com/SalmeronDevZone/snake-data-lair/tree/main/SQL) |
| **Spark on a Lakehouse**: explicit schemas, partitioned Parquet, Delta tables, Spark SQL | [PythonProjects · FABRIC](https://github.com/SalmeronDevZone/PythonProjects/tree/main/FABRIC) |
| **Python for data**: pandas, generators, CDC, retries with backoff, API pagination, idempotent ingestion | [PythonProjects · exercises](https://github.com/SalmeronDevZone/PythonProjects/tree/main/ejercicios) |
| **Engineering habits**: tests and CI in every repository, Git workflows | [Git labs](https://github.com/SalmeronDevZone/GitHub/tree/main/ejercicios) · the green badges in each README |

## 🚀 Featured work

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/SalmeronDevZone/Insight_Horizon"><img src="assets/pipeline.svg" alt="Medallion ETL pipeline: raw, bronze, silver, quarantine and gold star schema"/></a>
      <h3><a href="https://github.com/SalmeronDevZone/Insight_Horizon">🌌 Insight_Horizon</a></h3>
      <p><b>From raw files to trusted data.</b> A medallion ETL pipeline that cleans dirty CSVs, quarantines bad rows with their reasons and loads a star schema. Idempotent, incremental, 13 tests and CI that publishes a data-quality report. Plus 8 production-style challenges.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
        <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite"/>
        <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/SalmeronDevZone/snake-data-lair"><img src="assets/sql-lab.svg" alt="SQL exercises with an automatic grader"/></a>
      <h3><a href="https://github.com/SalmeronDevZone/snake-data-lair">🐍 snake-data-lair</a></h3>
      <p><b>SQL for data engineers.</b> Five engines, PL/SQL, a Fabric star schema and 22 auto-graded exercises (13 SQL + 9 pandas): deduplicating loads, gaps &amp; islands, sessionization, data-quality checks, SCD type 2.</p>
      <p>
        <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL"/>
        <img src="https://img.shields.io/badge/Oracle%20PL%2FSQL-F80000?style=flat-square" alt="Oracle PL/SQL"/>
        <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/SalmeronDevZone/azure-lab"><img src="https://raw.githubusercontent.com/SalmeronDevZone/azure-lab/main/docs/capturas/portal-cloud-shell.png" alt="Azure Lab: Azure portal and Cloud Shell"/></a>
      <h3><a href="https://github.com/SalmeronDevZone/azure-lab">☁️ Azure Lab</a> <sub>· the DevOps step</sub></h3>
      <p><b>A private Azure to learn DevOps</b>: no account, no bill. Azure portal, Cloud Shell (<code>az</code>, <code>kubectl</code>, <code>terraform</code>, <code>git</code>, <code>docker</code>), Azure DevOps with YAML pipelines and a 13-level academy with 47 self-grading labs. Runs in Docker: <code>docker compose up -d --build</code>.</p>
      <p>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <a href="https://salmerondevzone.github.io"><img src="assets/portfolio.png" alt="Jurassic Park DevOps Edition portfolio"/></a>
      <h3><a href="https://salmerondevzone.github.io">🦖 Jurassic Park · DevOps Edition</a></h3>
      <p><b>My portfolio as a retro game</b>: the park's ops division keeping Isla Nublar online with Terraform, Kubernetes and Azure, built on a data-engineering past. Character sheet, stack inventory, missions map and a blameless post-mortem boss fight.</p>
      <p>
        <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5"/>
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
        <img src="https://img.shields.io/badge/GitHub%20Pages-222222?style=flat-square&logo=githubpages&logoColor=white" alt="GitHub Pages"/>
      </p>
    </td>
  </tr>
</table>

## 🧰 Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,postgres,mysql,sqlite,go,java&perline=10" alt="Python, PostgreSQL, MySQL, SQLite, Go, Java"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=azure,terraform,docker,kubernetes,githubactions,linux,bash,git,prometheus,grafana&perline=10" alt="Azure, Terraform, Docker, Kubernetes, GitHub Actions, Linux, Bash, Git, Prometheus, Grafana"/>
</p>

| Area | Tools |
| --- | --- |
| 🧪 **Data engineering** | PySpark · Microsoft Fabric (Lakehouse, Data Factory, Warehouse) · Delta · SSIS · dimensional modeling · data quality |
| 🗄️ **SQL** | T-SQL (SQL Server) · PL/SQL (Oracle) · MySQL · PostgreSQL · SQLite |
| 🐍 **Languages** | Python (pandas, NumPy) · SQL · Go · Java · C# · Kotlin |
| ☁️ **Cloud & IaC** | Azure · Terraform · Key Vault · Entra ID |
| 📦 **Containers & CI/CD** | Docker · Kubernetes (AKS) · Helm · Argo CD · Azure DevOps · GitHub Actions |
| 📈 **Observability** | Prometheus · Grafana · Azure Monitor |

## 🗂️ All repositories

| Repository | What's inside |
| --- | --- |
| [Insight_Horizon](https://github.com/SalmeronDevZone/Insight_Horizon) | Medallion ETL pipeline with tests and CI, 8 challenges, analysis notebooks |
| [snake-data-lair](https://github.com/SalmeronDevZone/snake-data-lair) | SQL across five engines, PL/SQL, 22 auto-graded SQL and pandas exercises |
| [PythonProjects](https://github.com/SalmeronDevZone/PythonProjects) | 10 Python data-engineering exercises, PySpark on Fabric, a Go data-quality CLI and a Go-for-data course |
| [azure-lab](https://github.com/SalmeronDevZone/azure-lab) | Local Azure simulator to learn DevOps: portal, Cloud Shell, Azure DevOps and 47 labs |
| [GitHub](https://github.com/SalmeronDevZone/GitHub) | 10 auto-graded Git labs, a Git cheat sheet and a guide for HR |
| [bits-and-bytes](https://github.com/SalmeronDevZone/bits-and-bytes) | Layered C# apps with stored procedures, Java and Kotlin, 8 Java-for-data exercises |

## 🤝 Let's connect

Happy to talk about data pipelines, SQL, Spark and Fabric, or about the road from data engineering to DevOps.

<p>
  <a href="https://www.linkedin.com/in/jesussalmeronarmario/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTQuOTggMy41QzQuOTggNC44OCAzLjg3IDYgMi41IDZTMCA0Ljg4IDAgMy41IDEuMTIgMSAyLjUgMXMyLjQ4IDEuMTIgMi40OCAyLjV6TS41IDhoNHYxNmgtNFY4em03LjUgMGgzLjh2Mi4yaC4wNWMuNTMtMSAxLjg0LTIuMiAzLjgtMi4yIDQuMDYgMCA0LjggMi42NyA0LjggNi4xNVYyNGgtNHYtNy44YzAtMS44Ni0uMDMtNC4yNi0yLjYtNC4yNi0yLjYgMC0zIDIuMDMtMyA0LjEyVjI0aC00Vjh6Ii8%2BPC9zdmc%2B" alt="LinkedIn"/></a>
  <a href="mailto:jsalmedev@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://salmerondevzone.github.io"><img src="https://img.shields.io/badge/Portfolio-161b22?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmZmZmIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iMTAiLz48cGF0aCBkPSJNMiAxMmgyME0xMiAyYTE1IDE1IDAgMCAxIDAgMjBNMTIgMmExNSAxNSAwIDAgMCAwIDIwIi8%2BPC9zdmc%2B" alt="Portfolio"/></a>
  <a href="https://kaggle.com/jesssalmern"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle"/></a>
  <a href="https://leetcode.com/mrsaylar"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
</p>

<p align="center"><sub>⭐ If any of these repositories helps you learn, a star is always appreciated.</sub></p>
