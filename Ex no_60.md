# EX 60 C function to find the peek element of the queue using linked list.
## DATE:
## AIM:
To write a C function to find the peek element of the queue using linked list.

## Algorithm
1. Start
2. Check if the queue is empty (front == NULL):
3. If empty, print "Queue is empty" and exit.
4. Otherwise, return the data of the front node.
5. End 

## Program:
```
struct Node
{
   int data;
   struct Node *next;
}*front=NULL,*rear=NULL;
void peek()
{
    printf("%c",front->data);
}
```

## Output:
![image](https://github.com/user-attachments/assets/9c6ba75e-7d77-4094-b672-ca562d3051f3)



## Result:
Thus the program was executed and the output was verified successfully.
