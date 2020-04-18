#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The time complexity is O(n) because the loop will run a linear number of times in relation to the input.


b) The time complexity is O(n log n) because there is a loop nested inside of another loop. J is being squared.


c) The time complexity is O(n) because the recursive function will run a linear number of times in relation to the input.

## Exercise II

- n-story building
- plenty of eggs
- egg cracks if thrown from floor f or higher
- egg does not crack if thrown from floor lower than f
- find f where the number of broken eggs is minimized
- binary search, drop egg from middle floor, search either half based on whether it breaks or not
- keep searching until the egg lives
- time complexity of O(log n) since we are splitting up the input on each pass