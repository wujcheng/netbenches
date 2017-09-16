```
x enabled-default.pps
+ disabled.pps
+--------------------------------------------------------------------------+
|         +                                                                |
|         +                                                                |
|    x    +   xx                          x     x  +                      +|
|     |________M_________A__________________|                              |
||________M____________________A_____________________________|             |
+--------------------------------------------------------------------------+
    N           Min           Max        Median           Avg        Stddev
x   5       4170038       4322787       4204441     4240500.1     67583.064
+   5       4186001       4415456       4186811       4261884     107132.41
No difference proven at 95.0% confidence
```

FreeBSD 11.1 vs 11.1-yandex

```
x ../fbsd11.1/enabled-default.pps
+ enabled-default.pps
+--------------------------------------------------------------------------+
|                                                                  +       |
|x x x xx                                                        + +     ++|
| |__A__|                                                                  |
|                                                                |_M_A___| |
+--------------------------------------------------------------------------+
    N           Min           Max        Median           Avg        Stddev
x   5       3091435     3202055.5       3158043     3155398.5      46057.01
+   5       4170038       4322787       4204441     4240500.1     67583.064
Difference at 95.0% confidence
	1.0851e+06 +/- 84342.4
	34.3887% +/- 2.99517%
	(Student's t, pooled s = 57830.4)
```