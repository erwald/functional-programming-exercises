#### Solutions

```haskell
Prelude> [ x * 2 | x <- a, even x ]
[4,8,12,16,20,24,28,32,36,40]

Prelude> map (\x -> x * 2) (filter even a)
[4,8,12,16,20,24,28,32,36,40]

Prelude> map (* 2) (filter even a) -- (* 2) here being simply a function.
[4,8,12,16,20,24,28,32,36,40]

Prelude> map (* 2) . filter even $ a -- With function composition.
[4,8,12,16,20,24,28,32,36,40]
```
 
