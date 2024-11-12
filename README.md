# Love-Calculator
#### 1. Modules to Install

This code uses built-in Python libraries, so you don't need to install any additional modules. It uses:

— `random`: For generating random numbers.
— `time`: For adding delays to the output.

#### 2. What Does the Code Do?

This code calculates a playful "love score" between two names based on various factors and then displays a message about the relationship based on this score.

#### 3. How the Code Works

1. Input:
   — The user is prompted to enter two names. These names are used as input for the love score calculation.

2. Counting Vowels and Consonants:
   — The code has functions to count vowels and consonants in each name. Vowels are the letters `a`, `e`, `i`, `o`, and `u`, while consonants are all other alphabetic characters except vowels.

3. Calculating the Love Score:
   — Several factors contribute to the love score:
     — Vowels: If both names have the same number of vowels, a random score is added to the love score.
     — Consonants: If both names have the same number of consonants, another random score is added.
     — First Letter: If the first letters of both names are the same, a random score is added.
     — Length: If both names are of the same length, a small random score is added.
     — A random score is added to ensure there is always some score.

4. Displaying Results:
   — The code simulates "calculating" by pausing for a short, random amount of time.
   — It then prints out a message showing the calculated love score as a percentage.
   — Based on the score, it categorizes the relationship into one of several types:
     — 90% and above: An unbreakable relationship.
     — 70% to 89%: A strong relationship, likely leading to marriage.
     — 50% to 69%: A good relationship, possibly leading to a honeymoon in Paris.
     — Below 50%: A weak relationship that might have been a good match.

This script is a fun program that calculates and displays a "love score" between two names. It uses factors such as the number of vowels and consonants, the first letters, and the lengths of the names to generate this score. The result is then used to categorize the relationship and provide a playful message about it.
