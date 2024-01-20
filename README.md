## The Central Park Squirrel Census

The file squirrels.qmd is the exploratory code. Numerous things have been changed for the final product to improve it, and will not be kept in the final presentation.

The file squirrels_presentation.qmd is the final presentation. 

In the project description, I have seen the requirement to summarise some of the data. However, my data set is not a great candidate for that, being almost not numerical at all. One could count the occurrence of unique values of some columns, but I find bar plots to represent that better. I therefore summarised only one column.

### Important

- Despite having an active app on shinyapps.io, its URL yields an error every time, so I was not able to include it in the presentation itself. Please run the appropriate code chunk to view the interactive map with squirrel occurrences throughout the month.

- In the last slides, two patchwork plots used to work and for some reason stopped at some point. The other patchwork plots work well. The maps are correct, but as soon as I add the final line, for example (am_map | pm_map), I receive an error which I cannot seem to get rid of.