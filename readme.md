# Go JSON Parser

A simple JSON parser written in Go. Still a work-in-progress.

## Origins

This project was created as part of the coursework for the ["Performance-Aware Programming" course](https://www.computerenhance.com/p/table-of-contents) I am taking. Some of the coursework artifacts are still in this project, like the Haversine compute scripts. It seemed useful to make the parser stuff into a separate module to gain experience with that while learning Go.

I am also learning Go, & this is the 1st project I am using it with, so there's bound to be mistakes!

## Usage

TODO

## Progress

- The lexer works, but is missing support for boolean & null types.
- The parser scaffolding is in place, but no real parsing of data is implemented yet. Currently working on this.
	- I think the parser design is going to be a recursive descent parser.
- There are unit tests for the lexer & parser, which will continue to be expanded.
