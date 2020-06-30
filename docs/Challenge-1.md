# Challenge 1 - if/else

## The Challenge

Take a number and then print a string depending on value.

[View on HackerRank](https://www.hackerrank.com/challenges/py-if-else/problem?h_r=next-challenge&h_v=zen)

## My Solution

```python
if __name__ == '__main__':
    n = int(input().strip())

    if n%2 != 0:
        print("Weird")

    else:
        if n >= 2 & n <= 5:
            print("Not Weird")
        elif n >= 6 & n <= 20:
            print("Weird")
        elif n > 20:
            print("Not Weird")
```