Download Link: https://assignmentchef.com/product/solved-ch231a-assignment6-bubble-sort-stable-and-adaptive-sorting
<br>
<h1></h1>

<ul>

 <li><em>Bubble Sort </em>is a sorting algorithm that works by repeatedly iterating through the list to be sorted, comparing each pair of adjacent items, and swapping them if they are in the wrong order. This is repeated until no swaps are needed, which indicates that the list is sorted. Write down the <em>Bubble Sort </em>algorithm in pseudocode including comments to explain the steps and/or actions.

  <ul>

   <li> Determine and prove the asymptotic worst-case, average-case, and best-case time complexity of <em>Bubble Sort</em>.</li>

   <li> Stable sorting algorithms maintain the relative order of records with equal keys (i.e., values). Thus, a sorting algorithm is <strong>stable </strong>if whenever there are two records <em>R </em>and <em>S </em>with the same key and with <em>R </em>appearing before <em>S </em>in the original list, <em>R </em>will appear before <em>S </em>in the sorted list. Which of the sorting algorithms <em>Insertion Sort</em>, <em>Merge Sort</em>, <em>Heap Sort</em>, and <em>Bubble Sort </em>are stable? Explain your answers.</li>

  </ul>

  <ul>

   <li>( A sorting algorithm is <strong>adaptive</strong>, if it takes advantage of existing order in its input. Thus, it benefits from the pre-sortedness in the input sequence and sorts faster. Which of the sorting algorithms <em>Insertion Sort</em>, <em>Merge Sort</em>, <em>Heap Sort</em>, and <em>Bubble Sort </em>are adaptive? Explain your answers.</li>

  </ul></li>

</ul>

<h1>Problem 6.2 <em>Heap Sort                                                                                 </em></h1>

<ul>

 <li> Implement the <em>Heap Sort </em>algorithm as presented in the lecture.</li>

 <li>(Implement a variant of the <em>Heap Sort </em>that works as follows: In the first step it also builds a max-heap. In the second step, it also proceeds as the <em>Heap Sort </em>does, but instead of calling <em>MAX</em>–<em>HEAPIFY </em>, it always floats the new root all the way down to a leaf level. Then, it checks whether that was actually correct and if not fixes the max-heap by moving the element up again. This strategy makes sense when considering that the element that was swapped to become the new root is typically small and thus would float down to a leaf level in most cases. Hence, one would save the additional tests when floating down the element. And, the fixing step (moving the element upwards again) would be a rare case.</li>

 <li><strong>Bonus </strong> Compare the original <em>HeapSort </em>and its variant from subpoint (b) for input sequences of different lengths (including larger input sequences). What can you observe?</li>

</ul>