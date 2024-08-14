# Anime in The New York Times: A Topic Modeling Analysis

This project analyzes the representation and themes associated with anime in The New York Times articles from 1981 to 2023 using Semi-Supervised Topic Modeling.
It is based on coursework during my exchange semester at the WASEDA University in Tokyo, Japan.
# Anime in The New York Times: A Topic Modeling Analysis

This project analyzes the representation and themes associated with anime in The New York Times articles from 1981 to 2023 using Semi-Supervised Topic Modeling.

## Project Overview

This analysis explores the evolution of anime coverage in The New York Times over four decades. Using advanced natural language processing techniques, specifically Semi-Supervised Topic Modeling, I uncover the main themes and trends in anime-related articles, providing insights into the changing perception and cultural impact of anime in the United States.

## Objectives
- Track the evolution of anime coverage in The New York Times from 1981 to 2023
- Identify and analyze the main topics associated with anime in these articles
- Investigate the "Anime spillover effect" hypothesis, which suggests that increased interest in anime leads to broader engagement with Japanese culture

## Methodology

1. Data Collection and Preprocessing
- 1,219 articles from The New York Times mentioning "anime" (1981-2023)
- Collected via ProQuest archive query
- Cleaned and preprocessed to remove irrelevant content and standardize text
![articles_anime_plot](https://github.com/user-attachments/assets/d8352139-7e96-4342-b008-89fe0e04d810)
3. Exploratory Data Analysis
![image](https://github.com/user-attachments/assets/14bf72fe-35dd-41b3-a7b1-93ac679e20c8)
![image](https://github.com/user-attachments/assets/c7ea22c5-07c5-4cab-946e-b57fee9ac238)

4. Semi-Supervised Topic Modeling (STM)
![image](https://github.com/user-attachments/assets/71072d61-11dc-49b3-970a-2ee5846dd703)
![image](https://github.com/user-attachments/assets/949c8b8a-22b4-41af-93fd-c798529e544d)

6. Topic Analysis and Interpretation
![my_plot](https://github.com/user-attachments/assets/bc5d3d00-2276-4a05-bb09-53c394d79839)
7. Visualization of Results

## Key Findings

- Evidence supporting the "Anime spillover effect", with anime-related articles increasingly touching on broader aspects of Japanese culture and society
![image](https://github.com/user-attachments/assets/e7bf65c1-4669-413c-aa01-ef8dfe162e39)
- Data shows clear diversification of topics alongside the increase in number of articles per year
- Suggest that the idea behind Cool Japan has merit
- I find evidence that alongside the increased coverage of anime, the number of topics it relates to increases.
- People with interest in Anime are possibly more likely to find out about these topics

![my_base_plot_white_background](https://github.com/user-attachments/assets/b34a462b-395f-4c93-affb-8deaf95ec051)

Which topics are likely to appear together in the same article?
- Entertainment Cluster: Articles discussing Hollywood Cinema often detail Film Directing techniques, while those on Anime & Manga frequently reference Ghibli Films.
- Cultural Dynamics: Pieces on Culinary Trends tend to explore Cultural Heritage, and those focusing on Fashion Trends commonly link to Asian Beauty concepts.
- Digital Media Correlation: Discourse around Social Media intersects with Digital Media impacts, just as Gaming & Fantasy connects with Comic Culture in digital entertainment.
- Socio-Economic Insights: Education & Campus articles typically involve Urban Housing issues, and Governance & Funding is often discussed alongside Political Dynamics.

## Technologies Used

- R (version 4.3.1)
- Key packages: 
  - [stm](https://www.structuraltopicmodel.com/) (for topic modeling)
  - [quanteda](https://quanteda.io/) (for text preprocessing)
  - [ggplot2](https://ggplot2.tidyverse.org/) and [plotly](https://plotly.com/r/) (for visualization)
  - [dplyr](https://dplyr.tidyverse.org/) and [tidyr](https://tidyr.tidyverse.org/) (for data manipulation)
  - [furrr](https://furrr.futureverse.org/) (for parallel processing)

The furrr package is particularly noteworthy in this project. It extends purrr's mapping functions to work in parallel, significantly reducing computation time for our topic modeling tasks.
By leveraging multiprocessing capabilities, I was able to efficiently train multiple topic models and perform other computationally intensive operations, making the analysis of large text datasets more feasible and time-efficient working within R.

## Repository Structure

- `anime_nyt_analysis.Rmd`: R Markdown file containing the entire analysis
- `data/`: Raw data file (anime_texts.txt)
- `output/`: Generated plots and results
- `anime_nyt_analysis.html`: Knitted HTML report of the analysis

## How to Run

1. Clone this repository
2. Open the `anime_nyt_analysis.Rmd` file in RStudio
3. Install required R packages (listed at the beginning of the R Markdown file)
4. Run all chunks in the R Markdown file or knit the document to HTML
5. View results in the `output/` directory and in the generated HTML report


![my_plot](https://github.com/user-attachments/assets/bc5d3d00-2276-4a05-bb09-53c394d79839)


## License

This project is licensed under the [MIT License](LICENSE).
