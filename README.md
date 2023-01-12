Movies Project
================
by The Kable Guys


## Data Dictionary

`movies.csv`

|variable      |class     |description |
|:-------------|:---------|:-----------|
|year          |double    | Year |
|imdb          |character | IMDB|
|title         |character |Title of movie |
|test          |character | Bechdel Test outcome|
|clean_test    |character | Bechdel Test cleaned |
|binary        |character | Binary pass/fail of bechdel |
|budget        |double    | Budget as of release year |
|domgross      |character | Domestic gross in release year |
|intgross      |character | International gross in release year |
|code          |character | Code |
|budget_2013   |double    | Budget normalized to 2013 |
|domgross_2013 |character | Domestic gross  normalized to 2013 |
|intgross_2013 |character | International gross normalized to 2013 |
|period_code   |double    | Period code |
|decade_code   |double    | Decade Code |
|imdb_id       |character | IMDB ID |
|plot          |character | Plot of movie |
|rated         |character | Rating of movie |
|response      |character | Response? |
|language      |character | Language of film |
|country       |character | Country produced in |
|writer        |character | Writer of film |
|metascore     |double    | Metascore rating (0-100) |
|imdb_rating   |double    | IMDB Rating 0-10|
|director      |character | Director of movie |
|released      |character | Released date |
|actors        |character | Actors |
|genre         |character | Genre |
|awards        |character | Awards |
|runtime       |character | Runtime |
|type          |character | Type of film |
|poster        |character | Poster image |
|imdb_votes    |character | IMDB Votes |
|error         |character | Error? |


## Summary 

For our project we wanted to focus on female representation in the film industry, specifically measured by a metric referred to as the Bechdel test. A film must meet three criteria to pass the Bechdel test, those being that it has two female characters, that those characters speak to each other, and that their conversation involves something other than a man. We specifically wanted to examine which factors, including but not limited to the release year of a movie, its domestic and international gross, and its critical reception, impacted the odds that a film passes the Bechdel test. After constructing a logistic regression model, we discovered that newer films, longer films, films with higher Metacritic scores, and films made for younger audiences have higher odds of passing the Bechdel test, while films with higher budgets and higher IMDB ratings have lower odds of passing.