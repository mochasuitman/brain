- Like #mvwaddch() but for strings
- ```C
  int mvwprintw(WINDOW *, int y, int x, const char *, ...);
  ```
-
- It is the composition of `move()` function and `wprintw()` function
- ```C
  move(y, x);
  wprintw(window, str);
  ```