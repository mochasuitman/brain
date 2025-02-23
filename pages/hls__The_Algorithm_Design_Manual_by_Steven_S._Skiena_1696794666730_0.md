file:: [The_Algorithm_Design_Manual_by_Steven_S._Skiena_1696794666730_0.pdf](../assets/The_Algorithm_Design_Manual_by_Steven_S._Skiena_1696794666730_0.pdf)
file-path:: ../assets/The_Algorithm_Design_Manual_by_Steven_S._Skiena_1696794666730_0.pdf

- Techniques
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 6523096d-333d-4d4a-8374-20f84fa66e5e
- Resources
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 6523096f-e979-48bd-a046-71806308ad36
- modeling, the art of abstracting a messy real-world application into a clean problem suitable for algorithmic attack
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 65230975-d6bd-415a-9b07-cb1f4ddc9797
- familiar with many classic algorithmic problems,
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 65230990-c9a3-4ae4-81ae-74b6ce7dadbe
- The Catalog of Algorithmic Problems
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 65230b0f-9be8-4366-a7b9-9b086d144b40
- War Stories
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 65230b12-c4ee-4878-bc75-0e268d4a62d7
- Electronic Component
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 65230b16-fdd0-4366-a8bd-e9c4d340ec81
- moral of these stories is that algorithm design and analysis is not just theory, but an important tool to be pulled out and used as needed.
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 65230b91-8bb1-4dff-a314-49f5c2057cbe
- atalog of the75 most important problems arising in practice
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 65230b9e-a10f-475b-9ca0-fef39814a932
- With these implementations available, the critical issue in algorithm design becomes properly modeling your application, more so than becoming intimate with the details of the actual algorithm.
  ls-type:: annotation
  hl-page:: 6
  hl-color:: yellow
  id:: 65230bbd-3e10-4350-90b3-182b8ee65be1
- algorithm must solve a general, well-speciﬁed problem.
  ls-type:: annotation
  hl-page:: 15
  hl-color:: yellow
  id:: 6523a22f-b380-4d09-b63f-0f4faa3ad415
- distinction, between a problem and an instance of a problem
  ls-type:: annotation
  hl-page:: 15
  hl-color:: yellow
  id:: 6523a23b-6f59-452f-90c3-21ac77ba25eb
- algorithm is a procedure that takes any of the possible input instances and transforms it to the desired output.
  ls-type:: annotation
  hl-page:: 15
  hl-color:: yellow
  id:: 6523a249-7598-45e3-8ea2-cdacc8363d42
- three desirable properties for a good algorithm.
  ls-type:: annotation
  hl-page:: 16
  hl-color:: yellow
  id:: 6523a269-9181-4c45-b6d8-1cad2eb6a086
- correct
  ls-type:: annotation
  hl-page:: 16
  hl-color:: yellow
  id:: 6523a26b-a151-45d8-a795-03a0b0d3146f
- eﬃcient
  ls-type:: annotation
  hl-page:: 16
  hl-color:: yellow
  id:: 6523a273-9329-4e03-bf43-283b63afd180
- easy to implement
  ls-type:: annotation
  hl-page:: 16
  hl-color:: yellow
  id:: 6523a277-dcb3-4299-89dd-f6e5a4038fcf
- Correct algorithms usually come with a proof of correctness
  ls-type:: annotation
  hl-page:: 17
  hl-color:: yellow
  id:: 6523a2f6-b2ee-4b6b-b049-f6919753c992
- “it’s obvious” never suﬃces as a proof of correctness
  ls-type:: annotation
  hl-page:: 17
  hl-color:: yellow
  id:: 6523a316-2cad-43d8-8d2e-2e9e3740bc15
- ﬁrst construct an ordering of the contact points
  ls-type:: annotation
  hl-page:: 17
  hl-color:: yellow
  id:: 652410e5-dffe-40af-bb87-b1b2a38d12fa
- he robot arm then proceeds back to the ﬁrst contact point to prepare for the next board, thus turning the tool-path into a closed tour, or cycle.
  ls-type:: annotation
  hl-page:: 17
  hl-color:: yellow
  id:: 652410f9-4783-4e7e-b1eb-a298d9800d0e
