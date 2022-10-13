<h1 align="center"> ALX-Udacity Data Analytics Nanodegree Project-1 </h1>
<p align="center"> 
  <img src="https://opportunitycrib.com/wp-content/uploads/2022/04/Alx-Virtual-Assistant-Programme-696x473.jpg" alt="Sample signal" width="70%" height="70%">
</p>
<!-- Content -->
<h2 id="Content"><p>&#128193; Files</p></h2>
<details open="open">
  <summary>Contents</summary>
  <ol>
    <li><a href="https://github.com/Ikuku-Success/Udacity-Data-Analytics-Nanodegree-Project-1/blob/main/Investigate_a_Dataset.ipynb"><p>&#128193; Investigate_a_Dataset.ipynb</p></a></li>
    <li><a href="https://github.com/Ikuku-Success/Udacity-Data-Analytics-Nanodegree-Project-1/blob/main/tmdb-movies.csv"><p>&#128193; tmdb-movies.csv</p></a></li>
  </ol>
</details>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Introduction -->
<h2 id="introduction"> :pencil:Introduction</h2>
<p align="justify"> 
  This data set contains information about 10,000 movies collected from The Movie Database (TMDb),including user ratings and revenue. 
Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters. There are some odd characters
in the ‘cast’ column. Don’t worry about cleaning them. You can leave them as is. The final two columns ending with “_adj” show the budget and
revenue of the associated moviein terms of 2010 dollars, accounting for inflation over time.
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Problem Statement -->
<h2 id="Problem Statement"> :pencil:Problem Statement</h2>

- How does budget affect revenue?
- How does budget affect popularity
- Does popularity affect profit?
- Does popularity affect rating?
- Who is thr most popular director?
- Which of the directors generated the most revenue?

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Data Sourcing -->
<h2 id="Data Sourcing"> :pencil:Data Sourcing</h2>
The dataset was assigned as my first Nanodegree project. After asking questions, I went ahead to explore the data and see what's really in for me. I noticed it has;

- The dataset contains 54 years of movies data, cutting across several genres
- It contains 21 columns and 10866 rows
- Twenty-one of which are strings. Then floats and integres are divided in the ratio 4 : 6

<!-- Data Cleaning & Transformation -->
<h2 id="Data Sourcing"> :pencil:Data Cleaning & Transformation</h2>

Our dataset was not really dirty, it only needed a little data cleanng to make it set for EDA. I noticed some weird zeros and replaced them with null values, changed the datatype of release dates to datetime. Finally, I removed all null values.
<!-- Conclusion & Observation -->
<h2 id="Conclusion & Observation"> :pencil:Conclusion & Observation</h2>

> **•** The dataset contains 54 years of movies data, cutting across several genres.

> **•** From the dataset there are 574 movies that are Adventure or Action or Science Fiction movies. Also, 196 movies are romantic movies, 35 are history movies and 32  War movies. There are 163 Family movies, about 38 Music movies and 139 Horror movies. We also see that 1102 movies are not Adventure or Action movies and 830 movies are Drama or Comedy movies.

> **•** Avatar generated the most revenue and the most profit overall. It also ranks 12th on the all time most popular movie. It premiered in 2009 and was the most popular movie that year.

> **•** The movie, Boy generated the least revenue although compared to its budget there was significant profit.

> **•** Not only that avatar generated the most revenue, it also generated the most profit with the movie The Warrior's Way running at a loss.

> **•** The Warrior's Way exhausted the most budget despite having the least profit. Love, Wedding, Marriage exhausted the least budget but still made significant profit.

> **•** Most of the movie which generated the most revenue and profit had adventure and action in their genres, most movies with comedy and drama generated lesser profit and revenue. This constraint also affected the popularity of the movie. A couple of the movies with the biggest budget didn't generate as much traction, profit or revenue and weren't all that popular.

> **•** Talking about popularity & profit, from the visualization above we can notice a strong positive correllation between revenue and budget this means that in most cases the higher the budget for a movie there's a probability that the movie would generate as much profit. 

> **•** Also, we saw the relationship between popularity and rating. we saw from the chart that movies which were very popular had higher ratings than the less popular movies, this may be as a result of the most talked about movie being watched and loved by viewers ends up getting a good rating and movies that are not really talked about were not really seen by most viewers and had poor rating. 

> **•** Don't you think this will affect profit? Well, looking at the other correllation matrix table and the scatter plot, we'd notice a positive correlation between profit and popularity. What this implies is that as people keep talking about a movie, recommending it and making the movie trend, the revenue less the budget increases and this is more money for the directors and every one concerned.

> **•** So, if you are looking for a movie director to generate a lot of revenue for you then Peter Jackson is the man for you. He is the all time director with the highest revenue generated.

> **•** Christopher Nolan had a fair share of the recognition as he is the most popular movie director.

> **•** Revenue is skewed to the left with most of its values clustered between 0 - 1 X 10^(9), on the other hand, budget is also skewed to the left with most of its values between 0 - 2.5 X 10^(8). Some movies seem to run at a loss as profit margin ranges between -0.5 - 1 X 10^(9).

> **•** Let's look at runtime and popularity. The correlation between runtime and popularity depicts a low positive correlation. What does this mean? Well, it means that the popularity of a movie does not really depend on its length. As mentioned above there are other factors that greatly influence popularity based on this dataset.
