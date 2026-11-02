# Formula 1 Race Intelligence Dashboard
### Transforming Formula 1 Data into Championship Intelligence

## 1. Project Title and Introduction

**Project Title:** Formula 1 Race Intelligence: Interactive Dashboard and Data Story

Formula 1 is one of the world's most data-driven sports, where driver performance, team strategy, race outcomes, reliability, and championship standings play crucial roles in determining success.

The **Formula 1 Race Intelligence** project uses data visualization and analytics to explore Formula 1 racing statistics and uncover meaningful patterns in driver performance, constructor competitiveness, race results, and championship history.

The project consists of an interactive Tableau dashboard and a Tableau Story, supported by a dedicated website that brings both visualizations together in a single, professional interface.

**Project Links:**
- **Tableau Dashboard:** https://public.tableau.com/views/FORMULA1RaceIntelligenceDashboard_17936379448320/Formula1RaceIntelligenceDashboard
- **Tableau Story:** https://public.tableau.com/views/FORMULA1RaceIntelligenceStory/Formula1RaceIntelligenceStory

## 2. Project Overview

The Formula 1 Race Intelligence project transforms historical Formula 1 racing data into interactive visualizations that make complex racing statistics easier to understand.

The dashboard provides an analytical view of driver performance, team rankings, race outcomes, driver reliability, and geographical race participation. Interactive filters allow users to explore the available data according to selected parameters.

The Tableau Story complements the dashboard by presenting selected visualizations in a structured sequence, helping users explore the relationships between race participation, driver reliability, team performance, and championship success.

The project also includes a custom-designed website featuring a motorsport-inspired interface with a black-and-red color scheme, navigation sections, project information, and embedded Tableau visualizations.

**Main components:**
- Interactive Formula 1 analytics dashboard.
- Tableau Story for guided data exploration.
- Driver performance and reliability analysis.
- Constructor performance comparisons.
- Geographical visualization of race participation.
- Website interface for accessing the dashboard and story.

## 3. Objectives

The primary objective of this project is to analyze Formula 1 racing data and communicate meaningful insights through interactive dashboards and data storytelling.

The specific objectives are:

1. **Analyze driver performance:** Compare drivers using available performance metrics, points, and race results.
2. **Evaluate constructor performance:** Examine team rankings and compare competitive performance.
3. **Explore race outcomes:** Investigate recorded race results and retirement or non-finish information.
4. **Visualize geographical participation:** Present country-wise information associated with Formula 1 drivers and races.
5. **Investigate driver reliability:** Analyze recorded DNFs and other available reliability-related indicators.
6. **Identify championship trends:** Explore how driver and team performance relates to championship standings.
7. **Develop interactive visualizations:** Enable users to investigate the data through filters and charts.
8. **Communicate findings through storytelling:** Organize visualizations into a Tableau Story that presents the analysis in a logical sequence.
9. **Create an accessible project interface:** Integrate the dashboard and story into a dedicated website.

## 4. Tools and Technologies

The project uses data visualization tools and web technologies to present Formula 1 statistics in an accessible and interactive format.

| Tool or Technology | Purpose |
|---|---|
| Tableau Public | Creating, publishing, and sharing interactive dashboards and stories |
| Microsoft Excel or CSV files | Potential source and storage formats for tabular racing data |
| HTML5 | Structuring the project website |
| CSS3 | Designing the website layout, colors, typography, and responsive interface |
| JavaScript | Supporting navigation, responsive behavior, and Tableau embedding |
| Tableau Public Embedding | Displaying published dashboard and story visualizations within the website |
| GitHub Pages or Netlify (optional) | Hosting the website online |

**Note:** Tableau Public is the primary visualization platform. Excel, CSV, and other data preparation tools should be listed as tools actually used in the project's data workflow. GitHub Pages and Netlify are optional deployment platforms rather than required components.

## 5. Dataset Description

The project explores Formula 1 racing data containing information about drivers, constructors, races, results, and championship performance.

The dashboard presents several categories of racing statistics, allowing users to examine historical performance and compare results across available records.

**Potential dataset entities and fields include:**

