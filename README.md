# Evaluation1-OSS

student_detail = {}

def add(stud_id , name, stud_class ,grades)
 if stud_id in student_detail :
        print("Student with ID {stud_id} already exists")
        return
    
    student_detail[stud_id] = {
        'name' :name,
       'class': stud_class,
        'grades' :grades
    }
    
    print("student {name} added")
    
    def update(stud_id, grades)
    
    if stud_id not in student_detail:
        print(f"student with ID {stud_id} not found")
        return
    
    student_detail[stud_id]['grades'] =new_grade
    print("grades for student ID {stud_id} updated")
    
    def average(stud_id):
          if stud_id not in student_detail:
        print(f"student with ID {stud_id} npt found")
        return 0
    
    grades= student_detail[stud_id]['grades']
    if not grade:
        print ("grades not found")
        return 0
        
        average = sum(grades) / len(grades)
        return average
    
    user_input = input("Enter name")
    
        
