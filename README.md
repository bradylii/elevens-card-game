"Elevens" Part 4
================

This is the fourth part of what will eventually build into an implementation of the "Elevens" solitare game. 

## Introduction

You implemented a Deck class in Activity 2. This class should be complete except for the shuffle method. You also implemented a DeckTester class that you used to test your incomplete Deck class.

In Activity 3, you implemented methods in the Shuffler class, which shuffled integers. Now you will use what you learned about shuffling in Activity 3 to implement the Deck shuffle method.

Think about how you shuffle a deck of cards by hand. How well do you think it randomizes the cards in the deck?  This assignment explores two possible approaches to shuffling the deck.

## Submitting

We are using Repl's built in unit tests and submission.  Once you have completed the project (including your own additional testing in DeckTester.java), click the check-mark on the left navigation panel to run the testShuffle unit test.  If the test passes along with your testing/validation of shuffle(), go ahead and submit your project using the button in the upper right.

If testShuffle fails, the error message will give you a hint as to what failed, but you'll likely need to do some testing of your own to investigate exactly what went wrong.  Try to figure out how your code might fail, and add more tests to DeckTester.java to see if you can reproduce it yourself.

## Exercises

1. The included file Deck.java, is a correct solution from Activity 2. Complete the Deck class by implementing the shuffle method. Use the efficient selection shuffle algorithm from Activity 3.Note that the Deck constructor creates the deck and then calls the shuffle method. The shuffle method also needs to reset the value of size to indicate that all of the cards can be dealt again.

2. The included DeckTester.java file, provides a basic set of Deck tests. It is similar to the DeckTester class you might have written in Activity 2. Add additional code at the bottom of the main method to create a standard deck of 52 cards and test the shuffle method. You can use the Deck toString method to “see” the cards after every shuffle.