# Pin Down the Score: The Impact of Scoring Systems on Skill Differentiation in Ten-Pin Bowling

## Abstract

This paper examines the skill and luck components in ten-pin bowling under two different scoring systems: traditional and World Bowling's current-frame scoring. Using computational models to simulate millions of potential games, we analyze score distributions and the frequency of achieving specific scores. We hypothesize that traditional scoring requires more skill due to the limited ways of achieving each score, whereas World Bowling's system introduces more variability and a potential increase in luck due to multiple scoring paths leading to similar results. Through statistical analysis and simulation, we aim to show that traditional scoring demands a higher level of skill, strategic thinking, and consistency, making it particularly suitable for professional play where distinguishing based on skill is crucial.


## Introduction

- Introduce ten-pin bowling and its significance.
- Describe traditional and World Bowling scoring systems.
- State the hypothesis and objectives of the paper.
  - Traditional scoring requires more skill due to complexity and strategic demands.
  - World Bowling scoring introduces more variability and luck.

## Literature Review

- Research on the impact of scoring systems in sports (e.g., bowling, golf, etc.).
- Studies on skill vs. luck in competitive sports.
- Previous works on ten-pin bowling scoring systems.
- Relevant statistical methodologies for analyzing game outcomes.

## Methods

### Data Sources

- **Balmoral Software Table Data**: Utilized to compare all possible game outcomes for traditional and World Bowling scoring systems.
- **Professional Bowlers Association (PBA) Data**: Strike and spare percentages for professional bowlers.
- **Simulation Data**: Generated using Python code to simulate 10-frame games based on strike and spare percentages.

### Simulation Approach

- **Traditional Scoring Simulation**:
  - Simulate frames with strike, spare, and open probabilities.
  - Calculate cumulative scores considering the dependency on subsequent rolls.
- **World Bowling Scoring Simulation**:
  - Simulate frames with independent scoring for each frame.
  - Calculate scores based on individual frame outcomes.

### Statistical Analysis

- **Descriptive Statistics**: Mean, median, mode, variance, standard deviation, skewness, and kurtosis for score distributions.
- **Probability Distributions**: Calculate the probability of achieving specific scores.
- **Kolmogorov-Smirnov Test**: Compare empirical distribution functions of the two scoring systems.
- **Levene’s Test**: Assess equality of variances between the two scoring systems.

## Results

### Score Distribution Analysis

- **Traditional Scoring**:
  - Higher variance and skewness towards higher scores.
  - Distribution showing fewer ways to achieve each score.
- **World Bowling Scoring**:
  - Lower variance, more uniform distribution.
  - More ways to achieve higher scores.

### Skill and Strategy

- **Traditional Scoring**:
  - Rewards strategic planning and consistency.
  - Greater impact of strikes and spares on subsequent frames.
- **World Bowling Scoring**:
  - Simplified frame-by-frame scoring.
  - Reduced impact of strategic frame buildup.

## Discussion

- Comparison of how each system influences the importance of skill and luck.
- Analysis of the strategic depth required in traditional scoring.
- Implications for professional and recreational play.

## Conclusion

- Traditional scoring requires more skill due to its complexity and the cumulative effect of frames.
- World Bowling scoring introduces more variability and potentially more luck.
- Traditional scoring is more suitable for professional play, where skill differentiation is crucial.

Our analysis supports the hypothesis that traditional scoring in ten-pin bowling requires more skill than World Bowling's current-frame scoring system. Traditional scoring's complexity and cumulative effects of strikes and spares demand higher strategic planning and consistency from players. In contrast, World Bowling scoring introduces more variability and potentially more luck, making it more accessible for casual players but less effective in distinguishing skill levels in professional play. This study underscores the importance of considering scoring systems' impacts on the sport's dynamics and player performance.



## Future Work

- Real-world performance analysis of players under both scoring systems.
- Psychological impacts of scoring systems on player performance and enjoyment.

