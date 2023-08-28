# Calculations for my graduate work
This paper performs the usual calculations and table manipulations using the pandas library. As a result of the study, we obtained an index model that aggregates diverse data from seven tables. This model has two metrics - growth and percentage growth by decades.

The index formula was devised to gain a comprehensive understanding of the structure by assembling the puzzle pieces (trade, foreign investment, sociology, migration). Inspiration was drawn from both combining the fractions with the concept of mathematical expectation.
1. Fractions were used to show the percentage of a country's trade, investment, etc. among multiple countries. This indicator allowed us to compare the growth of values over the years, for example:
    Country A's trade has held steady at one value (1->1) with country E; 
    Country B has doubled (1->2) its trade with country E;
    Country C increased trade (1->4) fourfold with Country E.
    At the beginning the share for each three country was 1/3, but comparing later to the total number: 
    A downgraded from (1/3 to 14%);
    B downgraded from (1/3 to 28%);
    C upgraded from (1/3 to 57%) 
    So even if countries A and B kept a good level, country C showed even more outstanding growth than A and B.
2. Mathematical expectation formula inspired me to multiply fractions (trade, investment) by certain weighting coefficients, after that they were summed into one value. But the most main focus is the percentage structure of outputed value, not just one number.

Dataset link: https://docs.google.com/spreadsheets/d/1eD4JKBmUovQHFA-oWWbfAxs4Ai4j5AS5/edit?usp=sharing&ouid=105518727383442622983&rtpof=true&sd=true
