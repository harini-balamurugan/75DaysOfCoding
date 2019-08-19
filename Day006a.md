## Given two timestamps of the same day: a number of hours, minutes and seconds for both of the timestamps. The moment of the first timestamp happened before the moment of the second one. Calculate how many seconds passed between them.

```
Example input #1
1
1
1
2
2
2

Example output #1
3661

```

```
Example input #2
1
2
30
1
3
20

Example output #2
50

```

## source code
```
hour_1 = int(input())
minute_1 = int(input())
second_1 = int(input())
hour_2 = int(input())
minute_2 = int(input())
second_2 = int(input())
T1= (hour_1 * (3600) + minute_1 * (60) + second_1 )
T2= (hour_2 * (3600) + minute_2 * (60) + second_2 )
print(T2 - T1)
```
