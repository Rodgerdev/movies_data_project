# **Movie Performance Trend Analysis**

## **Table of Contents**

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Data Exploration] (#data-exploration)
- [Visualisations] (#Visualisations)
- [Installation](#installation)
- [Usage](#usage)
- [Acknowledgments](#acknowledgments)

## **Project Overview**

The **Movies Data Project** aims to analyze and derive insights from various movie datasets. The project seeks to identify the top-performing film genres in terms of profit by analyzing which film genres (action, drama, comedy, animation, etc.) are performing best at the box office and identifying the highest performing genre over the last decade.

## **Data Sources**

This project utilizes datasets from multiple sources:

- **Box Office Mojo**: This dataset contains detailed information on movie titles, genres, box office revenues, release dates, and production budgets
- **IMDB**: Provides comprehensive data on movie ratings, cast, crew, and user reviews, useful for understanding audience reception.
- **Rotten Tomatoes**: Offers critic and audience reviews and ratings.
-The Numbers: 

- **The Movie Database (TMDb)**: Supplies data on movie genres, release dates, and popularity metrics.
- **The Numbers**: Includes data on financial performance metrics, production costs and box office earnings, useful in analyzing budget-to-revenue ratios.

  ## Data Exploration
- **Tools:**
  - Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Exploration Goals:**
  - Analyze genre popularity
  - Investigate movie profits over time
  - Find best performing movies

## **Visualizations**
1. *Genre popularity*
![Genre popularity](https://github.com/user-attachments/assets/c03dc539-8523-4f06-8d24-4cf45683c8a3)
From this we can conclude the top 10 genres are:

Drama with 28394 movies
Documentary with 16423 movies
Comedy with 15514 movies
Thriller with 7583 movies
Horror with 6917 movies
Action with 6297 movies
Romance with 5976 movies
Crime with 4338 movies
Biography with 3693 movies
Adventure with 3621 movies

2. *Movie Profits*
![Trend of profits](https://github.com/user-attachments/assets/f623234b-b12b-4b5f-90fc-d635a98820f6)
Profits increase gradually over the years. The drop in the year 2020 and 2019 was maybe due to covid-19.

3. *Most performing movies*
![Movie profits](https://github.com/user-attachments/assets/39d418ae-324f-4c20-a471-cca76bc28c35)
Avatar leads with the highest profit, followed by Titanic, Avengers: Infinity War, and Star Wars entries.

## **Installation**

To set our the project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Rodgerdev/movies_data_project.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd movies_data_project
   ```

## **Usage**

After installation, you can explore the project using the provided Jupyter Notebooks:

1. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

2. **Open the main analysis notebook**:

   - `phase_2_project.ipynb`: Contains the primary data analysis and visualizations.

3. **Run the notebook cells** to execute the analysis step-by-step.
   
## **Acknowledgments**

- **Data Providers**:
  - [Box Office Mojo](https://www.boxofficemojo.com/)
  - [IMDB](https://www.imdb.com/)
  - [Rotten Tomatoes](https://www.rottentomatoes.com/)
  - [The Movie Database (TMDb)](https://www.themoviedb.org/)
  - [The Numbers](https://www.the-numbers.com/)

- **Inspiration**: This project is inspired by helping our company enter the movie industry by identifying the types of films that are currently performing the best at the box office. The ultimate goal is to provide actionable insights to guide the creation of content that will maximize box office success for the company's new movie studio.
