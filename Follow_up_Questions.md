These are some of the follow up questions you can ask the interviewer to get more information about the data used in the question

#### String
1. Does case sensitivity matter?
2. Do white spaces matter?

    ##### TIPS:
    1. You can double the string to check rotation
    2. 

#### Arrays
1. Is the input sorted?
2. Can it contain Negatives or Zero?
3. Are the elements distinct? If they are not how does the problem work?
4. Does spread start from multiple points at the same time? (Rotten oranges)

    ##### TIPS:
      1. Sorted + Distinct - Think Binary Search 
      2. Sorted + Not distinct - Then Modified Binary Search
      3. Use BFS/DFS by converting array into a graph - Every (i,j) has possible next steps
      4. Think about what/how extra memory can be used to design an O(n) algorithm

#### Linked Lists
1. How is it linked - Single, Double, Circular?
2. Are we given the length of the list 
3. 
    ##### TIPS:
    1. If no extra space is allowed - Think multiple pointers/ just think about it like an array O(n^k) solutions
    2. Measure the length of lists if O(n) + Rest of the O(solution) 
    3. Make Multiple lists if it is easy solution
        1. E.g Sort odd after even - Create a odd list and Even List and then just join
    4. Take Advantage of insert@head or insert@tail to achieve O(1) Insert time instead of O(n) insert.
    5. 
