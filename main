if __name__ == '__main__':
    records = []
    marks_range = set()
    
    for _ in range(int(input())):
        students_score = []
        name = input()
        students_score.append(name)
        score = float(input())
        students_score.append(score)
        marks_range.add(score)
        records.append(students_score)
        
marks_range = sorted(set(marks_range))

second_lowest_grade_students = []

for i in records:
    if i[1] == marks_range[1]:
        second_lowest_grade_students.append(i[0])
        
second_lowest_grade_students = sorted(second_lowest_grade_students)
        
print(*second_lowest_grade_students, sep='\n')
