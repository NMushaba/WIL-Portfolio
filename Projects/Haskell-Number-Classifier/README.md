# Haskell Number Classifier

## Project overview

This small Haskell example demonstrates classifying an integer as positive, negative, or zero using an `if-then-else` expression.

## My learning activity

During the Cardano Haskell lessons, I completed exercise HC3T1 by defining `checkNumber :: Int -> String` and checking it with positive, negative, and zero inputs.

## Technologies

- Haskell

## Example

```haskell
checkNumber :: Int -> String
checkNumber n =
  if n > 0 then "Positive"
  else if n < 0 then "Negative"
  else "Zero"
