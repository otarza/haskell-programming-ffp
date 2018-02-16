# Exercises: Comprehension Check

1. Given the following lines of code as they might appear in a source file, how would you change them to use them directly in the REPL?

```haskell
half x = x / 2

square x = x * x
```
Solution:

```haskell
let half x = x / 2

let square x = x * x
```
2. Write one function that can accept one argument and work for all the following expressions. Be sure to name the function.
```haskell
3.14 * (5 * 5)
3.14 * (10 * 10)
3.14 * (2 * 2)
3.14 * (4 * 4)
```
Solution:

```haskell
psquare x = 3.14 * (x * x)
```

# Exercises: Parentheses and Association
1. a) 8 + 7 * 9
   b) (8 + 7) * 9
   Answer: Parentheses matter.

2. a) perimeter x y = (x * 2) + (y * 2)
   b) perimeter x y = x * 2 + y * 2
   Answer: Parentheses do not matter.

3. a) f x = x / 2 + 9
   b) f x = x / (2 + 9)
   Answer: Parentheses matter.
