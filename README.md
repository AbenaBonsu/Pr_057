
Overview:
In the world today, there are many pressing and relevant issues that effect vast and diverse populations of people. These issues are often times overshadowed by other problems that are more visibly apparent or noticeable to the common public.

As a team, we wanted to tackle one of the many civic concerns that we found to be eclipsed and dominated by other more recognizeable issues. We hoped to shed light on one such dispute, and perhaps gain deeper insight into why, or even how it happens. To do this, we decided to focus on the issue of gentrification. This notebook analyzes factors and elements that are present in gentrified areas, and the findings can be used to both observe and gain understanding into an issue that effects millions of people nation-wide.

Background Information:
Before we can delve into our data and deeper analysis of such a complex social issue, we will first define what gentrification is.

Gentrification:
A term for the arrival of wealthier people in an existing urban district, a related increase in rents and property values, and changes in the district's character and culture.

In general, this term is often used negatively, suggesting the displacement of poor communities by rich outsiders. In reality, the effects of gentrification are complex and oftentimes contradictory, and its real impact varies. Due to this, the true nature of gentrification is commonly disputed. There are varied perspectives towards the kinds of effects it is thought to have on the communities touched by the process. This stark contrast in opinion is particularly due to the fact that the true and lasting effects of gentrification are hard to both track and quantify.

Catogorization of Gentrification:
In today’s age, areas within the US are oftentimes sectioned off into 3 tracts: gentrified, non-gentrified, and ineligible to be gentrified. A tract is eligible to gentrify if its median household income and median home value are both in the bottom 40th percentile of all tracts within a metro area at the beginning of the decade.

Possible factors seemingly associated with gentrification include changes to crime, home value, housing income and racial diversity within an area.

Dispute and controversy:
Though there are many opinions on this complex subject, in general they can be separated out into two camps. Those who are for gentrification, and those who are against it.

In an attempt to make neighborhoods more “middle-class,” some believe that gentrification disproportionately targets underrepresented and low income families. Critics claim that gentrification (often forcefully) pushes these marginalized groups to less-privileged and oftentimes under-resourced areas, while catering to an influx of wealthy (ie white) populations.

On the other hand, those in favor of gentrification believe that the process tends to decrease crime, while adding diversity to neighborhoods that may be predominantly one race or ethnicity. This topic is one that is definitely widely contested. It still continues to affect many communities in the US today.

Clearly, gentrification is an exremely multi-faceted and complex issue. In this notebook, we will be delving into factors that we feel are closely associated with gentrified areas. From this, we will draw conclusions into what be beleive the true nature of gentrification seems to suggest.

Research Question:
How does gentrification contribute to changes in San Diego demographics? In particular, how do factors such as crime, home value, housing income and racial diversity change as a result of gentrification.

Hypothesis:
We believe that overtime, the overall rate of crime in a gentrified neighborhood does decrease, however within the overall county overall crime rates will remain constant. If these findings are true, this will seem to suggest that the crime in gentrified areas are not truly eradicated like we are led to believe--but simply displaced or distributed to other non-gentrified neighborhoods.

Approach: Testing our Hypothesis:
In order to thoroughly test our hypothesis, and answer our overall research question, we have designed a methodology that will help us both isolate and analyze gentrified areas throughout San Diego based on factors that we have created. We will define multiple indexes for gentrification, including our own. We will then see how our data analysis and findings support/reflect these different defintions.

First we will start by actually identifying these gentrified neighborhoods. We will perform this classification by separating the populations present in San Diego county into different categories. These categories will include home value, housing income, and racial diversity within each city.

Methodology for Data Collection:
Once we have identified the gentrified neighborhoods present, we will then begin to look at the crime rates associated with these areas. We will look at the crime rates present both pre-and post-gentrification, and then compare this to the overall (city-wide) crime-rates within that same time frame. With these two data sets, we will determine whether or not a particular neighborhood’s decrease in crime directly correlated to a decrease in city-wide crime as well. These patterns of crime rate over time will be used to determine if gentrification favors the idea that crime in these areas are truly eliminated, or instead simply removed and uprooted to other areas within San Diego.

While conducting these analyses, the techniques implemented will include data gathering, data wrangling and data cleaning. In terms of finding data, we referenced government websites with open data sources and pulled the available information on housing, demographics, and crime rates. These data sets are commonly found in the form of CSV or JSON; however, for data contained in excel spreadsheets, we will convert the files into CSV files. After loading both CSV and JSON files into data frames by utilizing the functions given in pandas, we will sort data pertaining to different regions by zip code or neighborhood.

Methodology for Data Analysis:
In terms of analysis, data visualization will allow us to observe relationships between different characteristics of gentrified neighborhoods. These datasets may also have outliers and other biases we need to identify and avoid. In order to examine that, we will identify the mean, median, and mode to determine the L2 errors (mean squared error) and L1 errors as well as resampling. By simply plotting the data and visualizing the data, we will be able to see certain trends and possible outliers. This methodology will allow us to sift through the large amounts of data present and isolate the points/factors that are relevant to our particular research question.

Definitions of Gentrification to be Tested:
How we define through our dataset: 
We are defining it by comparing the affordability. If low income earners used to be able to afford a place and no longer be able to afford the place over time, with adjusted annual income within each year.

How we are comparing: 
We are comparing by benchmarking with one area that low income earners could relatively able to afford and one area that low income earners cannot afford. We are comparing the changes in crime within the benchmark areas against the gentrified areas we defined.
