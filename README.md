# Kickstarter-Challenge
MSU Data Analytics Module 1 Challenge

# Overview:

The purpose of this project is to maximize the probability for success of a kickstarter by analyzing data from past projects in order to find trends and insights that can be leveraged to set our project up for success, focusing mostly on launch dates and fundraising goals.

As this is a purely quantitative analysis, the scope of the analysis is rather limited.  We have no way to objectively measure the quality of a proposed theatrical productions, so we instead focused on things that are directly measureable -- namely launch date and stated fundraising goal.  Thankfully, for ease of analysis, the data used was already clean and organized, so no work was needed on that front.  It is very important when performing data analyses to make sure that data used is clean and unclottered with erroneous entries.

# Analysis:

### Criteria

For all of our analyses, we drill down to the most specific subcategory we can, in order to make sure that any insights found are actually relevant to the project at hand -- we don't need to know which month is best for launching a kickstarter for a 3d printed phone case when we will be launching one to fund a stage play production.  As such, before any other considerations, we filter our data so that we are only looking at theater kickstarters.  We also filter out projects that are still live, as those projects have not yet reached a conclusion, and as such offer no useful data for the type of analysis we are performing.

### Launch Date

For our first analysis, we will look at the time of year that each project was launched.  A pivot table was created to group projects by the month in which they were launched, irrespective of year, to attempt to find an ideal time of year to launch a theater kickstarter.  Year launched was also included as a filter, so that results could be more finely targeted at the past few recent years if needed.  In so doing, we find that not only does May have the largest number of theater projects launched, but the largest number of successful projects, and the best rate of success among other months.  June is also a good month to start a theater kickstarter, being only slightly worse than May in these metrics.

### Fundraising Goal

For our second analysis, we looked at theater kickstarter outcomes as a function of their initial fundraising goals.  For this, formulas were used to add up the number of outcomes in each category, grouped according to fundraising goal ranges.  As with the last analysis, we make sure to disregard projects that aren't in relevant categories.  Through this, we find that lower goals tend to be more successful.  While projects with goals ranging from $35000 to $44999 have good rates of success, the sample sizes for those goal ranges are very small.  Our data for the smaller goals is, by comparison, much more reliable.  From the data, it would appear that a goal under $5000 tends to have the greatest chance of success.
