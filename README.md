# COVID-19-in-US
COVID-19 in Virginia and the US

Virginia: 

I got interested first in tracking cases in my own state of Virginia, based on the data the Virginia Department of Health (VDH) publishes daily. 

Definitions:

New reports: new cases (for Virginia, Fairfax County, Virginia minus Fairfax County) reported by the Virginia Department of Health. These cases represent an update from what the VDH website posted the previous day. The number included positive test and probable cases, which still have to meet diagnostic criteria including pneumonia-like conditions and known exposure to COVID-19. Tests may have been administered several days earlier. Northern Virginia (NoVa) case totals come from the Northern Virginia Regional Dashboard Coronavirus testing website.

New hospitalizations: new hospitalizations reported by the Virginia Department of Health. These hospitalizations represent an update from what the VDH website posted the previous day.

New deaths: new deaths reported by the Virginia Department of Health. These deaths represent an update from what the VDH website posted the previous day.

New tests: new tests reported by the Virginia Department of Health by lab report date. 

New positive results: new positive test results reported by the Virginia Department of Health by lab report date.

Some notes about testing numbers in Virginia:

Tests are are offset from everything else, in terms of time. For a while the Virginia Department of Health (VDH) was publishing both swab tests (for infecion) and antibody tests as an aggregate of total tests. Governor Northam found out about it and told them to disaggregate those numbers. Now, VDH has a graph of daily testing encounters by lab report date. Presumably this is the day the test was administered, whereas VDH report date is the day after the test result came back to VDH. (VDH verifies all numbers by 5 p.m. ET and publishes those numbers the following day.) But test results reported to the VDH on one day can be from tests administered on several different days. So when a new test result is reported to the VDH, it gets added to the results total for that day, but added to the new tests total/positive cases graph for day it was administered. Updating requires going back through ALL the dates to see which have been modified, not just the most recent day. Some numbers are revised down, on both the testing and positive results graphs. No explanation is provided on the VDH site for numbers that are revised down (and probably not something anyone would recognize if they weren't looking at individual dates every day). The VDH could be shifting numbers from one day to another if a date was incorrect, eliminating false positives after a confirmation test, or continuosly eliminating anti-body tests from what should be only a tally of infection tests. 

The testing graphs on the VDH site only go back to March 16, 2020, and does not reflect testing done earlier in March. The cumulative total from the graph therefore does not match the top line total of tests at the top of the page. 

There is aso a note on the VDH web site that testing labs don't report all negative tests. This affects the denominator of total tests and may account for some of the high degree of correlation between tests and cases. Late-reported negative tests may also account for testing numbers being revised up.

A note on May 6 and 7 reporting:

VDH typically updates its web site by 10 a.m. ET based on what was verified by 5 p.m. ET the day before. The web site had a glitch on the night of May 5, so the web site was not updated on May 6. Combined numbers were publshed on May 7. There are a few different ways to handle that when dealing with daily numbers. Worldometer and Johns Hopkins, because they publish more than just Virginia numbers, left Virginia updates as 0 for all categories and locations for May 6. The Virginia Public Access Project eliminated May 6 from their graph altogether. I decided to take what was new from May 5 to May 7 and split the difference between May 6 and May 7. 

New York: 

New York State, during its peak, was about a third of US COVID-19 cases total, so I was interested in what the total US case count looked like without New York cases. Later I added a graph that excluded both New York and New Jersey cases, since both peaked highly around the same time. Those graphs and calculations use the Johns Hopkins data that populates their map. Raw data can be found here: https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports
