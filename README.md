Merge sort is a popular and efficient sorting algorithm that follows the divide-and-conquer approach. 
It divides the unsorted list repeatedly into smaller sublists until each sublist contains only one element. 
Then, it merges these sublists back together, sorting them in the process, until the entire list is sorted.
Here's a brief overview of the Merge Sort algorithm:
      1.Divide: The unsorted list is divided recursively into smaller sublists until each sublist contains only one element. 
      This is done until there are no more divisions possible
      2.Conquer: After the list is divided into its smallest parts, the merging process begins. 
      Pairs of sublists are merged back together into sorted sublists, combining elements in a sorted manner.
      3.Combine: Merging continues until there's only one sorted list remaining, which is the fully sorted list.
The key operation in merge sort is the merging step, where two sorted sublists are merged into a single sorted list. 
This process involves repeatedly comparing the elements from both sublists and arranging them in order.
Merge sort has a time complexity of O(n log n) in all cases (best, average, and worst-case scenarios). 
It's stable (maintains the relative order of equal elements) and doesn't require additional memory when merging (since it typically utilizes auxiliary arrays to merge).
