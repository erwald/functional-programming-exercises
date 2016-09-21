#### Solutions

```haskell
Prelude> concat [ replicate x x | x <- take 5 a ]
[1,2,2,3,3,3,4,4,4,4,5,5,5,5,5]

Prelude> concat (map (\x -> replicate x x) (take 5 a))
[1,2,2,3,3,3,4,4,4,4,5,5,5,5,5]

Prelude> concat . map (\x -> replicate x x) . take 5 $ a -- With function composition.
[1,2,2,3,3,3,4,4,4,4,5,5,5,5,5]
```

