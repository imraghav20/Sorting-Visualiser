This is a webpage which will enable us to see working of sorting algorithms visually.
 Included sorts are:
 1. Merge Sort - Merge Sort is a Divide and Conquer algorithm. It divides input array in two halves, calls itself for the two halves and then merges the two sorted halves. The merge() function is used for merging two halves. The merge(arr, l, m, r) is key process that assumes that arr[l..m] and arr[m+1..r] are sorted and merges the two sorted sub-arrays into one
 2. Quick Sort- QuickSort is a Divide and Conquer algorithm. It picks an element as pivot and partitions the given array around the picked pivot. There are many different versions of quickSort that pick pivot in different ways.
                ->Always pick first element as pivot.
                ->Always pick last element as pivot (implemented below)
                ->Pick a random element as pivot.
                ->Pick median as pivot.
                The key process in quickSort is partition(). Target of partitions is, given an array and an element x of array as pivot, put x at its correct position in sorted array and put all smaller elements (smaller than x) before x, and put all greater elements (greater than x) after x. All this should be done in linear time.
 3. Bubble Sort- Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping the adjacent elements if they are in wrong order.
 4. Heap Sort - Heap sort is a comparison based sorting technique based on Binary Heap data structure. It is similar to selection sort where we first find the maximum element and place the maximum element at the end. We repeat the same process for the remaining elements.
             Heap Sort Algorithm for sorting in increasing order:
              1. Build a max heap from the input data.
              2. At this point, the largest item is stored at the root of the heap. Replace it with the last item of the heap followed by reducing the size of heap by 1. Finally, heapify the root of the tree.
              3. Repeat step 2 while size of heap is greater than 1.
Use slider to cange size of array.
