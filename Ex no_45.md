# EX 45 C program that implements a queue using an array, and performs insertion (enqueue) and display operations.
## DATE:
## AIM:
To write a C program that implements a queue using an array, and performs insertion (enqueue) and display operations. 

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a functions to perform enqueue and,display elements in Queue using array. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End 

## Program:
```
/*
C program that implements a queue using an array, and performs insertion (enqueue) and display operations.
Developed by:santhiya c 
RegisterNumber:212223060247  
*/
char queue[50]; 
int size=10,front,rear,i; 
void enqueue(char data) 
{ 
if(rear<size) 
{ 
if(front==-1) 
{ 
front=0; 
} 
rear=rear+1; 
queue[rear]=data; 
} 
{ 
printf("%c\n",queue[i]); 
} 
} 
void dequeue()
void dequeue() 
{  
if(front==-1||front>rear) 
{ 
printf("Queue Underflow\n"); 
} 
else 
{ 
front=front+1; 
} 
 
} 
void display() 
{ 
for(i=front;i<=rear;i++) 
printf(“%c “,queue[i]); 
} 
```

## Output:

![image](https://github.com/user-attachments/assets/ac8358b4-0e03-451a-81c8-d1c4b2c0392b)



## Result:
Thus the program was executed and the output was verified successfully.
