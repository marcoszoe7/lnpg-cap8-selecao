## Q2 — Sentença de seleção múltipla

### C

```c
switch (k) {
    case 1:
    case 2:  j = 2 * k - 1; break;
    case 3:
    case 5:  j = 3 * k + 1; break;
    case 4:  j = 4 * k - 1; break;
    case 6:
    case 7:
    case 8:  j = k - 2;     break;
}
```

### Ruby

```ruby
case k
when 1, 2    then j = 2 * k - 1
when 3, 5    then j = 3 * k + 1
when 4       then j = 4 * k - 1
when 6, 7, 8 then j = k - 2
end
```

### Erlang

```erlang
J = case K of
    K when K =:= 1; K =:= 2 ->
        2 * K - 1;
    K when K =:= 3; K =:= 5 ->
        3 * K + 1;
    4 ->
        4 * K - 1;
    K when K =:= 6; K =:= 7; K =:= 8 ->
        K - 2
end.
```




















