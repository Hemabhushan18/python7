# python7
Total marks using Global Functions

total= 0
def add_subject_marks():
    global total
    marks= int(input("Enter marks of a subject: " ))
    total+=marks
    return marks
print("Subject1 marks :", add_subject_marks())
print("Subject2 marks :", add_subject_marks())
print("Subject3 marks :", add_subject_marks())
print("Total marks stored in global:", total)
