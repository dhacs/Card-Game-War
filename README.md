# War Project!

This repository contains **three programs** that all simulate the card game of War. War is a simple card game that involves two players each receiving half a shuffled deck of cards. Players take turns revealing the top card from their deck, and the player with the higher card takes both cards and adds them to the bottom of their deck. If there is a tie in the game, the function is called to resolve the tie by adding cards to a "warchest" and continuing the game recursively until one player wins.

This project was programmed in three diferent languages: **Elixir**, **Haskell**, and **Rust**. It follows proper software principles and design patterns such as tail-end recursion and pattern matching. 

In both Elixir and Haskell, the 'deal' function is implemented, which takes a list of 52 integers representing a shuffled deck of cards, distributes the cards evenly between two players, and then calls the 'gametime' function recursively to determine and return the winning player's hand as a list of 52 integers.

In Rust, the 'deal' function takes an immutable reference to an array of unsigned 8-bit integers (u8), distributes the cards evenly to two vectors of u8, and calls the gametime function recursively to play the game. It converts the winning player's hand to a new array of u8 and returns it's ownership.


For legal purposes, the code can only be shared upon request.