- nearest-neighbor heuristic
  ls-type:: annotation
  hl-page:: 18
  hl-color:: yellow
  id:: 6524113b-3c49-405d-b264-8f526f44c266
- simple to understand and implement.
  ls-type:: annotation
  hl-page:: 18
  hl-color:: yellow
  id:: 6524114d-ace4-4059-9173-7ede32ca955c
- there is only one problem. This algorithm is completely wrong.
  ls-type:: annotation
  hl-page:: 18
  hl-color:: yellow
  id:: 6524117d-dffd-49d0-96c5-085217a9f863
- it doesn’t necessarily ﬁnd the shortest possible tour.
  ls-type:: annotation
  hl-page:: 18
  hl-color:: yellow
  id:: 6524118a-8b32-44c3-9390-0469e133353b
- he nearest-neighbor rule is doomed to work incorrectly on certain point sets.
  ls-type:: annotation
  hl-page:: 18
  hl-color:: yellow
  id:: 652411db-e9bb-48d7-a4fa-6b05d27bca0c
- Always walking to the closest point is too restrictive
  ls-type:: annotation
  hl-page:: 19
  hl-color:: yellow
  id:: 652412af-330b-465f-b70e-410d5e689d96
- The quest for an eﬃcient algorithm to solve this problem, called the traveling salesman problem (TSP), will take us through much of this book.
  ls-type:: annotation
  hl-page:: 20
  hl-color:: yellow
  id:: 6525b2a9-a1ba-4a56-91ea-10692021f4e2
- There is a fundamental diﬀerence between algorithms, which always produce a correct result, and heuristics, which may usually do a good job but without providing any guarantee
  ls-type:: annotation
  hl-page:: 21
  hl-color:: yellow
  id:: 6525b2b9-59bc-44e7-b29e-d147477db90e
- Reasonable-looking algorithms can easily be incorrect. Algorithm correctness is a property that must be carefully demonstrated
  ls-type:: annotation
  hl-page:: 23
  hl-color:: yellow
  id:: 6525b4a3-e2b1-482a-ba16-34fea34b3737
- Ensuring the optimal answer over all possible inputs is a diﬃcult but often achievable goal. Seeking counterexamples that break pretender algorithms is an important part of the algorithm design process. Eﬃcient algorithms are often lurking out there; this book seeks to develop your skills to help you ﬁnd them.
  ls-type:: annotation
  hl-page:: 23
  hl-color:: yellow
  id:: 6525b4b6-eaba-4080-bf29-6512511bbece
- need tools to distinguish correct algorithms from incorrect
  ls-type:: annotation
  hl-page:: 23
  hl-color:: yellow
  id:: 6525b5e5-6cb1-4b3e-902c-76849f6059ce
- primary one of which is called a proof
  ls-type:: annotation
  hl-page:: 23
  hl-color:: yellow
  id:: 6525b5ed-dace-4a5e-b188-25c9f425275a
- precise statemen
  ls-type:: annotation
  hl-page:: 23
  hl-color:: yellow
  id:: 6525b5f3-806d-417c-b352-471d166b7ede
- set of assumptions
  ls-type:: annotation
  hl-page:: 23
  hl-color:: yellow
  id:: 6525b5f7-985c-4cee-8e9f-01313e76a0b4
- hain of reasoning
  ls-type:: annotation
  hl-page:: 23
  hl-color:: yellow
  id:: 6525b60f-1e77-45ae-bea0-5aa5a53955c8
- The heart of any algorithm is an idea. If your idea is not clearly revealed when you express an algorithm, then you are using too low-level a notation to describe it
  ls-type:: annotation
  hl-page:: 24
  hl-color:: yellow
  id:: 6525b667-ac71-47a5-a899-ff21355e4ad8
- careful description of the sequence of steps to be performed
  ls-type:: annotation
  hl-page:: 24
  hl-color:: yellow
  id:: 6525b670-eca3-466b-9dc5-6a6167156525
- careful description of the proble
  ls-type:: annotation
  hl-page:: 24
  hl-color:: yellow
  id:: 6525b824-bb01-455a-9343-7e7254776b17
- Problem speciﬁcations have two parts: (1) the set of allowed input instances, and (2) the required properties of the algorithm’s output.
  ls-type:: annotation
  hl-page:: 24
  hl-color:: yellow
  id:: 6525b82d-750b-4a95-8339-ef0dfa1b36f4
