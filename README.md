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

> **Adding logos:** drop each party's official logo image (PNG/SVG, ideally square, ~40×40px) into `images/parties/` using the filename shown in the `Logo file` column below, then it will render automatically in the `Logo` column. Official party symbols/emblems are trademarked by the respective parties and the Election Commission of India — source them from each party's official website or the [ECI's recognized symbols list](https://www.eci.gov.in/) and use in accordance with applicable trademark/usage guidelines. This repo does not ship third-party logo files.

<br/>

<div align="center">

| Index | Party | Party Symbol |
|:---:|:---|:---|
| 1. | Bharatiya Janata Party (BJP) | <img src="https://github.com/geershatisaxena/Election-Result-Analysis/blob/main/bjp.png" width="32"/> |
| 2. | Indian National Congress (INC) | <img src="https://github.com/geershatisaxena/Election-Result-Analysis/blob/main/congresss.png" width="32"/> |
| 3. | Samajwadi Party (SP) | <img src="https://github.com/geershatisaxena/Election-Result-Analysis/blob/main/samajwadi.png" width="32"/> |
| 4. | All India Trinamool Congress (AITC) | <img src="https://github.com/geershatisaxena/Election-Result-Analysis/blob/main/All%20India%20Trinamool%20Congress.png" width="32"/> |
| 5. | Dravida Munnetra Kazhagam (DMK) | <img src="https://github.com/geershatisaxena/Election-Result-Analysis/blob/main/Dravida%20Munnetra%20Kazhagam.jpg" width="32"/> |
| 6. | Telugu Desam Party (TDP) | <img src="https://github.com/geershatisaxena/Election-Result-Analysis/blob/main/Telugu%20Desam%20Party.png" width="32"/> |
| 7. | Janata Dal (United) (JD(U)) | <img src="https://github.com/geershatisaxena/Election-Result-Analysis/blob/main/Janata%20Dal%20(United).png" width="32"/> |
| 8. | Shiv Sena (Uddhav Balasaheb Thackeray) (SS(UBT)) | <img src="https://github.com/geershatisaxena/Election-Result-Analysis/blob/main/Shiv%20Sena%20(UBT).jpg" width = "32"/>|
| 9. | Shiv Sena (SHS) | <img src="https://github.com/geershatisaxena/Election-Result-Analysis/blob/main/Shiv%20Sena.png" width="32"/> |
| <img src="images/parties/ncpsp.png" width="32"/> | Nationalist Congress Party (Sharadchandra Pawar) (NCP(SP)) | `images/parties/ncpsp.png` |
| <img src="images/parties/ljprv.png" width="32"/> | Lok Janshakti Party (Ram Vilas) (LJP(RV)) | `images/parties/ljprv.png` |
| <img src="images/parties/ysrcp.png" width="32"/> | YSR Congress Party (YSRCP) | `images/parties/ysrcp.png` |
| <img src="images/parties/rjd.png" width="32"/> | Rashtriya Janata Dal (RJD) | `images/parties/rjd.png` |
| <img src="images/parties/cpim.png" width="32"/> | Communist Party of India (Marxist) (CPI(M)) | `images/parties/cpim.png` |
| <img src="images/parties/aap.png" width="32"/> | Aam Aadmi Party (AAP) | `images/parties/aap.png` |
| <img src="images/parties/iuml.png" width="32"/> | Indian Union Muslim League (IUML) | `images/parties/iuml.png` |
| <img src="images/parties/jmm.png" width="32"/> | Jharkhand Mukti Morcha (JMM) | `images/parties/jmm.png` |
| <img src="images/parties/rld.png" width="32"/> | Rashtriya Lok Dal (RLD) | `images/parties/rld.png` |
| <img src="images/parties/jds.png" width="32"/> | Janata Dal (Secular) (JD(S)) | `images/parties/jds.png` |
| <img src="images/parties/jnp.png" width="32"/> | Jana Sena Party (JnP) | `images/parties/jnp.png` |
| <img src="images/parties/vck.png" width="32"/> | Viduthalai Chiruthaigal Katchi (VCK) | `images/parties/vck.png` |
| <img src="images/parties/cpi.png" width="32"/> | Communist Party of India (CPI) | `images/parties/cpi.png` |
| <img src="images/parties/cpiml.png" width="32"/> | Communist Party of India (Marxist–Leninist) Liberation (CPI(ML)L) | `images/parties/cpiml.png` |
| <img src="images/parties/ads.png" width="32"/> | Apna Dal (Sonelal) (AD(S)) | `images/parties/ads.png` |
| <img src="images/parties/agp.png" width="32"/> | Asom Gana Parishad (AGP) | `images/parties/agp.png` |
| <img src="images/parties/aimim.png" width="32"/> | All India Majlis-e-Ittehadul Muslimeen (AIMIM) | `images/parties/aimim.png` |
| <img src="images/parties/sad.png" width="32"/> | Shiromani Akali Dal (SAD) | `images/parties/sad.png` |
| <img src="images/parties/skm.png" width="32"/> | Sikkim Krantikari Morcha (SKM) | `images/parties/skm.png` |
| <img src="images/parties/zpm.png" width="32"/> | Zoram People's Movement (ZPM) | `images/parties/zpm.png` |
| <img src="images/parties/jknc.png" width="32"/> | Jammu & Kashmir National Conference (JKNC) | `images/parties/jknc.png` |

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
