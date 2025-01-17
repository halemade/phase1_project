![Photo by <a href="https://unsplash.com/@jakobowens1?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Jakob Owens</a> on <a href="https://unsplash.com/@halemade/likes?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  ](./images/jakob-owens-sOWoC7fA5DA-unsplash.jpg)

# MICROSOFT studio: Film Recommendations

**Authors**: <br>[Taylor Hale Robert](mailto:taylorhale11@gmail.com)
                <br>[Naomi Weinberger](mailto:weinberger.naomi@gmail.com)
                <br>[Harrison Gu](mailto:Harrison.s.gu@gmail.com)


## Overview

This project analyzes the climate over the last 20 years in the film industry. Descriptive analysis of film characteristics by film ROI shows that particular characteristics are common across the highest revenue films. Microsoft can use this analysis to determine the best direction for profitable product development and launch.

## Data Sources & Features

We worked across 3 different data sources for this anaylysis:

- [IMDB](https://www.imdb.com/) data was used for our genre and director analysis
- [TMDb](https://www.themoviedb.org/), from which we used both the provided datasets and accessed the API
- [The Numbers](https://www.the-numbers.com/), as a provided data set

We used ROI as a metric for the majority of most of our analysis, in an effort to discern characteristics of films that most consistently yield valuable returns.In cases where ROI information wasn't available, we used user rating. 
## Analysis

After our initial analysis revealed a positive correlation between hgih budget and high %ROI, we continued our analysis and created our visualizations based on a subset of films with budgets >= 100 mil. <br><br>
![Photo by <a href="https://github.com/halemade/film_recommendations/blob/main/images/budgets%202.PNG">Harrison Gu</a> on <a href="https://github.com/halemade/film_recommendations/blob/main/images/budgets%202.PNG"></a>
  ](./images/budgets%202.PNG)


We broke out the data by budget, MPAA rating, genre, release timing and runtime to understand how these characteristics of the films varied agains %ROI. 

## Conclusions

This analysis leads to five recommendations for MS2021:

- **Produce films with a budget greater than 100mil** Films with the highest investments have the highest rate of return.
- **Pay attention to film MPAA rating** Films with the highest investments have the highest rate of return.
- **Work within the most popular genres.** Films with the highest investments have the highest rate of return.
- **Hire highly rated directors** Films with the highest investments have the highest rate of return.
- **Create films that run between 90-130 minutes, or over 130 minutes for a higher but more variable ROI.** Films below of this range drop drastically in performance.
- **Release films on Friday, ideally in the months of March-April or November-December** ROI is highest during these periods, regardless of genre.

### Next Steps

Further analyses could yield additional insights and improve understanding of the industry:

- **Explore ROI for the IMDB information and get more recent data** 
- **Analyze specific subsections, e.g. low budget comedy films** 
- **Explore the effect streaming services and the recent changes to how studios are releasing on the performance of films** 

## For More Information

See the full analysis in the [Jupyter Notebook](./2000-2020_film_analysis.ipynb) or review this [presentation](./Film_Recommendations_Presentation.pdf).

For additional info, contact the authors at:<br>
[Taylor Hale Robert](mailto:taylorhale11@gmail.com)
<br>[Naomi Weinberger](mailto:weinberger.naomi@gmail.com)
<br>[Harrison Gu](mailto:Harrison.s.gu@gmail.com)


## Repository Structure

```
├── code
│   ├── explore_budget_final.ipynb
│   ├── User_Ratings_Genre_Director.ipynb
│   ├── explore_data.ipynb
│   ├── parse_genres.ipynb
│   ├── ratings_final.ipynb
│   └── release_and_ROI.ipynb
├── zippedData
├── images
├── .gitignore
├── README.md
├── Film_Recommendations_Presentation.pdf
└── 2000-2020_film_analysis.ipynb
