type:: [[programming language]]
name:: C++

-
## [[resources]]
	- [learncpp.com](https://www.learncpp.com/)
	-
## [[libraries]]
	-
- ## [[theory]]
	- ### How a C++ program runs
	  collapsed:: true
		- The source code gets involved in 3 main operations before becoming ready for execution
		- #### Translation phase
			- In this phase the code gets ready to be compiled
			- A code file that is gone through the translation process is called translation unit
			-
		- #### Compilation of *.cpp* files
			- The [[compiler]] program compiles each *.cpp* file into *.o* files
			- ![cpp-compilation.png](../assets/cpp-compilation_1683319562030_0.png){:height 194, :width 445}
			-
		- #### Linking of *.o* files
			- A program called [[linker]] links all the *.o* files and all the libraries together and creates an executable file *.exe*
			- ![cpp-linking.png](../assets/cpp-linking_1683319581098_0.png)
		-
	- ### [[variables]]
	  collapsed:: true
		- #### [[declaration]]
		  collapsed:: true
			- ```C++
			  int x;  // define a variable named x, of type int
			  ```
			-
		- #### [[assignment]]
		  collapsed:: true
			- ```C++
			  int x;  // declaration of an integer value called "x"
			  x = 10;  // assignment of value (10) into variable x
			  // The variable x now has value (10)
			  ```
			-
		- #### [[initialization]]
		  collapsed:: true
			- #### Default Initialization #[[bad practice]]
				- ```C++
				  int x;
				  ```
				-
			- #### Copy Initialization #[[bad practice]]
				- It is more of a [[C]] way of initializing variables
				- ```C++
				  int x = 1;
				  ```
				-
			- #### Direct Initialization #[[bad practice]]
				- ```C++
				  int x(1);
				  ```
				-
			- #### Zero Initialization #[[good practice]]
				- It is useful when you plan to immediately replace the value of the variable
				- In other words, you don't care which value is assigned to the variable because it will be assigned after the variable initialization
				- ```C++
				  int x {};
				  std::cin >> x;  // The value is immediately replaced by the value inserted using "cin"
				  ```
				-
			- #### Value Initialization #[[good practice]]
				- It is useful when you need a default value for the variable
				- ```C++
				  int x { 1 };
				  ```
				-
			- #### Unused Variable #[[good practice]]
				- It is useful when we are dealing with a *maybe unused* variable
				- If the variable might be unused, and we didn't wrote the maybe_unused keyword, the compiler may throw an error
				- ```C++
				  [[maybe_unused]] int x {};  // Or x{ 1 } for example, it doesn't matter
				  ```
				-
	- ### New line character
	  collapsed:: true
		- #### '\\n' escape character #[[good practice]]
			- It is preferable due to performance reasons
			- It is preferable due to readability reasons
			- ```C++
			  std::cout << '\n';
			  ```
			-
		- #### endl #[[bad practice]]
			- ```C++
			  std::cout << endl;
			  ```
			-
	- ### [[operators]]
	  collapsed:: true
		- Every operator returns a value, it may be not used explicitly by the user though
		- #### Operators that explicitly return a value
			- ```C++
			  +; -; *; /;  // etc...
			  ```
			-
		- #### Operators that implicitly return a value
			- Those operators usually return their left operand
			- This happens to facilitate operators chaining
			- ```C++
			  <<; >>; =;  // etc...
			  std::cout << 5;  // The value returned by "<<" is "std::cout" 
			  ```
			-
		- #### Chaining operators one another
			- Operators can be chained
			- ```C++
			  int x = (3 + 1);  // (3 + 1) = 4 --> x = 4 --> Value of x is 4
			  int x = y = 5;  // y = 5 --> x = y --> Value of x is 5
			  std::cout << (x = 2);  // x = 2 --> cout << x --> Value printed is 2
			  std::cout << "Hello" << "World";  // (std::cout << "Hello") << "World" 
			  								  // "Hello" is printed and std::cout is returned.
			  								  // Than the returned std::cout is used to 
			  								  // print "World"
			  ```
			-
	- ### [[undefined behaviour]] (UB)
	  collapsed:: true
		- ```C++
		  int x;  // Default Initialization
		  std::cout << x;
		  ```
		-
		- This code will produce an undefined behaviour
		- The variable *x* will apparently store a random value, but it is not random.
		- The value of x is the value allocated at the memory space that is now pointed by the [[pointer]] "int *pX;"
		- Before the program started, that memory space was used by other programs or by the OS
		- It means that default initialization does not allocate any value inside the memory space, it only reserve a space in memory for later use
		-
	- ### [[functions]]
	  collapsed:: true
		- #### [[declaration]]
		  collapsed:: true
			- ```C++
			  int main() {
			    	std::cout << "Hello World!\n";
			    	return 0;
			  }
			  ```
			-
		- #### Functions that return a value
		  collapsed:: true
			- To define a value returning function you should first declare the [[data type]] of the returning value inside the function declaration
			- ```C++
			  int main() { return 0; }  // "int" is the data type of the returning value
			  ```
			-
			- Make sure to always write a return statement if the function should return a value, otherwise it will cause an [[undefined behaviour]] #[[good practice]]
			- *main* function will always *return 0* if return statement is not provided. That being said, you should always write a return statement in the *main* function #[[good practice]]
			-
		- #### Functions that do not return any value
		  collapsed:: true
			- To define a non-value returning function you should write [[void]] as the data type of the function's returning value
			- ```C++
			  void sayHi() { std::cout << "Hi!\n"; }  // No return value needed
			  ```
			-
		- #### [[nested functions]]
		  collapsed:: true
			- In C++ nested functions are NOT supported
			- You can't define a function inside another function
			-
		- #### [[parameter]] and [[argument]]
		  collapsed:: true
			- ```C++
			  #include <iostream>
			  
			  void printNum(int x) {  // (int x) is called "parameter"
			    std::cout << x << '\n';
			  }
			  
			  int main() { 
			  	printNum(10);  // (10) is called "argument"
			    	return 0;
			  }
			  ```
			-
			- When a function is called, all of the parameters of the function are created as variables, the value of each argument is copied into the matching parameter
			- In memory there will be 2 variables with different addresses but same value
			- The parameter will be destroyed after the function ends, but the argument passed from the caller function will not be destroyed
			- When you want to update a value from a separate function, you should pass the [[pointer]] to the variable
			- ```C++
			  #include <iostream>
			  
			  void updateNum(int *pX) {
			    	*pX = 10;
			  }
			  
			  int main() {
			  	int x { 1 };
			    	updateNum(&x);
			  }
			  ```
			-
		- #### [[out of scope]]
		  collapsed:: true
			- ```C++
			  #include <iostream>
			  
			  int printNum() {
			  	std::cout << "Number: " << x << '\n';  // [ERROR] --> 'x' is out of scope
			  }
			  
			  int main() {
			    	int x { 10 };
			    	printNum();
			    	return 0;
			  }
			  ```
			-
		- #### [[going out of scope]]
		  collapsed:: true
			- ```C++
			  #include <iostream>
			  
			  int main() {
			    	int x { 2 };
			  	return 0;  	
			  }
			  // Here the variable x is going out of scope, end of the curly braces
			  ```
			-
	- ### [[namespace]]
	  collapsed:: true
		- ```C++
		  std::cout  // "std" is the "C++ Standard Library" namespace
		  		   // (::) is called Scope Resolution Identifier
		  ```
		-
		- You can access an identifier inside a namespace by using the [[scope resolution identifier]] (double colon *"::"* between the namespace and the identifier)
		-
		- #### using *"using namespace"* command #[[bad practice]]
			- It is preferable to not use *"using namespace"* command
			- You should avoid using this command in order to avoid [[naming collisions]]
			- ```C++
			  using namespace std;
			  
			  int main() {
			  	cout << "Hello World!\n";  // It isn't explicitly known where "cout" is declared
			    	return 0;
			  }
			  ```
			-
	- ### [[preprocessor]]
		-
-
-