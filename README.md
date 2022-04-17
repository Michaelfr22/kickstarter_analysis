# Kickstarting with Excel

## Overview of Project

	In this first Challenge, I used the Kickstarter dataset to visualize campaign outcomes based on their respective **Launch Dates** and **Funding Goals**.

### Purpose

	For the First Deliverable, the relationship between **Launch Date (Month)** and **Number of Outcomes** was analyzed to understand which months represent a higher rate of Successful Outcomes in * *Theater* *.
	The Second Deliverable presented the relationship between the **Funding Goal** and **Portion of Outcomes** that lead to successful and failed * *Plays* *.
	Both Deliverables are visualized by using Line Graphs to demonstrate how the Number, or Percentage of Successful Outcomes changed depending on the time of year and varying Funding Goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

	In order to visualize the relationship in question for the First Deliverable, a pivot table was generated to display the quantity of Successful and Failed Outcomes by Month.
	The Kickstarter dataset was then filtered by Parent Category to only display the quantities of outcomes regarding Theater data.
	The pivot table provided the initial glimpse into the Outcomes "pie" with the Successful, Failed, and Canceled categories being the "slices".

### Analysis of Outcomes Based on Goals

	In order to visualize the relationship in question for the Second Deliverable, a second sheet (Outcomes Based on Goals) was created with the purpose to separate the number of Successful, Failed, and Canceled projects into Funding Goal "buckets".
	These "buckets" were labeled by increasing amount ranges, such as "less than $1000", to "$1000 to $4999", up to "greater than $50000".
	The finalized product of the Outcomes Based on Goals sheet calculated the percentage of Successful, Failed, and Canceled projects within each Funding Goal bucket.

### Challenges and Difficulties Encountered

	One potential challenge for the First Deliverable was ensuring that the pivot table was formatted and filtered correctly.
	If the Theater data was not separated by Month, the line chart would not have displayed the neccesary information to understand the dataset.

	The main difficulty encountered during the formation of the Second Deliverable was avoiding gaps and overlaps in the Funding Goal buckets.
	If any gaps or overlaps existed, the data would not be organized correctly; thus making the associated line chart inaccurate and misinformed.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

	1) Successful and Failed Theater outcomes followed a similar month-to-month trend: increasing in Feb, April, May, and Oct, WHILE decreasing in Mar, Jun, Sep, and Nov.
	2) Successful Theater Outcomes peak annually in the month of May with its lowest point in Dec.

- What can you conclude about the Outcomes based on Goals?

	1) The deeper one looks into the data, one will notice two pockets of data where particular Funding Goals lead to more Successful Outcomes (Increasing Funding Goal does NOT CORRELATE to Successful Outcomes).

- What are some limitations of this dataset?

	The Kickstarter dataset can be used as reference when selecting an optimal Launch Date and Funding Goal for an event campaign, but since the data is merely a SAMPLE one should not "live or die" by the results of this project. Incorporate other resources.

- What are some other possible tables and/or graphs that we could create?
	
	It would be interesting to see the Successful Outcomes broken into categories to represent which ones have a higher rate of success.
	This could be a Pie Chart to understand the portions of each category and their respective Success.
	This could also be a Bar Chart to display the rate of successful outcomes (Successful outcomes DIV BY total outcomes) for each project category for comparison purposes.