- An important and honorable technique in algorithm design is to narrow the set of allowable instances until there is a correct and eﬃcient algorithm. For example, we can restrict a graph problem from general graphs down to trees, or a geometric problem from two dimensions down to one.
  ls-type:: annotation
  hl-page:: 25
  hl-color:: yellow
  id:: 6525b83f-725f-4615-bdea-686a91ac5100
- Finding the right formulation for your problem is an important part of solving it. And studying the deﬁnition of all these classic algorithm problems will help you recognize when someone else has thought about similar problems before you.
  ls-type:: annotation
  hl-page:: 25
  hl-color:: yellow
  id:: 6525b8fc-c365-4875-90c1-b57cf3338776
- two common traps in specifying the output requirements of a problem.
  ls-type:: annotation
  hl-page:: 25
  hl-color:: yellow
  id:: 6525b904-e66a-4417-94dc-390f3128bd20
- asking an ill-deﬁned question
  ls-type:: annotation
  hl-page:: 25
  hl-color:: yellow
  id:: 6525b907-4d1e-422e-b472-4ffff654ebd8
- creating compound goals
  ls-type:: annotation
  hl-page:: 25
  hl-color:: yellow
  id:: 6525b90c-6d5a-4d79-97a7-2e2cb4d69a03
- The best way to prove that an algorithm is incorrect is to produce an instance in which it yields an incorrect answer. 
  ls-type:: annotation
  hl-page:: 25
  hl-color:: yellow
  id:: 6525bb4c-b0a2-4deb-b999-9643278621bd
- counter-examples
  ls-type:: annotation
  hl-page:: 25
  hl-color:: yellow
  id:: 6525bb50-de6d-45a5-887b-8ab5f8fe5c6f
- Good counter-examples have two important properties
  ls-type:: annotation
  hl-page:: 25
  hl-color:: yellow
  id:: 6525bb6d-a1c3-4387-8ca8-af3596e4f743
- Veriﬁability
  ls-type:: annotation
  hl-page:: 25
  hl-color:: yellow
  id:: 6525bb6f-9f7a-4f49-890f-91473d54cdc1
- Simplicity
  ls-type:: annotation
  hl-page:: 26
  hl-color:: yellow
  id:: 6525bb71-ee9c-4771-abca-3248343c04b7
- Searching for counterexamples is the best way to disprove the correctness of a heuristic
  ls-type:: annotation
  hl-page:: 26
  hl-color:: yellow
  id:: 6525bc89-fa9e-4fb7-9a9d-2cb38507f269
- Think small
  ls-type:: annotation
  hl-page:: 26
  hl-color:: yellow
  id:: 6525bca6-6a84-49db-88e7-df3eda0f6f38
- Think exhaustively
  ls-type:: annotation
  hl-page:: 26
  hl-color:: yellow
  id:: 6525bcb0-9099-4804-a88a-240a347cf7df
- Hunt for the weakness
  ls-type:: annotation
  hl-page:: 26
  hl-color:: yellow
  id:: 6525bcb4-2c9f-4a1f-a706-102e2c9f6ca2
- Go for a tie
  ls-type:: annotation
  hl-page:: 26
  hl-color:: yellow
  id:: 6525bcb7-e83b-42b6-b7a1-c7f1e123e3dc
- Seek extremes
  ls-type:: annotation
  hl-page:: 26
  hl-color:: yellow
  id:: 6525bcbb-84e0-4520-8505-a4f5e307b6cf
- calculate what answer your algorithm will give in this instance, and (2) display a better answer so as to prove the algorithm didn’t ﬁnd it.
  ls-type:: annotation
  hl-page:: 25
  hl-color:: yellow
  id:: 6526dcf3-9eec-4e9d-9f1d-208068c1ee5a
- They make clear exactly why the proposed algorithm fails.
  ls-type:: annotation
  hl-page:: 26
  hl-color:: yellow
  id:: 6526dd00-db9f-4a0e-af61-2269a38cb2a0
- worth simplifying it down to its essence
  ls-type:: annotation
  hl-page:: 26
  hl-color:: yellow
  id:: 6526dd08-bbab-4267-9485-58fb6e6273a8
