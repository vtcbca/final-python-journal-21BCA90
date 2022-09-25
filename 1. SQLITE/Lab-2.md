Create the below three tables along with key constraints and Write an Insert script for insertion of rows with substitution variables and insert appropriate data.

**STUDENT (rollno, name, class, birthdate)**

**COURSE (courseno, coursename, max_marks, pass_marks)**

**SC (rollno, courseno, marks)**

Note: use ‘FY, SY, TY’ as class in STUDENT table.

1. Display details of student who takes ‘Database Management System’ course.
2. Display the names of students who have scored more than 70% in Computer
   Networks and have not failed in any subject.
3. Display the average marks obtained by each student.
4. Select all courses where passing marks are more than 30% of average maximum
   mark.
5. Display all course name.
6. Display the student details who have secure 1 st rank in ‘Computer Network’
   course.
7. Display all SY student list along with course name.
8. Display the average marks obtained by each student.
9. Write a trigger which does not allow deletion of student whose pass_mark is
   greater than 35.
10. Write a trigger which does not allow insertion / updating student whose max-
   marks more than 100 and less than 0.
