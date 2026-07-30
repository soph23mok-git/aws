# Bending Spoons Test Prep
# 1. Multi-Step Probability Simulator (Markov Chains)
Used for: A state changes step-by-step based on probabilities
# Example Questions:
a) Board Games: A token starts at square 0 on a board. You flip a coin. Heads moves you forward 2 spaces, tails moves you backward 1 space. What is the chance you land exactly on square 10 within 6 flips?

b) Stoke/Value Drift: A stock price starts at £50. Every hour, it has a 70% chance to go up by £1 and a 30% chance to drop by £2. What is the probability that the stock hits £45 before it hits £55.

c) Inventory/Resource Lifespan: A machine has 3 battery charges. Each day of operation, there is a 20% chance it uses 2 charges, a 50% chance it uses 1 charge, and a 30% chance it uses 0 charges. What is the probability it runs out of battery on exactly day 3?

# 2. The Conditional/Dependent Probability Filter
Used for: Given that X happened, what is the probability of Y?
# Example Questions:
a) Colored Marbles: A bag contains 5 red, 4 blue, and 3 green marbles. You draw 3 marbles without replacement. Given that at least two of the drawn marbles are red, what is the probability that all three are red?

b) Medical/Test Screenings: In a population, 2% of people have a virus. A test is 95% accurate for positive cases and 90% accurate for negative cases. Given that a randomly selected person tested positive, what is the probability they actually have the virus?

c) Dice Conditions: You roll three standard 6-sided dice. Given that the sum of the dice is an even number, what is the probability that all three dice showing the same number?

# 3. Grid Movement Counter (Combinatorics w/ Blocks)
Used for: Finding paths on grids with forbidden zones 
# Example Questions: 
a) City Grid Navigation: A delivery driver must travel from the northwest corner of an 8x8 city block grid to the southeast corner, moving only east or south. How many unique routes exist if 3 specific intersections are closed due to roadwork?

b) Board Game Obstacles: A chess piece starts at the top-left square (0,0) of a modified 5x5 board and can only move one square down or one square right at a time. How many ways can it reach the bottom-right corner if it must pass through square (2,2)? (Calculated by finding paths to (2,2) multiplied by paths from (2,2) to the end).

c) Monetary Step Ladders: An employee receives promotions moving through a corporate matrix of roles (rows represent departments, columns represent seniority ranks). If they can only transition to the right or down, how many career paths exist if one department is completely banned?
