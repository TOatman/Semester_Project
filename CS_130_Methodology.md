# Data Source
https://corgis-edu.github.io/corgis/csv/injuries/
# Data Preparation/Cleaning
1. The first thing I did to modify the data was making a counter that was able to help me count how many times each city had an injury reported
1. I also reordered some of the data so it made more sense in the context for what I wanted to examine
# Assumptions
1. I made the assumption that when the column "business.second name" has a NaN in the row it meant that the business didn't have a second name
1. I also made the assumption that for the column "statistics.days away" and "statistics.days away/restricted/transfer" where mostly the same considering the first column gets added to the second in some rows but not others
# Limitations
1. From the assumption about "statistics.days away" and "statistics.days away/restricted/transfer" I think that the data number in each column was different and the same depending on the specific injury