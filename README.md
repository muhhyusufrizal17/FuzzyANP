# Impulsive Buying Analysis using FANP & ANP (Decision Support System)
Fuzzy ANP-based decision support system to analyze impulsive buying behavior and identify key influencing factors. This project analyzes factors influencing and explores about phenomena using Fuzzy ANP approach and compares it with classical ANP to evaluate both decision accuracy and computational performance. Focuses on analyzing consumer behavior using a single dataset with multiple evaluation approaches to understand the impact of different factors in decision-making.


## Problem Statement
Impulsive buying behavior in fandom communities is influenced by multiple psychological and social factors. However, identifying the most dominant factors and evaluating decision-making methods remains a challenge.
## Data
The analysis is based on questionnaire data collected from 30 respondents in the pre-model stage and 100 respondents in the main model stage. The respondents were selected based on specific criteria relevant to the study, including being active or former fans of a particular franchise, having experience purchasing merchandise, and engaging within fandom communities. 
To support the analysis of age and environmental influence, the respondent group represents a range of fandom life stages, predominantly consisting of individuals aged 20–40 years. This ensures a more representative understanding of purchasing behavior across different levels of maturity and financial capability.
## Impact
This project demonstrates the practical value of decision support systems in analyzing complex consumer behavior.
First, it helps identify the most influential psychological and social factors behind impulsive buying, enabling a deeper understanding of what truly drives consumer decisions.
Second, by comparing FANP and ANP, the project shows how different methods affect the prioritization of factors, providing insight into selecting more appropriate decision-making approaches.
Finally, the inclusion of computational complexity analysis highlights the importance of efficiency and scalability, ensuring that the chosen method remains practical when applied to larger datasets.


### Key Findings
- FANP produces more distinct and interpretable factor weights compared to ANP
- Classical ANP shows fluctuating execution time as the number of nodes increases  
- Psychological factors dominate impulsive buying behavior  
- FANP demonstrates more stable and efficient in handling uncertainty without significantly increasing computational cost and performance as data size increases
- Fuzzy ANP not only improves decision accuracy by handling ambiguity, but also maintains stable computational performance, making it suitable for complex decision-making scenarios.

## Key Insights
The top factors influencing impulsive buying behavior are:
1. Emotional attraction when seeing merchandise or illustration has made to merchandise
2. Self-reward motivation  
3. Perceived product exclusivity  
These findings indicate that psychological triggers play a dominant role in consumer purchasing decisions.


## Refined Description (E1–E12)
- E1 – Attraction when encountering merchandise
- E2 – Sudden feelings of boredom or post-purchase regret
- E3 – Anxiety when unable to obtain desired merchandise
- E4 – Restlessness triggered by limited or exclusive items
- E5 – Purchasing merchandise as a form of self-reward
- E6 – Using self-reward as justification for unnecessary purchases
- E7 – Level of awareness and self-control before making a purchase
- E8 – Influence of age on purchasing mindset and behavior
- E9 – Exposure to influence from peers or community
- E10 – Impact of ongoing trends on purchasing decisions
- E11 – Purchasing merchandise as a way to support one’s idol
- E12 – Viewing “oshikatsu” as the ultimate expression of devotion to an idol

## Method
- Fuzzy Analytic Network Process (FANP)
- Fuzzy Geometric Mean (FGM) for preprocessing
- Triangular Fuzzy Numbers (TFN)
- Degree of Possibility
- Pairwise comparison and weighting
- Fuzzy Membership Trapezoidal
- Analytic Network Process (ANP)

## Tools
Python, NumPy, Pandas  

## 📊 Dashboard
![Dashboard](Visualization.png)

## 📊 Visualization Insights

The visualizations demonstrate that FANP effectively captures the dominance of emotional and psychological factors in impulsive buying behavior, with key drivers such as attraction to merchandise (E1), limited/exclusive perception (E4), and self-reward motivation (E5) emerging as the most influential. Compared to ANP, FANP produces more distinct and discriminative weights, enabling clearer prioritization of factors, while ANP tends to distribute weights more evenly. Additionally, the computational complexity analysis shows that FANP maintains relatively stable performance as data size increases, whereas ANP is more sensitive to changes in node size, indicating that FANP offers better scalability and efficiency for larger datasets.
