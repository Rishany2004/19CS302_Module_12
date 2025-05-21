# EX 58 C Function to display queue elements using Linked List.(use integer data in the queue)
## DATE:
## AIM:
To write a C Function to display queue elements using Linked List.

## Algorithm
1. Start.
2. Define a variables.
3. Write a program to display stack elements using linked list.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End
   
## Program:
```
struct Node
{
   float data;
   struct Node *next;
}*front=NULL,*rear=NULL;
void display()
{
    struct Node *ptr;
    ptr=front;
    if(front==NULL)
    {
        printf("queue is empty");
        
    }
    else
    {printf("Queue elements:\n");
    while(ptr!=0)
    {
        printf("%.3f\n",ptr->data);
        ptr=ptr->next;
    }}
}
```

## Output:

![image](https://github.com/user-attachments/assets/da9024eb-00b6-4a76-94c3-73c4bb1f448a)

## Result:
Thus the program was executed and the output was verified successfully.
