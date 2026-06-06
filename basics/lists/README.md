marks = []

n = int(input("Enter number of students: "))

for i in range(n):
    marks.append(float(input("Enter marks: ")))

print("Average Marks:", sum(marks)/len(marks))
print("Highest Marks:", max(marks))
print("Lowest Marks:", min(marks))
