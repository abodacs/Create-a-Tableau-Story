# Prosper Loan Data visualization using Tableau

[Explore Prosper Loan Data -- before Feedback](https://public.tableau.com/profile/abdullah1192#!/vizhome/ProsperLoanDataVisualization-V1/Story?publish=yes)

[Explore Prosper Loan Data -- after Feedback](https://public.tableau.com/profile/abdullah1192#!/vizhome/ProsperLoanDataVisualization-V1/StoryV2?publish=yes)

## About

Prosper is a peer-to-peer lending platform that aims to connect people who need money with those people who have the money to invest. In this data analysis project, In my Tableau story I have done exploration on the relationship between loans and the people acquiring them, the reasons for taking out a loan and who defaults the most. I have given a brief insight into the people acquiring loans by looking at the debt levels by state. I explored the reasons that people have for taking out loans as well as who is most likely to default based on their occupation and income range. Breaking down the number of defaulters by occupation it seems that college student have the highest borrower and default rates.

## Dataset

The Prosper loan data set contains 113,937 loans with 81 variables on each loan,
including loan amount, borrower rate (or interest rate), current loan status,
borrower income, and many others. The dataset and data-dictionary can be found at the links below:

* [Udacity hosted dataset dataset](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)
* [Prosper Loan Data - VariableDefinitions](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)

## Summary

Personal online loan business has been an important way for borrowers to raise money and for investors to earn interest. In this story, we explored many aspects for personal loan business based on the [Prosper](https://www.prosper.com/plp/about/contact-us/) Loan Dataset, including the default rates across different states of US, sereval factors which have clear impact on default rate, etc. Moreover, this analysis showed that higher risk loans don’t guarantee higher return so a useful tip for investors was given

## Design

* **Online Personal Loans Climbed Up Over time While Credit Score Went Down** Line Chart;
* **Default Rates for Different States of US have Obvious Variance** Thematic Maps.

In order to see whether each state had the similar tread or not, I chose to use different colors to stand for different state

* **Higher Income means Lower Default Rate** Bar Chart;

* **Better Credit Rating means Lower Default Rate:** Stacked Bar Chart, with one bar for each ProsperRating and using color to stand for each IncomeRange within that ProsperRating loan.

* **DefaultRate vs BorrowerRate:** Scatter Plot, with using color to stand for each Occupation, and I added a filter for different ProsperRating
  Default rate of the College Student: I used two Bar Charts to show the loans number and defualt rate for different grade of the college
* **College Student:** Two Bar Charts to show the loans number and default rate.
  Higher grade students would have more loans and lower default rate, with exception for sophomore student

## Feedback

I shared my first sketch on Udacity slack group and sent it to two of my friends.

1.  In your first graph where you have map was to not very obvious.

2.  In your third dashboard title was not visible properly. - rahul_kumar

3.  In Default rate & BorrowerRate for each Occupation graph filter for "Other" was hidden.

4.  For each dashboard please write a short description about your graph.You have mentioned 1,2,3,4,5 - rahul_kumar

## Resources

* [Prosper About.](https://www.prosper.com/plp/about/contact-us/)
* [Prosper Loan Data Project on Kaggle.](https://www.kaggle.com/jschnessl/prosperloans)
* [Repo on the same project.](https://github.com/yajiez/create-tableau-story)

- [Udacity Tableau Course.](https://www.udacity.com/course/data-visualization-in-tableau--ud1006)
- [Tableau Tutorials.](https://www.tableau.com/learn/training)