- mateur algorists tend to draw a big messy instance and then stare at it helplessly. The pros look carefully at several small examples, because they are easier to verify and reason about.
  ls-type:: annotation
  hl-page:: 26
  hl-color:: yellow
  id:: 6526de56-862b-406c-9845-c8617f5ed0e3
- usually easier to verify or reason about extreme examples than more muddled ones
  ls-type:: annotation
  hl-page:: 26
  hl-color:: yellow
  id:: 6526df5b-48c1-4092-a3ef-db421e1d11cb
- oof or demonstration of correctness is needed. Often mathematical induction is the method of choice
  ls-type:: annotation
  hl-page:: 27
  hl-color:: yellow
  id:: 6526e0cb-4e88-4b72-8243-1c64aa1d5bee
- The reason both seemed like magic is because recursion is mathematical induction
  ls-type:: annotation
  hl-page:: 27
  hl-color:: yellow
  id:: 6526e0ec-27e2-4c84-9772-9e0465b85cfb
- Once you understand either recursion or induction, you should be able to see why the other one also works.
  ls-type:: annotation
  hl-page:: 27
  hl-color:: yellow
  id:: 6526e0fd-5df5-4fc8-8afa-d2298112e91e
- many of the algorithms we study are either recursive or incremental.
  ls-type:: annotation
  hl-page:: 27
  hl-color:: yellow
  id:: 65280b48-11c4-4752-adf3-8646958a6168
- Mathematical induction is usually the right way to verify the correctness of a recursive or incremental insertion algorithm
  ls-type:: annotation
  hl-page:: 28
  hl-color:: yellow
  id:: 65280be8-e712-4ca1-b2e6-ee13b84d04e5
- One must be suspicious of inductive proofs, however, because very subtle reasoning errors can creep in
  ls-type:: annotation
  hl-page:: 27
  hl-color:: yellow
  id:: 65280c13-9ea1-4416-801d-f13e2dcb99bb
- boundary errors
  ls-type:: annotation
  hl-page:: 27
  hl-color:: yellow
  id:: 65280c16-0801-4fe0-8c06-eb68721091ae
- more common class of inductive proof errors concerns cavallier extension claim
  ls-type:: annotation
  hl-page:: 27
  hl-color:: yellow
  id:: 65280c1f-8165-43dd-a7fe-c960d84b04f9
- Summation formula are concise expressions describing the addition of an arbitrarily large set of numbers
  ls-type:: annotation
  hl-page:: 29
  hl-color:: yellow
  id:: 652afff6-7ab6-4498-ac2c-7719f2824e25
- Arithmetic progressions 
  ls-type:: annotation
  hl-page:: 29
  hl-color:: yellow
  id:: 652c4a4c-2a02-47e4-bba9-3e03b0d59a52
- Geometric series
  ls-type:: annotation
  hl-page:: 30
  hl-color:: yellow
  id:: 652c4a50-b341-41fa-998f-ea9e58573559
- general trick of separating out the largest term from the summation to reveal an instance of the inductive assumption lies at the heart of all such proofs
  ls-type:: annotation
  hl-page:: 31
  hl-color:: yellow
  id:: 654177fb-b41b-4f86-ab05-bdfa585dd9c7
- Indeed, proper modeling can eliminate the need to design or even implement algorithms, by relating your application to what has been done before
  ls-type:: annotation
  hl-page:: 31
  hl-color:: yellow
  id:: 6541785a-f6f6-4761-bad3-b7c0bb3bade5
- you must learn to describe your problem abstractly, in terms of procedures on fundamental structures.
  ls-type:: annotation
  hl-page:: 31
  hl-color:: yellow
  id:: 65417871-b8dc-45de-8aa6-8ae51070431f
- Permutations
  ls-type:: annotation
  hl-page:: 31
  hl-color:: yellow
  id:: 654a81bc-4c51-4c2c-a6d7-c5f8a2c3c84f
- Subsets
  ls-type:: annotation
  hl-page:: 31
  hl-color:: yellow
  id:: 654a81be-b81b-4c8e-9089-2d093adbb0c2
- Trees
  ls-type:: annotation
  hl-page:: 32
  hl-color:: yellow
  id:: 654a81c0-3344-481c-868b-69d6f885811a
