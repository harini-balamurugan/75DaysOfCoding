## Given a three-digit number. Find the sum of its digits.

```
Example input
123

Example output
6
```

```
a = int(input(" "))
total = 0
while(a>0):
  number = a%10
  total = total + number
  a = a//10
print(" ",total)  
```

