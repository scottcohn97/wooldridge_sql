# Convert stata .dta to SQL .db

For my econometrics course, I was given a folder of the wooldridge `.dta` files for use in problem sets. I prefer to use R or python. In R there is a package called `wooldridge` which solves all of the problems with using Wooldridge's datasets. You can also import `.dta` files using the `foreign` library. I thought it would be easier to make a SQL database I can put in my `econometrics` course folder so I can quickly grab, using SQL, whichever table I wanted and make changes before saving it to the namespace in R _or_ python. This mini project does that. Moreover, it can be used to create a SQL database from any list of `.dta` or `.csv` files with some slight modification.


Wooldridge, Jeffrey M., 1960-. (2012). Introductory econometrics : a modern approach. Mason, Ohio :South-Western Cengage Learning,