- Points
  ls-type:: annotation
  hl-page:: 32
  hl-color:: yellow
  id:: 654a81c3-512b-4f75-acdd-b66f3e444369
- Polygons
  ls-type:: annotation
  hl-page:: 32
  hl-color:: yellow
  id:: 654a81c5-498e-49e3-adbf-52f363525542
- Strings
  ls-type:: annotation
  hl-page:: 32
  hl-color:: yellow
  id:: 654a81cb-4e44-4c6b-bbf3-523d86cba17d
- The act of modeling reduces your application to one of a small number of existing problems and structures. Such a process is inherently constraining, and certain details might not ﬁt easily into the given target problem. Also, certain problems can be modeled in several diﬀerent ways, some much better than others
  ls-type:: annotation
  hl-page:: 33
  hl-color:: yellow
  id:: 654a82ab-4aa7-4fda-8926-35f241f8925c
- Take-Home Lesson: Modeling your application in terms of well-deﬁned structures and algorithms is the most important single step towards a solution.
  ls-type:: annotation
  hl-page:: 33
  hl-color:: yellow
  id:: 654a82bc-e28c-4ca7-8ed8-63aa765fda1b
- think recursively is learning to look for big things that are made from smaller things of exactly the same type as the big thing.
  ls-type:: annotation
  hl-page:: 33
  hl-color:: yellow
  id:: 654a8350-9f46-40d2-950d-7c80ce2d6209
- Recursive descriptions of objects require both decomposition rules and basis cases, namely the speciﬁcation of the smallest and simplest objects where the decomposition stops. 
  ls-type:: annotation
  hl-page:: 34
  hl-color:: yellow
  id:: 654a840c-d60d-4f9a-9c12-68b12fec5fa9
- simple operation
  ls-type:: annotation
  hl-page:: 43
  hl-color:: yellow
  id:: 654b5252-dcf6-4eaf-97f1-839938ecc207
- one time step
  ls-type:: annotation
  hl-page:: 43
  hl-color:: yellow
  id:: 654b5255-a673-48b4-ad53-9fa755128fe3
- Loops and subroutines are not considered simple operations
  ls-type:: annotation
  hl-page:: 43
  hl-color:: yellow
  id:: 654b525c-f396-4c6a-a874-ae89df5596f7
- Each memory access takes exactly one time step
  ls-type:: annotation
  hl-page:: 44
  hl-color:: yellow
  id:: 654b525f-8a21-4c8f-be66-38a434aa0158
- worst-case complexity of the algorithm is the function deﬁned by the maximum number of steps taken in any instance of size n. 
  ls-type:: annotation
  hl-page:: 45
  hl-color:: yellow
  id:: 654b52b6-e1b7-40b2-841c-dfefb268216a
- best-case complexity of the algorithm is the function deﬁned by the minimum number of steps taken in any instance of size n
  ls-type:: annotation
  hl-page:: 45
  hl-color:: yellow
  id:: 654b52b9-1f63-4986-86d5-b6944844d114
- verage-case complexity of the algorithm, which is the function deﬁned by the average number of steps over all instances of size n
  ls-type:: annotation
  hl-page:: 45
  hl-color:: yellow
  id:: 654b52bd-5f03-40e4-93eb-78924e6651ad
- Have too many bumps 
  ls-type:: annotation
  hl-page:: 46
  hl-color:: yellow
  id:: 654b54a5-8dfe-40a3-afc3-b0c514effd2d
- Require too much detail to specify precisely
  ls-type:: annotation
  hl-page:: 46
  hl-color:: yellow
  id:: 654b54a8-a173-4ee9-835e-9527d51b54fb
- precise answer depends upon uninteresting coding details
  ls-type:: annotation
  hl-page:: 46
  hl-color:: yellow
  id:: 654b54bc-8ecc-4f65-8044-95a51398eca4
- f (n) = O(g(n)) means c · g(n) is an upper bound on f (n).
  ls-type:: annotation
  hl-page:: 47
  hl-color:: yellow
  id:: 654b5c65-b672-41af-84c8-dead4d44e0ff
