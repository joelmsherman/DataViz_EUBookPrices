# Makeover Monday (MoM) - Week 38
**Book Price Inflation/Deflation in EU Countries**

## MoM Background
Makeover Monday is a weekly learning and development opportunity to work with a given data set and create better, more effective visualizations.  The goal with MoM is to make information more accessible, and participants are from around the world.  MoM is sponsored by Tableau.  Each week, sponsors post a visualization to be improved, along with a dataset for the original visualization.  Participants then make and share their vizs and the community gets smarter and more creative as a whole!

## Source Article and Viz
This week's Viz: Week 38 brings [a viz](https://data.world/makeovermonday/2020w38/workspace/project-summary?agentid=makeovermonday&datasetid=2020w38) showing the average (across member countries) HICP (i.e. CPI) for books relative to all goods/services over time.

## Data Source
Data comes from Eurostat [here](https://appsso.eurostat.ec.europa.eu/nui/show.do?query=BOOKMARK_DS-055106_QID_2BA8FB1D_UID_-3F171EB0&layout=TIME,C,X,0;COICOP,B,Y,0;UNIT,B,Z,0;GEO,B,Z,1;INDICATORS,C,Z,2;&zSelection=DS-055106INDICATORS,OBS_FLAG;DS-055106GEO,EU27_2020;DS-055106UNIT,I15;&rankName1=UNIT_1_2_-1_2&rankName2=INDICATORS_1_2_-1_2&rankName3=GEO_1_2_1_1&rankName4=TIME_1_0_0_0&rankName5=COICOP_1_2_0_1&sortC=ASC_-1_FIRST&rStp=&cStp=&rDCh=&cDCh=&rDM=true&cDM=true&footnes=false&empty=false&wai=false&time_mode=NONE&time_most_recent=false&lang=EN&cfo=%23%23%23%2C%23%23%23.%23%23%23).

## My Approach for Week 38
The original viz is a simple line chart that aggregates the CPIs for books and all goods across countries.  I choose to look only at the CPI for books, by country, to see where inflation or deflation in book prices is occurring.  I also implemented different "long-run" approach to determining price change measure, looking at slope of log-transformed, long-run HICP for each country.
