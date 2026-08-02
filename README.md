<!-- ░▒▓  animated matrix + glitch hero (self-hosted SVG, animates on GitHub)  ▓▒░ -->
<div align="center">
  <a href="https://github.com/syukrifadzil">
    <img src="https://raw.githubusercontent.com/syukrifadzil/syukrifadzil/main/assets/hero.svg?v=1" width="100%" alt="Syukri Fadzil — Data Engineer"/>
  </a>
</div>

<div align="center">

![Kuala Lumpur](https://img.shields.io/badge/📍_Kuala_Lumpur-0d1117?style=flat-square&labelColor=0d1117&color=00d9ff)
![Profile Views](https://komarev.com/ghpvc/?username=syukrifadzil&style=flat-square&color=00ff88&label=visitors)
[![Followers](https://img.shields.io/github/followers/syukrifadzil?style=flat-square&color=00ff88&labelColor=0d1117&label=followers)](https://github.com/syukrifadzil?tab=followers)
[![Say hi](https://img.shields.io/badge/say_hi-→-ff2e6e?style=flat-square&labelColor=0d1117)](mailto:msyukri_mf@yahoo.com)

</div>

<br/>

## 👋 Hey, I'm Syukri

I'm a **data engineer** in Kuala Lumpur. My day job is the unglamorous plumbing that keeps a cloud **data lake** alive — moving raw data through `transform → conform → enrich` until it's clean enough that people actually trust it in a dashboard.

Off the clock I build things that scratch an itch: a forecasting model here, a stock-monitoring app there, a food app for when my friends and I can't decide where to eat. Honestly, half of them will never make a cent. I build them anyway, because that's how I learn the fun stuff — ML, time-series, shipping real apps.

```console
syukri@kl ~ % whoami
> data engineer by day, builder by night
> i turn messy data into pipelines, then pipelines into dashboards people trust
> currently obsessed with time-series forecasting & brutally honest ML
```

<div align="center"><img src="https://raw.githubusercontent.com/syukrifadzil/syukrifadzil/main/assets/matrix-divider.svg?v=1" width="100%" alt=""/></div>

## ⭐ Stuff I've built that I'm actually proud of

### 🛒 [store-sales-forecasting](https://github.com/syukrifadzil/store-sales-forecasting)

[![top language](https://img.shields.io/github/languages/top/syukrifadzil/store-sales-forecasting?style=flat-square&color=00d9ff&labelColor=0d1117)](https://github.com/syukrifadzil/store-sales-forecasting)
[![last commit](https://img.shields.io/github/last-commit/syukrifadzil/store-sales-forecasting?style=flat-square&color=00ff88&labelColor=0d1117)](https://github.com/syukrifadzil/store-sales-forecasting/commits)
[![stars](https://img.shields.io/github/stars/syukrifadzil/store-sales-forecasting?style=flat-square&logo=github&color=00ff88&labelColor=0d1117)](https://github.com/syukrifadzil/store-sales-forecasting/stargazers)
![CV RMSLE](https://img.shields.io/badge/CV_RMSLE-0.3855-ff2e6e?style=flat-square&labelColor=0d1117)

My take on the Kaggle **Store Sales** competition. Instead of training 1,782 tiny models, I trained **one global LightGBM** across every store-and-product series at once, with lag features that are careful not to peek into the future. I wrote it to be *read*, not just run — the docstrings explain the *why*. If you're learning time-series, this is a good place to poke around.

> ⭐ Star it if you like clean, well-documented ML.

### 📈 [Pantau](https://github.com/syukrifadzil/stock-ml-monitor-dist) &nbsp;<sub>*(pantau = "to monitor" in Malay)*</sub>

[![release](https://img.shields.io/github/v/release/syukrifadzil/stock-ml-monitor-dist?style=flat-square&label=release&color=00ff88&labelColor=0d1117)](https://github.com/syukrifadzil/stock-ml-monitor-dist/releases/latest)
![platforms](https://img.shields.io/badge/macOS_·_Windows_·_Linux-0d1117?style=flat-square&color=00d9ff&labelColor=0d1117)
[![last commit](https://img.shields.io/github/last-commit/syukrifadzil/stock-ml-monitor-dist?style=flat-square&color=00d9ff&labelColor=0d1117)](https://github.com/syukrifadzil/stock-ml-monitor-dist/commits)
![honest](https://img.shields.io/badge/signals-brutally_honest-ff2e6e?style=flat-square&labelColor=0d1117)

A desktop app that watches a **Bursa Malaysia** price-direction model — and it's stubbornly honest. Every signal sits right next to the accuracy it would *need* to be worth trading, and the app will tell you to your face when the edge just isn't there. A research tool, not a hype machine. Installers for all three platforms are in **Releases**.

> 💾 macOS · Windows · Linux — grab the latest build and try it.

<div align="center"><img src="https://raw.githubusercontent.com/syukrifadzil/syukrifadzil/main/assets/matrix-divider.svg?v=1" width="100%" alt=""/></div>

## 🧪 On my workbench right now

A few things not quite ready for the world yet:

```text
🍜  makan-app ........... a KL food-discovery app, for the eternal "where do we eat?" debate
🛰️  personal-risk-radar . a personal-finance early-warning system
📊  stock-ml-monitor ..... the research engine that feeds Pantau
```

<sub>Private for now — follow along and you'll catch them the moment they go public.</sub>

<div align="center"><img src="https://raw.githubusercontent.com/syukrifadzil/syukrifadzil/main/assets/matrix-divider.svg?v=1" width="100%" alt=""/></div>

## 🛠️ What I actually do all day

Picture a data lake as a line of filters, each one making the data a little cleaner and more useful:

```mermaid
flowchart LR
    A["raw"] --> B["transform"] --> C["conform"] --> D["enrich"] --> E["serve → Power BI"]
    style A fill:#0d1117,stroke:#ff2e6e,color:#e6f1ff
    style B fill:#0d1117,stroke:#00d9ff,color:#e6f1ff
    style C fill:#0d1117,stroke:#00d9ff,color:#e6f1ff
    style D fill:#0d1117,stroke:#00d9ff,color:#e6f1ff
    style E fill:#0d1117,stroke:#00ff88,color:#e6f1ff
```

I build and babysit those stages: **watermark-driven loads** so nothing gets processed twice, **Glue / PySpark** for the heavy lifting, **Step Functions + Lambda** to orchestrate it, **Athena** to query it, and **Power BI** on top so the business sees numbers they can trust. When two feeds disagree, I'm the one doing the record-by-record detective work to find out why.

### The toolbox

![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=00d9ff)
![SQL](https://img.shields.io/badge/SQL-0d1117?style=for-the-badge&logo=amazonredshift&logoColor=00ff88)
![PySpark](https://img.shields.io/badge/PySpark-0d1117?style=for-the-badge&logo=apachespark&logoColor=E25A1C)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=for-the-badge&logo=typescript&logoColor=3178C6)
<br/>
![AWS Glue](https://img.shields.io/badge/Glue-0d1117?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)
![Athena](https://img.shields.io/badge/Athena-0d1117?style=for-the-badge&logo=amazonwebservices&logoColor=00d9ff)
![Step Functions](https://img.shields.io/badge/Step_Functions-0d1117?style=for-the-badge&logo=amazonwebservices&logoColor=ff2e6e)
![Lambda](https://img.shields.io/badge/Lambda-0d1117?style=for-the-badge&logo=awslambda&logoColor=FF9900)
![S3](https://img.shields.io/badge/S3-0d1117?style=for-the-badge&logo=amazons3&logoColor=569A31)
![DynamoDB](https://img.shields.io/badge/DynamoDB-0d1117?style=for-the-badge&logo=amazondynamodb&logoColor=4053D6)
<br/>
![pandas](https://img.shields.io/badge/pandas-0d1117?style=for-the-badge&logo=pandas&logoColor=00d9ff)
![LightGBM](https://img.shields.io/badge/LightGBM-0d1117?style=for-the-badge&logo=leaflet&logoColor=00ff88)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0d1117?style=for-the-badge&logo=scikitlearn&logoColor=F7931E)
![Power BI](https://img.shields.io/badge/Power_BI-0d1117?style=for-the-badge&logo=powerbi&logoColor=F2C811)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=2496ED)

<div align="center"><img src="https://raw.githubusercontent.com/syukrifadzil/syukrifadzil/main/assets/matrix-divider.svg?v=1" width="100%" alt=""/></div>

## 🐍 My commits, eaten by a snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/syukrifadzil/syukrifadzil/output/github-snake-dark.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/syukrifadzil/syukrifadzil/output/github-snake.svg" />
</picture>

<br/><br/>

<img src="https://raw.githubusercontent.com/syukrifadzil/syukrifadzil/main/assets/terminal.svg?v=1" width="100%" alt="status readout"/>

</div>

<div align="center"><img src="https://raw.githubusercontent.com/syukrifadzil/syukrifadzil/main/assets/matrix-divider.svg?v=1" width="100%" alt=""/></div>

## 📡 Come say hi

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://linkedin.com/in/syukrifadzil)
[![Email](https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:msyukri_mf@yahoo.com)
[![Projects](https://img.shields.io/badge/Browse_my_repos-0d1117?style=for-the-badge&logo=github&logoColor=00ff88)](https://github.com/syukrifadzil?tab=repositories)

<br/>

<sub>Thanks for scrolling this far. Pick a project up top and poke around — and if you're building something in data or ML, my inbox is open. 🟢</sub>

</div>
