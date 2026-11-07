Java Lab Record

A collection of Java programs written for my Object-Oriented Programming lab record. Each experiment has an aim, algorithm, source code, sample output, and result in the original record; this repository contains the source code.

Topics Covered
Arrays, searching and sorting
Control statements (if-else, switch)
Strings and basic algorithms
Inheritance and interfaces
Packages
Multithreading
File I/O
Applets and AWT layouts
Experiments
Ex. No.	Title	Concept
1a	Ascending Order	Arrays, sorting
1b	Binary Search	Arrays, searching
1c	Largest and Smallest Number in an Array	Arrays
1d	Print Marks Above 60	Arrays, conditions
2a	Arithmetic Operations	switch case
2b	Even or Odd	switch case
2c	Largest of Three Numbers	if-else-if
2d	Leap Year	if-else
3	String Operations	String methods
4	Armstrong Number	Loops
5	Inheritance	Single, multilevel, hierarchical, multiple, hybrid
6a	Arithmetic Operations using Packages	User-defined packages
6b	Perimeter and Area of Shapes	User-defined packages
7a	Student Details	Inheritance + interface
7b	Volume of Cylinder and Area of Sphere	Interfaces
8a	Multithreading	Thread class
8b	Thread Priority	setPriority()
9a	File Reader	FileReader
9b	File Writer	FileWriter
10a	Drawing a Human Face	Applet, Graphics
10b	Drawing Lines and Rectangles	Applet, Graphics
11a	Grid Layout	Applet, GridLayout
11b	Card Layout	Applet, CardLayout
11c	Border Layout	Applet, BorderLayout
Project Structure
java-lab-record/
├── 01_arrays/          # 1a, 1b, 1c, 1d
├── 02_control/         # 2a, 2b, 2c, 2d
├── 03_strings/
├── 04_armstrong/
├── 05_inheritance/
├── 06_packages/        # 6a (add, sub, mul, div), 6b (shape)
├── 07_interfaces/      # 7a, 7b
├── 08_threads/         # 8a, 8b
├── 09_file_io/         # 9a, 9b
├── 10_applets/         # 10a, 10b
├── 11_layouts/         # 11a, 11b, 11c
└── README.md
Requirements
JDK 8 or later (java -version to check)
A terminal or an IDE such as IntelliJ IDEA, Eclipse, or VS Code
How to Run

Compile and run a normal program:

bash
javac AscendingOrder.java
java AscendingOrder

Programs with packages (6a, 6b), run from the folder that contains the package directories:

bash
javac add/Add.java sub/Sub.java mul/Mul.java div/Div.java ArithDemo.java
java ArithDemo
bash
javac shape/*.java Calculate.java
java Calculate

Applets (10a, 10b, 11a, 11b, 11c):

bash
javac face.java
appletviewer face.java

Note: Applets are deprecated and were removed from modern JDKs (appletviewer is not available after JDK 17). To run them, use JDK 8 (or an older JDK) or an IDE configured with one.

File I/O (9a, 9b): run 9b first to create sample2.txt, then run 9a to read it.

Sample Output

Example for Ex. 1a (Ascending Order):

Enter no. of elements you want in array: 10
Enter all the elements:
2 5 3 4 8 6 0 1 7 9
Ascending Order: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
Author

Name : u.uday kiran 
Reg_number : 11249A391
Department:CSE
College name:SCSVMV

License

This repository is for educational purposes. Feel free to use it for reference, but please write your own programs for your own record.
