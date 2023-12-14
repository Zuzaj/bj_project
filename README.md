<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->
<h1 align="center"> 🃏 Black Jack project 🃏 </h1>


## 💡 Topic

Blackjack (formerly black jack and vingt-un) is a casino banking game. It is the most widely played casino banking game in the world. It uses decks of 52 cards and descends from a global family of casino banking games known as "twenty-one". This family of card games also includes the European games vingt-et-un and pontoon, and the Russian game Ochko. Blackjack players do not compete against each other. The game is a comparing card game where each player competes against the dealer.


## 🐍 Programming language 
Whole code is written in python programming language.

## Game components (classes):
* ♦️  Card - class representing a particular card
* ♥️  Deck - class composed of multiple cards, with methods to deal and shuffle available cards
* ♣️  EnglishDeck - class inheriting from Deck, with all possible cards
* ♠️  Hand - class representation of player's hand, includes methods to add cards and sum their value
* 🂵  Player - class that stands for each player and his cards
* 🃞  BlackjackGame - class imitating the real game and its rules
* 🂸  BlackjackGUI - class responsible for the game's interface

## Rules
The object is to have a hand with a total value higher than the dealer’s without going over 21. Kings, Queens, Jacks and Tens are worth a value of 10. An Ace has the value of 1 or 11. The remaining cards are counted at face value.

1. You are dealt two cards each whilst the dealer is dealt one face up. If your first 2 cards add up to 21 (an Ace and a card valued 10), that’s Blackjack! If they have any other total, decide whether you wish to ‘draw’ or ‘stay’. You can continue to draw cards until you are happy with your hand.

2. Then the dealer draws another card for their hand. They must draw until they reach 17 or more.

3. Once all cards are drawn, whoever has a total closer to 21 than the dealer wins. If player’s hand and dealer’s hand have an equal value, it’s a tie.



<p align="right">(<a href="#readme-top">back to top</a>)</p>




