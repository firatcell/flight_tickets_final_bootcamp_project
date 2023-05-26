# Airline tickets project
The data was downloaded from Kaggle posted by Barking Data an online web data mining provider.<br />
Data source: https://www.kaggle.com/datasets/polartech/flight-data-with-1-million-or-more-records/discussion?resource=download<br />
Tableau: https://public.tableau.com/app/profile/firat6571/viz/Final_Bootcamp_Project/Modelling?publish=yes<br />

## Objectives
Find what determines price.<br />
What is the relationship between Price and Stops?<br />
What is the relationship between Price and Duration?<br />
What is the relationship between Price and Emissions?<br />
What is the relationship between Price and Time?<br />
What other relationships can we see? <br />

## Findings
An analysis of the data reveals that, on average, as the number of stops increased, so did emissions, duration, and price. However, these trends showed a drop-off towards the end.<br />

Interestingly, customers showed a preference for flights with two stops, as indicated by the total emissions and sum of stops.<br />

Contrary to popular belief, the data showed that flights with more stops could actually result in higher prices.<br />

It is important to note that these trends are likely influenced by longer flight durations. Flights with fewer stops tended to have longer durations, which may explain the observed patterns in emissions, duration, and price.<br />

Emissions appeared to be a significant factor, along with the hour of the day, in determining price. However, it was challenging to accurately identify seasonal changes based on the data.<br />

In summary, the data analysis suggests a complex relationship between the number of stops, emissions, duration, and price. Further investigation is required to gain a deeper understanding of the underlying factors driving these relationships and to pinpoint seasonal variations accurately.<br />

## Evaluation
My data was susceptible to outliers and extreme values, so in future, I need to employ stricter data cleaning processes.<br />
This happened because I deliberately chose to include all data points initially to maintain accuracy in my modelling, but it compromised the dataset's reliability.<br />
While accuracy is vital for maintaining measurement fidelity, reliability ensures consistent and stable results. <br />
By recognising this trade-off, I can improve analysis quality and increase confidence in future findings.<br />