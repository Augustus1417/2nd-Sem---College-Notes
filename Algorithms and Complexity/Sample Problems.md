#### Binary Tree Traversal
##### 1.
```mermaid
graph TD;
    A[1] --> B[2]
    A[1] --> C[3]
    B[2] --> D[4]
    B[2] --> E[5]
    C[3] --> F[6]
    C[3] --> G[7]
    D[4] --> H[8]
    D[4] --> I[9]
    E[5] --> J[10]
    E[5] --> K[11]
    F[6] --> L[12]
    F[6] --> M[13]
    G[7] --> N[14]
    G[7] --> O[15]

```
**Pre-order Traversal (Root, Left, Right):**  
- *Answer*: 1, 2, 4, 8, 9, 5, 10, 11, 3, 6, 12, 13, 7, 14, 15
    
**In-order Traversal (Left, Root, Right):**  
- *Answer*: 8, 4, 9, 2, 10, 5, 11, 1, 12, 6, 13, 3, 14, 7, 15
    
**Post-order Traversal (Left, Right, Root):**  
- *Answer*: 8, 9, 4, 10, 11, 5, 2, 12, 13, 6, 14, 15, 7, 3, 1

##### 2.
```mermaid
graph TD;
    A[1] --> B[2]
    A[1] --> C[3]
    B[2] --> D[4]
    B[2] --> E[5]
    D[4] --> F[6]
    C[3] --> G[7]
    G[7] --> H[8]
    G[7] --> I[9]
```

**Pre-order Traversal (Root, Left, Right):**  
- *Answer*: 1, 2, 4, 6, 5, 3, 7, 8, 9
    
**In-order Traversal (Left, Root, Right):**  
- *Answer*: 6, 4, 2, 5, 1, 3, 8, 7, 9
    
**Post-order Traversal (Left, Right, Root):**  
- *Answer*: 6, 4, 5, 2, 8, 9, 7, 3, 1

##### 3.
```mermaid
graph TD;
    A[1] --> B[2]
    A[1] --> C[3]
    B[2] --> D[4]
    C[3] --> E[5]
    C[3] --> F[6]
    E[5] --> G[7]
```

**Pre-order Traversal (Root, Left, Right):**  
- *Answer*: 1, 2, 4, 3, 5, 7, 6
    
**In-order Traversal (Left, Root, Right):**  
- *Answer*: 4, 2, 1, 7, 5, 3, 6
    
**Post-order Traversal (Left, Right, Root):**  
- *Answer*: 4, 2, 7, 5, 6, 3, 1

--- 
#### Frequency Count
##### 1.
```python
x = 1 # --> 1
while (x <= n): # n - x + 2 = n - 1 + 2 = n + 1 (substitute x)
	x = x + 1   # n - x + 1 = n - 1 + 1 = n
				# total = 2n + 2
```
