PRACTICAL-1

Summary :

The five sorting algorithms—Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort—are used to arrange data in ascending or descending order. Bubble Sort repeatedly compares adjacent elements and swaps them when they are in the wrong order. Selection Sort finds the smallest element and places it in the correct position. Insertion Sort builds the sorted list one element at a time. Merge Sort divides the data into smaller parts and then merges them in sorted order. Quick Sort selects a pivot element and divides the data around the pivot. Each algorithm has different time and space requirements, so the suitable algorithm depends on the size and nature of the input data.

Conclusion :

Sorting algorithms are used to arrange data in ascending or descending order, making searching and data processing more efficient. Bubble Sort, Selection Sort, and Insertion Sort are simple and suitable for small datasets, while Merge Sort and Quick Sort are more efficient for large datasets. Each algorithm has its own advantages, limitations, and time complexity. The choice of the best sorting algorithm depends on the size of the data, available memory, and application requirements.



PRACTICAL-2

Summary :

Linear Search and Binary Search are two common searching algorithms used to find a particular element in a list. Linear Search checks each element one by one from the beginning until the required element is found or the list ends. It is simple and can work on both sorted and unsorted data. Binary Search works by repeatedly dividing a sorted list into two halves and checking the middle element. It eliminates half of the remaining elements after each comparison, making it much faster for large datasets.

Conclusion:

Linear Search and Binary Search are two fundamental searching techniques used to locate an element in a collection. Linear Search is simple to implement and works on both sorted and unsorted data, but its performance decreases as the size of the dataset grows because it checks elements one by one. In contrast, Binary Search is much faster for large datasets, as it repeatedly divides the search space in half, but it requires the data to be sorted before searching. Therefore, Linear Search is suitable for small or unsorted datasets, while Binary Search is the preferred choice for large, sorted datasets due to its higher efficiency and lower search time. Together, these algorithms demonstrate the importance of selecting an appropriate searching technique based on the nature of the data and application requirements.


PRACTICAL- 3

Summary

Max-Heap Sort is a comparison-based sorting algorithm that uses a Max Heap data structure. In a Max Heap, the largest element is always present at the root. The algorithm first builds a Max Heap from the given elements and then repeatedly moves the largest element to the end of the array. After each movement, the heap is rearranged to maintain the Max Heap property. This process continues until all elements are sorted in ascending order.

Conclusion:

Heap Sort using a Max Heap is an efficient comparison-based sorting algorithm that sorts elements in ascending order by repeatedly extracting the largest element from the heap. It provides a consistent time complexity of O(n log n) in the best, average, and worst cases, making its performance reliable regardless of the input data. Heap Sort is an in-place algorithm with O(1) auxiliary space (excluding the recursion stack), making it memory-efficient. Although it is not a stable sorting algorithm, it is well suited for applications that require predictable performance and efficient sorting of large datasets.


PRACTICAL-4

Summary :

The factorial program was implemented using both iterative and recursive methods in Python. The user enters a number, and the program calculates its factorial using both approaches. The execution time of each method is measured using Python's time. perf_ counter() function. The iterative method uses a loop, while the recursive method repeatedly calls the same function until it reaches the base condition.

 Conclusion:

Both iterative and recursive methods successfully calculate the factorial of a given number. Both methods have O(n) time complexity, but their space requirements are different. The iterative method has O(1) space complexity, whereas the recursive method has O(n) space complexity because of the function call stack. Therefore, the iterative method is more memory-efficient, while the recursive method provides a simpler representation of the factorial logic.


PRACTICAL-7

Summary :

The making change problem was implemented using the Dynamic Programming technique. The program calculates the minimum number of coins required to make a given amount. Dynamic Programming stores previously calculated results in a table, which avoids repeatedly solving the same subproblems. The algorithm has O(n × A) time complexity and O(A) space complexity.

 Conclusion:

The Dynamic Programming approach provides an efficient solution to the making change problem by storing and reusing previously calculated results. It successfully finds the minimum number of coins required for the given amount. Compared with a simple recursive approach, Dynamic Programming reduces repeated calculations and provides better performance for larger amounts.
