# ML-deep-learning
deep laerning project abt grades of the student
Objective: The objective of this practical assignment is to create a deep learning model using TensorFlow
to perform classification on a tabular dataset. By the end of this assignment, students should have a
better understanding of how to design, train, and evaluate neural networks for tabular data using
TensorFlow.
Dataset: The dataset consists of 480 student records and 17 features. The features are classified into
three major categories: (1) Demographic features such as gender and nationality. (2) Academic
background features such as educational stage, grade Level and section. (3) Behavioral features such as
raised hand on class, opening resources, answering survey by parents, and school satisfaction.
Attributes
• Gender - student's gender ( 'Male' or 'Female’)
• Nationality- student's nationality (’ Kuwait’,’ Lebanon’,’ Egypt’,’ SaudiArabia’,’ USA’,’ Jordan’,’
• Venezuela’,’ Iran’,’ Tunis’,’ Morocco’,’ Syria’,’ Palestine’,’ Iraq’,’ Lybia’)
• Place of birth- student's Place of birth (’ Kuwait’,’ Lebanon’,’ Egypt’,’ SaudiArabia’,’ USA’,’ Jordan’,’
Venezuela’,’ Iran’,’ Tunis’,’ Morocco’,’ Syria’,’ Palestine’,’ Iraq’,’ Lybia’)
• StageID- educational level student belongs (‘ lowerlevel’,’MiddleSchool’,’HighSchool’)
• Grade ID ( ‘G-01’, ‘G-02’, ‘G-03’, ‘G-04’, ‘G-05’, ‘G-06’, ‘G-07’, ‘G-08’, ‘G-09’, ‘G-10’, ‘G-11’, ‘G-12 ‘)
• Section ID- classroom student belongs (’A’,’B’,’C’)
• Topic- course topic (’ English’,’ Spanish’, ‘French’,’ Arabic’,’ IT’,’ Math’,’ Chemistry’, ‘Biology’,
‘Science’,’ History’,’ Quran’,’ Geology’)
• Semester- school year semester (’ First’,’ Second’)
• Parent responsible for student (’mom’,’father’)
• Raised hand- how many times the student raises his/her hand on classroom (0-100)
• Visited resources- how many times the student visits a course content(0-100)
• Viewing announcements-how many times the student checks the new announcements(0-100)
• Discussion groups- how many times the student participate on discussion groups (0-100)
• Parent Answering Survey- parent answered the surveys which are provided from school or not
(’Yes’,’No’)
• Parent School Satisfaction- the Degree of parent satisfaction from school(’Yes’,’No’)
• Student Absence Days-the number of absence days for each student ( above-7, under-7)
• The students are classified into three numerical intervals based on their total grade/mark:
o Low-Level: interval includes values from 0 to 69,
o Middle-Level: interval includes values from 70 to 89,
o High-Level: interval includes values from 90-100
