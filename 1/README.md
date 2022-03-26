## Question

- Given two arrays, `A` and `B` and both have length `n`.
- One operation consists of following done in order:
  - Select `i`, `(0 < i < n)`
  - `swap(A[i], A[i+1])`
  - `A[i] = A[i] + 1`
  - `A[i+1] = A[i+1] - 1`
- Find the minimum number of operation needed to make `A` equal to `B`
- If it is not possible to convert then return `-1`

## Constraints

- `2 <= N <= 2*10^5`
- `0 <= A[i], B[i] <= 10^9`
- All input are integers

## Input

- first line `n`
- second line `A` array elements
- third line `B` array elements

## Sample Case

### 1

```
5
4 5 6 7 8
4 5 6 7 8
```

Output

```
0
```

### 2

```
3
2 2 1
2 2 3
```

Output:

```
-1
```
