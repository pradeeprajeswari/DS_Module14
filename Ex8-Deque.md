# Ex8 Deque
## DATE:06/03/2025
## AIM:
To write a C function to count the number of elements present in the deque.

## Algorithm
1. Start 
2. Define a function count() that takes an array arr as input. 
3. Initialize a counter c to track the number of non-zero elements. 
4. Loop through the array from index 0 to MAX-1. 
5. For each element, check if it's non-zero. 
6. If the element is non-zero, increment the counter c. 
7. Return the final count of non-zero elements in the array. 
8. End 
## Program:
```
/*
Program to count the number of elements present in the deque
Developed by: PRADEEP E
RegisterNumber:  212223230149
*/
```
```
int count(int *arr) {
  int c = 0, i;
  for(i=0;i<MAX;i++){
      if(arr[i]!=0)
         c+=1;  }
  return c;
}
```

## Output:

![image](https://github.com/user-attachments/assets/8d492f7e-02f7-4288-833d-f8921db117f1)


## Result:
Thus, the C code to count the number of elements present in the deque is implemented successfully.
