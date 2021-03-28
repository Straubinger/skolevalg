Results of the Danish School General Elections 2015-2019
---

### Description

Every two years since 2015 a mock general election has been held among 8th, 9th and 10th graders in Denmark. It is voluntary for the schools to participate in the elections. More info at <a href="https://www.skolevalg.dk/">Skolevalg.dk</a> (in Danish).

### Repository content

The `skolevalg.csv` data file consists of the following variables:

- `year` = The year of the school election
- `school` = School
- `party_s` = Number of votes for the Social Democratic Party
- `party_rv` = Number of votes for the Social Liberal Party
- `party_kf` = Number of votes for the Convervative People's Party
- `party_nb` = Number of votes for the New Right
- `party_sf` = Number of votes for the Socialist People's Party
- `party_la` = Number of votes for the Liberal Alliance
- `party_kd` = Number of votes for the Christian Democrats
- `party_df` = Number of votes for the Danish People's Party
- `party_v` = Number of votes for the Liberal Party
- `party_el` = Number of votes for the Red-Green Alliance
- `party_alt` = Number of votes for the Alternative
- `blank` = Number of blank votes
- `invalid` = Number of invalid votes
- `not_voted` = Number of students that have not voted
- `valid` = Number of valid votes
- `stemmeberettigede` = Electorate (schools with an electorate of 0 did not participate in the election)
- `municipality` = Municipality where the school is located
- `zip_code` = Zip code of the school
- `region` = Region where the school is located

The following command will load the data into R:

``` R
read.csv(text=getURL("https://github.com/Straubinger/skolevalg/edit/master/skolevalg.csv"))
```
