# Merge Sort Implementation in C

This project provides a working C implementation of the Merge Sort algorithm. You can compile and run this code to see Merge Sort in action.

## What the project does

This C code sorts an array of integers using the Merge Sort algorithm.  It's a practical demonstration of how Merge Sort works.  When you run the code, it will:

1.  Initialize a predefined unsorted array of integers (e.g., `{4, 1, 3, 2, 5}`). You can easily modify this array in the `main` function to experiment with different input data.
2.  Perform the Merge Sort algorithm on the array.  This involves recursively dividing the array into smaller subarrays and then merging them back in sorted order.
3.  Print the sorted array to the console. You'll see the original unsorted array transformed into a sorted array (e.g., `{1, 2, 3, 4, 5}`).

The code is structured into two key functions:

*   `dividing(int start, int end, int arr[])`: This function handles the recursive division of the array. It splits the array into halves repeatedly until it reaches single-element subarrays.
*   `merging(int start, int mid, int end, int arr[])`: This function performs the merging of sorted subarrays. It takes two sorted subarrays and combines them into a single sorted subarray.

The `main` function sets up the initial array, calls the `dividing` function to start the sorting process, and then prints the final sorted array.

