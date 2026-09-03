# C Console Output
STATE: C

[Library: <stdio.h>](./c-stdio.h.md)

**Main Function**:
```C
printf();
```


<details><summary><b> Variable Output </b></summary>


```C
//'x' satisfies the data type
printf("%d", x); // Integer
printf("%i", x); // Integer
printf("%u", x); // Unsigned Integer
printf("%hd", x); // Short Integer
printf("%ld", x); // Long Integer
printf("%lld", x); // Long Long Integer
printf("%zu", sizeof(x)); // Size_t Integer

printf("%o", x); // Octal Integer
printf("%x", x); // Hexadecimal Integer (lowercase)
printf("%X", x); // Hexadecimal Integer (uppercase)
printf("%#x", x); // Hexadecimal Integer (with prefix)

printf("%5d", x); // Padded Integer (spaces)
printf("%05d", x); // Padded Integer (zeros)
printf("%-5d", x); // Left-aligned Integer
printf("%*d", 5, x); // Dynamic Width Integer

printf("%+d", x); // Signed Integer (always show sign)
printf("% d", x); // Space-prefixed Positive Integer

printf("%c", c); // Single Character
printf("%s", str); // String
printf("%lc", wc); // Wide Character
printf("%ls", wstr); // Wide String

printf("%10s", str); // Padded String (right-aligned)
printf("%-10s", str); // Padded String (left-aligned)
printf("%.5s", str); // Truncated String (max length)

printf("%f", f); // Float / Double Decimal
printf("%F", f); // Float / Double Decimal (uppercase INF/NAN)
printf("%e", f); // Exponential Notation (lowercase)
printf("%E", f); // Exponential Notation (uppercase)
printf("%g", f); // Compact Representation (lowercase)
printf("%G", f); // Compact Representation (uppercase)
printf("%a", f); // Hexadecimal Floating Point (lowercase)
printf("%A", f); // Hexadecimal Floating Point (uppercase)
printf("%.2f", f); // Precision Floating Point

printf("%Lf", lf); // Long Double Decimal
printf("%Le", lf); // Long Double Exponential
printf("%Lg", lf); // Long Double Compact

printf("%p", ptr); // Pointer Address
printf("%n", &n); // Written Character Count
```
</details><br>

**Multiple Variable Output**
```C
//'x', 'y', 'z' satisfies the data type
printf("first: %d, Second: %f Third: %s", x, y, z);
```