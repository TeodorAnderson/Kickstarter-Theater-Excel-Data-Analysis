# Mod1KickstarterTanderson
 
# Kickstarting with Excel
 
## Overview of Project
 
### Background
 	
  	Louise, an aspiring playwright, wrote a play called *Fever* and predicts that it will cost about $10,000 to produce. Unfamiliar with the market and data on crowdfunded campaigns she asks an excel data analyst, myself, for assistance.
 
### Purpose
 	Using a large data set on crowdfunded kickstarter campaigns, I will provide the client with helpful visuals, data subsets and analysis on successful and failed campaigns, and how their date of start and duration, geographical region, amount of backers, funding and goals have affected their outcome.
 
## Analysis and Challenges
 
### Analysis of Outcomes Based on Launch Date
![Outcomes of DatesPivot Table](https://user-images.githubusercontent.com/116928193/203170867-665b01b9-e658-4df1-b2ef-e77f7e945b5e.png)
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/116928193/203160358-c2d14975-8f68-4aab-97be-946ca64a67ed.png)
 
 	 In the line graph featured above, the failed campaigns show a steady year round pattern in all regions, save a drop in failed outcomes in September, a small spike in October and back to normal in November and december.
 	The successful campaigns however show a very high spike in May, with the return to normal lasting until september. 
 	It is possible that lower consumer spending during the warmer months correlates to a higher drive to both invest in plays as well as attend them.
 
### Analysis of Outcomes Based on Goals
![Goal Outcomes Pivot Table](https://user-images.githubusercontent.com/116928193/203170843-96ed9637-8f87-4493-a57f-107c04b3844a.png)
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/116928193/203162896-9768e493-f5b8-4edc-9f84-f0b8fdef717b.png)
 
In the line graph shown above, we can come to the conclusions that successful campaigns with the lowest goals tend to do better, with a spike at the monetary goals of above $35,000, no successful plays at $45,000 and only two plays succeeding at above $50,000.
 
### Challenges and Difficulties Encountered
 	When creating a subset of data for plays in Edinburgh, I had a challenge using the VLOOKUP function calling data on average donation, specifically not understanding why my third value was not referring to the column on the original worksheet. For example when coding =VLOOKUP(A2, Kickstarter!B:T, 15, FALSE), I was trying to draw data from column P, the 16th letter and receiving the wrong data. I figured out that the value of the 3rd function started looking from where the second function began searching, in this case B:T.
 	I also had challenges as a first time excel user being careful with the cells and functions, as my subsets in Descriptive statistics were not matching the examples given in the modules, I restarted the project from the beginning more carefully and they matched the second time.
 	Another problem I encountered was that when creating graphs, like the Outcomes Based on Goals for example, my graphs would portray too many values and the ranges of donations were in the Y axis, instead of the percentages. Right clicking and hitting select data allowed me to pick the right variables to show as well as switching the X and Y axis.
 
## Results
### Conclusions about Outcomes based on Launch Date
 Successful campaigns are on average 29 to 32 days, and for the highest statistical outcome Louise should start her in May.
### Conclusions about Outcomes Based on Goals
The most succesful campaigns have the lowest goals, less than $15,000, and if not she should reach high for $35,000, as shown in the data.

### Limitations of the the Data Set
Some limitations the data set has are its lack of information about how each succesful campaign performed as a return on interest.
### Other possible graphs
More graphs we could create are two histograms below showing the lengths of time successful and failed campaigns take, giving Louise useful parameters in how long her campaigns should take
 ![Sucessful Camp Histogram](https://user-images.githubusercontent.com/116928193/203169402-8401e2e3-0506-4c51-b9e9-52943efdf68c.png)
 
![Failed Histogram](https://user-images.githubusercontent.com/116928193/203182906-3d7afd23-b30c-4b08-bbfd-b655452ed5db.png)

 
 
 

 
 
 
 
 
