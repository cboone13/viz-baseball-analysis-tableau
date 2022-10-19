# Udacity_tableau_baseball_analysis
Udacity data analyist nandegree - data visualization project that demonstrates how to use tableau to analyze a data set and tell a stroy from that data. 

### Tableau Initial Story Link: https://public.tableau.com/profile/chris.boone#!/vizhome/UdacityCreateaTableauStory-BaseballDataSetv1/Story1

### Tableau Final Story Link: https://public.tableau.com/profile/chris.boone#!/vizhome/UdacityCreateaTableauStory-BaseballDataSetv2/BaseballPlayerPerformanceBasedOnHandedness

## Summary

Using the baseball data set which contains 1,157 players (737 right handed, 316 left handed, and 104 both handed) I am going to create a story that shows my exploration of the data to determine if left, right, or both handed hitters have a higher average performance.

## Design

On all visualizations I linked each one so that it would filter the highlighted group on each page for each viz when a group is selected.

1) I chose to use a donut chart to show percentage of each handedness out of the total. It gives a visually appealing way to show how much of the total number of players exist of each handedness.

2) I also used a bar chart for this so that it made it more clear the differences between the groups.

3) For height and weight, I used a scatter plot with an average line. I used this to give a solid visual representation of the correlation between height and weight of players as well as the distribution.

4) I created a scatter plot showing each players HR to Avg correlation. I included the average lines for both that shift based on which group is selected. This helps to show the central average as well as the independent averages of HR and Avg of the groups of players.

5) I used a bar chart with marks to show the average batting average for each group based on the player height. This allows us to see if height has an impact on batting average. It also shows us there is there is a downward trend. As players get taller, their batting average goes down.

6) I included a cross-chart underneath the avg batting average vs player height by handedness as I though it may be confusing for the reader when not filtering by group to compare the marks (avg batting avg) for each height.

7) Conclusions: I broke each batting group out and put, what I believe gave the best visual representation of the averages, side by side. I fixed the axis so the graph lines were matched up and therefore comparable.

## Feedback

**1) Storyline font is smallish, perhaps even bolding would make it stand out more.**

    Action: Increased font size and boldness.

**2) Storyline box size hides some info - could make  graphs smaller and storyline box larger (is that even possible)**

    Action: Increased height of story points.

**3) Handedness legend: did you set it up so that the majority color is brighter - note the blue and gold are barely visible. Perhaps that was on purpose**

    Action: This was due to the chart starting with a group already selected so it was filtering. I
    deselected so that no group was selected when first viewing the chart for batting
    average vs home runs.

**4) Verify your conclusion to me it looks like left then right and then both handers**

    Action: Corrected the wording to accurately reflect the visualizations.

## Resources:

https://github.com/gaurav214/Udacity_Tableau_Project