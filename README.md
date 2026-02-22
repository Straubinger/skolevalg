Results of the Danish School General Elections 2015-2026
---

### Description

Every two years since 2015 a mock general election has been held among 8th, 9th and 10th graders in Denmark. It is voluntary for the schools to participate in the elections. More information at <a href="https://www.skolevalg.dk/">Skolevalg.dk</a> (in Danish).

It is possible to find additional information about the schools e.g. number of students at <a href="https://www.uddannelsesstatistik.dk/">Uddannelsesstatistik.dk</a> (in Danish).

### Repository content

The `skolevalg.csv` data file consists of the following variables:

- `date` = Date of the school election
- `year` = Year of the school election
- `school` = School
- `school_id` = ID of the school (missing until 2024)
- `party_s` = Number of votes for the Social Democratic Party
- `party_rv` = Number of votes for the Social Liberal Party
- `party_kf` = Number of votes for the Conservative People's Party
- `party_nb` = Number of votes for the New Right (only 2017-2021)
- `party_sf` = Number of votes for the Socialist People's Party
- `party_vegan` = Number of votes for the Vegan Party (only 2021)
- `party_la` = Number of votes for the Liberal Alliance
- `party_kd` = Number of votes for the Christian Democrats (only 2015 and 2019-2021)
- `party_m` = Number of votes for the Moderates (from 2024)
- `party_df` = Number of votes for the Danish People's Party
- `party_v` = Number of votes for the Liberal Party
- `party_dd` = Number of votes for the Denmark Democrats (from 2024)
- `party_el` = Number of votes for the Red-Green Alliance
- `party_alt` = Number of votes for the Alternative (from 2017)
- `blank` = Number of blank votes (missing in 2024)
- `invalid` = Number of invalid votes
- `not_voted` = Number of students that have not voted (missing from 2024)
- `valid` = Number of valid votes
- `electorate` = Electorate (missing from 2024)
- `municipality` = Municipality where the school is located
- `municipality_id` = ID of the municipality where the school is located
- `zip_code` = Zip code of the school (missing from 2026)
- `region` = Region where the school is located
- `region_id` = ID of the region where the school is located

The following command will load the data into R:

``` R
read.csv(url("https://raw.githubusercontent.com/Straubinger/skolevalg/master/skolevalg.csv"))
```
