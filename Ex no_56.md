# EX 56 C function to display stack elements using Linked List.(store integer data in stack) .
## DATE:
## AIM:
To write a C function to display stack elements using Linked List.

## Algorithm
1.Define a structure Node with an integer data and a pointer to the next node. 
2.Create a function push() to insert an integer element into the stack (insert at the beginning of the list).
3.Create a function display() to traverse the stack and print the elements.
4.Create a function pop() to remove the top element from the stack (remove from the beginning). 
5.Use main() to manage the stack and perform operations like pushing, displaying, and popping.

## Program:
```
Struct Node 
{ 
float data; 
struct Node *next; 
}*head; 
void display() 
{ 
struct Node *temp= head; 
while(temp!=NULL) 
{ 
printf("%.2f\n",temp->data); 
temp=temp->next; 
} 
 
}
```

## Output:

![image](https://github.com/user-attachments/assets/4eb9a810-8d65-4bd2-84fe-3c3502ac0d25)


## Result:
Thus the program was executed and the output was verified successfully.
