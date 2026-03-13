# Searching-for-a-student-in-a-list-
Data structure practical program 
# Linear Search to find student by ID

students = [
    {"id": 101, "name": "Ravi"},
    {"id": 102, "name": "Anu"},
    {"id": 103, "name": "Kiran"}
]

key = int(input("Enter Student ID to search: "))
found = False

for student in students:
    if student["id"] == key:
        print(f"Student Found: ID={student['id']}, Name={student['name']}")
        found = True
        break

if not found:
    print("Student not found")

output:
Enter Student ID to search: 102
Student Found: ID=102, Name=Anu
