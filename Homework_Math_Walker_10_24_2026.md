# Homework: Boolean Logic

Use these symbols:

- `+` means **OR**.
- Multiplication means **AND**: `xy` means x AND y.
- `'` means **NOT**: `y'` means NOT y.
- `0` means **false**, and `1` means **true**.

## Exercise 1: AND and OR

Complete the truth table.

| x | y | xy | x + y |
|---|---|----|-------|
| 0 | 0 | 0  |   0   |
| 0 | 1 | 0  |   1   |
| 1 | 0 | 0  |   1   |
| 1 | 1 | 1  |   1   |

## Exercise 2: AND with NOT

Complete the truth table.

| x | y | y' | xy' |
|---|---|----|-----|
| 0 | 0 | 1  |  0  |
| 0 | 1 | 0  |  0  |
| 1 | 0 | 1  |  1  |
| 1 | 1 | 0  |  0  |

Answer these questions:

1. Which values of x and y make `xy' = 1`?
- y = 0 and x = 1, that way y' = 1. 1*1=1
2. Explain the difference between `xy` and `xy'` in one sentence.
- `xy` means taking raw number we are given, while `xy'` takes x and multiplies it by y bar.

## Exercise 3: Find the Boolean Rules

Complete the table.

| x | x + 1 | x · 1 | x + 0 | x · 0 |
|---|-------|-------|-------|-------|
| 0 |   1   |   0   |   0   |   0   |
| 1 |   1   |   1   |   1   |   0   |

Use your results to complete these rules:

1. `x + 1 = __1__`
- No matter what is the value of x, in an OR statement, at least one option should be 1.
2. `x · 1 = __x__`
- The result depends on x. If x is 0, the whole equation cancels out, it becomes 0. If x is 1, since both values are 1, the result is also equal to 1.
3. `x + 0 = __x__`
- Yet again, the result depends on x. for OR to be true, there must be 1 at least once.
4. `x · 0 = __0__`
- This is always 0, since we multiply by 0. for AND to be true, both must be true.

For each rule, explain why it works using the meaning of AND or OR.