# Documenatation of Power Bi DAX Measures

## Description
- Confirmed accumulated := all Confirmed COVID-19 cases till specific Date
- Confirmed accumulated PrevDay := self-explanatory
- Confirmed := Confirmed in given time intervall
- Confirmed movAvg := Moving Average of Confirmed of last 5 Days
- Confirmed Rate := Confirmed / Confirmed accumulated PrevDay
- Confirmed Rate movAvg := Moving Average of last 5 Days' *Confirmed Rate* 
- Confirmed Doubling Time
    - Total Confirmed will doubled in x days, assuming that *Confirmed Rate movAvg* will be stable
- Deaths Measure are analog defined

## Formulas

```dax
Doubling Time = 
    log(2) / log(1 + [Confirmed Rate movAvg])
```

```dax
Confirmed movAvg = 
    VAR __LAST_DATE = LASTDATE(cases_time[Last_Update])
    VAR __BEGIN_DATE = DATEADD(__LAST_DATE, -4, DAY)
	RETURN 
		AVERAGEX(
			DATESBETWEEN(
				cases_time[Last_Update],
				__BEGIN_DATE,
				__LAST_DATE
			),
			CALCULATE([Confirmed_m])
		)
```




