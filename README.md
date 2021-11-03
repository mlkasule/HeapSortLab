## Build Heap
1. Let index = length/2-1.  This is the parent of the last node in the tree, i.e. list[index + 1] . . . list[length-1] are leaves
2. Convert the subtree with root of list[index] into a heap.
a. Given list[a] is root of tree, list[b] is left child (root *2 +1), list[c] is right child (root*2+2), if exists
b. Compare list[b] with list[c] to determine larger child, list[largerIndex]
c. Compare list[a] with list[largerIndex].  If list[a] < list[largerIndex], then swap, else already a heap
d. If swap, repeat step 2 for the subtree of list[largerIndex]
3. Convert the subtree with the root of list[index-1] into a heap, repeat until list[0]
## Heap Sort
1.Swap the root with the end of the list.
2. Heapify the list up to but not including the root
3. Repeat until there is only one node in the list

Simulate the heapsort algorithm manually to sort the array:
Show all steps
Make into a heap
Sort

Solution in pdf
