# Challenge 1 - if/else

## The Challenge

Take a number and then print a string depending on value.

[View on HackerRank](https://www.hackerrank.com/challenges/py-if-else/problem?h_r=next-challenge&h_v=zen)

## As Flow chart

```flow
s=>start
e=>end
f=>what anderes
cond=>condition: Odd or Even?

s->cond
cond(odd)->e
cond(even)->f
```

## My Solution

```python
if __name__ == '__main__':
    n = int(input().strip())

    if n%2 != 0:                # is odd
        print("Weird")
    else:                       # is even
        if n >= 2 & n <= 5:         # range 1
            print("Not Weird")
        elif n >= 6 & n <= 20:      # range 2
            print("Weird")
        elif n > 20:                # range 3
            print("Not Weird")
```