| Data Category | Example Information |
|---|---|
| Drivers | Driver names, nationalities, and identifiers |
| Constructors | Team names and constructor identifiers |
| Races | Race names, dates, seasons, and circuits |
| Race Results | Finishing positions, points, and race outcomes |
| Driver Reliability | DNF records and recorded retirement reasons |
| Championship Performance | Driver points, constructor standings, and rankings |
| Geographical Information | Countries associated with drivers or race participation |
| Lap and Pit-Stop Information | Lap times, tyre usage, and pit-stop records, where available |

**Dataset source:** The precise dataset source and version should be documented according to the files used to build the Tableau workbook.

A potential public source for historical Formula 1 data is the Ergast-compatible dataset maintained by the Jolpica-F1 project.

Dataset reference: https://github.com/jolpica/jolpica-f1

**Important:** The exact source, date range, number of records, and field definitions should be verified against the actual data connected to the Tableau workbook before being included as confirmed dataset metadata.

## 6. Dashboard Features

The Formula 1 Race Intelligence Dashboard brings multiple visualizations together to provide an overview of Formula 1 performance and racing statistics.

### 6.1. Global Driver Distribution

Displays geographical information related to driver nationalities and participation across different countries.

**Purpose:** To explore the geographical distribution represented in the dataset.

### 6.2. Driver Reliability Analysis

Visualizes recorded driver non-finishes and reliability-related race outcomes.

**Purpose:** To compare recorded reliability indicators and investigate differences between drivers.

### 6.3. Driver Performance Leaderboard

Ranks drivers according to the performance metric displayed in the dashboard.

**Purpose:** To identify leading drivers and compare their results using the selected measure.

### 6.4. Team Performance Ranking

Compares constructors using the team-performance measure represented in the visualization.

**Purpose:** To identify relative team performance and examine competitive differences.

### 6.5. Interactive Filters

The dashboard includes filters for available dimensions such as DNF reason, race year, and the number of top parameters displayed.

**Purpose:** To help users focus on selected records and customize the information shown in the visualizations.

### 6.6. Summary Metrics

The dashboard presents high-level indicators, including competing teams, seasons represented, recorded race outcomes, and circuits showcased.

**Purpose:** To provide a quick overview of the data covered by the dashboard.

## 7. Story and Analysis

The Tableau Story, titled **Formula 1 Race Intelligence: From Global Overview to Championship Success**, complements the dashboard by arranging selected visualizations into a guided analytical experience.

Instead of viewing each chart independently, users can navigate through a sequence of views to understand different aspects of Formula 1 performance.

The published story includes analytical views covering the following themes:

### 7.1. Global Driver Distribution Across Grand Prix Nations

Explores the geographical distribution represented by the driver data and highlights the countries associated with participation.

### 7.2. Country-Wise Race Participation

Examines the distribution of race-related information across countries represented in the visualization.

### 7.3. Team Championship Performance Analysis

Compares constructor performance and examines the differences represented in the championship data.

### 7.4. Driver Reliability Analysis

Investigates recorded non-finishes and reliability-related race outcomes across drivers.

### 7.5. Podium Achievements by Driver and Team

Explores podium-related achievements and compares the results displayed for drivers and constructors.

### 7.6. Tyre Compound Usage Distribution

Examines tyre compound usage patterns where those records are included in the underlying data.

### 7.7. Team Performance Comparison

Provides an additional perspective on constructor performance and competitive differences.

**Analytical approach:** The story moves from geographical and participation patterns toward driver and constructor performance. It helps users connect individual visualizations and develop a broader understanding of the relationships represented in the dataset.

The findings should be interpreted according to the measures, filters, historical period, and data definitions used in the published Tableau workbook.

## 8. Key Insights

The dashboard and story support several types of analysis. The following are the principal insights users can investigate through the available visualizations.

- **Driver performance:** Identify drivers with high values for the selected performance metric and compare their results.
- **Constructor competitiveness:** Examine differences between team rankings and the performance measures used in the dashboard.
- **Reliability patterns:** Identify drivers with higher recorded DNF counts and investigate the associated retirement reasons.
- **Geographical distribution:** Explore the countries represented in the driver distribution visualization.
- **Championship performance:** Compare team and driver performance indicators to investigate competitive trends.
- **Podium achievements:** Examine the distribution of podium results across drivers and teams.
- **Race participation:** Investigate the geographical and historical patterns represented in the dataset.
- **Tyre usage:** Explore the distribution of tyre compounds where the underlying records support this analysis.

