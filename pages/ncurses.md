type:: [[library]]
name:: ncurses
programming-language:: #C #C++ 
topics:: #CLI #UI
docs:: [link](https://tldp.org/HOWTO/NCURSES-Programming-HOWTO/)

-
- ## Installation
	- ### Fedora
		- ```Terminal
		  sudo dnf install ncurses-devel
		  ```
	-
- ## Configuration and basic usage
	- Include `ncurses.h` in your project
	- ```C
	  #include <ncurses.h>
	  ```
	-
	- Compile your project
	- ```Terminal
	  gcc -g -o example example.c -lncurses
	  ```
	-
- ## Hello World
	- ```C
	  #include <ncurses.h>
	  
	  int main() {
	    initscr();
	    printw("Hello World!");
	    refresh();
	    getch();
	    endwin();
	    return 0;
	  }
	  ```
	-
- ## Common Patterns
	- `w`, `mv`, `mvw` function naming convention actually represents what the function does. It is consistent throughout the entire codebase
		- `w` ==> Function take a `WINDOW *` as input (default window is `stdscr`)
		- `mv` ==> Function moves to a specific (x, y) position
		- `mvw` ==> Combination of `w` and `mv`, move to (x, y) position of a chosen window
	-
- ## Features
	- ### Initialization functions
		- {{embed [[initscr()]]}}
		- {{embed [[refresh()]]}}
		- {{embed [[raw()]]}}
		- {{embed [[noecho()]]}}
		- {{embed [[echo()]]}}
		- {{embed [[keypad()]]}}
		- {{embed [[endwin()]]}}
		-
	- ### Output functions
		- {{embed [[addch()]]}}
		- {{embed [[printw()]]}}
		- {{embed [[mvaddch()]]}}
		- {{embed [[mvprintw()]]}}
		- {{embed [[waddch()]]}}
		- {{embed [[wprintw()]]}}
		- {{embed [[mvwaddch()]]}}
		- {{embed [[mvwprintw()]]}}
		-
	- ### Input functions
	-
-