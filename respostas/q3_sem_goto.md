
Solução — sem goto nem break

#Java

````j = -3;
int parar = 0;

for (i = 0; i < 3 && !parar; i++) {
    int val = j + 2;

    if (val == 3 || val == 2) {
        j--;
    } else if (val == 0) {
        j += 2;
    } else {
        j = 0;
    }

    if (j > 0) {
        parar = 1;   /* substitui o break do for */
    } else {
        j = 3 - i;
    }
}
````


