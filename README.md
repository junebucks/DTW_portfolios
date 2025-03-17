# DTW_portfolios

 These are additional result of empirical analysis that were not included in the **study.**
 The additional empirical analysis inclueds
 - Changes in rebalancing period
 - Changes in the number of stocks
 
## 1. Rebalaning Period
These results used the same data as the study, but with rebalancing period of quaters and years.
(In the paper, the rebalancing period was 6 months)

### 1.1 Quater

The tables show results using Maximum Diversification Portfolio (MDP), Equally Risk Contribution Portfolio (ERCP), Hirarchical Risky Parity (HRP) from above.

| Metrics | Traditional | TDTW | CDTW (Matern) | CDTW (Exponential) |CDTW (Gaussian)|
|--|--|--|--|--|--|
|Cum ret|1|2|3|4|5|
|Ann ret|1|2|3|4|5|
|Ann vol|1|2|3|4|5|
|Sharpe R|1|2|3|4|5|
|Sortino R|1|2|3|4|5|
|MDD|1|2|3|4|5|
|Calmar R|1|2|3|4|5|


| Metrics | Traditional | TDTW | CDTW (Matern) | CDTW (Exponential) |CDTW (Gaussian)|
|--|--|--|--|--|--|
|Cum ret|1|2|3|4|5|
|Ann ret|1|2|3|4|5|
|Ann vol|1|2|3|4|5|
|Sharpe R|1|2|3|4|5|
|Sortino R|1|2|3|4|5|
|MDD|1|2|3|4|5|
|Calmar R|1|2|3|4|5|

| Metrics | Traditional | TDTW | CDTW (Matern) | CDTW (Exponential) |CDTW (Gaussian)|
|--|--|--|--|--|--|
|Cum ret|1|2|3|4|5|
|Ann ret|1|2|3|4|5|
|Ann vol|1|2|3|4|5|
|Sharpe R|1|2|3|4|5|
|Sortino R|1|2|3|4|5|
|MDD|1|2|3|4|5|
|Calmar R|1|2|3|4|5|



### 1.2 Year






## 2. The Number of Stocks

GICS sector 기준 10개 섹터 내 시가 총액 상위 3개 종목, 총 30개를 수집하였다. (논문에서는 상위 1개 종목)
Data1은 상위 2개 종목, 총 20개를 활용한 결과를, Data2는 상위 3개 종목, 총 30개를 활용한 결과이다. 

### 2.1 Data1
The tables show results using Maximum Diversification Portfolio (MDP), Equally Risk Contribution Portfolio (ERCP), Hirarchical Risky Parity (HRP) from above.

| Metrics | Traditional | TDTW | CDTW (Matern) | CDTW (Exponential) |CDTW (Gaussian)|
|--|--|--|--|--|--|
|Cum ret|0.0259|0.4697|0.3275|0.3911|0.3990|
|Ann ret|0.0031|0.0475|0.0347|0.0405|0.0412|
|Ann vol|0.1770|0.1695|0.1720|0.1720|0.1719|
|Sharpe R|0.0174|0.2799|0.2017|0.2357|0.2399|
|Sortino R|0.0093|0.0318|0.0252|0.0281|0.0284|
|MDD|0.4207|0.4674|0.4741|0.4741|0.4740|
|Calmar R|0.0073|0.1015|0.0732|0.0855|0.0870|

In MDP, summarize the results as follows
- 전통적인 것들보다 DTW를 쓴 것이 우수한 경향
- 설명 변수 별 특징 같은거
- 뭐가 제일 좋은지

| Metrics | Traditional | TDTW | CDTW (Matern) | CDTW (Exponential) |CDTW (Gaussian)|
|--|--|--|--|--|--|
|Cum ret|0.4737|0.6011|0.6104|0.6127|0.6152|
|Ann ret|0.0478|0.0583|0.0590|0.0592|0.0594|
|Ann vol|0.1686|0.1688|0.1689|0.1690|0.1690|
|Sharpe R|0.2835|0.3453|0.3495|0.3505|0.3516|
|Sortino R|0.0321|0.0375|0.0379|0.0379|0.0380|
|MDD|0.4533|0.4611|0.4624|0.4624|0.4624|
|Calmar R|0.1055|0.1265|0.1277|0.1281|0.1285|

In MDP, summarize the results as follows
- 전통적인 것들보다 DTW를 쓴 것이 우수한 경향
- 설명 변수 별 특징 같은거
- 뭐가 제일 좋은지

| Metrics | Traditional | TDTW | CDTW (Matern) | CDTW (Exponential) |CDTW (Gaussian)|
|--|--|--|--|--|--|
|Cum ret|0.5959|0.5827|0.6509|0.6297|0.6355|
|Ann ret|0.0579|0.0568|0.0622|0.0606|0.0610|
|Ann vol|0.1707|0.1689|0.1707|0.1705|0.1707|
|Sharpe R|0.3391|0.3366|0.3646|0.3552|0.3574|
|Sortino R|0.0372|0.0368|0.0393|0.0385|0.0387|
|MDD|0.4479|0.4628|0.4671|0.4671|0.4654|
|Calmar R|0.1293|0.1228|0.1332|0.1297|0.1311|



### 2.2 Data2

The tables show results using MDP, ERCP, HRP from above.

| Metrics | Traditional | TDTW | CDTW (Matern) | CDTW (Exponential) |CDTW (Gaussian)|
|--|--|--|--|--|--|
|Cum ret|0.4030|0.6261|0.4736|0.4660|0.5961|
|Ann ret|0.0416|0.0603|0.0478|0.0471|0.0579|
|Ann vol|0.1810|0.1790|0.1790|0.1787|0.1801|
|Sharpe R|0.2300|0.3369|0.2670|0.2638|0.3215|
|Sortino R|0.0288|0.0381|0.0319|0.0316|0.0367|
|MDD|0.4757|0.5010|0.5108|0.5109|0.5109|
|Calmar R|0.0875|0.1203|0.0936|0.0923|0.1134|


| Metrics | Traditional | TDTW | CDTW (Matern) | CDTW (Exponential) |CDTW (Gaussian)|
|--|--|--|--|--|--|
|Cum ret|0.6703|0.7046|0.7022|0.7001|0.7153|
|Ann ret|0.0637|0.0663|0.0661|0.0660|0.0671|
|Ann vol|0.1789|0.1796|0.1797|0.1796|0.1799|
|Sharpe R|0.3561|0.3693|0.3681|0.3674|0.3731|
|Sortino R|0.0398|0.0410|0.0409|0.0408|0.0414|
|MDD|0.4959|0.4971|0.4985|0.4986|0.4986|
|Calmar R|0.1285|0.1334|0.1327|0.1323|0.1346|

| Metrics | Traditional | TDTW | CDTW (Matern) | CDTW (Exponential) |CDTW (Gaussian)|
|--|--|--|--|--|--|
|Cum ret|0.6868|0.6760|0.7316|0.7270|0.07752|
|Ann ret|0.0650|0.0641|0.0683|0.0680|0.0715|
|Ann vol|0.1795|0.1784|0.1804|0.1802|0.1811|
|Sharpe R|0.3620|0.3595|0.3789|0.3775|0.3951|
|Sortino R|0.0403|0.0400|0.0419|0.0418|0.0434|
|MDD|0.5056|0.4939|0.4965|0.4954|0.4954|
|Calmar R|0.1285|0.1299|0.1376|0.1373|0.1444|


