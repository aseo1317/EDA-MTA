# Project Gala MVP

At its core, the goal of this data analysis is to maximize the potential signatures (and potential donations) the street team of WTWY can gather for its organization. Using MTA turnstile data, we have done some preliminary analysis of traffic patterns. 

<p align="center">
    <img src="https://user-images.githubusercontent.com/89528655/133327202-2db973cd-30a2-4aa7-a1f8-a8a057bfddc3.png" />
</p>

This bar chart shows the ten subway stations with the most total entries during roughly a three-month period. The data mostly squares with what we know about the stations themselves. For example, the leading station of 34 ST Penn Station serves not only as a station for two of the MTA's most used subway lines in the 123 and ACE but also as a hub for travelers from outside the city who will then in turn use the subway. The 2-4 stations share similar characteristics in that they are dually purposed as subway stations and general transportation nodes. These four stations seem like strong early contenders to place WTWY's street team. 

The next three stations don't fall into the same category as 1-4. They are stations that at first glance have only one subway line or at most one subway group of lines (e.g. 123). Further analysis shows that these high figures are a result of cleaning the data by station name. However, there are multiple stations named for each of these streets (3 for 86th, 5 for 23rd, 4 for 125th). For example, the total for 86th St represents the sum of **three distinct stations** on Broadway, Central Park West, and Lexington Ave, respectively. We can exclude these three "stations" from our initial recommendation as it is impossible to determine if any single station is driving the totals. 

One notable absence in this chart is Times Square, which came in at 11th. This is a puzzling result but may be attributed to the decrease in tourists due to the COVID-19 pandemic.

<p align="center">
    <img src="https://user-images.githubusercontent.com/89528655/133327331-e43cb11f-ec84-41ed-b3b7-921343ca0859.png" />
</p>

This second chart shows the total entries of the same three-month period except instead of by station it is by the day of the week. Unsurprisingly, the weekdays outpaced the weekends led by Wednesday, Tuesday, and Thursday. This data makes sense as there are fewer out of city commuters on the weekends and Mondays and Fridays are either holidays or vacation days taken to make a long weekend.  

Our initial recommendation is to position the street teams at the first four stations and then 14th Street Union Square on a weekday (with emphesis on Tuesday-Thursday). Further data cleaning may be beneficial to determine how the data changes when parsed by linename and station and not just by station name. 

