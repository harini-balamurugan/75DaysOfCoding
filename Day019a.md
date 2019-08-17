## 

Given a list of distinct numbers, swap the minimum and the maximum and print the resulting list.

```
Example input
3 4 5 2 1

Example output
3 4 1 2 5
```

```
a = [int(s) for s in input().split()]
min,max = a.index(min(a)),a.index(max(a))
a[min],a[max] = a[max],a[min]
print(a)
```
