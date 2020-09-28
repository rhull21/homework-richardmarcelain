# Marcelain 9/28 Assignment 5

I made my forecast using 2019 data estimates for time periods matchig this year's prediction calendar.  Each weekly estimate lined up close to previous predictions using the same methods, and were the most accurate method I've tried.


#### Assignment Questions

__1.__ Summary of data frame properties:
 - **Column names** are agency_cd, site_no, datetime, flow, code, year, month, day
 - **Index** is 11592 entries, 0 to 11591
 - **Data types** for each column are agency_cd(object), site_no(int64), datetime(object), flow(float64), code(object), year(int32), month(int32), day(int32)

__2.__ Statistics of Daily Flow [cfs]
 - **Min:**     19.00
 - **Mean:**   345.63
 - **Max:**  63400.00
 - **Std:**   1410.83
 - **25%:**     93.70
 - **50%:**    158.00
 - **75%:**    216.00

__3.__ Statistics of Monthly Flow [cfs]
	count	mean	std	min	25%	50%	75%	max
month								
1	992.0	706.32	2749.15	158.0	202.00	219.50	292.00	63400.0
2	904.0	925.25	3348.82	136.0	201.00	244.00	631.00	61000.0
3	992.0	941.73	1645.80	97.0	179.00	387.50	1060.00	30500.0
4	960.0	301.24	548.14	64.9	112.00	142.00	214.50	4690.0
5	992.0	105.44	50.77	46.0	77.97	92.95	118.00	546.0
6	960.0	66.00	28.97	22.1	49.22	60.50	77.00	481.0
7	992.0	95.57	83.51	19.0	53.00	70.90	110.00	1040.0
8	992.0	164.35	274.46	29.6	76.07	114.00	170.25	5360.0
9	956.0	172.69	286.78	36.6	88.07	120.00	171.25	5590.0
10	961.0	146.17	111.78	69.9	107.00	125.00	153.00	1910.0
11	930.0	205.11	235.67	117.0	156.00	175.00	199.00	4600.0
12	961.0	337.10	1097.28	155.0	191.00	204.00	228.00	28700.0

__4.__ Table of 5 highest and lowest flow values:
![](2020-09-28-07-38-01.png)

__5.__ Table of highest and lowest flow years for each month:
![](2020-09-28-07-43-59.png)

__6.__ Table of historical flows that are with 10% of the week 1 forecast of 101.5 dfs: 

agency_cd | site_no  |  datetime  | flow code | year | month | day
607     |   USGS | 9506000 | 1990-08-31 |  94.0   | A | 1990   |   8  | 31
2799       USGS  9506000  1996-08-31  101.0    A  1996      8   31
3529       USGS  9506000  1998-08-31  105.0    A  1998      8   31
6086       USGS  9506000  2005-08-31   97.1    A  2005      8   31
7912       USGS  9506000  2010-08-31   95.4    A  2010      8   31
10469      USGS  9506000  2017-08-31  101.0    A  2017      8   31