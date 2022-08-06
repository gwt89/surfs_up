# surfs_up
## Project Overview

The purpose of this project is to gather temperature data for the months of June and December in Oahu to determine if the surf and ice cream shop business will be sustainable year round. To get the temperature information we needed I ran two separte queries. One for June and the other for December. I then converted the temperatures to a list, stored them in a dataframe, and printed out the summary statistics for each month separately.

## Resources

Data Source: hawaii.sqlite
Software: Jupyter Notebook, PostgreSQL, Python 3.10, Visual Studio Code v1.70.0, Flask

## Results

![June Temps](https://user-images.githubusercontent.com/105949411/183265010-1b35545f-dbd4-424a-8125-d5b1d000f513.png)

![December Temps](https://user-images.githubusercontent.com/105949411/183265013-feacf610-8292-476f-a815-1b36034275f4.png)

1. The mean temperature for June was 74.9° and the mean temperature for December was 71°
2. The max temerparture for June was 85° and the max temperature for December was 83°
3. The standard deviation for June was 3.25° and the standard deviation for December was 3.74°; making an almost .5° between the two months.

### Summary

Overall there is not much difference between the temperatures of June and December so more information should be gathered before a final decision is made. One query that could provided helpful information would be to run a query on precipitation. I would imagine that rainier months will not perform as well overall when compared to sunnier months. Another query that could be run would be to figure out what the temperatures and precipitation will be like for your hours of operation. Since the store will probably not be open 24hrs, knowing what the weather will be like while the store is open is all we really need to know.
