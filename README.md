### last updated 3/30/2020
+ It is a very simple model to track the progress of Covid in major countries and estimate if the exponential (explosive) spread of the virus is slowing down 
+ I fit the data to an exponential function N=I x exp(Ke*days). And by looking at the data fit of (1) all data; (2) the most recent 5-7 day data; (3) and setdiff([1],[2]) and examining how Ke (the constant in the exponent) changes, we can compare the "explosiveness" of the spread in different regions (the higher Ke, the faster the spread) and estimate if the spread is slowing down (significant drop in Ke)
+ 3/28: I added a "range" of estimate to account for change in the rate of growth based on last 7 days of data. This is kind of ad-hoc, mostly used to highlight the uncertainty in the prediction. A very tight range indicates the trend is a very good exponential fitting and the prediction is likely to be accurate.
+ 3/28: I also added the data for a few large states in the US

###  Observations as of 3/30: same trend continues

###  Observations as of 3/29: 
#### US
+ almost same as 3/28. The number on Sunday 3/29 was slightly below prediction. Not sure it is an deviation due to a Sunday or safe-at-home is having some positive effects. Need to wait a couple of more days to confirm the trend. 


###  Observations as of 3/28: 
#### China
+ Rapid spread happened around Jan-22 - Feb05 (for about 2 weeks) with Ke=0.197. The turning point occured around Feb05 with Ke drop to around 0.075 in the 7 day after. The predicted number for Feb-18 (~77k) slightly overshoot the acutal number (~74k).

#### Italy: 
+ Rapid spread happened around Feb-23 - Mar21 (about 4 weeks) with Ke=0.149. It suggests Italy was 1 month behind China and spread slower. On Mar21, 7-day trailing Ke dropped to around 0.078. On Mar22, 7-day trailing Ke dropped to around 0.074.It sugguests the worst is likely over for Italy. Predicted number is around 150k cases in a week.

#### Spain: 
+ Rapid spread started around  Mar-09 and is ongoing. Ke is about 0.166, about the same as Italy. There is a slight drop to 0.142, indicating the explosive spreading is likely to persist for quite a few more weeks
+ Spain could be worse than Italy in 1 week

#### US:
+ US is unquestionably the worst. Rapid spread started around the same time as in Spain (6 weeks behind China and 2 weeks behind Italy). Ke =0.317 was the highest. The most recent 7 day Ke is 0.199, dropped from 0.219 on yesterday. This mostly due to NY data and is very explosive - comparable to the worst in China and worse than worst time in Italy It suggests there is likely quite a few weeks of rapid growth in US left. And we may see numbers above 400K in a week.

#### US New York:
+ NY has been hitting very hard with the mostly explosive days saw Ke>0.4. The most recent 7-day trailing Ke is now 0.181, still bad but much improved. It is now compatible to (and slightly better than) the rest of US

#### US other states:
+ all other states areall going through perfect exponential spread (with slightly varying explosive), indicating we will see many dark days ahead. Simply put, THIS IS GOING TO BE BAD.
+ California' Ke is about 0.19, which has been very consistent. IT IS GOING TO BE BAD.
+ Texas sees slight higher Ke at about 0.22, worse than california. IT IS GOING TO BE BAD.
+ Massachusetts' Ke has gone up from about 0.2 to about 0.3. IT IS GOING TO BE VERY BAD in MA.