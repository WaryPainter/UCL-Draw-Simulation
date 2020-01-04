# UCL-Draw-Simulation
Simulating UEFA Champion's League Draw Probabilities
(More specifically for the Round of 16 2019/20)

Due the design of UEFA's drawing procedure, the probabilities of the the Round of 16 (RO16) matchups cannot be easily calculated. This script simulates the drawing procedure to get a better estimate of the probabilities of each matchup.

The primary reason for doing this project was to improve my Python capabilities, primarily in coding simulations and as practice for the Pandas and NumPy libraries.

__Draw Quirks__
Fixed Rules:
1) Winners are drawn against runner-ups
2) Teams that were in the same group cannot be drawn to face each other
3) Teams from the same country cannot be drawn to face each other

Draw Procedure:
This specific procedure introduces some bias.
1) A runner-up is chosen
2) A list of all possible opponents left is created (based on valid draws remaining)
3) Opponent is drawn


![Heatmap](https://github.com/WaryPainter/UCL-Draw-Simulation/blob/master/heatmap.png)
