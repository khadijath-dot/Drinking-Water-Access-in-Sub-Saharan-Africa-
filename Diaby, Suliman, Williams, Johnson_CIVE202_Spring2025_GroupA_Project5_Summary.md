Project \#5 Summary

Group Members: Mallory Williams, Khadijath Diaby, Manal Suliman, and Lilee Johnson

Due by May 9, 2025

Table of Contents

[Technical Executive Summary](#technical-executive-summary)

[Non-Technical Executive Summary](#non-technical-executive-summary)

[Methods](#methods)

[Results](#results)

[References](#references)

Table of Figures

[Figure 1 - Scatterplot of drinking water access by country over time for safely managed water sources](#_Toc197727241)

[Figure 2 - Scatterplot of drinking water access in Sub-Saharan Africa for safely managed water](#_Toc197727242)

[Figure 3 - Bar chart of unimproved water sources in 2000](#_Toc197727243)

# Technical Executive Summary

The goal of this project is to analyze the drinking water access across Sub-Saharan Africa using the JMP WaSH Database. The Water Project, a non-governmental organization, works to bring access to drinking water to countries globally. The organization wants to determine how to fill the gaps in access to drinking water. The analysis will show the difference in drinking water access over time. A comparison of the countries will be shown using a time-series plot. The data will be filtered by country and coverage to show the access to drinking water in Sub-Saharan Africa.

# Non-Technical Executive Summary

The goal of the project is to analyze the drinking water access in Sub-Saharan Africa. Using Python, comparison in drinking water over time will be shown with plots. There will be interactive plots to make it easy for viewers to understand. The types of households compared to population will be discussed. Scatterplots will show the changes in drinking water access over time.

# Methods

The Water Project, a non-governmental organization (NGO), had hired Group A to examine the Joint Monitoring Programme (JMP) household water access dataset, Group A is asked to analyze trends in drinking water access and compare results between countries over time. JMP maintains the global data on Water Supply, Sanitation, and Hygiene (WaSH) database. The data used is collected from Sub-Saharan Africa, and it reflects the progress toward Sustainable Development Goals related to water and sanitation. Group A acquired data in the form of comma-separated value files (CSVs) which will be uploaded to Python software to conduct the analysis. Two files were taken from <https://washdata.org/data>: (1) household water access dataset by region and (2) household water access by country. Python software will be used to aid the analysis, but it will also help clean up and organize the datasets. This includes interpolating not available (N/A) values and correcting the data type in each column.

The first figure studied country vs service level and complied the scatterplot by year, coverage, and country. This was done so we can analyze drinking water access with safely managed service across Sub-Saharan countries from year 2000 to 2022. The Water Project can use what we found to compare how access to drinking water has changed over time. The second figure is another study similar to figure one. Its variables are year, coverage, and residence type instead. It is important for us to also compare resident type so The Water Project can make any correlations as needed to compare results over time.

-   Code and functions we used

# Results

The very first graph we created was plotting the year against the percent coverage while grouping by country to visualize changes in access to safely managed drinking water services. Immediately, you can see the vertical clusters in each year. One explanation for this is that there are so many countries in the dataset that have a percent coverage below 50%. This means that the countries with a lower coverage in the beginning, the earliest year the data was taken, mostly maintained that level until the end data of the dataset. The countries below the 50% line that do increase in percent reach experience a slight incline. This observation implies that their progress in expanding access to safely managed drinking water services is and will remain limited over time if intervention is not undertaken.

![A graph of water access AI-generated content may be incorrect.](media/a5679322ccc31493fe0b9bc6765bb93b.png)

Figure 1 - Scatterplot of drinking water access by country over time for safely managed water sources

Chad, according to Figure 1, appears to have the lowest percent coverage of safely managed water sources. The reach stays consistently below 5% throughout the whole graph. There are many reasons for this, one of them being the fact that Chad is a landlocked country. A landlocked country is a nation that does not have a border that touches an ocean or a sea that directly connects to an ocean (Johnston, 2025). As a landlocked country, Chad has no coastal ports which makes it difficult to and costly to import water treatment equipment, parts, and chemicals for infrastructure. Chad also heavily depends on Lake Chad which is currently shrinking and has been since the 1960s. The lake has lost over 90% of its surface water since the ‘60s from climate change and desertification. These are just a few reasons why Chad has the lowest coverage in terms of safely managed service levels. Chad isn’t the only country with extremely poor coverage. We must find a way to mitigate the geographic location and characteristics of these countries.

In Figure 1, there is a large gap, closer to the top of the graph, starting from 2000 and widening towards 2015 before it ends up closing. On the surface, it may seem as though there is an absence of water services. In reality, it’s most likely a lack of available data during that period. The lack of data reflects changes in criteria for what really constitutes as “safely managed” drinking water. After Sustainable Development Goals (SDGs) were adopted in 2015, the new standard for safely managed drinking water included that water sources be located on premises, readily available, and not contaminated. With that being said, we think countries that had really good coverage before 2015 should be monitored from time to time since the standards did change, creating that massive gap in our graph.

![A graph of water access AI-generated content may be incorrect.](media/bdea09085ec4a27bf11e3e957f0edfd3.png)

Figure 2 - Scatterplot of drinking water access in Sub-Saharan Africa for safely managed water

Once we saw the amount of countries with outrageously low coverage for safely managed water and the overall low coverage in rural areas (Figure 2), with a little bit of knowledge and research, we concluded that most of the countries below the 50% coverage line are rural. With that in mind, we decided to go study further in some of these countries. If these countries had an extremely low coverage for the best water source available in the database, they might have higher coverage for one of the worst water conditions: unimproved service levels. We made an interactive bar chart graphing country against the percent access grouped by residence type (Figure 3). We wanted to better examine countries that have little to almost no access to good water. The red bars indicating rural residence range from really tiny and obscure to above most of them going above 40%, just what we predicted. In almost every country, rural bars are significantly higher taller than urban bars. Countries with extremely high rural unimproved coverage (\>50%) in 2000 include Mozambique, Rwanda, Togo, and Sierra Leone and these align with the low-coverage countries from Figure 1. Other countries, like Botswana and Seychelles, have low unimproved urban coverage. This suggests that urban infrastructure was already developed by 2000.

![A graph of water coverage AI-generated content may be incorrect.](media/81b068b9e7f72ce2ef3e78cc9e820ec8.png)

Figure 3 - Bar chart of unimproved water sources in 2000

Figure 3 really reinforces the fact that structural rural disadvantages do exist and have a large effect on water access in Sub-Saharan Africa. This could be from lagged investments or conflicts (UNICEF). At least half of the countries on the graph have been experiencing violent conflicts since even before 2000. For instance, Angola and Burundi underwent a civil war that ended in 2002 and 2005, respectively, Eritrea and Ethiopia experience a border war from 1998-200, Rwanda dealt with post-genocide instability, etc (SIPRI). Many water infrastructures like pipelines and wells were often destroyed during hostilities. These conflicts led to mass displacement, placing added pressure on water resources in communities and camps “taking in” the displaced people. Additionally, these camps and communities were blocked from getting any aid. Any government resources were redirected to military expenditures.

After thorough analysis, the findings will help The Water Project by giving them a way to show:

-   Drinking water access with safely managed service across Sub-Saharan countries from 2000 to 2022
-   Unimproved service levels in 2000 and in 2022
-   Safely managed service levels in 2000 and in 2022

Scatter plots were used to show drinking water access by country and across Sub-Saharan Africa. The Water Project can use these scattered plots to show the reasoning of their effort focus to shift towards Sub-Saharan Africa. They can also use these scatter plots to determine how access to drinking water has improved over time and if there are any gaps in access.

Interactive bar graphs were used to show unimproved water coverage by country and residence type in 2000 and in 2022. The Water Project can use this data to see and show if countries that had unimproved service levels in 2000 improved by 2022. They can use this to persuade others that these areas need to be in line to receive improvements.

Interactive bar graphs were also used to show safely managed service levels in 2000 and in 2022. This data can be utilized by The Water Project to study and present which countries have safely managed service levels. They can compare information from 2000 to 2022 to see which countries improved, worsened, or stayed about the same. They can then adjust their focus to more at risk countries.

Together The Water Project can use these findings to help them justify their focuses on bringing drinking water service access to Sub-Saharan Africa.

# References

“7. Armed Conflict and Peace Processes in Sub-Saharan Africa \| SIPRI.” *Www.sipri.org*, www.sipri.org/yearbook/2020/07.

Johnston, Ron. “Geography \| Definition, Types, History, & Facts.” *Encyclopædia Britannica*, 19 Apr. 2018, [www.britannica.com/science/geography](http://www.britannica.com/science/geography).

Unicef. “Progress on Household Drinking Water, Sanitation and Hygiene, 2000-2020.” *UNICEF DATA*, 1 July 2021, data.unicef.org/resources/progress-on-household-drinking-water-sanitation-and-hygiene-2000-2020/.
