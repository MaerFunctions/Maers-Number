# Maers-Number
A fast-growing mathematical function exceeding Rayo’s number..

Maer’s number (written as Maer(n)) is a large number idea from math logic.. it’s related to Rayos number, but instead of only caring about what one fixed language can define, it looks at what entire formal systems can define and prove

You start with a number n, which is just a limit on how long a definition is allowed to be.. with that limit, you look at all sound, computably enumerable theories of arithmetic. Sound just means the theory never proves false stuff about natural numbers

Inside each of those theories, you look at every total function that can be defined using at most n symbols.. some of these functions grow insanely fast, depending on how strong the theory is. Maer(n) is defined to be bigger than the outputs of all of those functions, across all such sound theories

What really makes Maer blow up is that it doesn’t stop at one theory.. it also allows reflection, meaning stronger systems can talk about the correctness of weaker ones, when you iterate that idea, Maer(n) keeps jumping past the limits of any single formal system

For small values of n, Maer(n) is still small.. because there just isn’t enough room to define anything crazy, but once n gets big enough, Maer(n) grows extremely fast and ends up being larger than things like Rayos number, TREE numbers, and Garden numbers

Maer’s number isn’t something you can calculate or write out.. the point is to show how big numbers can get when you mix definability, provability, and meta-level reasoning, instead of just raw combinatorics..

(Inspired from Rayo but not copied, made into something original while also using the one thing that can help it stay larger than Rayo)
