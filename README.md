
# Microsoft's new film studio

## Navigation

This README.md will be the source of information for navigating through the repository.

* `zippedData` folder: contains datasets used for analysis
* `images` folder: contains graphs and other relevant images
* `movie_industry_analysis.ipynb`: jupyter notebook with technical analysis
* `presentation.pdf`: slide-deck of non-technical information

## Introduction: Business Opportunity

Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They have decided to create a new movie studio, but the problem is they don’t know anything about creating movies. They have hired you to help them better understand the movie industry.

Your team is charged with doing data analysis and creating a presentation that explores what type of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the CEO can use when deciding what type of films they should be creating.


## Approach

In order to address Microsoft's request to know what type of films are achieving success at the box office, I've established a metric of "return on production costs" (herein referred to as ROI) as the main indicator of the success of a film.

I also considered worldwide gross box office sales as another measure of success.

With these two parameters, I examined which movie studio, actors/actresses, genres, and release months have historically yielded big box office success as well as a high ROI.

## Findings - highlights

![Average ROI by Studio](/images/average_ROI_by_studio.png "Average ROI by Studio")

> Top 10 studios with highest average ROI

*New Line Cinema, WB (NL)* - a label of Warner Bros. Picture Group - along with *UTV Motion Pictures (UTV)* - an Indian motion picture company that is owned by The Walt Disney Company India have historically shown they're experienced and knowledgeable in successful distribution, production, and other filmmaking processes.


![Average ROI by Actor/Actress](/images/average_ROI_by_actor.png "Average ROI by Actor/Actress")

> Top 10 Actors/Actresses with highest average ROI

Actors/Actresses like *James McAvoy, Kevin Hart, Jennifer Lawrence*, and *Kristen Wiig* have provided the highest average return on production costs as their big names drew many viewers to the box offices.

![Total Box Office Sales By Genre](/images/highest_box_office_genres.png "Total Box Office Sales By Genre")

> Top 10 Genres with highest total box office sales

Genres such as *Action,Adventure,Sci-Fi* and *Adventure,Animation,Comedy* do very well in worldwide box office sales, most likely due to blockbuster action movies that resonated well with younger audiences.

![Total Box Office Sales By Month](/images/highest_box_office_genres.png "Total Box Office Sales By Month")

> Total box office sales by month

As expected, the summer months of May, June, July historically have the highest box office sales as studios release their 'tent-pole' movies that feature large budget special effects, franchise installments, and all-star casts to draw in the summer crowds. The months of November and December also do well during the holiday season as families gather more often and studios release potentially great films to target awards season.

###### *Further analysis is viewable in the `movie_industry_analysis.ipynb` notebook and/or the `presentation.pdf` slide deck.*

## Conclusion

Although the data does not account for marketing/distribution costs in the ROI metric, the analysis provides a great foundation to explore next actionable steps in terms of which movie studio, actor(s)/actress(es) to cast, genre, and month to release the movie.

## Future Opportunities

Further exploration can be conducted on the statistical significance of the data - whether the results can be attributed to chance.

Other opportunities are available in exploring the ROI on directors, # of movies released by month, and substitution of "popularity" (average film rating) for ROI against the parameters used in this data analysis.
