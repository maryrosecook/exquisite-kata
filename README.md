# Exquisite Kata

## Introduction

In this workshop, we'll practice some skills: refactoring, contributing to an unfamiliar codebase, and red green refactor.

### Exquisite corpse

Exquisite corpse is a party game.  One person makes up the first sentence of a story and writes it at the top of a piece of paper.  They fold the paper to cover their sentence.  They pass the paper to the person next to them.  That person writes their own sentence and folds the paper over.  This continues for a few more passes.  At the end, one person unfolds the paper and reads the whole story to the group.

### Code kata

The programmer takes some user stories and they spend around an hour implementing them.  The goal is for the programmer to practice their craft, maybe trying out new techniques or languages.

### Exquisite kata

* We'll break into pairs.

* Each pair will clone this repo.

* The pair will spend fifteen minutes implementing the user stories below.

* After fifteen minutes, each pair will pass their computer to another pair.

* Each pair will continue implementing user stories in the code on the computer they have been passed. (Unlike in exquisite corpse, the previous pair's code is visible and modifiable by the next pair.)

* We'll do four fifteen minute sessions.

* We'll have a short plenary at the end.

### Guidelines

* Be ruthlessly test first.

* Red, green, and then make sure you refactor.

* Please use Atom or Sublime Text so that the people who inherit your code aren't confounded by your wild Vim setup.

* Don't forget to swap driver and navigator.

## Setup

### Get the code

Clone the repo.

### Run the tests

    $ rspec

### Run the program

    $ ruby lib/tic_tac_toe.rb

## User Stories

```
As a person
So I can have fun
I want to play a game of tic tac toe with my friend on the command line
```

```
As a player
So I can play when it's my turn
I want the game ask me for my move when it's my turn
```

```
As a player
So I can play my move where I want
I want to choose which square to make my move in
```

```
As a player
So I can see the state of the game
I want the game to print out the board after each move
```

```
As a player
So I can know when I've won
I want the game to announce a winner as soon as the game has been decided
```
