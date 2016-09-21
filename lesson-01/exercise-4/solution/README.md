#### Solutions

```haskell
Prelude> fst (foldl (\(res, lst) x -> if x == lst then (res, x) else (res ++ [x], x)) ([], 0) a)
[1,2,3,4,5]

Prelude> fst . foldl (\(res, lst) x -> if x == lst then (res, x) else (res ++ [x], x)) ([], 0) $ a -- With function composition.
[1,2,3,4,5]
```

