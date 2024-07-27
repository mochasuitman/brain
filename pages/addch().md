- Write a single char at the current cursor position into default `stdscr` window
  id:: 66a4b179-7444-4cd5-a2eb-0b511fce2c0a
- ```C
  addch(char);
  ```
-
- In order to add attributes to the char you can either use #attrset() #attron() #attroff() functions, or do like this:
- ```C
  addch(ch | A_BOLD | A_UNDERLINE)
  ```