These are analytical questions and potential findings rather than independently verified conclusions. Specific claims about the leading driver, strongest constructor, most common retirement reason, or dominant tyre compound should be confirmed by examining the actual Tableau visualizations and applying the relevant filters.

## 9. Project Structure

The project can be organized into the following directory structure for GitHub or portfolio presentation.

```text
Formula-1-Race-Intelligence/
│
├── index.html
│
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
│       └── project-preview.png
│
├── data/
│   └── README.md
│
├── documentation/
│   └── project-report.pdf
│
└── README.md
```

**File descriptions:**

- `index.html`: Main website containing the project overview and embedded Tableau visualizations.
- `assets/css/style.css`: Stylesheet for the website's appearance and responsive layout, if CSS is maintained separately.
- `assets/js/script.js`: JavaScript for website interactions and embedding support, if maintained separately.
- `assets/images/`: Screenshots and other project-related visual assets.
- `data/README.md`: Dataset source, schema, licensing, and preparation notes.
- `documentation/project-report.pdf`: Optional detailed project report.
- `README.md`: Project introduction, tools, dashboard links, features, and access instructions.

**Note:** This is a suggested repository structure. The actual website may keep its HTML, CSS, and JavaScript together in a single HTML file. The Tableau workbooks remain hosted on Tableau Public unless you separately export or download them.

## 10. How to Access the Project

The project can be explored through the published Tableau visualizations or through the custom website.

### Step 1: Open the Dashboard

Visit the published Tableau dashboard:

https://public.tableau.com/views/FORMULA1RaceIntelligenceDashboard_17936379448320/Formula1RaceIntelligenceDashboard

Use the available filters and charts to explore driver performance, constructor rankings, reliability indicators, and race statistics.

### Step 2: Open the Tableau Story

Visit the published Tableau Story:

https://public.tableau.com/views/FORMULA1RaceIntelligenceStory/Formula1RaceIntelligenceStory

Navigate through the story views to explore the analysis in a guided sequence.

### Step 3: Open the Website

Open the project's HTML file in a modern web browser while connected to the internet.

The website provides navigation between the project overview, analytics sections, interactive dashboard, and Tableau Story.

For convenient sharing, the website can optionally be published using GitHub Pages or Netlify.

### Step 4: Explore the Visualizations

Interact with the published Tableau views to investigate the data, adjust available filters, compare categories, and examine the trends represented in the charts.

**Project links:**

- Dashboard: https://public.tableau.com/views/FORMULA1RaceIntelligenceDashboard_17936379448320/Formula1RaceIntelligenceDashboard
- Story: https://public.tableau.com/views/FORMULA1RaceIntelligenceStory/Formula1RaceIntelligenceStory
- Dataset reference: https://github.com/jolpica/jolpica-f1

## 11. Author and Acknowledgements

**Author:** [Your Name]

**Project:** Formula 1 Race Intelligence: Interactive Dashboard and Data Story

**Platform:** Tableau Public

This project was developed to demonstrate the use of data visualization, exploratory analysis, and data storytelling in the context of Formula 1 motorsport.

Acknowledgements:

- **Tableau Public:** For providing a platform to build, publish, and share interactive dashboards and data stories.
- **Jolpica-F1:** For maintaining a public Formula 1 data API and supporting access to historical racing information, if used as a source in the project.
- **Formula 1:** For the motorsport context that inspires the analysis of drivers, constructors, race results, and championship performance.

The project demonstrates how racing data can be organized into interactive visualizations that make performance comparisons easier to explore and understand.

---

### Conclusion

The Formula 1 Race Intelligence project combines interactive data visualization with structured storytelling to explore the performance patterns behind Formula 1 racing.

By integrating a Tableau dashboard, a Tableau Story, and a dedicated website, the project provides a unified experience for examining driver results, constructor performance, reliability indicators, geographical distribution, and championship-related trends.

It demonstrates the value of data analytics and visualization in transforming complex sporting statistics into an accessible and engaging analytical experience.
