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
![articles_anime_plot](https://github.com/user-attachments/assets/d8352139-7e96-4342-b008-89fe0e04d810)
## Methodology

1. Data Collection and Preprocessing
2. Exploratory Data Analysis
3. Semi-Supervised Topic Modeling (STM)
4. Topic Analysis and Interpretation
5. Visualization of Results

## Key Findings

- Evidence supporting the "Anime spillover effect", with anime-related articles increasingly touching on broader aspects of Japanese culture and society


## Technologies Used

- R (version X.X.X)
- Key packages: 
  - [stm](https://www.structuraltopicmodel.com/) (for topic modeling)
  - [quanteda](https://quanteda.io/) (for text preprocessing)
  - [ggplot2](https://ggplot2.tidyverse.org/) and [plotly](https://plotly.com/r/) (for visualization)
  - [dplyr](https://dplyr.tidyverse.org/) and [tidyr](https://tidyr.tidyverse.org/) (for data manipulation)
  - [furrr](https://furrr.futureverse.org/) (for parallel processing)

The furrr package is particularly noteworthy in this project. It extends purrr's mapping functions to work in parallel, significantly reducing computation time for our topic modeling tasks.
By leveraging multiprocessing capabilities, I was able to efficiently train multiple topic models and perform other computationally intensive operations, making the analysis of large text datasets more feasible and time-efficient working within R.

## Repository Structure

- `scripts/`: R scripts for each stage of the analysis
- `data/`: Raw and processed data files
- `output/`: Generated plots and results
- `docs/`: Detailed documentation and analysis report

## How to Run


1. Clone this repository
2. Install required R packages: `source("scripts/00_setup.R")`
3. You need to gather the texts yourself. I am not allowed to publish content of the New York Times.
    - You can access the data by using news archives like ProQuest. Most universities should have access for students. Ask your chair or check your Uni website.
    - Not a student. ProQuest access can be quite expensive but there are similar datasources on the Cyberweb.
4. Run scripts in numerical order from `01_data_preparation.R` to `05_visualization.R`
5. View results in the `output/` directory

## Full Report

![my_plot](https://github.com/user-attachments/assets/bc5d3d00-2276-4a05-bb09-53c394d79839)
![my_base_plot_white_background](https://github.com/user-attachments/assets/b34a462b-395f-4c93-affb-8deaf95ec051)
For a detailed analysis and discussion of findings, please see the [full report](link-to-html-report).

## Contributors

- [Your Name](link-to-your-github-profile)

## License

This project is licensed under the [MIT License](LICENSE).
