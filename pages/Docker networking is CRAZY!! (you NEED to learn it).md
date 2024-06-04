type:: [[video]] 
title:: Docker networking is CRAZY!! (you NEED to learn it)
creator:: [[NetworkChuck]]
topics:: #Docker #networking #[[software development]] 
status:: #[[🌿 to plant]]
language:: [[🇬🇧 ENG]]
link:: [link](https://youtu.be/bKFMS5C4CG0)

-
- [[Docker]] [[networking]] is used to manage different [[network]] of [[containers]]
- By defult, every [[container]] deployed will run in a default [[default bridge]] network
- Each [[container]] has a virtual [[ip address]] that is used by the [[network]]
-
- ## Find the list of current [[network]]
	- To find a list of current active [[docker]] [[network]] you should use this command:
	- ```Terminal
	  docker network ls
	  ```
-
- ## The [[default bridge]] network
	- Every time a new [[container]] is instantiated will be inserted by default in the [[default bridge]] net
	- Each [[container]] will have a virtual [[ethernet]] [[interface]], each connected to the Docker0 bridge
	- The problem with this [[network]] is that we ha to do [[port binding]] manually