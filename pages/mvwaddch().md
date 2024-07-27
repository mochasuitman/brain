- Writes a char into specific position and in specific window (like `mvaddch()` but with custom window)
- ```C
  int mvwaddch(WINDOW *, int y, int x, ch);
  ```
-
- It is the composition of function `move()` and function `waddch()`
- ```C
  move(y, x);
  waddch(window, ch);
  ```