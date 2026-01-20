# projects-
# Program to calculate average marks of a student

marks = list(map(int, input("Enter marks separated by space: ").split()))

total = sum(marks)
average = total / len(marks)

print("Total Marks:", total)
print("Average Marks:", average)
