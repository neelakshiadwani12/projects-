# Projects

## Program to Calculate Average Marks of a Student

This is a simple Python program that calculates the total and average marks of a student.

## Code
```python
marks = list(map(int, input("Enter marks separated by space: ").split()))

total = sum(marks)
average = total / len(marks)

print("Total Marks:", total)
print("Average Marks:", average)
