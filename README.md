Heap sort algorithm is divided into two basic parts:

    Creating a Heap of the unsorted list/array.
    Then a sorted array is created by repeatedly removing the largest/smallest element from the heap, and inserting it into the array. The heap is reconstructed after each removal.

Initially on receiving an unsorted list, the first step in heap sort is to create a Heap data structure(Max-Heap or Min-Heap). Once heap is built, the first element of the Heap is either largest or smallest(depending upon Max-Heap or Min-Heap), so we put the first element of the heap in our array. Then we again make heap using the remaining elements, to again pick the first element of the heap and put it into the array. We keep on doing the same repeatedly untill we have the complete sorted list in our array.
Complexity Analysis of Heap Sort :

 1.Worst Case Time Complexity: O(n*log n)

2. Best Case Time Complexity: O(n*log n)

3. Average Time Complexity: O(n*log n)

 4.Space Complexity : O(1)

  a.  Heap sort is not a Stable sort, and requires a constant space for sorting a list.
   b. Heap Sort is very fast and is widely used for sorting.

