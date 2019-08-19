##

Given a list of non-zero integers, find and print the first adjacent pair of elements that have the same sign. If there is no such pair, print 0.

```
Example input #1
-1 2 3 -1 -2

Example output #1
2 3
```

```
Example input #2
1 -3 4 -2 1

Example output #2
0
```

## source code
```
x = input()
lst = list(map(int, x.split()))
i = 1

for i in range(1, len(lst)):
  if lst[i] * lst[i-1] > 0:
    print(str(lst[i - 1]), str(lst[i]))
    break
  elif i == len(lst)-1:
    print("0")
```
