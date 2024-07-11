# simple-rescale
Code that rescales a set of detectors to original proportions (using simple constant offsets)

Function: Take detector confidences that do not aggregate to original category proportions
and rescale them (very simple constant addition scaling) to original category proportions

Use: a set of detectors developed with SMOTE or other rebalancing algorithms will no longer
match original proportions of categories, and will be scaled differently from each other.
This code provides offsets that can be added to confidences to make them comparable.

Instructions: Run each cell of this Jupyter Notebook one after the other

Input: A file with confidences for each data point for each category, 
and a file with original proportions for each category
Output: Rescaled confidences, final proportionsS

By Ryan S. Baker, 7/11/2024
MIT License
