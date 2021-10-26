# kickstarter-Analysis

### Purpose

The purpose of this analysis is to uncover trends on the success, failure and cancelation rates of other Kickstarters given their launch dates and funding goals.

### Analysis and Challenges

Louise’s wanted to know how other Kickstarters did in other in relation to their launch dates and their funding goals since her play came really close to its funding goal. Louise had a play with a Launch date in July 2016 and was created in June 2016. Her goal was set at $2,885.00 and was pledged $2,485.00.

In order to do help Louise see how other Kickstarters did in comparison to hers I had to organize the data so that we only had the relevant information presented. What I did first was create a pivot table with the Parent Category and Years as filters and placed the Launch date in Rows, Outcomes in Columns and had a count of outcomes in the Values. See image below.

![image](https://user-images.githubusercontent.com/92561003/138615533-000adea2-ba97-4fab-bd94-e8532fd20a75.png)

What made doing the "Theater Outcomes by Launch Date" analsysis difficult and a challenge for me was at first I did not know what to use as a value in the pivot table fields. I had to play around with the different columns that would work as the values and found out that "Count of outcomes" was the correct one.

Another analysis that was done on the "Outcomes Based on Goals" worksheet. What made this difficult and challenging was that I forgot to lock the arrays using the dollar signs ($) and only noticed this when I went to drag the formula from column B to C. What I did at first was highlight the section that needed to be locked then used the hot-key Command + T to automatically add in the dollar signs. I then realized that I could just click the cell, then highlight the formula and press the hot key to lock the whole formula. See images below

![Not Locked](https://user-images.githubusercontent.com/92561003/138615556-7ddc3af0-ebbe-429b-b61a-4cdebd9da025.png)

![Locked](https://user-images.githubusercontent.com/92561003/138615561-9c94567d-6fd2-4903-8d27-7654ef096a8a.png)

### Results

#### Conclusions Drawn

A conclusion I was able to draw from the Theater Outcomes by Launch date is that in May and June had the most successfully funded theater Kickstarters compared to other months in the year. This can been seen in the graph, Theater_Outcomes_vs_Launch.png.
Another conclusion that I was able to draw is from June to July and November to December the amount of theater Kickstarters that failed went up compared to the previous month while number of successfully funded theater Kickstarters went down compared to the previous months. In all the other months if the rise or fall in successful or failed theater Kickstarters went in the same direction.

One thing that I can conclude from the Outcomes based on Goals analysis is that play Kickstarters would have a lower success rate the higher their goal was after with the exception to the $35,000.00 to $39,999.00, $40,000.00 to $44,999.00 and Greater than $50,000.00 range.

#### Limitations

A limitation to the Theater Outcomes by Launch Date dataset is that it does not show the overall rate of success, failure and cancelation are for a given month. It also doesn’t show the average rate of success, failure, and cancelation are for a given month. This would be helpful to see when the most successful months compared to the averages are so that you can know what months have the highest rates are.

What would be helpful would be to see is another column of the rates of success, failure and cancelation for the given months compared to the total number of theater Kickstarters. Then another column showing the plus or minus to what the average success, failed and canceled rate is.

Something else that would have been helpful is if the kickstarter types were both comparing the same type of kickstarter and not two different types so that you could see the rates of success, failure and cancelation for the given month in the “Theater Outcomes by Launch Date” analysis. I would include two pivot tables that have the same criteria except have on filter for Theater and the other filter for Play. I would also change the sheet name to Play and Theater Outcomes by Launch Month. 

The same can be said for the Outcomes based on Goals. I would include two different tables that had one for plays and one for theater to see the success, failure and cancellation of each goal range.
