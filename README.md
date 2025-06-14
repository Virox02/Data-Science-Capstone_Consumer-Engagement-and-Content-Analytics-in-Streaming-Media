# 🎬 Streaming Media Consumption Analysis During COVID-19

This repository contains the final project presentation for my undergraduate **Data Science Capstone (STATS 170B)** at **UC Irvine**. The project analyzes the evolution of media consumption behaviors on streaming platforms during the COVID-19 pandemic, offering insights into genre trends, user engagement patterns, and recommendations for content producers.

## 📌 Project Objective

To analyze how media consumption patterns changed during COVID-19 and derive **actionable insights** to guide **film and television production** strategies. Specifically, the project aimed to:
- Identify top-performing genres during the pandemic
- Build predictive models to maximize user engagement
- Validate trends using **sentiment analysis** and **topic modeling** (LDA) on IMDb reviews

## 📂 Contents

- `Final Project Presentation.pdf` – Slide deck summarizing data sources, methodologies, findings, and recommendations

## 📊 Methodology

### 1. Data Sources
- **Streaming Dataset** (Middle East-based): Viewing times, durations, genres, platforms
- **IMDb Reviews Dataset**: Text reviews with sentiment cues

### 2. Analytical Techniques
- **Regression & GLM**: Modeled factors influencing unique viewer counts (e.g., content type, language, genre)
- **LDA Topic Modeling**: Discovered latent themes in movie reviews to infer sub-genres and sentiment clusters
- **Clustering**: Segmented genres based on normalized engagement metrics
- **Time Series Analysis**: Tracked viewer spikes during COVID-19 months

## 🔍 Key Findings

- 📈 Sharp rise in media consumption during early 2020, especially post-March (pandemic onset)
- 🎥 **Top Genres**: Action, Comedy, Drama, Adventure, Crime
- 🌍 **Top Languages**: English, Arabic, French
- 🧠 English-language Action films had the **highest user engagement**
- 📅 Seasonal content timing (e.g., family movies during holidays) can optimize viewership

## 🧠 Tools & Technologies

- Languages: Python, R, SQL
- Libraries: `pandas`, `scikit-learn`, `spaCy`, `Transformers`, `plotly`, `ggplot2`
- Techniques: LDA, GLM, clustering, regression diagnostics
- Platforms: PostgreSQL (for querying and hosting data)

## 📈 Recommendations

- Invest in Action-driven content, particularly for English-speaking audiences
- Align content drops with seasonal demand (e.g., family content during holidays)
- Extend analysis globally and across more recent data (post-2020)

## 👥 Team Members
- Ishan Varshney
- Rose Absin
- Shadi Bitarafhaghighi
- **Viraj Vijaywargiya** *(myself)*

---

📌 *This project earned 2nd place at the UC Irvine ICS Project Expo 2024.*
