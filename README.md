# Blocked - Slide, Knock, Exit

[![blocked Banner](https://user-images.githubusercontent.com/8487294/158229495-cfc9b831-e0e2-421a-ae19-1266204788c6.png)](https://www.youtube.com/watch?v=on9iqcS6-x4)

An innovative spin on the classic sliding puzzle game. Sliding puzzle games usually feature free-moving blocks that have to be slid to achieve a set position or to let a block free (Rush Hour). Any block may be moved, as long as there is space ahead of it.

Play it on the web [here](https://blocked.jeffsieu.com)!

## Core game mechanic - Control

Blocked introduces a new concept: control.

![image](https://user-images.githubusercontent.com/8487294/158158649-224bb5dc-fd0c-469e-be6a-fa91971b6ad1.png)

At any point in the game, only the controlled block may be moved. Control may be transferred to another block by sliding into it. However, control may only be transferred if the currently controlled block impacts exactly one other block.

Having a single controllable block at a time, combined with the control-transfer mechanic, introduces several interesting mechanisms that are explored in the several levels in the game. Blocks have to be coordinated in order to prevent deadlock later in the game. Walls also add a new dimension to the game by implicitly introducing single-axis movement and one-way mechanisms.

## Level editor

![Level editor](https://user-images.githubusercontent.com/8487294/158159303-53808f51-b956-4370-8264-4ea64c2ca374.png)

The game also features an in-built level editor that allows for convenient level prototyping and sharing.

## Sharing levels

User-created levels can be shared via a button that is on the generated level page. This copies a shareable URL into the user's clipboard.

Example link:
[https://blocked.jeffsieu.com/#/editor/generated/eAHT0oKC1FQurQoQ0KvQiwCy9cCgQk9PC8SuQGZD5KDiIB1wNVp6WNRDAZCdm5sLEq%2BoALIRAACupRzb](https://blocked.jeffsieu.com/#/editor/generated/eAHT0oKC1FQurQoQ0KvQiwCy9cCgQk9PC8SuQGZD5KDiIB1wNVp6WNRDAZCdm5sLEq%2BoALIRAACupRzb)

## Generating solutions

Solutions can be generated then autoplayed. The generator uses the A\* algorithm to search for the optimal solution.

![image](https://user-images.githubusercontent.com/8487294/158224455-fd787d04-35c8-4573-80eb-0a07aac54239.png)

## Issues

Please report any issues [here](https://github.com/jeffsieu/blocked/issues/new).
