<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,1,2&height=180&section=header&gradientColors=FF9933,FFFFFF,138808&text=Lok%20Sabha%202024&fontSize=48&fontColor=1a1a2e&animation=twinkling" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=800&size=22&duration=3000&pause=1000&color=FF9933&center=true&vCenter=true&repeat=true&width=900&height=60&lines=18th+LOK+SABHA+%E2%80%94+CONSTITUENCY+DATA+ANALYSIS;543+SEATS+%7C+ALL+RECOGNIZED+PARTIES;PANDAS+%7C+NUMPY+%7C+MATPLOTLIB+%7C+SEABORN" alt="Typing SVG" />

<br/><br/>

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)](https://seaborn.pydata.org/)

<img src="https://img.shields.io/badge/_Constituencies-543-FF9933?style=flat-square&labelColor=1a1a2e"/>&nbsp;<img src="https://img.shields.io/badge/_Election_Year-2024-138808?style=flat-square&labelColor=1a1a2e"/>&nbsp;<img src="https://img.shields.io/badge/_Lok_Sabha-18th-navy?style=flat-square&labelColor=1a1a2e"/>&nbsp;<img src="https://img.shields.io/badge/_Status-Government_Formed-gold?style=flat-square&labelColor=1a1a2e"/>

</div>

<br/>
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=gradient&customColorList=0,1,2&gradientColors=FF9933,FFFFFF,138808" width="100%"/>
<br/>

A constituency-level data analysis of the 2024 Indian General Election, covering all 543 Lok Sabha seats. The project examines party performance, victory margins, candidate competitiveness, and regional voting patterns using Python's standard data science stack.

---

## Table of Contents

- [Overview](#overview)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Party Directory — 18th Lok Sabha](#party-directory--18th-lok-sabha)
- [Methodology](#methodology)
- [Analysis & Visualizations](#analysis--visualizations)
  - [Party-Wise Seat Distribution](#party-wise-seat-distribution)
  - [Party Performance](#party-performance)
  - [Candidate Vote Share Comparison](#candidate-vote-share-comparison)
  - [Margin of Victory](#margin-of-victory)
  - [Top Winning Margins](#top-winning-margins)
  - [Runner-Up (Trailing) Analysis](#runner-up-trailing-analysis)
  - [Regional Performance](#regional-performance)
- [Key Findings](#key-findings)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Future Scope](#future-scope)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This project analyzes the results of the 2024 Lok Sabha (Indian General Election) at the constituency level. It transforms raw election data into structured insights on:

- Party-wise seat performance across all 543 constituencies
- Victory margins and electoral competitiveness
- Candidate-level vote share comparisons
- Runner-up performance and near-win contests
- Regional and state-level voting trends

The goal is to provide a clear, data-driven view of constituency outcomes without making predictive or political claims beyond what the dataset supports.

## Objectives

**Electoral Analysis**
- Analyze constituency-wise outcomes
- Evaluate winning party performance and seat share
- Measure victory margins and electoral competitiveness

**Political Intelligence**
- Compare performance across parties
- Identify regional strongholds and closely contested seats
- Examine voting patterns by state/region

**Data Exploration**
- Constituency-level insights and result verification
- Margin distribution analysis
- Candidate-level (winner vs. runner-up) comparisons

## Dataset

| Field | Description |
|---|---|
| `Constituency` | Parliamentary constituency name |
| `Const. No.` | Unique constituency identifier |
| `Leading Candidate` | Winning candidate |
| `Leading Party` | Winning party |
| `Trailing Candidate` | Runner-up candidate |
| `Trailing Party` | Runner-up party |
| `Margin` | Victory margin (votes) |
| `Status` | Result status |

**Snapshot**

| Metric | Value |
|---|---|
| Election Year | 2024 |
| Total Constituencies | 543 |
| Granularity | Constituency-level |
| Coverage | All states and union territories |

> Source the raw data file path/link here, e.g. `data/lok_sabha_2024_results.csv`, and note its provenance (e.g. Election Commission of India) so results are reproducible and verifiable.

---

## Party Directory — 18th Lok Sabha

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=700&size=24&pause=2000&color=FF9933&center=true&vCenter=true&width=900&height=60&lines=🇮🇳+ALL+PARTIES+WITH+SEATS+IN+THE+18th+LOK+SABHA;543+SEATS+%E2%80%A2+RESULTS+DECLARED+4+JUNE+2024" alt="Party Directory Header"/>
</div>

<br/>

<div align="center">

<img src="https://img.shields.io/badge/_Recognized_Parties-30-FF9933?style=for-the-badge&labelColor=1a1a2e"/>

</div>

Party symbols as recognized by the Election Commission of India for the 18th Lok Sabha.
![Parties](https://github.com/geershatisaxena/Election-Result-Analysis/blob/main/chartSeatShare%20(1).png)



> **Adding logos:** drop each party's official logo image (PNG/SVG, ideally square, ~40×40px) into `images/parties/` using the filename shown in the `Logo file` column below, then it will render automatically in the `Logo` column. Official party symbols/emblems are trademarked by the respective parties and the Election Commission of India — source them from each party's official website or the [ECI's recognized symbols list](https://github.com/geershatisaxena/Election-Result-Analysis/blob/main/chartSeatShare%20(1).png) and use in accordance with applicable trademark/usage guidelines. This repo does not ship third-party logo files.

<br/>

<div align="center">

| Logo | Party Name | MPs | Logo | Party Name | MPs | Logo | Party Name | MPs | Logo | Party Name | MPs | Logo | Party Name | MPs |
|------|------------|-----|------|------------|-----|------|------------|-----|------|------------|-----|------|------------|-----|
| <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQz8WpbcEda7F_akG1tqLmK1zwVIBhsi__Bi8N-y5VQbA&s=10" width="32"/> | Bharatiya Janata Party (BJP) | 240 | <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR0BjhE24n6IDg4wUDDSmxhUVAPvhAb0VCkWQ0nV1fmqA&s=10" width="32"/> | Indian National Congress (INC) | 99 | <img src="data:image/png;base64,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" width="32"/> | Samajwadi Party (SP) | 37 | <img src="images/parties/aitc.png" width="32"/> | All India Trinamool Congress (AITC) | 29 | <img src="images/parties/dmk.png" width="32"/> | Dravida Munnetra Kazhagam (DMK) | 22 |
| <img src="images/parties/tdp.png" width="32"/> | Telugu Desam Party (TDP) | 16 | <img src="images/parties/jdu.png" width="32"/> | Janata Dal (United) (JD(U)) | 12 | <img src="images/parties/ssubt.png" width="32"/> | Shiv Sena (UBT) | 9 | <img src="images/parties/ncpsp.png" width="32"/> | NCP (Sharadchandra Pawar) | 8 | <img src="images/parties/shs.png" width="32"/> | Shiv Sena (SHS) | 7 |
| <img src="images/parties/ljprv.png" width="32"/> | Lok Janshakti Party (Ram Vilas) | 5 | <img src="images/parties/ysrcp.png" width="32"/> | YSR Congress Party (YSRCP) | 4 | <img src="images/parties/rjd.png" width="32"/> | Rashtriya Janata Dal (RJD) | 4 | <img src="images/parties/cpim.png" width="32"/> | Communist Party of India (Marxist) (CPI(M)) | 4 | <img src="images/parties/aap.png" width="32"/> | Aam Aadmi Party (AAP) | 3 |
| <img src="images/parties/iuml.png" width="32"/> | Indian Union Muslim League (IUML) | 3 | <img src="images/parties/jmm.png" width="32"/> | Jharkhand Mukti Morcha (JMM) | 3 | <img src="images/parties/rld.png" width="32"/> | Rashtriya Lok Dal (RLD) | 2 | <img src="images/parties/jds.png" width="32"/> | Janata Dal (Secular) (JD(S)) | 2 | <img src="images/parties/jsp.png" width="32"/> | Jana Sena Party (JSP) | 2 |
| <img src="images/parties/vck.png" width="32"/> | Viduthalai Chiruthaigal Katchi (VCK) | 2 | <img src="images/parties/cpi.png" width="32"/> | Communist Party of India (CPI) | 2 | <img src="images/parties/cpiml.png" width="32"/> | CPI (Marxist–Leninist) Liberation | 2 | <img src="images/parties/jknc.png" width="32"/> | Jammu & Kashmir National Conference (JKNC) | 2 | <img src="images/parties/agp.png" width="32"/> | Asom Gana Parishad (AGP) | 1 |
| <img src="images/parties/ads.png" width="32"/> | Apna Dal (Sonelal) (AD(S)) | 1 | <img src="images/parties/aimim.png" width="32"/> | AIMIM | 1 | <img src="images/parties/sad.png" width="32"/> | Shiromani Akali Dal (SAD) | 1 | <img src="images/parties/skm.png" width="32"/> | Sikkim Krantikari Morcha (SKM) | 1 | <img src="images/parties/zpm.png" width="32"/> | Zoram People's Movement (ZPM) | 1 |
| <img src="images/parties/uppl.png" width="32"/> | United People's Party Liberal (UPPL) | 1 | <img src="images/parties/hams.png" width="32"/> | Hindustani Awam Morcha (Secular) | 1 | <img src="images/parties/kcm.png" width="32"/> | Kerala Congress (M) | 1 | <img src="images/parties/rsp.png" width="32"/> | Revolutionary Socialist Party (RSP) | 1 | <img src="images/parties/ncp.png" width="32"/> | Nationalist Congress Party (NCP) | 1 |
| <img src="images/parties/votpp.png" width="32"/> | Voice of the People Party (VOTPP) | 1 | <img src="images/parties/rlp.png" width="32"/> | Rashtriya Loktantrik Party (RLP) | 1 | <img src="images/parties/bap.png" width="32"/> | Bharat Adivasi Party (BAP) | 1 | <img src="images/parties/mdmk.png" width="32"/> | Marumalarchi Dravida Munnetra Kazhagam (MDMK) | 1 | <img src="images/parties/aspkr.png" width="32"/> | Aazad Samaj Party (Kanshi Ram) | 1 |
| <img src="images/parties/ajsu.png" width="32"/> | AJSU Party (AJSU) | 1 |  |  |  |  |  |  |  |  |  |  |  |  |

</div>

> Party list based on results declared by the Election Commission of India on 4 June 2024 for the 543-seat 18th Lok Sabha; verify against the [ECI's official statistical reports](https://www.eci.gov.in/general-election-to-loksabha-2024-statistical-reports) before publishing.

<br/>
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=gradient&customColorList=0,1,2&gradientColors=FF9933,FFFFFF,138808" width="100%"/>
<br/>

## Methodology

1. **Data cleaning** — standardizing constituency and party names, handling missing/null values, validating margin and vote-count fields.
2. **Exploratory analysis** — aggregating seat counts by party, computing margin distributions, and summarizing candidate-level vote shares.
3. **Visualization** — generating charts with Matplotlib/Seaborn to surface seat distribution, margin trends, and regional patterns.
4. **Interpretation** — summarizing observed patterns as descriptive findings, not predictive or normative claims.

## Analysis & Visualizations

### Party-Wise Seat Distribution

![Party Seat Distribution](seat.png)

Seat counts by party across all 543 constituencies, including national vs. regional party seat share and state-wise concentration.

### Party Performance

![Party Performance](votes.png)

Aggregate seat totals, seat-share percentage, and regional presence by party.

### Candidate Vote Share Comparison

![Vote Comparison](compare.png)

Constituency-level vote totals and margins for selected candidates, included here as an illustrative comparison.

> Replace the example candidates with whichever comparison is most relevant to your analysis, or generalize this section to a "Top Candidates by Vote Share" view to keep the README focused on the dataset rather than specific individuals.

### Margin of Victory

| Category | Description |
|---|---|
| Very Close Contest | Narrow victory margin |
| Competitive Contest | Moderate margin |
| Comfortable Win | Strong lead |
| Landslide Victory | Very large margin |

Margin buckets are used to classify constituency competitiveness and identify closely contested seats.

### Top Winning Margins

Highlights the constituencies with the largest victory margins, representing the most dominant individual results in the dataset.

### Runner-Up (Trailing) Analysis

![Top Trailing Parties](tv.png)

Examines which parties most frequently finished second, and how narrow those defeats were — useful for identifying competitive but unconverted regions.

### Regional Performance

State- and region-wise breakdown of seat distribution and party influence, highlighting how voting patterns vary geographically.

## Key Findings

- A small number of major parties account for the majority of seats won, with regional parties holding significant influence in specific states.
- Victory margins vary widely, ranging from extremely close contests to landslide wins, reflecting differing levels of electoral competitiveness across regions.
- Runner-up performance data shows several parties with strong second-place finishes, indicating competitive presence even without seat conversion.
- Regional and state-level patterns are a significant factor in overall outcomes, alongside national-level party performance.

> Replace these with the specific, numbers-backed findings from your own analysis (e.g. "Party X won N seats with an average margin of Y votes") once the notebook/script has been run on the dataset.

## Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core data processing |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computation |
| Matplotlib | Visualization |
| Seaborn | Statistical graphics |
| Jupyter Notebook | Analysis environment |

## Project Structure

```
Election-Result-Analysis/
├── data/
│   └── lok_sabha_2024_results.csv
├── notebooks/
│   └── election_analysis.ipynb
├── images/
│   ├── parties/
│   │   ├── bjp.png
│   │   ├── inc.png
│   │   └── ... (one file per party, see Logo file column above)
│   ├── seat.png
│   ├── votes.png
│   ├── compare.png
│   └── tv.png
├── README.md
└── requirements.txt
```

> Adjust this tree to match your actual repository layout.

## Getting Started

```bash
# Clone the repository
git clone https://github.com/geershatisaxena/Election-Result-Analysis.git
cd Election-Result-Analysis

# Install dependencies
pip install -r requirements.txt

# Run the analysis notebook
jupyter notebook notebooks/election_analysis.ipynb
```

## Future Scope

**Advanced Analytics**
- State-wise deep-dive analysis
- Alliance and coalition impact assessment
- Historical election comparison (2014, 2019, 2024)

**Machine Learning**
- Constituency competitiveness scoring
- Swing-seat identification based on historical margins

**Interactive Dashboards**
- Streamlit or Power BI dashboard for exploring results
- Interactive choropleth maps of constituency outcomes

## Contributing

Contributions are welcome. Please open an issue to discuss proposed changes, or submit a pull request with a clear description of the analysis or fix.

## License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,1,2&height=180&section=footer&gradientColors=FF9933,FFFFFF,138808&text=Jai%20Hind&fontSize=42&fontColor=1a1a2e&animation=twinkling" width="100%"/>

<sub>Data-driven exploration of India's 2024 parliamentary election results 🇮🇳</sub>

</div>
