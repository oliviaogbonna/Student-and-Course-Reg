Entities
Student : REGULAR ENTITY
StudentID : [PK] ATTRIBUTE Type:NUMERIC Length=10 Width=
Name : ATTRIBUTE Type:CHAR Length=30
Course : REGULAR ENTITY
CourseID : [PK] ATTRIBUTE Type:NUMERIC Length=10 Width=
Descr : ATTRIBUTE Type:CHAR Length=30
Relationships
Student_Course : REGULAR RELATIONSHIP Student ONE OPTIONAL to Course MANY MANDATORY
Course_Student : REGULAR RELATIONSHIP Course ONE MANDATORY to Student MANY MANDATORY
