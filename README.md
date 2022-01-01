# Average_height_loop
student_heights = input("Input a list of student heights ").split()
for n in range(0, len(student_heights)):
  student_heights[n] = int(student_heights[n])

total_heights = 0
for height in student_heights:
    total_heights += height

student_number = 0
for number in student_heights:
    student_number += 1

average_height = round(total_heights/ student_number)
print(average_height)
