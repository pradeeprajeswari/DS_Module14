# Ex6 Dequeue Elements from Circular Queue
## DATE:03/03/2025
## AIM:
To write a C program to delete three elements from the filled circular queue.

## Algorithm

1. Start the program. 
2. Check if the queue is empty using the condition: `front == -1`.  
3. If the queue is empty, display "Queue Underflow".
4. If there is only one element (`front == rear`), set `front = -1` and `rear = -1`.  
5. Otherwise, set `front = (front + 1) % size`. 
6. Return the dequeued element from `queue[front]`.  
7. End.

## Program:
```/*
Program to delete three elements from the filled circular queue
Developed by: PRADEEP E
RegisterNumber:  212223230149
*/
```
```
int deQueue() {
  int element;
  if (isEmpty()) {
    printf("Queue is empty !! \n");
    return (-1);
  } else {
    element = items[front];
    if (front == rear) {
      front = -1;
      rear = -1;
    } 
    else {
      front = (front + 1) % SIZE;
    }
    return (element);
  }
}
```

## Output:
![image](https://github.com/user-attachments/assets/1e23e84d-671c-41a0-89d4-3eee4cd16bb3)

## Result:
Thus, the C program to delete three elements from the filled circular queue is implemented successfully.
