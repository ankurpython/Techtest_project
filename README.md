# Testtest_Project
The purpose of this project to check the Django Experience of Programmer. 

## Teacher Directory
**A client has requested we create a Directory app containing all the Teachers in a given school.
Each teacher should have the following information**
* First Name
* Last Name
* Profile picture
* Email Address
* Phone Number
* Room Number
* Subjects taught
*  
**Teachers can have the same first name and last name but their email address should be unique
A teacher can teach no more than 5 subjects
The directory should allow Teachers to filtered by first letter of last name or by subject.
You should be able to click on a teach in the directory and open up the profile page. From there you
can see all details for the teacher.
An Importer will be needed to allow Teachers details to be added to the system in bulk. This should
be secure so only logged in users can run the importer.
The CSV attached contains a list of teacher who need to be uploaded as well as the filename for the
profile image. Profile images are in the attached Zip file.
if an image is not present for the profile then you should use a default placeholder image.
You can use SQLite for the database backend for simplicity**

## Steps to Run 
1. Download or Clone the Repository:    **https://github.com/ankurpython/Techtest_project**
2. Make sure to install requirements.txt file:   **https://github.com/ankurpython/Techtest_project/blob/master/teacherdirectory/requirements.txt**
3. After all the installation complete use the django command to runserver:   **py manage.py runserver**
4. Open the browser: **http://localhost:8000**
5. Click on sign up page to create the credential.
      > If you don't want to  create the credential, you can use admin credential
         1. **username == ankursaurabh**
         2. **password == ankur121**
6. You can import the CSV file by click on IMPORT.
7. Display all the data by click on the TEACHER.
8. 

*Deployed on server: **http://teacherdirectory.pythonanywhere.com/admin*
> **use the credential:**
  * username==ankursaurabh
  * password==ankur121


## Screenshots

1. **Base Page**


![base_page](https://user-images.githubusercontent.com/48859058/122656388-c3218780-d177-11eb-9041-5ab719ffaaa0.png)




2. **After login with Admin Panel: Click on Import to add new files in CSV Format.**



![click on import to add the new fille in csv format](https://user-images.githubusercontent.com/48859058/122656417-dd5b6580-d177-11eb-8b71-fdfb0a6757a1.png)



3. **Click on Teacher Table_1**



![click on taecher tab_1](https://user-images.githubusercontent.com/48859058/122656423-f106cc00-d177-11eb-8afe-afdae8be351b.png)



4. **Click on Teacher Table_2**


![click on taecher tab_2](https://user-images.githubusercontent.com/48859058/122656426-024fd880-d178-11eb-9747-9b94baede78e.png)



5. **Brief Informtion related to Teacher Table**


![brief information related to teacher](https://user-images.githubusercontent.com/48859058/122656435-11368b00-d178-11eb-9a88-d03c9346c1ac.png)







### Thank You



