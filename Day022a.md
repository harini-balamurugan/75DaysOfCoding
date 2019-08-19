## Dicts: Countries and cities

Given a list of countries and cities of each country, then given the names of the cities. For each city print the country in which it is located.

```
Example input
2
USA Boston Pittsburgh Washington Seattle
UK London Edinburgh Cardiff Belfast
3
Cardiff
Seattle
London

Example output
UK
USA
UK
```

## source code
```
cc = {}
for i in range(int(input())):
  country, *cities = input().split()
  for city in cities:
    cc[city] = country
for i in range(int(input())):
  print(cc[input()])
```        
        
