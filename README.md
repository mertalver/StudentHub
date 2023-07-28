# StudentHub
**README - Student Directory Application using Doubly Linked List**

General Problem Description:
Develop a student directory application based on the usage of a doubly linked list data structure to store students' information sorted by student numbers. Below, you will find detailed requirements to implement the Java code that meets these specifications.

Requirements:
1. Create a class named "Student" to represent students. The "Student" class should store student number, full name (adSoyad), and a list of contact phone numbers. Since a student can have multiple phone numbers (e.g., mobile, home, etc.), the phone numbers should be stored in an "ArrayList." The "Student" class should have three constructors (parameterless, with all parameters, and a copy constructor), get/set methods, and a toString method.

2. Write a "Node" class representing a node for the doubly linked list. It should have the necessary fields for the doubly linked list and also contain a variable of type "Student."

Note: You can choose to write the "Node" class separately or as an inner class within the doubly linked list class, as per your preference.

3. Implement the doubly linked list class named "DoublyLinkedList." To take advantage of the benefits of using a doubly linked list, define two variables to represent the head and tail of the list. The following methods should be implemented in the doubly linked list class based on the described options:
   * A method that takes a parameter of the "Student" class and adds the student to the list in ascending order based on their student number.
   * A method that searches for a student in the list based on their full name (ad and soyad). If found, it should print the information of the student(s) with the same name and surname.
   * A deletion method that removes the student with a given student number from the list.
   * A method that prints all records in ascending order of student numbers.
   * A method that prints all records in descending order of student numbers.

Application Options:
The application should provide the following options to the user:
1. Read data from the text file named "ogrenciler.txt" in the format shown below and create the doubly linked list in memory. (Data is separated by commas.)
   Note: The student directory should be created in ascending order based on student numbers, as mentioned before.

   Example content of "ogrenciler.txt":
   ```
   125, Veli Tuz, 0 533 1111111, 0 232 1111111
   112, Ali Can Kara, 0 554 2222222, 0 543 3333333, 0 312 1111111
   144, Canan Demir, 0 216 4444444
   118, Veli Tuz, 0 505 2222222
   102, Ayse Demir, 0 532 6667777, 0 232 2233455
   ... and so on
   ```

2. Allow the user to enter all the details of a student through the keyboard. The student should be added to the list in the appropriate position based on their student number. In other words, insertion should be done in the doubly linked list.

3. Allow the user to enter the name and surname of a student. The application should display the information of the student(s) with the same name and surname, if found.

4. Allow the user to enter a student number. The application should remove the student with the given student number from the doubly linked list.

5. Print all records in ascending order of student numbers.

6. Print all records in descending order of student numbers.

7. Exit the program.
