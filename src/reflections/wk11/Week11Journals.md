**What does Inheritance accomplish for us in C#?**

Inheritance helps us by coorisponding two classes. If we have a default inhearatable class, we know every class which inhearites this unique class has its properties and may not have to re-assign them. 

**How does Member inheritance work in C#? Does a class inherit all members of the base class?**

aclass does not inherit all members in members are classified private. 

**How does accessibility affect inheritance?**

if something in private in an inherited class, said class inheriting it cannot access the private members. Make it internal if you want to access it within the application, but leave it unaccessable to users.

**Mondays Link:** https://github.com/KranberryKin/Vaca

**What is the difference between a primary key and a foreign key**

Primary Key is an ID used within the object, and the Foreign Key is the corrisponding ID, but on an object from a different table of data to refrence it. 

**What is an Alias?**

Alias is like a naming convention for a banana word. But it stores data in a loction of memory.

**Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:**

Two tables have the same name for many to many relatinship, which would confuse mysql. but if the many to many table was doctors-patients we can make it work. if a doctorID is given....
SELECT p.*, dp.* FROM doctors-patients dp JOIN patients p ON p.id = dp.patientId WHERE dp.doctorId = @doctorId;

**Tuesdays Link:**https://github.com/KranberryKin/AmaZeny

**What is SQL injection?**

Where the user can input a value which the sql database can read instead of being the needed data, and changes the database in a form of an attack.

**What are 3 methods SQL injection can be done by?**



**How can we detect and sanitize SQL injection attacks?**

There are different forms of tests you can run checking for specific characters like a ';'. Or you can find the data and change it manually with only the properties you want the user to edit.

**Wednesday Link:** https://github.com/KranberryKin/AmaZeny

**Write a review and reflection of your experiences in this course, as this is the last lecture before your final project, what are your concerns, how do you plan to manage your time, what have you enjoyed most about the course up to this point.**

It has been fairly stressful and enjoyable experiance. Never imagined being able to wittness and experiance a place where we learn new stuff everyday. And use the information and skills we learned perviously through practice, While attempting the new information. Learning from both ends was enjoyable symutainiously. I don't have any concerns other than that I have allot of work that needs to be done. I been making myself a todo list of all the tasks i want myself to do, with the mindset of small steps of done. 
