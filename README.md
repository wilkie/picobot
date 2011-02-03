# Picobot

## What is it?

Picobot was originally designed by the introduction to computer science course designers of Harvey Mudd College. This is a reimaging of their design with more modern techniques and a simpler syntax. It will use the canvas tag although also revert to pure javascript/dom if necessary. Currently, since pure javascript is seen as more constrictive, I am working on that version.

## How does it work?

Picobot is a robot that can move in any cardinal direction. It chooses where to move based upon rules written by the player. These rules are organized by a grouping that is designated by a value that represents picobot's state. In fact, this state is the only memory picobot has. The idea of the puzzle is to write rules that are sufficient for covering all tiles by navigating around walls regardless of where picobot starts.

## What does it teach?

Picobot teaches the concept of computation early without the need for a sophisticated language. The current picobot is not turing complete, but is sufficiently complicated as to present a computational challenge to any student regardless of previous experience. 

Since picobot is described by a set of rules, it is easy to show complexity as a factor of the number of rules. For instance, although several solutions are equally correct, some are more efficient since they involve less rules (space complexity), or solve the puzzle with picobot doing less repetitive work (time complexity).
