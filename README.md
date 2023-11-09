A game without players
"Life" develops strictly according to prescribed rules. It does not require any action on the part of the player - except that it cannot start itself.
Game description
The game is played on a two-dimensional grid. The cells in this grid are either dead or alive. According to the rules, on each turn the cells come to life, die or do not change their status in any way.
Rules of the game
Each step, the game checks where the cells are on the field:
a live cell with two or three neighbors continues to live
a dead cell with three neighbors comes back to life
a live cell dies and a dead cell remains dead if they have more than three or less than two neighbors.
Despite the simple rules, new, different cell states regularly appear in the game.
Some of them remain stable and do not change in any way. These patterns are called "still lifes". The easiest way to recognize a "still life" is in a two-by-two square. If it appeared from the beginning of the game or appeared in the process of evolution, it will exist the whole further game without changes.
There have been so many variations of the figures that they are now categorized. Here are some of them:
stable (like a square)
moving
periodic (they repeat their state from time to time)
guns (occasionally "shoot" gliders)
steam locomotives (leave a trace in motion)
devourers (do not collide with other figures)
Each cell on each step of the game has some state, and the whole game is a transition from one state to another. It can be called a state-machine, i.e. a system of a set of states, events and transitions from the current state to a new one. In programming theory, a state-machine is translated as a finite automaton (or infinite, if the field is unbounded).
