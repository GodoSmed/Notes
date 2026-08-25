# C Input/Output Library

STATUS: C

<!-- cSpell:disable -->

```C
#include <stdio.h>
```

| Function     | Description                                                                                |
| :----------- | :----------------------------------------------------------------------------------------- |
| `fclose()`   | Closes a file                                                                              |
| `feof()`     | Returns a true value when the position indicator has reached the end of the file           |
| `ferror()`   | Returns a true value if a recent file operation had an error                               |
| `fgetc()`    | Returns the ASCII value of a character in a file and advances the position indicator       |
| `fgets()`    | Reads a line from a file and advances the position indicator                               |
| `fopen()`    | Opens a file and returns a file pointer for use in file handling functions                 |
| `fprintf()`  | Writes a formatted string into a file                                                      |
| `fputc()`    | Writes a character into a file and advances the position indicator                         |
| `fputs()`    | Writes a string into a file and advances the position indicator                            |
| `fread()`    | Reads data from a file and writes it into a block of memory                                |
| `fscanf()`   | Reads formatted data from a file and writes it into a number of memory locations           |
| `fseek()`    | Moves the position indicator of a file pointer                                             |
| `ftell()`    | Returns the value of the position indicator of a file pointer                              |
| `fwrite()`   | Writes data from a block of memory into a file                                             |
| `getc()`     | The same as `fgetc()`                                                                      |
| `getchar()`  | Reads one character of user input and returns its ASCII value                              |
| `printf()`   | Writes a formatted string to the console                                                   |
| `putc()`     | The same as `fputc()`                                                                      |
| `putchar()`  | Outputs a single character to the console                                                  |
| `puts()`     | Outputs a string to the console                                                            |
| `remove()`   | Deletes a file                                                                             |
| `rename()`   | Changes the name of a file                                                                 |
| `rewind()`   | Moves the position indicator to the beginning of the file                                  |
| `scanf()`    | Reads formatted data from user input and writes it into a number of memory locations       |
| `snprintf()` | Writes a formatted string into a char array (memory-safe)                                  |
| `sprintf()`  | Writes a formatted string into a char array                                                |
| `sscanf()`   | Reads a formatted string from a char array and writes it into a number of memory locations |
