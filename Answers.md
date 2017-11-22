•	Try using a TreeMap and a HashMap instead of MyHashMap.
Are the resulting word frequencies any different?
Is the time performance any different? If so, how would you rank the three 
 implementations (in increasing order of time complexity)?
 
 Yes, HashMap is faster than TreeMap
 
•	How are % and Math.floorMod different? Which works more reliably for computing
a hash table index?
% doesn't round 
Math.floorMod rounds down, it maps a number to the nearest lowest integer
Math.floorMod works more reliably for computinga hash table

•	What is the time complexity of MyHashMap.size(), and how could you make it much
more efficient?
 It is O(n),  we could make size an instance variable and make sure that we increment 
 the value at the same time that we add items to the HashMap


•	How does this implementation compare to one where you would directly use your
linked Node class from the earlier assignment? Answer briefly in terms of ease of 
implementation, correctness, reliability, and performance.

They are both reliable, HashMap is faster in terms of performace, linked node is better 
in terms of ease of implementation and they are both correct.
