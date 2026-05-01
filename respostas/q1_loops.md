# Q1 — Reescrita com laço

## Java

```java
int k = (j + 13) / 27;
int i = 0;
while (k <= 10) {
    k = k + 1;
    i = 3 * k - 1;
}
```

## Python

```python
k = (j + 13) // 27
while k <= 10:
    k = k + 1
    i = 3 * k - 1
```

## Haskell

```haskell
let k0 = (j + 13) `div` 27
    loop k
      | k > 10    = (k, 3 * k - 1)
      | otherwise = loop (k + 1)
    (kFinal, i) = loop k0
```

## Swift

```swift
var k = (j + 13) / 27
var i = 0
while k <= 10 {
    k += 1
    i = 3 * k - 1
}
```






