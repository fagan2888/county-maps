
# Election Maps

Take a look at some of the maps in the outputs folder. Each is generated by boosting the `n`th percentile of densities and above to full saturation. The most accurate map is therefore the 100.00 one, but it gives very little information about anything other than New York. By saturating small urban counties, we can get more information about suburbs, etc.

Of course, we can take this to the logical extreme and saturate something near minimum density to full saturation. This gives us the typical map (1.00) which conveys the most information, but does it in the least accurate manner.

# Data Citations

Election data is from https://github.com/tonmcg/County_Level_Election_Results_12-16.

County area data is from https://www.census.gov/support/USACdataDownloads.html.

The blank map of counties as the basis for the colorized maps is from https://commons.wikimedia.org/wiki/File:USA_Counties.svg.

I have made some data-sanitation-oriented modifications (fixing typos, changing Co. to County, etc.). Any responsibility for introduced errors is mine.
