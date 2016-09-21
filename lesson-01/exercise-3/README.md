Create a list of all the natural numbers

```haskell
Prelude> a = [1..]
```

and return a list of the first five values, each repeated a number of times according to its value:

```haskell
Prelude> ???
[1,2,2,3,3,3,4,4,4,4,5,5,5,5,5]
```

> **TIP:** Once again it can be a good idea to use [list comprehension](https://wiki.haskell.org/List_comprehension) (or the `map` function).
>
> **TIP:** Use the `take` function, which returns the first n elements from a given list.
>
> **TIP:** Use the `replicate` function, which takes an integer n and a value x and returns a list of length n in which each value is x.
>
> **TIP:** Use the `concat` function, which takes a list and returns it flattened.
