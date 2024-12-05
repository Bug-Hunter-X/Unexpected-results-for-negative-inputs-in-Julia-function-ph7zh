# Julia Function Bug
This repository contains a Julia function that produces unexpected results for negative inputs. The issue lies in the way negative numbers are handled within the conditional statements. The solution demonstrates the correct approach to handle negative numbers, ensuring accurate results.

## Bug Description
The `myfunction` function is designed to square the input if it's positive, return 0 if it's 0, and return the negative of the square if the input is negative. However, the current implementation incorrectly calculates the result for negative numbers.

## Bug Solution
The solution addresses the problem by explicitly handling negative numbers correctly, thereby resolving the issue and generating the expected outputs.