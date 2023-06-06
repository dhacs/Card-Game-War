# War-Code

This repository contains code for a public war game implemented in three different languages: Elixir, Haskell, and Rust. The project follows proper software principles and design patterns, such as tail-end recursion and pattern matching, to ensure efficient and maintainable code.

War is a simple card game that involves two players each receiving half a shuffled deck of cards. Players take turns revealing the top card from their deck, and the player with the higher card takes both cards and adds them to the bottom of their deck. If there is a tie in the game, the function is called to resolve the tie by adding cards to a "warchest" and continuing the game recursively until one player wins.

## Files

The repository consists of the following files:

- `War.hs`: Haskell implementation
- `War.ex`: Elixir implementation
- `main.rs`: Rust implementation

## Elixir and Haskell Implementations

In both the Elixir and Haskell implementations, the module "War" is defined. It includes an implementation of the `deal` function, which takes a list of 52 integers representing a shuffled deck of cards. The `deal` function evenly distributes the cards between two players and then recursively calls the `gametime` function to determine the winning player's hand. The winning player's hand is returned as a list of 52 integers.

## Rust Implementation

In the Rust implementation, the `deal` function takes an immutable reference to an array of unsigned 8-bit integers (`u8`). It distributes the cards evenly between two vectors of `u8` and then recursively calls the `gametime` function to play the game. The winning player's hand is converted to a new array of `u8`, and ownership of the new array is returned.

## Privacy
For legal purposes, the code can only be shared upon request.
If you have any questions or inquiries regarding the project, please contact [dylan.ha@torontomu.ca](mailto:dylan.ha@torontomu.ca).

---
