- Like #mvaddch() but for strings
- ```C
  int mvprintw(int y, int x, const char *, ...);
  ```
-
- It is the composition of `move()` function and `printw()` funtion
- ```C
  move(y, x);
  printw(str);
  ```