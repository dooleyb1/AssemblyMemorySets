# AssemblyMemorySets
ARM Assembly Language program which uses memory arrays to perform basic set operations.

The operations available are:

* **Closure**
* **Symmetric Difference**
* **Closure**

## Closure

A mathematical set, A, containing 32-bit signed integers is stored in memory. This program determines whether, for every integer in the set, the set **also contains the negation** of that integer.

## Symmetric Difference

Two mathematical sets, A and B, containing 32-bit unsigned integers are stored in memory. program that will create a third set, C , that is the [symmetric difference](https://en.wikipedia.org/wiki/Symmetric_difference) of A and B.

## Anagrams

Two strings are anagrams of each other if one string can be formed by rearranging the characters
of the other. Each letter of one string may only be used once to form the other string. For
example, ”tacos” is an anagram of ”coats”. The string ”bests” **is not**, however, an anagram of
”beets” because although they contain the same characters, each character does not occur the
same number of times.

The program stores 1 in R0 if the string is an Anagram and zero otherwise.

## Assembly Files

* **[Closure.s](https://github.com/dooleyb1/AssemblyMemorySets/blob/master/closure/Closure.s)** - Program to determine whether or a set is closed.

* **[SymmDiff.s](https://github.com/dooleyb1/AssemblyMemorySets/blob/master/symmetric_difference/Symmdiff.s)** - Program to determine the Symmetric Difference of two sets A and B.

* **[Anagram.s](https://github.com/dooleyb1/AssemblyMemorySets/blob/master/anagram/Anagram.s)** - Program to determine whether or not two words are anagrams of each other.
