# Assignment-1-Foundations-Mastery
Part 2 Reflection:
In general, the difference between the mean and median shows how far the 
distribution of a dataset strays from symmetry. For the attendees data, the 
difference between the mean and the median is positive, indicating that the 
distribution is positively skewed. More than half of the protests in the dataset
have lower attendance than the protests with the highest numbers of attendees.


Part 3 Reflection:
No, the number of protests in Washington is not surprising. From historical
context and recent events, WA tends to be a politically active state so I would 
expect the proportion of protests in WA to be relatively high.

The `state_table` variable contains values, such as "Mi" and "iD", which are not
state name abbreviations. There should be at most 50 entries in the table
because there are only 50 possible unique states in the US; however, the table
actually contains 61 entries. These logical discrepancies show that the location
data needs to be cleaned to only include locations that follow the format
where the last two characters of each location are a capitalized state
abbreviation. My analysis would need to change by combining potential overlaps
in locations or resorting the counts for invalid state abbreviations into
the correct table entries.


Part 4 Reflection:
The change in the number of protests from 2019 to 2020 is not suprising.
2020 has been a tumultuous year in US history due to the global pandemic,
social justice issues, and other current events. It makes sense that the 
frequency of protests would significantly increase from 2019 to 2020.

On the state level, Connecticut Governor Ned Lamont signed a policing bill on training policies. On July 31st, chokeholds among other things were banned. Utah also banned chokeholds in most cases. https://ballotpedia.org/Changes_to_policing_policy_in_the_states_and_100_largest_cities,_2020


Part 5 Reflection:
Based on the table stored in the `high_level_table` variable, the "high level"
purposes that have the highest counts are Other, Education, and Environment.
The data seem to indicate that historically the US population is most
dissatisfied with the state or legal policies related to education and
environmental issues. Alternatively, the data may suggest that individuals
who feel strongly about education and environmental issues are more likely to
attend protests for these "high level" purposes.
