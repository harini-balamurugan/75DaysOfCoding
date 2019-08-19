## Dicts: Synonyms

You are given a dictionary consisting of word pairs. Every word is a synonym of the other word in its pair. All the words in the dictionary are different.

After the dictionary there's one more word given. Find a synonym for it.

```
Example input
3
Hello Hi
Bye Goodbye
List Array
Goodbye

Example output
Bye
```

## source code
```
n = int(input())
a = {}
for i in range(n):
  one,two = input().split()
  a[one] = two
  a[two] = one
print(a[input()])

```
