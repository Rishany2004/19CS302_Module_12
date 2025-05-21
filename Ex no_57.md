# EX 57 C function to perfom push,pop and peek functions in Stack using Linked List.( store float data in stack)
## DATE:
## AIM:
To write a C function to perfom push,pop and peek functions in Stack using Linked List.

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
char data;  
struct Node *next;  
}*head,*t;
void push(char data)  
{  
    struct Node *n=(struct Node *)malloc(sizeof(struct Node));
    n->data=data;
    n->next=0;
    if(head==NULL)
    {
        head=n;
    }
    else
    {
        n->next=head;
        head=n;
    }
}  
void pop()  
{  
    if(head==NULL)
    {
        printf(" ");
    }
    else
    {
        head=head->next;
    }
}  
void display()  
{  
    if(head==NULL)
    {
        printf(" ");
    }
    else
    {
        printf("stack:");
        t=head;
        while(t!=0)
        {
            printf("%c ",t->data);
            t=t->next;
        }
        printf("\n");
    }
}  
void peek()
{
    printf("stack top:%c\n",head->data);
}
```

## Output:
![image](https://github.com/user-attachments/assets/1ac74cd6-f1d6-4a80-a8fe-66840d6f5a4e)

## Result:
Thus the program was executed and the output was verified successfully.
