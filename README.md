<div align="center">

<!-- ═══════════════ HEADER ═══════════════ -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3500&pause=800&color=00D9FF&center=true&vCenter=true&width=820&height=80&lines=Data+Engineer;Kuala+Lumpur+based+%7C+AWS+Data+Lakes;I+turn+messy+data+into+pipelines...;...then+build+ML+side-projects+for+fun" alt="Typing SVG" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00d9ff,100:00ff88&height=180&section=header&text=&fontSize=0&animation=twinkling" width="100%"/>

<!-- ═══════════════ BADGES ═══════════════ -->
[![Location](https://img.shields.io/badge/Kuala_Lumpur-🇲🇾-00d9ff?style=for-the-badge&labelColor=0d1117)](https://github.com/syukrifadzil)
![Profile Views](https://komarev.com/ghpvc/?username=syukrifadzil&style=for-the-badge&color=00d9ff&labelColor=0d1117)
[![GitHub followers](https://img.shields.io/github/followers/syukrifadzil?style=for-the-badge&color=00ff88&labelColor=0d1117)](https://github.com/syukrifadzil?tab=followers)
[![Open to collab](https://img.shields.io/badge/Open_to-Collaboration-00ff88?style=for-the-badge&labelColor=0d1117)](mailto:msyukri_mf@yahoo.com)

</div>

---

## 🌌 `whoami`

```python
class DataEngineer:
    def __init__(self):
        self.name  = "Syukri Fadzil"
        self.role  = "Data Engineer"
        self.base  = "Kuala Lumpur, Malaysia 🇲🇾"
        self.focus = "Cloud data lakes on AWS  ->  Power BI"

    @property
    def day_job(self):
        # raw -> transform -> conform -> enrich -> serve
        return "I build the layers of a data lake and the pipelines between them"

    @property
    def after_hours(self):
        return ["time-series ML", "quant research", "shipping small apps"]

    def philosophy(self):
        return "Without data, you're just another person with an opinion."
```

---

## ⭐ `featured_projects` — the stuff I'm proud of

<div align="center">

<a href="https://github.com/syukrifadzil/store-sales-forecasting">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=syukrifadzil&repo=store-sales-forecasting&theme=transparent&hide_border=true&title_color=00d9ff&text_color=c9d1d9&icon_color=00ff88&bg_color=0d1117" />
</a>
<a href="https://github.com/syukrifadzil/stock-ml-monitor-dist">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=syukrifadzil&repo=stock-ml-monitor-dist&theme=transparent&hide_border=true&title_color=00d9ff&text_color=c9d1d9&icon_color=00ff88&bg_color=0d1117" />
</a>

</div>

**🛒 [store-sales-forecasting](https://github.com/syukrifadzil/store-sales-forecasting)** — my Kaggle *Store Sales* solution. One **global LightGBM** model across **1,782** store×family time series, leakage-safe lag features, and honest baselines. **CV RMSLE 0.3855.** Written to be *read* as much as run — the docstrings explain the *why*, not just the *what*.
> ⭐ Star it if you like clean, well-documented ML.

**📈 [Pantau](https://github.com/syukrifadzil/stock-ml-monitor-dist)** *(pantau = "to monitor" in Malay)* — a cross-platform desktop dashboard for a **Bursa Malaysia** price-direction research model. What makes it different: it puts every signal next to the accuracy it would *need* to be worth trading, and **tells you honestly when it has no edge.** Transparency over hype.
> 💾 Cross-platform installers live in **Releases** (macOS · Windows · Linux).

---

## 🧪 `in_the_lab` — currently cooking

```text
🍜  makan-app ............ a KL food-discovery app (TypeScript / React)
🛰️  personal-risk-radar .. a personal-finance risk radar (Python)
📊  stock-ml-monitor ..... the research engine behind Pantau
```
<sub>Private for now — public write-ups coming. Follow to catch them when they drop.</sub>

---

## 🛠️ `what_i_actually_do` — data-lake engineering

<div align="center">

| Layer | I build & own |
|:--|:--|
| 🌊 **Ingest** | `raw` landing + **watermark-driven incremental loads** (DynamoDB high-watermarks) so pipelines only touch new data |
| ⚙️ **Process** | `transform -> conform -> enrich` in **Glue / PySpark**, orchestrated by **Step Functions + Lambda** |
| 🔎 **Serve** | curated, query-fast datasets in **Athena** feeding **Power BI** dashboards |
| 🧭 **Keep it honest** | reconciliation, record-by-record comparisons, and root-cause digging when feeds disagree |

</div>

---

## ⚡ `tech_stack`

<div align="center">

### Languages
![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=00d9ff)
![SQL](https://img.shields.io/badge/SQL-0d1117?style=for-the-badge&logo=amazonredshift&logoColor=00ff88)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=for-the-badge&logo=typescript&logoColor=3178C6)
![Bash](https://img.shields.io/badge/Bash-0d1117?style=for-the-badge&logo=gnubash&logoColor=4EAA25)

### Data &amp; ML
![pandas](https://img.shields.io/badge/pandas-0d1117?style=for-the-badge&logo=pandas&logoColor=00d9ff)
![NumPy](https://img.shields.io/badge/NumPy-0d1117?style=for-the-badge&logo=numpy&logoColor=4DABCF)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0d1117?style=for-the-badge&logo=scikitlearn&logoColor=F7931E)
![LightGBM](https://img.shields.io/badge/LightGBM-0d1117?style=for-the-badge&logo=leaflet&logoColor=00ff88)
![PySpark](https://img.shields.io/badge/PySpark-0d1117?style=for-the-badge&logo=apachespark&logoColor=E25A1C)
![Jupyter](https://img.shields.io/badge/Jupyter-0d1117?style=for-the-badge&logo=jupyter&logoColor=F37626)

### AWS Data Platform
![Amazon S3](https://img.shields.io/badge/S3-0d1117?style=for-the-badge&logo=amazons3&logoColor=569A31)
![AWS Glue](https://img.shields.io/badge/Glue-0d1117?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)
![Athena](https://img.shields.io/badge/Athena-0d1117?style=for-the-badge&logo=amazonwebservices&logoColor=00d9ff)
![Step Functions](https://img.shields.io/badge/Step_Functions-0d1117?style=for-the-badge&logo=amazonwebservices&logoColor=FF4F8B)
![AWS Lambda](https://img.shields.io/badge/Lambda-0d1117?style=for-the-badge&logo=awslambda&logoColor=FF9900)
![DynamoDB](https://img.shields.io/badge/DynamoDB-0d1117?style=for-the-badge&logo=amazondynamodb&logoColor=4053D6)

### Analytics &amp; Apps
![Power BI](https://img.shields.io/badge/Power_BI-0d1117?style=for-the-badge&logo=powerbi&logoColor=F2C811)
![Electron](https://img.shields.io/badge/Electron-0d1117?style=for-the-badge&logo=electron&logoColor=47848F)
![React](https://img.shields.io/badge/React-0d1117?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-0d1117?style=for-the-badge&logo=nodedotjs&logoColor=5FA04E)

### Tooling
![Docker](https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=2496ED)
![Git](https://img.shields.io/badge/Git-0d1117?style=for-the-badge&logo=git&logoColor=F05032)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0d1117?style=for-the-badge&logo=githubactions&logoColor=2088FF)
![Linux](https://img.shields.io/badge/Linux-0d1117?style=for-the-badge&logo=linux&logoColor=FCC624)

</div>

---

## 🐍 `contribution_matrix`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/syukrifadzil/syukrifadzil/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/syukrifadzil/syukrifadzil/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/syukrifadzil/syukrifadzil/output/github-snake-dark.svg" />
</picture>

</div>

---

## 📊 `system_metrics`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=syukrifadzil&show_icons=true&theme=transparent&hide_border=true&title_color=00d9ff&text_color=c9d1d9&icon_color=00ff88&bg_color=0d1117" height="170"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=syukrifadzil&theme=transparent&hide_border=true&stroke=00d9ff&ring=00ff88&fire=00d9ff&currStreakLabel=00d9ff&sideLabels=c9d1d9&currStreakNum=00ff88&dates=888888&background=0d1117" height="170"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=syukrifadzil&layout=compact&theme=transparent&hide_border=true&title_color=00d9ff&text_color=c9d1d9&bg_color=0d1117&langs_count=8" height="165"/>

</div>

---

## 🏆 `achievements`

<div align="center">

![Trophies](https://github-profile-trophy.vercel.app/?username=syukrifadzil&theme=darkhub&no-frame=true&no-bg=true&column=7&margin-w=15&margin-h=15)

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=syukrifadzil&theme=react-dark&hide_border=true&bg_color=0d1117&color=00d9ff&line=00ff88&point=00d9ff&area=true&area_color=00d9ff)](https://github.com/syukrifadzil)

</div>

---

## 🔗 `connect`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://linkedin.com/in/syukrifadzil)
[![Email](https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:msyukri_mf@yahoo.com)
[![Kaggle](https://img.shields.io/badge/Kaggle-0d1117?style=for-the-badge&logo=kaggle&logoColor=20BEFF)](https://github.com/syukrifadzil/store-sales-forecasting)

</div>

<div align="center">

```
"The goal is to turn data into information, and information into insight."
                                                    — Carly Fiorina
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff88,50:00d9ff,100:0d1117&height=120&section=footer&animation=twinkling" width="100%"/>

<sub>⚡ Thanks for stopping by — pick a project above and dive in.</sub>

</div>
