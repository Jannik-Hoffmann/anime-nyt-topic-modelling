# Anime in The New York Times: A Topic Modeling Analysis

This project analyzes the representation and themes associated with anime in The New York Times articles from 1981 to 2023 using Semi-Supervised Topic Modeling.
It is based on coursework during my exchange semester at the WASEDA Univerity in Tokyo, Japan.
# Anime in The New York Times: A Topic Modeling Analysis

This project analyzes the representation and themes associated with anime in The New York Times articles from 1981 to 2023 using Semi-Supervised Topic Modeling.

## Project Overview

This analysis explores the evolution of anime coverage in The New York Times over four decades. Using advanced natural language processing techniques, specifically Semi-Supervised Topic Modeling, we uncover the main themes and trends in anime-related articles, providing insights into the changing perception and cultural impact of anime in the United States.

## Objectives

- Track the evolution of anime coverage in The New York Times from 1981 to 2023
- Identify and analyze the main topics associated with anime in these articles
- Investigate the "Anime spillover effect" hypothesis, which suggests that increased interest in anime leads to broader engagement with Japanese culture

## Data Source

- 1,219 articles from The New York Times mentioning "anime" (1981-2023)
- Collected via ProQuest archive query
- Cleaned and preprocessed to remove irrelevant content and standardize text

## Methodology

1. Data Collection and Preprocessing
2. Exploratory Data Analysis
3. Semi-Supervised Topic Modeling (STM)
4. Topic Analysis and Interpretation
5. Visualization of Results

## Key Findings

- [Visualization: Increase in anime-related articles over time](link-to-image)
- [Visualization: Evolution of topics associated with anime](link-to-image)
- Evidence supporting the "Anime spillover effect", with anime-related articles increasingly touching on broader aspects of Japanese culture and society

## Technologies Used

- R (version X.X.X)
- Key packages: 
  - stm (for topic modeling)
  - quanteda (for text preprocessing)
  - ggplot2 and plotly (for visualization)
  - dplyr and tidyr (for data manipulation)

## Repository Structure

- `scripts/`: R scripts for each stage of the analysis
- `data/`: Raw and processed data files
- `output/`: Generated plots and results
- `docs/`: Detailed documentation and analysis report

## How to Run

1. Clone this repository
2. Install required R packages: `source("scripts/00_setup.R")`
3. Gather texts and aggregate in txt file.
4. Run scripts in numerical order from `01_data_preparation.R` to `05_visualization.R`
5. View results in the `output/` directory

## Full Report

For a detailed analysis and discussion of findings, please see the [full report](link-to-html-report).

## Contributors

- [Your Name](link-to-your-github-profile)

## License

This project is licensed under the [MIT License](LICENSE).
