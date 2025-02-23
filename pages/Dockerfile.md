- It is a file that contains the definition of how to build a [[Docker]] [[image]] from a developed application
-
- ## The "FROM" command
	- It starts from a parent [[image]] (usually a lightweight [[Linux]] distro)
	- Each Dockerfile should start with the FROM command, it defines the parent [[image]]
	- ```Terminal
	  // FROM <image>:<version>  (generic form)
	  FROM node:19-alpine
	  ```
	-
- ## The "COPY" command
	- It is used to copy the application files from the host into the [[container]]
	- It copies files or directories from <src> and adds them to the filesystem of the [[container]] at the path <dest>
	- This command is executed on the host machine
	- ```Terminal
	  // COPY <src> <dest>  (generic form)
	  COPY package.json /app/
	  COPY src /app/
	  // The name "app" was choosen randomly
	  ```
	-
	- Now package.json file and the entire src folder have been copied inside the /dest/app/ directory inside of the [[container]]
	-
- ## The "WORKDIR" command
	- Is like the command "cd" in [[Windows OS]]
	- It is used to change the current directory in which the commands will be executed
	- Before running the commands to install [[dependencies]] we should change the current directory
	- ```Terminal
	  // WORKDIR <new-dir>  (generic form)
	  WORKDIR /app
	  ```
	-
- ## The "RUN" command
	- After we defined the base image of the container, we should install every [[dependencies]] that is used in our application
	- We created an [[image]] based upon a [[Linux]] distro with [[Node.js]] installed, so we have the ability to run the npm commands to install [[dependencies]]
	- The run command will execute any command in a [[shell]] inside the [[container]] [[enviroment]]
	- ```Terminal
	  RUN <command>  (generic form)
	  RUN npm install 
	  ```
	-
- ## The "CMD" command
	- It is used to write the instruction that is to be executed when a [[Docker]] [[container]] starts
	- There can ONLY be ONE "CMD" command per Dockerfile
	- ```Terminal
	  // CMD ["<executable>", "<parameter-1>", "...", "<parameter-n>"]  (generic form)
	  CMD ["node", "server.js"]
	  ```