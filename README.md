# Covid_19_tracking
#
### last updated 3/27/2020
### It is a very simple model to track the progress of Covid in major countries and estimate if the exponential (explosive) spread of the virus is slowing down 
+ I fit the data to an exponential function N=I x exp(Ke*days). And by looking at the data fit of (1) all data; (2) the most recent 5-7 day data; (3) and setdiff([1],[2]) and examining how Ke - the constant in the exponent - changes, we can compare the "explosiveness" of the spread (the higher Ke, the faster the spread) and weather the spread is slowing down (significant drop in Ke)

###  China: 
+ Rapid spread happened around Jan-22 - Feb05 (for about 2 weeks) with Ke=0.197. The turning point occured around  with Ke drop to around 0.075 in the 7 day after. The predicted number for Feb-18 (~77k) slightly overshoot the acutal number (~74k).

### Italy: 
+ Rapid spread happened around Feb-23 - Mar21 (about 4 weeks) with Ke=0.149. It suggests Italy was 1 month behind China and spread slower. On Mar21, with Ke drop to around 0.078. It sugguested the worst is likely over. Predicted number is around 150k cases

### Spain: 
+ Rapid spread started around  Mar-09 and is ongoing. Ke is about 0.274, worse than Italy. The prediction is it is going to last quite a few more weeks

### US:
+ US is unquestionably the worst. Rapid spread started around the same time as in Spain (6 weeks behind China and 2 weeks behind Italy). Ke =0.317 was the highest. The most recent 7 day Ke is 0.219, still very explosive. It suggests there is likely quite a few weeks of rapid growth in US left. And we may see numbers above 400K in a week.

  
