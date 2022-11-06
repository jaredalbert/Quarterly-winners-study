# Quarterly-winners-study
This is a copy of the study that I originally did for Vic Neiderhoffer in a jupyter note through DataCamp

This study examines several questions around the quarterly performance of quantiles of components of the Russell 3000 over the last 5 years.

The first question: is there a difference in the performance over the following 4 quarters between the quantile performance rankings over the previous quarter. That is, do the returns of the last quarter give an indication of how the stock will do over the next 4 quarters?

To answer this, the study resamples all data by end of quarter, then ranks the natural log performance of each stock into deciles. It then looks at how each decile does over the next four quarters.

The data for this study is the daily closing prices of all 3514 components that were in the Russell 3000 during the last 5 years. Those that were removed/added from/to the index are included. Bankrupt/delisted companies are also included, and the price is adjusted for all corporate actions. This is a complete point in time data set.
