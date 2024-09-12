# colllege management system
 
College Class
This repository contains a simple College class written in C++. The class is designed to store and manage information about a college student.

Class Description
The College class has the following attributes:

name: A string representing the name of the student.
mobile_number: An integer representing the mobile number of the student.
email_id: A string representing the email ID of the student.
address: A string representing the address of the student.
city: A string representing the city of the student.
state: A string representing the state of the student.
pincode: An integer representing the pincode of the student.
course: A string representing the course enrolled by the student.
gpa: A float representing the GPA of the student.
The College class has the following methods:

College(): Default constructor for the College class.
College(string n, int mn, string ei, string a, string c, string s, int p, string co, float g): Constructor for the College class that initializes the object with the given values.
getName(): Returns the name of the student.
setName(string n): Sets the name of the student.
getMobileNumber(): Returns the mobile number of the student.
setMobileNumber(int mn): Sets the mobile number of the student.
getEmailId(): Returns the email ID of the student.
setEmailId(string ei): Sets the email ID of the student.
getAddress(): Returns the address of the student.
setAddress(string a): Sets the address of the student.
getCity(): Returns the city of the student.
setCity(string c): Sets the city of the student.
getState(): Returns the state of the student.
setState(string s): Sets the state of the student.
getPincode(): Returns the pincode of the student.
setPincode(int p): Sets the pincode of the student.
getCourse(): Returns the course enrolled by the student.
setCourse(string co): Sets the course enrolled by the student.
getGPA(): Returns the GPA of the student.
setGPA(float g): Sets the GPA of the student.
display(): Displays the information of the student.
calculateAge(): Calculates the age of the student based on the date of birth.
calculateDuration(): Calculates the duration of stay in the college based on the date of admission.
searchStudent(string n): Searches for a student based on the name.
sortStudents(vector<College> students): Sorts the students based on the GPA/CGPA.
writeToFile(string filename): Writes the student data to a file.
readFromFile(string filename): Reads the student data from a file.
Example Usage
![image](https://github.com/user-attachments/assets/21c90606-36f7-4087-aadb-e0e3a7d366b2)

Contributing
We welcome contributions to this repository. Please submit a pull request with your changes.

License
This project is licensed under the MIT License.
