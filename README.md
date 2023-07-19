# CodeWars
Welcome to the coding competition! This is a 2-player game where each team will code their own strategy to deploy robots, gather resources, and attack the opponent's base. The game is played on a 40x40 grid, and the objective is to outmaneuver and outwit the other team to secure victory.

## The Objective
The objective of the game is to eliminate the opponent's Elixir supply or have a higher average Elixir count than the opponent after 1500 timeframes.

## Key Commodities
**Elixir**: Each team's base starts with an initial supply of Elixir, which is used to create robots. Robots can collect Elixir from the grid, and their individual Elixir counts are independent.

**Virus**: The grid contains both Elixir and Virus. Teams can deploy Virus on enemy robots or bases, reducing their Elixir in a 1:1 ratio. Virus can be collected and stored at the base.

## Game Rules

*The grid consists of Elixir and Virus at random locations. Elixir supply is not renewed, but Virus will be renewed after a specified number of turns.

*Robots are deployed from the bases and follow the pre-coded scripts submitted by the teams. Robots can collect both Elixir and Virus while wandering the grid.

*Each team can deploy Virus on enemy robots or bases, which will reduce the target's Elixir count.

*The game ends if any team's Elixir supply reaches zero, in which case the opposing team wins!

*If 1500 timeframes pass, the winner will be determined based on the moving average of each team's Elixir count.
