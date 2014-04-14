PyCards
=====

A python module to easily create and use a deck of cards.

#What it does#

This python module creates and easy way to implement a standard 52 deck of cards into your python program to use. You can use the python class files individually or you can just download and use the module provided by placing it in your program directory.

Eventually, I may add more to this module such as a hand of cards and more error detection.

#Usage#

If you are using the individual files in your project:  
  
	from card import Card # To import and use a playing card
	from deck import Deck # To import and use a deck of cards

If you are using the PyCard module:

	>>> from PyCard import * # To import and use the entire PyCard module

To create a standard 52 deck of cards unshuffled:

	>>> deck = Deck() # creates and unshuffled deck of cards
	
To put all cards back in the deck and shuffle:
  
  	>>> deck.shuffle() # shuffles the deck of cards
  
To deal a single card from the deck:

  	>>> hand1.append(deck.dealCard()) # Deals a single card from the deck to a hand
  
  	>>> kitty.append(deck.dealCard()) # Deals a single card to a throwaway pile
  
To print out a card:

  	>>> print card # Prints the rank and suit of a single playing card
  
  	>>> # The following prints out a hand of cards
  	>>> output = "Cards in hand: "
  	>>> for card in hand:
  	>>>   output += str(card) + " "
  	>>> print output

To print out the entire deck:

  	>>> print deck # Prints out every card in the deck
	
#Demos#

The repository holds a demo, which is published on the github project page:
[Demo](https://github.com/Chippers255/EuchrePy)
