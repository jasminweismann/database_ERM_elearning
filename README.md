# database_ERM_elearning

# eLearning

The data structure of a new e-learning system is to be implemented. 
Draw the following facts in an ER diagram in Chen notation and create a relational model. 
An e-course is clearly identified by a course number (LVANR). In addition, a designation (NAME) is stored, a maximum number of participants (MAXIMUM) and the amount of time (SIZE) required to complete the course. 

It is noted which e-courses are a prerequisite for which other e-courses. 

Learning modules have a name (NAME) and a unique identification number (ID). Courses are assigned several learning modules (at least one). Learning modules can be used for several courses. For each course the sequence (ORDER) of modules is noted. 
Each learning module contains several learning objects (e.g. pictures, texts, videos). Learning objects are uniquely identified by the module to which they are assigned and their name (NAME). The type (TYPE) is also stored for learning objects.
In some cases, an e-course may also be assigned a test module. A mode (MODE) of a test module is known and a unique name (DEFINITION) - a test module can be assigned to several e-courses. 
Persons are uniquely identified by a personal number (PNR). The name (NAME) is also stored. Persons can participate in any number of courses. An e-course, is moderated by at least one and at most two persons, whereby one person can moderate a maximum of four courses.
