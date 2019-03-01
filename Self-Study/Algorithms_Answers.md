Add your answers to the Algorithms exercises here.

### Exercise I

a) This would be considered O(c) because it is multiplying and not exponentially increasing as the value gets larger.

b) O(n**3) Because the first three loops are iterating with `n` but the last one is only iterating with k

c) O(c) although it is recursively calling itself, the only time bunnies has any changes to it is in the return statement, but while recursion it is only used as comparison

### Exercise II

Since we know buildings are in numerical order, we can use binary sorting algorithms like quicksort or merge sort. But in this case since the height of the building is unknown, Merge sort would be best in this ideal situation.

First thing we'll have to do is go to the middle of the _n_story building, drop an egg, if it breaks, then we go with the lower half, if it doesn't break then we go to the upper half and repeat the process until we only have two floors left to determine the final floor.