- f (n) = Ω(g(n)) means c · g(n) is a lower bound on f (n).
  ls-type:: annotation
  hl-page:: 47
  hl-color:: yellow
  id:: 654b5c6a-2686-4646-bbdd-2ac21e19a98c
- f (n) = Θ(g(n)) means c1 · g(n) is an upper bound on f (n) and c2 · g(n) is a lower bound on f (n)
  ls-type:: annotation
  hl-page:: 47
  hl-color:: yellow
  id:: 654b5c70-e364-4ad1-a236-9407cb85a4e6
- The Big Oh notation and worst-case analysis are tools that greatly simplify our ability to compare the eﬃciency of algorithms.
  ls-type:: annotation
  hl-page:: 47
  hl-color:: yellow
  id:: 654ca247-f16a-400e-9ba7-66881ee995e8
- we cavalierly discard the multiplicative constants.
  ls-type:: annotation
  hl-page:: 49
  hl-color:: yellow
  id:: 654ca262-77b3-47d4-aa10-a23398e30aa7
- how long algorithms that use f (n) operations take to run
  ls-type:: annotation
  hl-page:: 50
  hl-color:: yellow
  id:: 654ca273-0a2b-44a7-aafe-2a9bdb34ea30
- only a few function classes tend to occur in the course of basic algorithm analysis. 
  ls-type:: annotation
  hl-page:: 51
  hl-color:: yellow
  id:: 654ca4dd-cb98-4c36-bbfd-043222484933
- Constant functions, f (n) = 1 
  ls-type:: annotation
  hl-page:: 51
  hl-color:: yellow
  id:: 654ca4ed-3ebe-4e1e-9b3e-6b4e1630e5b9
- Logarithmic functions, f (n) = log n
  ls-type:: annotation
  hl-page:: 51
  hl-color:: yellow
  id:: 654ca4f1-0167-4a55-9686-e8d1410ab0bb
- Linear functions, f (n) = n
  ls-type:: annotation
  hl-page:: 51
  hl-color:: yellow
  id:: 654ca4f4-2e47-40a6-8b6c-18191d87b773
- Superlinear functions, f (n) = n lg n
  ls-type:: annotation
  hl-page:: 51
  hl-color:: yellow
  id:: 654ca4f9-f977-40c6-8d6c-ae9d151a0c03
- Quadratic functions, f (n) = n2
  ls-type:: annotation
  hl-page:: 51
  hl-color:: yellow
  id:: 654ca4fe-30d4-4a65-b252-e54ce81546af
- Cubic functions, f (n) = n3
  ls-type:: annotation
  hl-page:: 51
  hl-color:: yellow
  id:: 654ca500-1144-4b18-b1c7-d29faf6d750d
- Exponential functions, f (n) = cn
  ls-type:: annotation
  hl-page:: 51
  hl-color:: yellow
  id:: 654ca504-4ed7-400b-8db3-80b87e4a888b
- Factorial functions, f (n) = n!
  ls-type:: annotation
  hl-page:: 51
  hl-color:: yellow
  id:: 654ca507-9b94-4360-963f-8f7e6456482d
- Although esoteric functions arise in advanced algorithm analysis, a small variety of time complexities suﬃce and account for most algorithms that are widely used in practice.
  ls-type:: annotation
  hl-page:: 52
  hl-color:: yellow
  id:: 654ccfd4-7c92-472a-8306-c2fc7ac5e470
- The sum of two functions is governed by the dominant one
  ls-type:: annotation
  hl-page:: 52
  hl-color:: yellow
  id:: 654cf567-0ce3-48a9-8c69-8d20ed56abb2
- Multiplication is like repeated addition
  ls-type:: annotation
  hl-page:: 52
  hl-color:: yellow
  id:: 654cf574-fc5d-40ee-abf5-1062aac23f7a
- when two functions in a product are increasing, both are important
  ls-type:: annotation
  hl-page:: 53
  hl-color:: yellow
  id:: 654cf7b3-0fb5-48c0-a814-53ccc7c0d5b2
- A basic rule of thumb in Big Oh analysis is that worst-case running time follows from multiplying the largest number of times each nested loop can iterate. 
  ls-type:: annotation
  hl-page:: 55
  hl-color:: yellow
  id:: 654e9041-d019-41d2-afcc-fb792ca4f527