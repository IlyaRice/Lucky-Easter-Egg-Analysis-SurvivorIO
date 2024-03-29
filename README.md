# Lucky Easter Egg Analysis in Survivor.io

This repository explores the Lucky Easter Egg seasonal minigame within Survivor.io through a deep dive into statistical analysis and probability calculations. It aims to uncover the optimal strategy for players to maximize their rewards without falling prey to the dreaded bombs hidden in some eggs.

## Game Overview

In the Lucky Easter Egg minigame, players are presented with a field of 25 eggs, of which 22 contain gifts and 3 hide bombs. The game starts with several eggs already opened, and players can continue to open one egg after another to increase their rewards. However, uncovering a bomb resets the player's points for that round. The challenge lies in balancing the desire for higher rewards against the risk of losing everything.

<img src="https://github.com/IlyaRice/Lucky-Easter-Egg-Analysis-SurvivorIO/blob/master/Images/Game%20screenshot.jpg?raw=true" width="40%">

*Screenshot of the Lucky Easter Egg minigame in action.*

## Project Insights

The analysis pinpoints stopping at the 11th egg as the statistically optimal strategy, factoring in the initial number of eggs opened. Highlights from the project include:

- The impact of initial conditions on success probability.
- A detailed reward structure analysis, emphasizing the risk-reward trade-off.
- Simulation results providing realistic expectations for game outcomes.

## Key Visualizations

### Cumulative Chance of Not Encountering a Bomb

<img src="https://github.com/IlyaRice/Lucky-Easter-Egg-Analysis-SurvivorIO/blob/master/Images/01%20Cumulative%20Chances.png?raw=true" width="80%">

Illustrates the changing probability of safely opening eggs based on the initial number of eggs opened.

### Reward Structure Analysis

<img src="https://github.com/IlyaRice/Lucky-Easter-Egg-Analysis-SurvivorIO/blob/master/Images/02%20Prize%20at%20step%20bar.png?raw=true" width="80%">

Shows the incremental increase in rewards, highlighting the lure of higher stakes.

### Expected Value Analysis

<img src="https://github.com/IlyaRice/Lucky-Easter-Egg-Analysis-SurvivorIO/blob/master/Images/03%20EVs%20plot%20new.png?raw=true" width="80%">

Merges the chance of avoiding bombs with the increasing rewards to showcase the Expected Value (EV) for each step.

### Total Points Distribution Simulation

<img src="https://github.com/IlyaRice/Lucky-Easter-Egg-Analysis-SurvivorIO/blob/master/Images/04%20Points%20Distribution%20in%20simulation.png?raw=true" width="80%">

A detailed simulation showing the distribution of total points across multiple series, offering a comprehensive view of potential game outcomes.

## Conclusion

This project sheds light on the underlying mathematics of the Lucky Easter Egg minigame in Survivor.io, guiding players towards making informed decisions to maximize their rewards. It's an exemplary demonstration of how data analysis can be applied to game strategies, enhancing both understanding and performance.
