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
1. 
   - a) ```haskell 8 + 7 * 9```
   - b) ```haskell (8 + 7) * 9```

   Answer: Parentheses matter.

   2. 
   - a) ```haskell perimeter x y = (x * 2) + (y * 2) ```
   - b) ```haskell perimeter x y = x * 2 + y * 2 ```

   Answer: Parentheses do not matter.

   3. 
   - a) ```haskell  f x = x / 2 + 9 ```
   - b) ```haskell f x = x / (2 + 9) ```

   Answer: Parentheses matter.

   # Exercises: Heal the Sick

   1. ```haskell let area x = 3. 14 * (x * x)``` - Problem: extra space after 3.```
   2. ```haskell let double x = b * 2 ``` - Problem: b is not declared.```
   3. ```haskell x = 7
                  y = 10
                f = x + y
     ``` Problem: Incorrect indentation.

  # Exercises: A Head Code
  
  1. ```haskell let x = 5 in x``` result: 5
  2. ```haskell let x = 5 in x * x``` result 25
  3. ```haskell let x = 5; y = 6 in x * y``` result 30
  4. ```haskell let x = 3; y = 1000 in x + 3``` result 6
