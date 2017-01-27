# An Examination of 2014 VISA Applications.

## Question 1: Which companies applied for the most H1B visas in NYC?A foreseable issue when summarizing the data by employer name would be inconsistencies/errors in spelling (e.g., INC v. INC.).

[See .ipynb]

##  Question 2: Are the wages statistically different between NYC & Mountain View? What could explain the results?

The average wages between the two are significantly different. Seems likely that the companies in each location are different and pay differently; especially considering how Google is based in Mountain View.

...Yep, Google applies for the most H1B visas in Mountain View by a sizeable margin. If Google pays their employees on average more than other companies, that's likely the reason Mountain View has a higher mean salary. 

## Question 3: For NYC, what is the relationship between the total number of H-1B visas requested by an employer and the average wages proposed? Is the relationship statistically significant? What might explain this relationship?

There isn't a significant relationship between the number of H1B visas requested by an employer and the average wages proposed. The wages of H1B visas appears normally distributed, so taking a subsample (a company with multiple applications) is likely to approximate the population mean (i.e., the central limit theorem), and not give a meaningful relationship. Only if companies applying for VISAs consistently took a non-representative subsample (e.g., Bloomberg only taking on high paying employees), should there be any kind of relationship.

# Brainstorming
This dataset could be used to answer a variety of interesting questions, like: 

1. What industries apply for the most H1B visas (i.e., what industries have the biggest domestic talent gap)?
2. What countries are successfully training their citizens for in-demands jobs (i.e., where are applicants coming from and for what purpose)?
3. Between the visas offered are there different 'types' (i.e., clusters)?
4. In conjunction with domestic employment data, this data could be used to see if any companies are abusing the VISA system (e.g., are they hiring foreign professionals at a lower salary then domestic professionals).
5. Do different companies hire different nationalities?
6. Where are these VISAs spread out around the US.

# Exploration
I'm a Canadian in New York, so lets see who I should be sending my resume to. In other words: 

## Question 4: What company in New York paid the most for Canadian professionals in 2014?

...Well, looks like banking and consulting is where it's at for Canadians in NYC. This wasn't particularly insightful though... lets see how VISAs are distributed around the US.

## Question 5: What states applied for the most visas in the continental US in 2014?
As seen, California, Texas, and New York all apply for the most VISAs. They all have the large populations, so do they really apply for the most VISAs per capita?

## Question 6: What states applied for the most visas per capita in the continental US in 2014?

As seen, Washington and New Jersey have the most applications per 100,000 residents. Let's see if this is significant... 

Whoa, didn't even see DC on the map. But, DC, Washington, and New Jersey all apply for significantly more VISAs per capita than other US states (α=0.05).