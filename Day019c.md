## Lists: Greater than neighbors

Given a list of numbers, determine and print the number of elements that are greater than both of their neighbors.
The first and the last items of the list shouldn't be considered because they don't have two neighbors.

```
Example input
1 5 1 5 1

Example output
2
```

```
a = [int(s) for s in input().split()]
total = 0
for i in range(1, len(a) - 1):
  if a[i - 1] < a[i] > a[i + 1]:
    total += 1
print(total)
```
