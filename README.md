# R Data Frame Subsetting Bug

This repository demonstrates an uncommon error in R related to data frame subsetting using logical conditions. The bug arises from an incorrectly constructed logical expression that leads to unexpected behavior.  The solution explains how to correctly write the logical condition to achieve the desired subsetting.

## Bug Description
The code attempts to subset a data frame based on a condition.  However, due to a mistake in the condition, the subsetting produces an unexpected result—an empty data frame in this example.  The problem highlights how subtle errors in logical expressions can lead to difficult-to-debug problems, particularly in larger datasets.

## Solution
The solution corrects the logical condition to accurately identify and subset the appropriate rows of the data frame.