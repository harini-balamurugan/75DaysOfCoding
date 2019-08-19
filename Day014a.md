## For the given integer N calculate the following sum:
1³ + 2³ + ... + N³


```
Example input
3

Example output
36
```

## source code
```
a = int(input())
li=[]
for i in range(1,a+1):
  b = i**3
  li.append(b)
print(sum(li))
```
