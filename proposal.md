# Proposal

## What will (likely) be the title of your project?

Proof Validation

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

I wish to build a program that validates given proofs in sentential and predicate logic.

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

My program will be built in Python. It will allow the user to input a proof as some set of premises and a conclusion in logical notation. It will then check if the proof is in sentential or predicate logic to determine which rules to apply. Finally, it will output whether or not the proof is logically valid.

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

N/A

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

N/A

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

I would like to at least accomplish the program's being able to check simple sentential logic proofs.

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

A better outcome would be to be able to check predicate logic proofs.

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

The best outcome would be to have a GUI for the user to input their premises/conclusions/subproofs; it may also be possible to write an automatic proof machine for simple sentential proofs.

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

I will first outline my goals and general structure of the program. I will determine whether I'd rather use a parser generator like lark or not, and if not, whether I will use typical notation (which would require the user to use explicit parentheses) or reverse polish notation. 
If I choose to use a parser generator then I would have to learn how these work and how to work with them. I also may need to study some meta-logic to determine what is actually theoretically achieveable (e.g. predicate logic is undecideable, hence an automatic proofer for this would be more difficult to achieve and would have to be time limited).