# stliteplayground
Small portable apps based on pyodide/stlite

## TeamMaker
#### Description
The app was designed to generate rank and gender balanced teams for collective sports.  
I requires a dataframe with at least 4 columns (the names of columns are not fixed).  
+ "Name": player identifier
+ "Rank": numeric value. players with lowest rank are assigned to teams first
+ "Gender": player gender. either 'm' or 'f'

The remaining columns are supposed to be dates (in the form dd/mm or dd/mm/yyyy, or any such format). each of these columns should be filled with binary choice
|First Name| Ranking|Gender|(...)| 05/01 | 12/01 | 19/01 |
|----------|--------|------|-----|-------|-------|-------|
|Alice| 2|f|(...)| y | y | n |
|Bob| 1|m|(...)| n | y | y |

With appropriate data, the  software randomly generates rank blalanced and gender balenced team.
#### Usage
Open web page with any browser and follow instructions in About tab
