# COVID-19-in-US
COVID-19 in Virginia and the US

I got interested first in tracking cases in my own state of Virginia, based on the data the Virginia Department of Health 
publishes daily. 

Some notes about testing numbers in Virginia:

Tests are are offset from everything else, in terms of time. For a while the Virginia Department of Health (VDH) was publishing both swab tests (for infecion) and antibody tests as one number of total tests. Apparently Governor Northam found out about it and told them to disaggregate those numbers. Which is good. Now, VDH has a graph of daily testing encounters by lab report date. I take that as the day the test was administered, whereas report date is the day the test result came back. But test results on one day can be from tests administered on several different days. So when a new test result comes back, it gets added to the results total for that day, but added to the new tests total for day it was administered. So when I update, I have to go back through VDH's whole graph to see ALL the dates that have been modified, not just the recent day.

There is aso a note on the VDH web site that testing labs don't report all negative tests. This affects the denominator of total tests and may account for some of the high degree of correlation between tests and cases. 

A note on May 6 and 7 reporting:
VDH typically updates its web site by 10 a.m. ET based on what was verified by 5 p.m. ET the day before. The web site had a glitch on the night of May 5, so the web site was not updated on May 6. Combined numbers were publshed on May 7. There are a few different ways to handle that when dealing with daily numbers. Worldometer and Johns Hopkins, because they publish more than just Virginia numbers, left Virginia updates as 0 for all categories and locations for May 6. The Virginia Public Access Project eliminated May 6 from their graph altogether. I decided to take what was new from Maya 5 to May 7 and split the difference between May 6 and May 7. 

New York State is about a third of COVID-19 cases total, so I was interested in what the total US case count looked like 
without New York cases. That uses the Johns Hopkins data that populates their map.
