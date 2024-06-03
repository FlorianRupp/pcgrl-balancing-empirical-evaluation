# It might be balanced, but is it actually good? An Empirical Evaluation of Game Level Balancing

This is the repository for supplementary files for the paper "It might be balanced, but is it actually good? An Empirical Evaluation of Game Level Balancing" accepted at the IEEE Conference on Games 2024 in Milan, Italy.

**Paper abstract:** Achieving optimal balance in games is essential to their success, yet reliant on extensive manual work and playtesting. To facilitate this process, the Procedural Content Generation via Reinforcement Learning (PCGRL) framework has recently been effectively used to improve the balance of existing game levels. 
This approach, however, only assesses balance heuristically, neglecting actual human perception.
For this reason, this work presents a survey to empirically evaluate the created content paired with human playtesting. Participants in four different scenarios are asked about their perception of changes made to the level both before and after balancing, and vice versa.
Based on descriptive and statistical analysis, our findings indicate that the PCGRL-based balancing positively influences players' perceived balance for most scenarios, albeit with differences in aspects of the balancing between scenarios.



The repository contains:
* The catalog of all survey questions.
* For each scenario:
  * The level (tile map) of both versions, the unbalanced and balanced each.
  * The cleaned survey data per item (question) regarding the unbalanced and balanced version respectively.
  * Violin plots of the data distributions per item of the unbalanced and balanced version.
