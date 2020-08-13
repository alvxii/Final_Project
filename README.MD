# Dark Money
## by Alex de Almeida

For my final project I chose to interrogate data from OpenSecrets about dark money and the 501(c) organizations that receive and spend these funds on American politics.



OpenSecrets is a nonpartisan, independent and nonprofit research group that tracks money is U.S. politics and its effect on elections and public policy. OpenSecrets has readily available data sets for download in csv format throughout the site. Upon entering the site I was immediately drawn to the sinister looking section “Dark Money”. 501(c) organizations, nonprofits, are not required to disclose their donors while they spend millions to influence political outcomes; when they decide not to disclose the source of their funds, it is considered dark money. OpenSecrets tracks how the funds are spent through annual IRS 990 forms, although disclosures on the forms can be vague.



I downloaded the <a href="https://www.opensecrets.org/dark-money/process">csv </a> file for the political spending percentages, and began my process of cleaning up the data. The file happened to be in excellent shape, but I decided I wanted to constrict the information. The most recent annual records in the chart are the year 2014, but I decided to focus solely on the last election year available, 2012. I used a filter on the dataset in Google Sheets to select data within the dates 1/1/2012 – 12/31/2012. Considering there were still over 1600 rows of data I decided to create several pivot tables to separate some of the columns and assess the numbers. I created three pivot tables with the first column remaining the same in all three, donors. Then, I added IRS Total Spending, FEC Total Spending, and SUM of FEC Political Spending w/ Recipients Total.

<img src="https://media.journalism.berkeley.edu/upload/2020/08/1597211851780e856.png"/>
<img src="https://media.journalism.berkeley.edu/upload/2020/08/15972119048a27751.png"/>


I set a condition to show values greater than 5 million in the pivot tables containing IRS Total Spending and FEC Total Spending to constrict the data to show the top spending donors in 2012. As you can see above the list of donors and spending on both charts are very similar.

The top donor list of FEC Political Spending with Recipients is radically different as the only donor listed in the former charts and the latter is Crossroads GPS. American Crossroads is a Super PAC that raises funds from donors to advocate for certain candidates of the Republican Party. It has pioneered many of the new methods of fundraising opened up by the Supreme Court's ruling in Citizens United. I thought it goes to show that it's extremely difficult to pinpoint where these funds are being spent.




<img src="https://media.journalism.berkeley.edu/upload/2020/08/15972126324c39df2.png"/>



I feel it's necessary to include the overall percentages out of the total expenditures for each of the FEC Spending Totals becuase by law these 501(c) organizations are required to spend under 49.9% of their total expenditures on political spending. The issue with this is that political spending is such a vague term that many of these organizations find loopholes to exceed that threshold without categorizing their spending as "political". Funds spent on Ad production and TV air time that do not explicitly call to vote for or against a candidate and air more than 30 days before a primary and 60 days before a general election are not required to be reported to the FEC. The highest ranked spending 501(c), the NRA, spends roughly 250 million a year and yet they claimed to spend about 9 million for political spending, or roughly 3% of their budget. 

<img src="https://media.journalism.berkeley.edu/upload/2020/08/159721392573214bc.png">

I thought the project led to some fascinating insights into how these 501(c) organizations have taken advantage of different loopholes in the law to spend millions on influencing political elections. Because their is no concrete way to determine where these funds are being spent, at the moment it's not possible to quantify their effects. I think it shows that moneys involvement in political processes in the United States is an opaque picture at best.

