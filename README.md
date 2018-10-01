# Text-Just

Text justification utilizes dynamic programming. As long as an array of words and a page width is given, the way to
nicely justify the text can be found. 

Implement a “split” method that, given as parameters the width ω and the array W, returns a list L of the indices of the array where each line should start to minimize the aggregated badness (i.e. the sum of the badness of all lines in such split).
