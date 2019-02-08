# First-year-students
Program, that operates with list of first-year students, professors and so on. 

Features of the program:

1. Program has 4 classes: Humans, Students, Professors and Group.

2. Class Humans creates objects like human with properties name and age.

3. Class Students inherits some properties of Humans. In addition, every object of this class has properties performance and presence.
   Performance determines the level of student training from 1 to 10. Presence determines the attendance of student from 1 to 10.
   1 - the worst, 10 - the best one.

4. Class Professors inherits some properties of Humans. Further, Professors has propertie subject and they can interact with students to check who absent anf who present today.

5. Class Group creates an object like group of students with some number. Within this class students of this group have ability to choose monitor. Monitor - is the student, that has maximum performance. If several students has the same maximum performance, then a student with a greater age will be selected. If the several students has the same maximum performance and age, then a student with a greater presence will be selected 

6. Block of arrays and variables. Provides the data area for creation of students, professors anf groups. Has the data about names, ages, subjects, numbers of groups.

7.  Block that creates needed objects with help of classes. Within this block appears the students, that joined together in one group. As default, the number of students in group is equal to 20. This number can vary as needed. In this block appears the group of students and professor.

8. Block of information output to console. It output the information about group number, about the monitor of group, about professors name and subject, about how many students absent and present, about who of students absent and present.
