## Q3 — Sem goto/break

### Java

```java
int j = -3;
boolean parar = false;
for (int i = 0; i < 3 && !parar; i++) {
    int val = j + 2;
    if (val == 3 || val == 2) {
        j--;
    } else if (val == 0) {
        j += 2;
    } else {
        j = 0;
    }
    if (j > 0) {
        parar = true;
    } else {
        j = 3 - i;
    }
}
```

### Python

```python
j = -3
parar = False
i = 0
while i < 3 and not parar:
    val = j + 2
    if val == 3 or val == 2:
        j -= 1
    elif val == 0:
        j += 2
    else:
        j = 0
    if j > 0:
        parar = True
    else:
        j = 3 - i
    i += 1
```

### Swift

```swift
var j = -3
var parar = false
var i = 0
while i < 3 && !parar {
    let val = j + 2
    if val == 3 || val == 2 {
        j -= 1
    } else if val == 0 {
        j += 2
    } else {
        j = 0
    }
    if j > 0 {
        parar = true
    } else {
        j = 3 - i
    }
    i += 1
}
```

