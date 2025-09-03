
Algorithm	How It Works (Simple Analogy)	Time Complexity	Stable?

1.Bubble Sort	Repeatedly swap adjacent elements if they’re out of order—like bubbling the largest item to the top	T.C. : O(n²),	
Stable : ✅ Yes

2.Selection Sort	Pick the smallest item and place it at the beginning—like selecting the best player for a team. 
T.C. : 	O(n²)	,
Stable : ❌ No

3.Insertion Sort	Insert each item into its correct position—like sorting playing cards in your hand.
T.C. :	O(n²)	
Stable : ✅ Yes

4.Merge Sort	Divide the array, sort each half, then merge—like organizing two sorted piles of papers.
T.C. :	O(n log n) ,
Stable :	✅ Yes

5.Quick Sort	Pick a pivot, partition around it, then sort recursively—like dividing a group around a leader. 
T.C. :	O(n log n),	
Stable : ❌ No

6.Heap Sort	Use a heap structure to repeatedly extract the max/min—like building a pyramid and removing the top. 
T.C. :	O(n log n)	,
Stable : ❌ No

7.Counting Sort	Count occurrences and place items accordingly—great for small-range integers.
T.C :O(n + k),
Stable :	✅ Yes

8.Radix Sort	Sort digit by digit (like sorting phone numbers).
T.C. :	O(nk),
Stable :	✅ Yes
