# Australia-Gender-Pay-Gap
Redesign Project - Fall 2017(focused on gender pay gap in Australia)

It will take 50 years for women to be paid equal to men if significant changes are not made, a Government agency has warned.

RESEARCH ON TOPIC -> 
BACKGROUND: https://www.wgea.gov.au/addressing-pay-equity/what-gender-pay-gap

During my research I found that factors like discrimination, childcare and industrial segregation drives the disparity between gender wages. To dig deeper I followed a few articles to understand the reason for this unequality.

-	Industrial Segregation:
According to Workplace Gender Equality Agency (WGEA) report, female-dominated organizations like healthcare and social assistance tend to be paid lower in Australia. Various government policies has taken place in previous decade to strike balance between gender payrates. 
This visual shows the percent decrease/ increase in the pay gap compared to previous year, based on industry. It is a very good visual if the aim is to show that we are heading in right direction with this problem. But it fails to explain the factors affecting the change, also no actions can be suggested based on mere its visual. 

![ScreenShot](https://user-images.githubusercontent.com/32226479/32413109-95196ca4-c1c7-11e7-9075-424e9a6beb26.png)

-	Childcare:
Mothers are less likely to be hired for jobs, to be perceived as competent and paid as much as their male colleagues with same qualifications. Fathers on the other hand are perceived to be more stable and committed and mothers more distractible. Employers need to understand the reality and change the old notions in their mind.

-	Discrimination:
As per PwC’s CEO Succession study, only 9% of CEO appointments at world’s 2500 largest organizations comprise of female candidates in Australia. 

REDESIGN FOCUS -> http://www.womensagenda.com.au/latest/eds-blog/australia-s-50-highest-paying-jobs-are-paying-men-significantly-more/

Data from Australian Tax Data reveals gender pay gaps in same occupation. It is fair to use a table to show the job payments according to gender. But in my view the same dataset could be used in a better way to make a claim as well as inspire an action. The dataset includes average taxable income, gender, individuals working, occupation. This data could be used to show the difference between individuals working in organizations vs pay gap in those organization. Using this information, we can analyze how change in gender ratio in an organization impact pay gap based on which we can draw conclusions and suggest actions.

![ScreenShot](https://user-images.githubusercontent.com/32226479/32413116-e53410a4-c1c7-11e7-834f-bcb4b4e99248.png) ![ScreenShot](https://user-images.githubusercontent.com/32226479/32413121-fe317ed4-c1c7-11e7-9633-62a730ea9c3e.png)

WORK DONE ->
The dataset provided was inconsistent with the result I was expecting. 

![ScreenShot](https://user-images.githubusercontent.com/32226479/32413125-16fc7298-c1c8-11e7-98e4-37df18abc876.png)

I needed to add new columns using the data of only 1 column. Eg. I wanted a female income & male income column instead of average taxable income and I wanted female workers & male workers instead of individuals to calculate the differences and compare. 
I tried various methods and applied various syntaxes to get the desired result but failed. Finally, I manually updated the data in excel sheet and computed the differences into a different column.

![ScreenShot](https://user-images.githubusercontent.com/32226479/32413128-2a4b8640-c1c8-11e7-8c52-0f56a634a9cf.png)

Finally, when I compared these 2 differences (individuals working vs pay gap), the graph was not showing data points in the visualization.

To test and try why the data was not showing I added the original dataset with the updated one to see how is it showing the data.

![ScreenShot](https://user-images.githubusercontent.com/32226479/32413138-5e733e7c-c1c8-11e7-8b0b-3861cd596a31.png)
![ScreenShot](https://user-images.githubusercontent.com/32226479/32413140-6a67c39c-c1c8-11e7-97ac-57c8ca0e0035.png)
![ScreenShot](https://user-images.githubusercontent.com/32226479/32413146-7c663c72-c1c8-11e7-935b-e2054396b814.png)

Finally, after trying various column combinations I could get to the point which I wanted to make from the graph. 

![ScreenShot](https://user-images.githubusercontent.com/32226479/32413160-a1e43b66-c1c8-11e7-9bcb-d13c31e29e40.png)

CLAIM: Pay Gap in organization decreases with the decrease in gender ratio

VISUALISATION: https://public.tableau.com/profile/sanjana.thakur#!/vizhome/Redesign_Project_0/PayGapreducesasthedifferencebetweenmalesfemalesworkingreduces?publish=yes

WARRANT: http://data.wgea.gov.au/industries/1

ACTIONS: 

	Identify income disparity to solve the problem. Make your progress publicly known.

	Set equal pay for same job, same qualification.

	Introduce strict equal gender strategy & policies.

	Include family friendly workplace

References:

http://www.abc.net.au/news/2017-07-26/gender-pay-gap-women-could-be-paid-less-for-another-50-years/8745690
https://www.wgea.gov.au/sites/default/files/BCEC%20WGEA%20Gender%20Pay%20Equity%20Insights%202017%20Report.pdf
https://www.theguardian.com/australia-news/datablog/2017/oct/18/australia-gender-pay-gap-why-do-women-still-earn-less-than-men
https://www.nytimes.com/2014/09/07/upshot/a-child-helps-your-career-if-youre-a-man.html
https://www.wgea.gov.au/sites/default/files/wgea-business-case-for-gender-equality.pdf

