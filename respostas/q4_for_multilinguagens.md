## Q4 — For em 5 linguagens

### Python

```python
n = 100
sum = 0
j = 17
for i in range(n):
    sum += i * j + 3
    j -= 1
```

### C

```c
int i, j, n = 100, sum = 0;
for (i = 0, j = 17; i < n; i++, j--)
    sum += i * j + 3;
```

### JavaScript

```javascript
let sum = 0, n = 100;
for (let i = 0, j = 17; i < n; i++, j--)
    sum += i * j + 3;
```

### Kotlin

```kotlin
var sum = 0
var j = 17
val n = 100
for (i in 0 until n) {
    sum += i * j + 3
    j--
}
```

### Rust

```rust
let mut sum: i32 = 0;
let n: i32 = 100;
let mut j: i32 = 17;
for i in 0..n {
    sum += i * j + 3;
    j -= 1;
}
```
