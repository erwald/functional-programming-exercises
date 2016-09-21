Using the result of the previous exercise 

```haskell
Prelude> a = [1,2,2,3,3,3,4,4,4,4,5,5,5,5,5]
```

return the list with all adjacent duplicates removed:

```haskell
Prelude> ???
[1,2,3,4,5]
```

> **TIP:** Once again it can be a good idea to the `foldl` function.
>
> **TIP:** Let the accumulator value be a tuple, and use the `fst` function to get the first element from the final result.
>
> **TIP:** Use the `++` operator to join two lists together.

