
BLACKJACK
This was our first CMSC132 (data structure and algos) Project black jack. Students were given nothing but a few helper classes to work around and use.

Given classes:
Card.java - Contained instance variables of suit and rank that also had constructors and a to String and equals method to use as helper methods throughout the project.

Rank.java- contained enumerator variables representing card symbols and there intended values.

Suit - containing enumerators for the Suit

Hand Assesment.java - an enumerator class used to reach a conclusive answer to the current hand a player/dealer has

Game Result.java- an enumerator class used to conclude a discrete answer to a win/loss/push/black jack

GUI


Completed classes:

1. BlackjackModel.java- The BlackjackModel class is responsible for managing the mechanics of a Blackjack game. It keeps track of the dealer's and player's cards, provides methods for dealing cards, evaluating hands, and determining the game outcome. The class has a deck instance variable representing the deck of cards used in the game. It initializes the deck, shuffles it, and deals initial cards to the dealer and player. Methods are available to add cards to the player's or dealer's hand, assess the value of a hand, and determine whether the dealer should take another card. The class also compares the assessments of the player's and dealer's hands to determine the game result.
The BlackjackModel class provides the necessary functionality to manage the game logic of a simple Java Blackjack game. It handles card dealing, hand evaluation, and game outcome determination. The class ensures the integrity of the game by tracking the state of the dealer's and player's cards and applying the rules of Blackjack. With its methods for manipulating cards, evaluating hands, and assessing the game result, the BlackjackModel class serves as the backbone of the game mechanics.

The class provides the following methods:

getDealerCards(): Returns a copy of the dealer's current cards.

getPlayerCards(): Returns a copy of the player's current cards.

setDealerCards(ArrayList<Card> cards): Manually sets the dealer's cards.

setPlayerCards(ArrayList<Card> cards): Manually sets the player's cards.

 createAndShuffleDeck(Random random): Creates a new deck and shuffles it using the provided random seed.

  initialDealerCards(): Deals the initial two cards to the dealer from the deck.

  initialPlayerCards(): Deals the initial two cards to the player from the deck.

  playerTakeCard(): Adds a new card to the player's cards from the deck.

  dealerTakeCard(): Adds a new card to the dealer's cards from the deck.

  possibleHandValues(ArrayList<Card> hand): Takes a hand of cards as input and calculates the possible values it can add up to. Returns an 
  
  ArrayList of Integer values representing the possible hand values.

  assessHand(ArrayList<Card> hand): Determines the type of hand based on the values of the cards in the hand. Returns a HandAssessment enum value representing the assessment of the hand.

  gameAssessment(): Compares the assessments of the player's and dealer's hands to determine the game result. Returns a GameResult enum value representing the game result.

  dealerShouldTakeCard(): Evaluates the dealer's hand to determine whether the dealer should take another card ("hit") or not. Returns true if the dealer should take a card, false otherwise.

2.  The Deck class in the deckOfCards package represents a standard deck of 52 playing cards. It provides functionality for creating and managing the deck, including shuffling the cards and dealing individual cards.
The class has the following instance variables:
cards: An ArrayList of Card objects representing the cards in the deck.
DECK_SIZE: A constant integer value indicating the total number of cards in a standard deck (52).
The class provides the following methods:
Constructor: Initializes the cards ArrayList by iterating through all possible combinations of Suit and Rank values and creating a Card object for each combination.
shuffle(Random randomNumberGenerator): Shuffles the order of the cards in the deck using the provided random number generator. This ensures that the cards are randomly distributed.
dealOneCard(): Takes the top card from the deck (at index 0), removes it from the deck, and returns it as a Card object.
The Deck class allows for the creation, shuffling, and dealing of cards from a standard deck. It serves as a fundamental component for any card game that requires a deck of cards, providing the necessary functionality for managing and manipulating the deck.


  <img width="624" alt="Screen Shot 2023-05-20 at 7 16 01 PM" src="https://github.com/Justin-STEAMDreams/CMP-Be-CreARTive-2023/assets/123784372/bc4de977-e3ae-4434-ab11-5c007d99ae2b">
  
  <img width="612" alt="Screen Shot 2023-05-20 at 7 16 35 PM" src="https://github.com/Justin-STEAMDreams/CMP-Be-CreARTive-2023/assets/123784372/ab26ed93-3eec-4e92-a42a-732deeea2110">
<img width="622" alt="Screen Shot 2023-05-20 at 7 17 17 PM" src="https://github.com/Justin-STEAMDreams/CMP-Be-CreARTive-2023/assets/123784372/91227fa9-1d9b-4934-b267-b76193bc456d">


  

