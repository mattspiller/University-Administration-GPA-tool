# Author: Matthew Spiller
# Date Modified: February 18, 2022

# University Administration GPA tool
# Description: Determines whether student will receive entrance scholarship, appear on dean's list, and/or receive an academic warning.

DEANS_LIST_THRESHOLD = 3.5
ENTRANCE_SCHOLARSHIP_THRESHOLD = 3.5

def is_student_on_deans_list(gpa):
    if (gpa >= DEANS_LIST_THRESHOLD):
        print("Student qualifies for Dean's List")


def does_student_receive_entrace_scholarship(gpa):
    if (gpa >= ENTRANCE_SCHOLARSHIP_THRESHOLD):
        print("Student qualifies for Entrance Scholarship Renewal")


def does_student_receive_academic_warning(gpa, threshold):
    if (gpa < threshold):
        print("Student to receive Academic Warning")


print("----------")

# another_student acts as a boolean in determining whether program should continue running
# this could have been done with a 'break' statement instead, but I'd prefer to use a loop ending condition.
another_student = ""
while another_student != "no":

    another_student = ""

    print("Please enter Student's GPA: ")
    gpa = float(input())

    print("Please enter Program Threshold: ")
    threshold = float(input())

    is_student_on_deans_list(gpa)
    does_student_receive_entrace_scholarship(gpa)
    does_student_receive_academic_warning(gpa, threshold)

    while another_student != "no" and another_student != "yes":
        print("Would you like to assess another student (yes, no): ")
        another_student = input()

        if another_student == "yes":
            print("----------")
        elif another_student != "no":
            print("Please answer with a 'yes' or 'no' response")
