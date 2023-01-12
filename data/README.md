# Dimensions

The `movies.csv` dataset has 1794 observations, each representing a film released from the years 1970 to 2013, and 34 variables. Key variables in the dataset are genre, IMDB rating, domestic gross, international gross, budget, awards, and whether or not the film passes the Bechdel Test. The dataset comes from a FiveThirtyEight article titled "The Dollar-And-Cents Case Against Hollywood’s Exclusion of Women," which relied on data from BechdelTest.com and The-Numbers.com. FiveThirtyEight used the former to determine if films passed the Bechdel Test and the latter to obtain financial information on the films. 

# Codebook

All variables considered in the project are defined as follows:

  - `year` - Year of the film's release

  - `budget_2013` - Budget of the film normalized to the year 2013
  
  - `domgross_2013` - Domestic gross of the film normalized to the year 2013
  
  - `intgross_2013` - International gross of the film normalized to the year 2013
  
  - `rated` - Content rating assigned to the film
  
  - `metascore` - Metacritic rating of the film, from 0-100
  
  - `imdb_rating` - IMDB rating of the film, from 0-10
  
  - `runtime` - Runtime of the film, in minutes
  
  - `binary` - PASS/FAIL designation of whether or not the film passes the Bechdel test

