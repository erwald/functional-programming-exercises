Create a list of numbers from 1 to 20 

```haskell
Prelude> a = [1..20]
```

and return the length of the list *without using the `length` function*: 

```haskell
Prelude> ???
20
```

> **TIP:** Use the `foldl` function, which takes a function, a starting value and a list and, for each element of the list, calls the function with two arguments – an accumulator (initially the starting value) and the current element – and, once the whole list has been processed, returns the accumulator.
