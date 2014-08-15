% Game of Launchpad
% Lyndon Maydwell
% Sat, 16 August, 2014

## Game of Life

------------------

So there's this thing called the Game of Life

------------------

It was invented by a guy "Conway"

------------------

Which is why we call it "Conway's Game of Life"

------------------

## John Conway

A radical dude...

------------------

He had an idea:

Complex behavior could stem from simple rules

------------------

Game of life has only 3 rules that govern the evolution of a cell

    (defn next [alive? neighbours]
      (condp #(%1 %2) [alive? neighbours]
        #(=   [true 2] % ) true
        #(= 3 (second  %)) true
                           false))

------------------

But demonstrates

* Discrete Entities
* Evolution
* Defense
* Transmission of information

------------------

And more...

------------------

<https://www.youtube.com/watch?v=CgOcEZinQ2I>

## Launchpad

------------------

So there's this thing called the Novation Launchpad

------------------

Musicians use it to perform rapid sampling and controls

------------------

<https://www.youtube.com/watch?v=R3tVbrvc6UQ>

## Clojure

------------------

So in order to make the game of life more tactile I wrote
a small clojure program to simulate an interactive version
of the game on the launchpad.

------------------

And here it is!

------------------

<https://www.youtube.com/watch?v=Bdn9paOvXQk>

<https://github.com/sordina/launchpad>
