- This function writes a char in a specific position
- ```C
  int mvaddch(int y, int x, char ch);
  ```
-
- It is the composition of function `move()` and function `addch()`
  id:: 66a4b2f5-edbe-489b-a90f-692aeb03f31c
- ```C
  move(y, x);
  addch(ch);
  ```