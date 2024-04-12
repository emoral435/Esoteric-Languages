# This file is used for the ideation of the slides used for this project.

## At minimum, the presentation should address the following: 
• Give a brief overview of the language. ✅
• Who designed the language and why? ✅
• What does the syntax look like? ✅
• What programming paradigm(s) does the language implement? ✅
• If appropriate, is the language static or dynamic? Explain why. ✅
• How does this language compare to the ones we have learned (SQL, Python, F#, 
Prolog and Go)? What are the similarities and differences? ✅
• How does it handle memory? ✅
• Show a short but meaningful example (more than “Hello World!”). Live coding 
would be ideal for this, but is not required.

## Things I also want to add in order to make the presentation fun:
• What is an esoteric language? ✅
• Starlogs to end off the presentation ✅
• Truttle1 videos ✅
• A fun mario speedrunning reference for all the Mario fans
• GIFS!! 

## Answers to the above questions:
• What is an esoteric language?
	* Most people are used to programming languages that can efficiently solve problems related to real world industries
	or are used to produce meaningful impact within communities.
		- JavaScript, C++, and Python are the programming languages that usually come first in mind
	* Esoteric languages take a different approach - they explore the creative representations that programming languages can represent.
		- They are not made to be efficient, and are usually made up as a joke. 
		- show picture of Piet - They still can have creative merit, however, and perhaps we can learn from *SOME* of them

• [Truttl1 playlist of esoteric languages](https://youtube.com/playlist?list=PLO-PlVJRfGIVZuzu6e_0qOvqRnM_TdNye&si=o56gGtuH2fZsMT0y)

• Give a brief overview of the language.
	* In this presentation, we will be explore MarioLANG.
		- Picture of MarioLANG code
		- Clip of mario being dramatic to the code [found here](https://youtu.be/XymIOAuCCHw?si=IaTZ_ikwBqlgwMDd&t=15)
		- The language is composed of characters that make the source code look like a Mario level stage!
		- Mario himself represents the instruction pointer. Each character then either modifies Mario, the instruction pointer,
		or modifies a piece of memory that we can later use ourself to print to the console!
		- The language uses a one-dimensional array, or tape, to store data. In our language, item blocks affect and update our tape!
		We can move left and right, and increment our tape as we want. We can then print our tape as ASCII to get out desired console output.
		- This language does not have an official interpreter or compiler, but the author of this language does have an interpretation of what he
		himself thinks an interpreter should look like for the language. Yes, even the author of this language does not know how an interpreter would look like.

• Who designed the language and why? 
	* The creator of the language is [Wh1teWorlf](https://esolangs.org/wiki/User:Wh1teWolf). He is an anonymous developer, however, his self-bio on esolangs.orgs shows that
	he loves working on esoteric languages in his free time, specifically BrainF*ck.
	* He loves working on the aforementioned language so much that he has made several interpreters for the languages. All his variations of the language are well documented - that is, all but MarioLANG.
	* We know he is working on version 2.0, but we do not know why it was created in the first place. But... seeing as it looks cool, do we need a reason outside outside of it just being cool?

• What does the syntax look like?
	* The syntax for the language is composed of three distinct modules - *parts, items, and instructions*
	* Parts
		- Parts make up the world that Mario, the instruction pointer, resides in. This can be walls, floors (which are classed the same - they just prevent Mario from moving), elevators, etc.!
		- Showcase parts in a picture
	* Items
		- Items are like the items found in a real Mario world. They can change the instruction pointers direction, what is on our tape, and what gets output to the console.
		- Showcase items in a picture
	* Instructions
		- Instructions tell Mario what do currently do. This includes to go right, jump, stop walking, start walking THE OTHER way, etc.
		- Showcase instructions in a picture
	
• What programming paradigm(s) does the language implement?
	* MarioLANG is imperative by default. Each command within its syntax does one thing and one thing precisely. Every step is defined and definite, and the order of operations is decided by the programmer, making it imperative
	* To derive this language further, MarioLANG is a procedural language. Once we start the program, each time we hit an ASCII character representing Mario's world, we start a procedure that can change memory, or state.
		- Show picture of JavaScript from DEV article 
	* MarioLANG is also an esoteric programming language. It was made to just represent Mario's world via ASCII characters, and is actually quite fun when you get the hang of it.

• How does this language compare to the ones we have learned (SQL, Python, F#, Prolog and Go)? What are the similarities and differences?
	* MarioLANG under the hood still uses memory to store state and information, just like the other languages.
	* MarioLANG can be interpreted, just as Python is interpreted, and at its core, MarioLANG files have to adhere to certain rules to make it syntactically correct.
	* MarioLANG does not follow and support a BNF structure, instead, opting to simply be a storage management system.
	* No known company uses MarioLANG in production... yet.
	* MarioLANG does abide by programming paradigm conventions, just as the rest of the other languages we have learned do.
	* MarioLANG has no way to define new functions, new states that have not been pre-defined, and also does not support concurrency or the usage of external libraries.

• If appropriate, is the language static or dynamic? Explain why.
	* We are only able to store one state within the game, and that is the state in our tape / array. 
	* This state can only be an integer, so technically, since we cannot change the type of our state container during compilation,
	this classifies MarioLANG as a statically typed language.
	* Perhaps in the future, MarioLANG 2.0 can support items that change the state to store multiple or different types on the tape.

• How does it handle memory?
	* MarioLANG supports having a dynamic array of integers, also known as a tape.
	* This array can be either on the heap or on the stack. For most cases, since there is only one state array, stack-overflow problems are not a concern.
	* In the compiler that I found and that is included in this GitHub repository, we use a vector that is stored in the heap.

• Thank you! Link to references and GitHub repository
* [Starlogs](https://starlogs.dev/emoral435/Esoteric-Languages)




## References
- [Wiki](https://esolangs.org/wiki/Main_Page)
- [Functional vs Object Oriented vs Procedural programming ](https://dev.to/jjablonskiit/functional-vs-object-oriented-vs-procedural-programming-2lc5)


