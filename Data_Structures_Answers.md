Add your answers to the questions below.

1. What is the runtime complexity of your ring buffer's `append` method? O(1)

2. What is the space complexity of your ring buffer's `append` function? O(1)

3. What is the runtime complexity of your ring buffer's `get` method? O(1)

4. What is the space complexity of your ring buffer's `get` method? O(1)

5) What is the runtime complexity of the provided code in `names.py`? O(n^2), we're nesting a loop in a loop and iterate through each item in both arrays to see if they match.

6) What is the space complexity of the provided code in `names.py`? O(n log n),we are creating two new arrays that is dependant on the sizes of the inputs and one duplicate array will be half the size of the combined sizes of the inputs given.

7) What is the runtime complexity of your optimized code in `names.py`? O(n), Making the dictionary used in this function involves looping over names_1, but as we're only setting up keys to variables the actions taken by the loop is constant. Next, we loop through names_2 and the actions taken in that loop have a constant runtime checking if something is in a dictionary is fast, making that sequence O (n) overall. O (n) + O (n) is just O (2n), which we can shorten to O (n).

8) What is the space complexity of your optimized code in `names.py`? O (n log n), as the duplicates array's size would be, at max, half the total amount of names provided.
