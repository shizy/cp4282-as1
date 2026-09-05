# Acknowledgement
AI was used in the course of completing the assignment, specifically to clarify my intuition on the implementation of the existing tile-based rendering logic. Specifically, I clarified on how the implementation transitions from a gaussian-based tile record data structure, where we have an unordered list of tile-splat pairs grouped by splats, to a tile-based data structure, where we have a front-to-back ordered buffer sorted by tile. 

From the clarification, I better understood the purpose of bit-packing into a tile-splat pair when it comes to the depth followed by radix sorts, and how the implementation was actually done.

AI was not used in the implementation of the assignment.