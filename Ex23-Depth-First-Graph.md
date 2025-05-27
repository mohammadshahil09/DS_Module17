# Ex23 Depth First Graph
## DATE:22.4.25
## AIM:
To compose the code for the function createNode to traverse the graph below in the depth first fashion.

![image](https://github.com/user-attachments/assets/63552824-d0a3-49c6-a473-6db27d1f03e4)

## Algorithm
1.Use malloc to allocate memory for a new node of type struct node.

2.Set the vertex field of the new node to the value v.

3.Set the next pointer of the new node to NULL.

4.Return the pointer to the newly created node.

5.Complete the function execution.

## Program:
```
/*
Program to traverse the graph below in the depth first fashion

struct node* createNode(int v) {
  struct node* newNode = malloc(sizeof(struct node));
  newNode->vertex = v;
  newNode->next = NULL;
  return newNode;

 
*/
```

## Output:

![image](https://github.com/user-attachments/assets/f55022d8-d2b6-4e78-b68e-72a136432f78)


## Result:
Thus, the C code for the function createNode to traverse the graph below in the depth first fashion is implemented successfully
