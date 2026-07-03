# Day 27– Friday, 03 July 2026

## Topics Learned: Insertion Sort & Merge Sort

### Insertion Sort
- Works like sorting playing cards in your hand.
- Builds the sorted array one element at a time.
- Each new element is compared with already sorted elements and placed in the correct position.
- **Time Complexity:**
  - Best Case: O(n) (already sorted)
  - Worst Case: O(n²) (reverse order)
- **Space Complexity:** O(1) (in-place sorting)

**Example:**
Array = [5, 3, 4, 1]  
Step 1: [3, 5, 4, 1]  
Step 2: [3, 4, 5, 1]  
Step 3: [1, 3, 4, 5]

###  Merge Sort
- A **divide and conquer** algorithm.
- Splits the array into halves until single elements remain, then merges them back in sorted order.
- Very efficient for large datasets.
- **Time Complexity:**
  - Best, Average, Worst Case: O(n log n)
- **Space Complexity:** O(n) (extra space for merging)

**Example:**
Array = [5, 3, 4, 1]  
Split → [5, 3] & [4, 1]  
Sort → [3, 5] & [1, 4]  
Merge → [1, 3, 4, 5]

##  Progress Notes
- Learned two important sorting algorithms today.
- Insertion Sort is simple and good for small datasets.
- Merge Sort is powerful for larger datasets due to its efficiency.
- Practiced examples manually to understand step-by-step execution.

